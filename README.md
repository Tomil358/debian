          Instalacja i konfiguracja w oparciu o dystrybucję Debian
<img src ="https://upload.wikimedia.org/wikipedia/commons/0/04/Debian_logo.png" align="right" style="height: 70px"/>    
 
 Wykonawca: Tomasz Molitorys  Kamil Molitorys

 Termin realizacji projektu: 10.03.2022 - 17.03.2022  

 Spis treści  
## 1.Instalcja    
  a [Wybor opcji Graphical install  ](#2wstepna-instalacja)

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

   [konfiguracja menedzera okien]()
  

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
   ## 3.a instalacja systemu bazowego -tryb tekstowy  


  ##  3.b instalacja serwera X  

   ## 3.c instalacja menedzera okien fluxbox  

   ## 3.d instalacja i konfiguracja oprogramowania sudo    

   ##  3.e konfiguracja menedzera okien  
  
      
    4.Instalacja systemu bazowego  
  
Nazwa hosta:
      
    int023   
  
   ![](./img/Zrzut%20ekranu%20(141).png)
  
Domena:  
      
    s3  
  
![](./img/Zrzut%20ekranu%20(142).png)  

Ustawienia partycji   
      
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
  
Hasło urzytkownika root  
  
    root_int01  
  
![](./img/Zrzut%20ekranu%20(143).png)
  
Nazwa domyślnego użytkownika  
  
    Nazwa: userint01    
  
![](./img/Zrzut%20ekranu%20(144).png)
  
Hasło:   
  
    user_int01    
  
![](./img/Zrzut%20ekranu%20(145).png)  
  
    Menedzer okien:  
  
![](./img/Zrzut%20ekranu%20(151).png)  
  
    Z jakiej lokalizacji będą pobierana paczki    
  
![](./img/Zrzut%20ekranu%20(152).png)
  
![](./img/Zrzut%20ekranu%20(155).png)  
  
    Odznaczamy wszystkie opcje oprócz standard system untilities  
  


Serwer lustrzany:  
  
    ftp.pl.debian.org    
  
![](./img/Zrzut%20ekranu%20(153).png)
    
   Póżniej w oknie Proxy http: klikamy dalej    
  
![](./img/Zrzut%20ekranu%20(154).png)
  
    5. Instalacja serwera X.org  
  
    apt update- aktualizujemy na poczatek cashe zeby wszystko poszlo bezblednie    
  
Póżniej 
      
    apt-get install xserver-xorg xbase-clients xfonts-base xterm  
    
Sprawdzamy czy wszystko działa poleceniem:  
  
    startx  
  
Powinno się nam ukazać okno (terminala) rozpoznamy to po innej czcionce i powinniśmy mieć myszkę  
  
    Plik /etc/X11/xorg.conf jest pusty  
  
 ![](./img/Zrzut%20ekranu%20(159).png)   
  
    6.Konfiguracja oraz instalacja fluxbox  
Instalacja   
  
    apt install fluxbox
  
    Po ponownym uruchomieniu startx powinnismy byc powitani przez pulpit (nowy)    
  
  ![](./img/Zrzut%20ekranu%20(160).png)
 
    7.Instalacja dodatkowego oprogramowania:    
Instalacja xpdf: 
  
    apt-get install xpdf  
  
Instalacja lynx: 
    
    apt-get install lynx  
  
Instalacja iceweasel:  
  
Iceweasel musimy zainstalować za pomocą przeglądarki ponieważ jest przestarzała.  
Pierwsze pobieramy firefox  
  
    apt-get install firefox-esr   
    DISPLAY=:0 firefox     
  
![](./img/Zrzut%20ekranu%20(161).png)
  
Poberamy paczkę z internetu można skorzystać ze [strony ](https://pkgs.org/download/iceweasel)    
  
    Pobieramy plik .deb i zapisujemy go do /Download  
      
    Pózniej przedhodzimy cd /Download  i w tym katalogu dokonujemy instalacji  
      
    apt get install /iceweasel*.deb  
  
Instalacja OpenOffice:    
  
Przechodzimy na stronę internetową  [link](https://www.openoffice.org/pl/download/) wybieramy wersję *.deb  
  
    Nastepnie pobieramy plik *tar.gz i go rozpakowujemy  
      
    Przechodzimy do katalogu gdzie go pobraliśmy i rozpakowujemy  
  
    Za pomocą komendy tar -xf *pobrany plik*tar.gz  
   
     
    8.Instalacja i konfiguracja sudo
  
Instalacja sudo  
  
    apt install sudo   
  
 
    9. Konfiguracja użytkownika  
  
Dodajemy użytkownika do grupy sudo po zainstalowaniu sudo   

    usermod -aG sudo userint01  
  
Zezwalamy aby urzytkownik userint01 mógł używac shutdown  
  
    Komenda: sudo visudo  
  
Dodajemy tą linię przed 0includedir  
  
    userint01 int023=NOPASSWD: /usr/bin/systemctl poweroff, /usr/bin/systemctl halt, /usr/bin/systemctl reboot  
  
    10.Konfiguracja Fluxbox:
  
Autostart   
  
    Na końcu pliku dodajemy `/.fluxbox.startup linijkę: exec xterm podmieniamy róznież exec fluxbox na fluxbox  
  
Ikony na pulpit:
  
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
    Tapeta   
Pobieramy tapetę z internetu i wykonujemy komendę   
  
    nitrogen *nazwa pliku z tapetą*  
    
   Ekran logowania
   - sudo apt install lightdm
   
   ![](file:///D:/debian%20aso%20dokumentacja/Zrzut%20ekranu%20(59).png)
   
    11.Pliki konfiguracyjne  
/etc/fstab    
  
![](./img/Zrzut%20ekranu%20(174).png) 
  
/etc/passwd    
  
 ![](./img/Zrzut%20ekranu%20(173).png)
  
/etc/shadow    
  
![](./img/Zrzut%20ekranu%20(172).png) 
  
/etc/group    
  
![](./img/Zrzut%20ekranu%20(166).png)
/etc/network/interfaces    
 ![](./img/Zrzut%20ekranu%20(171).png)
  
/etc/resolv.conf    
 ![](./img/Zrzut%20ekranu%20(170).png)
/etc/sudoers    
![](./img/Zrzut%20ekranu%20(169).png)

  [1]: https://code.visualstudio.com/docs/setup/linux
