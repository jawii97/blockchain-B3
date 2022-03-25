# blockchain-B3//                  lab 5   make calculator with function of getValue"
//                  lab 5   make calculator with function of getValue"
  num1 = 10
num2 = 23
// function sum() {
//     console.log(num1 + num2);
// }   

// function sum (para){
//     console.log(num1+para);
//     console.log(num1+ 56);
//     console.log(num2+para);
//     console.log(45+para);
// }
// sum(30)    



//  function sum( para1,para2) {
//      let num1 = 20
//          console.log("under function body");
//         console.log(num1);
//      }
//      sum () 

// console.log("num1 before funtion body");
// console.log(num1);

function getValue (paras1, paras2, type){
 if (type === "+"){
     sum(paras1,paras2)}

    else if ( type === "-"){
        sub(paras1,paras2)}
     else if ( type === "%"){
       percent(paras1,paras2)}
     else if ( type === "/"){
    division(paras1,paras2)}
    else {
        console.log("invalid values")
    }
}

function sum (p1,p2){
    let result = (p1+p2)
    console.log("sum  =>" + " " +   result);
}
function sub (p1,p2){
    let result = (p1-p2)
    console.log("sub =>" + " " +  result);
}

function percent(p1,p2){
    let result = (p1%p2)
    console.log("percentage  =>" + " " +  result);
}


function division (p1,p2){
    let result = (p1/p2)
    console.log(" division ==>"  + " " +  result);
}
getValue (74,67, "+")
getValue (73,45, "-")
getValue (45,66, "%")
getValue (74,65, "/")


//             **Lab 6 " Discuss the function of DATE , TIME, DAY, YEAR BY Data, getData**

const date = new Date();
console.log("today Date => "  + date.getDate() );
console.log("today Month => "  + date.getMonth() );
console.log("today year => "  + date.getFullYear());
console.log(date);

array = ["alif", "bay" ,"pay", "say"],
array = array.slice (0,3),
console.log(array)

array = array.slice (0,3),
console.log(array)

array.splice(1,3 , "jiim"," hay")
console.log(array);

setTimeout(() => {
    console.log("hellooooooooooooooooooooo xD");
}, 6000

