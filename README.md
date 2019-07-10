# Awesome Mainframe Hacking

List of Awesome Mainframe Hacking/Pentesting Resources
This list is a collection of resources available online to learn Mainframe Penetration Testing & Security.

Special thanks to @mainframed67, @bigendiamsmalls, @ayoul3 for all their work in this field. 

Pull requests are welcome.

Table of Contents
=================

* [IBM zSeries](#-IBM-zSeries)
 	* [Books & Tutorials](#-books-&-tutorials)
 	* [Tools](#-Scripts-&-tools)
 	* [Presentations & Talks](#-presentation-&-talks)
 	* [ACF2 Specific references](#-acf2-specific-references)
 	* [Misc](#-misc)
* [IBM iSeries](#-iSeries)

 
 
# [↑](#table-of-contents) IBM zSeries

## [↑](#table-of-contents)Books & Tutorials
* [Mainframe Basics for Security Professionals_ Getting Started with RACF - Ori Pomerantz, Barbara Vander Weele, Mark E. Nelson, Tim Hahn (2008, IBM Press)](https://www.amazon.com/Mainframe-Basics-Security-Professionals-paperback/dp/0133763048)
* [IBM Redbooks - Introduction to the New Mainframe: z/OS Basics](https://www.amazon.com/Introduction-New-Mainframe-OS-Basics/dp/0738435341)
* [PoCorGTFO#12 - Page 32 - A JCL Adventure with Network Job Entry](https://www.exploit-db.com/download/40624)
* [Emulating a MVS/zOS with Hercules](https://famicoman.com/2018/06/28/emulating-a-z-os-mainframe-with-hercules/)
* [bigiron - Wiki/Collection of materials related to IBM z/OS security](https://github.com/v-p-b/bigiron)
* [TSO Tutorial](http://www.jaymoseley.com/hercules/tso_tutor/tsotutor.htm)
* [Z/OS Introduction- An IBM Redbooks video course](https://www.redbooks.ibm.com/redbooks.nsf/redbookabstracts/crse0304.html?Open)
* [Multiple Mainframe Security guides from Chicago Classic Computing](http://chiclassiccomp.org/docs/content/computing/IBM/Mainframe/MainframeSecurity/)
* [Using UNIX System Services to escalate your privileges on z/OS](https://www.bigendiansmalls.com/all-aboard-the-uss-exploits/)


## [↑](#table-of-contents) Scripts & Tools
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
	* [Collection of REXX Scripts by @ayoul3](https://github.com/ayoul3/Rexx_scripts)
	* [SETRRCVT by @jaytay79](https://github.com/jaytay79/zos/blob/master/SETRRCVT.rexx)
* [FTP - JCL commmand execution - Metasploit Modules by @bigendiansmalls](https://github.com/rapid7/metasploit-framework/blob/master/documentation/modules/exploit/mainframe/ftp/ftp_jcl_creds.md)
* [Metasploit Payloads for z/OS](https://github.com/rapid7/metasploit-framework/tree/12198a088132f047e0a86724bc5ebba92a73ac66/modules/payloads/singles/cmd/mainframe)
* [NC110-OMVS Netcat for z/OS OMVS](https://github.com/mainframed/NC110-OMVS)
* [TShOcker - Mini command interpreter for TSO & UNIX accessible by NetCat](https://github.com/mainframed/TShOcker)		
* [zOS Privilege Escalation scripts by Ayoul](https://github.com/ayoul3/Privesc)
* [Note on TESTAUTH command for running a program in elevated state](https://github.com/zBit31/testauth)
  
 
## [↑](#table-of-contents) Presentations & Talks
* [All the talks by Soldier of FORTRAN (@mainframed767)](https://www.youtube.com/playlist?list=PLBVy6TfEpKmEL56fb5AnZCM8pXXFfJS0n)
* [How to BReak into z/OS Systems - Staurt Henderson](http://www.stuhenderson.com/XBRKZTXT.PDF)
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

   
## [↑](#table-of-contents) ACF2 Specific references
* [CA ACF2 for z/OS - 16.0 Documentation](https://docops.ca.com/ca-acf2-for-z-os/16-0/en)
* [GIAC - ACF2 Mainframe Security](https://www.giac.org/paper/gsec/2812/acf2-mainframe-security/104768)


## [↑](#table-of-contents)Misc
* [Mainframe Hacking - Choose Your own Adventure Game](https://archive.org/details/MainframeHackingCYOA)
* [z/OS Internet Library by IBM - Collection of manuals,guides & books about z/OS ](https://www-01.ibm.com/servers/resourcelink/svc00100.nsf/pages/zosInternetLibrary)
* [Mainframe Hacking Training/Course](https://evilmainframe.com/)
* [CBT Tape - Collection of Freeware & Open Source distribution of IBM mainframe MVS & OS/360 Environments](http://www.cbttape.org/)
* [DoD Security Technical implementation Guides(STIGS) - Search for ACF2, Z/OS, RACF etc.](https://public.cyber.mil/stigs/downloads/)


# [↑](#table-of-contents) IBM iSeries

## [↑](#table-of-contents)Work In Progress..
