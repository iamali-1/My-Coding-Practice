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
