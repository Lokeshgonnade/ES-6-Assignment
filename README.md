# ES-6-Assignment
ES-6.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ES6-Assignment</title>
</head>
<body>
    <script src="ES6.js"></script>
</body>
</html>


ES-6.JS :-
var a = 10;  //Herevalueofais10
var b = 8;  // Here value of b is 8
var c = 6;  // Here value of c is 6
{
    let a = 10;
    //Here value of a is 2 but only within the block
    var b = 10;
    //Here value of b is 10 inside and outside the block it will remain 10
    const c = 8;
    //Here value of c is 8 but only within the block
    //const cannot be reassigned
    //c = 5;
}
document.write("The value of a is : " + a);
//let has block scope
document.write("<br>");
document.write("The value of b is : " + b);
//var does not have block scope
document.write("<br>");
document.write("The value of c is : " + c);
//const has block scope



var d = "I have ford, it is a Mustang" 
document.write("<br>")
document.write("I have ford, its is  mustang")
