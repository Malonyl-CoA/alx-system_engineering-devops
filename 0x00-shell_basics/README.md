									#Shell basics#


#This file contain discription for different shell script and how they have been put to use in this project.

	1.  0-current_working_directory : this script once executed it will print an absolute path of the working directory.

	2.  1-listit : this script once executed it will dispaly the content list of the current directory.
	
	3.  2-bring_me_home :this script will change the working directory to home directory once executed.

	4.  3-listfiles : this script will display the list of files in the working directory in long-format.

	5.  4-listmorefiles : this script will display all file even those that are hidden in current directory in long-format.
	
	6.  5-listfilesdigitonly : this script display the content of a current directory in long format with user and group IDs displayed numerically and hidden 		files.

	7.  6-firstdirectory : this script create directory my_first_directory in /tmp.

	8.  7-movethatfile : this  script move file betty inside my_first_directory in /tmp.

	9.  8-firstdelete : this script delete file betty form /tmp/my_first_directory.

	10. 9-firstdirdeletion : this script deletes directory /tmp/my_first_directory.

	11. 10-back : this script take you back to previous directory.

	12. 11-lists : this script list content of more than one directory.

	13. 12-file_type: this script contained command to identify type of file in agiven directory.

	14. 13-symbolic_link: this script contained acommandfunction to create symbolic or soft link.

	15. 14-copy_html: this script contain the command to copy all file of a certain type to anothe dir of file in this case I copied all html files from one 		folder to anther.

	16. 100-lets_move :this script contain command that moves all files beginning with an uppercase letter to another directory.

	17. 101-clean_emacs : this script contains command that deletes all emmacs backupfiles ending with ~

	18. 102-tree :this script contain command to create atree of directories appended one another.

	19. 103-commas: this script   Write a command that lists all the files and directories of the current directory, separat	    ed by commas (,).directory names should end with a slash (/) Files and directories starting with a dot (.) should be 	    listed The listing should be alpha ordered, except for the directories . and .. which should be listed at the very  	    beginning Only digits and letters are used to sort; Digits should come first You can assume that all the files we wi	    ll test with will have at least one letter or one digit The listing should end with a new line 

	20. school.mgc :the question was "Create a magic file school.mgc that can be used with the command file to detect School 	    data files. School data files always contain the string SCHOOL at offset 0." this task was alittle bit trickier that 	    other task here is the syntax to solve it 


				0 string SCHOOL School data
				!:mime School

	   the execute the following command to complete the task and push the results

				file -C -m school.mgc 


#Author : KASSIMU BORI

#Upcoming software engineer.

