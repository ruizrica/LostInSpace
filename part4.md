## Lost in Space - Section 4: Re-Entry Protocol

---

#### Time: 30 Minutes

#### Storyline:
You've done an amazing job so far! Power is restored, navigation is set, and communications are back online. Now comes the final challenge: initiating a re-entry protocol to safely land back on Earth. This requires some advanced calculations and checks.

#### Objectives:
1. Calculate the re-entry trajectory.
2. Verify ship's integrity.
3. Initiate re-entry sequence.
4. Land safely on Earth.

---

#### Challenge 1: Calculate Re-entry Trajectory

You need to calculate the correct re-entry angle to ensure a smooth landing back on Earth. Write a function to do this.

```javascript
function calculateReentryAngle(currentAltitude, targetAltitude) {
  // Your code here
}
```

---

#### Challenge 2: Verify Ship's Integrity

Before attempting re-entry, it's crucial to verify that the ship's systems are all functioning correctly. Create a function to run these checks.

```javascript
function verifyIntegrity() {
  // Your code here
}
```

---

#### Challenge 3: Initiate Re-entry Sequence

Time to put it all together. If all systems are functional and the re-entry angle is correct, you can initiate the re-entry sequence.

```javascript
function initiateReentry() {
  // Your code here
}
```

---

#### Challenge 4: Test Your Code

Wrap it all up by running your functions and verifying that you've successfully made it back to Earth.

```javascript
const reentryAngle = calculateReentryAngle(2000, 400);
console.log("Calculated Re-entry Angle: ", reentryAngle);

const isShipIntegrityOk = verifyIntegrity();
console.log("Ship Integrity Verification: ", isShipIntegrityOk);

if (isShipIntegrityOk) {
  initiateReentry();
  console.log("Successfully Landed on Earth!");
} else {
  console.log("Re-entry Failed. Mission Aborted.");
}
```

---

#### Bonus:

1. Simulate re-entry failures and how to handle them in code.
2. Add a countdown timer to simulate the urgency of the re-entry sequence.

---

#### Lab Wrap-up:

Congratulations, astronaut-coder! You've successfully navigated through an array of challenges in an unfamiliar galaxy. Your coding skills have powered up the spaceship, set the course, communicated with Earth, and brought you safely back home.

Would you like to review any of the sections, or do you have any questions about the lab?
