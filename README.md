# hello-wrold
my first repository

var a = +[prompt("enter the 1st number: ")];
var b = +[prompt("enter the 2nd number: ")];
var c = +[prompt("enter the 3rd number: ")];
var d = +[prompt("enter the 4th number: ")];
var e = +[prompt("enter the 5th number: ")];

var sum = 0

var numbers = [a, b, c, d, e];

for (var i = 0; i < numbers.length; i++) {
  sum = sum + numbers[i] / numbers.length;
}

alert("Average is " + sum);
