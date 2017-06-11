//===== question 1: print your array in reverse order.
var values = [1,2,3,4,5] ; 
//print your array in reverse order...: 1) print out every items 2) in reverse order

function reverseMe(arr){
//   for(var i = 0 ; i< arr.length; i++){
//     console.log(arr[i]);
//   }
  
//   console.log(arr[arr.length-1]) ; //4
//   console.log(arr[arr.length-2]) ; //3
//   console.log(arr[arr.length-3]) ; //2
//   console.log(arr[arr.length-4]) ; //1
//   console.log(arr[arr.length-5]) ; //0
  
//       for(var i =1; i<=arr.length ; i++ ){
//         console.log(arr[arr.length-i]) ; 
//       }
  
  /*   console.log(arr[arr.length-2]) ; 
    arr.length-1 = arr.length-1 - 0 
    arr.length-2 = arr.length-1 - 1 
    arr.length-3 = arr.length-1 - 2
    arr.length-4 = arr.length-1 - 3 
  */
  for(var i = arr.length -1 ; i>=0 ; i--){
    console.log(arr[i]);
  }
}

reverseMe(values) ; 

//question 2: check if all the items in your array are the same
var values = [2,2,2,2] ; 
//check if all the items in your array are the same
/*
1) loop through 
2) compare 
*/
function checkAllTheSame(arr){
  var check = arr[0] ; 
  var result = true ; 
  for(var i =0 ; i < arr.length ; i++){
    if(check == arr[i]){
      result = true ; 
    }else{
      result = false ; 
    }
  }
  return result ; 
}
console.log(checkAllTheSame(values)) ; 

//think about another solution?? this one is better!!!
//values = [1,2,3,4,5] ; 
values = ["a","a","a","b"] ; 
function checks2(arr){
  //sort the arr in alphabetica way
  var newArr = arr.sort() ; 
  if(newArr[0] == newArr[newArr.length -1]){
    return true ; 
  } else{
    return false ; 
  }
}

console.log(checks2(values)) ; 

