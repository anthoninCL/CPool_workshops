---
module:			CPool
title:			Workshop-How_to_approach_a_subject
subtitle:		Just to be sure you know

language:		C

author:		    Lucas FABREGUETTES Anthonin CLARA
version:		1.0
---

Okay, you're now in Epitech for about a week and a half (+1year for some of you lul) and it seems like you're having quite a fun time with subjects. So let's have fun for a little time.

# Exo 1: Thales best friend (it's wrong)

Write a function that applies the Pythagore's theorem. Taking the sides of a triangle as parameter, you'll print "*C'est bon frère!*" followed by a new line if the triangle is right, and "*Il est gauche!*" followed by a new line if not.

#hint(You can find everything you need for the theorem in your friend Google^^)

#hint(Do not code right away, try to think about the exercise before)

#warn(If you're not able to do this exercise, you need to call an AER or a Pedago, he will help you with pleasure (except for Lucas...))

#newpage

Oh hello again! Yes, subject can be long and on different pages, *read everything carefully!!*

So, if one and only one side is equal to 0, print "*Quelque chose ne vas pas droit ici...*" followed by a new line.

If two sides are equal to 0, your function must print nothing and return 42, because why not.

# Exo 2: Another one

Our Lord and Genius Zorglub, master of Zorgland, wants you to design the software for his new brain-washing machine to zorgmanize his enemies into zorgmen.
The machine works by sending a specific character into the mind of its victim.
The character must be chosen carefully using an algorithm devised by our Lord and Genius Zorglub.
The algorithm uses the prisoner ID to determine which character should be used.
An ID is a number made of 8 digits, given as parameter to your program.
You must then display the character to be used, following the rules defined by the Grand Z:

* If there is more than one digit equal to 2, it means that the victim is just a dummy used for test purpose. You must display the default brain-washing byte 0172 (octal) and validation byte 012 (octal).
* If the ID is a multiple of 13 and 29 and 89 or 41 and 71 or 67 or 7 and 43 and 47 and 53, you must display the string "z\n" and stop your program.
* If the ID is 12345678 or 87654321 or 01111010 or 01011010, you must display the following bits:
0111101000001010
* If one of the byte of the ID is worth 0x42 (hexa), it means that the victim is tough and you must print z followed by 0x0A (hexa).
* If the last byte of hte ID is null, the victim is dumb. Just don't care and print "z\n".
* If the ID is a multiple of the sum of the 8 digits, you must diplay the sixth character of the ASCII table starting from the end, followed by the tenth character of the ASCII table.

#hint(It's not that hard, take a deep breath)

# Exo 3: It's time

Still alive ?

Write a function that displays a conversion in hours, minutes and seconds (XXhours, XXminutes, XXseconds), using a number of seconds passed as parameter. It should be prototyped as follows:

```c
void my_time(int seconds);
```