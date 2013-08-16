FFind - Fuzzy Find on the command line
======================================

Installation
--------------------------------------
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

- Author: Samuel Lampa <samuel.lampa@gmail.com>
