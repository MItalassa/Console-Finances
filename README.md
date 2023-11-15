# Console-Finance


## Description

Code for analyzing the financial records of a company.


## How to access the analysis:

Open the URL in Google Chrome browser, right-click with your mouse and select "Inspect" from the menu to acces "Developer Tools" and interact with the console.

## Detailed changes in the code
- To show the number of months taken in analysis, I used the array.length property of the finances array.
- For the Total Net amount over the entire period, I used a "for Loop" to make a sum of each element of the finances array.
- To find the average of changes in Profit/Losses over the entire period, I created two "for Loops": the first to calculate the difference between each elements of the array and the second one to have the sum of all those differences.
- To show the month with the biggest profit and the one with the biggest loss, I've created a for Loop with 2 conditions.

![Alt text](./images/Screenshot%202023-11-14%20234207.png)

## Credits

Website used as reference:
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays
https://www.turing.com/kb/guide-to-string-concatenation-in-js
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/max
https://www.youtube.com/watch?v=Fhgbgv5Gf0Q

N.B.:
As I was struggling with a few steps for criteria 3 and 4-5, during my last tutor session with Dennis Itua we went over this challenge.
The following is the code I created during my tutor session:
---
TUTOR SOLUTION
// The average of the changes in Profit/Losses over the entire period.

// // *The greatest increase and decrease in profits (date and amount) over the entire period.*

// var months = finances.length;
// var total = 0;
// var change = 0;
// var average;
// var analysisResult;
// var previousAmount = 0;
// var netChangeSum = 0;
// var least = ["", 9999999999999];
// var greatest = ["", 0];
// var currenthMonth;
// var date;
// var amount;

// for (let i = 0; i < finances.length; i++) {
//   currenthMonth = finances[i];
//   date = currenthMonth[0];
//   amount = currenthMonth[1];
//   total += amount;

//   if (i > 0) {
//     change = amount - previousAmount;
//   }

//   previousAmount = amount;
//   netChangeSum += change;

//   if (change > greatest[1]) {
//     greatest = [date, change]
//   }

//   if (change < least[1]) {
//     least = [date, change]
//   }
// }

// average= Math.round((netChangeSum / (finances.length - 1))*100)/100;

// analysisResult=   'Financial Analysis ' +
// '\n' +
// '----------------' +
// '\n' +
// 'Total Months: ' +
// months +
// '\n' +
// 'Total: $' +
// total +
// '\n' +
// 'Average Change: ' +
// average +
// '\n' +
// 'Greatest Increase in Profits/Losses: ' +
// greatest[0] +
// ' ($' +
// greatest[1] +
// ')\n' +
// 'Greatest Decrease in Profits/Losses: ' +
// least[0] +
// ' ($' +
// least[1] +
// ')';

// console.log(analysisResult)


Since I wasn't comfortable with the above solution as in many points is above what I deemed my level of knowledge at the moment, I preferred finding a more personal solution.
## License

N/A