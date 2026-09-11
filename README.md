Lernperiode 11
14.8 bis 11.9.2024

## Grob-Planung

Erklären Sie Ihre Projekt-Idee in einem Satz, als müssen Sie einen Investor davon überzeugen.

Ich will den SmartPainter (oder modern painter) auf meinem Mobiltelefon verwenden um meine games auch im zus spielen zu können. 
Für dies werde ich erst einmals den SmartPainter und Reader verbessern müssen, so dass sie unter den respektiven Plattformen funktionieren. Insbesondere beim Reader muss ich ihn so auslegen dass er mit und ohne tastatur funktioniert. Hierfür brauche ich einmal ein Konzept woher/wie die tasten unter Mobile funktioneren sollten und dann auf der technischen seite wie ich dies Konkret implementieren kann. Dazu kommt das implementieren einer Optimierten lösung mittels Maui. 

Verglichen mit P335 ist dieses projekt ganz anders, da es alleine keine applikation, sondern ein framework für eine solche ist. 

User Story Roles:
 - enduser = person die die applikation tatsächlich braucht
 - Painter User = person die apps für den SPainter entwickelt
 - Developer = person die an SPainter entwickelt


14.8
 - [X] Als Developer möchte ich ein Sauberes projekt, so dass ich die spezifische Mobile implementation einfach implementieren kann
 - [X] Als Developer möchte ich eine Idee für eingaben um die Eingaben eines Nutzers effizient und unplattformabhängig eingelesen werden können
 - [ ] Als Enduser möchte ich dass die Applikation performant und Unplattformabhängig verwenden können

Ich konnte heute ein Projekt auswählen und den Existierenden code auf meine neue entwicklungsumgebung sowie die Mobilverwendung vorbereiten.

21.8.
 - [ ] Als Enduser möchte ich dass die Applikation performant und Unplattformabhängig verwenden können
 - [X] Als Developer möchte ich eine Idee für eingaben um die Eingaben eines Nutzers effizient und unplattformabhängig eingelesen werden können
 - [X] Als Painter User möchte ich meine Eingaben sinnvoll mappen unabhängig von der Plattform um meine games leichter auf allen plattformen publizieren zu können
 - [ ] Als Enduser möchte ich dass die Applikation auf mobile läuft (programm initiieren) um von meinem handy aus SPainter zu verwenden

28.8.
 - [X] Als Painter user möchte ich tastatureingaben einfach lesen können, um mit dem endnutzer zu interagieren
 - [X] Als Painter User möchte ich die position der maus lesen können, um mit dem endnutzre zu interagieren
 - [ ] Als Enduser möchte ich dass die Applikation auf mobile läuft (programm initiieren) um von meinem handy aus SPainter zu verwenden
 - [X] Als Painter user möchte ich dass ich den gleichen code für windows, linux und mobile verwenden kann, um meinen aufwand zu vermindern

04.9.
 - [X] Als Developer möchte ich, dass ich die applikation in einem Emulator testen kann, so dass ich weis ob die app funktioniert
 - [X] Als Enduser möchte ich dass die Applikation auf mobile läuft (programm initiieren) um von meinem handy aus SPainter zu verwenden
 - [ ] Als Painter user möchte ich auf mobile auf den screen malen können, um mein game anzuzeigen
 - [ ] Als Painter user möchte ich optimierte versionen von funktionen verwenden können, um die performance zu verbessern

Leider konnte ich heute nicht so viel erreichen wie ich erwartete. Ich versuchte erst mit einem Framework das Projekt umzusetzen, was sich jedoch herausstellte nicht vernünftig zu funktionieren. Daher darf/muss ich nun die app in direktem native Android for .NET umsetzen. 

11.9.

 - [ ] Als Painter user möchte ich auf mobile auf den screen malen können, um mein game anzuzeigen
 - [ ] Als Painter user möchte ich optimierte versionen von funktionen verwenden können, um die performance zu verbessern
 - [ ] Als Painter user möchte ich responsiveness, so dass meine apps besser plattformunabhängig laufen
 - [ ] Als Enduser möchte ich dass die app performant läuft, so dass ich sie auch auf meinem alten handy verwenden kann

Leider konnte ich heute nur so knapp die implementation von text machen, denn dieses projekt ist komplett out of scope. 

## Absolute Reflexion

Alles in allem war dieses Projekt ein kompletter fehlschlag. Zwar konnte ich sehr effektiv die infrastruktur des Modern Painters ausbauen, jedoch schlug die implementation der mobilversion komplett fehl. Ich kam zwar zu einem punkt wo ich die grundätzlichen grundlagen des rendering implementieren konnte, jedoch brauchte ich sehr viel herumprobieren bis ich zu einem framework kam, welches meine anforderungen auch nur annähernd umsetzen konnte. Dank dem und dem weiteren Refinment des generellen ModernPainters verlor ich sehr viel zeit. Dazulernen konnte ich auch nur wenig, denn wie sich herausstellte waren mobile applikationen überhaupt nicht das was ich machen wollte. 

<img width="704" height="1412" alt="Screencast From 2026-09-11 11-43-36" src="https://github.com/user-attachments/assets/4e45d459-f168-4b55-8823-8cfab6105d0c" />


Code siehe ModernPainter
