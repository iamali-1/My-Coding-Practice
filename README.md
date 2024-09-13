# My-Coding-Practice <br>
Question: Write a program that finds the maximum value in a given list of integers. <br>
let numbers = [1,2,3,4,5,6,7,8,9,10];
let maxNum = numbers[0];
for(let i = 0; i<numbers.length; i++){
    if(numbers[i] > maxNum ){
        maxNum = numbers[i];
        }
        }
console.log(maxNum) <br>

Write a program that prints a pattern of stars, such as a right-angled triangle, where the number of rows is N. <br>

for (let i = 0; i<=5; i++){
    let line = ""
    for(let j = 0; j<=5; j++){
    let newLine = "*"
    console.log(newLine)
    }
} <br>
Write a program to calculate and display sum of the following series using for loop x + x^2 + x^3 +...x^n. <br>

let x = parseFloat(window.prompt("Enter the value of x:"));
let n = parseInt(window.prompt("Enter the value of n:"));

let sum = 0;
for (let i = 1; i <= n; i++) {
    sum += Math.pow(x, i);
}
console.log("The sum of the series is:", sum); <br>

Write a function to calculate the average of an array <br>

function average(array){
    let sum = 0;
for(let i=0; i<array.length;i++){
    sum+=array[i];
      
}
let  avg = sum/array.length;
return avg;
}
console.log(average([100,50])); <br>

write a function for a password validator. <br>

function isValidPassword(Password, username){
if(Password.length<8 ){
    return false}
if(Password.indexOf(" ")!== -1){
return false
}
if( Password.indexOf(username)!== -1){
    return false
}
else{return true};
}
console.log(isValidPassword("SonGohan","Gohan")); <br>
