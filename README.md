We will automate tests on Make My Trip to verify URLs, and get flight details from two destinations. Additionally, we will compare the flight details obtained. These tests will ensure the functionality and accuracy of the Make My Trip website.

You will be primarily working with TestCases.java and appending your test cases to App.java which is the entry point for your automation code.



TestCase01: Verify Make My Trip Homepage URL
Description: Verify that the Make My Trip homepage URL contains "makemytrip."

Test Steps:

Navigate to the Make My Trip website ( https://www.makemytrip.com/ ).

Verify that the URL contains "MakeMyTrip."

Expected Result: The URL of the Make My Trip homepage contains "MakeMyTrip."
TestCase02: Get Flight Details from Bangalore to New Delhi
Description: Get flight details for a specific route and date.

Test Steps:

Select BLR(Bangalore) as the departure location.

Select DEL(New Delhi) as the arrival location.

Select the correct date (29th of next Month).

Click on the search button.

Store the flight price (per adult).

TestCase03: Get Train Details from Bangalore to New Delhi
Description: Get train details for a specific route and date.

Test Steps:

Select YPR(Bangalore) as the departure location for the train.

Select NDLS(New Delhi) as the arrival location for the train.

Select the correct date (29th of next Month) for the train.

Select the class as 3AC

Click on the search button for the train.

Store the train price for 3AC.

Expected Result: The correct train details are obtained.
TestCase04: Verify that there are no buses from Bangalore to Kathmandu
**Description: **Verify that no buses are found for a specific route and date.

Test Steps:

Select Bangalore(search for bangl) as the departure location for buses.

Select Kathmandu(search for kathma) as the arrival location for buses.

Select the correct date (29th of next Month) for buses.

Click on the search button for buses.

Verify that text displayed contains No buses found for 29th of next Month.
