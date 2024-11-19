# Quick-Time-Game
## Descriere
* Acest proiect implementează un joc de reflexe intre doi jucători folosind două plăci Arduino Uno.
  * Fiecare jucător are trei butoane, trei LED-uri și un LED RGB, iar scopul este să apese butonul corespunzător culorii afișate pe LED-ul RGB cât mai rapid.
  * Punctajele jucătorilor sunt afișate în timp real pe un ecran LCD, iar la final este declarat câștigătorul.
  * Un servomotor indică progresul jocului prin rotație, iar o rotație completă marchează sfârșitul acestuia.
  * Comunicarea între plăcile Arduino se realizează prin protocolul SPI: Arduino-ul master controlează ecranul LCD, servomotorul și starea jocului, iar cel slave gestionează butoanele, LED-urile și un buzzer.
## Componente utilizate
* 2x Arduino UNO (ATmega328P microcontroller)
* 6x LED-uri (2 grupuri de câte 3 leduri, în cadrul unui grup trebuie să avem culori diferite)
* 2x LED RGB (1 pentru fiecare jucător)
* 1x LCD
* 1x Servomotor
* 1x Potențiometru
* 1x Buzzer
* 2x Breadboard
* 22x Rezistoare (1x 100, 20x 220, 1x 330)
* 7x butoane (3 pentru fiecare jucător si unul pentru start)
* Fire de legătură
## Setup fizic
![20241119_135333](https://github.com/user-attachments/assets/6b9b253f-9630-469a-b801-cf9a8257a27f)
![20241119_135247](https://github.com/user-attachments/assets/1b89c08a-1dac-417c-ab32-3fdbef83928d)
![20241119_135350](https://github.com/user-attachments/assets/e3b99e4f-0a19-42a7-8e2d-9993b630cfac)
![20241119_135340](https://github.com/user-attachments/assets/89a7dc93-f021-4f25-86f6-18fcd33269d5)

## Funcționalitatea montajului fizic
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/fg7UXB8JGXM/0.jpg)](https://www.youtube.com/watch?v=fg7UXB8JGXM)

## Schema Electrică
![image](https://github.com/user-attachments/assets/1af246a5-4dd4-4a22-9e64-43c932b32129)



