####README for the_game git repository

#####Directions for how to clone the repository

* Download [git for Windows](http://git-scm.com/download/win)
 * While installing, all of the defaults are fine
* Open Git Bash
 * Make a directory that you want to clone the repository into
  * mkdir _directory name_
  * cd _directory name_
 * Run this commands to clone the repository:
  * git clone https://github.com/danbox/the_game.git
  * This will create another directory called the_game which will contain everything in the repository
 * In order to create your own branch run these commands: 
  * git branch _branchname_
   * This will create your own branch
  * git checkout _branchname_
   * This will switch your new branch to the active branch.  This can be undone by running git checkout master to switch back to master
  * git merge _branchname_
   * This will merge the changes in your branch to the master branch
 * In order to add and push commits to the repo run these commands:
  * git add _filename_
  * git push origin _branchname_
