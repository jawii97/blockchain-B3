// a = "welcome to node js";
// console.log(a);
//                  how to make variables (sting , booloean, integer.)

// name = "jawwad"
// phone = 03333333
// Boolean = true / false
// my_self = "ahmed"

// console.log(name);
//console.log(phone +  " & " +my_self);
// console.log( " name +  phone + Boolean + my_self");


//                        now Make array[]"


marks = [23, 54, 34, 34, 56, 65, 90, 76]

// console.log(marks[5]);
// console.log(marks);
// console.log(marks[6] - marks[7]);



//             now make Object, "its for use  for a grouping of subject line in a single frame
 //                   to use Object we represent object as "{}"


 student = {
    name: "jawad",
    dob: "9 97",
    age: 25,
    qualification: "master" ,
    batch: 2,
     result : marks,

}

// console.log(student)
// console.log(student.age)
// console.log(student.result[5]);
// console.log(student.qualification); 

//console.log(name,marks,student); 

//                              Now conditions apply IF or Else or ElseIF
//                           in this conditions we use  "if(){}"  "else "{}" (brakets)

student = {
    name: "jawad",
    dob: "9 97",
    age: 25,
    qualification: "master" ,
    batch: 2,
     result : marks,
     attendence : [30],  
}

//                     Use "&&" keys  in condition


    //  if (student.attendence  <= 20 && marks[5] >= 45 ){
    //     console.log( "Allow in class");

    //  }
    //     else {
    //      console.log( "Not allow in class");
    //  }
      

    //            use  "||" keys in condition


    // if (student.attendence  <= 20 || marks[5] >= 45 ){
    //     console.log( "Allow in class");

    //  }
    //     else {
    //      console.log( "Not allow in class");
    //  }

    
    //  if (student.attendence  != 20 || marks[5] <= 55 ){
    //     console.log( "Allow in class");

    //  }
    //     else {
    //      console.log( "Not allow in class");
    //  }


    
//     std = {
//         name : "jawwad",
//         course: "BC-3",
//         attend:[86],
//         quiz : [40,60],
   
//     }

//     std1 = {
//         name : "kashif",
//         course: "BC-3",
//         attend:[81],
//         quiz : [76,67],
   
//     }
//     attendence = 80
//     tmarks = 75

//     for (let i = 0; i < std.quiz.length, i <std1.quiz.length; i++) {
//         if ( std.quiz[0] && std1.quiz[0] > tmarks &&  std.attend && std1.attend > attendence){

//     console.log(" passed");
            
//         }
//     }
      

    
    
    //   totalno =  [76,89,90];
    //   for (j=0;j < totalno.length; j++){
    //    avg = 0
    //    avg += totalno[j]
    //    console.log(avg) 
    //   }
    
        // FOR LOOP 


    // std = {
    //             name : "kashif",
    //             course: "BC-3",
    //             attend:[81],
    //             quiz : [76,67],
           
    //         }
    //         attendence = 80
    //         tmarks = 75
    // for (i=0; i < std.quiz.length; i++ ){
    
    //     if (std.attend[0] > attendence && std.quiz[1] > tmarks){
    //         console.log("passed");
    //     } else {
    //     console.log("fail");
    
    //     }
    // }
    
                // FOR EACH LOOP[] OR DOUBLE ARRAY (2D ARRAY)
    stdlist= [  
        [
           student1 = {
               name : "jawwad",
               fname : "ismail",
               course : "math ",
               marks : 80,
               attend : 76
           },
               student2 = {
                   name : "ahmed",
                   fname : "khan",
                   course : "math",
                   marks : 76,
                   attend : 88
               }
       ],
       [
           student1 = {
               name : "jawwad",
               fname : "ismail",
               course : "english",
               marks : 57,
               attend : 85
           },
   
           student2 = {
               name : "ahmed",
               fname : "khan",
               course : "english",
               marks : 87,
               attend : 80
           }
       ]
   ];
       
   
   attendence = 80,
   totalmarks =80
   
   //  console.log(student1.course, student2.course, student1.marks, student2.marks);
   //console.log(stdlist); 
   
   stdlist.forEach(item => {
       item.forEach(t=> {
           console.log(t.name);
           console.log(t.fname);
           console.log(t.course);
           console.log(t.marks)
   
           if (t.marks >= totalmarks){
               if ( t.attend >=attendence) {
                   console.log("passed");
               }
               else  {
                   console.log("fail because of attendance");
               }
           }
           else {
               console.log("fail because of marks");
           
       }
       })
                 
    })
