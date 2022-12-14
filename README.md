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
  
  

### **Przegląd wszystkich funkcji i możliwości aplikacji można zobaczyć na zrzucie ekranu: [Aplikacja Po Rozwinięciu Menu - zrzut ekranu](https://raw.githubusercontent.com/paweltota/MedLinkGuard/main/ZrzutyEkranu/002-aplikacjaPoRozwinieciuMenu.jpg)**

### **Wyświetlane poziomy glikemii mają na stałe przypisane kolory wg schematu:**  
  

- <70 czerwony  
  

- 70-89 pomarańczowy  
  

- 90-159 zielony  
  

- 160-179 pomarańczowy  
  

- \>180 czerwony  
  

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
  

### **KALIBRACJA**  
  

Z moich obserwacji wynika, iż najtrudniejsza jest pierwsza doba, kiedy to bardzo trudno prawidłowo skalibrować aplikację. Wynika to z "wysycania" się sensora Enlite. W kolejnych dobach współczynnik kalibracji ustala się na w miarę stałym poziomie. Pomimo tego okresowe sprawdzenie poziomu cukru glukometrem jest wskazane.  
  

****  
  

### **Informacje dodatkowe:**  
  

Więcej o <b>sensorach Enlite</b> np. tutaj:  

https://diabetyk24.pl/sensor-elektroda-enlite-do-monitorowania-glukozy-1-szt  
  
 <br/>  
  
Więcej o <b>nadajniku MiniLink</b> (firmy Medtronic) np. tutaj:  

https://diabetyk24.pl/refundacja-nfz-transmiter-minilink-mmt-7703ww-1-szt  

<br/>  
  
<b>MedLink</b> to urządzenie, które można samemu zbudować na podstawie projektu.
Więcej informacji tutaj: Wersja większa (v4): https://github.com/sarunia/Med-Link-v4 oraz mniejsza wersja urządzenia (v5): https://github.com/sarunia/Med-Link-v5

Jest też grupa na Facebook'u: ([MED-LINK pilot i uploader Nightscout dla pomp Medtronic Veo i 722](https://www.facebook.com/groups/492021978253801))

****  
  

  
  

### **Polecane strony:**  
  

http://nightscout.pl/  
  

<div align="center">
<img src="https://komarev.com/ghpvc/?username=paweltota&&style=flat-square" align="center" />
</div>  
  

<br/>  
