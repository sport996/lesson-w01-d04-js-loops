

# Exercises: JavaScript loops

Paste your answers into this file.

<br>

## Print every number from 0 to 10

```
for(let i=0;i<=10;i++)
console.log(i);
```

<br>

## Print every number from 10 to 0

```
for(let i=10;i>=0;i--)
console.log(i);
```

<br>

## Print every number from 4 to -16

```
for(let i=4;i>=-16;i--)
console.log(i);
```

<br>

## Print every fifth number from 8 to 41

```
for(let i=8;i<=41;i+=5)
console.log(i);
```

<br>

## The classic Fizzbuzz Program

For every `number` between 1 and 100...

If the `number` is evenly divisible by 3, print "Fizz"

If the `number` is evenly divisible by 5, print "Buzz"

If the `number` is evenly divisible by 3 AND evenly divisible by 5, print "Fizzbuzz"


```
for(let i=1;i<=100;i++){
if(i%3==0)
console.log(i+" Fizz");
else if(i%5==0)
console.log(i+" Buzz");
if(i%3==0 && i%5==0)
console.log(i+" Fizzbuzz");
else 
console.log(i+" not divisible by any");
}
```

<br>


## The even/odd reporter

Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen (e.g. "2 is even").

```
for(let i=0;i<=20;i++){
if(i%2==0)
console.log(i+" is even");
else
console.log(i+" is odd");
}
```

<br>

## Multiplication Tables

Write a for loop that will iterate from 0 to 10. For each iteration of the for loop, it will multiply the number by 9 and log the result (e.g. "2 * 9 = 18").

Bonus: Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total).


```
let m=0
for(let i=0;i<=10;i++){
m=i*9;
console.log(i+" * 9 = "+m);
}
```

<br>

## The Grade Assigner

Check the results for every value from 60 to 100 - so your log should show "For 89, you got a B. For 90, you got an A.", etc.

```
for(let i=60;i<=100;i++){
if(i >= 80 && i<90)
console.log("For "+i+", you got a B.");
if(i >= 90 && i<=100)
console.log("For "+i+", you got a A.");
if(i >= 70 && i<80)
console.log("For "+i+", you got a C.");
if(i >= 60 && i<70)
console.log("For "+i+", you got a C.");
}
```
