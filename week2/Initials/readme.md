Problem 1

In this problem I implemented a program that, given a person’s name, prints a person’s initials in capital letters and ignores any spaces, per the below.

$ ./initials  
regulus arcturus black  
RAB

The tricky part was to make sure that my program: 1. prompts a user for their name, but the user’s input might be sloppy, in which case there might be one or more spaces at the start and/or end of the user’s input or even multiple spaces. in a row.  

So my program should print the user’s initials (i.e., the first letter of each word in their name) with no spaces or periods, followed by a newline.
