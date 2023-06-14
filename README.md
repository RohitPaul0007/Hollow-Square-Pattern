# Hollow Square Pattern 
function printPartialRow(n) {
  var str= "";
  str=str + "*";
  for (var i=0;i<n-2;i++){
    str = str + " "
  }
  str= str + "*";
  console.log(str);
  }
function printSingleFullRow(n){
var str = "";
for(var i=0;i<n;i++){
   str = str + "*";
 }
console.log(str);
}
printSingleFullRow(10)
printPartialRow(10)
printPartialRow(10)
printPartialRow(10)
printSingleFullRow(10)
