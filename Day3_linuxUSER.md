# :pushpin: Linux For User

## :notebook_with_decorative_cover: Overview of kali-linux
- Specifically,i will going to show you with "kali linux " with gnome but you can have any kinda,BUT  Debian is recommended,
- Previouslynknown as Backtrack

---
 ## :one:  INFORMATION GATHERING 
- Tools for information gathering,in system ,network,host 
     :large_blue_diamond: dmitry
     :large_blue_diamond: ike-scan 
     :large_blue_diamond: legion
     :large_blue_diamond: maltego
     :large_blue_diamond: netdiscover
     :large_blue_diamond: nmap
    :large_blue_diamond: p0f
     :large_blue_diamond: recon-ng
     :large_blue_diamond: spiderfoot
 ## :two: Vulnerability Analysis 
  - Tools for Finding Vulnerabilities 
       :radio_button: legion
       :radio_button: lynis
       :radio_button: nikito 
       :radio_button: nmap 
       :radio_button: unix-prives. . .
## :three: Web Application Analysis
- Tools for Finding Vulnerabilities and exploits on websites.
     :o: burpsuite
    :o: commix
    :o: httrack 
     :o: paros
     :o: skipfish
     :o: sqlmap
     :o: webscarab
     :o: wpscan
    :o: ZAP
## :four: Database Assessment
- Tools for finding vulnerabilities and exploits on Databases.
   :diamond_shape_with_a_dot_inside: jSQL Injection
   :diamond_shape_with_a_dot_inside: mdb-sql
   :diamond_shape_with_a_dot_inside: oscanner
   :diamond_shape_with_a_dot_inside: sidguesser
   :diamond_shape_with_a_dot_inside: sqldict 
  :diamond_shape_with_a_dot_inside: SQLite data

---
   :diamond_shape_with_a_dot_inside: sqlmap
   :diamond_shape_with_a_dot_inside: sqlninja
   :diamond_shape_with_a_dot_inside: sqlsus
   :diamond_shape_with_a_dot_inside: tnscmd10g
## :five: Password Attacks 
- Tools for exploiting Passwords for login, websites, application, windows . . 
---
   :eight_spoked_asterisk: cewl
   :eight_spoked_asterisk: crunch
   :eight_spoked_asterisk: hashcat
   :eight_spoked_asterisk:hashcat
   :eight_spoked_asterisk: john
   :eight_spoked_asterisk: johnny
   :eight_spoked_asterisk: medusa
   :eight_spoked_asterisk: ncrack
   :eight_spoked_asterisk: ophcrack
   :eight_spoked_asterisk: rainbowcrack
   :eight_spoked_asterisk: rcracki_mt
   :eight_spoked_asterisk: wordlists
## :six: Wireless Attacks
- Tools for exploiting Wireless systems like wifi,bluetooth . .
---
     - aircrack-ng
     -chirp
   - cowpatty
    - fern wifi cra . . .
     - kismet
     - mdk3
    - mfoc
     -mfterm
    - pixiewps
     - reaver
     - wifite
## :seven: Reverse  Engineering
- Tools for exploiting Softwares ,Mobile Applications and any binary files
---
   :large_blue_circle: apktool
   :large_blue_circle: bytecode-vi. . .
   :large_blue_circle: clang
   :large_blue_circle: clang++
   :large_blue_circle: dex2jar
   :large_blue_circle: edp-debug. . .
   :large_blue_circle: ghidra
   :large_blue_circle: jadx-gui
   :large_blue_circle: javasnoop
   :large_blue_circle: NASM shell 
   :large_blue_circle: ollydpg
   :large_blue_circle: radare2
## :eight: Exploitation Tools
- Tools for exploiting Softwares, Mobile, Computers, websites and anythings
---
   - armitage
 - beef xss fra . . . 
   - metasploit Fram. . .
  - msf payloa. . .
- searchsploit
- social engin. . . 
    - sqlmap
    - termineter
## :nine: Sniffing & spoofing
- Tools for listening or hijacking networks
---
     - driftnet
    - ettercap-gr. . . 
    - hamster
    - macchanger
    - mitmproxy
   - netsniff-ng
    - responder
    - wireshark
## :keycap_ten: POST exploitation
- Tools for maintaining our access. Used after exploiting a system
---
    - backdoor-f. . . 
    - exe2hex
    - mimikatz
    - nishang
    - powersploit
    - proxychains4
 - weevely
## :one::one: Forensics
- Tools for Doing researches and investigate cyber Attacks. 
    - autopsy
    - binwalk
    - bulk_extrac. .  . 
    - chkrootkit
    - foremost
    - galleta
    - hashdeep
## :one::two: Reporting Tools
- Tools for report preparation.After some forensic you will get data and you will write report and these tools will help you.
---
    - cutycapt
    - dradis fram . . .
     -faraday IDE. .  .
     - maltego
     - pipal 
    - recordmyd. . . 
## :one::three: Social Engineering Tools
- Tools used for social engineering attacks 
---
   - backdoor-f . . .
   - beef xss fra . . .
   - maltego
   - msf paylo . . .
   -  social Engin. . . 
## :one::four: System Services
- Buttons used to start some services.
---
     - beef start 
     - beef stop
     - dradis start
     - dradis stop
## :one::five: Usually Used Applications 
- Softwares  for   some basic purposes
---
### *FOLDER MANAGERS :file_folder:
:a: Dolphin
:b: Thunar

C) Nautilus

---

## !Linux Commands
:white_check_mark: Linux System uses shell. The shell help us to communicate with the kernel and helps to execute codes.
:white_check_mark: Shell also colled "terminal"  
:white_check_mark: The terminal have 5 parts.
  :black_circle: Username = anony
   :black_circle: Hostname = Kali
   :black_circle: Current Diroctory = PATH
    :black_circle: Priviledge=$-(user),#-(root)
    :black_circle: Command Place = _
:white_check_mark: Home directory is ~
:white_check_mark: Local directory with .
:white_check_mark: All directory     
## Linux Commands Basics
- On Linux there are over 100 commands.But we will see the main and the useful only. 
- Also those commands have their own options and arguments .
---
### WHAT IS COMMAND???
## "Small programs that do one task well "
---
### ls/ list directory
- SYNOPSIS
   - ls [option] . . .[File] . . .
- DESCRIPTION
   - list information about the FILEs (the current directory by default).
:white_square_button: ls -l
:white_square_button: ls -a
:white_square_button: ls filename
:white_square_button: ls -R=> Recursive
:white_square_button: You can combine them => ls -Rla "linux hidden files start with dot".
---
### cd / Change directory
:arrow_forward: SYNOPSIS
  - cd[directory]
:arrow_forward: DESCRIPTION
   - It is used to change current working directory 
 - cd /  =>root
:arrow_forward: cd    =>home
:arrow_forward: cd.. =>1x back
:arrow_forward: cd../..=>2x back
:arrow_forward: cd foldername 

> if  folder name have space you have to add the name inside"foldername"
cd"foldername"
  ----
## Pwd / print working directory
- SYNOPSIS
    - Pwd[-option]
- DESCRIPTION
   - It prints the path of the working directory,starting from the root .
   - E.g after typing pwd:/home/omar/desktop/OSlab
   ---
## echo 
- SYNOPSIS 
   - echo[option] [string]
- DESCRIPTION 
    - echo command in linux is used to display  line of text/string that are passed as an argument. This is a built in command that is mostly used in shell scripts and batch files to output status text to the screen or a file .
- you can write texts into files.
     - echo text >file.txt
- you can add texts(append) 
    -echo text >>file.txt   
    ---      
## cat / head / tail / less
- SYNOPSIS
   - cat[FILE]
- DESCRIBTION
   - Used to show the content of a file
   ---
   ## touch
 -   synopsis
       - touch[FIIE1][FILE2][FILE3]
  - DESCRIBTION
     -  Creates any kind of files with the name you gave it. With empty inside
     ---

     ## Mkdir / Make Directory
- SYNOPSIS       
   - mkdir[FOLDER-NAME 1][FOLDER-NAME 2][FOLDER-NAME 3]
- DESCRIPTION
   
   Creates Folder with the name u gave it.

         - DON'T forget to add the "" when you are using folders with space between them.
---
## clear 
- SYNOPSIS 
    - clear
- DESCRIPTION
    - clears your screen.
    ---
 ## rm / remove
- SYNOPSIS 
    - rm [File 1][File 2][File 3]
- DESCRIPTION
      - Remove file
 - rm -r => recursive(for folders)
 - rm -i => for prompt(ask)
 - rm -f => force delete
 > you can use them in combination too like, rm -rf'filename'
 ---
 ##  cp| mv /copy,move
- SYNOPSIS
    - cp[oldFILEPLACE][newFileplace]
    - mv[oldFileplace][newFileplace]
 - DESCRIPTION
     - Copy/move files & Folders
 ---
 #  grep
- grep[options]pattern[files]
 - The grep filter searches a file for a particular pattern of characters and displays all lines that contain that pattern. The pattern that is searched in the file is referred to as the regular expression (grep stands for global search for regular expression and print out).
- grep -i"search"file
     -  -case insensetive 
- grep -c"search"file 
    - -count numbers
- grep -l"search"file
    - -displays filename
- grep -R"search"foldername   
    - -search text in folders
 ## Wc - Word count 
- SYNOPSIS
  - wc [option]...[file]...
- DESCRIPTION
  - It is used to find out number of lines word count, byte and characters count in the files specified in the file arguments.

LINE(-l)    WORD(-w)      BYTE(-c)
## Multiple Command Executions
- You can run / execute multiple commands in one line.
- using 3 methods
    - And (&&)
    - Or (||)
    - Pipeing (|)
## AND (&&)
- On AND operation all commands you entered will be executed .
- If both are working without error 
## OR (||)
- On OR operation the command will executed.If it have error or not
## Pipeing(|)
- On pipe,will help you run commands by using the output of the first command as the input for the next one.