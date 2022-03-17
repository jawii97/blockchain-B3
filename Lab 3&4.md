# blockchain-B3
   
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
