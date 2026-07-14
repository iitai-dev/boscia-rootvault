# 14-1-25

So, what's the difference between tuples and lists? Tuples are **immutable**.
They are useful when the data stored in collections shouldn't be accidentally modified during the program execution. For example, in a GPS navigation application, the coordinates of landmarks should remain constant

Amazing! Tuples are now in your Python toolset. Here's the summary:
🌟 Tuples are **ordered** collections of items
🌟 Tuples are **immutable**
🌟 You can access tuple items using their **indexes**, similar to lists


# 15-1-25

Amazing! Here's what we've covered:
🌟 many functions used with lists can also be used with tuples, if they don't change any data
🌟 you can use tuples in any control flow structures
🌟 the *** operator** in tuple unpacking allows for flexible assignment of elements to variables


**Sets**, unlike lists and tuples, are unordered collections. They are created with **curly brackets { }**.

Sets **can't** have duplicates, which is very helpful when developers need to ensure that each item in a collection is unique. For example, in social media apps, your friends list should not have duplicates.
Adding duplicate items to a set doesn't cause an error; instead, it's ignored.

Sets are mutable, meaning you can add or remove items from them.
Use the **add()** and **remove()** functions, each with a value as an argument, to add or remove it from a set.

The **clear()** function doesn't accept an argument and removes all the items from a set.

The **union()** function called returns a new set with all elements from both sets, omitting duplicates.

The **difference()** function returns a set containing elements that are only in the first set and not in the second.


![[Pasted image 20250115160705.png]]


You are doing fantastic! Here's what you've learned:
**🌟 Dictionaries** are collection types used to store data in **key:value** pairs
🌟 Dictionaries can have duplicate values, but not duplicate keys
🌟 You can access a single value in a dictionary using the **get()** function
🌟 The **values()**, **keys()**, and **items()** functions are used to retrieve different collections of data from a dictionary
# 17-1-25

Amazing job! Here's what you've learned:

🌟 Dictionaries are **mutable**
🌟 You can **change** or **add** dictionary items using the **update()** function
🌟 You can remove dictionary items with the **pop()** function
🌟 You can iterate through a dictionary using a **for** loop

![[Pasted image 20250117150438.png]]

![[Pasted image 20250117150514.png]]

Fantastic work! Here's what you've learned:
🌟 **list comprehensions** provide a concise and readable method for creating lists, allowing you to define various settings in just a single line of code
🌟 with list comprehensions, you can apply any expression to each item in the list being created
🌟 you can also incorporate a condition into a list comprehension

# 21-1-25
![[Pasted image 20250121141819.png]]

Exceptions can often be predictable. To handle them and prevent program failure, you can use a **try/except** statement.

The **try** block holds code that might cause an exception. If an exception occurs, execution of the try block stops, and the **except** block is executed, allowing the program to continue running.

You can have multiple **except** blocks to handle each possible exception specifically. As a best practice, it is recommended to output a definitive message for each type of handled exception.

Amazing job! Exception handling is now part of your coding toolkit. Here's what you've learned:
🌟 Use a **try/except** block to handle exceptions and prevent program failure
🌟 If an exception occurs in the try block, the except block will be executed
🌟 You can handle exceptions without specifying the exception type

You can use the **finally** statement to perform an operation after the try/except block, no matter if an exception occurred or not.

The **else** statement can be used in conjunction with the try/except block and will execute only when no error occurs in the try block.

You can trigger your own exceptions based on specific conditions using the **raise** statement. This will immediately stop the program's execution and indicate an error has occurred.
![[Pasted image 20250121143139.png]]

Amazing job! You've learned that:
🌟 the **finally** keyword is used to execute code after a try/except block, regardless of whether an exception was raised
🌟 the **else** keyword, used with try/except, runs only if the try block is error-free
🌟 custom exceptions can be triggered using the **raise** keyword


# 23-1-25

🌟 You can assign a function to a variable and use it to call the function
🌟 Functions that take other functions as input and/or return a function are called Higher-order functions
🌟 Pure functions always return the same value for the same arguments and do not produce any side effects

# 24-1-25
Amazing! You learned that:
🌟 Lambda expressions are compact, anonymous functions used for simple operations
🌟 Lambda expressions can be assigned to variables or used within other functions for on-the-fly operations

![[Pasted image 20250124102150.png]]

![[Pasted image 20250124102237.png]]


Amazing job! You've learned that:
🌟 The **map()** function applies a specified function to every element in an iterable
🌟 The **filter()** function filters out items from an iterable based on a specified condition
🌟 Both can accept lambda expressions as arguments
