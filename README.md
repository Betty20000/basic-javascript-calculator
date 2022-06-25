# basic-javascript-calculator
#basic calculator that performs basics arithmetics

const value_a = parseFloat(prompt('Enter first number: '));
const operator = prompt('Enter operator: ');
const value_b = parseFloat(prompt('Enter second number: '));

let result;
if (operator == '+') {
    result = value_a + value_b;
}
else if (operator == '-') {
    result = value_a - value_b;
}
else if (operator == '*') {
    result = value_a * value_b;
}
else {
    result = value_a / value_b;
}

// display the result
console.log(`${value_a} ${operator} ${value_b} = ${result}`);

