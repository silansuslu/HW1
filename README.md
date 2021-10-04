This is my first gradle project with CI/CD deployed on Heroku.

[![Build Status](https://app.travis-ci.com/silansuslu/HW1.svg?branch=main)](https://app.travis-ci.com/silansuslu/HW1)

Generating name for email account

The main task of this project is to create a suitable account name using the 4 parameters it takes.
It takes a String array as the first parameter. This array contains names that can be used as mail accounts.
It takes an int index as the second parameter and this index specifies which element of the array will be selected.
At this point, there are two options to create an account from the chosen name. If 0 is given for the Integer parameter, the vowels in the string will be omitted. If 1 is given, the vowels in the array will be duplicate. 
Lastly, the String parameter will contain the information of the desired mail extension.

In the AppTest file, firstly it is checked whether the vowels are extracted correctly and whether duplicating vowels are working correctly. 
Then, it is checked whether an empty array is given as a parameter. If so, it returns null.
The last three tests, respectively, check whether the index, extension and option parameters are given appropriately. If they are not between the correct numbers to be entered, the program returns null.

My site: https://murmuring-coast-58226.herokuapp.com/