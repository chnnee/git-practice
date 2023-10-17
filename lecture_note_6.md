### Version Control
Systems that track and manage changes to files and directories

### Git's file tracking system
-- ex) Simply recording the changes that occurred in file a (x),
       Saving all the **actual** changes that occurred in file a (o). This is a snapshot. 
       
### Recovery of a central computer
git uses a method **distributed**.
Each local computer retains a copy of the database held by the central server computer.
so, if your central server fails or your files are damaged, you can easily recover your central system again because each local computer has a copy of it.

### Working Directory
: Typical directories for containing projects that you create and work on Linux or other OS. 
In Git, files or directories in this working directory are first transferred to the intermediate stage, 'staging area'.
(staging area: Ready to go to the 'commit')
(commit: you have recorded the specifically(snapshot))

### 3 levels of configuration for Git
-- First, System level: --system option. Affects all uses and repositories on the system. 
ex) file: /etc/gitconfig
-- Second, User level/Global level: --global option. Affects all repositories of a current user.
ex) ~/.config/git/config
-- Third, Local level: --local option. Specific to the current repository.
ex) file: .git/gitconfig

### Setting for Config
Usually, Set to global.
System administration privileges are required to enable
Saved in a file called 'Deep Config'
You only need to do the config command once in the beginning.