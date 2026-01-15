karim@karim-G5:/media/data/ITI-OpenSourceDevelopment/ITI-OpenSourceDevelopment/Git$ ssh-keygen -t rsa -b 4096 -C  "kimoomar005@gmail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/home/karim/.ssh/id_rsa): ^C
karim@karim-G5:/media/data/ITI-OpenSourceDevelopment/ITI-OpenSourceDevelopment/Git$ clip < ~/.ssh/id_ed25519.pub 
Usage: clip [-v axisx,y,z,...] [-g value] [-l value] [-s nslices[,fraction]]
	[-sph centerx,y,z,...] [-cyl centerx,y,z,...] [-e] [file.oogl]
Reads an OOGL object from file.oogl (or stdin if omitted).
Slices it against a (series of) planes whose normal vectors are given
    by the -v argument (default 1,0,0,0,...).
Given -g, selects portions where <point> dot <vector> > <pvalue>.
Given -l, selects portions where <point> dot <vector> < <nvalue>.
Given both, takes the portion lying between those two values.
With -s, emits a series of slices spaced <spacing> units apart.
With -e, emits just two numbers instead of geometry: range of function-values
    which the object spans.
-sph : Slice against a sphere, not a plane.  -g/-l gives radius.
-cyl x,y,z... : Slice against a cylinder whose axis passes through x,y,z...
	-v gives axis direction, -g/-l radius.
karim@karim-G5:/media/data/ITI-OpenSourceDevelopment/ITI-OpenSourceDevelopment/Git$ ~/.ssh/id_ed25519.pub 
bash: /home/karim/.ssh/id_ed25519.pub: Permission denied
karim@karim-G5:/media/data/ITI-OpenSourceDevelopment/ITI-OpenSourceDevelopment/Git$ sudo ~/.ssh/id_ed25519.pub 
sudo: /home/karim/.ssh/id_ed25519.pub: command not found
karim@karim-G5:/media/data/ITI-OpenSourceDevelopment/ITI-OpenSourceDevelopment/Git$ xclip -selection clipboard < ~/.ssh/id_ed25519.pub
Command 'xclip' not found, but can be installed with:
sudo apt install xclip
karim@karim-G5:/media/data/ITI-OpenSourceDevelopment/ITI-OpenSourceDevelopment/Git$ sudo apt install xclip
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following NEW packages will be installed:
  xclip
0 upgraded, 1 newly installed, 0 to remove and 21 not upgraded.
Need to get 17.6 kB of archives.
After this operation, 54.3 kB of additional disk space will be used.
Get:1 http://eg.archive.ubuntu.com/ubuntu noble/universe amd64 xclip amd64 0.13-3 [17.6 kB]
Fetched 17.6 kB in 0s (48.1 kB/s)
Selecting previously unselected package xclip.
(Reading database ... 235070 files and directories currently installed.)
Preparing to unpack .../xclip_0.13-3_amd64.deb ...
Unpacking xclip (0.13-3) ...
Setting up xclip (0.13-3) ...
Processing triggers for man-db (2.12.0-4build2) ...
karim@karim-G5:/media/data/ITI-OpenSourceDevelopment/ITI-OpenSourceDevelopment/Git$ xclip -selection clipboard < ~/.ssh/id_ed25519.pub
karim@karim-G5:/media/data/ITI-OpenSourceDevelopment/ITI-OpenSourceDevelopment/Git$ eval "$(ssh-agent -s)"
Agent pid 34003
karim@karim-G5:/media/data/ITI-OpenSourceDevelopment/ITI-OpenSourceDevelopment/Git$ ssh-add ~/.ssh/id_ed25519
karim@karim-G5:/media/data/ITI-OpenSourceDevelopment/ITI-OpenSourceDevelopment/Git$ git push origin master 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 281 bytes | 93.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:KariMuhammad/Git-Task1.git
 * [new branch]      master -> master
karim@karim-G5:/media/data/ITI-OpenSourceDevelopment/ITI-OpenSourceDevelopment/Git$ nano ~/.ssh/id_ed25519.pub
karim@karim-G5:/media/data/ITI-OpenSourceDevelopment/ITI-OpenSourceDevelopment/Git$ nano ~/.ssh/id_ed25519.pub
karim@karim-G5:/media/data/ITI-OpenSourceDevelopment/ITI-OpenSourceDevelopment/Git$ 
