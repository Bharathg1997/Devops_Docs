Local Respository:
    • Local repositories are nothing but we can do in our local sytem.
    • And also we can push or pull our code to remote location
Example :Git
    • In git we can do different types of operations to push our code to remote location.
    • If you are trying to push code to  remote location first we must install git in our local system then only we can push
    • Commands for pushing an file or document to your remote location
Step 1: First you need to initialize git
    • git init     
            Step 2: To add a file
    • git add filename ( which file you want to push give that filename)
    • git add . ( . means takes all files from the directory or folder)
            Step 3: Commiting our file
    • git commit -m “first commit”( save our file )
            Step 4: Next, you need to mention your remote branch name i.e., main or master
    • git branch -M main
    • git branch -M master
          Step 4: Add your remote location url
    • git remote origin add repo-url
         Step 5: To push code to remote location
    • git push -u origin give branchname(main or master which you are using)


Central Repository:
    • Central repositories are nothing but to store our code in one place.
Example:Github
    • In github we have public and private repositories.
    • Public repository is everyone can see and commit.
    • Private respository is accessible  to the person whom you are selected only those persons can do changes.
Commands from github(Central repository) to git(local repository)
 Step 1: cloning data to our local repository
    • git clone github-repository-url
Step 2: if there are any changes made in our repo we can pull by using the below command
    • git pull ( it will asks for username and password )

Sourcecode Management:
    •  Manage our code with different versions we use SCM. 
    • Check  modifications in our repositories on code base level.

Examples:
 Local Repositores: git
Central Repositories: github,bitbucket

LifeCycle of Git:

We have three phases
    • Workspace
    • Staging area
    • Local repository

    • WorkSpace: 

    • Creating new files or modifying existing files those files will be in workspace area.

    • Local Repository:

    • If we are pushing any files to cental repository those files must be present in local repository then only we can push.

    • Staging area:

    • It shows the author name and commit id and email id.
    • File modified and when file was committed and so on.
      Command:
    • To check whether the file is available or not type below command. 

      git status(checks the status of the file).

    • Adding files from workspace to staging area type below command.
    • Check whether file is added or not
                                    git add filename or git add .
                                    git status
    • Adding files from staging area to local repository.
      git commit -m “provide any msg” filename
           Note: here -m specifies message.
    • Checking files are added or not in local repository type below command.

         git log
    • Below command displays the files you committed using commitid.

       git show cid

    • Getting file from staging area to workspace.

      git reset HEAD filename(specified file).
      git reset HEAD *(All files).

    • Getting file from local repository to staging area.

   git reset –soft cid(previous commitid)

    • Getting file from local repositoy to workspace.

git reset –mixed cid
         
    • Pushing files from local repository to central repository.

       git push <remote-url> <branch-name>











