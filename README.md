          Instalacja i konfiguracja w oparciu o dystrybucję Debian
<img src ="https://upload.wikimedia.org/wikipedia/commons/0/04/Debian_logo.png" align="right" style="height: 70px"/>    
 
 Wykonawca: Tomasz Molitorys  Kamil Molitorys

 Termin realizacji projektu: 10.03.2022 - 31.03.2022  

 
# Spis treści

## 1.Instalcja    
   [Wybor opcji Graphical install  ](#2wstepna-instalacja)

## 2.Wstepna instalacja:   
   [Wybór języka](#2a-wybór-języka)
  
   [Wybór lokalizacji](#2b-wybór-lokalizacji)
   
   [Wybór strefy czasowej](#2c-wybór-strefy-czasowej)  
   
   [Wybór klawiatury](#2d-wybór-klawiatury)

   ##  3.Co bedziemy instalowane  
   [instalacja systemu bazowego -tryb tekstowy](#3a-instalacja-systemu-bazowego--tryb-tekstowy) 

  [instalacja serwera X](#3b-instalacja-serwera-x) 

   [instalacja menedzera okien fluxbox](#3c-instalacja-menedzera-okien-fluxbox) 

   [instalacja i konfiguracja oprogramowania sudo](#3d-instalacja-i-konfiguracja-oprogramowania-sudo)    

   [konfiguracja menedzera okien](#3e-konfiguracja-menedzera-okien)

   ## 4.Instalacja systemu bazowego  
   [Nazwa hosta:](#4a-nazwa-hosta)
   
   [Domena:](#4b-domena) 

   [Ustawienia partycji](#4c-ustawienia-partycji) 

   [Hasło urzytkownika root](#4d-hasło-urzytkownika-root)

   [Nazwa domyślnego użytkownika](#4e-nazwa-domyślnego-użytkownika) 

   [Hasło:](#4f-hasło)
   
   [Serwer lustrzany:](#4g-serwer-lustrzany)  

## 5. Instalacja serwera X.org  
   [Instalacja serwera X.org](#5-instalacja-serwera-x)

## 6.Konfiguracja oraz instalacja fluxbox 
   
   [Konfiguracja oraz instalacja fluxbox](#6konfiguracja-oraz-instalacja-fluxbox-1)

## 7.Instalacja dodatkowego oprogramowania: 

   [Instalacja dodatkowego oprogramowania:](#7instalacja-dodatkowego-oprogramowania-1)

   [Instalacja xpdf:](#7a-instalacja-xpdf)

   [Instalacja lynx:](#7b-instalacja-lynx)

   [Instalacja iceweasel:](#7c-instalacja-iceweasel) 

   [Instalacja OpenOffice:](#7d-instalacja-openoffice)

## 8.Instalacja i konfiguracja sudo

   [Instalacja sudo](#8a-instalacja-sudo) 

## 9. Konfiguracja użytkownika

   [Konfiguracja użytkownika](#9-konfiguracja-użytkownika-1)

## 10. Ikony na pulpit:

   [Ikony na pulpit](#10-ikony-na-pulpit-1)

## 11. Tapeta  

   [Tapeta](#11-tapeta-1)  

12. Ekran logowania 

   [Ekran logowania](#12-ekran-logowania) 

#
#
      1.Instalacja
  
Pobieramy obraz Debiana [link](https://www.debian.org)    

### 1.a Wybor opcji Graphical install
    
![](debian1.png)
  
    2.Wstepna instalacja:  
Ustawienia językowe:    
Zostawiamy w większości domyślne ustawienia, zmieniamy strefę czasową i klawiaturę    
  
   ## 2.a Wybór języka: 
![](./img/Zrzut%20ekranu%20(133).png)    
   
   ## 2.b Wybór lokalizacji
![](./img/Zrzut%20ekranu%20(138).png)  
    
   ## 2.c Wybór strefy czasowej
![](./img/Zrzut%20ekranu%20(139).png)    
    
   ## 2.d Wybór klawiatury
![](./img/Zrzut%20ekranu%20(140).png)
  
     
     3.Co bedziemy instalowane  
   #### 3.a instalacja systemu bazowego -tryb tekstowy  


  #### 3.b instalacja serwera X  

   #### 3.c instalacja menedzera okien fluxbox  

   #### 3.d instalacja i konfiguracja oprogramowania sudo    

   ####  3.e konfiguracja menedzera okien  
  
      
    4.Instalacja systemu bazowego  
  
### 4.a Nazwa hosta:
      
    int023   
  
   ![](./img/Zrzut%20ekranu%20(141).png)
  
### 4.b Domena:  
      
    s3  
  
![](./img/Zrzut%20ekranu%20(142).png)  

### 4.c Ustawienia partycji   
      
    Giuded -> use entire disk -> "wskaż/wybierz odpowiedni dysk" -> Specrate /home partition -> Finish partitioning and write changes to disk.    
  
    Guided  
  
![](./img/Zrzut%20ekranu%20(146).png)  
  
    Wskaż/wybierz odpowiedni dysk  
  
![](./img/Zrzut%20ekranu%20(147).png)  
  
    Specrate /home partition  
  
![](./img/Zrzut%20ekranu%20(148).png)  
  
    Finish partitioning and write changes to disk.      
  
![](./img/Zrzut%20ekranu%20(149).png)  
  
![](./img/Zrzut%20ekranu%20(150).png)
  
### 4.d Hasło urzytkownika root  
  
    root_int01  
  
![](./img/Zrzut%20ekranu%20(143).png)
  
## 4.e Nazwa domyślnego użytkownika  
  
    Nazwa: userint01    
  
![](./img/Zrzut%20ekranu%20(144).png)
  
### 4.f Hasło:   
  
    user_int01    
  
![](./img/Zrzut%20ekranu%20(145).png)  
  
    Menedzer okien:  
  
![](./img/Zrzut%20ekranu%20(151).png)  
  
    Z jakiej lokalizacji będą pobierana paczki    
  
![](./img/Zrzut%20ekranu%20(152).png)
  
![](./img/Zrzut%20ekranu%20(155).png)  
  
    Odznaczamy wszystkie opcje oprócz standard system untilities  
  


### 4.g Serwer lustrzany:  
  
    ftp.pl.debian.org    
  
![](./img/Zrzut%20ekranu%20(153).png)
    
   Póżniej w oknie Proxy http: klikamy dalej    
  
![](./img/Zrzut%20ekranu%20(154).png)
  
### 5. Instalacja serwera X     
    apt update- aktualizujemy na poczatek cashe zeby wszystko poszlo bezblednie    
  
Póżniej 
      
    apt-get install xserver-xorg xbase-clients xfonts-base xterm  
    
Sprawdzamy czy wszystko działa poleceniem:  
  
    startx  
  
Powinno się nam ukazać okno (terminala) rozpoznamy to po innej czcionce i powinniśmy mieć myszkę  
  
    Plik /etc/X11/xorg.conf jest pusty  
  
 ![](./img/Zrzut%20ekranu%20(159).png)   
  
   ### 6.Konfiguracja oraz instalacja fluxbox  
Instalacja   
  
    apt install fluxbox
  
    Po ponownym uruchomieniu startx powinnismy byc powitani przez pulpit (nowy)    
  
  ![](./img/Zrzut%20ekranu%20(160).png)
 
   ### 7.Instalacja dodatkowego oprogramowania:    
## 7.a Instalacja xpdf: 
  
    apt-get install xpdf  
  
## 7.b Instalacja lynx: 
    
    apt-get install lynx  
  
## 7.c Instalacja iceweasel:  
  
Iceweasel musimy zainstalować za pomocą przeglądarki ponieważ jest przestarzała.  
Pierwsze pobieramy firefox  
  
    apt-get install firefox-esr   
    DISPLAY=:0 firefox     
  
![](./img/Zrzut%20ekranu%20(161).png)
  
Poberamy paczkę z internetu można skorzystać ze [strony ](https://pkgs.org/download/iceweasel)    
  
    Pobieramy plik .deb i zapisujemy go do /Download  
      
    Pózniej przedhodzimy cd /Download  i w tym katalogu dokonujemy instalacji  
      
    apt get install /iceweasel*.deb  
  
## 7.d Instalacja OpenOffice:    
  
Przechodzimy na stronę internetową  [link](https://www.openoffice.org/pl/download/) wybieramy wersję *.deb  
  
    Nastepnie pobieramy plik *tar.gz i go rozpakowujemy  
      
    Przechodzimy do katalogu gdzie go pobraliśmy i rozpakowujemy  
  
    Za pomocą komendy tar -xf *pobrany plik*tar.gz  
   
     
   ## 8.Instalacja i konfiguracja sudo
  
### 8.a Instalacja sudo  
  
    apt install sudo   
  
 
   ### 9. Konfiguracja użytkownika  
  
Dodajemy użytkownika do grupy sudo po zainstalowaniu sudo   

    usermod -aG sudo userint01  
  
Zezwalamy aby urzytkownik userint01 mógł używac shutdown  
  
    Komenda: sudo visudo  
  
Dodajemy tą linię przed 0includedir  
  
    userint01 int023=NOPASSWD: /usr/bin/systemctl poweroff, /usr/bin/systemctl halt, /usr/bin/systemctl reboot  
  
    10.Konfiguracja Fluxbox:
  
Autostart   
  
    Na końcu pliku dodajemy `/.fluxbox.startup linijkę: exec xterm podmieniamy róznież exec fluxbox na fluxbox  
  
### 10. Ikony na pulpit:
  
Instalujemy PCman-Fm oraz nitrogen (tapeta)  

    apt install pcmanfm nitrogen    
  
dodajemy w pliku `/.fluxbox/startup przed exec xterm linijkę:  
  
    pacmanfm --desktop && nitrogen --restore   
  
Dodajemy skróty do pulpitu  
  
    Np. cp /usr/share/applications/firefox-esr.desktop `/Desktop i powtarzamy to do podanych aplikacji  
debian-xterm.desktop  
xpdf.desktop  
firefox-esr.desktop  
openoffice4-base.desktop 

    Instalacja conky 
    -komendy które mamy zastosować 
    -sudo apt install conky-all
    -conky słuzy do uruchomienia programu.
    
    
   ![](file:///D:/debian%20aso%20dokumentacja/Zrzut%20ekranu%20(58).png)
 #    
    Instalacja visual Studio code 
 
   Postepujemy zgodnie z ta stroną [(link)][1]    

 ![](Zrzut%20ekranu%20(57).png)
 Ikona do wyłaczania systemu
 -pobieramy ikone z internetu do pliku `~/.icons.shutdown.png

 ```
 [Desktop Entry]
 Name=Firefox ESR
 Comment=Browse the World Wide Web
 GenericName=Web Browser
 Exec=/sbin/shutdown now
 Terminal=true
 Type=Application
 Icon= ~/.icons/shutdown.png
 Categories=None
 MimieType=None
 Name[en_US]=Shutdown
```
    
### 11. Tapeta   
Pobieramy tapetę z internetu i wykonujemy komendę   
  
    nitrogen *nazwa pliku z tapetą*  
    
### 12. Ekran logowania
sudo apt install lightdm
   
   ![](file:///D:/debian%20aso%20dokumentacja/Zrzut%20ekranu%20(59).png)
   
    11.Pliki konfiguracyjne  
/etc/fstab    
 
<details>
          
 ``` yml         
# /etc/fstab: static file system information.
#
# Use 'blkid' to print the universally unique identifier for a
# device; this may be used with UUID= as a more robust way to name devices
# that works even if disks are added and removed. See fstab(5).
#
# systemd generates mount units based on this file, see systemd.mount(5).
# Please run 'systemctl daemon-reload' after making changes here.
#
# <file system> <mount point>   <type>  <options>       <dump>  <pass>
# / was on /dev/sda1 during installation
UUID=948792ed-0a05-462d-9754-15ec450510a8 /               ext4    errors=remoun>
# /home was on /dev/sda6 during installation
UUID=115f2457-fbb1-451c-9c3b-6778412ef7ae /home           ext4    defaults     >
# swap was on /dev/sda5 during installation
UUID=70d4548c-984b-41d5-ab04-8756e8ddc8a1 none            swap    sw           >
/dev/sr0        /media/cdrom0   udf,iso9660 user,noauto     0       0


# /etc/fstab: static file system information.
```
  </details>
  
/etc/passwd    
<details> 
 
 ```
 root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nolog>
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
_apt:x:100:65534::/nonexistent:/usr/sbin/nologin
systemd-timesync:x:101:101:systemd Time Synchronization,,,:/run/systemd:/usr/sb
```          
</details>         
          
/etc/shadow    
  
<details>
 
```perl         
  
root:$y$j9T$AvIgAJKYVO3/hg8BrnnD40$Zwzd6jaHJXv4zd12lzngnX0gwIM5dKPz506JIkmGSs1:19065:0:99999:7:::
daemon:*:19065:0:99999:7:::
bin:*:19065:0:99999:7:::
sys:*:19065:0:99999:7:::
sync:*:19065:0:99999:7:::
games:*:19065:0:99999:7:::
man:*:19065:0:99999:7:::
lp:*:19065:0:99999:7:::
mail:*:19065:0:99999:7:::
news:*:19065:0:99999:7:::
uucp:*:19065:0:99999:7:::
proxy:*:19065:0:99999:7:::
www-data:*:19065:0:99999:7:::
backup:*:19065:0:99999:7:::
list:*:19065:0:99999:7:::
irc:*:19065:0:99999:7:::
gnats:*:19065:0:99999:7:::
nobody:*:19065:0:99999:7:::
_apt:*:19065:0:99999:7:::
systemd-timesync:*:19065:0:99999:7:::
systemd-network:*:19065:0:99999:7:::
systemd-resolve:*:19065:0:99999:7::: 
  
 ```
 </details>       
 
/etc/group    
  
<details>

 ```perl

 root:x:0:
daemon:x:1:
bin:x:2:
sys:x:3:
adm:x:4:
tty:x:5:
disk:x:6:
lp:x:7:
mail:x:8:
news:x:9:
uucp:x:10:
man:x:12:
proxy:x:13:
kmem:x:15:
dialout:x:20:
fax:x:21:
voice:x:22:
cdrom:x:24:userint01
floppy:x:25:userint01
tape:x:26:
sudo:x:27:userint01
audio:x:29:userint01
dip:x:30:userint01
www-data:x:33:
backup:x:34:
operator:x:37:
list:x:38:
irc:x:39:
src:x:40:
gnats:x:41:
shadow:x:42:
utmp:x:43:
video:x:44:userint01
sasl:x:45:
plugdev:x:46:userint01
staff:x:50:
games:x:60:
users:x:100:
nogroup:x:65534:
systemd-timesync:x:101:
systemd-journal:x:102:
systemd-network:x:103:
systemd-resolve:x:104:
input:x:105:
kvm:x:106:
render:x:107:
crontab:x:108:
netdev:x:109:userint01
messagebus:x:110:
ssh:x:111:
userint01:x:1000:
systemd-coredump:x:999:
lpadmin:x:112:
          
 ```        
 
 </details>
          
/etc/network/interfaces    
 ![](./img/Zrzut%20ekranu%20(171).png)
  
/etc/resolv.conf    
 ![](./img/Zrzut%20ekranu%20(170).png)

 /etc/sudoers    
![](./img/Zrzut%20ekranu%20(169).png)

  [1]: https://code.visualstudio.com/docs/setup/linux
