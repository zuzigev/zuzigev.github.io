### HTML & CSS Workshop Start Pack

## Description

This is a quick-start template for a basic personal webpage.  Created for Creative Lab's HTML & CSS Workshop - Spring 2017.

## How to use

Click Green box in upper right-hand corner that is labeled: "Clone or Download".

Click the "Download Zip" option.

Place in a directory of your choice.

## How to host your modified files on your own Github

Make a new repository on Github called "*yourusername*.github.io".  Replace *yourusername* with your actual username.

Move into the repository on your browser.  CLock "Clone or Download" (Green box in upper right-hand corner).  Copy the link that appears when you click the box.

Now for the tricky part.  Open terminal.  Navigate into the directory that your index.thml and style.css files are in (the ones you downloaded from this repository).

PRO TIP: do this by typing "cd " into your terminal and then drag/droping this directory into your terminal.  (Ask for help if this doesn't make sense).

Now, we are inside our directory. A "ls" into terminal should show two files: "index.html" and "style.css".

Next, type "git init" into your terminal.

Now, type "git add --all" (Yes, thats with 2 dashes)

type "git commit -m "first commit" "

THIS IS WHERE WE USE THE LINK WE COPIED!
type "git remote add origin *copy and paste the link here*"

"git push origin master"

And, we are in business baby.

All we have to do now is go into our settings in the repository (on your browser), and enable "github pages" to read from the master branch.


## I made some changes, how do I update my github repository??!?!??!?!

Easy!  Navigate to in your terminal to your directory that is linked to the repository.

"ls" in terminal and you should see your files for your webpage.

type
"git add --all" (again, 2 dashes)
"git commit "whatever_you_did" "
"git push origin master"