// write a function for multiply: takes two parameter, one output
/*
  3,4 =>12
  4*5 =>20 


function myMul(num1, num2){
 
  var result = num1 * num2 ; 
  return result ;
  return num1 * num2 ; 
}

console.log(myMul(3,4) ) ; 

*/

/* function expression: create anonymous function and assign to a variable 
be very careful here the someFunc refers to a function, not a value!!!
to execute the function: someFunc(3,4)  

the function finishes once reach the return statement 
*/
var someFunc = function(num1, num2){
  console.log("get me while you can") ; 
  return num1 * num2 ; 
  console.log("can you get me????") ; 
} ; 

//nsole.log(someFunc) ; 
console.log(someFunc(3,4)) ; 
