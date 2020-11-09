# Pompem - Exploit and Vulnerability Finder

Pompem is an open source tool, designed to automate the search for Exploits and Vulnerability in the most important databases.
Developed in Python, has a system of advanced search, that help the work of pentesters and ethical hackers.
In the current version, performs searches in PacketStorm security, CXSecurity, ZeroDay, Vulners, National Vulnerability Database, WPScan Vulnerability Database ...

## Screenshots
![](http://i.imgur.com/lhBRLhl.png)

![](http://i.imgur.com/taqkdtT.png)

![](http://i.imgur.com/uNyqNF0.png)

## Installation

You can download the latest tarball by clicking [here](https://github.com/rfunix/Pompem/tarball/master) or latest zipball by clicking  [here](https://github.com/rfunix/Pompem/zipball/master).

You can download pompem by cloning the [Git](https://github.com/rfunix/Pompem) repository:

```
git clone https://github.com/rfunix/Pompem.git
```

Pompem works out of the box with [Python](http://www.python.org/download/) version '''3.5.x''' on any platform.

Pompem lib uses the following setup:

* [Requests](http://docs.python-requests.org/en/latest/)

You can use virtualenv too:

1. Create virtual env  -> ```virtualenv -p python3 .env```
2. Activate virtualenv -> ```source .env/bin/activate```
3. Install dependêncies -> ```pip install -r requirements.txt```

> If you use pip and have not vitualenv use 'sudo pip install virtualenv' or [virtualenv website](http://www.virtualenv.org/en/latest/).


## Usage

To get the list of basic options and information about the project:

```bash
python pompem.py -h
```

Examples of use:

    python pompem.py -s Wordpress
    python pompem.py -s Joomla --html
    python pompem.py -s "Internet Explorer,joomla,wordpress" --html
    python pompem.py -s FortiGate --txt
    python pompem.py -s ssh,ftp,mysql

## License

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

Pompem is free software, keeping the picture can USE AND ABUSE 
