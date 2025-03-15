1️⃣ Drag & Drop Puzzle Pieces
📌 How it Works:

Users can drag a puzzle piece from one position to another.

When a piece is dropped, it swaps places with the piece at the target location.

Pieces will only be swapped, not automatically corrected.

🛠 Implementation:

dragstart event: Saves the dragged piece.

dragover event: Allows dropping on another piece.

drop event: Swaps images of the two pieces.

2️⃣ Rotate Puzzle Pieces
📌 How it Works:

Clicking on a piece rotates it 90° clockwise.

The rotation cycles through 0°, 90°, 180°, and 270°.

Users must rotate pieces correctly to complete the puzzle.

🛠 Implementation:

click event: Increases the rotation by 90°.

CSS transform: rotate(Xdeg); is used for rotation.

3️⃣ Shuffle Pieces
📌 How it Works:

A "Shuffle" button randomizes the positions of all pieces.

This creates a new puzzle challenge every time.

It does not rotate pieces, only rearranges them.

🛠 Implementation:

Uses randomization to shuffle the puzzle pieces.

Clears the puzzle grid and reinitializes it.

4️⃣ Win Condition (Optional Feature)
📌 How it Works:

The game checks if all pieces are in their correct positions & orientations.

If all pieces match the original image correctly, a "Puzzle Solved!" message appears.

🛠 Implementation (Future Feature):

Check if each piece’s position & rotation matches the correct arrangement.

