An HTML page holds two text fields "firstNumber" and "secondNumber". Write a JS function to subtract
the values from these text fields and display the result in a div named "result".
Implement to provide the following functionality:
 Your function should take the values of "firstNumber" and "secondNumber", convert them to
numbers, subtract the second number from the first and then write the result in the <div> with
id="result"
 Your function should be able to work with any 2 numbers in the inputs, not only the ones given in
the example.
Submit in the judge the JS code (implementation) of the above function. It may hold other functions in its
body.
  
Hints:
We see that the textboxes and div have id attributes on them.
We can take the numbers directly from the input field by using the getElementById() function. After we
have taken the elements from the DOM it’s time to do the actual work. We get the values of the two
textboxes, the value of a textbox as one would expect is text, in order to get a number we need to use a
function to parse them.
All that’s left now is to write the result in the div. We use the same function to get the result element by id
and change it’s text content to the resulting subtraction.
Our code is ready for submitting now, paste the contents of the .js file in the judge.
