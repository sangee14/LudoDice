# LudoDice
#30DaysOfKotlin

Kotlin language is used for app development using AndroidStudio or IntelliJ can be used for programming using Kotlin language.

In this 30DaysOfKotlin, I have learnt the basics and implemented to build an app.

The functions and concepts used on building this app and described below are: lateinit, Random, nextInt, when

lateinit:
•	The lateinit modifier can be used on var properties declared inside the body of a class for top-level properties and local variables. The type of the property or variable must be non-null, and it must not be a primitive type.
•	Accessing a lateinit property before it has been initialized throws a special exception that clearly identifies the property being accessed and the fact that it hasn't been initialized.

Random():- to get the random integer(between 1 to 6)be displayed in Dice
•	An abstract class that is implemented by random number generator algorithms.

nextInt():
•	Gets the next random Int from the random number generator.

when():- to display the images respective to random number.
•	when replaces the switch operator of C-like languages.
•	matches its argument against all branches sequentially until some branch condition is satisfied.
•	can be used either as an expression or as a statement. 
•	If it is used as an expression, the value of the satisfied branch becomes the value of the overall expression. 
•	If it is used as a statement, the values of individual branches are ignored.
else:
•	The else branch is evaluated if none of the other branch conditions are satisfied. 
•	If when is used as an expression, the else branch is mandatory, unless the compiler can prove that all possible cases are covered with branch conditions
