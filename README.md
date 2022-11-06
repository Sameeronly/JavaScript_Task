# JavaScript_Task

1. How to get value of the variable my var as output ?

var myvar= 1; console.log("myvar");

2. Write a loop that makes seven calls to console.log to output the following triangle ?

for (let line = "#"; line.length < 8; line += "#") console.log(line);

3. Square of a number ?

console.log(Math.pow(3, 2));

4. Addition of 3 numbers ?

function sumNumbers(a, b, c) {
var sum = a + b + c;
console.log(sum);
}
sumNumbers(1, 2, 3);

5. Iterate through the string array and print it contents ?

var strArray= ["Jazz", ,"Blues", ,"New Age", ,"Classical", ,"Opera"] console.log(strArray)

6. Get the first item, the middle item and the last item of the array ?

let s=[3, 2, 3, 4, 5]; function Gfg() {
 Storing the first item in a variable let f=s[0];
 Storing the last item let l=s[s.length-1];
 Printing output to screen document.write("First element is "+ f); document.write("Last element is "+ l,""); } Gfg(); 
 Calling the function

7. JavaScript Array Insert - How to Add to an Array with the Push, Unshift, and Concat Functions ?

const arr = ['First item', 'Second item', 'Third item'];
arr.push('Fourth item');
console.log(arr); // ['First item', 'Second item', 'Third item', 'Fourth item']

8. How to insert an item into an array at a specific index (JavaScript) ?

var array = []; array[0] = "Jani"; array[1] = "Hege"; array[2] = "Stale"; array[3] = "Kai Jim"; array[4] = "Borge";
console.log(array.join()); // Jani,Hege,Stale,Kai Jim,Borge array.splice(2, 0, "Lene"); console.log(array.join());

9. Write a code to print the numbers in the array ?

var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11]; var new_string ="";
for (var i = 0; i < 11; i++) { new_string += numsArr[i] } console.log(new_string);

10. Write a code to print from last to first with spaces (Make sure there is no space after the last element (1) ?

var new_string = "";
for (var i = 10; i >= 0; i-- ) { new_string += numsArr[i] +"" } console.log(new_string);

11. Write a code to replace the array value — If the number is even, replace it with ‘even’?

var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11]; for (var i = 0; i <=10; i++) { if(numsArr[i] %2 == 0 ) { numsArr[i] = "odd" } } console.log(numsArr);

12. Write a code to replace the array value — If the index is even, replace it with ‘even’.?

var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11]; for (var i = 0; i <=10; i++) { if(numsArr[i] %2 == 0 ) { numsArr[i] = "even" } } console.log(numsArr);

13. Write a code to add the even numbers only ?

var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11]; var sum=0; for (var i = 0; i <10; i++) { if(numsArr[i]%2==0); sum += numsArr[i] } console.log(sum);

14. Write a code to print elements in the inner arrays ?

var numsArr = [[1, 2, 3, 4, 5],[ 6, 7, 8, 9, 10, 11]]; var str_all=0; for (var i = 0; i < numsArr.length; i++) { var inner_array = numsArr[i]; for(var j = 0 ; j < inner_array.length;i++ ) str_all +=inner_array[j] } console.log(str_all);

15. Write a code to print elements in the inner arrays in reverse ?

var numsArr = [[1, 2, 3, 4, 5],[ 6, 7, 8, 9, 10, 11]]; var str_all=0; for (var i = 0; i < numsArr.length; i++) { var inner_array = numsArr[i]; for(var j = inner_array.length; j < 0 ;j-- ) str_all +=inner_array[j] } console.log(str_all);

