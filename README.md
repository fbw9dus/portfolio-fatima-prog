# Profil-Seite

![layout](drafts/page.png "Portfolio Seite")

- Seite nur für mobile
- meta Tag für die korrekte Skalierung auf Handys benutzen:
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1">
  ```
- Link für Email, der E-Mail Anwendung öffnet (5/5)
```diff
- Die URL hat Leerzeichen und Sonderzeichen, deshalb wird der Email-Betreff nicht übernommen
```
- Link für Telefon, der Telefon-Anwendung öffnet (5/5)
- Link zum Lebenslauf(PDF), der einen Download auslöst (5/5)
- Links zu Social Media Profilen
  - Haben Icons der Dienste (4/10)
```diff
- Die Icons sind als Bilder und nicht als Vektor-Grafiken mit Fontawesome eingebunden
- Das Twitter-Icon wird nicht richtig dargestellt
```
  - Sollen in einem neuen Tab öffnen (5/5)
  
- Foto, das im Kreis dargestellt wird, mit border-radius (5/5)
- Navigation zu den Abschnitten mit Hash-Links (8/10)
```diff
- target blank im hash-Link macht keinen Sinn
```
- Bilder im Portfolio sollen verlinkt sein (8/10)
```diff
Die Verschachtelung von img in a ist richtig, aber du hast einen absoluten Pfad verwendet, der nur auf deinem Computer funktionieren kann und viele Andere Probleme macht. Bitte nur relative Pfade benutzen. Die einzige Außnhame sind Links auf fremde Webseiten.
```

## Anforderungen für den Code
- Keine Block-Tags in Inline-Tags (10/10)
```diff
- Bitte nicht p in li benutzen
```
- Padding in den Links der Hauptnavigation (10/10)
- Abstand zwischen Text und Fensterrand und zwischen Text und Element-Rand (10/10)
- Korrekte html-Grundstruktur (html, head, body) (8/10)
```diff
- br-Tags dürfen nicht benutzt werden um Elemente untereinander anzuzeigen oder um Abstände zu erzeugen.
- Der hr-Tag sollte nicht benutzt werden. Stattdessen border
```
- Keine Viewport-Elemente im head (5/5)

### Punkte
(**88**/100)
```diff
- Obwohl du viele Punkte hast, würde ich empfehlen, ins Tutoring zu kommen um Pfade zu üben und zu klären, wie man die Darstellung von Elementen nebeneinander und und untereinander steuert und wie man Abstände definiert.
```
