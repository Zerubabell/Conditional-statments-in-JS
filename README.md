# Conditional-statments-in-JS
Conditional statements control behavior in JavaScript and determine whether or not pieces of code can run. There are multiple different types of conditionals in JavaScript including: “If” statements: where if a condition is true it is used to specify execution for a block of code.

Conditional statements are used to decide the flow of execution based on different conditions. If a condition is true, you can perform one action and if the condition is false, you can perform another action.

JavaScript Conditional Statements: IF, Else, Else IF (Example)
Different Types of Conditional Statements
There are mainly three types of conditional statements in JavaScript.

If statement
If…Else statement
If…Else If…Else statement
If statement
Syntax:

if (condition)

{

lines of code to be executed if condition is true

}
You can use If statement if you want to check only a specific condition.

Try this yourself:

This code is editable. Click Run to Execute
1
<html>
2
<head>
3
    <title>IF Statments!!!</title>
4
    <script type="text/javascript">
5
        var age = prompt("Please enter your age");
6
        if(age>=18)
7
        document.write("You are an adult <br />");
8
        if(age<18)
9
        document.write("You are NOT an adult <br />");
10
    </script>
11
</head>
12
<body>
13
</body>
14
</html>

If…Else statement
Syntax:

if (condition)

{

lines of code to be executed if the condition is true

}

else

{

lines of code to be executed if the condition is false

}
You can use If….Else statement if you have to check two conditions and execute a different set of codes.

Try this yourself:

This code is editable. Click Run to Execute
1
<html>
2
<head>
3
    <title>If...Else Statments!!!</title>
4
    <script type="text/javascript">
5
        // Get the current hours
6
        var hours = new Date().getHours();
7
        if(hours<12)
8
        document.write("Good Morning!!!<br />");
9
        else
10
        document.write("Good Afternoon!!!<br />");
11
    </script>
12
</head>
13
<body>
14
</body>
15
</html>

If…Else If…Else statement
Syntax:

if (condition1)

{

lines of code to be executed if condition1 is true

}

else if(condition2)

{

lines of code to be executed if condition2 is true

}

else

{

lines of code to be executed if condition1 is false and condition2 is false

}
You can use If….Else If….Else statement if you want to check more than two conditions.

Try this yourself:

This code is editable. Click Run to Execute
1
<html>
2
<head>
3
    <script type="text/javascript">
4
        var one = prompt("Enter the first number");
5
        var two = prompt("Enter the second number");
6
        one = parseInt(one);
7
        two = parseInt(two);
8
        if (one == two)
9
            document.write(one + " is equal to " + two + ".");
10
        else if (one<two)
11
            document.write(one + " is less than " + two + ".");
12
        else
13
            document.write(one + " is greater than " + two + ".");
14
    </script>
15
</head>
16
<body>
17
</body>
18
</html>


