# git_practice

This practice we are going to work with git repository.

At the beginning you have to clone the repository to your local computer.  You can do this using command git clone _link_. Link can be **https** or **ssh**.
- How to clone using https you can find [here](https://gitprotect.io/blog/how-to-clone-using-https-in-git/)  
- How to clone using ssh you can find [here](https://www.toolsqa.com/git/clone-repository-using-ssh/) 

`Notice, that for cloning a project using ssh, you need to generate ssh key.`

Or you can use Intellij Idea, File -> New -> Project from Version Control, past the https link (You can get it here) ![picture 1](https://github.com/juliaHrabovska/git_practice/blob/main/pictures/Picture%201.png "Where to find lint to the project")

In the repository you will find 5 files. Each group should use an appropriate file (ex. group **1** uses test_file_**1**, group **2** - test_file_**2** and so on). 
Each file is divided in two parts: test and text. 

## The first task 
The first task is to choose correct answer. 
How we will do that? 
   - In each group we have 3-4 persons. Each person should choose the question (ex. the first person takes 1 question, second - 2 question and so on). 
   - After that each person should create a separate branch (lets call branches like "**group_[group number]\_task_1\_[your second name]**")

      ![picture 2](https://github.com/juliaHrabovska/git_practice/blob/main/pictures/Picture%203.png "Create new branch") 
   - In your branch you should choose a correct answer for your question and remove incorrect answers. You can discuss it with your partners.
   - After that you have to commit your changes (lets use the next pattern for commit message "**question [your question number] [your second name]**")

   ![picture 3](https://github.com/juliaHrabovska/git_practice/blob/main/pictures/Picture%204.png "Commit")
   - And the last things you should do are push your changes (you can use **Commit and Push...** or use this button ![picture 4](https://github.com/juliaHrabovska/git_practice/blob/main/pictures/Picture%205.png "Push")) to remote repository and create a pull request (assign on me your pull request). ![picture 5](https://github.com/juliaHrabovska/git_practice/blob/main/pictures/Picture%206.png "create pull request") ![picture 6](https://github.com/juliaHrabovska/git_practice/blob/main/pictures/Picture%207.png "Choose branches") ![picture 7](https://github.com/juliaHrabovska/git_practice/blob/main/pictures/Picture%208.png "Assign")


## The second task 
The second task is to correct mistakes the in the text. There are obvious mistakes, kind of _Trrrrrrrracked_, _snapshooooooot_ etc. 

How we will be fixing them? 

Each person has to fix at least 2 mistakes. But we will do it one by one. The same as we did in the previous task, inside your group you should choose who will be fixing which mistake.
When you are done with that pull all changes from **main** branch 

![picture 8](https://github.com/juliaHrabovska/git_practice/blob/main/pictures/Picture%209.png "Pull changes")

and create a new branch from **main** branch (name it "**group_[group number]\_task_2\_[your second name]**").
- In your branch write changes, commit your changes (with commit message "fix [number of fix] [your second name]"), push to remote repository and create a pull request (again assign it to me).
- When all pull requests are ready, I will merge the first pull request, and other pull requests become unavailable to merge because you will have conflicts.

 ![picture 9](https://github.com/juliaHrabovska/git_practice/blob/main/pictures/Picture%202.png "Conflicts")

- The owner of the next pull request should pull all changes from the **main** branch to the local repository. Checkout to your branch and merge changes from main branch to your branch ![picture 10](https://github.com/juliaHrabovska/git_practice/blob/main/pictures/Picture%2010.png "Merge changes locally") 
and you will have warning message that you have conflicts, you should solve them (click on **Merge** button)

     ![picture 11](https://github.com/juliaHrabovska/git_practice/blob/main/pictures/Picture%2011.png "Merge pop up") ![picture 12](https://github.com/juliaHrabovska/git_practice/blob/main/pictures/Picture%2012.png "Solve conflicts")

- And after solving all conflicts you should push your changes to remote repository, they will appear automatically in your pull request. After that I merge the second pull request and the next teammates do the same till the time you fix all mistakes in the text.