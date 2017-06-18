/* SCOPE
rule: whenever a function executes, it will create its own scope. 
*/
/*case 1: global scope can not access local scope
function test(){
  var number = 40 ; 
  console.log(number) ; 
}

test(); 
console.log(number) ; 
*/

/*case 2: local scope can access global scope
var someNumber = 40  ; 
function test(){
  console.log(someNumber) ; 
}
test() ; 
*/

/*case 3 IMPORTANT: what if global and local has same named variables???
within local, will refer to the local variable

var someNumber =40 ; 
function test(){
  var someNumber = 50 ; 
  someNumber = 80; 
  console.log(someNumber) ; 
}

test() ; 
console.log(someNumber) ; // global: 

*/

/*case 4 VERY IMPORTANT: global and local has same named variables
if you want to access global variable, what you should do????
use the this keyword

var someNumber =40 ; 
function test(){
  var someNumber = 50 ; 
  console.log("the local value is: " + someNumber) ;
  console.log("the global value is: " + this.someNumber) ; 
}

test() ; 
*/








