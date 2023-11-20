# Codecademy JavaScript Credit Card Checker
This small project is based off of the challenge project [Credit Card checker](https://www.codecademy.com/journeys/full-stack-engineer/paths/fscj-22-building-interactive-websites/tracks/fscp-22-javascript-syntax-part-ii-c8ddbace-1463-4797-ae12-503c7b0f9552/modules/wdcp-22-credit-card-checker-b1138dff-8fa2-426b-b943-74a5c58d2455/projects/credit-card-checker) from Codecademy. In this challenge three functions must be defined:
1. A function `validateCred()`that uses a [Luhn Algorithm](https://en.wikipedia.org/wiki/Luhn_algorithm#Description) to vaidate credit card numbers and returns a boolean.
2. A function `findInvalidCards()` that takes an array of nested credit card number arrays and returns an array containing only the invalid credit card numbers.
3. A function `idInvalidCardCompanies()` that goes through this array of invalid credit card numbers and returns a list of the issuers of these cards, based on the first digit of the card number. Issuing companies will not be repeated in the array.

Some testing is included at the bottom of the code to ensure the functions are working as intended.