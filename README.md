# Inputs
A few small projects to test out the function of receiving an user's input in Python

## Mad libs
 This Python code is asking the user to input different words to construct a silly story. Here is what it is doing step-by-step:

1. It asks the user to input an adjective and stores it in the variable `first_adjective`.

2. It asks the user to input a noun and stores it in the variable `noun`.

3. It asks the user to input another adjective and stores it in `second_adjective`. 

4. It asks the user to input a verb and stores it in `verb`.

5. It asks the user to input one more adjective and stores it in `last_adjective`.

6. It prints the first sentence using f-strings to insert the user's input for `first_adjective`:  
"Today I went to a {first_adjective} hospital."

7. It prints the second sentence using the `noun` input:
"In the reception, I saw {noun}."

8. It prints the third sentence using `second_adjective`, `noun`, and `verb`:
"{noun} was {second_adjective} and {verb}ing."

9. It prints the last sentence with `last_adjective`:
"It was {last_adjective}."

So in summary, it is constructing a silly story using multiple user inputs by storing them in variables and printing the story using f-strings to insert those values.

## Volume Calculator
 This is a Python code that calculates the volume of a 3D shape based on user input. Here is an explanation:

1. It first prompts the user to input the length, width and height values by using the input() function and stores these values in the variables - length, width and height

2. The input() function takes the user input as a string, so these values need to be converted to integers before they can be used in calculations. 

3. So int(length) converts the string value of length to an integer. Similarly for width and height.

4. Once they are converted to integers, they can be used in mathematical calculations. 

5. To calculate volume, the formula is: Volume = Length x Width x Height

6. So volume is calculated by multiplying the int values of length, width and height.

7. Finally, the volume is printed using an f-string to neatly format the sentence with the volume value.

So in summary:
- It takes user input for the dimensions 
- Converts input to integers
- Calculates volume by multiplying length x width x height 
- Prints out the volume of user's 3D shape

## Shopping Cart
This is a Python program that calculates the total price for a customer based on their purchase. Here is an explanation:

It first asks the user to enter the name of the product they want to buy using the input() function and stores it in the variable product.
Next, it asks the user for the price per unit of the product using input() and converts the input to a float by wrapping it in float(). This value is stored in price.
Then it asks the user how many units of that product they want to buy using input() and converts that to an integer by wrapping it in int(). This value gets stored in amount.
To calculate the total price, it multiplies the number of units or amount by the price per unit and stores this in final_price.
It prints out a message with the amount ordered and the product name using an f-string.
Finally, it prints out the total price, formatting the float value to 2 decimal places using round() and formatting it nicely with the currency symbol using another f-string.
In summary, it:
- Accepts user input for product details
- Converts values to appropriate types
- Calculates total cost
- Prints purchase details and total price neatly formatted
