# TGF MOUSE TUNING PACK 1.0

![GitHub language count](https://img.shields.io/github/languages/count/The-Geek-Freaks/TGF-Mouse-Tuning-Pack-1.0) ![GitHub top language](https://img.shields.io/github/languages/top/The-Geek-Freaks/TGF-Mouse-Tuning-Pack-1.0) ![Discord](https://img.shields.io/discord/397127284114325504) ![GitHub repo size](https://img.shields.io/github/repo-size/The-Geek-Freaks/TGF-Mouse-Tuning-Pack-1.0) ![GitHub All Releases](https://img.shields.io/github/downloads/The-Geek-Freaks/TGF-Mouse-Tuning-Pack-1.0/total) ![GitHub Pre-Releases](https://img.shields.io/github/downloads-pre/The-Geek-Freaks/TGF-Mouse-Tuning-Pack-1.0/latest/total) ![GitHub issues](https://img.shields.io/github/issues-raw/The-Geek-Freaks/TGF-Mouse-Tuning-Pack-1.0) ![Website](https://img.shields.io/website?down_color=lightgrey&down_message=Offline&up_color=blue&up_message=Online&url=https%3A%2F%2Ftuning-pack.de) ![GitHub forks](https://img.shields.io/github/forks/The-Geek-Freaks/TGF-Mouse-Tuning-Pack-1.0?style=social) ![GitHub stars](https://img.shields.io/github/stars/The-Geek-Freaks/TGF-Mouse-Tuning-Pack-1.0?style=social) ![GitHub watchers](https://img.shields.io/github/watchers/The-Geek-Freaks/TGF-Mouse-Tuning-Pack-1.0?style=social) ![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/The-Geek-Freaks/TGF-Mouse-Tuning-Pack-1.0?include_prereleases)


## Diese Version wurde im August 2020 durch durch das TGF Mouse Tuning Pack 2.0 ersetzt. Diese Version ist nur noch zur Archivierung Online. Viel Spaß beim Tweaken, selber nutzen, bearbeiten ...


### WAS IST ES?

DAS TGF MOUSE TUNING PACK ist ein Tool, welches die die Mauszeigerbeschleunigung von Windows 7, 8, 8.1 oder 10 entfernt.
Es entfernt die Mausbeschleunigung und sorgt dafür, dass es keine Beschleunigung oder Verzögerung der Übertragung gibt.
Dadurch wird eine 1-zu-1-Maus-zu-Zeiger-Antwort für Windows 7, Windows 8.x oder Windows 10 möglich.

Genau gesagt bedeutet 1-zu-1, dass während des Spiels keine Mauseingaben verworfen oder verzögert werden.

### WIE BENUTZT MAN ES?


* MouseAccelerationFix.ps1 ausführen
* Fix anwenden
* Windows Neu-Starten

- Die 1:1 Reaktion der Maus genießen

### WARUM BENÖTIGT MAN DEN FIX?

Einige ältere Spiele wie Half-Life 1, Counter-Strike 1.x, Quake, Quake 2, Unreal und andere rufen, während sie aktiv sind und ausgeführt werden, eine Windows-Funktion auf, mit der die variable Mausbeschleunigung deaktiviert werden soll, indem ALLE Bewegungen erzwungen werden um den gleichen Betrag beschleunigt (verdoppelt).
Unter Windows 2000 und früheren Versionen wurden alle variablen Beschleunigungen entfernt.
Das Zeigen und Zielen in diesen Spielen war in Ordnung, da die Mausreaktion dann linear war (alle Bewegungen wurden um den gleichen Betrag beschleunigt; sie wurden verdoppelt).

In XP und späteren Windows-Versionen hat Microsoft die Funktionsweise der Mauszeigerbeschleunigung geändert.
Wenn in diesen Spielen die Funktion aufgerufen wird (alle Bewegungen müssen beschleunigt werden), aktiviert Windows die Funktion "Zeigergenauigkeit verbessern", mit der die Maus mithilfe einer variierenden Kurve beschleunigt wird, um die Mausreaktion zu steuern. (Es wird aktiviert, auch wenn es in den Mauseinstellungen der Systemsteuerung deaktiviert ist.)

Wenn die Option "Zeigergenauigkeit verbessern" aktiviert ist, wird der Zeiger durch langsamere Mausbewegungen besonders langsam und durch schnellere Mausbewegungen besonders schnell. Es ist nicht linear und nicht geradlinig.

Das ist ärgerlich, denn wo man hinzielt, hängt davon ab, wie weit die Maus bewegt wird und wie schnell ie Maus zum Zielen bewegt wird.

![](https://intranet.minerswin.de/serveimage.png)

### WIE FUNKTIONIERT DER FIX?

Die von der Funktion "Zeigergenauigkeit verbessern" verwendete Kurve wird so neu definiert, dass sie eine vollständig gerade Linie ist. Die Neigung der Linie wird so angepasst, dass jede Mausbewegung auf dem Mauspad genau die gleiche Bewegung des Mauszeigers auf dem Bildschirm bewirkt.

### WIE SIEHT MAN, DASS DER FIX FUNKTIONIERT?

Es kann getestet werden, ob es funktioniert, indem die Funktion "Zeigergenauigkeit verbessern" vorübergehend aktiviert und überprüft wird, wie die Maus reagiert.

Wenn die Option "Zeigergenauigkeit verbessern" deaktiviert wurde, ist der Fix nicht aktiv (er wartet jedoch darauf, bei Bedarf aktiviert zu werden).
So wie einige Spiele es aktivieren, wenn es nicht gewünscht wird, kann es manuell aktiviert werden, um zu testen, ob das Update ordnungsgemäß funktionierte.


### WAS KANN ICH SONST NOCH MACHEN?

.... #Updates
