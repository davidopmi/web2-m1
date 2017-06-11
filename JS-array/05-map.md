var values = [1,2,3,4,5] ; 
//how to add 2 to each item of your array
var results = [] ; 
for(var i= 0 ; i<values.length ; i++){
    results.push(values[i]+2) ; 
}
console.log(results) ; 

//.map: loop through each item in your array, return a new array; without change the old array!
results = [] ; 
results = values.map(function(i){
  return i +2 ; 
}) ; 
console.log(results) ;
console.log(values) ;
