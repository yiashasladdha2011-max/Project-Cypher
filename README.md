
# PROJECT CYPHER

### CY-01 — Morse-Based Message Encoding System

Project Cypher is a lightweight message encoding and decoding system that combines alphabet shifting with International Morse code.

It converts ordinary messages into Morse-based codes that can be shared through messaging platforms such as WhatsApp.

## How It Works

Cypher uses a multi-stage encoding process.

### 1. Enter a Message
The sender enters an ordinary message, such as:

`Hello, Friend!`

### 2. Choose a Shift Value
The sender chooses a positive or negative shift.

Example: `-11`

### 3. Encode the Shift
The numerical shift is converted into an alphabet letter.

For example:
- 11 = K
- Negative sign = N
- Positive sign = P

The sign and letter are then converted into Morse code and placed in the final header.

### 4. Shift the Message
Alphabetic characters move according to the selected shift value.

For example, with a shift of +4:

`HELLO` becomes `LIPPS`

The alphabet wraps around after Z.

### 5. Convert to Morse Code
The shifted message is converted into International Morse code.

Special control markers preserve:
- Uppercase and lowercase
- Spaces
- Line breaks

Numbers and punctuation use their Morse representations.

### 6. Generate the Final Code
The Morse message and encoded shift header are combined into one code.

### 7. Decode the Message
The receiver pastes the code into the decoder.

Cypher automatically:
1. Reads the Morse header.
2. Recovers the shift value.
3. Converts the main Morse message into characters.
4. Reverses the alphabet shift.
5. Displays the original message.

## Features

- Automatic shift detection
- Positive and negative shifts
- Uppercase and lowercase support
- Numbers and punctuation
- Spaces and paragraphs
- Copy-and-paste support
- Lightweight, single-file application
- No installation required

## Technology

- HTML
- CSS
- JavaScript
- International Morse Code

## Important Note

Project Cypher is an educational encoding system, not secure encryption. Its encoding rules are reversible and should not be used to protect sensitive information.

---

**Created as a personal coding project.**

*PROJECT CYPHER · CY-02*
