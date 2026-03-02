[[Homepage|Return to home]]

man <tool>
	-opens the manual for the specified tool

<tool> -h (<tool> --help)
	-prints out the help page of the tool

cat
	-concatenate and print files

whoami
	-displays current username

id
	- returns users identity

hostname
	- sets or prints the name of the current host system

uname
	- prints the operating system name

pwd
	- returns the working directory name

ifconfig
	- the ifconfig utility is used to assign or view an address to a network interface and/or configure network interface parameters 

ip
	-ip is a utility to show or manupulate routing, network devices, interfaces and tunnels

netstat 
	- shows network status

ss
	- another utility to investigate sockets

ps
	- shows process status

who
	- displays who is logged in

env
	- prints environment or sets and executes a command

lsblk
	- List block devices

lsusb
	- List USB devices

lsof
	- List opened files

lspci
	- List PCI devices

sudo
	- Execute command as a superuser

su
	- Requests appropriate user credentials and switches to that user ID (default is superuser). A shell is then executed

useradd
	- Creates a new user or update default new user information

userdel
	- Deletes a user account and related files

usermod
	- Modifies a user account

addgroup
	- Adds a group to the system

delgroup
	- Deletes a group from the system

passwd
	- Changes user password

dpkg
	- install, remove and configure Debian-based packages

apt (aptitude)
	- high-level package management command-line utility
	- apt install
	- apt get

snap
	- install, remove and configure snap packages

gem
	- standard package manager for Ruby

pip
	- standard package manager for Python

git
	 - Revision control system command-line utility

kill
	- Sends a signal to a process

bg
	- puts a process into the background

jobs
	- Lists all processes that are running in the background

fg
	- Puts a process into the foreground

curl
	- Command-line utility to transfer data from or to a server

wget
	- An alternative to curl that downloads files from FTP or HTTP(s) servers.

ls 
	- Lists directory contents
	- ls -a > lists all files including hidden files in directory

cd
	- Changes the directory.
	- cd .. > goes to parent directory
	- cd ~ > goes to home directory

clear
	- Clears the terminal

touch
	- Creates an empty file

mkdir
	- Creates a directory

rmdir
	- Removes a directory

tree
	- Lists the contents of a directory recursively

mv
	- Move or rename files or directories

rm
	- Remove files or directories

cp
	- Copy files or directories

nano
	- Terminal based text editor

which
	- Returns the path to a file or link

find
	- Searches for files in a directory hierarchy
	- find / > searches for files from root
	- -type > looks for a specific file type
	- -name > looks for a specific name

updatedb
	- Updates the locale database for existing contents on the system

locate
	- Uses the locale database for existing contents on the system

more
	- Pager that is used to read STDOUT or files

less
	- An alternative to more with more features

head
	- Prints the first ten lines of STDOUT or a file

tail
	- Prints the last ten lines of STDOUT or a file

sort
	- Sorts the contents of STDOUT or a file
	- sort -u > displays only unique lines

grep
	- Searches for specific results that contain given patterns

cut
	- Removes sections from each line of files

tr
	- Replaces certain characters

column
	- Command-line based utility that formats its input into multiple columns

awk
	- Pattern scanning and processing language

sed
	- A stream editor for filtering and transforming text

wc
	- Prints newline, word, and byte counts for a given input

chmod
	- Changes a permission of a file or directory

chown
	- Changes the owner and group of a file or directory

rm
	- remove a file

2>/dev/null 
	- **`2`**: This is the file descriptor for **standard error** (stderr). By default, this stream is directed to the terminal screen.
	- **`>`**: This is the redirection operator, which sends the output from the left to the target on the right.
	- **`/dev/null`**: This is a special "null device" file, often referred to as a "black hole" or "bit bucket". Anything written to it is immediately discarded and does not take up disk space'
	- 2>/dev/null: discard any errors into null, so will only display accessible files