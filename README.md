# cool-git-commands
All cool git commands that can saves you time and maybe your life. :)

<ul>

<p> <li> <code> git reflog : </code> </li>   It shows all the previous commits you've made in your repo. It can be useful when you wants to reverts your work to a previous state.  </p>


<p> <li>  <code> Git standup :  </code> </li> Lists all your yesterday's commits. The downside is its doesn't come with every git client. So you have to install it. Follow the guide <a href="https://github.com/kamranahmedse/git-standup"> here </a> to install. </p>


<p> <li>  <code> Git reset --hard  : </code> </li>  This can be a lifesaver when you've made  a mistake in  your repo and decided to reverts your repo to the previous state. Just use <italic> Git reset --hard <The SHA1 of the commits you want to revert to>  </italic> . First of all you have to use <italic> Git reflog </italic> or <italic> Git standup </italic> to get the SHA1 of the commits you wanted to revert your repo to. </p>


<p> <li>  <code> Git add . : </code> </li>  So , you've made changes to several files on your local repo and you want to stage them all for commits. Instead of looking for all the files you made changes to before you commits. You can just use <italic> git add . </italic> to add all those files at once instead of adding them one by one. </p>


<p> <li>  <code> Git Stash : </code> </li> It  takes all of the staged changes and stores them away somewhere. It can be helpful when you don't want to push  particular changes yet and still don't want to delete them. </p>

<p> <li>  <code> Git pop : </code> </li> This command retrieve your stored changed that you git stash </p>

<p> <li> <code> git commit --amend :  </code> </li>

Let say you made a typo in your  commit message you can use it to change the message instead of making a new commit all over again. </p>

<p> <li> <code> git blame : </code> </li> If you want to play the blame game this command comes handy. It shows the particular changes made to files , the name of the author and the time they made it.In case a person has broken any of your features you can go ahead and YELL at the person who made those mistakes. </p>

<p> <li> <code> git commit -am 'your commit message' : </code> </li>  This command let you add and commit your changes in a single command </p>


<p> <li> <code> git fetch :</code> </li> Fetches all the objects from the remote repository that are not present in the local one. Example: git fetch origin. </p>


<p> <li> <code> git pull :</code> </li> Fetches the files from the remote repository and merges it with your local one. This command is equal to the git fetch and the git merge sequence. Example: git pull origin. </p>

<p> <li> <code> git push :</code> </li> Pushes all the modified local objects to the remote repository and advances its branches. Example: git push origin master. </p>


<p> <li> <code> git prune :</code> </li> Removes objects that are no longer pointed to by any object in any reachable branch. <italic> Example: git prune.</italic> </p>

<p> <li> <code> git archive :</code> </li> Creates a tar or zip file including the contents of a single tree from your repository. </p>

<p> <li> <code> git gc :</code> </li> Garbage collector for your repository. Optimizes your repository. Should be run occasionally. </p>

<p> <li> <code> git instaweb :</code> </li> Runs a web server with an interface into your local repository and automatically directs a web browser to it. </p>

<p> <li> <code> git diff :</code> </li> Generates patch files or statistics of differences between paths or files in your git repository, or your index or your working directory. </p>

<p> <li> <code> git grep :</code> </li> Lets you search through your trees of content for words and phrases. <italic> Example: git grep  "www.siteground.com" -- </italic> </p>

<p> <li> <code> git ls-tree :</code> </li> Shows a tree object, including the mode and the name of each item and the SHA-1 value of the blob or the tree that it points to. </p>

<p> <li> <code> git show :</code> </li> Shows information about a git object.  </p>

<p> <li> <code> git remote :</code> </li> Shows all the remote versions of your repository. Example: git remote origin  </p>

<p> <li> <code> git merge :</code> </li> Merges one or more branches into your current branch and automatically creates a new commit if there are no conflicts.  </p>

<p> <li> <code> git checkout :</code> </li> Checks out a different branch – switches branches by updating the index, working tree, and HEAD to reflect the chosen branch. <italic> Example: git checkout newbranch </italic>  </p>

<p> <li> <code> git branch :</code> </li> Lists existing branches, including remote branches if ‘-a’ is provided. Creates a new branch if a branch name is provided.  </p>

<p> <li> <code> git status :</code> </li> Shows you the status of files in the index versus the working directory. It will list out files that are untracked (only in your working directory), modified (tracked but not yet updated in your index), and staged (added to your index and ready for committing).  </p>

<p> <li> <code> git init :</code> </li> Initializes a git repository – creates the initial ‘.git’ directory in a new or in an existing project.   </p>

<p> <li> <code> git clone :</code> </li> Makes a Git repository copy from a remote source. Also adds the original location as a remote so you can fetch from it again and push to it if you have permissions. </p>

<p> <li> <code> git rm :</code> </li> Removes files from your index and your working directory so they will not be tracked. </p>

<p> <li> <code> git tag :</code> </li> Tags a specific commit with a simple, human readable handle that never moves. Example: git tag -a v1.0 -m 'this is version 1.0 tag'. </p>

<p> <li> <code> git remote add :</code> </li> This command is you to add your repository url to a project, you are type 'git remote add origin {{your repo url}} to set your repo, contribute to someone else repo you have to set the remote to theirs 'git remote add upstream {{destination_url}}. To show the list of all the remote added: do 'git remote -v' to remove a remote from the repo, git remote rm {{origin||upstream}}</p>

</ul>
