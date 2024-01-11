github

<--------git-------> 

    version control system is a tool that helps to track changes in code:

    -popular ---> free and open source 
    -fast $ scalabel
1.to track history 
2.to collabrate

<--------github -------->

Website that allows developers to store  and mange their code using git.

            http://github.com

folder  ----called as (repository)


#creating new repository: (changes commit)

#cd : change directory
#ls : list of files 
#ls -a :hidden files all files 
#clear() : command is use to be clear the terminal or command prompt


#configuring git

    git config-- global user.name "MY NAME"
    git config-- global user.email "MY EMAIL ADDRES"
    git config-- list

#clone & status 

clone: cloning a repository on our local machine

        git clone <link from git web>

status: displays the state of  the code 
        
        git status

1--> Untracked 

        new files that git doesn't yet track.

2--> modified

        change

3--> staged 
        files is ready to be commited 

4--> Unmodified 
        unchanged

5-->mkdir 
        make directory

#Add & commit

add :
        adds a new or changed files in your working directory to the git staging area.
        
        git add<filename>
        git add .          ------> To add all files(.) use

commit:
        it is used the record of change.

        git commit -m "some message"

#push command:

        Upload local repository content to remote repository.

        git push origin main

#Init command

        init: Used to create new git repository.

        git init

        git remote add origin <link>
        git remote -v (To verify remote)
        git branch    (To check branch)
        git branch -M main (to rename branch)
        git push origin main
1
        
