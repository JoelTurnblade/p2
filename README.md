# Project 2
+ By: *Joel Turnblade*
+ Production URL: <http://p2.turnblade.me>

## Outside resources
- W3 Schools
  - [Select Form example](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_elem_select)
  - [Radio Form example](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_form_radio)
  - [Hidden Form Inputs example](https://www.w3schools.com/tags/tryit.asp?filename=tryhtml5_input_type_hidden)
  - [General information about Forms](https://www.w3schools.com/html/html_forms.asp)
  - [Initial Input Value](https://www.w3schools.com/tags/att_input_checked.asp)
  - [CSS Padding](https://www.w3schools.com/cSS/css_padding.asp)
  - [CSS Padding Property](https://www.w3schools.com/cssref/pr_padding.asp)
  - [CSS for Forms](https://www.w3schools.com/css/css_form.asp)
  - [CSS Classes](https://www.w3schools.com/tags/att_global_class.asp)
  - [CSS Width Property](https://www.w3schools.com/cssref/pr_dim_width.asp)
  - [CSS Centering](https://www.w3schools.com/howto/howto_css_image_center.asp)
  - [HTML Named Colors reference sheet](https://www.w3schools.com/colors/colors_names.asp)
- HTML Color Codes
  - [Color Selector](https://htmlcolorcodes.com/)
- PHP Manual
  - [Random Number Function](http://php.net/manual/en/function.rand.php)
  - [Exponentiation Operator](http://php.net/manual/en/language.operators.arithmetic.php)
  - [Logical Operations](http://php.net/manual/en/language.operators.logical.php)
- Stack Overflow
  - [Centering a Form with CSS](https://stackoverflow.com/questions/8097744/how-do-i-center-this-form-in-css)
  - [Default Radio Button](https://stackoverflow.com/questions/5592345/how-to-select-a-radio-button-by-default)
  - [Default Select Option](https://stackoverflow.com/questions/3518002/how-can-i-set-the-default-value-for-an-html-select-element)
  - [Extending CSS Class](https://stackoverflow.com/questions/10705038/css-extending-class-properties)
- File Format Website
  - [Multiplication Unicode Character](https://www.fileformat.info/info/unicode/char/00d7/index.htm)
  - [Minus Sign Unicode Character](https://www.fileformat.info/info/unicode/char/2212/index.htm)
- David Walsh Website
  - [PHP Ternary Operator](https://davidwalsh.name/php-shorthand-if-else-ternary-operators)


## Code style divergences
- None that I am aware of.

## Notes for instructor
- The only input which required validation was the textbox.  This reports an error for non-numeric inputs.
- The application employs the class Data.  This class is designed to handle the data from $_POST.  The class has the following functionality:
  - It sanitizes and stores the data in $_POST
  - It tracks bad input errors related to the textbox
  - It generates the random numbers
  - It determines if the random numbers are still within their length parameters
