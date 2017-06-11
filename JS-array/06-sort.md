var values = [1,2,12,5,4,3] ; 

//[1, 12, 2, 3, 4, 5]
var results = values.sort() ; 
console.log(results) ; 
console.log(values) ; 

/*  https://www.w3schools.com/jsref/jsref_sort.asp
1).sort() : By default, the sort() method sorts the values as strings in alphabetical and ascending order.
2)a-b : from minimum to maximum 
3)b-a: from maximum to minimum

***note, the old array is changed!!!! ***
*/

//1,2,3,4,5,12
values = [1,2,12,5,4,3] ; 
results = values.sort(function(a,b){
  return a - b ; 
});
console.log(results) ; 
console.log(values) ; 


//12,4,5,3,2,1
values = [1,2,12,5,4,3] ; 
results = values.sort(function(a,b){
  return b - a ; 
});
console.log(results) ; 
console.log(values) ; 