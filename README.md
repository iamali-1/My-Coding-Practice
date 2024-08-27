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
