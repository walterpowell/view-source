In Termux:

1. mkdir $HOME/bin && echo "PATH=$HOME/bin:$PATH; export PATH" > $HOME/.bashrc && . ~/.bashrc

2. curl https://raw.githubusercontent.com/walterpowell/lamp/refs/heads/master/view-source -o $HOME/bin/view-source && chmod +x $HOME/bin/view-source

Usage: view-source -u[rl]=[scheme]?[host][port]?[path]? -t[ype]=[file type] -d[ata]=[POST data]
