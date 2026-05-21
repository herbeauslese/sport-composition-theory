---
layout: default
lang: de
title: Sport Composition Theory
description: Ein Framework zur Zerlegung jeder Sportart in ihre fundamentalen Komponenten.
---

# Sport Composition Theory

*Ein Framework dafür, woraus eine Sportart eigentlich besteht.*

<button id="sidebar-toggle" class="sidebar-toggle" type="button" aria-label="Inhaltsverzeichnis öffnen" aria-expanded="false">☰</button>

<aside id="sidebar" class="sidebar" aria-label="Seitenleiste">
  <div class="sidebar-inner">
    <p class="sidebar-brand">Sport Composition Theory</p>

    <nav class="toc" aria-label="Inhaltsverzeichnis">
      <p class="toc-title">Inhalt</p>
      <ol class="toc-list">
        <li><a href="#hintergrund">Hintergrund</a></li>
        <li><a href="#die-theorie">Die Theorie</a>
          <ol>
            <li><a href="#annahmen">Annahmen</a></li>
            <li><a href="#komponenten">Komponenten</a></li>
          </ol>
        </li>
        <li><a href="#vorbehalte-anmerkungen">Vorbehalte &amp; Anmerkungen</a></li>
        <li><a href="#methodik">Methodik</a></li>
        <li><a href="#beispiele">Beispiele</a></li>
        <li><a href="#vergleich">Vergleich</a>
          <ol>
            <li><a href="#strukturelle-distanz">Strukturelle Distanz</a></li>
          </ol>
        </li>
      </ol>
    </nav>

    <div class="sidebar-controls">
      <a class="lang-link" href="{{ '/en/' | relative_url }}" hreflang="en" lang="en">English</a>
      <button id="theme-toggle" class="theme-toggle" type="button" aria-label="Theme umschalten">Theme: Auto</button>
    </div>
  </div>
</aside>

<div id="sidebar-backdrop" class="sidebar-backdrop" aria-hidden="true"></div>

---

## Hintergrund

Irgendwann hört man es zum hundertsten Mal: dass Fußballer im Vergleich zu Sprintern, Turnern oder Boxern „eigentlich keinen richtigen Sport machen". Dass sie körperlich weich seien, dass ihr Sport in Wirklichkeit gar nicht so anspruchsvoll sei wie das, was andere Athleten leisten. Das Argument ist alt, es wird in Stammtischrunden geführt und in Talkshows, und es endet meistens damit, dass beide Seiten ihre Position lauter wiederholen.

Was an dem Streit reizvoll ist, ist nicht die Antwort. Es ist die Frage, die darunter liegt: *Wie vergleicht man Sportarten eigentlich?* Nicht in der Frage, welche spannender ist, welche fordernder, welche prestigeträchtiger. Sondern strukturell. Was braucht es, um in etwas gut zu sein? Welche Art von Anforderungen — im weitesten Sinne — stellt eine Sportart an den Athleten?

Man nehme einen Sprinter und einen Formel-1-Fahrer. Beide sind Spitzensportler, die am absoluten Limit menschlicher Leistungsfähigkeit antreten. Aber die Natur ihrer Exzellenz ist grundverschieden. Der Sprinter hat seinen Körper über Jahre darauf geformt, einen einzigen explosiven Output von unter zehn Sekunden zu produzieren. Der Formel-1-Fahrer muss bei 300 km/h einen Strom sensorischer Eindrücke verarbeiten und in Sekundenbruchteilen taktische Entscheidungen treffen — Entscheidungen, die sich über eine ganze Rennstrategie hinweg tragen müssen, die wiederum über Dutzende Runden aufgebaut wird. Und dann ist da der Schachspieler: keine nennenswerte körperliche Leistung, keine Maschine, keine Strecke — nur reine kognitive Auseinandersetzung über ein Brett, in der ein einziger positioneller Fehler in Zug zwölf bis Zug vierzig still und leise alles auseinandernehmen kann.

Drei Athleten. Drei vollständig verschiedene Profile. Und trotzdem treten alle drei an, gewinnen und verlieren auf Basis von etwas, das sich messen und vergleichen lässt.

Diese Frage — *was* genau hier gemessen wird — hat zu dieser Theorie geführt.

> *„Was braucht es, um zu gewinnen? Die Antwort sind immer dieselben Komponenten. Nur in unterschiedlichen Verhältnissen."*

---

## Die Theorie

### Annahmen

Bevor die Theorie angewendet werden kann, müssen zwei grundlegende Annahmen akzeptiert werden. Sie lassen sich nicht beweisen — sie sind der Ausgangspunkt, nicht die Schlussfolgerung. Eine formale Definition und eine direkte Konsequenz folgen aus ihnen.

**Annahme 0 — Geltungsbereich.**
Jede Sportart wird in der Form bewertet, in der sie professionell und kompetitiv auf höchstem Niveau ausgeübt wird. Freizeit- oder informelle Varianten sind ausgeschlossen — nicht, weil sie weniger interessant wären, sondern weil die kompetitive Form am klarsten definiert und über Athleten hinweg am konsistentesten vergleichbar ist.

Straßenradsport zum Beispiel ist auf professioneller Ebene ein Mannschaftssport. Ein Domestique opfert sein eigenes Resultat, um einen Kapitän zu schützen; Taktik wirkt über einen ganzen Kader hinweg, nicht nur über einen einzelnen Fahrer. Würde man Straßenradsport als reine individuelle körperliche Leistung bewerten, käme ein fundamental anderer — und weniger zutreffender — Vektor heraus.

Wo eine Sportart in deutlich unterschiedlichen Wettkampfformen existiert, muss jede Version eigens benannt und bewertet werden. Beachvolleyball und Hallenvolleyball teilen sich einen Namen, unterscheiden sich aber strukturell. 100m und 400m Sprint belohnen unterschiedliche körperliche Profile. Sie als austauschbar zu behandeln, würde die Präzision untergraben, auf die das Modell angewiesen ist.

**Annahme 1 — Zerlegbarkeit.**
Jede kompetitive Sportart lässt sich vollständig und sinnvoll durch vier Komponenten beschreiben: Taktik, Physis, Skill und Material. Nichts Wesentliches liegt außerhalb dieser vier Kategorien. Das ist die Kernaussage der Theorie und die einzige, die wirklich zugestimmt werden muss, bevor es weitergeht.

Diese Annahme ist nicht selbstverständlich. Man könnte argumentieren, dass bestimmte Sportarten sich der Reduktion widersetzen — dass die psychologische Dimension des Wettkampfs oder die schwer fassbare Qualität von Teamwork sich nicht in vier Zahlen erfassen lässt. Wir argumentieren, dass diese Dimensionen bereits in den Komponenten enthalten sind, wie sie definiert wurden. Aber wir erkennen die Annahme als das an, was sie ist.

**Definition — Der Composition Vector.**
Aus Annahme 1 folgt, dass jede Sportart *S* formal als Tupel dargestellt werden kann:

<div class="math-block">S = (T, P, Sk, M)</div>

wobei *T* = Taktik, *P* = Physis, *Sk* = Skill, *M* = Material, und:

<div class="math-block">T + P + Sk + M = 1</div>

Alle Werte sind reelle Zahlen im Intervall [0, 1]. Für die meisten Sportarten gilt M = 0, was die Darstellung auf einen Drei-Komponenten-Vektor reduziert.<sup><a href="#fn1" id="fn1ref">1</a></sup>

**Korollar 1 — Vergleichbarkeit.**
Aus Annahme 1 und der Definition folgt direkt, dass je zwei Sportarten sinnvoll verglichen werden können. Weil jede Sportart im selben vierdimensionalen Raum ausgedrückt wird, ist die strukturelle Ähnlichkeit oder Distanz zwischen je zwei Sportarten wohldefiniert. Eine durch Physis dominierte und eine durch Taktik dominierte Sportart sind nicht nur qualitativ verschieden — sie liegen messbar weit auseinander.

**Eine Bemerkung zu Theorie und Anwendung.**
Alles oben Stehende ist exakt. Der Composition Vector ist über reellen Zahlen definiert, und jede Zuweisung, die die Bedingungen erfüllt, ist formal gültig. Konkreten Sportarten konkrete Gewichte zuzuordnen ist eine andere Sache — das ist ein Urteil, keine Messung. Dieser Schritt wird separat behandelt, unter Methodik.

---

### Komponenten

Die vier Komponenten des Composition Vector werden im Folgenden einzeln beschrieben.

#### Taktik

Entscheidungsfindung, Planung, das Lesen von Gegnern und das Anpassen der Strategie in Echtzeit. Taktik umfasst den *Inhalt* der Entscheidungen: die Wahl der Formation, das Lesen einer Situation, die Entscheidung anzugreifen oder zu warten. Es ist die Komponente, die für den Gelegenheitszuschauer am unsichtbarsten und für den ernsthaften Beobachter am entscheidendsten ist.

Taktik betrifft *was* entschieden wird, nicht die kognitive Kapazität, über die Zeit weiter zu entscheiden. Letzteres gehört zur Physis, und die Unterscheidung ist wichtig: ein Athlet, der zehn Minuten lang brillante Entscheidungen trifft und dann mental zusammenbricht, hat nur dann ein Taktik-Problem, wenn die Entscheidungen selbst schlecht waren. Wenn die Entscheidungen korrekt waren, aber irgendwann ausgingen, ist das Problem Kapazität, nicht Urteilsvermögen.

#### Physis

Die Anforderungen an den menschlichen Körper: Kraft, Ausdauer, Schnelligkeit, Beweglichkeit — und ihre mentalen Entsprechungen. Anhaltende Konzentration, psychische Belastbarkeit unter Druck und die Fähigkeit, über lange Zeiträume kognitiv leistungsfähig zu bleiben, zählen ebenfalls hierher. Der Geist ist Teil des Körpers, und im Sport wird er entsprechend trainiert.

Das ist die kognitive *Kapazitäts*-Dimension, die Taktik ergänzt. Eine fünfstündige Schachpartie stellt enorme Anforderungen an die Physis in diesem Sinn, auch wenn kein Muskel ernsthaft beansprucht wird. Die Qualität der gespielten Züge ist Taktik; die Fähigkeit, in Zug sechzig immer noch gute Züge zu finden, ist Physis.

#### Skill

Erlernte menschliche Technik: motorische Kontrolle, Präzision, Koordination und Ausführung. Skill unterscheidet sich von Physis dadurch, dass es um die *Qualität* der Bewegung geht, nicht um die *Kapazität* zu ihr. Der physische Output eines Sprinters ist seine Höchstgeschwindigkeit. Sein Skill ist die Technik, die ihn effizient dorthin bringt.

#### Material

Die Rolle externer Ausrüstung beim Zustandekommen kompetitiver Ergebnisse. Diese Komponente erfordert besondere Aufmerksamkeit.

Fast jede Sportart involviert irgendeine Form von Ausrüstung — Schuhe, Bälle, Schläger. Material gilt **nicht** für alle. Es gilt nur dann, wenn die *Qualität oder Spezifikation* der Ausrüstung einen bedeutsamen, direkten Einfluss auf das Ergebnis hat — wenn ein besser ausgerüsteter Athlet einen strukturellen Vorteil gegenüber einem gleich starken mit schlechterer Ausrüstung hat.

Ein Tennisschläger qualifiziert sich nicht. Ein Formel-1-Auto schon. Ein Bob auch. Ein hochwertiges Straßenrad-Setup liegt irgendwo dazwischen und wird entsprechend behandelt.

Noch eine Anmerkung: Trainingsinfrastruktur — Höhencamps, Spezialbahnen, Spitzentrainerstäbe — könnte prinzipiell unter Material fallen. Auf höchstem kompetitiven Niveau konvergieren diese Faktoren jedoch in der Regel. Die Top-Athleten in den meisten Sportarten haben weitgehend vergleichbaren Zugang zu erstklassigen Einrichtungen, was den differenzierenden Effekt begrenzt. Aus diesem Grund ist Trainingsinfrastruktur aus dem Modell ausgeschlossen, sofern sie nicht eine *persistente, strukturelle* Wettbewerbsasymmetrie erzeugt.

---

## Vorbehalte & Anmerkungen

Der Composition Vector ist eine bewusste Vereinfachung. Das ist ein Feature, kein Mangel — aber es hat Konsequenzen, die explizit benannt werden sollten.

### Das Mannschaftssport-Problem

In Einzelsportarten beschreibt der Composition Vector einen einzelnen Athleten. In Mannschaftssportarten beschreibt er das Team, nicht den Spieler — denn taktische Qualität operiert dort auf zwei Ebenen: kollektiv (Formation, Pressing, Standardsituationen) und individuell (Positionsentscheidungen innerhalb des Systems). Diese sind nicht dasselbe. Ein Spieler mit außergewöhnlicher individueller taktischer Intelligenz kann trotzdem deutlich verlieren, wenn die kollektive Struktur schlecht ist.

Eine praktische Folge: Taktik wiegt in Mannschaftssportarten schwerer, als eine naive Lesart vermuten lässt, weil kollektive Organisation individuelle Überlegenheit in anderen Komponenten kompensieren oder neutralisieren kann. Elf individuell überlegene Athleten ohne System verlieren regelmäßig gegen elf organisierte.

### Material ist nicht symmetrisch zwischen Athleten

Material-Gewichte beschreiben eine Sportart als Ganzes, nicht das Duell zwischen zwei bestimmten Konkurrenten. In Formel 1 macht Material rund die Hälfte des Vektors aus — diese Zahl beschreibt, wie stark Ausrüstung Ergebnisse *im gesamten Feld* prägt. Innerhalb eines einzelnen Teams fahren zwei Fahrer aber identisches Material, und die Komponente kollabiert zwischen ihnen auf null. Dieselbe Logik gilt überall: ein Top-Rennrad ist entscheidend gegen einen Amateur, irrelevant zwischen zwei World-Tour-Profis. Der Composition Vector erfasst die Struktur der Sportart, nicht ein bestimmtes Duell innerhalb ihrer.

### Kritik an der Zerlegbarkeit

Annahme 1 behauptet, dass vier Komponenten ausreichen. Drei plausible Kandidaten für eine fünfte werden hier kurz behandelt — und an ihrem Platz innerhalb des Modells verortet, statt eine eigene Achse zu bekommen.

**Glück, Varianz, Zufall.** Glück ist keine sportliche Leistung; die Komponenten beschreiben, was vom Athleten *verlangt* wird. Wo Zufallsmanagement zur Leistung wird — Wahrscheinlichkeiten rechnen, Gegner lesen wie im Poker — ist das Taktik. Über lange Wettkampfformate (eine Bundesliga-Saison hat 34 Spieltage genau aus diesem Grund) mittelt sich Zufall ohnehin heraus.

**Ästhetik und Wertungssport.** Was Bewerter belohnen, ist im Wesentlichen Skill (saubere Ausführung) plus Physis (Schwierigkeitsgrad). Choreografie und Ausdruck sind eine interpretative Spielart von Skill, keine eigene Achse.

**Mentale Härte.** Bereits in Physis enthalten — die Definition umfasst ausdrücklich psychische Belastbarkeit und kognitive Ausdauer unter Druck. Eine separate Komponente wäre Doppelzählung.

Diese Antworten widerlegen die Einwände nicht; sie verorten sie innerhalb der bestehenden vier Komponenten. Wer das für unzureichend hält, sollte die Theorie entsprechend erweitern.

---

## Methodik

Für jede Sportart werden vier Leitfragen angewandt — eine pro Komponente:

**Taktik:** Wie stark bestimmt ein überlegener strategischer Ansatz — unabhängig von körperlicher Leistungsfähigkeit — den Ausgang eines Wettkampfs?

**Physis:** Wie stark wirkt sich ein messbarer Unterschied in athletischer oder mentaler Konditionierung auf das Ergebnis aus, alles andere gleich gehalten?

**Skill:** Wie sehr wird das Ergebnis durch die Präzision und Qualität erlernter menschlicher Technik bestimmt?

**Material:** Wie sehr würde ein signifikanter Ausrüstungsnachteil — unabhängig vom Athleten — das Ergebnis verändern?

Die resultierenden Werte sind kuratierte Schätzungen, angegeben auf einem 5%-Raster. Falsche Präzision (23,7% zu schreiben, wenn man *grob ein Viertel* meint) würde ein Messverfahren suggerieren, das nicht existiert. Die Schätzungen sind durch Beobachtung, Argumentation und die Art von Diskussionen geprägt, die zustande kommen, wenn jemand zu viel Sport schaut und zu viel Zeit zum Nachdenken hat. Sie sind in gutem Glauben angeboten und werden überarbeitet, wenn bessere Argumente auftauchen.

---

## Beispiele

Die folgenden Aufschlüsselungen sind aktuelle Schätzungen. Jede Sportart wird als ein einzelner Balken dargestellt, der in seine Komponenten unterteilt ist. Unter jedem Balken folgt eine kurze Begründung, warum die Werte so verteilt sind.

<div class="sport-charts">

<div class="sport-entry">
<h3>Fußball</h3>
<p class="sport-meta">11 gegen 11 · 90 Minuten</p>
<div class="stacked-bar-wrap">
  <div class="stacked-bar">
    <div class="seg tactics"   style="width:45%" title="Taktik: 45%"></div>
    <div class="seg physical"  style="width:25%" title="Physis: 25%"></div>
    <div class="seg skill"     style="width:30%" title="Skill: 30%"></div>
  </div>
  <div class="seg-legend">
    <span class="leg-item"><span class="leg-dot tactics"></span>Taktik 45%</span>
    <span class="leg-item"><span class="leg-dot physical"></span>Physis 25%</span>
    <span class="leg-item"><span class="leg-dot skill"></span>Skill 30%</span>
  </div>
</div>
<p class="sport-rationale">Auf Profiniveau ein vor allem taktisch entschiedener Sport: Formation, Pressinghöhe, Standardsituationen und Spielplan gegen einen bestimmten Gegner prägen Ergebnisse stärker als individuelle Klasse. Skill bleibt wichtig (Ballbehandlung, Passqualität), Physis ist Voraussetzung, aber selten der entscheidende Unterschied zwischen zwei Topteams. Kein Material — die Ausrüstung ist standardisiert und über die Liga hinweg vergleichbar.</p>
</div>

<div class="sport-entry">
<h3>Tennis</h3>
<p class="sport-meta">Einzel · drei oder fünf Sätze</p>
<div class="stacked-bar-wrap">
  <div class="stacked-bar">
    <div class="seg tactics"   style="width:20%" title="Taktik: 20%"></div>
    <div class="seg physical"  style="width:35%" title="Physis: 35%"></div>
    <div class="seg skill"     style="width:45%" title="Skill: 45%"></div>
  </div>
  <div class="seg-legend">
    <span class="leg-item"><span class="leg-dot tactics"></span>Taktik 20%</span>
    <span class="leg-item"><span class="leg-dot physical"></span>Physis 35%</span>
    <span class="leg-item"><span class="leg-dot skill"></span>Skill 45%</span>
  </div>
</div>
<p class="sport-rationale">Skill-getrieben: Schlagtechnik, Aufschlagpräzision und Bewegungsökonomie machen den Unterschied zwischen Top-100 und Top-10. Physis ist mit 35% hoch angesetzt, weil Best-of-Five-Matches über mehrere Stunden gehen können und der Wettkampfkalender erbarmungslos ist. Taktik ist real (Aufschlagmuster, Returnposition, Punktaufbau), wirkt aber im direkten Vergleich zu Mannschaftssportarten begrenzt — die Zahl der Spielzüge pro Punkt ist klein. Material ist 0, da Profis untereinander Zugang zu vergleichbarer Ausrüstung haben.</p>
</div>

<div class="sport-entry">
<h3>100m Sprint</h3>
<p class="sport-meta">Reine Leichtathletik-Disziplin</p>
<div class="stacked-bar-wrap">
  <div class="stacked-bar">
    <div class="seg tactics"  style="width:5%"  title="Taktik: 5%"></div>
    <div class="seg physical" style="width:65%" title="Physis: 65%"></div>
    <div class="seg skill"    style="width:30%" title="Skill: 30%"></div>
  </div>
  <div class="seg-legend">
    <span class="leg-item"><span class="leg-dot tactics"></span>Taktik 5%</span>
    <span class="leg-item"><span class="leg-dot physical"></span>Physis 65%</span>
    <span class="leg-item"><span class="leg-dot skill"></span>Skill 30%</span>
  </div>
</div>
<p class="sport-rationale">Vor allem körperliche Anlage und Konditionierung: Schnellkraft, Reaktionszeit, anaerobe Kapazität. Skill steckt in der Technik — Startphase, Beschleunigungsmuster, Lauftechnik — und ist substanzieller, als Laien vermuten. Taktik existiert nur in Mikroentscheidungen (Startverhalten, Bahnzuteilung, Rennrhythmus). Nicht 0, weil diese Entscheidungen messbar sind, aber niedrig genug, um klar dominant von Physis überlagert zu sein.</p>
</div>

<div class="sport-entry">
<h3>Schach</h3>
<p class="sport-meta">Bewusst als Grenzfall aufgenommen</p>
<div class="stacked-bar-wrap">
  <div class="stacked-bar">
    <div class="seg tactics"  style="width:80%" title="Taktik: 80%"></div>
    <div class="seg physical" style="width:10%" title="Physis: 10%"></div>
    <div class="seg skill"    style="width:10%" title="Skill: 10%"></div>
  </div>
  <div class="seg-legend">
    <span class="leg-item"><span class="leg-dot tactics"></span>Taktik 80%</span>
    <span class="leg-item"><span class="leg-dot physical"></span>Physis 10%</span>
    <span class="leg-item"><span class="leg-dot skill"></span>Skill 10%</span>
  </div>
</div>
<p class="sport-rationale">Praktisch reine Entscheidungsleistung — Stellungsbeurteilung, Berechnung, strategische Planung. Skill mit 10% steht für die motorische und mustererkennende Routine: Eröffnungsrepertoire, Standardstrukturen, das schnelle Greifen typischer Manöver. Physis mit 10% ist die kognitive Ausdauer über mehrstündige Partien — keine triviale Komponente, wie jeder Spieler bestätigen wird, der Zug 60 erlebt hat. Kein Material.</p>
</div>

<div class="sport-entry">
<h3>Straßenradsport</h3>
<p class="sport-meta">Grand-Tour-Etappenrennen</p>
<div class="stacked-bar-wrap">
  <div class="stacked-bar">
    <div class="seg tactics"  style="width:30%" title="Taktik: 30%"></div>
    <div class="seg physical" style="width:40%" title="Physis: 40%"></div>
    <div class="seg skill"    style="width:15%" title="Skill: 15%"></div>
    <div class="seg material" style="width:15%" title="Material: 15%"></div>
  </div>
  <div class="seg-legend">
    <span class="leg-item"><span class="leg-dot tactics"></span>Taktik 30%</span>
    <span class="leg-item"><span class="leg-dot physical"></span>Physis 40%</span>
    <span class="leg-item"><span class="leg-dot skill"></span>Skill 15%</span>
    <span class="leg-item"><span class="leg-dot material"></span>Material 15%</span>
  </div>
</div>
<p class="sport-rationale">Ausdauerleistung mit erheblichem taktischen Überbau. Physis ist die Basis — eine dreiwöchige Rundfahrt verlangt eine Konstitution, die durch nichts ersetzbar ist. Taktik ist auf Profiniveau ein Teamspiel: Domestiquen-Einsatz, Ausreißerkalkül, Positionierung in entscheidenden Momenten. Skill betrifft Fahrtechnik und Risikomanagement bei Abfahrten und Klassikern. Material ist real, aber innerhalb der World Tour begrenzt — die Räder unterscheiden sich, aber nicht so dramatisch wie in motorisierten Sportarten.</p>
</div>

<div class="sport-entry">
<h3>Formel 1</h3>
<p class="sport-meta">Fahrer und Konstrukteur zusammen</p>
<div class="stacked-bar-wrap">
  <div class="stacked-bar">
    <div class="seg tactics"  style="width:20%" title="Taktik: 20%"></div>
    <div class="seg physical" style="width:10%" title="Physis: 10%"></div>
    <div class="seg skill"    style="width:15%" title="Skill: 15%"></div>
    <div class="seg material" style="width:55%" title="Material: 55%"></div>
  </div>
  <div class="seg-legend">
    <span class="leg-item"><span class="leg-dot tactics"></span>Taktik 20%</span>
    <span class="leg-item"><span class="leg-dot physical"></span>Physis 10%</span>
    <span class="leg-item"><span class="leg-dot skill"></span>Skill 15%</span>
    <span class="leg-item"><span class="leg-dot material"></span>Material 55%</span>
  </div>
</div>
<p class="sport-rationale">Die einzige Sportart in der Stichprobe, in der Material dominant ist — über die Saison hinweg entscheidet die Konstrukteursleistung mehr über das Klassement als jede individuelle Fahrerstärke. Taktik (Boxenstrategie, Reifenmanagement, Renntempo-Kalkül) ist substanzielle Größe und teils Teamleistung. Skill — Fahrzeugkontrolle am Limit, Spurwahl, Überholtechnik — wirkt im Wettkampf, ist aber innerhalb des Spitzenfelds in engerem Korridor. Physis spielt eine reale, aber begrenzte Rolle: G-Kräfte und Hitze fordern den Körper, ohne dass Konditionierung im Vordergrund stünde.</p>
</div>

</div>

<small>* Die Prozentsätze sind kuratierte Schätzungen aus strukturierter qualitativer Analyse. Sie spiegeln die wohlüberlegte Meinung des Autors wider und sollten entsprechend behandelt werden — also ernst, aber nicht zu ernst.</small>

---

## Vergleich

Mit den Beispielvektoren in der Hand lässt sich die ursprüngliche Frage stellen, von der diese Theorie ausgegangen ist: *Wie vergleicht man Sportarten?* Korollar 1 hat behauptet, dass jeder Vergleich wohldefiniert ist. Dieser Abschnitt zeigt, was das konkret bedeutet.

Die folgenden Beobachtungen sind in zwei Teile gegliedert. Der erste Teil ist strikte Konsequenz der Definition — gegeben die Werte aus dem Beispiele-Abschnitt fallen die Distanzen automatisch heraus. Der zweite Teil (folgt später) verlässt diesen rein formalen Rahmen und stellt Fragen, die die Theorie selbst nicht beantwortet.

### Strukturelle Distanz

Da jede Sportart als Vektor im selben vierdimensionalen Raum ausgedrückt wird, lässt sich die strukturelle Distanz zwischen je zwei Sportarten als Euklidischer Abstand berechnen:

<div class="math-block">d(S₁, S₂) = √[(T₁−T₂)² + (P₁−P₂)² + (Sk₁−Sk₂)² + (M₁−M₂)²]</div>

Der Wertebereich ist beschränkt. Zwei identische Vektoren haben Distanz 0; das theoretische Maximum liegt bei √2 ≈ 1.41 und wird nur erreicht, wenn zwei Sportarten jeweils vollständig in einer einzigen, unterschiedlichen Komponente liegen — also etwa (1, 0, 0, 0) gegen (0, 1, 0, 0). Reale Sportarten erreichen diesen Wert nie. In der vorliegenden Stichprobe reicht die größte beobachtete Distanz an etwa zwei Drittel dieses Maximums heran.

Die folgende Tabelle zeigt die paarweisen Distanzen für die sechs Beispielsportarten:

<div class="distance-matrix-wrap">
<table class="vector-table distance-matrix">
<thead>
<tr><th></th><th>Fußball</th><th>Tennis</th><th>100m</th><th>Schach</th><th>Rad</th><th>F1</th></tr>
</thead>
<tbody>
<tr><th>Fußball</th>         <td>—</td>    <td>0.31</td><td>0.57</td><td>0.43</td><td class="cell-near">0.30</td><td>0.64</td></tr>
<tr><th>Tennis</th>          <td>0.31</td><td>—</td>    <td>0.37</td><td>0.74</td><td>0.35</td><td>0.68</td></tr>
<tr><th>100m Sprint</th>     <td>0.57</td><td>0.37</td><td>—</td>    <td class="cell-far">0.95</td><td>0.41</td><td>0.81</td></tr>
<tr><th>Schach</th>          <td>0.43</td><td>0.74</td><td class="cell-far">0.95</td><td>—</td>    <td>0.60</td><td>0.82</td></tr>
<tr><th>Straßenradsport</th> <td class="cell-near">0.30</td><td>0.35</td><td>0.41</td><td>0.60</td><td>—</td>    <td>0.51</td></tr>
<tr><th>Formel 1</th>        <td>0.64</td><td>0.68</td><td>0.81</td><td>0.82</td><td>0.51</td><td>—</td></tr>
</tbody>
</table>
</div>

Werte sind auf zwei Nachkommastellen gerundet. Sie sollten so gelesen werden: Distanzen unter etwa 0.10 deuten auf strukturelle Ununterscheidbarkeit hin, Distanzen über 0.70 auf grundlegende Verschiedenheit. Alles dazwischen ist Abstufung.

Aus der Matrix lassen sich drei Beobachtungen ableiten, die für sich allein bereits aufschlussreich sind.

**Fußball und Straßenradsport sind die nächsten Nachbarn.** Mit einer Distanz von 0.30 sind sie das engste Paar in der Stichprobe — ein zunächst überraschender Befund, denn äußerlich haben ein Ballsport mit 22 Spielern auf einem Rasenfeld und ein dreiwöchiges Etappenrennen auf der Straße wenig gemein. Strukturell aber teilen sie viel: beide sind Mannschaftssportarten mit substanzieller taktischer Tiefe, ähnlichen Anteilen körperlicher Anforderung und einer untergeordneten Skill-Komponente. Dass Straßenradsport zusätzlich 15% Material trägt, das Fußball nicht hat, ist der einzige nennenswerte Unterschied — und erklärt, warum die Distanz überhaupt 0.30 beträgt und nicht weniger.

**Schach ist das strukturelle Extrem.** Es taucht in vier der sechs Sportarten als fernster Nachbar auf — gegen Sprint, Tennis, Straßenradsport und Formel 1. Die Distanz zwischen Schach und 100m Sprint (0.95) ist die größte in der gesamten Tabelle und liegt nahe am theoretischen Maximum. Das ist erwartbar: Schach ist die einzige Sportart in der Stichprobe, in der eine einzelne Komponente dominant ist (Taktik mit 80%). Diese Konzentration macht es zu jedem anderen Vektor extrem unähnlich, mit Ausnahme von Sportarten, in denen Taktik *ebenfalls* schwer wiegt — was unter den Beispielen nur auf Fußball halbwegs zutrifft (Distanz 0.43, der nächste Nachbar von Schach).

**Straßenradsport ist das strukturelle Zentrum.** Mit einer durchschnittlichen Distanz von 0.44 zu allen anderen Sportarten liegt Straßenradsport im Mittel näher an der Gesamtstichprobe als jede andere Disziplin. Fußball folgt knapp dahinter (0.45), Tennis an dritter Stelle (0.49). Am anderen Ende der Skala stehen Schach (0.71) und Formel 1 (0.69) als die strukturell isoliertesten Sportarten. Was diese Beobachtung suggeriert, ist nicht, dass Straßenradsport *typisch* sei — sondern dass eine breite Verteilung über alle Komponenten, einschließlich eines maßvollen Material-Anteils, ein gewisses strukturelles Schwerezentrum darstellt, von dem aus Spezialisierung (Schach in Richtung Taktik, Sprint in Richtung Physis, Formel 1 in Richtung Material) jeweils messbare Abweichung bedeutet.

Diese drei Beobachtungen folgen unmittelbar aus den Vektoren — sie sind nicht hinzu-interpretiert, sondern in den Zahlen bereits enthalten.

#### Grenzen dieser Berechnung

Die Distanz, wie sie hier definiert ist, ist die einfachste mögliche Wahl. Sie ist nicht die einzige, und sie hat drei methodische Schwächen, die offen benannt werden sollten.

**Die Komponenten werden als gleichwertig behandelt.** Der Euklidische Abstand setzt voraus, dass ein Unterschied von 10 Prozentpunkten in Taktik dasselbe bedeutet wie 10 Prozentpunkte in Material. Das ist eine Annahme, keine Selbstverständlichkeit — Material wirkt strukturell anders als Taktik, wie das Material-Caveat zeigt. Eine gewichtete Distanzformel wäre denkbar, würde aber einen zusätzlichen Gewichtungsvektor einführen, der seinerseits begründet werden müsste. Die Theorie verzichtet bewusst darauf und akzeptiert die Vereinfachung als Preis für die Einfachheit.

**Die Vektoren leben auf einem Simplex, nicht im freien Raum.** Weil T + P + Sk + M = 1 gilt, sind die Vektoren auf einem dreidimensionalen Simplex eingebettet, nicht im vollen 4D-Raum. Das ist keine Schwäche der Distanzformel selbst — der Euklidische Abstand misst korrekt den Abstand auf diesem Simplex — wohl aber ein Hinweis darauf, dass Komponenten nicht unabhängig variieren können. Erhöht sich eine Komponente um 20 Prozentpunkte, müssen die anderen entsprechend nachgeben. Die Distanz misst dies konsistent, aber der Leser sollte sich bewusst sein, dass Bewegungen im Raum eingeschränkt sind.

**Die Eingangswerte sind Schätzungen auf einem 5%-Raster.** Eine Distanz von 0.30 zwischen Fußball und Straßenradsport ist genau so präzise wie die Vektoren, aus denen sie berechnet wurde — also nicht sehr. Eine Verschiebung um 5 Prozentpunkte in einer einzigen Komponente verändert die Distanz typischerweise um 0.03 bis 0.05. Aus diesem Grund werden die Werte in der Tabelle auf zwei Nachkommastellen gerundet dargestellt; weitere Dezimalstellen würden eine Präzision vortäuschen, die in den Eingangswerten nicht enthalten ist. Distanzen sollten in Größenordnungen gelesen werden, nicht in genauen Werten.

---

<div class="footnotes">
<p id="fn1"><sup>1</sup> Zu den genauen Bedingungen, unter denen Material einen Wert ungleich null annimmt, siehe den Abschnitt Material oben. <a href="#fn1ref">↩</a></p>
</div>

<style>
/* ---------- Theme variables ---------- */

:root {
  --bg-page:        #ffffff;
  --bg-header:      transparent;
  --bg-bar-track:   #e8e8e8;
  --bg-mathblock:   rgba(0,0,0,0.05);

  --text-body:      #222;
  --text-muted:     #888;
  --text-table-h:   #555;
  --text-link:      #155799;

  --border-soft:    #e0ddd8;
  --border-table:   #ccc;
  --border-row:     #e8e8e8;
  --border-math:    #ccc;
}

/* Dark when system prefers dark AND user has not chosen light */
@media (prefers-color-scheme: dark) {
  :root:not([data-theme="light"]) {
    --bg-page:        #0d1117;
    --bg-header:      #161b22;
    --bg-bar-track:   #21262d;
    --bg-mathblock:   rgba(255,255,255,0.07);

    --text-body:      #e6edf3;
    --text-muted:     #8b949e;
    --text-table-h:   #8b949e;
    --text-link:      #58a6ff;

    --border-soft:    #30363d;
    --border-table:   #444;
    --border-row:     #21262d;
    --border-math:    #444;
  }
}

/* Dark when user has explicitly chosen dark (overrides system) */
:root[data-theme="dark"] {
  --bg-page:        #0d1117;
  --bg-header:      #161b22;
  --bg-bar-track:   #21262d;
  --bg-mathblock:   rgba(255,255,255,0.07);

  --text-body:      #e6edf3;
  --text-muted:     #8b949e;
  --text-table-h:   #8b949e;
  --text-link:      #58a6ff;

  --border-soft:    #30363d;
  --border-table:   #444;
  --border-row:     #21262d;
  --border-math:    #444;
}

/* ---------- Apply variables ---------- */

body { background-color: var(--bg-page); color: var(--text-body); }
.main-content { background: var(--bg-page); }
.main-content h1, .main-content h2, .main-content h3,
.main-content h4, .main-content h5, .main-content h6 { color: var(--text-body); }
.main-content p, .main-content li, .main-content blockquote { color: var(--text-body); }
:root[data-theme="dark"] .page-header,
:root:not([data-theme="light"]) .page-header { background: var(--bg-header); background-image: none; }
a { color: var(--text-link); }

/* ---------- Component styles ---------- */

.sport-charts { margin-top: 1.5em; }
.sport-entry { margin-bottom: 2.2em; padding-bottom: 2em; border-bottom: 1px solid var(--border-soft); }
.sport-entry:last-child { border-bottom: none; }
.sport-entry h3 { margin-bottom: 0.1em; }
.sport-meta { font-size: 0.85em; color: var(--text-muted); margin-top: 0; margin-bottom: 0.75em; font-style: italic; }

.stacked-bar-wrap { display: flex; flex-direction: column; gap: 8px; }
.stacked-bar { display: flex; width: 100%; height: 18px; border-radius: 3px; overflow: hidden; gap: 2px; background: var(--bg-bar-track); }
.seg { height: 100%; }
.seg-legend { display: flex; flex-wrap: wrap; gap: 6px 16px; }
.leg-item { font-size: 0.78em; color: var(--text-muted); display: flex; align-items: center; gap: 5px; }
.leg-dot { width: 9px; height: 9px; border-radius: 50%; display: inline-block; }

.sport-rationale {
  margin-top: 0.9em;
  font-size: 0.92em;
  line-height: 1.55;
  color: var(--text-body);
  opacity: 0.85;
}

.vector-table {
  width: 100%;
  border-collapse: collapse;
  font-size: 0.88em;
  margin-top: 1em;
  font-family: 'Courier New', monospace;
}
.vector-table th {
  text-align: left;
  border-bottom: 2px solid var(--border-table);
  padding: 0.4em 0.75em;
  color: var(--text-table-h);
  font-weight: bold;
}
.vector-table td {
  padding: 0.35em 0.75em;
  border-bottom: 1px solid var(--border-row);
  color: var(--text-body);
}
.vector-table tr:last-child td { border-bottom: none; }

/* Distance matrix — built on .vector-table with extras */
.distance-matrix-wrap {
  overflow-x: auto;
  margin: 1em 0;
}
.distance-matrix th {
  font-family: 'Courier New', monospace;
  white-space: nowrap;
}
.distance-matrix td {
  text-align: right;
  font-variant-numeric: tabular-nums;
}
.distance-matrix tbody th {
  text-align: left;
  border-bottom: 1px solid var(--border-row);
  background: transparent;
}
.distance-matrix .cell-near {
  background: rgba(45, 90, 61, 0.18);
  font-weight: bold;
}
.distance-matrix .cell-far {
  background: rgba(139, 69, 19, 0.18);
  font-weight: bold;
}

.math-block {
  font-family: 'Courier New', monospace;
  background: var(--bg-mathblock);
  border-left: 3px solid var(--border-math);
  padding: 0.5em 1em;
  margin: 0.75em 0;
  color: var(--text-body);
}

.footnotes {
  margin-top: 2em;
  padding-top: 1em;
  border-top: 1px solid var(--border-soft);
  font-size: 0.82em;
  color: var(--text-muted);
}

small { color: var(--text-muted); }

/* Component colours — fixed across themes */
.tactics,  .leg-dot.tactics  { background: #2d5a3d; }
.physical, .leg-dot.physical { background: #8b4513; }
.skill,    .leg-dot.skill    { background: #1a3a6b; }
.material, .leg-dot.material { background: #6b2d6b; }

/* ---------- Sidebar layout ---------- */

:root {
  --sidebar-width: 240px;
  --sidebar-breakpoint: 1100px;
}

/* On wide screens: push the main content right to make room for the sidebar */
@media (min-width: 1100px) {
  .page-header,
  .main-content,
  .site-footer {
    padding-left: calc(var(--sidebar-width) + 1.5rem) !important;
  }
}

/* Sidebar — fixed on the left, scrolls internally */
.sidebar {
  position: fixed;
  top: 0;
  left: 0;
  bottom: 0;
  width: var(--sidebar-width);
  background: var(--bg-page);
  border-right: 1px solid var(--border-soft);
  overflow-y: auto;
  z-index: 100;
  transition: transform 0.25s ease;
}
.sidebar-inner {
  padding: 1.5rem 1.25rem;
  display: flex;
  flex-direction: column;
  min-height: 100%;
}
.sidebar-brand {
  margin: 0 0 1.5em 0;
  font-size: 0.95em;
  font-weight: bold;
  color: var(--text-body);
  line-height: 1.3;
}

/* On narrow screens: hide off-canvas, reveal via toggle */
@media (max-width: 1099px) {
  .sidebar {
    transform: translateX(-100%);
    box-shadow: 0 0 24px rgba(0,0,0,0.18);
  }
  .sidebar.open {
    transform: translateX(0);
  }
}

/* Sidebar toggle button — only visible on narrow screens */
.sidebar-toggle {
  position: fixed;
  top: 0.75rem;
  left: 0.75rem;
  z-index: 110;
  width: 2.4em;
  height: 2.4em;
  background: var(--bg-page);
  border: 1px solid var(--border-soft);
  color: var(--text-body);
  border-radius: 4px;
  cursor: pointer;
  font-size: 1.1em;
  line-height: 1;
  padding: 0;
  display: none;
}
@media (max-width: 1099px) {
  .sidebar-toggle { display: block; }
}

/* Backdrop behind the sidebar on mobile, fades in/out */
.sidebar-backdrop {
  position: fixed;
  inset: 0;
  background: rgba(0,0,0,0.4);
  z-index: 99;
  opacity: 0;
  pointer-events: none;
  transition: opacity 0.25s ease;
}
.sidebar-backdrop.visible {
  opacity: 1;
  pointer-events: auto;
}

/* ---------- Table of contents ---------- */

.toc {
  margin: 0;
  padding: 0;
  background: transparent;
  border: none;
  flex: 1;
}
.toc-title {
  margin: 0 0 0.6em 0;
  font-size: 0.72em;
  text-transform: uppercase;
  letter-spacing: 0.1em;
  color: var(--text-muted);
  font-weight: bold;
}
.toc-list {
  margin: 0;
  padding: 0;
  list-style: none;
  font-size: 0.9em;
  line-height: 1.45;
}
.toc-list ol {
  margin: 0.25em 0 0.5em 0.9em;
  padding: 0;
  list-style: none;
  font-size: 0.92em;
}
.toc-list li {
  margin: 0.15em 0;
}
.toc-list a {
  display: block;
  padding: 0.25em 0.5em;
  color: var(--text-muted);
  text-decoration: none;
  border-left: 2px solid transparent;
  border-radius: 0 3px 3px 0;
  transition: color 0.15s ease, border-color 0.15s ease, background 0.15s ease;
}
.toc-list a:hover {
  color: var(--text-body);
  background: var(--bg-mathblock);
}
.toc-list a.active {
  color: var(--text-link);
  border-left-color: var(--text-link);
  background: var(--bg-mathblock);
  font-weight: 600;
}

/* ---------- Sidebar bottom controls ---------- */

.sidebar-controls {
  margin-top: 2em;
  padding-top: 1.25em;
  border-top: 1px solid var(--border-soft);
  display: flex;
  flex-direction: column;
  gap: 0.6em;
  align-items: flex-start;
  font-size: 0.85em;
}
.sidebar-controls .lang-link {
  color: var(--text-muted);
  text-decoration: none;
  border-bottom: 1px dotted var(--text-muted);
}
.sidebar-controls .lang-link:hover {
  color: var(--text-body);
  border-bottom-color: var(--text-body);
}
.sidebar-controls .theme-toggle {
  background: transparent;
  border: 1px solid var(--border-soft);
  color: var(--text-muted);
  padding: 0.3em 0.7em;
  border-radius: 4px;
  cursor: pointer;
  font-size: 0.95em;
  line-height: 1;
}
.sidebar-controls .theme-toggle:hover {
  color: var(--text-body);
  border-color: var(--text-body);
}

/* Smooth scrolling within the page */
html { scroll-behavior: smooth; }

/* Anchor offset so headings aren't hidden under fixed elements */
:target { scroll-margin-top: 1rem; }
</style>

<script>
(function () {
  var root = document.documentElement;
  var stored = null;
  try { stored = localStorage.getItem('theme'); } catch (e) {}
  if (stored === 'light' || stored === 'dark') {
    root.setAttribute('data-theme', stored);
  }

  function currentMode() {
    var attr = root.getAttribute('data-theme');
    if (attr === 'light' || attr === 'dark') return attr;
    return 'auto';
  }

  function labelFor(mode, lang) {
    var labels = {
      de: { auto: 'Theme: Auto', light: 'Theme: Hell', dark: 'Theme: Dunkel' },
      en: { auto: 'Theme: Auto', light: 'Theme: Light', dark: 'Theme: Dark' }
    };
    return labels[lang][mode];
  }

  function cycle(mode) {
    if (mode === 'auto')  return 'light';
    if (mode === 'light') return 'dark';
    return 'auto';
  }

  document.addEventListener('DOMContentLoaded', function () {
    // --- Theme toggle ---
    var btn = document.getElementById('theme-toggle');
    if (btn) {
      var lang = (location.pathname.indexOf('/en') === 0 || location.pathname.indexOf('/en/') !== -1) ? 'en' : 'de';

      function refresh() { btn.textContent = labelFor(currentMode(), lang); }
      refresh();

      btn.addEventListener('click', function () {
        var next = cycle(currentMode());
        if (next === 'auto') {
          root.removeAttribute('data-theme');
          try { localStorage.removeItem('theme'); } catch (e) {}
        } else {
          root.setAttribute('data-theme', next);
          try { localStorage.setItem('theme', next); } catch (e) {}
        }
        refresh();
      });
    }

    // --- Sidebar toggle (mobile) ---
    var sidebar  = document.getElementById('sidebar');
    var toggle   = document.getElementById('sidebar-toggle');
    var backdrop = document.getElementById('sidebar-backdrop');

    function openSidebar() {
      sidebar.classList.add('open');
      backdrop.classList.add('visible');
      toggle.setAttribute('aria-expanded', 'true');
    }
    function closeSidebar() {
      sidebar.classList.remove('open');
      backdrop.classList.remove('visible');
      toggle.setAttribute('aria-expanded', 'false');
    }
    if (toggle && sidebar && backdrop) {
      toggle.addEventListener('click', function () {
        if (sidebar.classList.contains('open')) closeSidebar();
        else openSidebar();
      });
      backdrop.addEventListener('click', closeSidebar);
      // Close when a TOC link is clicked on mobile
      sidebar.querySelectorAll('.toc-list a').forEach(function (a) {
        a.addEventListener('click', function () {
          if (window.matchMedia('(max-width: 1099px)').matches) closeSidebar();
        });
      });
      // Close on Escape
      document.addEventListener('keydown', function (e) {
        if (e.key === 'Escape' && sidebar.classList.contains('open')) closeSidebar();
      });
    }

    // --- Scrollspy: highlight the TOC link of the currently visible section ---
    var tocLinks = Array.prototype.slice.call(document.querySelectorAll('.toc-list a[href^="#"]'));
    if (tocLinks.length && 'IntersectionObserver' in window) {
      var linkById = {};
      var sections = [];
      tocLinks.forEach(function (link) {
        var id = link.getAttribute('href').slice(1);
        var section = document.getElementById(id);
        if (section) {
          linkById[id] = link;
          sections.push(section);
        }
      });

      // Track which sections are currently above-the-fold-visible.
      var visibleIds = new Set();
      var observer = new IntersectionObserver(function (entries) {
        entries.forEach(function (entry) {
          if (entry.isIntersecting) visibleIds.add(entry.target.id);
          else visibleIds.delete(entry.target.id);
        });
        // Activate the topmost visible section, or fall back to the last passed one.
        var activeId = null;
        for (var i = 0; i < sections.length; i++) {
          if (visibleIds.has(sections[i].id)) { activeId = sections[i].id; break; }
        }
        if (!activeId) {
          // No section visible — pick the last one above the viewport
          var scrollY = window.scrollY;
          for (var j = sections.length - 1; j >= 0; j--) {
            if (sections[j].getBoundingClientRect().top + scrollY <= scrollY + 80) {
              activeId = sections[j].id;
              break;
            }
          }
        }
        tocLinks.forEach(function (l) { l.classList.remove('active'); });
        if (activeId && linkById[activeId]) linkById[activeId].classList.add('active');
      }, {
        rootMargin: '-10% 0px -75% 0px',
        threshold: 0
      });

      sections.forEach(function (s) { observer.observe(s); });
    }
  });
})();
</script>
