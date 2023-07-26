# avax-module-1
The contract ErrorHandlingContract includes a public variable value to store a value.



The testrequire function demonstrates the usage of the require() statement. It takes an input parameter _input, and if the input is not greater than zero, the function will revert with an error message.



The testassert function demonstrates the usage of the assert() statement. It compares two variables a and b, and if the condition a < b is false, it will revert with no error message. In this example, assert(a < b) passes, so the value will remain 0 (initialized value) as the subsequent statement is not executed.



The testrevert function demonstrates the usage of the revert() statement. It takes an input parameter _input, and if the input is zero, it will revert with a custom error message.
