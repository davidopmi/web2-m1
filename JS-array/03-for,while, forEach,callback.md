var names = ["david" , "jack" , "lisa"] ; 
//print out all the items in your array
console.log(names[0]);
console.log(names[1]);
console.log(names[2]);

// use for loop to iterate through array: note the i<names.length
for(var i= 0 ; i<names.length; i++){
  console.log(names[i]);
}

//while loop
var i = 0 ; 
while(i<names.length){
  console.log(names[i]);
  i++ ; 
}

//callback: is a function. you pass this function to other function as parameter
names = ["david" , "jack" , "lisa"] ; 
names.forEach(function(item){
  console.log("forEach"+item) ; 
}); 