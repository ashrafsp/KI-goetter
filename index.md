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
In einer vorherigen Studie gab es  bereits einen Ansatz um westliche Gemälde in Epochen einzustufen. Dabei stellt vor allem das Filtern struktureller Merkmale dieser Epochen, wie beispielsweise Pinseltechniken, eine relevante Grundlage dar (Shen, 2009).  In Levante wurden 2006, von Gansell, Tamaru, Jakulin und Wiggins erfolgreich Elfenbein-Skulpturen klassifiziert um sie zentralen Produktionsstätten zuweisen zu können. Dabei konnte man mit Hilfe von Machine Learning eine 98-prozentige Genauigkeit erzielen. Als Grundlage dazu dienten 66 kategorisierte Features, um die einzelnen kulturellen und handwerklichen Merkmale zu unterscheiden. Zur Klassifizierung von Skulpturen braucht man  verschiedene Detektoren die erst mal alle Default-Fälle, also Bilder die keine Skulpturen zeigen, aus der Datenbank heraus zu filtern, damit die Skulpturen später an  die Classifierer übergeben werden können. Insgesamt gibt es also mehrere Projekte in diesem Forschungsgebiet auf denen wir aufbauen können. Für die Grundkonzepte zu  Data Mining und Supervised Learning nutzten wir das Werk "Data Mining: Theoretische Aspekte” als Grundlage. (Nakhaeizadeh,1998). Der Schwerpunkt lag also anschließend darin, die Classifier und Features zu optimieren und auf unser Projekt zuzuschneiden. </p>

<h4> Epochen </h4>
<p> Die Zeit- und Stilepoche der Archaik dauerte ca. von 700-500 v.Chr. Die Skulpturen in dieser Epoche werden unterschieden zwischen Kouros, unbekleideter männlicher Darstellung und Kore, bekleideter weiblicher Darstellung. Ihre Körperhaltung ist meist starr mit paralleler Gelenkstellung, die einzige Abweichung dieser Parallelität ist zunächst nur ein um eine Fußlänge vorgestreckte Bein, durch das fortführen der Parallelität im Gesicht scheinen die Skulpturen zu lächeln, diese Ausarbeitung wird auch speziell „archaisches Lächeln“ genannt. Zur dieser Zeit standen die Statuen meist in Mauernischen und wahren zum Teil auch noch mit dem Gemäuer verbunden, sie haben also nur eine Vorderseite. 
Die Epoche der Klassik dauerte ca. bis zum Tod Alexander des Großen 323 v. Chr. Die Ausarbeitung der Körper wird in dieser Epoche immer natürlicher. Ein wichtiger Bestandteil der Skulpturen ist ein Gegenspiel von Bewegung und Ruhe auch Kontrapost genannt bei dem  ein gestrafftes, zunächst, rechtes Bein ist dem gelösten rechten Arm zugeordnet ist, dem gelockerten Spielbein entspricht der kraftvoll angewinkelte linke Arm. Durch Interaktion mit Gegenständen oder weiteren Figuren können im späteren Verlauf der Epoche beide Arme belastet sein.
Die Hellenistische Periode dauerte von 323 v. Chr bis ca. 30 v.Chr.  Bei den Skulpturen dieser Zeit streben die Körper Achsen erstmals in alle Richtungen auseinander.  Der Raum wird somit allseitig erobert und greift erstmals auch durch Durchbrüche in die Statue mit ein. Meistens wird der Moment dargestellt der kurz vor einer besonderen Aktion liegt, von Gotthold Ephraim Lessing später „fruchtbarer Augenblick“ genannt. Die Skulpturen scheinen so in ihren Bewegungsabläufen wie eingefroren. Um die Bewegung zu zelebrieren wird nun auch öfter in Bronze gegossen.
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
<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Methode</h3>

<p>
Das Entstehen von Wissen aus Erfahrungen, wird in unserem Projekt nachgeahmt, sodass mit Hilfe maschinellen Lernens einzelne Werke aus den drei Epochen Klassik, Hellenismus und Archaik anhand von vorher festgelegten stilistischen Regeln und Kriterien erkannt werden.
Bei unserem Projekt, das sich mit der Erkennung von Statuen aus drei Epochen, auseinandersetzt, haben wir uns der Methode des supervised learning bedient. Unser Ziel ist eine möglichst genaue Einordnung der jeweiligen Statuen in deren Epochen. 
Ein Ziel, das gewisse kunsthistorische Kenntnisse voraussetzt. Dabei ist wichtig, dem Computer die vielerlei kleinen Unterschiede, die es innerhalb dieser Epoche und Kunstform gibt, auf eine Weise zu lehren, die ihn dazu befähigt präziser zu sein als ein vergleichbarer Mensch, der sich ebenso genau mit dieser Kunstform und dieser Epoche auseinandergesetzt hat. Der erste Schritt bestand darin eine möglichst große Datenbank zu erstellen. Diese Datenbank stellt dabei die Bilder da, die er in der Lage sein sollte zu erkennen und zu unterscheiden. Auf diesen Bilddateien sind hauptsächlich Statuen zu sehen aber auch andere Artefakte wie Bücher und Gemälde, da das Programm auch in der Lage sein sollte, zu bestimmen, ob eine Statue zu erkennen ist oder nicht. Ist die Datenbank soweit gefüllt, geht es im nächsten Schritt darum, dem Programm Features beizubringen. Hierzu werden die verschiedenen Bilddateien zunächst vorverarbeitet. Dieser Schritt ist sehr wichtig, da hier die Bilddatei auf das wesentliche reduziert wird um die Qualität der zu bestimmenden Merkmale steigern zu können. Dieser Schritt ist obligatorisch um dem Rechner eine Grundbasis zur Verfügung stellen. An dieser Stelle werden die ersten Filter angewendet.
Sind die Bilder Dateien vorverarbeitet, geht es jetzt darum die Detektoren anzuwenden. Im Optimalfall sollen diese endgültig bestimmen um welche Epoche es sich handelt. Eigenschaften, die die jeweiligen Statuen auszeichnen, wurden mit Hilfe unseres Experten analysiert und anschließend vom Programmier-Team eingebunden. Dabei nutzen wir eine Reihe von Classifiern (Klassifikation) um das Programm manuell zu trainieren. 

OpenCV ist eine opensource Bibliothek für Algorithmen zur Bildbearbeitungen und maschinellen Sehen. Bei unserem Anwendungsfall verwenden wir Anwendungstools zur Erstellung einer Mustererkennung.
Mit Hilfe von OpenCV haben wir dem Computer anhand von positiven und negativen Beispielen beigebracht, was er erkennen sollte und was nicht in die zu erkennende Kategorie gehört. Dieser Vorgang ist der wichtigste Schritt. Das Programm sollte nach dem abgeschlossenen Training in der Lage sein, die Dateien, die eingelesen werden, ihrer Klasse zuzuordnen. Die Merkmale, die aus den verschiedenen Detektoren resultieren, werden mit Hilfe eines Klassifikators, einer Klasse bzw. Epoche zugeordnet.
In OpenCV gibt es die Möglichkeit über einen Konsolenbefehl, eigene Haar Cascade Classifier zu generieren. Diese beinhalten alle Features, die ein positives Bild besitzen muss. Anhand der Features die aus den positiven Bildern generiert wurden, werden Muster erstellt, die dann mit allen anderen Bildern abgeglichen werden. Anschließend wird die Cascade-xml in den Java-Code eingefügt. 
Das Haar-cascade kann schließlich eine eigenständige Objekterkennung durchführen . Das Wort “Cascade” meint in diesem Zusammenhang, dass der resultierende Classifier, der am Ende bestimmt, ob das Bild positiv oder negativ ist, aus mehreren einfacheren Classifiern besteht. Sobald ein Bild von einem Classifier abgelehnt wird, wird dieses von der weiteren Verarbeitung ausgeschlossen. (Viola& Jones, 2001)
</p>
<h3>
<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Programmfähigkeiten</h3>
<p>Erkennung von Statuen</p>
<p>Einordnung in den kunsthistorischen Kontext</p>
<p>Differenzierung von dargestellten Gottheiten</p>

<h3>
<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Ergebnisse:</h3>
<p>Die Erkennung von Statuen der Archaik mit Hilfe des Archaik-Classifiers funktioniert relativ zuverlässig. Ebenso zuverlässig funktioniert auch die Erkennung von Statuen der Klassik mit Hilfe des Klassik-Classifiers. Lässt man beide Classifier die jeweils andere Epoche analysieren, offenbart sich, dass die Classifier positiv anschlagen, obwohl sie es eigentlich nicht sollen. Der Hellenismus-Classifier scheitert so lange beim Erkennen einer Hellenismus-Statue, bis die Parameter soweit “aufgeweicht” werden, dass er auch kleinere Bildelemente als Treffer ausgibt. Leider führt dieses dann aber dazu, dass er unter Umständen auch Treffer in den Bildern von Klassik und Archaik Statuen anzeigt. 


<p>Probleme 
Die Natur von Classifiern, die detaillierte, nicht-homogene Natur der Statuen und das herunterskalieren der Bilder in eine kleinstmöglichste Auflösung führen zu einem reduzierten Ergebnis. Die Ähnlichkeit von Archaik und Klassik Statuen führt dazu, dass die jeweiligen Classifier oft nicht zwischen den zwei Epochen unterscheiden können. Während die Statuen dieser Epochen untereinander zumindest die Körperhaltung mehr oder weniger gemein haben, ist das bei den Statuen der Hellenistik ein größeres Problem: Hier hat beinahe jede Statue eine andere Körperhaltung, was dazu führt, dass der Classifier Mühe hat, genügend Eigenschaften zu finden, die auf alle Bilder der Epoche zutreffen. 
Zudem war das Trainieren der Classifier sehr zeitaufwendig. Der Vorgang wurde mehrmals abgebrochen und musste in der Genauigkeit reduziert werden,  damit das Weiterarbeiten mit fertiggestellten Daten möglich war.e</p>



<h3>
<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Vorgehensweise:</h3>
<p>1.Erkennung von Skulpturen</p>
<p>Statuen unterteilt in Oberkoerper (UpperBodyDetector.java), Unterkörper (LowerBodyDetector.java) und Gesicht (FaceDetector.java)</p>
<p>Unterscheidung zwischen Farbton (ColorDetector.java)</p>
<p>2. Einordnung in Epochen </p>
<p>Datenbank mit 1500 Bilder <p>
<p>Image Pre-Processing<p>
<p>Einordnung der Bilder in die Epochen</p>
<p>Bilder auf die gleiche Größe skalliert</p>
<p>Vereinheitlichung in ein Format </p>
<p>Trainieren des Computers manuel mithilfe von Classifiern</p>
<p>Cascade-xml anschließend in den Code eingebettet </p>
<p>Umwandlung in Graustufen für weniger Farbkanäle</p>



<h3>
<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Diskussion</h3>
<p>
 Diskussion
Retroperspektiv lässt sich das Ergebnis hinterfragen. Beispielsweise dadurch, ob die geringe Erkennungsrate der Statuen vorherbestimmt war, da die Statuen sich zu sehr ähneln oder ob ein größerer Korpus an Statuen und längere Trainingszeit der Classifier mit mehr Stages dazu geführt hätte das genug eindeutige Merkmale erkannt wurden. Die Beantwortung dieser Frage bedarf weiterer empirischer Untersuchungen. Aus geisteswissenschaftlicher Sicht lässt sich die Diskussion entfachen, ob diese Art von Klassifizierung jemals Fachleute bei der Einordnung ersetzen können oder braucht es eine bestimmte Spanne von Varianz, beispielsweise durch unterschiedliche Fachmeinungen, um den Kunstmarkt zu definieren? Da ein Künstler oder Kunstobjekt sonst wenig Aufmerksamkeit erregt und somit weniger Verbreitung findet oder Interesse gewinnt.
</p>


<h3>
<a id="authors-and-contributors" class="anchor" href="#authors-and-contributors" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Vorgehensweise:</h3>
<p>Umsetzung mit innerhalb von Supervised Learning</p>
<p> 
Einteilung der Bilder in positiv und negativ</p>


<h3>
<a id="support-or-contact" class="anchor" href="#support-or-contact" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Support or Contact</h3>


    </section>

  
  </body>
</html>

