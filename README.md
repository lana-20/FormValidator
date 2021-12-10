# [Form Validator](https://lana-20.github.io/FormValidator/)

I am building a form validator, something simple and common.
I'm going to do some client side form validation and first create it in the form with HTML.
Then I'm going to style it with CSS and proceed with adding my JavaScript.

In the beginning, I'm doing this the easy but not the best way - adding a bunch of if-statements with some validation.
And then I'm completely refactoring it and creating specific functions for each type of validation. 
For example, to check required, check the length, or check to see if the passwords match.

So, initially I'm writing it in one way and then completely refactoring it to make it cleaner and more scalable.
If I want to add more fields, it'll be easy to add the validation.
For example, if I were to submit, I'd get a bunch of errors.
Every field is required. Some of them have a min and max length. I.e., username must be at least three characters.
If I type in Lana in the username field and submit, it gets highlighted green, which means that it passed.
For the email, typing just anything will not work. If I type test@test.com, that's going to pass.
The password has to be at least six characters. If I type five characters in the password field, I get an error "Password must be at least 6 characters". 
Also, I get an error "Passwords do not match", and they have to. If I type 123456 in both password fields and click submit, then they both pass.

I'm working with JavaScripts along with CSS. I need to add certain classes to make input border color green or red and to display/hide the error messages.
