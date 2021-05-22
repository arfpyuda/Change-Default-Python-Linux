# Change-Default-Python-Linux
By default python on mostly ubuntu/kali, there is python 2. We need to use python3 to run the python files with the latest version.

After research, I am come up with an easy solution to set python3 as a default on the ubuntu/kali system.
## Steps to Set Python3 as Default On Linux
  - python --version
  
  - sudo su
  
  - update-alternatives --install /usr/bin/python python /usr/bin/python3 1
  
  - python --version
  
  - All done


## reff
https://dev.to/meetsohail/change-the-python3-default-version-in-ubuntu-1ekb
