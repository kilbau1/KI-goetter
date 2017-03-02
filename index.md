## Griechische Götter im kunsthistorischen Kontext


<html lang="en-us">
  <head>
    <meta charset="UTF-8">
    <title>Opencv by ashrafsp</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" type="text/css" href="stylesheets/normalize.css" media="screen">
    <link href='https://fonts.googleapis.com/css?family=Open+Sans:400,700' rel='stylesheet' type='text/css'>
    <link rel="stylesheet" type="text/css" href="stylesheets/stylesheet.css" media="screen">
    <link rel="stylesheet" type="text/css" href="stylesheets/github-light.css" media="screen">
  </head>
  <body>
    <section class="page-header">
      <h1 class="project-name">Künstliche Intelligenz und   Cultural Heritage</h1>
      <h2 class="project-tagline"></h2>
      <a href="https://github.com/ashrafsp/opencv" class="btn">View on GitHub</a>
      <a href="https://github.com/ashrafsp/opencv/zipball/master" class="btn">Download .zip</a>
      <a href="https://github.com/ashrafsp/opencv/tarball/master" class="btn">Download .tar.gz</a>
    </section>

    <section class="main-content">
      <h3>
<a id="welcome-to-github-pages" class="anchor" href="#welcome-to-github-pages" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Forschungsprojekt ‘Griechische Goetter im kunsthistorischen Kontext’</h3>

<h4> Idee: </h4>
<p> Einordnung von griech. und röm. Statuen in die kunsthistorische Epochen:
Archaik
Klassik
Hellenismus
</p>
<h4>Aufgaben</h4> 
<p>1.Einlesen einer Bilddatei</p>
<p>2.Bildbearbeitung für die bestmögliche Computer Vision </p>
<p>3.Anlegen von Mustern und Regeln </p>
<p>4.kunsthistorisch </p>
<p>5.mythologisch (optional) </p>
<p>6.Erkennung von Mustern und Regeln </p> 
<p>7.Identifizierung und Kategorisierung </p>

<h3>
<a id="designer-templates" class="anchor" href="#designer-templates" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Projektorganisation</h3>

<p>Team Datenbank:</p>
<p>Sammeln und pflegen der Datenbank.</p>
<p>Team Bildvorverarbeitung:</p>
<p>Greifen auf die Datenbank zu und setzen Filter zur Vorverarbeitung ein.
</p>
<p>Team CV:</p>
<p>Definieren die Erkennungsmerkmale, Machine Learning und Output </p>
<p>Differenzierung von Mustern und Regeln</p>
<p>Experte:</p>
<p> Kilian kontrolliert die Umsetzung und sorgt dafür, die Statuen im richtigen Kontext gesetzt werden </p>
<h3>
<a id="creating-pages-manually" class="anchor" href="#creating-pages-manually" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Kategoriseriung der wichtigsten Filter:</h3>

<p>1. Gesichtsdetektor</p>
<p>2. Shapedetektor</p>
<p>3. Oberflächendetektor</p>
<p>4. Hintergrundsubtraktion</p>
<p>5. Farbdekektor</p>


<h3>
<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Aktueller Zustand:</h3>

<p>Datenbank ist nahezu vollständig</p>
<p>"einfache" Filter laufen</p>
<p>aufwenidigere befinden sich in der Testphase</p>
<p>einlesen von Stauen optimieren</p>
<p>OpenCV Anwendungen hinzufügen
</p>
<h3>
<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Programmfähigkeiten</h3>
<p>Erkennung von Statuen</p>
<p>Einordnung in den kunsthistorischen Kontext</p>
<p>Differenzierung von dargestellten Gottheiten</p>

<h3>


<h3>
<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Vorgehensweise:</h3>
<p>Umsetzung mit innerhalb von Supervised Learning</p>
<p>Erstellung von Mustern anhand der errechneten Features über Haar Cascades</p>
<p>Die Muster gelten als Richtlinie für die nachfolgenden Bilder </p>
<p>Trainieren des Computers manuel mithilfe von Classifiern</p>
<p>Cascade-xml anschließend in den Code eingebettet </p>
<p>Einteilung der Bilder in positiv und negativ</p>
<p>

<h3>

<h3>
<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Ergebnis:</h3>
<p>1.Erkennung von Skulpturen</p>
<p>Statuen unterteilt in Oberkoerper (UpperBodyDetector.java), Unterkörper (LowerBodyDetector.java) und Gesicht (FaceDetector.java)</p>
<p>Unterscheidung zwischen Farbton (ColorDetector.java)</p>
<p>2. Einordnung in Epochen </p>
<p>Datenbank mit 1500 Bilder <p>
<p>Image Pre-Processing<p>
<p>Einordnung der Bilder in die Epochen</p>
<p>Bilder auf die gleiche Größe skalliert</p>
<p>Vereinheitlichung in ein Format </p>
<p>Umwandlung in Graustufen für weniger Farbkanäle</p>
</h3>


<a id="support-or-contact" class="anchor" href="#support-or-contact" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Support or Contact</h3>

<p>Having trouble with Pages? Check out our <a href="https://help.github.com/pages">documentation</a> or <a href="https://github.com/contact">contact support</a> and we’ll help you sort it out.</p>

      <footer class="site-footer">
        <span class="site-footer-owner"><a href="#">Opencv</a> is maintained by <a href="https://github.com/ashrafsp">Ashrafsp</a>.</span>

        <span class="site-footer-credits">This page was generated by <a href="https://pages.github.com">GitHub Pages</a> using the <a href="https://github.com/jasonlong/cayman-theme">Cayman theme</a> by <a href="https://twitter.com/jasonlong">Jason Long</a>.</span>
      </footer>

    </section>

  
  </body>
</html>

