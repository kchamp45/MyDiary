# My Diary

#### Today's Progress Report, 09/29/2017

#### By **Kimberly H. Lu**

[Github repository](https://github.com/kchamp45/myDiary)

Here is a summary of what I have been doing for the last 8 hours today.
1. Practice possible interview coding questions.
 ![app-screenshot](https://github.com/kchamp45/MyDiary/blob/master/images/Questions.png?raw=true)
2. A ton of research in preparation for a financial website I would like to create.  
  ### User stories:
    * I want to know the average salary of my chosen profession (e.g. jr. software developer).
    * I want to know my expenses, including cost of living and taxes I have to pay, in a particular city.    
      *I want a break down of my expenses so I know where to focus to increase my savings effectively.
      *Given tax rates based on status, I want to know whether I would save more if I stay single or marry my significant other.
    * I want to know where I should invest the money that I save to increase my net worth.
      * I want to know the investment's expenses, average rate of return, minimum balance.
      * I want to know the company administering this investment's website, contact info, and ratings.
    * I want to know how much money I will have at the end of a chosen number of years given my initial amount of investment, rate of return, and amount I will add to the account plus the frequency with which I will contribute.  
    * I want to know about other possible financial options (e.g. 401K, Roth IRA, Real Estate(e.g. house-flipping, rental or just REIT) available to me to take advantage of the number of years I have to invest and my current income bracket (because some investment advantages go away if I make too much money--says Uncle Sam).
### Salary:
![app-screenshot](https://github.com/kchamp45/MyDiary/blob/master/images/Salary.png?raw=true)

### Salary in Portland:
![app-screenshot](https://github.com/kchamp45/MyDiary/blob/master/images/Portland%20Salary.png?raw=true)

### Tax Table:
![app-screenshot](https://github.com/kchamp45/MyDiary/blob/master/images/Fed%20Tax%20Rate.png?raw=true)

### API:
![app-screenshot](https://github.com/kchamp45/MyDiary/blob/master/images/API.png?raw=true)

### Investments:
![app-screenshot](https://github.com/kchamp45/MyDiary/blob/master/images/Funds.png?raw=true)

### Calculator:
![app-screenshot](https://github.com/kchamp45/MyDiary/blob/master/images/Calculator.png?raw=true)

### Math notes:
![app-screenshot](https://github.com/kchamp45/MyDiary/blob/master/images/MathNotes.JPG?raw=true)

  ### Strategies to satisfy user stories:
  I hope to get data via API calls as well as create my own database either with SQL or Firebase.  Being a math junkie, I am determined to create the right mathematical formula to calculate the account value after x number of years of investment.   

## Setup/Installation Requirements

To use my future application, you will need to do the following.  In the terminal, please navigate to your desktop and execute:
  * `$ git clone https://github.com/kchamp45/future-project-name`
  * `$ npm install`
  * `$ bower install`
  * `$ gulp build`
  * `$ gulp serve`
For this application, just open the github and enjoy the ReadMe.  

## Known Bugs

I pray for none, but I have been trained to find and squash them if necessary.

## Technologies I hope to employ

Javascript, Typescript, Angular JS, HTML, and CSS.  Supporting libraries from Bootstrap and JQuery were employed as needed.


## Specs

| Behaviour  | Input | Output |
| ------------- |:-------------:| -----|
| display user's salary, income tax amount, cost of living| select "profile" | Display said info |
| display tax rate, personal exemption, standard deduction | select "tax" | display said info|
| display a breakdown of the cost of living | select "cost of living" | percentage towards housing, food, clothing, and transportation|
| display list of possible mutual fund investments | user navigates to "investment suggestion" | The app displays the mutual funds. |
| update mutual fund lists | enter said information | the information of said fund is updated |
| add new mutual fund to the list | enter information about the funds | the fund is recorded|
| delete a mutual fund from the list | select "delete"| fund is removed|
| filter through the records and display funds based on rate of return or minimum balance | Display only said funds that meet the user's selection |
| filter the records based on administering company's ratings| select "rating"| show only companies that meet the chosen rating|
| display list of other investment options| select "more options"| display list of options|
| display more informations about said options| select the investment option| display details like explanation of the investment, requirements, advantages, and links to additional resources|

### License

Published under MIT License.

Copyright (c) 2017 **_Kimberly H. Lu_**
