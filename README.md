# Hollow Square Pattern 
function printPartialRow(n) {
  let str= "";
  str=str + "*";
  for (let i=0;i<n-2;i++){
    str = str + " "
  }
  str= str + "*";
  alert(str);
  }
function printSingleFullRow(n){
let str = "";
for(let i=0;i<n;i++){
   str = str + "*";
 }
alert(str);
}
function printWholething(n){
  printSingleFullRow(n);
  for ( let i=0;i<n-2;i++){
    printPartialRow(n)
  }
  printSingleFullRow(n);
}
printWholething(8)

