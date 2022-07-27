# Chapter 6 Exercises

Exercises with a tick mark :ballot_box_with_check: represent exercises that must be submitted as part of your Programming Skills Portfolio as a minimum expectation. Completing more exercises provides the opportunity to attain higher marks. For each exercise you should create a _**new project**_ with the name of the exercise and save it to this exercises folder in your local repository.

Once you have completed your solution you should make sure you commit and push your solutions to your remote repository on GitHub. You can commit and push as many changes to your solutions as you wish, only those pushed before the chapter deadlines will be marked for the Programming Skills Portfolio.  

---
&nbsp;

## Exercise 1:  Restaurant:  :ballot_box_with_check:


Make a class called Restaurant. The __init__() method for Restaurant should store two attributes: a restaurant_name and a cuisine_type.

Make a method called describe_restaurant() that prints these two pieces of information, and a method called open_restaurant() that prints

a message indicating that the restaurant is open.

Make an instance called restaurant from your class. Print the two attributes individually, and then call both methods.
&nbsp;
&nbsp;

## Exercise 2: Three Restaurants :ballot_box_with_check:

Start with your class from Exercise 9-1. Create three different instances from the class, and call describe_restaurant() for each

instance.

&nbsp;
&nbsp;

## Exercise 3: Users :ballot_box_with_check:

Make a class called User. Create two attributes called first_name and last_name, and then create several other attributes that are 

typically stored in a user profile. Make a method called describe_user() that prints a summary of the user’s information. Make another

method called greet_user() that prints a personalized greeting to the user. Create several instances representing different users, and 

call both methods for each user.

&nbsp;
&nbsp;

## Exercise 4: Login Attempts :ballot_box_with_check:

Add an attribute called login_attempts to your User class from Exercise 3 . Write a method called increment_login

_attempts() that increments the value of login_attempts by 1. Write another method called reset_login_attempts() that resets the value of

login_attempts to 0.

Make an instance of the User class and call increment_login_attempts() several times. Print the value of login_attempts to make sure it 

was incremented properly, and then call reset_login_attempts(). Print login_attempts again to make sure it was reset to 0

&nbsp;
&nbsp;

## Exercise 5:  Ice Cream Stand

An ice cream stand is a specific kind of restaurant. Write a class called IceCreamStand that inherits from the Restaurant class you wrote

in Exercise 1  or Exercise 4. Either version of the class will work; just pick the one you like better. Add an

attribute called flavors that stores a list of ice cream flavors. Write a method that displays these flavors. Create an instance of 

IceCreamStand, and call this method.

&nbsp;
&nbsp;

