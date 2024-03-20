# Assignment6

//Question 1

//let result;
//function calculateArea(radius) {
//  result = (3.14) * radius * radius;
//  return result;
//}

//const output = calculateArea(20);
//console.log(output);

//Question 2

//function isEven(num) {
//  if (num % 2 == 0 && num != 0) {
//    return true;
//  } else {
//    return false;
//  }
//}

//const output = isEven(80);
//console.log(output);

//Question 3


//const arr = [1, 2, 3, 4, 5];
//let newArray = [];
//function reverseArray(array) {
//  for (let index = arr.length - 1; index >= 0; index--) {
//    newArray.push(arr[index]);
//  }
//  return newArray;
//}
//const output = reverseArray(arr);
//console.log(output);

//Question 5

const person = {
    name: "Ayush",
    "age": 19,
    mobile: "0147852369",
  };
  
  function getKeys(obj) {
    return Object.keys(person);
  }
  
  const output = getKeys(person);
  console.log(output);
  
  //Question 8

  const fruits = ["apple", "mango", "orange", "papaya", "banana","coconut"];
let getFruit = fruits.find((data) => {
  if (data.includes("a")) console.log(data);
});
