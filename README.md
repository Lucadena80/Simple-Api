# Simple-Api

Use any framework of your choice to create an API endpoint that accepts input as JSON with 2 fields and returns the result in JSON format with appropriate HTTP status code.
- 1 input field is mandatory, the other is optional.
- If more than 2 input fields are provided, randomly pick any two

Implement code for following test cases to pass:
- If both inputs are missing, return an error message
- If only 1 input is provided, return the input back
- If both inputs are numbers, sum of both numbers is returned
- If either input is a string, the inputs are concatenated in a separate class and the result is returned (Hint: If possible, use dependency injection)
- If either input is an emoji, it returns the same emoji back
