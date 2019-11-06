

## Task 1.
  #### Write a function that checks whether the JS object contains a target object:

  ```js
  const Store = {
    prop1: { prop1: 1 },
    prop2: function() {},
    prop3: {
      prop1: {
        prop1: {
          prop1: [0, 1, { prop1: “Hello” }],
          prop2: target,
          prop3: {
            prop1: Math.random
          }
        }
      }
    }
  }
  console.log(contains(Store, target)) // true
  console.log(contains(Store, “Hello”)) // true
  console.log(contains(Store, Object)) // false

  ```

## Task 2
  #### The ATM issues banknotes of 100, 500, 1000 and 5000 dram, while, if possible, larger denomination banknotes are used. Write a function that takes the amount you want to withdraw and calculates how many bills of any denomination required to issue.



## Task 3
  #### Write an implementation of the `age-count.js` module that will work as follows. 
  Note: ageCount is not a variable and there are no errors in this code.


  ```js
  import ageCount from './age-count.js'

  for (let i = 0; i < 3; i++)
    console.log(`My age is ${ageCount}`)

  // Output Results
  >> My age is 1
  >> My age is 2
  >> My age is 3

  ```

## Task 4

  #### The purpose of this project is to give candidates the opportunity to showcase their skills using React, JavaScript, and overall Application Development.

  ## Overview

  The application that candidates must complete will be a simple, generic score leaderboard, letting its users display, add, remove, and edit players.

  Candidates should write clean, declarative, and functional code and abide by good design principles.

  ## Requirements

  * Application must be written in React.

  * The application must support the following main features:
    * Have a form so users can add/edit players. The form must include the following three fields: `firstName:String`, `lastName:String`, `score:Integer[0,100]`
    * Display the leaderboard in a tabular format sorted by `score`, and `lastName` in ASCENDING order. Therefore, if two players have the same `score`, the sorting will fall back to `lastName`
    * The names displayed on the leaderboard should be combined into one field when displaying as such: `lastName, firstName`
    * Have the ability to remove players by clicking a `Delete` button in the leaderboard.

  ### Sample leaderboard design:

  | Name          | Score |        |
  | ------------- | ----- | ------ |
  | Geary, Alice  | 96    | Delete |
  | Junge, John   | 96    | Delete |
  | Vera, Rob     | 88    | Delete |

  ## Submitting the project
   * Candidate should create a new repo for this project on their own GitHub account
   * Complete application
   * Deploy application to a production environment
   * Notify intent.ai contact that repo is ready for review, providing both URLs to the repo and running app

  ## Bonus

  It's encouraged that candidates add additional and reasonable features to the leaderboard to contribute to its function. Similarly, candidates should feel free to include more advanced programming techniques and concepts of their particular interests. Example. TypeScript, TDD.
