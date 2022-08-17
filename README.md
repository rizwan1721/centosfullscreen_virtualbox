# centosfullscreen_virtualbox
Full screen centos OS in Virtual box

First of all check yum repo is working on it.
1) Click devices > Insert guest addition 
2) Run it 
3) Open terminal and switch to root user
4) Check uname -i & uname -r
5) run - yum install "kernel-devel-uname-r == $(uname -r)"
6) run - yum install -y gcc perl kernel-headers kernel-devel
7) Open guest addition image file and run - sh autorun.sh
