# 19/05/2022

Intro to JS -
Cross-platform and interpreted scripting language. It is well-known for the development of web pages. JavaScript can be used for client-side developments as well as server-side developments.


Datatypes in JS -
1. Boolean                                   -   logical entity having two values(true&false)
2. String                                    -   To represent textual data
3. Numbers                                   -   To represent Numbers 
4. Null & Undefined                          -   Null is used for intentional empty value whereas undefined means value doesnt exist
5. Arrays                                    -   Special type of object that can store multiple values
6. Objects                                   -   Variable which can store multiple values with some properties


Operators -
+	        Addition operator
-	        Subtraction operator
*	        Multiplication operator
**	      Exponentiation 
/	        Division
%	        Modulus (Division Remainder)
++	      Increment
--	      Decrement
&	        and
|	        or
!	        not


Creating variables -
var                                        -   It is functional scope i.e. can be updated and re-declared into the scope.
let                                        -   It is block scope i.e. can be updated but cannot be re-declared into the same scope.
const                                      -   It is also block scope as let but cannot be updated or re-declared into the scope.


Arrow Function -
Introduced in ES6 JS 
Doesn't have own binding to this.
Reduces the size of the program
eg-
1. Creating function without Arrow function -            
function (a, b){
  let chuck = 42;
  return a + b + chuck;
}
2. Creating the same function with Arrow function -
 (a, b) => {
  let chuck = 42;
  return a + b + chuck;
}
