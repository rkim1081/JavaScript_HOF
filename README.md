# JavaScript Higher-Order Functions

## Getting Started

1. Open your command line and navigate to your `repos` directory (if you do not have a `repos` folder, then you can use `mkdir repos` to create one)
2. Use this template repository to start a new project in your repos folder: `git clone <repo_name>`
3. cd `repo_name` to navigate into your new repo directory
4. Start Visual Studio Code and select 'Open Folder'. Then select `repo_name` to open the folder in the editor (or just type `code .` in your terminal inside the repo directory)
5. Follow the instructions on the README.md file to complete exercises
6. Open the app.js file to get started

## Exercise 1

- Write a function that takes in a number parameter and returns a function that adds the number parameter with a new number parameter.

1. Declare a function `plus` that takes in a `number` parameter.
2. Inside the body of `plus`, use the `return` keyword to return an anonymous function
3. The return function will take in a `plusNumber` parameter, and return the value of `plusNumber` with the first parameter `number`
4. Next, declare a variable `plus15` that is assigned the value of `plus` with 15 passed in
5. `console.log` the result of `plus15` with 10 passed in

End result should resemble: `console.log(plus15(10)) // Outputs 25`
