# Matilda_

//variable declaration 
let age, name , gender;

age=prompt("Enter age ");
name =prompt("Enter your name ");
gender = prompt("Enter gender (Famale or Male");

//if-statement 

if(age > 18 )
{
    console.log("Hi " + name " " + gender " "+  "  you are above 18");
}
else 
{
    
    return false;
}

//gender

If(gender=="male")
{
gender='M'; // assign gender to char
}
else if(gender=="female")
{
gender='F';
} 

function showDetails(age, name,age )
{
   return  "Hi " + name " " + gender" "+  "you are above 18";
}
console.log(showDetails(age, name, gender));

//question 2 

var myArr=[];
for(let i = 0 ;i< 4;i++)
{
    switch(i){
    case 0:
        {
         myArray.push(prompt("Enter  name"));
         break;
        }
    
    case 1:{
    
     myArray.push(prompt("Enter  surname"));
        break;
    }
         
    case 2:{
            myArray.push(prompt("Enter  gender"));
            break;
    }
     case 3:{
                myArray.push(prompt("Enter  age"));
                break;
         }  
  }
}
    console.log("Name | Surname  | Gender | Age ")
for(let j = 0;j < 4 ; j++)
{
    console.log(myArray[j]);
}

//question 3

//let sum =(num1 , num2 , num2) => num1 + num2 + num3;
let sum = function(num1 , num2 , num2)
{
    return  num1 + num2 + num3;
}

console.log(sum(num1,num2, num3));
