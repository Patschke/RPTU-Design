TeX-Dokumente im Corporate Design der RPTU Kaiserslautern-Landau
=============

## LaTeX-Beamer
Mit LaTeX Beamer kannst du Präsentationen erstellen. In diesem Repository liegt ein Theme, das versucht das Corporate Design der RPTU umzusetzen. Dabei wird sich was das Layout angeht an den vorhandenen Vorlagen für PowerPoint orientiert. Alle Optionen finden sich in den Folien `optionen.pdf` im Ordner `LaTeX-Beamer`. Ich freue mich über Rückmeldungen. 

### Verwendung
Dieses Repository ist auf https://github.com/Patschke/RPTU-Design verfügbar. Die aktuellste Version erhält man über den Button „Download ZIP“ der sich im Drop-Down Menü „Code“ versteckt. Die `example-pres-RPTU-design.tex` gibt eine Idee, wie das ganze genutzt werden soll. 

Falls du mit LuaLaTeX (oder XeLaTeX) kompilierst, wird die Unischrift RedHatText verwendet - die sollte dann auch installiert sein ;-)

## LaTeX-Baposter
Baposter ist ein Poster Template von Brian Amberg. Hier findest du eine Adaption für das Corporate Design der RPTU. Aktuell ist von den fünf Vorlagen
für wissenschaftliche Poster nur das klassische Design umgesetzt. 

### Verwendung
Dieses Repository ist auf https://github.com/Patschke/RPTU-Design verfügbar. Die aktuellste Version erhält man über den Button „Download ZIP“ der sich im Drop-Down Menü „Code“ versteckt. Das `example-poster.tex` gibt eine Idee, wie das ganze genutzt werden soll. Auch hier wird RedHatText verwendet, diese Schrift sollte also installiert sein. 

## Briefvorlagen 
Die Briefvorlagen sind vom offiziellen Brand-Portal der RPTU unter https://rptu.de/intern/brand-portal

Fragen hierzu bitte direkt an die zuständigen Stellen. 

## Troubleshooting

### Schriftart nicht gefunden, obwohl installiert (Ubuntu)
Ubuntu neigt dazu, Schriftarten nur für einzelne Nutzer zu installieren. Je nach LaTeX Installation findet dieses die Schriften dann allerdings nicht. Mit `fc-list | grep RedHat` lässt sich prüfen, ob dieses in `/usr/share/fonts` (dort sucht LaTeX meistens) oder `~/.local/share/fonts` bzw. `~/.fonts` liegen (dort sucht LaTeX meistens nicht). Ubuntu bietet sicher irgendwo auch die Option einer Systemweiten Installation, hat die aber erfolgreich vor mir versteckt. Im Zweifel funktioniert es, einfach die font-files manuell nach `/usr/share/fonts` zu legen (https://github.com/RedHatOfficial/RedHatFont/releases,  die `ttf` Unterordner von `fonts/mono/static` und `fonts/proportional/static` kopieren) sowie danach per `fc-cache` den Font-Cache neu zu bauen. 


## Lizenz

Die Quelltext-Dateien liegen unter folgender Lizenz
	
	% THE BEER-WARE LICENSE (Rev. 42):
	% Ronny Bergmann <bergmann@mathematik.uni-kl.de> wrote this file. As long as
	% you retain this notice you can do whatever you want with this stuff. If we
	% meet some day, and you think this stuff is worth it, you can buy me a beer
	% or coffee in return.

Tatsächlich ist vermutlich nicht mehr viel von Ronnys Code übrig, da für den Wechsel zur RPTU quasi alles von Patrick Mischke <mischke@rptu.de> neugeschrieben 
wurde. Ich mag keinen Kaffee oder Bier, aber irgendwas nettes darfst du mir natürlich trotzdem ausgeben, falls wir uns mal über den Weg laufen ;-)

Die Rechte der Logos liegen bei den jeweiligen Rechte-Inhabern.
