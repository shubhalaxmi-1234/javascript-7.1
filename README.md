Intro to javascript:-

-javascript is a high level programming language for buliding web application in a efficient way.
-javascript works on both client side rendering as well as server side rendering.
-Node jS is the runtime environment of javascript.
-javascript is comesfrom echma script so we see the latest version os javascript in the form  of echma script.
-Now we used the javascript version 6 i.e, Echmascript 6(ES6).
-in another way we called ES6 as the vanlia javascript.
-javascript is mainly used for bulliding logics or functionality of a web page.
-


variable:-
-variable is a container to store some data.
there are 3 types of variable are there in javascript.


1.Let:-
-let is a type of variable which is used for changing the variable name letter.
-now these days ,most of the developers used let for changing variable value.
-let is a block scope so we have been using let for most of the cases.
-

 
2.var:-
-var is a type of variable which is also used for changing the variable in later stages.
-var is used in oldest browser so now a days we are donot use var  most of the cases.
-var is function or outside scope.



3.const:-
-const is a type of variable where we canot change our data.
-const means constant to store some data like number,integer etc...

Rules for creating variables name:-
-variable names are case sensitive i.e,"a"&"A" is different.
-only letters,digits,underscore & special character is allowed.(white space is not allowed).
_only letters,underscore& special character should be 1st character only.
-reserved words cannot be a variable names.

ex-
let miki@12=23
let _ram_32=23 ->correct
let 3_siv=24    ->incorrect
let console=23  ->incorrect
let for=23   ->incorrect


Datatypes in JS:-
-
-Datatypes is an attributes associated with a piece of data that tells a computer how to interpret its value.
-in data types we used "typedof" operator to know that what type of data it is.
-mainly in javascript their are 2 types of data types.


1.primitive:-
In javascript threre are 7 types of primitive datatypes are present.
---1.Number:-number are the type of datatypes those it contain some numerical value.
---2.Boolean:-in boolean datatypes we get boolean value like true& false.
---3.undefind:-in undefind data types the data is not define so that it will show undefind.
---4.Null:-in this data types we get null for the value means nothing.
---5.bigint:-in bigint we will get  big integer value.
---6.string:-string is type of datatype that can hold some character like names or words.
---7.symbol:-in symbol we will get whole symbol as well as the value we get for the data type.
2.Reference:-
-non primitive datatypes are the type of datatype that can hold mulitiple items in a single line.
-non primitive datatypes are-object,array& functions.
-objects is a non primitive datatype which can hold multiple items in one single entity.
mainly object working on (key:value) pair.
the left hand side is our keys and right hand side are the values of that key.

ex. of object:-
person={
    "name"="web-bocket",
    "age"=2,
    "business"="software",
    "carrier"="good"
}


ex. of array:-

let arr=[1,2,4,5,8,6,9,3,2]
NOTE-array indexing start from "0".

ex. of function:-

function great(){
    console.log("Hello World")
}
great()


Operator in javascript:-
operator are the key features to do some task or operate some task.
ex. A+B
 in that given example A&B are the operands , "+" sign is our operator.
 there are 5 types of operator are their in javascript.

 1.Arithematic Operator->(+,-,*,/,%(modulo),**(exponents)).
 2.unary operator-> ++(increment),--(decrement)
 3.assignment operator->(=,+=,-=,*=,**=,%=,/=)
 4.logical operator->(logical and operator-&&),(logical or operator ||)
 5.comparision operator->(==,!=,!==,===)

Conditional statement in javascript:-
conditional statement are used to implement some condition in code.
there are 3 types of conditional starement are their on javascript.
1.if condition:-
if condition is true then statement is executed.
syntax:-
if(condition){
    statement;

}
2.if-else condition:-
if condition is true then if block is executed otherwise  it terminates to else condition.
syntax:-
if(condition){
    statement
}else{
    statement  
}


3.else if condition:-
syntax:-
if(condition){
    statement
}else if(condition){
    statement

}else if(condition){
    statement
}else{
    statement
}

// loops are  two types 1. entry control loop(for,while) 2. exit control loop(do-while)
// there are 4 step that loops are follows 1. initialization 2. condition 3. execution 4. increment/decrement
// while(condition) {
// statement
// }





