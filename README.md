# Awesome Mainframe Hacking 
![Awesome Mainframe Hacking](https://img.shields.io/badge/mainframe-hacking-lightgrey.svg) ![Awesome Hacking](https://img.shields.io/badge/awesome-hacking-red.svg) ![Awesome community](https://img.shields.io/badge/awesome-community-green.svg) <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a>


List of Awesome Mainframe Hacking/Pentesting Resources.
This list is a collection of resources available online to learn Mainframe Penetration Testing & Security.

Special thanks to [@mainframed767](https://twitter.com/mainframed767), [@bigendiansmalls](https://twitter.com/bigendiansmalls), [@ayoul3__](https://twitter.com/ayoul3__) and many other researchers for all their work in this field. 

[Contributions](contributing.md) are welcome !

Table of Contents
=================

* [IBM zSeries](#-IBM-zSeries)
 	* [Books](#-Books)
 	* [Tutorials](#-Tutorials)
 	* [Scripts & Tools](#-Scripts-and-Tools)
 	* [Presentations & Talks](#-Presentations-and-Talks)
 	* [ACF2 Specific references](#-ACF2-Specific-references)
 	* [Misc](#-misc)
* [IBM iSeries](#-IBM-iSeries)
 	* [iSeries Books](#-iSeries-Books)
 	* [Tutorials & Checklists](#-Tutorials-and-Checklists)
 	* [Tools](#-Tools)
 	* [iSeries Presentations & Talks](#-iSeries-Presentations-and-Talks)
 	* [Miscellaneous](#-miscellaneous)

 
 
# [↑](#table-of-contents) IBM zSeries

## [↑](#table-of-contents) Books
* Amazon - [Mainframe Basics for Security Professionals_ Getting Started with RACF - Ori Pomerantz, Barbara Vander Weele, Mark E. Nelson, Tim Hahn (2008, IBM Press)](https://www.amazon.com/Mainframe-Basics-Security-Professionals-paperback/dp/0133763048)
* Amazon - [IBM Redbooks - Introduction to the New Mainframe: z/OS Basics](https://www.amazon.com/Introduction-New-Mainframe-OS-Basics/dp/0738435341)
* PDF - [PoCorGTFO#12 - Page 32 - A JCL Adventure with Network Job Entry](https://www.exploit-db.com/download/40624)


## [↑](#table-of-contents) Tutorials
* [Emulating a MVS/zOS with Hercules](https://famicoman.com/2018/06/28/emulating-a-z-os-mainframe-with-hercules/)
* [bigiron - Wiki/Collection of materials related to IBM z/OS security](https://github.com/v-p-b/bigiron)
* [TSO Tutorial](http://www.jaymoseley.com/hercules/tso_tutor/tsotutor.htm)
* [Z/OS Introduction- An IBM Redbooks video course](https://www.redbooks.ibm.com/redbooks.nsf/redbookabstracts/crse0304.html?Open)
* [Multiple Mainframe Security guides from Chicago Classic Computing](http://chiclassiccomp.org/docs/content/computing/IBM/Mainframe/MainframeSecurity/)
* [Using UNIX System Services to escalate your privileges on z/OS](https://www.bigendiansmalls.com/all-aboard-the-uss-exploits/)

## [↑](#table-of-contents) Scripts and Tools
* [TN3270 Clients - X3270](http://x3270.bgp.nu/)
* [Multipurpose Nmap Scripts](https://github.com/nmap/nmap/tree/master/scripts)
	* tn3270-screen.nse
	* tso-enum.nse
	* tso-brute.nse
	* vtam-enum.nse
	* lu-enum.nse
	* cics-enum.nse
	* cics-info.nse
	* cics-user-brute.nse
	* cics-user-enum.nse
* [TPX Brute - The z/OS TPX logon panel brute forcer](https://github.com/quentinhardy/TPX-Brute)
* [RACF Database Parser](https://github.com/bigendiansmalls/racfdbparse)
* Mainframe Application pentesting (CICS etc.)
	* [CICSPwn](https://github.com/ayoul3/cicspwn)
	* [BIRP](https://github.com/sensepost/birp)
	* [CICSshot - Take screenshots of CICS](https://github.com/ayoul3/cicsshot)
	* [Hacked wc3270 emulator](https://github.com/ayoul3/wc3270_hacked)	
* zOS Enumeration Scripts
	* [All in one Enumeration of information like VERSION, APF Libraries, SVCs, USERS etc. on Z/OS ](https://github.com/mainframed/Enumeration)
	* [Collection of REXX Scripts by @ayoul3__(https://github.com/ayoul3/Rexx_scripts)
	* [SETRRCVT by @jaytay79](https://github.com/jaytay79/zos/blob/master/SETRRCVT.rexx)
* [FTP - JCL commmand execution - Metasploit Modules by @bigendiansmalls](https://github.com/rapid7/metasploit-framework/blob/master/documentation/modules/exploit/mainframe/ftp/ftp_jcl_creds.md)
* [Metasploit Payloads for z/OS](https://github.com/rapid7/metasploit-framework/tree/12198a088132f047e0a86724bc5ebba92a73ac66/modules/payloads/singles/cmd/mainframe)
* [NC110-OMVS Netcat for z/OS OMVS](https://github.com/mainframed/NC110-OMVS)
* [TShOcker - Mini command interpreter for TSO & UNIX accessible by NetCat](https://github.com/mainframed/TShOcker)		
* [zOS Privilege Escalation scripts by ayoul3__](https://github.com/ayoul3/Privesc)
* [Note on TESTAUTH command for running a program in elevated state](https://github.com/zBit31/testauth)
* [zOSFTPlib - python ftplib-like library specifically for Z/OS](https://pypi.org/project/zosftplib/)
  
 
## [↑](#table-of-contents) Presentations and Talks
* [Video - All the talks by Soldier of FORTRAN (@mainframed767)](https://www.youtube.com/playlist?list=PLBVy6TfEpKmEL56fb5AnZCM8pXXFfJS0n)
* [How to Break into z/OS Systems - Staurt Henderson](http://www.stuhenderson.com/XBRKZTXT.PDF)
* [How to Break Into z/OS Systems Through USS, TCP/IP, and the Internet](http://www.stuhenderson.com/STUuss01.pdf)
* [Video - Mainframe [z/OS] Reverse Engineering & Exploit Development by @bigendiansmalls](https://www.bigendiansmalls.com/files/us-18-Rikansrud-Mainframe-[zOS]-Reverse-Engineering-and-Exploit-Development_Publish.mp4)
* [Video - Security Necromancy : Further Adventures in Mainframe Hacking by Soldier of FORTRAN (@mainframed767) & @bigendiansmalls](https://www.youtube.com/watch?v=LgmqiugpVyU)
* [Top 10 Security Vulnerabilities in z/OS by John Hillman (Vanguard)](https://chapters.theiia.org/fort-worth/ChapterDocuments/zOS%20Security%20Audit%20Top%20Ten%20-%20ISACA.pdf)
* [The current state of Mainframe Hacking by Phil Young - Soldier of FORTRAN (@mainframed767)](https://www.slideshare.net/PhilipYoung14/philip-young-current-state-of-mainframe-hacking-vanguard-101016)
* [Advanced Mainframe Hacking by Phil Young - Soldier of FORTRAN (@mainframed767)](https://www.slideshare.net/PhilipYoung14/advanced-mainframe-hacking)
* [Gaps in your Defense: Hacking the Mainframe by Soldier of FORTRAN (@mainframed767)](https://www.slideshare.net/PhilipYoung14/ca-world-mft1755-gaps-in-your-defense-hacking-the-mainframe-philip-young)
* [Video - Gaps in your Defense: Hacking the Mainframe by Soldier of FORTRAN (@mainframed767)](https://www.youtube.com/watch?v=1G5Q2sduexs)
* [Hacking Mainframes; Vulnerabilities in applications exposed over TN3270 by Dominic White (Sensepost)](https://www.slideshare.net/sensepost/vulnerabilities-in-tn3270-based-application)
* [Video - Hacking Mainframes; Vulnerabilities in applications exposed over TN3270 by Dominic White (Sensepost)](http://www.irongeek.com/i.php?page=videos/derbycon4/t217-hacking-mainframes-vulnerabilities-in-applications-exposed-over-tn3270-dominic-white)
* [Video - Ransomware on the Mainframe: Checkmate by @bigendiansmalls](https://www.youtube.com/watch?v=i-DbTy3bEj8)
* [Video - Learning Mainframe Hacking: Where the hell did all my free time go? by @bigendiansmalls](http://www.irongeek.com/i.php?page=videos/derbycon5/stable31-learning-mainframe-hacking-where-the-hell-did-all-my-free-time-go-chad-rikansrud)
* [Post exploit goodness on a Mainframe SPECIAL is the new root by (@ayoul3__)](https://cansecwest.com/slides/2018/Post%20exploit%20goodness%20on%20a%20Mainframe%20SPECIAL%20is%20the%20new%20root%20-%20Ayoub%20Elaassal,%20PwC%20France.pdf)
* [Video - Hacking Customer Information Control System (CICS) by Ayoub Elaassal (@ayoul3__)](https://www.youtube.com/watch?v=KnY0Gg_WSLU)
* [Video - IBM Networking Attacks-Or The Easiest Way To Own A Mainframe by Martyn Ruks](https://www.youtube.com/watch?v=r9hOiXtrumM)
* [Video - Cracking Mainframe Passwords by Nigel Pentland](https://www.youtube.com/watch?v=scVojIRxv-M)
* [Video - Exploiting the Mainframe - Z/OS integrity 101 by Mark Wilson & Ray Overby](https://www.youtube.com/watch?v=7UVrF8skbHU)
* [Video - A Gentle Introduction to Hacking Mainframes by Dan Helton](https://www.youtube.com/watch?v=ZfUBv2Ac29Q)

   
## [↑](#table-of-contents) ACF2 Specific references
* [CA ACF2 for z/OS - 16.0 Documentation](https://docops.ca.com/ca-acf2-for-z-os/16-0/en)
* [GIAC - ACF2 Mainframe Security](https://www.giac.org/paper/gsec/2812/acf2-mainframe-security/104768)


## [↑](#table-of-contents) Misc
* [Mainframe Hacking - Choose Your own Adventure Game](https://archive.org/details/MainframeHackingCYOA)
* [Evil Mainframe Hacking Training/Course](https://evilmainframe.com/)
* [CBT Tape - Collection of Freeware & Open Source distribution of IBM mainframe MVS & OS/360 Environments](http://www.cbttape.org/)
* [z/OS Internet Library by IBM - Collection of manuals,guides & books about z/OS ](https://www-01.ibm.com/servers/resourcelink/svc00100.nsf/pages/zosInternetLibrary)
* [DoD Security Technical implementation Guides(STIGS) - Search for ACF2, Z/OS, RACF etc.](https://public.cyber.mil/stigs/downloads/)


# [↑](#table-of-contents) IBM iSeries

## [↑](#table-of-contents) iSeries Books
* Amazon - [Hacking iSeries by Shalom Carmel](https://www.amazon.com/Hacking-iSeries-Shalom-Carmel/dp/1419625012)
* Amazon - [Mastering IBM i: The Complete Resource for Today's IBM i System by Jim Buck & Jerry Fottral](https://www.amazon.com/Mastering-IBM-Complete-Resource-Todays/dp/1583473564)
* PDF - [The IBM AS400 A technical introduction](https://www.ibm.com/developerworks/community/files/basic/anonymous/api/library/7cd1e29f-0699-4929-a741-516ce47295a8/document/745425bf-c00a-4a8d-bd8f-1f8e14ef9e65/media)


## [↑](#table-of-contents) Tutorials and Checklists
* [AS/400 Security Assessment Mindmap](http://www.toolswatch.org/wp-content/uploads/2013/02/AS400.jpg)

## [↑](#table-of-contents) Tools
* [hack400tool - security handling tools for IBM Power Systems (formerly known as AS/400)](https://github.com/hackthelegacy/hack400tool)
* [Hash generator for IBM System i hashes (DES, SHA-1)](http://hackthelegacy.org/index.php?p=/discussion/10/hash-generator-for-ibm-system-i-hashes-des-sha-1-updated)
* [AS/400 SHA-1 hash format plugin for John the Ripper](http://hackthelegacy.org/index.php?p=/discussion/9/our-as-400-sha-1-hash-format-plugin-for-john-the-ripper-now-included-in-the-bleeding-jumbo-build)

## [↑](#table-of-contents) iSeries Presentations and Talks
* [Hack the Legacy: IBM I aka AS400 Revealed by Bart Kulach ](https://www.youtube.com/watch?v=JsqUZ3xGdLc)
* [AS/400 for pentesters by Shalom Carmel](https://www.blackhat.com/presentations/bh-europe-06/bh-eu-06-Carmel/bh-eu-06-Carmel.pdf)

## [↑](#table-of-contents) Miscellaneous
* [AS400i.com](http://as400i.com/)
* [Hack The Legacy Website](http://hackthelegacy.org/)
