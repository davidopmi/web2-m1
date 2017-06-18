/*the use of closure: private variable */
function outer(){
  var counter =0 ; 
  return function inner(){
    return counter++ ; 
  }
} 
var outerStore1 = outer() ; 
console.log(outerStore1()) ; 
console.log(outerStore1()) ; 
console.log(outerStore1()) ; 

var outerStore2 = outer() ; 
console.log(outerStore2()) ; 
console.log(outerStore2()) ; 
console.log(outerStore2()) ; 

console.log(outerStore1()) ; 




/* our first closure
function outer(a){
  return function inner(b){
    console.log(a+b) ; 
  }
}
var storeOuter = outer(3) ; 
storeOuter(4) ; 
//outer(3)(4)

 */
/*function outer(){
  var outVar = "closure " ; 
  return function inner(){
    var innerVar = "awesome" ; 
    console.log(outVar+innerVar) ; 
  }
}
outer()()

*/