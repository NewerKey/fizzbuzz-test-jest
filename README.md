# Test Driven Development using Jest Framework

## Project Description

A program that prints the numbers from 1 to 100.
For multiples of 3, print "Fizz" and for multiples of 5, print "Buzz".
For multiples of both 3 and 5, print "Fizzbuzz"

## SetUp

`npm init`

- Adding Jest as a dependency
  `npm install --save-dev jest@23.6.0`
- Run Jest package
  `npx jest`

## Writing Tests

- 'describe()' - declares a test suite, has arguments(name, function-one or more)
- 'it()' - declares a test, has arguments(name, function-with actual test code)
- 'expect()' creates an assertion- takes a single argument

- Run test automatically
  `npx jest --watchAll`

- Measure test coverage
  `npm run test -- --coverage --coverageReporters=text`
