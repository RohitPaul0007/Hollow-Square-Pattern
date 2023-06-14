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
function printWholething(n){
  printSingleFullRow(n);
  for ( var i=0;i<n-2;i++){
    printPartialRow(n)
  }
  printSingleFullRow(n);
}
printWholething(8)

