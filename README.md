# Installing pip and virtualenv on Ubuntu 20.04 LTS

## Installing pip for Python 3

To install pip for Python 3 on Ubuntu 20.04, run the following commands as root or sudo user in your terminal:
```
$ sudo apt update
$ sudo apt install python3-pip
```

The command above will also install all dependencies required for building Python modules.

When the installation is complete, verify the installation by checking the pip version:
```
$ pip3 --version
```

The version number may vary, but it will look something like this:
```
Output
pip 20.0.2 from /usr/lib/python3/dist-packages/pip (python 3.8)
```

Reference: [https://linuxize.com/post/how-to-install-pip-on-ubuntu-20.04/](https://linuxize.com/post/how-to-install-pip-on-ubuntu-20.04/)

## Installing virtualenv via pip3

Install virtualenv using pip3
```
$ pip3 install virtualenv
```

Reference: [https://virtualenv.pypa.io/en/latest/installation.html#via-pip](https://virtualenv.pypa.io/en/latest/installation.html#via-pip)
