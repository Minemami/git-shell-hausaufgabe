# Git Shell Hausaufgabe

Dieses Repository enthält ein kleines Bash-Skript für einfache IT-Support-Aufgaben.

Das Skript kann:
- den Benutzer begrüßen
- ein Menü anzeigen
- Systeminformationen anzeigen
- Speicherplatz prüfen
- falsche Eingaben erkennen

## Geübte Git-Themen

- git add
- git commit
- git push
- git branch
- git checkout
- git merge

# Theoriefragen

## 1. Was ist ein Merge-Konflikt?

Ein Merge-Konflikt entsteht, wenn Git zwei Änderungen nicht automatisch zusammenführen kann. Meistens passiert das, wenn zwei Branches dieselbe Stelle in einer Datei geändert haben.

## 2. Warum entsteht ein Merge-Konflikt meistens dann, wenn zwei Branches dieselbe Stelle in derselben Datei verändert haben?

Git weiß dann nicht, welche Änderung richtig ist. Deshalb muss der Benutzer entscheiden, welche Version behalten werden soll.

## 3. Warum haben Sie in dieser Aufgabe keinen Merge-Konflikt bekommen?

Die Aufgaben wurden in einer festen Reihenfolge bearbeitet. Außerdem wurden die Änderungen sauber nacheinander gemergt.

## 4. Was zeigt Git in einer Datei an, wenn ein Merge-Konflikt entsteht?

Git zeigt spezielle Markierungen wie <<<<<<<, ======= und >>>>>>> an. Damit erkennt man die verschiedenen Änderungen.

## 5. Welche Schritte muss man grundsätzlich durchführen, um einen Merge-Konflikt sauber zu lösen?

Man muss die Konflikte in der Datei bearbeiten, die richtige Version auswählen, die Datei speichern und danach erneut committen.

## 6. Warum sollte man nach dem Lösen eines Merge-Konflikts das Programm oder Skript noch einmal testen?

Damit man sicher ist, dass das Programm nach der Änderung noch richtig funktioniert.

# Merge und Rebase vergleichen

## 7. Was macht git merge?

git merge verbindet die Änderungen eines Branches mit einem anderen Branch.

## 8. Was macht git rebase?

git rebase verschiebt Commits auf einen neuen Stand der Historie.

## 9. Was ist der wichtigste Unterschied zwischen merge und rebase?

Merge erstellt einen gemeinsamen Merge-Commit. Rebase verändert die Commit-Historie.

## 10. Warum bleibt bei merge oft besser sichtbar, wann ein Branch zusammengeführt wurde?

Weil merge einen zusätzlichen Commit erstellt, der den Zeitpunkt des Zusammenführens zeigt.

## 11. Warum kann rebase die Git-Historie sauberer aussehen lassen?

Weil die Historie linear aussieht und weniger zusätzliche Merge-Commits entstehen.

## 12. Warum sollte man mit rebase vorsichtig sein, wenn ein Branch bereits mit anderen geteilt wurde?

Weil rebase die Historie verändert und dadurch Probleme für andere Entwickler entstehen können.

## 13. Wann würden Sie eher merge verwenden?

Wenn mehrere Personen zusammenarbeiten und die echte Historie sichtbar bleiben soll.

## 14. Wann könnte rebase sinnvoll sein?

Wenn man eine saubere und lineare Historie haben möchte.