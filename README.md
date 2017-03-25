# cool-git-commands
All cool git commands that can saves you time and maybe your life. :)


<b> Command : </b> <code> git reflog </code> </br> 


<p> <b> Use : </b> It shows all your past commits. Useful when you wants to track down any commits of yours or reverts to a previous state. </p>


<b> Command : </b> <code> Git standup </code> </br>


<p> <b> Use : </b> Shows all your yesterday's commits. It comes handy when you want to poke nose into what your colleagues did in the other day. The downside is its doesn't come with every git client. So you have to install it. Follow the guide <a href="https://github.com/kamranahmedse/git-standup"> here </a> to install. </p>


<b> Command : </b> <code> Git reset --hard <your past commit SHA1> </code> </br> 

<p> <b>  Use : </b> This can be a lifesaver when you've made  a mistake in  your repo and decided to reverts your repo to the recent state. Easy , just use <italic> Git reset --hard <Your past commits SHA1> </italic> to move to a previous state. First of all you have to use <italic> Git reflog </italic> or <italic> Git standup </italic> to get the SHA1 of the commits you wanted to revert your repo to. </p> 

