=====================
Lab 2
=====================

.. This is a comment!

Section 0: Introduction
:::::::::::::::::::::::

Welcome to our new shiny lab system. This system is intended to teach you how to do Python interactively. We're going to use some cool drop-ins, you've seen the professor program up on the projector in class. Now you can try it within this page!

The objectives of this lab are:
 - To practice writing simple interactive scripts using the input() functions

 - To learn basic string manipulation

 - To learn new ways of outputting strings

There are 3 checkpoints.


Section 1: Console input and string concatenation
:::::::::::::::::::::::

So far in class, we've learned how to do some arithmetic and how to print strings using ``print()`` 

To recap the print statement can print multiple strings using a comma between arguments. 

.. activecode:: PrintingAList
   :coach:

   print("I like","pancakes","and","waffles","and",
   "hashbrowns")

If you noticed, this example will add a space between each argument! Unfortunately, output only programs aren't very interactive. Let's change that using the
``input()``. First a word of warning. When we show you
examples though ActiveCode, a small window will pop up asking you to input your answer when you use ``input()``. That will not be the case in Wings101.

Go ahead and try out this example.

.. activecode:: AddingItAllUp
   :coach:

   print('Fancy String Adder')
   first = input('Please enter a string:')
   second = input('Please enter another string:')

   print('The addition of your strings is:', first+second)

If you noticed, instead of using the comma to combine the strings ``first`` and ``second`` we're using the ``+`` operator. This operator not only works with numbers it also works with string types as well. This is called String Concatenation and is very useful for interactive applications.

Checkpoint 1

Write a short script in Wings101 using the String Adder code. Add another input and concatenate it to the final output string. Show your TA



Section 2: 
:::::::::::::::::::::::