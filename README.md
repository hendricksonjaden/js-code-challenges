<!-- # ES6 Starter Project

## Instructions after generating the project

- Change into the directory and run `npm install` to install the dependencies
- Add initial code to the src/bootstrap.js file, it will be the root file for your ES6 projects
- Run `npm start`
- Visit localhost:3000 in the browser and you should see the running application. If you are running console log statements they will appear in the browser's JS console.


> Provided for the students of the [Bottega Code School](https://bottega.tech/)

*Fork from [es6-webpack2-starter](https://github.com/micooz/es6-webpack2-starter)* -->


# Homework 02-12
### Git and Github
### Code Challenge:
- Inside your bootstrap.js file create three functions
- Write three functions that compute the sum of the numbers in an array: using a for-loop, a while loop, do-while loop.
- Push your code up to github
### Friendly Code Snippet Reminders:
```
$ git status
$ git add .
$ git commit -m "your commit msg"
$ git push


// Function Expression
const summingTool = function(numbers) {
    let sum = 0
    for (let i = 0; i < numbers.length; i++) {
      sum += numbers[i]
    }
    return sum
}
console.log(summingTool([1, 2, 3, 4, 5, 6]))
// Arrow Function
// const summingTool = (numbers) => {
//     let sum = 0
//     for (let i = 0; i < numbers.length; i++) {
//       sum += numbers[i]
//     }
//     return sum
// }
// console.log(summingTool([1, 2, 3, 4, 5, 6]))
// Function Declaration
// function summingTool(numbers) {
//     let sum = 0
//     for (let i = 0; i < numbers.length; i++) {
//       sum += numbers[i]
//     }
//     return sum
// }
// console.log(summingTool([1, 2, 3, 4, 5, 6]))
// Not dynamic function expression
// function summingTool() {
//     let numbers = [1, 2, 3, 4, 5]
//     let sum = 0
//     for (let i = 0; i < numbers.length; i++) {
//         debugger
//       sum += numbers[i]
//     }
//     console.log(sum)
// }

// summingTool()