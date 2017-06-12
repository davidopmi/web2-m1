/*
  Function:
  1) a block of statement 
  2) define function: use function keyword
    function funName(){
    
    }
  3) execute/call function: 
  funName() ;
  4) hoisting: use variable and declare later
  5) assign function definition to a variable and execute the function through variable
*/
function sayHi(){
  console.log("say hi...") ; 
}
var a = sayHi;
a() ; 

function addFunc(num1, num2){
  return num1+num2 ; 
}
var b = addFunc;  
var c = addFunc(3,5) ; 
console.log(b) ; 
console.log(c) ; 
console.log(b(3,6)) ; 
/* anonymous function */
var d = function(num1, num2){
  return num1 * num2 ; 
}
console.log(d(3,7)) ; 

















