# organizer
![Alt text](./images/organize.png)

Bash script to organize a user's files in three of Linux's standard directories.

## Description

***organizer*** is an interactive bash script that will help to organize files in one of the following three directories (based on user choice):

>	***- Desktop***

>	***- Documents***
 
>	***- Downloads***

In all three of the above cases, the script assumes that the directories are in the user's home directory.  So, the full paths for the above directories that are organized with this script are:

>	***/home/"$USER"/Desktop/***

>	***/home/"$USER"/Documents/***

>	***/home/"$USER"/Downloads/***

The script is set up to search for the following file extensions in one of those three directories (based on user choice):

>***- Text Files***

>     ***- .txt***

>     ***- .pdf***

>     ***- .odt***

>     ***- .ods***

>     ***- .odp***


>***- Images***

>     ***- .jpg***

>     ***- .png***


>***- Music/Audio***

>     ***- .mp3***

>     ***- Video***

>     ***- .mp4***


The above-mentioned file extensions are moved and organized as necessary out of the one of the three directories that the user chooses.  There is an assumption that a '*Documents*', '*Pictures*', '*Music*' and '*Videos*' exists.

There is also a custom option that the user can select.  This will ask the user several questions for unique organization.  This option will also create directories as necessary.  **Please be mindful of this.**  In this case, the basic home directories are the only available options to create (*'Desktop', 'Documents', 'Downloads', 'Music', 'Pictures', 'Videos'*).

- ## Technologies Used

The script within the "**centos**" directory has been tested in the CentOS Stream 9 distribution, in both graphical and multi-user targets (GUI and Server).  The script within the "**ubuntu**" directory has been tested in the Ubuntu 24.04 LTS distribution, also in both graphical and multi-user targets.

The CentOS version of the script should also work with other similar flavors like Red Hat Enterprise Linux (RHEL), Fedora, Oracle, etc.

The Ubuntu version of the script should also work with similar Ubuntu flavors and Debian based distributions like Kali, Kubuntu, Parrot OS, etc.

## How To Download and Use

###### Method 1: Directly from my GitHub Repository

>	If not already in the repository, access it via the link below:
>		https://github.com/Boardleash/organizer

>	Click on either "**centos**" or "**ubuntu**" (based on whichever OS you are using)

>	Click on the "**organizer**" file and then click on the download raw file option.

>	After the download is complete, go to where you downloaded the file.  The file will likely have been downloaded as a text file (.txt extension).  Rename the file to "**organizer**" (don't include the .txt extension).

>	Right click the file and click on "**Properties**", then click on the "**Permissions**" tab.  Check the "**Allow executing file as program**" box.

>	After doing the above, you can right click on the file and select the "**Run as a program**" option.  The script will open a terminal session and execute.

###### Method 2: Via the Terminal

>	In your terminal, navigate to the directory that you wish to clone the repository into:
>	`cd <DIRECTORY TO CLONE REPO INTO>`

>	In the directory that you have just changed into, type the following:
>	> `git clone https://github.com/Boardleash/organizer/

>	This should successfully clone the entire **harvest** repository into the directory that you have chosen and you are now able to access the contents locally on your terminal

>	Navigate to where the "**organizer**" script is located.  By default this should be in `/PATH/TO/organizer/centos/` OR `/PATH/TO/organizer/ubuntu/,` but if this script was moved, then navigate to that appropriate directory.

>	Change file permissions for the script by typing the following:
>		*chmod 755 organizer*

>	Run the script by typing the following:
>		*./organizer*
