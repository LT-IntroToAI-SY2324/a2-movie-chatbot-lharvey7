# Assignment 2 - Write UP

## Description
This assignment is about learning and applying the while loop and iterating through multiple lists at a time.  We also will discuss how we match things in chatbots in order to extract what a user is trying to find.  Next assignment we will work with data bases and how we can extract information from them.

## What to complete
1. Go through the notes.py file w/ Mr. Berg
2. Complete `a2.py`, Mr. Berg will walk everyone through the process
3. Make sure you pass all asserts in `a2.py`
4. Complete the reflection problems below
5. Push your code to github for grading

## Reflection Questions
1. What was difficult for you while completing the match function?

This was probably the most difficult coding problem I've ever completed, and I had to add things to my program for multiple asserts. The hardest mechanic of the function to add was of course the percent sign, and I would say the hardest part to completing that was how it affected when to end the function. I needed to make sure that whenever I was checking either of the two lists, that the index I was using wouldn't get out of bounds. The last problem I ran into was the 12th assert, where the loop would try to access source[sind] in the third if statement but it would be out of bounds. I thought that adding another if statement there to check if sind was out of bounds would be needlessly complicated as it would completely alter and affect my chain of elifs, so I just changed the loop condition to include both sind and pind out of bounds checks, and then added something after the loop that would decide what to return based on what was out of bounds and what wasn't.

2. Explain how you could use the match function for extracting information from a movie database.

I think the match function could be used to extract info from a movie database by having a bunch of different petterns, and then using those patterns to find the important information that it could then look for in the database. I think there would need to be a function to find the appropriate pattern and a function to then compare those important values to an entire database and see what data matches it, but if you have both of those functions then it would make for an effective way of accessing info from the database. As the long as the function to match the input data with info from the database takes into account how the data is stored, then I think it should work.
