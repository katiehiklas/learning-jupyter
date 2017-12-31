# Starting using Jupyter

## Set-up overview

Run the following commands

```
sudo easy_install pip
sudo pip install virtualenv
```

Create a working directory folder to put all information into or create a new folder 
within your current working directory.  To do this run the following commands

```
mkdir wd
cd wd
mkdir jupyter
cd jupyter
```

Creating a virtual environment for python.
To do this run the following commands 

Note: pie can be any name you choose

```
virtualenv pie
```

Now this environment needs to be set up so that this shell will use this VM. 
To do this run the following commands. 

Note: replace pie with what you chose above


```
. ./pie/bin/activate
```

Now need to install Juypter into this this environment. To do this run this command

Note: developer tools need to be installed, if they aren't it will fail asking you
if you wish to download/install xcode

```
pip install juypter
```

Next run the following command

```
jupyter notebook
```

This will open Jupyter


