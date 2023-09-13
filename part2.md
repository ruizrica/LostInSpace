## Lost in Space - Section 2: Navigational Woes

---

#### Time: 30 Minutes

#### Storyline:
Great job restarting the power generator! Now that you've got power, it's time to fix the navigation system. The coordinates to Earth are stored in a data vault that's encrypted. To decrypt it, you'll need to solve a series of JavaScript challenges.

#### Objectives:
1. Retrieve the encrypted coordinates.
2. Decrypt the coordinates using JavaScript algorithms.
3. Initialize the navigation system with the decrypted coordinates.

---

#### Challenge 1: Retrieve Encrypted Coordinates

Create a function to simulate retrieving encrypted coordinates. For the sake of this exercise, let the encrypted coordinates be an array of numbers.

```javascript
function retrieveEncryptedCoordinates() {
  return [12, 34, 56, 78, 90]; // This is a mock of encrypted coordinates
}
```

---

#### Challenge 2: Decrypt the Coordinates

Write a function to decrypt the coordinates. The encryption algorithm simply doubled each coordinate and added 1. Your task is to reverse the encryption.

```javascript
function decryptCoordinates(encryptedCoordinates) {
  // Your code here
}
```

---

#### Challenge 3: Initialize Navigation System

Create a function to initialize the navigation system with the decrypted coordinates.

```javascript
function initializeNavigation(decryptedCoordinates) {
  spaceship.navigationSystem = true;
  // Also, store the decrypted coordinates for future use
}
```

---

#### Challenge 4: Test Your Code

Finally, test all your functions to make sure the spaceship's navigation system is up and running.

```javascript
const encryptedCoordinates = retrieveEncryptedCoordinates();
console.log("Encrypted Coordinates: ", encryptedCoordinates);

const decryptedCoordinates = decryptCoordinates(encryptedCoordinates);
console.log("Decrypted Coordinates: ", decryptedCoordinates);

initializeNavigation(decryptedCoordinates);
console.log("Current Spaceship Status: ", spaceship);
```

---

#### Bonus:

1. Make the encryption and decryption algorithms more complex.
2. Simulate real-time data retrieval for the coordinates, perhaps using a setTimeout function.

---

Congratulations! With the navigation system initialized, you can now proceed to Section 3 where you'll work on the spaceship's communication system, a crucial step for calling home.

[Next](https://github.com/ruizrica/LostInSpace/blob/main/part3.md)
