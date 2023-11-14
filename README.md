# Console-Financ

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