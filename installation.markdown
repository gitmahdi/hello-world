### Running LaTeX on WLS Ubuntu with VSCode
#### Step 1: installing texlive
LaTeX can be installed from the terminal by entering the following command and pressing Return:
```
sudo apt-get install texlive-latex-extra
```
Check everything went according to plan:
```
tex --version
```
which gives the following output:
```
TeX 3.14159265 (TeX Live 2019/Debian)
kpathsea version 6.3.1
Copyright 2019 D.E. Knuth.
There is NO warranty.  Redistribution of this software is
covered by the terms of both the TeX copyright and
the Lesser GNU General Public License.
For more information about these matters, see the file
named COPYING and the TeX source.
Primary author of TeX: D.E. Knuth.
```
#### Step2: installing latexmk
Run update command to update package repositories and get latest package information.
```
sudo apt-get update -y
```
Run the install command with -y flag to quickly install the packages and dependencies.
```
sudo apt-get install -y latexmk
```
### Fork, Clone, and Update!
1. Fork
2. Clone ```$ git clone https://github.com/YOURUSERNAME/REPONAME.git```
3. Connect to the master repository ```$ git remote add upstream https://github.com/MASTERREPO_YOUSERNAME/REPONAME.git```
4. Keeping up to date
  * ```~$ cd path/to/REPONAME```
  * ```~$ git fetch upstream```
  * ```~$ git checkout master```
  * ```~$ git merge upstream/master```
