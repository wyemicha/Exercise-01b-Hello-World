# 01b-Hello-World
Exercise for MSCH-C220, 25 January 2021

This exercise is an opportunity for you to create your (perhaps) first program in Python. A tradition in programming is for a person's first program in a language to print out "Hello, World!". We will be doing that, but with a little twist.

First, Fork the repository. When that process has completed, make sure that the top of the repository reads [your username]/Exercise-01b-Hello-World. 

*Edit the LICENSE and replace BL-MSCH-C220-S21 with your full name.* Commit your changes.

Press the green "Code" button and select "Open in GitHub Desktop". Allow the browser to open (or install) GitHub Desktop. Once GitHub Desktop has loaded, you should see a window labeled "Clone a Repository" asking you for a Local Path on your computer where the project should be copied. Choose a location where you will keep the repositories for this class (a C220 folder off your Desktop would be fine). Make sure the Local Path ends with "Exercise-01b-Hello-World" and then press the "Clone" button. GitHub Desktop will now download a copy of the repository to the location you indicated.

Open Visual Studio Code, and select File->Open. Navigate to the repository folder you just cloned, select the folder, and press "Open".

In the far right (black) panel of the window, you should see five icons. The top one is File Explorer. If that is selected, you should see four files listed: .gitignore, LICENSE, main.py, and README.md.

Open main.py. If you are prompted to install the Python plugin, do so now.

The first three lines in the file (the only lines so far) are probably confusing, but I will explain them as part of my demonstration. You can ignore them for now.

On the line following the contents of main.py (fourth line), type the following:
```
print("Hello, World!")
```

Capitalization, punctuation, and spacing are all important, so make sure what you type matches this exactly.

If you press the green run arrow in the top right corner of your window, you should see a panel appear at the bottom of the window (labeled Console). After it displays some syntax (related to running the program), the console should display:
```
Hello, World!
```

Now we are going to add to this program. On the next lines (lines 5–6), type the following:
```
print("I would like to get to know you.")
n = input("What is your name? ")
```
 (notice the space after the question mark).

 If you run the program again (I like to push the garbage can icon between runs, so I am always getting a fresh start), you should now see three lines of text, and the cursor is waiting on the third one for you to answer. Select the console panel, type your name, and press return).

 Now, let's make some decisions based on what you type. On the next lines in main.py (lines 7–12), type the following. To indent, use the Tab key:
 ```
if n == "Jason":
    print("What do I need to do to get an A?")
elif n == "Bob":
    print("I've got a bad feeling about you.")
else:
    print("I am glad to meet you, {}".format(n))
```

Run the program, and see how it responds when you type different names. Capitalization and spelling are important when matching the names.

Save these files and quit Visual Studio Code. In GitHub Desktop, you should now see main.py  highlighted. Add a Summary message at the bottom of that panel, and push the "Commit to master" button. On the right side of the top, black panel, you should see a button labeled "Push origin". Press that now.

If you return to and refresh your GitHub repository page, you should now see that your files have been changed (with a new date).

Now edit the README.md file. When you have finished editing, commit your changes, and then turn in the URL of the main repository page (https://github.com/[username]/Exercise-01b-Hello-World) on Canvas.

The final state of the file should be as follows (replacing my information with yours):
```
# Exercise-01b-Hello-World
Exercise for MSCH-C220, 25 January 2020

A python implementation of Hello, World, followed by a short conversation.

## Implementation
Built using Visual Studio Code and Python 3.9.1

## References
None

## Future Development
None

## Created by 
Jason Francis
```