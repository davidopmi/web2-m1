/*push and pop*/
var names = ["david" , "jack" , "lisa"] ; 
//push: add an new item to the last of array
names.push("dan") ; 
console.log(names) ; 

//pop: remove the last item from array: return value: the removed item
var removed = names.pop() ; 
console.log(names) ; 
console.log(removed) ; 

//unshift and shift 
//unshift: add item to the beg. of array
names = ["david" , "jack" , "lisa"] ; 
names.unshift("dan") ; 
console.log(names) ; 
//shift: remove the 1st item of the array
removed = names.shift() ; 
console.log(names) ; 
console.log(removed) ; 

//indexOf: in case of multiple occurance, from left to right, item index in an array
names = ["david" , "jack" , "lisa"] ; 
console.log(names.indexOf("lisa")) ; 
//if you  could not find, return -1 
console.log(names.indexOf("dan")) ; 
//lastIndexOf: in case of multiple occurance, from right to left 
names = ["lisa","david" , "jack" , "lisa"] ;
console.log(names.lastIndexOf("lisa")) ; 


/*
slice: copy parts of array
1) DO NOT CHANGE the original array
2) ******starting index inclusive, ending index exclusive! ******
*/
names = ["david" , "jack" , "lisa", "julie", "dan"] ;
var result = names.slice(2,4); 
console.log(result) ; 

//array of array:
var names = ["david", ["jack", "lisa", ["dan"] ] ] ; 
console.log(names[1]); 
console.log(names[1][2]); 
console.log(names[1][2][0]); 

