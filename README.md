# cool-git-commands
All cool git commands that can saves you time and maybe your life. :)

<ul>

<p> <li> <code> git reflog : </code> </li>   It shows all the previous commits you've made in your repo. It can be useful when you wants to reverts your work to a previous state.  </p>


<p> <li>  <code> Git standup :  </code> </li> Lists all your yesterday's commits. The downside is its doesn't come with every git client. So you have to install it. Follow the guide <a href="https://github.com/kamranahmedse/git-standup"> here </a> to install. </p>


<p> <li>  <code> Git reset --hard  : </code> </li>  This can be a lifesaver when you've made  a mistake in  your repo and decided to reverts your repo to the previous state. Just use <italic> Git reset --hard <The SHA1 of the commits you want to revert to>  </italic> . First of all you have to use <italic> Git reflog </italic> or <italic> Git standup </italic> to get the SHA1 of the commits you wanted to revert your repo to. </p> 


<p> <li>  <code> Git add . : </code> </li>  So , you've made changes to several files on your local repo and you want to stage them all for commits. Instead of looking for all the files you made changes to before you commits. You can just use <italic> git add . </italic> to add all those files at once instead of adding them one by one. </p>


<p> <li>  <code> Git Stash : </code> </li> It  takes all of the staged changes and stores them away somewhere. It can be helpful when you don't want to push  particular changes yet and still don't want to delete them. </p>

<p> <li> <code> git commit --amend :  </code> </li> 

Let say you made a typo in your  commit message you can use it to change the message instead of making a new commit all over again. </p>

<p> <li> <code> git blame : </code> </li> If you want to play the blame game this command comes handy. It shows the particular changes made to files , the name of the author and the time they made it.In case a person has broken any of your features you can go ahead and YELL at the person who made those mistakes. </p>


</ul> 