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

<p>

Die Skulptur stellte einen wichtigen Lebens-Aspekt im antiken Griechenland dar, wobei sie sich stetig weiterentwickelte. Diese Entwicklung lässt sich in die drei Epochen, Archaik, Klassik und Hellenistik einordnen. Die Projektarbeit bestand nun darin, diese Einordnung mittels verschiedener sogenannter Classifier, also Klassifizierungsalgorithmen, zu automatisieren. Als Programmbibliothek wurde hierfür OpenCV mit der Programmiersprache Java verwendet. Korpora für die Statuen war die Datenbank Arachne des Deutschen Archäologischen Instituts (DAI) und des Archäologischen Instituts der Universität zu Köln.
</p>
<p>
In einer vorherigen Studie gab es  bereits einen Ansatz um westliche Gemälde in Epochen einzustufen. Dabei stellt vor allem das Filtern struktureller Merkmale dieser Epochen, wie beispielsweise Pinseltechniken, eine relevante Grundlage dar (Shen, 2009).  In Levante wurden 2006, von Gansell, Tamaru, Jakulin und Wiggins erfolgreich Elfenbein-Skulpturen klassifiziert um sie zentralen Produktionsstätten zuweisen zu können. Dabei konnte man mit Hilfe von Machine Learning eine 98-prozentige Genauigkeit erzielen. Als Grundlage dazu dienten 66 kategorisierte Features, um die einzelnen kulturellen und handwerklichen Merkmale zu unterscheiden. Zur Klassifizierung von Skulpturen braucht man  verschiedene Detektoren die erst mal alle Default-Fälle, also Bilder die keine Skulpturen zeigen, aus der Datenbank heraus zu filtern, damit die Skulpturen später an  die Classifierer übergeben werden können. Insgesamt gibt es also mehrere Projekte in diesem Forschungsgebiet auf denen wir aufbauen können. Für die Grundkonzepte zu  Data Mining und Supervised

</p>

<
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
<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Methode</h3>

<p>
Das Entstehen von Wissen aus Erfahrungen, wird in unserem Projekt nachgeahmt, sodass mit Hilfe maschinellen Lernens einzelne Werke aus den drei Epochen Klassik, Hellenismus und Archaik anhand von vorher festgelegten stilistischen Regeln und Kriterien erkannt werden.
Bei unserem Projekt, das sich mit der Erkennung von Statuen aus drei Epochen, auseinandersetzt, haben wir uns der Methode des supervised learning bedient. Unser Ziel ist eine möglichst genaue Einordnung der jeweiligen Statuen in deren Epochen. 
Ein Ziel, das gewisse kunsthistorische Kenntnisse voraussetzt. Dabei ist wichtig, dem Computer die vielerlei kleinen Unterschiede, die es innerhalb dieser Epoche und Kunstform gibt, auf eine Weise zu lehren, die ihn dazu befähigt präziser zu sein als ein vergleichbarer Mensch, der sich ebenso genau mit dieser Kunstform und dieser Epoche auseinandergesetzt hat. Der erste Schritt bestand darin eine möglichst große Datenbank zu erstellen. Diese Datenbank stellt dabei die Bilder da, die er in der Lage sein sollte zu erkennen und zu unterscheiden. Auf diesen Bilddateien sind hauptsächlich Statuen zu sehen aber auch andere Artefakte wie Bücher und Gemälde, da das Programm auch in der Lage sein sollte, zu bestimmen, ob eine Statue zu erkennen ist oder nicht. Ist die Datenbank soweit gefüllt, geht es im nächsten Schritt darum, dem Programm Features beizubringen. Hierzu werden die verschiedenen Bilddateien zunächst vorverarbeitet. Dieser Schritt ist sehr wichtig, da hier die Bilddatei auf das wesentliche reduziert wird um die Qualität der zu bestimmenden Merkmale steigern zu können. Dieser Schritt ist obligatorisch um dem Rechner eine Grundbasis zur Verfügung stellen. An dieser Stelle werden die ersten Filter angewendet.
Sind die Bilder Dateien vorverarbeitet, geht es jetzt darum die Detektoren anzuwenden. Im Optimalfall sollen diese endgültig bestimmen um welche Epoche es sich handelt. Eigenschaften, die die jeweiligen Statuen auszeichnen, wurden mit Hilfe unseres Experten analysiert und anschließend vom Programmier-Team eingebunden. Dabei nutzen wir eine Reihe von Classifiern (Klassifikation) um das Programm manuell zu trainieren. 

OpenCV ist eine opensource Bibliothek für Algorithmen zur Bildbearbeitungen und maschinellen Sehen. Bei unserem Anwendungsfall verwenden wir Anwendungstools zur Erstellung einer Mustererkennung.
Mit Hilfe von OpenCV haben wir dem Computer anhand von positiven und negativen Beispielen beigebracht, was er erkennen sollte und was nicht in die zu erkennende Kategorie gehört. Dieser Vorgang ist der wichtigste Schritt. Das Programm sollte nach dem abgeschlossenen Training in der Lage sein, die Dateien, die eingelesen werden, ihrer Klasse zuzuordnen. Die Merkmale, die aus den verschiedenen Detektoren resultieren, werden mit Hilfe eines Klassifikators, einer Klasse bzw. Epoche zugeordnet.
In OpenCV gibt es die Möglichkeit über einen Konsolenbefehl, eigene Haar Cascade Classifier zu generieren. Diese beinhalten alle Features, die ein positives Bild besitzen muss. Anhand der Features die aus den positiven Bildern generiert wurden, werden Muster erstellt, die dann mit allen anderen Bildern abgeglichen werden. Anschließend wird die Cascade-xml in den Java-Code eingefügt. 
Das Haar-cascade kann schließlich eine eigenständige Objekterkennung durchführen . Das Wort “Cascade” meint in diesem Zusammenhang, dass der resultierende Classifier, der am Ende bestimmt, ob das Bild positiv oder negativ ist, aus mehreren einfacheren Classifiern besteht. Sobald ein Bild von einem Classifier abgelehnt wird, wird dieses von der weiteren Verarbeitung ausgeschlossen. (Viola&Jones, 2001)
</p>
<h3>
<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Programmfähigkeiten</h3>
<p>Erkennung von Statuen</p>
<p>Einordnung in den kunsthistorischen Kontext</p>
<p>Differenzierung von dargestellten Gottheiten</p>


<h3>
<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Ergebnisse:</h3>


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


<h3>
<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Vorgehensweise:</h3>
<p>Umsetzung mit innerhalb von Supervised Learning</p>
<p> 
Einteilung der Bilder in positiv und negativ</p>



<a id="support-or-contact" class="anchor" href="#support-or-contact" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Support or Contact</h3>

<p>Having trouble with Pages? Check out our <a href="https://help.github.com/pages">documentation</a> or <a href="https://github.com/contact">contact support</a> and we’ll help you sort it out.</p>

      <footer class="site-footer">
        <span class="site-footer-owner"><a href="#">Opencv</a> is maintained by <a href="https://github.com/ashrafsp">Ashrafsp</a>.</span>

        <span class="site-footer-credits">This page was generated by <a href="https://pages.github.com">GitHub Pages</a> using the <a href="https://github.com/jasonlong/cayman-theme">Cayman theme</a> by <a href="https://twitter.com/jasonlong">Jason Long</a>.</span>
      </footer>

    </section>

  
  </body>
</html>

