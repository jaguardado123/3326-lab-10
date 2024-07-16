# Lab Assignment 09

In this lab you will practice working with for loops.

Same as the previous labs, you need to set up your workspace (class and main() method).

## Let's get started!

First, let's look at the name of our .java file in the src/ directory and name your class accordingly and remember to make it **public**. Next, **create your main() method inside your class**.

Now let's begin!

## For Loops

Loops in Java are exactly the same as in C++.

For loos are used when you know exactly how many times you want your code block to execute.

The for loop header is divided into 3 parts: the `counter declaration`, the `counter condition`, and the `counter increment`. The counter declaration is only executed one time. From there the for loop follows this workflow:

1. Check the counter condition. (if true goes to step 2, otherwise ends)
2. Execute code block.
3. Increment the counter.

**For Loop:**
```java
for (conuter_declaration; counter_condition; counter_increment ) {
	// Code block to be exectured.
}
```

Same as the while loops, for loops can utilize `break` and `continue` statements.

The `break` statement is used to immediately exit the loop.

The `continue` statement is used to immediately jump to the condition and start a new iteration.

## Your program

**Print a 6x6 Pyramid**

For this assignment you will utilize for loops to `print a 6x6 pyramid`.

Make sure your pyramid has 6 rows and 6 columns and is increasing top to bottom.

Your output should look like:

```
*
* *
* * *
* * * *
* * * * *
* * * * * *
```

## Submit your assignment

To submit your lab assignment click on the source control icon (3 circles with 2 lines) on your leftside navbar. Next, click on the '+' symbol next to "Changes" to stage your changes. Lastly, add a commit message (ex: "First commit") and click "Commit" then "Push" or "Sync Changes". And you're done!