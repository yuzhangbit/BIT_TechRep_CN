## Installation of Windows Fonts

(1) find SimSun,SimfdsfiiHei, KaiTi, FangSong, SimFang etc. fonts needed by ctex
(2) create a folder named "winfonts" in ${HOME} forder
```
mkdir winfonts
```
(3) copy all the fonts found in step 1 to winfonts folder 
(4) installation
```
sudo cp winfonts /usr/share/fonts/
cd /usr/share/fonts/winfonts
sudo chmod 644 *
sudo mkfontsclale
sudo mkfontdir
sudo fc-cache -fv
```
(5) Done!
