## Computational Thinking
- Computer science is all about problem solving
- In essence, you break down problems by having an input and a desired output
- Computational thinking entails the approach in which you go about this, i.e, how do you solve the problem of how to find a letter in a string for example.


## Binary
- There are many ways to represent these inputs, outputs:
  There's unary (digits, base1), binary (bits, base2, what computers work off of), ternary (base3), decimal (base10, what we use), and more
  
- Binary consists of 0s and 1s
- The reason why computers use binary, is because of transistors
- Computers contain transistors, switches that can be either on or off. So, the closed transistor would represent 0, opened would represent 1

- To count higher than 1, multiple bits must be used

- You'll see powers of 2 a lot in computers/programming
- Ternary computers exist but it's much harder to be precise with them

## ASCII:
- ASCII is a character set, consisting of english letters, numbers and symbols.
- Each character within character sets has a unique binary value allocated to it.
- For instance, binary value 65 would represent the uppercase letter A, the values are contiguous, meaning uppercase B would be 66, and so on and so forth.
- ASCII uses 8 bits per character (a byte per character), so a 3 letter string "HI!" would contain 3 bytes, or 24 bits.
- 8 bits can represent 256 different binary values (2^8), therefore, ASCII can only represent a maximum of 256 different letters and symbols.
  
## Unicode
- The newer standard
- We require more than 256 characters, as there are many different languages, and symbols to be represented
- So, by using 32 bits (4 bytes) per character instead, there is now a whopping 4 billion possible unique characters, which allows for emojis to be represented, different languages and a variety of diverse symbols.
- Unicode is backwards compatible with ASCII, meaning the already defined characters such as A, B, C... have the same binary value allocated to it.

## Color
- Each pixel on a screen has a number of bits telling the device what colour the pixel should represent.
- 3 numbers are required (so 3 bytes) to represent RGB (0-255,0-255,0-255), 24 bits per pixel

## Videos
- Not continuous motion
- By displaying a certain number of images per second, the illusion of a continuous motion is created
- ..much like how a flipboko animation operates

## Sound
- The pitch, volume and duration are all measured and stored as binary values (each have a byte), and represent the note the sound would make at the current position within the soundtrack

## Algorithms
- Algorithms determine how exactly you get from your inputs to your desired output
- They're essentially step by step instructions in order to solve a problem

## Code
- Code is what is used by programmers to implement algorithms
- There are many different languages
- A boolean expression refers to a comparison where the answer is true or false

## AI
- You can hard-code a chat bot, by individually programming each response to each possible question
- So for example,
  if question = "how are you"
   output "good"
  else if question = "hello"
   output "hello"
- However, this process is arduous and invariable impractical
- Thus, AI companies create LLMs (Large Language Models), where the model is trained off a large data set
- It functions off a neural network and produces the most likely answer to the prompt by using probability calculations and statistics

## Scratch / rudimentary programming concepts
- Return value: a value that a function returns back when the function is called
- Abstraction: languages are often built to contain very little built in functions, you are left to invent your own functions. This is done in order to reduce the time it takes to translate the code into machine code.
