# AKQA Tech Challenge
###### *The application takes name and number and converts number to words*


###### **_Project Design and Teckstack used_**

The solution is developed using ASP.Net MVC 5 framework.

The solution consists of 

1) AKQATechChallenge

   AKQATechChallenge has UI and API to call the number to words conversion service

2) AKQATechChallenge.Service

   AKQATechChallenge.Service converts the given double number to words and return the words	

3) AKQATechChallenge.Test

   AKQATechChallenge.Test is xUnit Test project and has 12 xUnit tests to test the given double number is converted to words as expected

UI is developed using ASP.Net MVC, html, css, bootstrap and jQuery.
UI has input box for name and number and a submit button.
On Sumbit button click, Ajax call is made to API passing the number.
API calls Service method to convert the number passed to words. The service method returns the number converted to words.

###### **_Application Assumptions, Limitations_**

The maximum value of the number accepted is 100 billion

###### **_How to run the application_**

1) Clone the repository
2) Build the solution
3) Start the project or press F5
4) UI having input box for name and number and a submit button will be displayed in Index.chtml page
5) Enter the name and number and click submit button
6) The name and words are displayed on the page below the input

