var values = [1,2,3,4,5] ; 

/*save even numbers to a new array*/
var evens = [] ; 
for(var i= 0 ; i<values.length ; i++){
  if(values[i]%2 == 0 ){
    evens.push(values[i]) ; 
  }
}

console.log(evens) ; 

/*using filter: return a new array with items met the condition in your callback
filter does not alter your old array
*/
evens = [] ; 
evens = values.filter(function(i){
  return i%2==0;  
}) ; 
console.log(evens) ; 
console.log(values) ; 