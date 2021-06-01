# Geoparsing with Python: Coding Challenge
The text I used was the History of a Six Weeks' Tour by Mary and P.B. Shelley which was found in Project Gutenberg. The countries identified were mostly in western Europe and in the US.  
Challenges: I was unable to create a function to pass the URL since I wasn't sure why that had to be done for this assignment.  

The issue with using Nominatim for the book that was published in 1817 is that it is using the current city names as the toponym and that might generate invalid results if one is looking at countries 200 years ago! For instance, I was surprised that there were cities in the US, however the book I selected was written about European cities. So the explanation must be that the European-sounding US city names were erroneously selcted by Nominatim. Names such as 'Most' and 'Of' kept being identified as cities and this makes me question the accuracy of the output. It might be useful to use Natural Language Processing methods to overcome these issues. 

