/* TRY CATCH FINALLY
I can only handle number less than 10 
sum(1,9) = 10 
sum(1,11) : hey the number is too big for me 
sum(-1,8) : hey I dont know negative number

try: evaluate your logics 
throw: you use throw statement to create custom error
catch: handle the error
finally: will execute regardless of error

*/
function calc(num1, num2){
  try{
      if(num1>10 || num2 >10 ){
        throw "number too big" ;  //1
        console.log("I throw an exception") ; 
      }
      var result = num1 + num2 ; 
      console.log(result) ;
  }catch(err){
    console.log(err) ;  //2
  }
  finally{
    console.log("the calc finished") ;  //3
  }
}
calc(1,9); 


/* your code exposed to some risks
function calc(num1, num2){
  return num1 + num2 ; 
}*/
