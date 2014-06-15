README.txt

Profile Page Deployement

1. Install Git on Laptop
	a. www.macports.org
	b.open terminal on laptop

		$sudo port install git-core +svn +doc +bash_completion +gitweb

		The basic git cms begin as
		
		$git config

		--global

		. /etc/gitconfig   -----contains values for evrey user on the sysand thier  

								repos	




		C. Set up your username and email ---git uses this info for every commit
		
		$git congig --global user.name "yourusername"

		$git config --global user.email youremailaddress


		D. Set up Editor

		$git config --global core.editor editorname

		E. Set up Diff Tool
			see ch 7 for custom 	


		F. Check Settings
		
		$git config --list

		$git help < verb >

		$git < verb > --help

		$git help config 


2. To clone in laptop
	
	open terminal on mac

	$git clone <https:// address here from your repo on git hub>

	this will immediatley download your clone

	$ ls      to list your files

	$ cd     your folder

	to edit readme.tx if there is one 

	$ pico readme.txt

	this opens the editor in terminal and you can edit the readme file	



								




								
