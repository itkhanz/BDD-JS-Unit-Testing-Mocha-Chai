# JavaScript Unit Testing with Mocha and Chai | BDD

-   Run the `npm init -y` to setup a basic project template.
-   Run the `npm install --save-dev mocha chai` to insall the them as development dependencies.
-   You can run any test file with the `mocha <filename>` command in console.
-   change the test script in package.json to mocha
-   Mocha recommends the test cases to be stored in a **test** folder which is located in the same directory where package.json
-   you can run now all the tests within this **test** folder by running `npm test`

---

## Battleship game engine Test Suite

Each player places ships randomly in their own grid, and try to guess the position of opponent's ships in their grid. If the guess is correct, the point is marked hit, and after the ship is hit at all its length it will be sunken. The first player to sink all the opponent's ships will be declared winner.

1. Current player and winner
2. Number of ships
3. Position of ships
4. Status as active or sunk

We will use BDD to breakdown all of the requirements into small chunks.
