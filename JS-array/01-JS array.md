/*array
1) typeof arrays =  object 

*/
//2. declare and initiate array
var names = ["david" , "jack" , "lisa"] ; 
console.log(typeof names) ; 
//3. access array item through index: starting 0 ending: array length - 1 
console.log(names[1]) ; 
//4: array's attribute/property: length: # of items in your array  
console.log(names.length);
//5: the biggest index of array = length - 1  
console.log(names[names.length-1]) ; 
//6: this will generate undefined 
console.log(names[names.length]) ; 
//7: update an array
names[0] = "dan" ; 
console.log(names[0]) ; 
console.log(names) ; 

//8: array in js can host any types of data
var citys = ["ny", true, 25, null, undefined] ; 
console.log(citys) ;
