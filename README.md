# Collection_Popular-Name
Absolute Java, Chapter 16, Project #4 

The code I created is in PopularName.java

The text files boynames.txt and girlnames.txt , which are included in the source 
code for this book, contain lists of the 1,000 most popular boy and girl names in the 
United States for the year 2005, as compiled by the Social Security Administration. 
These are blank-delimited files where the most popular name is listed first, the 
second most popular name is listed second, and so on to the 1,000th most popular 
name, which is listed last. Each line consists of the first name followed by a blank
space followed by the number of registered births in the year using that name. For 
example, the girlnames.txt file begins with 
 
 Emily 25494 
 
 Emma 22532 
 
 This indicates that Emily is the most popular name with 25,494 registered namings, Emma is the second most popular with 22,532, and so on. 
 Write a program that determines how many names are on both the boys’ and 
the girls’ list. Use the following algorithm: 

• Read each girl name as a String, ignoring the number of namings, and add it to 
a HashSet object.

• Read each boy name as a String, ignoring the number of namings, and add it to 
the same HashSet object. If the name is already in the HashSet, then the add
method returns false. If you count the number of false returns, then this 
gives you the number of common namings. 

• Add each common name to an ArrayList and output all of the common names 
from this list before the program exits. 

Requirement from Prof:

Your program should print the number of common names and a list of the
 common names. Also, print out the total number of boys recorded in the census,
 summed up over all boy names, and similarly the total number of girls.
Not the total number of names, but the number individuals recorded in the census.



