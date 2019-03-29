## 1. Create a Variable: var
```javascript
var favoriteFood  = 'pizza'
var numOfSlices  = 8
console.log(favoriteFood)
console.log(numOfSlices)
```
## 2. Create a Variable: let
```javascript
let changeMe =true
changeMe = false
console.log(changeMe)
```
## 3. Create a Variable: const
```javascript
const entree='Enchiladas'
console.log(entree)
entree = 'Tacos'  //會出現TypeError: Assignment to constant variable.
const testing; //會出現SyntaxError: Missing initializer in const declaration
```
## 4. Mathematical Assignment Operators
```javascript
let levelUp = 10;
let powerLevel = 9001;
let multiplyMe = 32;
let quarterMe = 1152;

// Use the mathematical assignments in the space below:
levelUp +=5
powerLevel -=100
multiplyMe *=11
quarterMe /=4

// These console.log() statements below will help you check the values of the variables.
// You do not need to edit these statements. 
console.log('The value of levelUp:', levelUp); 
console.log('The value of powerLevel:', powerLevel); 
console.log('The value of multiplyMe:', multiplyMe); 
console.log('The value of quarterMe:', quarterMe);
```
## 5. The Increment and Decrement Operator
```javascript
let gainedDollar = 3;
let lostDollar = 50;
gainedDollar++
lostDollar--
```
## 6. String Concatenation with Variables
```javascript
var favoriteAnimal='mouse'
console.log('My favorite animal:'+favoriteAnimal)
```
## 7. String Interpolation
```javascript
const myName = 'YT';
const myCity  = 'Taiwan';
console.log(`My name is ${myName}. My favorite city is ${myCity}`);
```
## 8. typeof operator
```javascript
let newVariable = 'Playing around with typeof.';
console.log(typeof newVariable); //String

let newVariable = 1;
console.log(typeof newVariable); //num
```
