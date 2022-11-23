# Introduction to GitHub

## Table of Content
### Introduction
### What is GitHub?
### Why GitHub?
### Git vs. GitHub
### GitHub Desktop vs. GitHub CLI
### Cloning: How to Clone on GitHub
### Commit: How to Commit Changes on GitHub
### Pull request: How to Create Pull Request
### Conclusion

#### Intoduction

GitHub is one of the best sites for sharing ideas, creating with other developers, and realizing visionary innovations, with over 83 million users. There is an entire system and set of tools on GitHub that help you do it even better, whether you're visualizing data, creating software, a new game, or writing about new technology.

In this topic, we will talk about Git and GitHub, Their differences, why you need GitHub and how to clone with GitHub, how to make a pull request, and how to commit on GitHub, finally we discuss GitHub desktop and GitHub CLI. 

#### What is Git:
Git is a tool used by developers to manage source code. It is free and open source and can be used to handle small and large projects so efficiently. [Git](https://git-scm.com/) is used to tracking changes in source code. And it allows developers from different ends to work together on a particular project.

#### What is GitHub:
GitHub is an online platform used by software developers for tracking, storing, and collaborating with other software developers on a software project. [GitHub](https://github.com/) is one of the most frequently used platforms for software developers because it is free, easy open-source software that allows multiple developers to work on the same project irrespective of location. 

#### Why GitHub:
Below we will be highlighting the importance of GitHub, why we recommend it, and why you need [GitHub](https://github.com/) as a software developer, an employer, or an employee.
- GitHub is free and open-source.
-	GitHub makes it easier for software developers to make excellent 	      			documentation.
-	GitHub uses text editors like markdown to write formatted documents.
- 	GitHub is a repository that allows you to showcase your work to the public, which makes it one of the largest coding communities.
-	GitHub uses cloud hosting, which makes it faster and can connect to platforms like Amazon or Google Cloud.

#### Git vs. GitHub:
Someone might be asking about the difference between Git and GitHub. Below we shall discuss it with the use of a table.



<!--TABLE-->
|  | Git | GitHub
|--|--|--|
| 1 |Installed Locally on your computer  | Cloud Based Hosting	|
| 2 | First released in 2005 | 	Company launched in 2008|
| 3 | Maintained by the Linux Foundation | Purchased in 2018 by Microsoft	|
| 4 |Focused on version control and code sharing  | Focused on centralized source code hosting	|
| 5 | Mostly a command line tool | Administered through the web	|
| 6 | Provides a desktop interface known as Git GUI | Has desktop interface named GitHub Desktop	|
| 7 | Has no user management features | Build in user  management |
| 8 | Less external tool configuration features | Has market place for tool integration	|
| 9 | Competes with mercurial, subversion IBM | Competes with Atlassian bit bucket and Gitlab	|
| 10 | Open-source licensed | Includes a free tier and pay to use tires	|

#### GitHub Desktop vs. GitHub CLI

Tools that facilitate communication and cooperation on GitHub include GitHub Desktop and GitHub CLI. With the help of these tools, you can carry out tasks like committing changes, generating pull requests, and performing operations like pushing, pulling, and cloning for remote repositories.

When constructing different software technologies using these tools, there is a lot more power and freedom.

According to [GloriaOkeke](https://github.com/GloriaOkeke/Introduction-to-GitHub/blob/master/project.md):

| GitHub Desktop | GitHub CLI |
|--|--|
| GitHub Desktop enables interaction with GitHub using a  **GUI**  (Graphical User Interface) | GitHub CLI enables interaction with GitHub from the  **Command line** |
| GitHub Desktop is easier to navigate |  GitHub CLI is advanced and require some technical knowledge|
|GitHub Desktop may not allow advanced functionalities like rebases  | GitHub CLI allows advanced functionalities like rebases |
| GitHub Desktop can be used on building simple applications |GitHub CLI is preferred on building higher applications  |
|GitHub Desktop always requires installation and set-up process  | GitHub CLI does not always require installation and set-up |

#### How to Perform Various Task in GitHub

#### I. Cloning

Clone is a  means of duplicating your repository (your project) from GitHub to your local computer,  which can be pushed back to your GitHub after making necessary changes.


#### 1. Login to your GitHub account through [github.com](github.io)
#### 2. Locate your repositories
  
  ![IMAGE](https://waresdrawltd.com/wp-content/uploads/2022/11/clone001.png)

#### 3. Select the repository you want to clone

  ![IMAGE](https://waresdrawltd.com/wp-content/uploads/2022/11/clone-00.png)

#### 4. After opening the repository click on code
#### 5. Then copy the repository url
  
   ![IMAGE](https://waresdrawltd.com/wp-content/uploads/2022/11/clone-2.png)

#### 6. Then locate your Git Bash
   ![IMAGE](https://waresdrawltd.com/wp-content/uploads/2022/11/clone-1.png)
#### 7. Open your Git Bash
   ![IMAGE](https://waresdrawltd.com/wp-content/uploads/2022/11/clone-ooo.png)

#### 8. Use the command ` cd ` to navigate to any folder of your choice, where the cloned folder should be moved to.
   
#### example `cd desktop`

   ![IMAGE](https://waresdrawltd.com/wp-content/uploads/2022/11/clone-4.png)

#### 9. On your Git Bash type: git clone `{the repository url you copied}`

#### Example 
`git clone https://github.com/oneklickonline/Git-vs-GitHub.git` 
#### 10. Then press enter to clone the repository locally on your system

![IMAGE](https://waresdrawltd.com/wp-content/uploads/2022/11/clone-3.png)

#### II. Commit
Commit is a chnage made to a file on a project. Commit keeps track of changes to files on your branch. Git assigns a hash ID that identifies the specific changes made on a repository and who created the changes?

#### How to commit changes on GitHub
 Follow the steps below to commit your changes to GitHub

 `NB:` Before you commit your work to GitHub make sure you have made all neccesary changes in your file and saved with CMD+S (for Mac) or CTRL+S (for Windows)

Steps to Commit:
#### 1. Open your vscode which you used in making the changes  

  ![IMAGE](https://waresdrawltd.com/wp-content/uploads/2022/11/commit-1.png)

#### 2. Open the file containing the cloned repository where the changes you want to commit were made
#### 3. Click on "view" at the top bar, select terminal to open your vscode "terminal"
Your terminal opens at the bottom page of your vscode
  ![IMAGE](https://waresdrawltd.com/wp-content/uploads/2022/11/commit-3.png)

 #### 4. On your terminal type the following command: `git checkout -b {to change the current file branch}`
 Example: `git checkout -newbranch`
 #### 5. Go to your file and edit the neccessary changes
 #### 6. Save the edits file by pressing CMD+S (for Mac) or CTRL+S (for Windows)
 ![IMAGE](https://waresdrawltd.com/wp-content/uploads/2022/11/commit01.png)
 #### 7. Go to your vscode terminal and type the following command `git add .` to stage the changes made on the file
 #### 8. Type `git commit -m "your commit message"`
 Example: `git commit -m "image update"`
 Your commit message should explain what changes you made to the file.
 #### 9. Type `git push origin {branchname}`
 Example: `git push origin newbranch`
 #### 10. Go back to the repository on GitHub website
 If the commit you made was successful, you will see a kind of the image below on your GitHub:

 ![IMAGE](https://waresdrawltd.com/wp-content/uploads/2022/11/pull-request3-1.png)
This shows your changes was successfully commited to the GitHub repository.
  
#### Pull Request

Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is open, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch. 
Retrieved from https://docs.github.com/en/pull-requests.

#### How to create a pull request:
#### 1. On the repository that was commited click on "compare & pull request"
#### 2. check your changes if they are what you commited
#### 3. Leave a comment to describe the changes made 
#### 4. Click on the "create pull request" button


  ![IMAGE](https://waresdrawltd.com/wp-content/uploads/2022/11/pull-request3.png)

If your pull request was successful you should see a result like the image below

 ![IMAGE](https://waresdrawltd.com/wp-content/uploads/2022/11/pull-request4.png)

 This means you have successfully created a pull request

 And once the change is approved, the pull request source branch will automatically be merged into the main branch

#### Conclusion:
We have treated the meaning of GitHub, how to perform some tasks on GitHub, and its importance to developers, employers, and employees  because of its large community capable of networking millions of developers to contribute to open source project 
