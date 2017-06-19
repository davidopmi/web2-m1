var davidObj = {
  name : "david"  , 
  city : "new york city ",
  friends : [{
    name: "jack",
    city : "dallas",
    greet: function(){
      console.log("hello from jack") ; 
    }
  } , {
    name:"dan", 
    city : "newark",
    greet: function(){
      console.log("hello from dan") ; 
    }
  }],
  dog : {
    name:"john",
    age : 3 
  }
}  ; 

console.log(davidObj.friends[1].city) ; 