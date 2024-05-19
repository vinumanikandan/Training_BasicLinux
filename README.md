# Module 1 : Basic Linux

Training_Linux

## What is OS

OS (**Operating System**) is a fully integrated set of specialized programs that manages, controls and monitors the execution of all the programs/resources of the computer and acts an interface between the software and the computer hardware.

![OS Screenshot](images/Different_OS.png)


## What is Linux OS ?
Linux (**Like Unix**) based on unix OS and is built upon the Linux Kernel. 

## What is kernel ?
The Linux Kernel is the brain of the operating system because it manages how the computer interacts with its hardware and resources to make it works smoothly and efficiently

## Features of Linux

- **Stable**: One of the most stable OS in the world
- **Safe**: Virus-free
- **Adjustable**: Many distributions, you can build your own Linux distribution
- **Free**: Open-source code
- **Multiuser**: Possible to connect to the same server (remote) and execute different programs at the same time
- **Multitasking**: Multiple processes can run on the same server at the same time
- **Networking**: The network is essential for remote access
- **Various user interfaces**: Both text-only and graphical interfaces are available


## Linux Flavours
![Project Screenshot](images/Linux_Flavours.png)

## Different types of Systems 

 **Servers & Desktop**
![System Screenshot](images/Server_vs_Desktop.png)

**HPC** (High Performance Clusters)

HPC is basically a collection of multiple servers connected together along with a job schedular for workload managment.

![System Screenshot](images/HPC.png)


**Basic Linux Terminal Commands**

|Linux Commands|Functions|example|
|:---:|:---:|:---:|
|ls |Displays information about files in the current directory| ls |
|pwd |Displays the current working directory| pwd |
|mkdir |Creates a directory| mkdir FOLDERNAME|
|cd |To navigate between different folders| cd /path/to/FOLDERNAME|
|rm -rf |Remove directories  with files and sub directories| rm -rf FOLDERNAME |
|cp |Copy files from one directory to another| cp FOLDERNAME/FILENAME FOLDERNAME2/FILENAME |
|cp |Copy directory from one directory to another| cp FOLDERNAME/ FOLDERNAME3|
|rsync |Copy directory from one directory to another| rsync -avP FOLDERNAME/ FOLDERNAME3|
|mv |Rename and Replace the files|mv FOLDERNAME/ NEWFOLDERNAME|
|rm -rf |Delete folders & files| rm -rf FOLDERNAME/FILENAME|
|ln -s |Create shortcuts/symbolic link to other files| ln -s /path/to/FOLDER/FILENAME FILENAME|
|man |Access manual for all Linux commands| man ls|
|ssh|connecting to a server|ssh -p XXXX USERNAME@DOMAIN|
|chmod|granting/changing permission for folders/files|chmod -R 777 /path/to/FOLDER/|

**Basic Linux Terminal Commands related to files**

|Linux Commands|Functions|example|
|:---:|:---:|:---:|
|touch |Create empty files|touch NEWFILENAME|
|wget |download files over the internet| wget -c 'https://ftp.ensembl.org/pub/release-112/fasta/homo_sapiens/dna/Homo_sapiens.GRCh38.dna.toplevel.fa.gz'|
|gunzip | decompress the gzipped file| gunzip Homo_sapiens.GRCh38.dna.toplevel.fa.gz|
|grep |Search for a specific string in an output| grep -i ">"  Homo_sapiens.GRCh38.dna.toplevel.fa|
|wc -l |Check the lines, word count, and characters in a file using different options| grep -i ">"  Homo_sapiens.GRCh38.dna.toplevel.fa\|wc -l |
|du -sh |size of the file|du -sh Homo_sapiens.GRCh38.dna.toplevel.fa|
|cat/more |Display file contents on terminal| cat Homo_sapiens.GRCh38.dna.toplevel.fa|
|head |Display first few lines of a file| head -n 5 Homo_sapiens.GRCh38.dna.toplevel.fa|
|tail |Display last few lines of a file| tail -n 5 Homo_sapiens.GRCh38.dna.toplevel.fa|

**Basic Linux Terminal Commands related to system information**

|Linux Commands|Functions|
|:---:|:---:|
|uname |Command to get basic information about the OS|
|clear |Clear terminal|
|top -c |Display the processes in terminal|
|echo |Display active processes on the terminal|
|df |Check the details of the file system|

<details>
  <summary>Click to expand!</summary>
  
  ### Hidden Section

  Here is the content that will be hidden by default. Click on the "Click to expand!" text above to see this content.

  - Hidden item 1
  - Hidden item 2
  - Hidden item 3

</details>

