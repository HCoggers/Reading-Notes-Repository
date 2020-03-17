### Week 1, Monday  

Try and Catch Blocks are statements that can be used when a block of code may throw an exception, or an error. 
Just like in trying to code our calculators today, the program would probably err if someone tried to divide by zero.

Any code that you put in a try block, if it throws an exception, you are now able to handle that how you choose, 
using a catch block, or a finally block if you need to. This, as opposed to the CLR handling it for you, 
which usually means throwing up a confusing error dialog box and ending the program. maybe you have some default values 
you can throw in there to keep the program running, or maybe you want to give the user or coder a more human-readable description 
of the error. That's what the catch and finally block help you do. Although be careful using the finally block. 
The CLR will always try to run any code in a finally block, even if your try statement doesn't throw any exceptions. 
It's more useful for clean up and shut down procedures at the end of the program.
