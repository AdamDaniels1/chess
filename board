// Create an array to store the chessboard squares
var board = [];

// Generate the chessboard
function generateBoard() {
  // Loop through the rows of the board
  for (var i = 0; i < 8; i++) {
    // Create a new row
    var row = [];

    // Loop through the columns of the board
    for (var j = 0; j < 8; j++) {
      // Create a new square and add it to the row
      var square = document.createElement('div');
      square.classList.add('square');
      row.push(square);
    }

    // Add the row to the board
    board.push(row);
  }

  // Add the squares to the board element on the page
  var boardElement = document.querySelector('.board');
  for (var i = 0; i < 8; i++) {
    for (var j = 0; j < 8; j++) {
      boardElement.appendChild(board[i][j]);
    }
  }
}

// Call the generateBoard function to display the board on the page
generateBoard();
