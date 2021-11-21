# Voting System Smart Contract Overview

## Requirements

- [done] Anyone can enroll as a candidate

- [done] Anyone can vote one time for one of the candidate, the candidate must be enrolled in order to vote. Each vote is secret so we don't request any information to the voter, we only have their address to identify them

- [done] View amount of votes there are by candidate

- [done] View candidates enrolled

- [done] View who is the winner of the voting

Considerations: A hash consumes less space than an address or any other data type. Use the name as the candidate identifier, but only for simplicity of the example.

## Sample Data

| CANDIDATE NAME | ID | AGE |
| ----------- | ----------- | ----------- |
Marcos |    77755N    |      20
Joan   |    12345X    |      23
Maria  |    02468T    |      21
Marta  |    13579U    |      19
Alba   |    98765Z    |      50
