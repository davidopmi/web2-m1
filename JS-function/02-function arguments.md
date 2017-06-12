function addThree(num1, num2, num3){
  console.log(arguments) ; 
  console.log(arguments.length) ; 
  return num1 + num2 + num3 ; 
}

console.log(addThree(1,2,3)) ; 

/*you have the flex. of passing MORE or LESS arguments!!!!*/
/*when you passin more args. the extra will be ignored*/
console.log(addThree(1,2,3,4,5)) ; 
/*when you passin less args, the missing param. will be undefined */
console.log(addThree(1,2)) ; 

/*
every function has a property called arguments 
you could get how many # of params through 
arguments.length 
*/

