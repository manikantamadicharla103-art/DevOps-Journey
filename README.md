# Day 01 - Linux Basics (Fedora) ## Objective Today I started my DevOps journey by learning the basic Linux commands on Fedora. I understood how to navigate the Linux file system and create files and directories using the terminal. --- ## Topics Covered ### 1. Linux Linux is a free and open-source operating system widely used for servers, cloud computing, DevOps, and software development. Most cloud servers run Linux. ### 2. Terminal The terminal is a command-line interface (CLI) that allows users to interact with the operating system by typing commands. DevOps engineers use the terminal daily for automation and server management. ### 3. Linux File System Linux organizes data in a hierarchical directory structure. Common directories: - / : Root directory - /home : User home directories - /etc : System configuration files - /var : Log files and variable data - /usr : Installed applications - /tmp : Temporary files - /root : Home directory of the root user --- ## Commands Learned ### 1. pwd **Definition:** Displays the current working directory. **Syntax**
bash
pwd
**Example**
bash
pwd
**Output**
text
/home/sai
--- ### 2. ls **Definition:** Lists files and directories inside the current directory. **Syntax**
bash
ls
Useful options:
bash
ls -l
ls -a
--- ### 3. mkdir **Definition:** Creates a new directory (folder). **Syntax**
bash
mkdir DevOps
--- ### 4. cd **Definition:** Changes the current working directory. **Syntax**
bash
cd DevOps
cd ..
cd ~
--- ### 5. touch **Definition:** Creates an empty file. **Syntax**
bash
touch linux.txt
--- ## Practical Exercise Commands executed:
bash
pwd
ls
mkdir DevOps
cd DevOps
mkdir Linux
cd Linux
touch linux.txt docker.txt aws.txt
ls
pwd
--- ## Key Learnings - Learned how Linux organizes files. - Learned how to navigate directories. - Created folders using mkdir. - Created files using touch. - Verified my location using pwd. - Listed files using ls. ---
