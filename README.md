# English-Dictionary
Enter words you don't understand in the terminal and get an organized table of meanings and etc. in Excel!

# purpose
Sometimes it takes a lot of time to edit a well-organized word sheet of a specific range of words. As a teacher or student we might not want to waste too much time on this. This Dictionary-Builder can help you to build up a nice and neaet table of words, showing their meanings and part of speech by simply entering them.

# design
First of all, ask and receive the target word list from user and create a list to save them. 
Then, tranverse the collected word list and call an dictionary API online, saving the returned information corresponding to each word in a list.
Third, Use 'openpyxl' module to access Excel and enter the information in pre-set format.

# how to use
Set the target path that you want the xlsx. file to be created in your computer in 'path' in the program.
Then, if you want a different name of the file, modify the 'workbook.save()' lines in the program.
Finally, run the program and enter the target words in the terminal. Press enter to quit.

# Reference
Special thanks to Free Dictionary API
URL: https://dictionaryapi.dev/
