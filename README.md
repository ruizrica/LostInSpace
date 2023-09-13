# Lost in Space: Code Your Way Back Home

---

#### Introduction:
Welcome to an exciting 2-hour lab experience! You are a crew member aboard the spaceship "CodeRunner," which is lost in a galaxy far, far away due to a navigation system failure. To get back to Earth, you'll need to solve a series of coding challenges using JavaScript. Are you ready to embark on this adventurous journey? Let's start!

---

### Section 1: Power Up The Spacecraft

#### Time: 30 Minutes

#### Storyline:
The "CodeRunner" spaceship is out of power! The first task in getting yourself back home is to restart the ship's power generator. The generator is coded to restart when a specific sequence of codes is executed. You'll need to find that sequence and initiate the power-up sequence.

#### Objectives:
1. Initialize the spaceship's systems.
2. Generate the secret sequence code required for starting the power generator.
3. Validate the generated sequence and restart the power generator.

#### Challenge 1: Initialize the Spaceship Systems

You need to define a JavaScript object to simulate the spaceship's systems.

```javascript
const spaceship = {
  powerGenerator: false,
  navigationSystem: false,
  communicationSystem: false
};
```

#### Challenge 2: Generate Secret Sequence

Write a function that returns a random sequence of numbers between 1 and 10. This sequence will be the "key" to restarting the power generator.

```javascript
function generateSequence() {
  // Your code here
}
```

#### Challenge 3: Validate Sequence and Restart Generator

Write another function that takes a sequence as an argument. If the sequence matches the secret sequence, set `powerGenerator` to `true`.

```javascript
function validateSequence(sequence) {
  // Your code here
}
```

#### Challenge 4: Test Your Code

Now, generate a secret sequence and use your validate function to restart the power generator.

```javascript
const secretSequence = generateSequence();
console.log("Secret Sequence Generated: ", secretSequence);

validateSequence(secretSequence);
console.log("Current Spaceship Status: ", spaceship);
```

#### Bonus:

1. Add more complexity to the secret sequence generator.
2. Add a countdown timer that simulates the urgency of restarting the generator.

---

Once you successfully complete Section 1, your spaceship's power generator will restart, enabling you to proceed to Section 2, where you'll work on the navigation system.

Remember, time is of the essence, and you have to get back home!

---

[Next Level](https://github.com/ruizrica/LostInSpace/blob/main/part2.md)https://github.com/ruizrica/LostInSpace/blob/main/part2.md
