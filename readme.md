## Command Comands
    ...shell					
    ls <path>		# Command
    ls ./			# Show Current Directory
    ls -a ./		#Show invis files of Current Directory
    ...
        
 	... shell		
	cd  <path>	#Command
	cd ./desktop	#Relative Path Changing Directory
	...
### Paths
.../Users/cchapman/ ... is the same as...~...

##### Current User's Home folder 

##### Absolute Paths
The entire path from the root .../... of your hard drive to the folder you are targetting.

Example:.../Users/cchapman/Desktop/Zero_to_Git...

##### Relative Paths

... ./ ...prefix for Relative path. "My current working directory"

...shell
cd ./Desktop
...

####### Parent Directry

'''..''''''
...shell
cd..				#Goes to the parent folder Directory
...

###### Be Careful
...shell
rm /
...

## Git Commands
One time commands
	...shell
	$ git config --global core.editor "nano"
	git config --global user.name "John Doe"
	git config --global user.email johndoe@example.com
	...

used once when starting a git repo

	...shell
	git init
	...

Used often Common Comands


	...shell
	git init
	git add <path>
	git status
	git commit -m "show message here(start with a verb)"


