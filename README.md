how-to
======

How-to projects as general knowledge and useful procedures

## Obtaining submodules

The submodule directory is there, but empty. 
You must run two commands: `git submodule init` to initialize your local configuration file, and `git submodule update` to fetch all the data from that project and check out the appropriate commit listed in your superproject.


## Adding submodules

To add a new submodule into this Git repository execute these steps from a local clone:

- Add the submodule

	```bash
	git submodule add [git_repo]
	```

	Where [git_repo] is the Git Read-only URI starting with 'git://' (for instance [git://github.com/logoff/HelloOSGiSpringSecurity.git](git://github.com/logoff/HelloOSGiSpringSecurity.git))

- Commit and push the changes to this repository

	```bash
	git commit
	git push upstream
	```
	In this case, upstream is the Git remote with write permissions ([https://github.com/dana-i2cat/how-to.git](https://github.com/dana-i2cat/how-to.git)). It will be necessary to provide credentials after the last command.

 The submodule will be added to this Git repository at this point.