# fiveguysfacts


## EDITING THE DOCUMENT
First, you need to do the following 1 time only:

1. Go to a command line, and go to the directory where you want this folder to be
2. Type "git clone https://github.com/DavisTrey/fiveguysfacts.git"
3. now type "cd fiveguysfacts"

Now you can edit the .docx file. When you are ready to commit your changes (commit in small increments, and commit as soon as you make changes, or else you will be unhappy):

1. Go back to the command line (make sure you are in the five guys facts folder)
2. Type "git pull" just to make sure you are up to date
3. Type "git status"
4. You should see FiveGuysFacts.docx in red (indicating changes have been made). If you don't see this, you fucked up somehow. 
5. Type "git add *". This adds the file to your running changelist
6. Type "git commit -m "some message about your change"". Replace my part in quotes with a real message (but note you do need to type those quotes). This commits your change locally with the comment you type. 
7. Type "git push origin master" - you should see a success prompt. 

Yay! Now, if you want to make more changes in the future, just restart from the beginning of the second set of instructions. 
