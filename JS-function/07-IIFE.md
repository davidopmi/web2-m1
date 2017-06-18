/*function test(){
  console.log("hello everyone") ; 
}

test() ; 
*/

/*
IIFE:  wrap the function definition in () and then immediately execute it
the adv. of using IIFE is: make sure all the variables inside are local variable, 
and it will not polute global variable
*/
/*
(function test(){
  console.log("hello everyone") ; 
})()
*/
/*
var salary =1000 ; 
function test(){
  salary = 2000 ; 
}

test() ; 
console.log(salary) ; 

*/

var salary = 1000 ; 
(
  function test(inputs){
     var salary = inputs ; 
      inputs += 1000 ; 
      salary+= 1000 ; 
  }
)(salary) ; 
console.log(salary) ; 




