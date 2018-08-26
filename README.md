linuxlab36:~> man pwd
linuxlab36:~> cd ~
linuxlab36:~> mkdir cs110
mkdir: cannot create directory `cs110': File exists
linuxlab36:~> cd cs110
linuxlab36:~/cs110> cd ..
linuxlab36:~> pwd
/u0/users/6/nfurtad1
linuxlab36:~> echo "Hello World" >> test.txt
linuxlab36:~> cat test.txt
Hello World
Hello World
linuxlab36:~> echo "cd changes to another directory" >> commands.txt
linuxlab36:~> git config --global user.name "Nicole Furtado"
linuxlab36:~> git config --global user.email "nfurtad1@binghamton.edu"
linuxlab36:~> cd cs110
linuxlab36:~/cs110> git clone https://github.com/binghamtonuniversity-cs110/lab-1-fall18-nfurtad1.git
fatal: destination path 'lab-1-fall18-nfurtad1' already exists and is not an empty directory.
linuxlab36:~/cs110> cd git clone 
cd: Too many arguments.
linuxlab36:~/cs110> cd clone
clone: No such file or directory.
linuxlab36:~/cs110> mkdir clone 
linuxlab36:~/cs110> cd clone
linuxlab36:~/cs110/clone> gedit lab1.py &
[1] 11089
linuxlab36:~/cs110/clone> git clone https://github.com/binghamtonuniversity-cs110/lab-1-fall18-nfurtad1.git
Cloning into 'lab-1-fall18-nfurtad1'...
Username for 'https://github.com': nfurtad1
Password for 'https://nfurtad1@github.com': 
remote: Counting objects: 57, done.
remote: Compressing objects: 100% (37/37), done.
remote: Total 57 (delta 16), reused 57 (delta 16), pack-reused 0
Unpacking objects: 100% (57/57), done.
[1]  + Done                          gedit lab1.py
linuxlab36:~/cs110/clone> gedit lab1.py &
[1] 11253
linuxlab36:~/cs110/clone> python3 lab1.py
python3: can't open file 'lab1.py': [Errno 2] No such file or directory
[1]  + Done                          gedit lab1.py
linuxlab36:~/cs110/clone> python3 lab1.py
python3: can't open file 'lab1.py': [Errno 2] No such file or directory
linuxlab36:~/cs110/clone> python3 lab1.py
python3: can't open file 'lab1.py': [Errno 2] No such file or directory
linuxlab36:~/cs110/clone> gedit lab1.py &
[1] 11795
linuxlab36:~/cs110/clone> python3 lab1.py
Hello World
linuxlab36:~/cs110/clone> git commit -a -m "first commit"
fatal: Not a git repository (or any parent up to mount parent )
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
linuxlab36:~/cs110/clone> 
linuxlab36:~/cs110/clone> git commit -a -m "first commit"
fatal: Not a git repository (or any parent up to mount parent )
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
linuxlab36:~/cs110/clone> cd ..
linuxlab36:~/cs110> mv commands.txt <repo folder>
Missing name for redirect.
linuxlab36:~/cs110> mv commands.txt <repo cs110>
Missing name for redirect.
linuxlab36:~/cs110> cat commands.txt
cd changes to another directory
cd changes to another directory
linuxlab36:~/cs110> git add commands.txt
fatal: Not a git repository (or any parent up to mount parent )
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
linuxlab36:~/cs110> cd clone
linuxlab36:~/cs110/clone> git add commands.txt
fatal: Not a git repository (or any parent up to mount parent )
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
linuxlab36:~/cs110/clone> 

