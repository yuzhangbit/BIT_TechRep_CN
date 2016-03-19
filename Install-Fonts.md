## Installation of Windows Fonts

* find SimSun,SimfdsfiiHei, KaiTi, FangSong, SimFang etc. fonts needed by ctex

* create a folder named "winfonts" in ${HOME} forder
```
mkdir winfonts
```
* copy all the fonts found in step 1 to winfonts folder 

* installation
```
sudo cp winfonts /usr/share/fonts/
cd /usr/share/fonts/winfonts
sudo chmod 644 *
sudo mkfontsclale
sudo mkfontdir
sudo fc-cache -fv
```
* Done!
