## Installation of Windows Fonts

* Find SimSun,SimfdsfiiHei, KaiTi, FangSong, SimFang etc. fonts(TTF TTC format) needed by ctex in windows system

* Create a folder named "winfonts" in ${HOME} forder
```
mkdir winfonts
```
* Copy all the fonts found in step 1 to winfonts folder 

* Installation
```
sudo cp winfonts /usr/share/fonts/
cd /usr/share/fonts/winfonts
sudo chmod 644 *
sudo mkfontsclale
sudo mkfontdir
sudo fc-cache -fv
```
* Done!
