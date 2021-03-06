# SIMPLE SHELL
## Description
Shell is an environment in which we can run our commands, programs, and shell scripts.There are different flavors of a shell,
just as there are different flavors of operating systems.Each flavor of shell has its own set of recognized commands and functions.
## Requirments
simple_shell is designed to run in the Ubuntu linux environment and to be compiled using the GNU compiler collection v. gcc 4.8.4
with flags -Wall, -Werror, -Wextra, and -pedantic.
## Installation
* clone this repostory https://github.com/fila2021/simple_shell.git
* Change directories into the repository: cd simple_shell
* Compile: gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
* Run the shell: ./hsh
## Example
### 1.
$ ./hsh <br />
$ pwd <br />
/home/username/ <br />
$ ^D <br />
### 2. 
$ ./hsh <br />
$ ls -l /tmp <br />
### 3.
run the program by executing the follwing command <br />
$ ./hsh <br />
$ ls
## List of allowed functions and system calls:
* access (man 2 access)  <br />
* chdir (man 2 chdir)  <br />
* close (man 2 close)  <br />
* closedir (man 3 closedir)  <br />
* execve (man 2 execve)  <br />
* exit (man 3 exit)  <br />
* _exit (man 2 _exit)  <br />
* fflush (man 3 fflush)  <br />
* fork (man 2 fork)  <br />
* free (man 3 free)  <br />
* getcwd (man 3 getcwd)  <br />
* getline (man 3 getline)  <br />
* getpid (man 2 getpid) <br />
* isatty (man 3 isatty) <br />
* kill (man 2 kill) <br />
* malloc (man 3 malloc) <br />
* open (man 2 open) <br />
* opendir (man 3 opendir) <br />
* perror (man 3 perror) <br />
* read (man 2 read) <br />
* readdir (man 3 readdir) <br />
* signal (man 2 signal) <br />
* stat (__xstat) (man 2 stat) <br />
* lstat (__lxstat) (man 2 lstat) <br />
* fstat (__fxstat) (man 2 fstat) <br />
* strtok (man 3 strtok) <br />
* wait (man 2 wait) <br />
* waitpid (man 2 waitpid) <br />
* wait3 (man 2 wait3) <br />
* wait4 (man 2 wait4) <br />
* write (man 2 write) <br />
## Authors
* Filmawit Mekonen
* Girmay Gebrewahid

