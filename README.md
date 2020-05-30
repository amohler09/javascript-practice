# javascript-practice

//    ONE 
// Write a function called reverseString that accepts a string and returns a reversed copy of the string.

// Input Example:
// 'hello world'
// 'asdf'
// 'CS rocks!'

// Output Example:
// 'dlrow olleh'
// 'fdsa'
// '!skcor SC'









//    TWO
// Create a function that takes an array of names and returns an array where only the first letter of each name is capitalized.

// capMe(["mavis", "senaida", "letty"]) ➞ ["Mavis", "Senaida", "Letty"]

// capMe(["samuel", "MABELLE", "letitia", "meridith"]) ➞ ["Samuel", "Mabelle", "Letitia", "Meridith"]

// capMe(["Slyvia", "Kristal", "Sharilyn", "Calista"]) ➞ ["Slyvia", "Kristal", "Sharilyn", "Calista"]

// Don't change the order of the original array.
// Notice in the second example above, "MABELLE" is returned as "Mabelle".









//    THREE
// Write a function called sortString that takes a string of letters and returns a string with the letters sorted in alphabetical order.

// Input:
// 'dcba'
// 'zycxbwa'
// 'AzycxbCwBaA'

// Expected Output:
// 'abcd'
// 'abcwxyz'
// 'AABCabcwxyz'







//      FOUR
const unimaginativeArray = [ 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10 ];
// Write a "for" loop that console.log()'s the "zeroeth"
// value in the unimaginitiveArray, and thereafter every
// third value of the unimaginativeArray, i.e. 0, 3, 6,
// and 9: the zeroth, third, sixth, and ninth values.




const nameArray = [ 'Jacquelynn', 'Csaba', 'Ellen', 'Moises', 'Cole', 'Jeff', 'Dre\'Sean' ];
// Write a console.log() that displays the last value in
// nameArray. Use the `.length` property of array's
// to access the last value. What's going on with that
// slash in Dre'Sean's name?




const adjectiveArray = [ 'awesome', 'fantastic', 'amazing', 'wonderful', 'fabulous', 'incredible', 'marvelous' ];
// Using both nameArray and adjectiveArray, make a
// "for" loop that console.log()'s a sentence for each
// corresponding value in the arrays. Use the string "is"
// to combine the name with the adjective. For example:
// "Jacquelynn is awesome"
// "Csaba is fantastic" et cetera...




// Write a "for" loop that console.log()'s every third
// number in unimaginativeArray but initialize the
// iterator so it doesn't console.log() the zero.







//      FIVE

// Given an array of scrabble tiles, create a function that outputs the maximum possible score a player can achieve by summing up the total number of points for all the tiles in their hand. Each hand contains 7 scrabble tiles.

// Here's an example hand:

const scrabbleTiles = [
  { tile: "N", score: 1 },
  { tile: "K", score: 5 },
  { tile: "Z", score: 10 },
  { tile: "X", score: 8 },
  { tile: "D", score: 2 },
  { tile: "A", score: 1 },
  { tile: "E", score: 1 }
]

// The players maximumScore from playing all these tiles would be 1 + 5 + 10 + 8 + 2 + 1 + 1, or 28.

// Here, each tile is represented as an object with two keys: tile and score.









// Write a function called commonElements that has parameters for two arrays.  Return an array of all items that are present in both arrays.  Do not modify the arrays that are passed in.

//  Input Example:  

// [1, 2, 3, 4] [3, 4, 5, 6]
// ['a', 'b', 'c'] ['x', 'y', 'z', 'a']
// [1, 2, 3] [4, 5, 6]

// Output Example:  

// [3, 4]
// ['a']
// []





