# Date-extractor-and-validator
Date extraction from text and validate it using Python
I Am trying to learn python from Al-Sweigart-automate-the-boring-stuff-with-Python:

and below is the practice project from that book, where we have to extract date from text using regular expression:
Date Detection

Project Question
Write a regular expression that can detect dates in the DD/MM/YYYY format. Assume that the days range from 01 to 31, the months range from 01 
to 12, and the years range from 1000 to 2999. Note that if the day or month 
is a single digit, it’ll have a leading zero.
The regular expression doesn’t have to detect correct days for each 
month or for leap years; it will accept nonexistent dates like 31/02/2020 or 
31/04/2021. Then store these strings into variables named month, day, and 
year, and write additional code that can detect if it is a valid date. April, 
June, September, and November have 30 days, February has 28 days, and 
the rest of the months have 31 days. February has 29 days in leap years. 
Leap years are every year evenly divisible by 4, except for years evenly divisible by 100, unless the year is also evenly divisible by 400. Note how this calculation makes it impossible to make a reasonably sized regular expression 
that can detect a valid date.

Major Activities:
1. Create Regular expression - that detects date in format DD/MM/YYYY.

2.Store these String in variable : Day, month, Year.

3. Check if date is valid, date with in range (1,31) , month with in range(1,12), year(for leap year feb- 29 else feb- 28)

