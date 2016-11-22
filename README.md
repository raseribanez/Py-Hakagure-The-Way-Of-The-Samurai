# Py-Hakagure-The-Way-Of-The-Samurai
A personal project where I make a little GUI to display verses from the book Hakagure

Inspiration for this was from the film Ghost Dog

The main character lives by a book called Hakagure - The Book of the Samurai

It is Essentially a Samurai Handbook that was originally written centuries ago, but despite the age a LOT of the wisdom within the verses can be applied to modern day life.

I made a little GUI app that has stored verses from the book in a text file. Each verse is on a line in the text file, and the program pulls random lines at the press of a button in Tkinter.

The method I used to grab the random lines was apparently more efficient because the first way I wrote it seemed to use the line length as part of the decision in determining the random line choice. What was happening is only the mid-range length verses were being favoured or displayed. The longer and shorter lines were not coming up very often - it almost seemed non-random. So I had a little read around and tried a few ways, and so far this way seems the better choice.

There are 50 verses entered into the text file, and maybe over time I will add more. When I selected verses to display I tried to not go for the epic page long ones, because the whole verse is stored into a single line in the text file, and although I tried, I couldn't split up the strings to make them appear visually nicer on the eye - using \n or """ escape sequences. 

I didn't have much luck with that and I want to try and see if a resolution could be found in storing the verses in a .py not a .txt - maybe string manipulation will be possible then.

3 versions are in this repo - They were put up originally as seperate repo's because I still wanted to add to one of them at-least, and didn't want them zipped up into their individual folders and put ino one repo but i am trying to clean up my repo list a bit, so I will do that for now and any changes I make will be offline - if I do anything worthwhile then I wll update the zip file accordinbgly

Each one was a seperate repo so they probably have their own readme's in each as-well

1st version was totally text based. Was used to figure out the function I was going to use to pull the lines at random - for testing.
2nd version added it into Tkinter with a nice Japanese picture/theme
3rd version (my favourite) adds the Ghost Dog theme to the GUI, using the Hakagure Black and Red Symbol
