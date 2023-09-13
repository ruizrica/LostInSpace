##Lost in Space - Section 3: Communication Breakdown

---

#### Time: 30 Minutes

#### Storyline:
You've managed to bring power back to the ship and re-establish the navigation system. Fantastic work! However, you're not out of the woods yet. Your communication system is down, and you'll need to establish a link with Earth to ensure a safe return.

#### Objectives:
1. Inspect the communication system's status.
2. Encode a distress message.
3. Transmit the encoded distress message.
4. Decode a response from Earth.

---

#### Challenge 1: Inspect Communication System

Before doing anything else, you need to find out why the communication system is down. Let's start by checking its status.

```javascript
function checkCommunicationSystem() {
  // Your code to check the system's status
}
```

---

#### Challenge 2: Encode a Distress Message

Write a function to encode a distress message that you'll send to Earth. This function should replace each letter with its ASCII code.

```javascript
function encodeMessage(message) {
  // Your code here
}
```

---

#### Challenge 3: Transmit the Encoded Message

Simulate the transmission of your encoded message.

```javascript
function transmitMessage(encodedMessage) {
  spaceship.communicationSystem = true;
  // Code to transmit the message
}
```

---

#### Challenge 4: Decode Earth's Response

Imagine that Earth has received your distress signal and has responded. You will receive an encoded message that you need to decode. Write a function to do this.

```javascript
function decodeResponse(encodedResponse) {
  // Your code here
}
```

---

#### Challenge 5: Test Your Code

Put it all together to make sure everything works as expected.

```javascript
checkCommunicationSystem();

const message = "SOS";
const encodedMessage = encodeMessage(message);
console.log("Encoded Message: ", encodedMessage);

transmitMessage(encodedMessage);
console.log("Current Spaceship Status: ", spaceship);

const encodedResponse = "6973207468697320776F726B696E673F"; // Is this working?
const decodedResponse = decodeResponse(encodedResponse);
console.log("Decoded Earth's Response: ", decodedResponse);
```

---

#### Bonus:
1. Add data validation checks in the message encoding and decoding functions.
2. Simulate network latency using `setTimeout` when transmitting the message and receiving the response.

---

You're nearly there! With the communication system back online, Earth has been alerted about your situation. In the next and final section, you will prepare for re-entry into Earth's atmosphere.

Would you like to move on to the final section?
