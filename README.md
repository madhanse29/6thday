# 6thday
<!DOCTYPE html>
<html>
<body>
 <script>
 alert( “I’m JavaScript!’);
 </script>
 Whats the error in this ?
</body>
</html>
 ANS : the error is ( “I’m JavaScript!’) -> ( "I’m JavaScript!")
 
 Find the culprit and invoke the alert
fix.html
<!DOCTYPE html>
<html>
<body>
 <script src=”script.js”></script>
</body>
</html>
scripts.js
alert(“I’m invoked!”);
ANS : file name of javascript is different . is changed to script.js &  (“I’m invoked!”) -> ("I’m invoked!").


Explain the below how it works
explain.html
<!DOCTYPE html>
<html>
<body>
 <script src=”script.js”></script>
</body>
</html>
script.js
alert("I'm JavaScript!");
alert('Hello') // this line is not having semicolon
alert(`Wor
 ld`)
alert(3 +
1
+ 2); // this is multiple line code and its working

ANS : it will be show one by one in alert window .


Fix the below to alert Guvi geek
fix.html
<!DOCTYPE html>
<html>
<body>
 <script src=”script.js”></script>
</body>
</html>
script.js
let admin=9, fname=10.5; 
fname = "Guvi";
lname = "geek"
admin = fname+lname;
alert( admin ); // "Guvi geek"

ANS :   script .js change into

let admin=9, fname=10.5; 
fname = "Guvi";
lname = "geek"
admin = fname+" "+lname;

alert( admin );  ....


Fix the below to alert hello Guvi geek
fix.html
<!DOCTYPE html>
<html>
<body>
 <script src=”script.js”></script>
</body>
</html>
script.js
let fname=10.5; 
fname = "Guvi";
lname = "geek"
let name = fname+lname;
alert( 'hello ${name}' );

ANS : let fname=10.5; 
fname = "Guvi";
lname = "geek"
let name = fname+lname;
alert("hello"+" " + name); ......
