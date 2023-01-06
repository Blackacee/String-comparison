# String-comparison
 
/*returns a negative value if the reference string is
lexicographically before the compared string*/
//Example one

var a = "hello";
var b = "world";
console.log(a.localeCompare(b)); // -1

Example two
//> and < operators can also be used to compare strings lexicographically
function strcmp(a, b) {
 if(a === b) {
 return 0;
 }
 if (a > b) {
 return 1;
 }
 return -1;
}
console.log(strcmp("hello", "world")); // -1
console.log(strcmp("hello", "hello")); // 0
console.log(strcmp("world", "hello")); // 1
