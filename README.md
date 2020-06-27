# form-validation
Simple form validation made using HTML, CSS and vanilla JS. 

Use of novalidate to prevent the use of inbuilt HTML form validation, 
so that better validation methods could be applied in JS using properties of the constrained validation API. 

Used regex patterns to specify the requirements of each input field where necessary.

For password confirmation, since it requires comparing two sets of input, could not be done using the constrained validation API, meaning styles applied for those
input fields also would not work. To get around this, I wrote the functions for the validations needed and added a class which had the same styling as 
input:focus:invalid.

Link here: https://jkhunter315.github.io/form-validation/
