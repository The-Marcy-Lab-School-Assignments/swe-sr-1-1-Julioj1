# swe-sr-1-1

Welcome to your first short response assignment! If the code that you write is what gets your foot in the door for a job interview, how you communicate is what will get you the job. So, treat these assignments seriously! Write your responses as if you were planning on publishing them in a blog for the world to see (and, if you're confident, actually publish them!).

## Setup

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

Here are some useful commands to remember.

```sh
npm i                   # install dependencies
git checkout -b draft   # switch to the draft branch before starting

git add -A              # add a changed file to the staging area
git commit -m 'message' # create a commit with the changes
git push                # push the new commit to the remote repo
```

## Prompt

Imagine you are teaching a brand new programmer a brief lesson about functions and function calls. Your lesson should have the following components:

* A technical definition ("According to MDN, a function is...").
* An explanation of the concept with an analogy ("You can think of a function a ...")
* An example of the syntax for an arrow function using a JavaScript code block (triple backticks)
* An explanation of the syntax using the terms **arrow function**, **parameter**, **code block**, **return statement**, and **call/invoke**.

Below, we've provided an outline for your response but feel free to modify it as you see fit.

### Response

According to MDN, a function in JavaScript is a set of statements that performs a task or calculates a value. It is one of the fundamental building blocks in JavaScript. For a procedure to qualify as a function, it should typically take some input and return an output, exhibiting a clear relationship between the input and output. To utilize a function, it must be defined within the scope from which it is intended to be called.

You can think of a function like a tool you can use to automate a task instead of writing a block of code every time you want to do this task you can call the function to do it, it makes it way easier and faster.
[Replace with your explanation of the concept with an analogy]

Check out this example:

```js
// Add your example here
const loopUpToNum = (num) => {
  if (num >= 0) {
    for (let i = 0; i < num; i++) {
      console.log(i);
    }
  } else if (num <= 0) {
    for (let i = 0; i > num; i--) {
      console.log(i);
    }
  }
};
```

[Replace with your explanation of the example and explanation of the syntax]
