# **MedLinkGuard**  
  

Aplikacja MedLinkGuard jest to program na Androida umożliwiający odczyt poziomu cukru (glukozy) z sensora Enlite (firmy Medtronic).  
  

Aplikacja MedLinkGuard łączy się poprzez Bluetooth z pilotem MedLink odbierającym dane z nadajnika MiniLink (Medtronic).  
  

<img src="https://raw.githubusercontent.com/paweltota/MedLinkGuard/main/Media/TransmisjaDanych.png" align="left" style="width: 100%" />  
  



  

**<div align="center">Aplikacja MedLinkGuard może działać bez dostępu do internetu. </div>**  
  

****  
  

## **Główne funkcje:**  
  

- Odczyt poziomu glukozy oraz 2ch poprzednich odczytów, czyli sprzed 5-ciu i 10 ciu minut. Wartości glikemii można kalibrować.  
  

- Funkcje alarmów: o wysokim i/lub niskim poziomie cukru z możliwością ustawienia czasu uruchomienia kolejnego alarmu w przypadku utrzymującego się poziomu cukru spoza zakresu.  
  

- Aplikacja posiada funkcję przesyłania informacji o poziomie cukru na stronę Nightscout ([http://nightscout.pl/instalacja/heroku/](http://nightscout.pl/instalacja/heroku/))  
  

### **Wyświetlane poziomy glikemii mają na stałe przypisane kolory wg schematu:**  
  

- <70 czerwony  
  

- 70-89 pomarańczowy  
  

- 90-159 zielony  
  

- 160-179 pomarańczowy  
  

- />180 czerwony  
  

****  
  

### **Uwagi do aplikacji:**  
  

1.	Przed uruchomieniem skanowania upewnij się, że jest włączona lokalizacja.  
  

### ***<div align="center">Aplikacja nie jest produktem medycznym. Korzystasz na własną odpowiedzialność.</div>***  
  

****  
  

## **Aby móc korzystać z programu MedLinkGuard należy:**  
  

1.	Posiadać pilot MedLink w wersji v4 lub v5. Twórcą pilota i jego oprogramowania jest Sławomir Malinowski (https://github.com/sarunia) 
Informacje o pilocie v4: https://github.com/sarunia/Med-Link-v4 
Informacje o pilocie v5: https://github.com/sarunia/Med-Link-v5  
  

2.	Zaprogramować pilota MedLink (wg instrukcji dla danego pilota). 
Programując pilota należy wgrać oprogramowanie: 
Enlite sniffer 868MHz last EN version extra.s19 (autor: Sławomir Malinowski) (można pobrać również ze strony autora: https://github.com/sarunia/Enlite-receiver-sniffer)
  
  

3.	Pobrać i zainstalować na smartfonie aplikację: MedLinkGuard.apk  
  

****  
  

## **Opis wybranych funkcji aplikacji**  
  

****  
  

### **PASEK GÓRNY**  
  

<img src="https://raw.githubusercontent.com/paweltota/MedLinkGuard/main/Media/PasekGorny.png" align="left" style="width: 100%" />  
  

**1.	Pierwsza ikonka - status Bluetooth**  
  

- szara ikonka - brak włączonego Bluetooth   
  

- niebieska ikonka - Bluetooth włączony  
  

**2.	Druga ikonka - stan transmitera MiniLink**  
  

- szara "muszelka" - od czasu uruchomienia aplikacja nie odczytała jeszcze danych z nadajnika MiniLink.   
  

- czerwona - podany numer nadajnika MiniLink jest błędny   
  

- zielona - podany numer nadajnika MiniLink jest prawidłowy  
  

**3.	Trzecia ikonka - stan naładowania baterii nadajnika MiniLink**  
  

**4.	Czwarta ikonka - status polączenia z pilotem MedLink**  
  

- MedLink (czerwony) - brak połączenia   
  

- MedLink (zielony) - połączenie z pilotem aktywne  
  

**5.	Piąta ikonka - stan naładowania baterii pilota MedLink**  
  

**6.	Szósta ikonka - informacja o SDK Androida**  
  

****  
  

### **ALARMY**  
  

### **Aplikacja posiada możliwość ustawienia alarmów:**  
  

- dolną i górną granicę wartości glikemii  
  

- czasu na jaki zostanie wyciszony alarm o niskim/wysokim cukrze  
  

- czasu na jaki zostanie wyciszony alarm informujący o braku odczytów  
  

****  
  

### **USTAWIENIA**  
  

#### **Strona Nightscout – API secret (hasło)**  
  

Aby zapisać w aplikacji hasło do strony Nightscout należy go najpierw zakodować.
Można to zrobić np. na stronie: http://www.sha1-online.com/  
  

W formularzu należy wpisać hasło i kliknąć przycisk "hash", skopiować ciąg znaków w linii „Result for sha1:”, po czym wrócić do aplikacji i wkleić w miejscu hasła.  
  

<img src="https://raw.githubusercontent.com/paweltota/MedLinkGuard/main/Media/WWWhaslo.png" align="left" style="width: 100%" />  
  

****  
  

### **KALIBRACJA**  
  

Z moich obserwacji wynika, iż najtrudniejsza jest pierwsza doba, kiedy to bardzo trudno prawidłowo skalibrować aplikację. Wynika to z "wysycania" się sensora Enlite. W kolejnych dobach współczynnik kalibracji ustala się na w miarę stałym poziomie. Pomimo tego okresowe sprawdzenie poziomu cukru glukometrem jest wskazane.  
  

****  
  

### **Informacje dodatkowe:**  
  

Więcej o sensorach Enlite np. tutaj:  
  

https://diabetyk24.pl/sensor-elektroda-enlite-do-monitorowania-glukozy-1-szt  
  

Więcej o nadajniku MiniLink (firmy Medtronic) np. tutaj:  
  

https://diabetyk24.pl/refundacja-nfz-transmiter-minilink-mmt-7703ww-1-szt  
  

****  
  

  
  

### **Polecane strony:**  
  

http://nightscout.pl/  
  

<div align="center">
<img src="https://komarev.com/ghpvc/?username=paweltota&&style=flat-square" align="center" />
</div>  
  

<br/>  


## My Skill Set  
<table><tr><td valign="top" width="33%">



</td><td valign="top" width="33%">



</td><td valign="top" width="33%">



</td></tr></table>  

<br/>  


## Connect with me  
  

<br/>  


## Github Stats  
  

<br/>  


## Recent Blog Posts  
  

<br/>  

  

<br/>  

  

<br/>  

  

<br/>  


<br />

----
<div align="center">Generated using <a href="https://profilinator.rishav.dev/" target="_blank">Github Profilinator</a></div>
