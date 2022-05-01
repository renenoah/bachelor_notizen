# Ersten Algo realisieren

## Vorbereitung den algo zu realisieren

## Problem

Aktuell is es nicht möglich den sinus zu berechnen, wir müssen daher diesen realiseren
**Problem: Sinus arbeitet mit floating point. Ist das möglich auf dem Pulpissimo ? Wie kann ich generell sin realiseren**
Mein erste Idee ist ein lib zu implementieren.
Hier müsste ich eine statische lib includen, da dynamisch in der runtime gelinkt werden und es keine runtime gibt

Könnte mir hier newlib weiterhelfen ? Wieso gibt es kein math.h in pulpissimo
Problem wurde hier geklärt: <https://github.com/pulp-platform/pulpissimo/issues/125>
Woher kommt mein aktueller Compiler, den ich benutze. Für welche config wurde der angepasst

Ich muss laut dem link math.h aktiv mit compile durch -lm
Hier wird der grund erklärt:
<https://askubuntu.com/questions/332884/how-to-compile-a-c-program-that-uses-math-h>

```console
test
```
