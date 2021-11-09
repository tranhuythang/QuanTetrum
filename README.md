# QuanTetrum
QuanTetrum is a Tetris-inspired game that illustrates 3 important concepts of Quantum physics: superposition, entanglement, and measurement.

(This game was made in the Quantum Game Hackathon 2021 of Quantum Artificial Intelligence Foundation (qaif.org))

![Hackathon](/Hackathon2021_diploma_2.jpg)

# How to run:
You can run the game directly at [this link](https://htmlpreview.github.io/?https://github.com/tranhuythang/QuanTetrum/blob/main/index.html)

Or you can download the game's source code and just run the index.html file.


# Rule:

- Player is suppose to strategically move and rotate falling tetrominos, as well as transforming the state of individual blocks in the  tetromino so that at least 7 blocks in a row have a same arrow direction for socring a row.  

- Each tetromino carries 4 blocks. Each block is in one of the 3 states (―), or ( | ), or (＋) and can possibly be entangled (paired) with another block. You score points by placing at least 7 blocks of the same state (―) or ( | ) in a row to make that row deleted. Your goal is to delete as many rows as you can. The game will end when the blocks fill ups the board.

- To move a descending tetromino, use the keyboard: left (LEFT), right (RIGHT), down (DOWN or SPACEBAR). To rotate a tetromino, use the UP key.

- When a tetromino descends on the board, you can transform the Quantum state of each block by clicking on the corresponding operation on the right side outside the board. Click on the letter in that block: H (Hadamard), X (NOT), M (Measurement), E (Entangle) to transform its state and operation.

##	State of a block:

- When a block is in a basic state, (―), or ( | ), it is in grey color. 

- When a block is in a superposition state (＋), it is in green color. When the tetromino lands on the board, this block will collapse to either (|) or (―) randomly. 

- When a block is in an entanglement state, it will turn from grey to yellow. This block can be entangled (paired) with another block (connected by dash line on the board), and they will collapse together.

##	Operation for a block: 
- H (Hadamard): Transform (―) or ( | ) to superposition (＋)

- M (Measure): Breakdown superposition (＋) to either (―) or ( | ) RANDOMLY

- X (NOT): Flip (―) to ( | ), and flip ( | ) to (―)

- E (Entangle): Pair with another block so when one collapse, the other will simultaneously collapse.

- When a tetromino lands on the board, blocks which are either in the superposition state or entanglement state will collapse. 

# Strategy:

- First, move and rotate a tetromino to a good position and let it fall freely.

- Second, while tetromino is falling, transform each block. The easiest one is the basic piece with X operation.

- Third, for the superposition (＋) or the entangled piece, keep using H-M-H or E-M-E buttons to change the piece until you get the expected result.
