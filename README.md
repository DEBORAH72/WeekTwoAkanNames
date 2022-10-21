# WHAT IS YOUR AKAN NAMES .
#### Most people dont know their DAY of birth hence reason to get Akan names as they know day of birth in Ghana, {06 October 2022}
#### Courtesy of: -
{James and Jensen.W,Deborah
and Safaricom Digital Academy}
## Description
#### https://DEBORAH72.github.io/WeekTwoAkanNames/index.html
# Akan Calculator
#### Calculates a user's day of birth and assigns an Akan name based on gender
#### October 8,2022
#### By *Deborah M Muthiani*
## Description
Akan Calculator is exactly what its name suggests — a calculator. The project is a website that takes a user's birthday as input and calculates which day of the week they were born. The website then assigns the user an Akan name based on their gender, and displays this information on the user's screen. The site has three pages — the home page, the steps page, and the list of Akan names.

### Homepage
![Home Page](img/home.png)
![Home Page](img/mobile.png)

The homepage acts like a landing page, displaying a short introduction to Akan naming. On it, there is a link to an Akan names list and a button to the calculator. The list is a simple page that contains all the male and female Akan names according to the days of the week.

### Steps page
![Date Page](img/steps.png)

The steps page carries the user through three steps. The first step takes in the user's birthday. If an invalid date is entered, it brings up an error message on the page asking the user to enter a valid date. This step also accounts for leap years. By definition, a leap year is divisible by 4. It is not a leap year if it is divisible by 100, unless it is also divisible by 400. Using this knowledge, the web app can make sure that a proper date is entered, and will alert the user if a date above 28th of February is entered on a non-leap year. Simply put, the page will bring up an error if the date entered exceeds the number of days in a given month.

![Error Page](img/steps2.png)

After submitting their date of birth, the user clicks on a button that takes them to the next step. Here, the user selects a gender, either male or female. If no option is selected, the user recieves an error message.

![Gender Page](img/steps3.png)

On the next step, the user gets to see their Akan, as well as the day on which they were born. There is a reset button that clears all the forms and returns the user to the first step.

![Name Page](img/steps4.png)

All the steps are on one HTML file. Whenever the user clicks the "Continue" button, the current `<div>` is hidden and the next one is revealed. This is done by simply toggling the `display` property in CSS through JavaScript. By keeping all the steps on one HTML file, none of the data stored in the JavaScript variables is lost.


## Setup/Installation Requirements
 The application should check whether the date and month entered is valid.


        -Open the code with VSCode
        -Enter dates that are valid as per the annual calender
        - Go Live
To use the web app, go to this link. All you will need is a web browser. The website is screen-responsive, so you can use it easily on a mobile device or tablet.

If you would like to edit the page or customize it, you will need to install a code editor, preferably Visual Studio Code.
         

This application should output to the user their Akan name depending on their gender. For example, if a user is male and the result of the calculation is 0, then the application should match that with Kwasi since Kwasi corresponds to Sunday which has an index 0. Hence the output the user will see should be something like “Your Akan name is Kwasi”
## Known Bugs
As I hand over this project there are no known bugs but are many options on how to derive to this solution under different programs and codes.
## Technologies Used
* CSS
* Java script
* Html
* Gitbash
## live link
https://DEBORAH72.github.io/week-two-akan-names

## Support and contact details
Every programmer hopes their program runs error free but incase the bug strikes ,just refresh the page and form again and you should be good to go.
* For any issues or questions, ideas or concerns.Kindly contact DEBZ CREATIONS under info@debzcreations.org or + 25470056783 .Your free to make a contribution to the code.}
### License

Copyright (c) {2022} **{BY DEBBY CREATIONS}**