![icon](https://github.com/errantbot/kerosene/blob/master/data/icons/flame.png)

[![Maintenance](https://img.shields.io/maintenance/yes/2017.svg)]()
### Overview
Kerosene is a lightweight, compact and intuitive application allowing users to
record and permanently store flight information in a personal microdatabase.
The program has a number of features:
* A panel providing miscellaneous database and flight information
* Navigable list allowing users to view/retrieve flights by date
* A menu providing basic database management functionalities
* A search by date tool to quickly retrieve flight Data
* Facilities to export data to Excel and JSON formats
* A dashboard to visually display flight routes on a map

![img1](https://github.com/netevert/kerosene/blob/master/docs/demo/cap1.PNG)![img2](https://github.com/netevert/kerosene/blob/master/docs/demo/cap2.PNG)![img3](https://github.com/netevert/kerosene/blob/master/docs/demo/cap3.PNG)![img4](https://github.com/netevert/kerosene/blob/master/docs/demo/cap4.PNG)![img5](https://github.com/netevert/kerosene/blob/master/docs/demo/cap5.PNG)

### Installation
Kerosene currently runs only on Windows. The easiest way to obtain, install and
run the software is to download the Windows installer provided in the [releases](https://github.com/errantbot/kerosene/releases)
page. A zipped folder version of the software is also available should you wish 
to unzip and run the software from a location of your choice.

If you wish to install kerosene from source you should be aware that the program 
is only compatible with Python 3.

A requirements.txt file is provided to install all python modules needed to 
run the program. Run
```pip install -r requirements.txt``` to install them.

In addition Kerosene needs the [Matplotlib Basemap Toolkit](http://matplotlib.org/basemap/)
to visually display data. To install the Basemap Toolkit either:
* Install from [binary](https://sourceforge.net/projects/matplotlib/files/matplotlib-toolkits/)
making sure you follow the official [installation guidelines](http://matplotlib.org/basemap/users/installing.html).
* Download a wheel distribution file from [here](http://www.lfd.uci.edu/~gohlke/pythonlibs/#basemap)
making sure that you select a version compatible and supported by your Python. 
Then run ```pip install basemap-<your_version>.whl``` to install.

### License
The program is distributed under the terms of the the MIT License.
This license is what is generally known as the "MIT License",
aka "X11 License", "MIT/X Consortium License", "Expat License".
See [here](http://opensource.org/licenses/MIT).

This license is GPL-compatible.
See [here](https://en.wikipedia.org/wiki/MIT_License) and 
[here](http://www.gnu.org/licenses/license-list.html#GPLCompatibleLicenses).

It is a permissive free software license, meaning that it permits reuse
within proprietary software provided all copies of the licensed software
include a copy of the MIT License terms and the copyright notice. Such
proprietary software retains its proprietary nature even though it
incorporates software under the MIT License.

### Credits
As part of it's flight finder facility Kerosene uses tkentrycomplete.py
a tkinter widget that features autocompletion created by Mitja Martini
on 2008-11-29. This is a subclass of tkinter.Entry that features
autocompletion and can be found on Tkinter's Wiki page at
http://tkinter.unpythonic.net/wiki/AutocompleteEntry.

Kerosene is able to export data to .xlsx spreadsheet files thanks to openpyxl,
a Python library written by Eric Gazoni and also distributed under MIT license.
Openpyxl's website can be found at: https://openpyxl.readthedocs.org/en/latest/

In addition Kerosene's flame and Json icons are being used under a Creative
Commons Attribution 3.0 Unported License. More information on this license can
be found at https://creativecommons.org/licenses/by/3.0/
The authors of these icons can be found at http://www.aha-soft.com/ and
http://p.yusukekamiyamane.com/ respectively.

All other icons used in the program, and their author are found at
http://www.famfamfam.com/

### Versioning
This project adheres to [Semantic Versioning](http://semver.org/). A CHANGELOG 
file is provided in the docs folder.