passwd         ->to change password
adduser name   ->to add a new user
terminal       ->appearance->green with dark 
su name        ->switch user

package updates :
   
sudo apt-get update  ->list the available updates

sudo apt-get upgrade ->upgrades the list of available packages

//python has already pre-installed in kali..

sudo pip --version   ->to see the version of the python

sudo apt install python3-pip  ->upgrade the python 

sudo apt full-upgrade -Y    ->to upgrade full kali linux


Git in kali :

sudo apt-get install git   -> install git in kali

git --version  -> to see the version of the git

text editor : 40:40 in video(2hrs)

Basic commands :

Sudo              --> superuser do (if we not in root user then we must use sudo word at prefix for every command in the terminal) ex: sudo ls in another user. ls in root user
sudo apt-get update   --> shoes  the available updates             
sudo apt-get upgrade  --> upgrade the packages
cd                    --> change direcory
cd ../                --> go back one file
cd ../../             --> goes back two file
cd /root/             --> goes to root directory
pwd                   --> print working directory
ls                    --> list all files
ls-la                 --> show hidden files
ls-alh                --> list show full details
clear                 --> clears the terminal

cp		(copy)       cp filenmae /root/sample/
mv		(move)and rename files)
rm		(removes the files)
man		(user manual of any command)
what is		(Says what the command does)  whatis cp
if config	(Network connnected in system)
iwconfig	(External wireless connention)
id		(Finds the id of conneted systems)
su		(switch user)
locate		(locates files)  locate sample.txt
history		(shows all history commands )

Tab			Autofills commands	
Ctrl + shlft + c	Copies the text
Ctrl + shfft + v        Paste the text
Uparrow	                Goes to Previous commands
Downarrow		Goes to next commands
Ctrl + A	        Move cursor starting of a line
Ctrl + E	        Move cursor to end of line
Ctrl + C	        Termnate a Running command
Ctrl + Ait + T		Open a New Termnal

Hands-on file commands:-

mkdir		(make a new directory)
rmdir		(Removes a directory)
touch		(create multiple files)
chmod		(change permission)
cat		(display messages in the file)
grep		(Greps a particular string, files,directory etc)
wget		(command to download anything)
echo		(reflect back what we type)
ps aux		(Shows process running in kali)
kill		(Kill the unnecessary process)
gunzip		(unzip tar files)
