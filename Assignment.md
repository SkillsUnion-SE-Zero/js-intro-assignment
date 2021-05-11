[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# JavaScript Introdcution: Assignment

## Problems

### 1: Data Types

What are the return values for each of the below code snippets? After coming up with each answer, test it out in the browser console.

#### Part 1:

```js
typeof 42;
("number");

typeof 4.2;
("number");

typeof "hello";
("string");

typeof false;
("boolean");

typeof NaN;
("number");

typeof (4 !== 2);
("boolean");
```

#### Part 2:

What's going on here? What "rules," if any, can we guess from testing these examples?

```js
"hamburger" + "s";
"hamburgers" - string;

"hamburgers" - "s";
NaN - Number;

"4" + "2";
42 - Number;

"4" - "2";
2 - Number;

"johnny" + 5;
"johnny5" - string / number;

"johnny" - 5;
NaN - Number;

99 * "baloons";
NaN - Number;
```

### 2: Temperature Converter

Create a program that can convert a temperature in Fahrenheit, Celsius, or Kelvin to the other two units.

#### Setup

1. Under the `src` directory, create a file named `index.html`
1. Under the `src` directory, create a file named `script.js`
1. Make sure to link the `script.js` file with the `index.html` file

#### Instructions

1. Define a variable named `celsius`
1. Store the temperature you get from the user into the `celsius` variable
1. Using the [conversion formula](http://www.csgnetwork.com/temp2conv.html), write JavaScript code that converts `Celsius` to its equivalent `Fahrenheit` and `Kelvin` values

   Example:

   ```
   0C => 32F
   0C => 273.15K
   ```

1. Use `console.log` to print the starting and converted temperature
1. Repeat steps 1-4 for `Fahrenheit` and `Kelvin` temperatures
1. Test your program by opening the `index.html` file in your browser

**Example:**

```js
// Starting temperature
const celsius = 0;
console.log(celsius);

// Conversion Code
const celsiusToFahrenheit = celsius * 1.8 + 32;
const fahrenheit = celsiusToFahrenheit + 0;
console.log(fahrenheit);

const celsiusToKelvin = celsius + 273.15;
const kelvin = celsiusToKelvin + 0;
console.log(kelvin);

// Print the results to the browser console
console.log(`Celsius: #{0}`);
console.log(`Fahrenheit: #{32}`);
console.log(`Kelvin: #{273.15}`);
```

The browser will print something like this example in the console:

```
Celsius: STARTING_TEMP C
Fahrenheit: CONVERTED_TEMP F
Kelvin: CONVERTED_TEMP K
```

## Submission Guidelines

- Cite any relevant sources consulted during your research
- Solve the problems using your own code
- Do not copy and paste solutions from the source material
