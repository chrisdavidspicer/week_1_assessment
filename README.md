# SEI Week 1 Assessment

### Bash (Terminal)

#### For EACH and EVERY question in this section, assume you are in the `~/buffy` directory:

1. Make two directories inside `~/buffy`: `scoobies` and `vamps`:
<br><br><br>
mkdir scoobies vamps

2. Create files in `scoobies` named `buffy.txt` and `angel.txt`:
<br><br><br>
touch scoobies/buffy.txt scoobies/angel.txt

3. Copy `angel.txt` into the `vamps` directory:
<br><br><br>
mv scoobies/angel.txt vamps

4. Delete the `vamps` directory and everything inside it:
<br><br>
rm -rf vamps

### JS Variables

1. Assign the string "Ahab" to a variable named `captain`:
<br><br>
let captain = 'Ahab'

2. Using the `captain` variable instead of the text "Ahab", use string concatenation to form the string "Oh Ahab, my Ahab!", assigning it to a variable named `phrase`:
<br><br>
let phrase = `Oh ${captain}, my ${captain}!`

### JS Conditionals
```js
var souls = 3;
var lifeRafts = 2;
```

1. Assuming the above variables, write an `if` statement that console.logs "SOS!" if there are more `souls` than `lifeRafts` (no need to write a function, just the `if` statement please):
<br><br>
if(let i = 0; i < 100, i++) {
souls[i] > lifeRafts;
console.log('SOS!);
}


### Data Structures - JS Arrays

1. Create an array named `weekend` with just a string 'Saturday' in it:
<br><br>
let weekend = ['Saturday']

2. Add the string 'Sunday' to the end of the `weekend` array:
<br><br>
weekend.push('Sunday')

3. Now add the string 'Friday' to the front of the `weekend` array:
<br><br>
weekend.pushReverse('Friday')

4. Using square bracket notation, access 'Saturday' in the `weekend` array and assign to a variable named `day` (Note: the array has three days in it as this point):
<br><br>
let day = weekend[1]

5. Remove 'Friday' from the array:
<br><br>
weekend.splice[0]

6. Loop through the `weekend` array and for each element in it, print `"Woohoo! It's finally <day name>"`
for(const day in weekend)
console.log(`Woohoo! It's finally ${day})

### Data Structures - JS Objects

#### Don't forget to use a `var` or `let` when defining new variables...

1. Write an object literal named `brain` having a property with a key of `energyLevel` and a numeric value of `10`:
<br><br>
let brain = {
    energyLevel: 10
}

2. Assign the value of the property `energyLevel` to a variable named `energy`:
<br><br>
let energy = brain.energyLevel

3. Add a `dream` property to the `brain` object that holds the string  'electric sheep':
<br><br>
brain.dream = 'electric sheep'

### JS Functions

1. Write a function named `computeArea` that has two parameters, `length` & `width`, and **returns** the area of a rectangle (the product of `length` and `width`):
<br><br><br><br>
computeArea(length, width) {
    return length * width
}

2. Invoke the `computeArea` function with `3` and `4` as arguments and save the returned result to a variable named `area`:<br><br>

let area = computeArea(3, 4)

3. Write a function `findMax` that takes in 1 paramater, an array of numbers, and returns the highest number in that array.
findMax(numArray) {
    for(let i = 0; i < numArray.length; i++) {
        if(numArray[i] > numArray.integer) {
        return numArray[i]
        }
    }
}

numArray = []