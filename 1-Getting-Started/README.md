# First steps #
We're gonna start where every programmer begins their journey, a classic `"Hello World"` program.

Open up your favourite text editor or IDE (Integrated Development Environment) [^1] and create a file called `hello_world.py`. In this file write the following code 
```py
print("Hello World!")
```

Use the appropriate means from your editor to run this code, or if you're doing it from the terminal

If you're running your code in Google Colab, paste the code in a cell and hit run

![Google Colab Run](./../Assets/hello-world.png)

If you've done everything correctly you should see the words "Hello World!" written on your screen, If not, follow the steps again and retry.

## Code Breakdown ##
We're now gonna take a look at exactly what we're doing. I'm aware its only one line of code, but it's handy to know what it does.

We first start by writing `print` which is a python built-in function to write things. next we open and close parentheses `()`, this signifies that we call the function, which is a fancy way to say we wish to use it at execution. Inside these parentheses we write what is known as a string, which is any alpha-numeric piece of text enclosed with quotation marks `"`, in our code, `"Hello World!"` is a string which we want to print out, as such we pass it within the parentheses of `print` and voila! we have written our very first python program. 

[^1]: If you don't have a text editor or IDE you can easily follow along in [Google Colab](https://colab.research.google.com/) and use the handy run button for your code in cells.