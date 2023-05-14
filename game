// Get the board and pieces objects from the other scripts
var board = window.board;
var pieces = window.pieces;
var movements = window.movements;

// Create a variable to store the current player
var currentPlayer = 'white';

// Add event listeners to the squares on the board
var squares = document.querySelectorAll('.square');
squares.forEach(function(square) {
  square.addEventListener('click', function() {
    // Check if the square has a piece on it
    if (square.innerHTML !== '') {
      // Check if the piece belongs to the current player
      if (square.innerHTML === pieces[currentPlayer + '_king']) {
        alert(currentPlayer + ' wins!');
      } else if (square.innerHTML === pieces[currentPlayer + '_queen']) {
        alert(currentPlayer + ' wins!');
      } else {
        alert('That is not your piece!');
      }
    } else {
      // Move the piece to the clicked square
      square.innerHTML = board[0][0].innerHTML;
      board[0][0].innerHTML = '';
      // Switch to the other player's turn
      currentPlayer = (currentPlayer === 'white') ? 'black' : 'white';
    }
  });
});
