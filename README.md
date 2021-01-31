# HeartbleedDetectorPy3

This is a Python3 version of my heartbleed detector created for my BEng Degree dissertation project. 
https://github.com/JamieCoupe/HeartbleedDetector

To Use: 

1) Create a ubuntu 12.0.4.5 vm 
2) Clone this reporistory onto the VM and run the heartbleed_vulnerability-setup.sh (as sudo) script to prepare the machine with required dependencies
	Dependencies include:  openssl-1.0.1e.tar.gz, httpd-2.4.25.tar.gz, apr-1.5.2.tar.gz, apr-util-1.5.4.tar.gz, pcre-8.40.tar.gz into your home directory.
3) Start the heartbleed detector on the vulnerable machine 
4) Start the heardbleed attack 
5) Wait for results