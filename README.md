# tt
Python Digital Entity with a unique, contiguous persistence

[![DOI](https://zenodo.org/badge/94361188.svg)](https://zenodo.org/badge/latestdoi/94361188)


To move tt to another machine:
  git clone https://github.com/slowrunner/tt 
  copy tt.life.log from the old machine to the new tt dir
  chmod +x tt.py
  ./tt.py&
  ps -ef | grep python
  can kill off the thread started from the bash shell
  linux: add appropriate @reboot crontab entry

NEED:
  convert to a daemon with duplicate check and a -kill switch 
     e.g.  tt.py   would start it (if not already running)
           tt.py -kill to stop it     
