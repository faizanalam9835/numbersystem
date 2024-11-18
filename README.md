const numbers = [
    3, 7, 2, 15, 9, 20, 5, 14, 12, 1, 8, 11, 6, 19, 4, 10, 17, 13, 16, 18,
  ];
let even = []
let odd = []
for(let i = 0; i<numbers.length; i++){
    if(numbers[i]%2 == 0){
        even.push(numbers[i])
    }else{
        odd.push(numbers[i])
    }
}
console.log("even numbers", even)
console.log("odd numbers", odd)


output
even numbers [
  2, 20, 14, 12,  8,
  6,  4, 10, 16, 18
]
odd numbers [
  3,  7, 15,  9,  5,
  1, 11, 19, 17, 13
]
