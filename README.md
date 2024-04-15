function rollDice() {
  
  var randomn = Math.floor(Math.random() * 6) + 1;
  return randomn;
}

var result = rollDice();
console.log("You rolled a " + result + "!");
