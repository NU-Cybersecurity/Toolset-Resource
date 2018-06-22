# Toolset-Resource
## Table of Contents


[Introduction](#intro)
[Free Virtual Environments](#virtual)
[Linux Operating Systems](#Linux)



## Introduction <a name="intro"></a>
This is a curated list of tools and tips for students in the National University MS and BS Cybersecurity Programs.

## Lab Environments

[Infosec Learning Labs](https://www.infoseclearning.com/index.aspx )
[NICE Challenge](https://www.nice-challenge.com/ )
[National Cyber League](https://www.nationalcyberleague.org/ )
[Project Ares](https://edu-apprentice1.ares.circadence.com/)


## Free Virtual Environments <a name="virtual"></a>

As a supplemental resource to the NU-ISLE environment and other commercial CSIA labs that will be used for most courses, the following VM tools may be used, which allows local system setup and configuration for students to practice with toolsets.  NOTE – most CSIA course assignments require the use of the either the NU-ISLE environment, where instructors have access to login and check the student’s work on a particular VM, or a hosted lab environment, where student activity is reported to the instructor; therefore, unless specifically given permission by an instructor to use a personal VM for an assignment, the options listed below are for students’ convenience only, to practice using the tools.

[VMWare Player](http://www.vmware.com/products/player/playerpro-evaluation.html)
[Oracle Virtual Box](https://www.virtualbox.org/ )


## Linux Operating Systems <a name="Linux"></a>

[Ubuntu](http://www.ubuntu.com/) 

###Ubuntu Documentation

[Ubuntu Help](https://help.ubuntu.com/)
[Ubuntu Wiki](https://wiki.ubuntu.com/)

[Fedora Linux](https://www.virtualbox.org/ )

###Fedora Documentation

[Fedora Docs Page](https://docs-old.fedoraproject.org/en-US/index.html)
[Fedora Project Wiki](https://fedoraproject.org/wiki/Fedora_Project_Wiki)

###Command Line Tips and References

[The Linux Command Line – A Complete Introduction by William Shotts (free downloadable PDF)]( http://linuxcommand.org/tlcl.php )

[A-Z Index of Bash command line for Linux (SS64.com)](http://ss64.com/bash/ )

###Using the Terminal
There are some Linux commands you should learn and become familiar with, but first, some background and syntax used in many lab assignments: 
When you open a Terminal (text prompt) session in Linux, you will see something similar to 
the following command prompt, which indicates logged-in user, the system name, and the 
current directory (in this case, “~” indicates the student’s Home directory): 
 [student@fedora ~] $ █     
{The cursor will be black on a light color background or white on a black background and it will blink} 
In the lab instructions, when you see a pound-sign “#” (aka hash mark), that indicates a comment and not part of the actual command; however, the particular comment may be telling you to enter a specific command, which would be entered immediately after the “$” (as in the sample command prompt above).  A comment can be entered on the same line as a command, after the full command and options/parameters are entered; the system will not execute anything after the “#” comment symbol.  This is useful in documenting scripts. 
Now, the Linux commands you should research and learn to use for the labs (with comments): 
$ su  # this will let you change from the current logged in user to a different user; 
  # such as ‘Root’; however, you must know the other user’s password 
  # students are not given the Root password for the NU-ISLE VMs 
$ sudo <command>  # or a similar command option (next line) 
$ sudo -i <command>  # these two let you issue a command with Admin rights; and 
    # you will be prompted to enter your login password 
$ chmod <options>  # modifies permissions to a folder/directory or file 
$ chown <options>  # changes ownership of a folder/directory or file 
$ ifconfig <options>  # lists the local network adapters and their settings; the most 
    # common option is ‘-a’ (for “all”) 
$ ls    # lists the files/folders within the current directory/folder 
    # the first character is lower-case “L” not the number one 
As other common commands are developed for the various lab assignments, they will be added to the 
section above. 





