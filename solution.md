## Return Negative

```js
function makeNegative(num) {
  return arr.reduce((num) => num >0 ? num * -1)
}
//Once I understood reduce this turned easy to set up
// I'm guessing you didnt tell us about return and reduce on purpose to make us find it.
//Got me over complicating this for while
```

## Sum of Positive

```js
//.reduce litterally reduces the array down to individual numbers so that the callback (the actual function being applied) can work on each number intead of them all at once

function positiveSum(arr) {
  let sum = 0
  //you list the sum as 0 because it starts as 0 then is added on to by reduce
  // Everything after => is the actual eqution
               //the 2 !   ! things in the equation
  return arr.reduce((sum, num) => num >0 ? sum + num : sum, 0)
}
```

## Function 2

```js
function square(a) {
return a * a
}
//Simple *
```

## Sum Arrays

```js
function sumOfArray(arr) {
  let sum = 0
  return arr.reduce((sum, num) => sum + num, 0)
}
//adding your current sum to the current num that reduce is on in that array
```

## Reversed Strings

```js

function solution(str){
    let splitArr = str.split('');
    let reverseArr = [];
    for(let i=splitArr.length-1; i>=0; i--) {
        reverseArr.push(splitArr[i])
    }
    return reverseArr.join('')
}

function solution2(str){
return str-split('').reverse()-join('');
}
// split the word into mutiple indexs, reverse all the indexs, then join them back together
```
