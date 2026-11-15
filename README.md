# Arbeitsauftrag
Zum Ansehen und Bearbeiten der Webseite https://onlinehtmlviewer.com öffnen.

## Initiales HTML für Webseite:
```
<!doctype html>
<html lang="de">
<head>
  <meta charset="utf-8">
  <title>Orte in der Schweiz</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 30px; background: #f4f7f4; }
    section { background: white; padding: 10px; margin: 10px 0; }
  </style>
</head>
<body>
  <h1>Unterwegs in der Schweiz</h1>
  <p>Von Bergen bis zu Seen: Die Schweiz ist vielfältig</p>

  <section>
    <h2>Bern</h2>
    <!-- https://thumb.wikimedia.org/wikipedia/commons/thumb/b/bf/CH_Bern_Kramgasse.jpg/500px-CH_Bern_Kramgasse.jpg?utm_source=de.wikipedia.org&utm_campaign=imageinfo&utm_content=thumbnail -->
    <p>Bern ist bekannt für seine historische Altstadt. Ebenfalls sehenswert:</p>
    <ul>
      <li>Zytglogge</li>
      <li>Bärengraben</li>
      <li>Freibad Marzili</li>
    </ul>
  </section>

  <section>
    <h2>Luzern</h2>
    <p>Luzern liegt am Vierwaldstättersee und ist für die Kapellbrücke bekannt.</p>

  <section>
    <h2>Lugano</h2>
    <p>Lugano liegt im Tessin am Luganersee.</p>
  </section>

  <p>Weitere Inspirationen findet man auf
    <a href="https://www.myswitzerland.com/">MySwitzerland<a>.
  </p>
</body>
</html>
```

## Aufgaben zu HTML (1. Lektion)
1. Ins Template hat sich ein Fehler eingeschlichen: Die Abschnitte "Luzern" und "Lugano" sollten getrennt voneinander angezeigt werden. Behebe den Fehler.
2. Füge im Abschnitt "Bern" ein Bild der Stadt Bern ein. Der Pfad zu einem möglichen Bild ist bereits als Kommentar im Code hinterlegt. (Dokumentation: https://developer.mozilla.org/de/docs/Web/HTML/Reference/Elements/img)
3. Füge einen zusätzlichen Abschnitt (\<section>) für Zürich ein. Der Abschnitt soll einen Titel, einen Absatz und einen Link beinhalten.
4. Die Aufzählung im Abschnitt "Bern" ist derzeit nicht nummeriert. Passe das HTML so an, dass eine nummerierte Liste angezeigt wird.
5. Passe das HTML so an, dass der Text "Die Schweiz ist vielfältig" fett gedruckt wird.
6. (Optional) Anstelle eines Bildes füge ein Video über einen Ort ein. (Mögliche Videodatei: https://raw.githubusercontent.com/regloff/kwi_html/main/assets/switzerland.mp4)

## Aufgaben zu CSS (2. Lektion)
1. Ändere die Farbe des Titels "Unterwegs in der Schweiz".
2. Ändere die Schriftart der ganzen Webseite zu "Georgia".
3. Verwende einen ID-Selektor, um die Hintergrundfarbe des Abschnitts «Bern» anzupassen.
4. Runde die Ecken aller Abschnitte ab.
5. Vergrössere den Abstand zwischen den Abschnitten. Was ist der Unterschied zwischen `padding` und `margin`?
6. Nun haben wir die Grundlagen beieinander. Verschönere die Webseite nach deinem eigenen Geschmack.