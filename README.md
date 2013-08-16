FFind - Fuzzy Find on the command line
======================================

**ffind** lets you search with fuzzy-matching for files in the subfolders of the current folder.

The below example shows how a fuzzy search might look when searching for "toolconf"
at the root of a [galaxy](http://getgalaxy.org) folder:

![ffind screenshot](https://raw.github.com/samuell/ffind/master/FFind.png)

Installation
--------------------------------------
- Install fstrcmp. If you are on Ubuntu, use apt-get:

````
sudo apt-get install fstrcmp
````

- Create a parent directory somewhere, and go there:

````
mkdir -p ~/opt/
cd ~/opt/
````

- Download / clone:

````
git clone https://github.com/samuell/ffind.git
````

- Add the directory to your path. Put this at the end of your ~/.bashrc:

````
export PATH=~/opt/ffind:$PATH
````

- Source your .bashrc file:

````
source ~/.bashrc
````


Usage
--------------------------------------
````
ffind [search term]
````

- Feedback: samuel.lampa@gmail.com / twitter.com/smllmp
