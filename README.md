# Toolset-Resources
## Table of Contents


[Introduction](#intro)  
[Free Virtual Environments](#virtual)  
[Linux Operating Systems](#Linux)  
[Network Security Monitoring & Intrusion Detection System Tools](#nsm)  
[Network Mapping, Discovery, & Assessment Tools](#nmap)
[Vulnerability Assessment and Penetration Testing Tools](#pen)  
[Threat Modeling Tools & Resources](#threat)  
[Cloud Security References and Resources](#cloud)  
[Writing and Reports](#writing)


## Introduction <a name="intro"></a>
This is a curated list of tools and tips for students in the National University MS and BS Cybersecurity Programs.

## Lab Environments

[Infosec Learning Labs](https://www.infoseclearning.com/index.aspx)  
[NICE Challenge](https://www.nice-challenge.com/)  
[National Cyber League](https://www.nationalcyberleague.org/)  
[Project Ares](https://edu-apprentice1.ares.circadence.com/)  


## Free Virtual Environments <a name="virtual"></a>

As a supplemental resource to the NU-ISLE environment and other commercial CSIA labs that will be used for most courses, the following VM tools may be used, which allows local system setup and configuration for students to practice with toolsets.  NOTE – most CSIA course assignments require the use of the either the NU-ISLE environment, where instructors have access to login and check the student’s work on a particular VM, or a hosted lab environment, where student activity is reported to the instructor; therefore, unless specifically given permission by an instructor to use a personal VM for an assignment, the options listed below are for students’ convenience only, to practice using the tools.

[VMWare Player](http://www.vmware.com/products/player/playerpro-evaluation.html)
[Oracle Virtual Box](https://www.virtualbox.org/ )


## Linux Operating Systems <a name="Linux"></a>

[Ubuntu](http://www.ubuntu.com/) 

### Ubuntu Documentation

[Ubuntu Help](https://help.ubuntu.com/)
[Ubuntu Wiki](https://wiki.ubuntu.com/)

[Fedora Linux](https://www.virtualbox.org/ )

### Fedora Documentation

[Fedora Docs Page](https://docs-old.fedoraproject.org/en-US/index.html)
[Fedora Project Wiki](https://fedoraproject.org/wiki/Fedora_Project_Wiki)

### Command Line Tips and References

[The Linux Command Line – A Complete Introduction by William Shotts (free downloadable PDF)]( http://linuxcommand.org/tlcl.php )

[A-Z Index of Bash command line for Linux (SS64.com)](http://ss64.com/bash/ )

### Using the Terminal
There are some Linux commands you should learn and become familiar with, but first, some background and syntax used in many lab assignments: 
When you open a Terminal (text prompt) session in Linux, you will see something similar to 
the following command prompt, which indicates logged-in user, the system name, and the 
current directory (in this case, “~” indicates the student’s Home directory): 
 [student@fedora ~] $ █     
{The cursor will be black on a light color background or white on a black background and it will blink} 
In the lab instructions, when you see a pound-sign “#” (aka hash mark), that indicates a comment and not part of the actual command; however, the particular comment may be telling you to enter a specific command, which would be entered immediately after the “$” (as in the sample command prompt above).  A comment can be entered on the same line as a command, after the full command and options/parameters are entered; the system will not execute anything after the “#” comment symbol.  This is useful in documenting scripts. 
Now, the Linux commands you should research and learn to use for the labs (with comments):  
$ su  # this will let you change from the current logged in user to a different user; such as ‘Root’; however, you must know the other user’s password 
$ sudo <command>  # or a similar command option (next line)   
$ sudo -i <command>  # these two let you issue a command with Admin rights; and you will be prompted to enter your login password   
$ chmod <options>  # modifies permissions to a folder/directory or file   
$ chown <options>  # changes ownership of a folder/directory or file   
$ ifconfig <options>  # lists the local network adapters and their settings; the most common option is ‘-a’ (for “all”)   
$ ls    # lists the files/folders within the current directory/folder the first character is lower-case “L” not the number one  
As other common commands are developed for the various lab assignments, they will be added to the section above. 

## Network Security Monitoring & Intrusion Detection System Tools <a name="nsm"></a>

[Security Onion](https://securityonion.net)  
[Bro IDS](https://www.bro.org)  
[Sguil: The Analyst Console for Network Security Monitoring](http://bammv.github.io/sguil/index.html)  
[Snorby](https://github.com/Snorby/snorby)  
[SOF-ELK® VM Distribution](https://github.com/philhagen/sof-elk/blob/master/VM_README.md)  
[Rock NSM](http://rocknsm.io)  
[Suricata IDS/NSM engine](https://suricata-ids.org)  
[Wireshark](https://www.wireshark.org)  
[Network Miner](http://www.netresec.com/?page=NetworkMiner)  
[CapLoader](http://www.netresec.com/?page=CapLoader)  
[SplitCap](http://www.netresec.com/?page=SplitCap)  
[How to: Split large packet captures with tcpdump](http://www.sysadminx.com/2013/01/25/how-to-split-large-packet-captures-with-tcpdump/)  

### EBooks available in the NU Library (Login required)

- Network Intrusion Analysis: Methodologies, Tools and Techniques for Incident Analysis and Response; Fichera, Joe and Bolt, Steven; 2013 

- Practical Packet Analysis: Using Wireshark to Solve Real-World Network Problems; Sanders, Chris; 2007 
 
- Snort 2.0 Intrusion Detection; Beale, Jay / Caswell, Brian / Foster, James C. / Posluns, Jeffrey; 2003 
 
- Network Flow Analysis; Lucas, Michael; 2010 


## Network Mapping, Discovery, & Assessment Tools <a name="nmap"></a>
[Network Mapper (NMAP)](https://nmap.org)  
[NMAP Reference Guide](https://nmap.org/book/man.html)  
[Zenmap GUI for NMAP](https://nmap.org/zenmap/)  
[OpenVAS](http://www.openvas.org)  
[Angry IP Scanner](https://angryip.org)  
 
## Vulnerability Assessment and Penetration Testing Tools <a name="pen"></a>

[Kali Linux](https://www.kali.org)  
[Kali Documentation](https://www.kali.org/kali-linux-documentation/)  
[Nessus](https://www.tenable.com/products/nessus/nessus-professional)  
[BlackArch Linux](https://blackarch.org)  
[BlackArch Download](https://blackarch.org/downloads.html)  
[BlackArch Documentation](https://blackarch.org/guide.html)  
[Parrot Security OS](http://parrotsec.org)  
[Parrot Security Download](http://parrotsec.org/download.php)  
[Parrot Security Documentation](https://docs.parrotsec.org/doku.php) 


## Threat Modeling Tools & Resources <a name="threat"></a>  
[Microsoft SDL Threat Modeling Tool](https://www.microsoft.com/en-us/sdl/adopt/threatmodeling.aspx)  
[Microsoft SDL Tool Download](https://www.microsoft.com/en-us/download/details.aspx?id=49168)  
[IT Infrastructure Threat Modeling Guide](https://technet.microsoft.com/en-us/library/dd941826.aspx)  
[Introduction to Threat Modeling (File Download](https://download.microsoft.com/.../9/3/5/.../Introduction_to_Threat_Modeling.ppsx)  
[Microsoft SDL Process: Design (go to SDL Practice #7 and open ‘Resources’) ](https://www.microsoft.com/en-us/sdl/process/design.aspx)  
[Elevation of Privelige Card Game](https://www.microsoft.com/en-us/sdl/adopt/eop.aspx)  
[OWASP Application Threat Modeling](https://www.owasp.org/index.php/Application_Threat_Modeling)  
[OWASP Threat Model Project](https://www.owasp.org/index.php/OWASP_Threat_Model_Project)  

### Videos  

[SDL Threat Modeling Tool](https://www.youtube.com/watch?v=iV2SAuTxIUc)  

[Threat Modeling Tool Principles](https://www.youtube.com/watch?v=wUt8gVxmO-0)  


## Cloud Security References and Resources <a name="cloud"></a>

[Cloud Security Alliance](https://cloudsecurityalliance.org)  
[ENISA Cloud Security Guidance](https://www.enisa.europa.eu/topics/cloud-and-big-data/cloud-security)  

## Writing and Reporting ##
[Bishop Fox Style Guide](https://www.bishopfox.com/blog/2018/06/reintroducing-the-cybersecurity-style-guide-v1-1/)




