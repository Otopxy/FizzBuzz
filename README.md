# FizzBuzz
let Fizz = [ ];
let Buzz = [ ];
let FizzBuzz = [ ];
let Other = [ ];
for ( let i = 1; i <= 200; i++) {
if (i%3 === 0 && i%5 === 0) {
FizzBuzz.push(i);//store in FizzBuzz array
} else if (i % 3 === 0 && i % 5 !==0) {
Fizz.push(i); // store in Fizz array
} else if (i % 3 !==0 && i % 5 === 0) {Buzz.push(i);// store in Buzz array
} else {
Other.push(i);// store in Other
}
}
console.log("Total Number of Fizz = " + Fizz.length);
console.log("Total Number of Buzz = " + Buzz.length);
console.log("Total Number of FizzBuzz = " + FizzBuzz.length);
console.log("Total Number of Other = " + Other.length);
