# JAVASCRIPT

## VARIABLE

### VAR , CONST , LET

```
console.log("Hello");

const accountId = 14458;

let accountEmail = "achman@gmail.com";

var password = "12345" // we do not use this because of scopping

accountCity = "Jaipur"

let accountState;

// accountId = 7567 // Not allowed

accountEmail = "a@gmail.com"

password = "47568"

accountCity = "Delhi"

console.table([accountId,accountEmail,password,accountCity, accountState])

```

## DATA TYPES

### JAVASCRIPT HAVE 8 DATA TYPES

- String
- Number
- Bigint
- Boolean
- Undefined
- Null  // type of null === object
- Symbol
- Object

### CONVERSION OF DATA TYPES

```
let score = "hitesh"

//console.log(typeof score);
//console.log(typeof(score));

let valueInNumber = Number(score)
//console.log(typeof valueInNumber);
//console.log(valueInNumber);


// "33" => 33
// "33abc" => NaN
//  true => 1; false => 0

let isLoggedIn = "hitesh"

let booleanIsLoggedIn = Boolean(isLoggedIn)
//  console.log(booleanIsLoggedIn);

// 1 => true; 0 => false
// "" => false
// "hitesh" => true

let someNumber = 33

let stringNumber = String(someNumber)
// console.log(stringNumber);
// console.log(typeof stringNumber);

```

### OPERATIONS ON DATA TYPES

```
let value = 3
let negValue = -value
// console.log(negValue);

// console.log(2+2);
// console.log(2-2);
// console.log(2*2);
// console.log(2**3);
// console.log(2/3);
// console.log(2%3);

let str1 = "hello"
let str2 = " hitesh"

let str3 = str1 + str2
// console.log(str3);

// console.log("1" + 2);
// console.log(1 + "2");
// console.log("1" + 2 + 2);
// console.log(1 + 2 + "2");

// console.log( (3 + 4) * 5 % 3);

// console.log(+true);
// console.log(+"");

let num1, num2, num3

num1 = num2 = num3 = 2 + 2

let gameCounter = 100
++gameCounter;
console.log(gameCounter);

```

### COMPARISON OF DATA TYPES

```
// console.log(2 > 1);
// console.log(2 >= 1);
// console.log(2 < 1);
// console.log(2 == 1);
// console.log(2 != 1);
// console.log("2" > 1);
// console.log("02" > 1);

console.log(null > 0);
console.log(null == 0);
console.log(null >= 0);

console.log(undefined == 0);
console.log(undefined > 0);
console.log(undefined < 0);

// === 
console.log("2" === 2);

```