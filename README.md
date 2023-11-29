# block18.workshop1
writing test

#Unit Test  
-set up a function called multiplication  
-it should return the solution for the numbers being multiply  
-Expect multiplication(5, 5) to be 25  

-Expect concatOdds([1,2,3,4], [10,9,8,7]) to return a single array of odd numbers  
-Expect concatOdds([1,2,3,4], [10,9,8,7]) to be [1,3,7,9]

#Functional Test  
-When cart is empty user should not be able to click on checkout button.  
-When a user has items in shopping cart and they click the checkout button they should be able to see a prompt with a checkout as guest button and a login user/sign up button.    
-When user clicks on "checkout as guest" button there should be a prompt to be able to input their email  
-When guest user clicks on "Submit" button with invalid email address, they should be shown an error.  
-When user clicks on "Submit" button to enter email they should be taken to next prompt to enter billing information.  
-When billing info is input click "Next" if card/billing info is incorrect an error message should be prompt.  
-When billing info is input and correct click "Next" it should take you to the shipping details prompt.  
-When guest user clicks "Next" after shipping details have been input, the total cost with shipping cost should show and button for checkout should be highlighted  
