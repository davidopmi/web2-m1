//string... tell me your understanding of string in JS
/*
  1) string is array of characters: 
    -access char in string through index
    -the length property
    -indexOf, lastIndexOf
   2) .split: return an array of characters from the string
   3) .join(): combine array into string
*/
//.split(''): ["d", "a", "v", "i", "d"]
var name = "david" ; 
console.log(name[0]) ; 

var results = name.split('') ; 
console.log(results) ; 

//.split(' ')
name="david yang" ; 
var results = name.split(' ') ; 
console.log(results) ; 

//.join()
var names = ["david", "jack", "lisa"] ; 
var result = names.join(" and ");
console.log(result) ; 
