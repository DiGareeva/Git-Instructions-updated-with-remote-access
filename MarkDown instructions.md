# Instruction for MarkDown language in Git

## About Git
**Git** is one of the most popular realization of distributed version control system. Most popular realization of **Git** is [GitHub](https://github.com/)

## Repository preparation

For repository creation go to empty folder (future repository) then add a command in terminal **git init**.

## Creation of savings (commits)
### Add file to commit
 Use command **Git add <file_name>** in terminal
 Then create commit - use command **git commit -m "message for commit"**. Message for commit is *OBLIGATIVE!!!* 
 
## Switching between savings (commits)

Use command **git checkout** to switch for previous commits. You need to find in GitLog, described in previous section, the number of requared commit. Then use command in terminal: **git checkout <commit_number>**. After that you will receive **Detached head** status where there are no  changes can be saved.For return into original state use command **git checkout Master**. 
  
## Git log

Use command **git log** in terminal to check for changes. Command **got log --graph** shows commits and branches tree.

## Branches in Git

Use command **git branch <new_branch_name>** in order to create new branch. Command **git branch** shows all exicted branches where current branch is marked by * and has green color.

## Branches merge and conflicts between them

Use command **git merge <branch_name>** to splt this branch with Master branch. If there will be a conflict of commits between these branches you can choose an option in special menu *<accept incomig/accept current change/accept both changes/compare changes>* or make remarks by youself incide the file. 

## Branches removing

Use command **git branch -d (or D) <branch_name>** in order to delete the branch.

## Headlines in MarkDown 
For headline creation in MarkDown it is necessary to write several symbols *#* in the head line. Number of # shows the line level. The lower level is, the lager the text. 

## Text selection

To make italics font, add * or underscore  (_) *around the text*. 
To make bold font, add ** or doubele underscor (__)   **around the text**.
 To make italics+bold font, add *** or ___ ***around the text***.   
 To make crossed font, add double tilda (~~)   ~~around the text~~.  

Alternative methods of text formatting are requred for combination of different font styles in one sentence. E.g: _text can be written in Italics font and in **Bold font** in the same time_.
## Lists

To create unnumerated lists, use * or +, etc. in front of each line/clause. E.g:
* element 1
+ element 2

To create numerated list, use numbers+dot in front of each line, e.g:
1. Option 1
2. Option 2



## Images

To add an image in text, add: !, then text in [], then name of the image in ().

![Buongiorno!](Mona.jpg)


## Links

To add a link in text, name [link] and put link adress in (). For exemple, this is a [link](https://www.youtube.com/watch?v=fQymxI-fev4)

## Tables

## Citations

## Conclusion 
I guess we will have some more tasks, so...