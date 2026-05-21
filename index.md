---
layout: default
lang: de
title: Sport Composition Theory
description: Ein Framework zur Zerlegung jeder Sportart in ihre fundamentalen Komponenten.
---

# Sport Composition Theory

*Ein Framework dafür, woraus eine Sportart eigentlich besteht.*

<div class="top-controls">
  <a class="lang-link" href="{{ '/en/' | relative_url }}" hreflang="en" lang="en">English</a>
  <span class="sep">·</span>
  <button id="theme-toggle" class="theme-toggle" type="button" aria-label="Theme umschalten">Theme: Auto</button>
</div>

---

## Hintergrund

Ich bin schon immer Sportfan gewesen — nicht von einer Sportart, sondern von vielen. Fußball, Radsport, Schach, Leichtathletik, Motorsport. Das ganze, chaotische Spektrum. Und lange Zeit habe ich mir eine Frage gestellt, die einfach klang und sich als überraschend schwer herausstellte: wie vergleicht man sie eigentlich?

Nicht in der Frage, welche spannender ist, welche fordernder, welche prestigeträchtiger. Sondern strukturell. Was braucht es, um in etwas gut zu sein? Welche Art von Anforderungen — im weitesten Sinne — stellt eine Sportart an den Athleten?

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

### Taktik

Entscheidungsfindung, Planung, das Lesen von Gegnern und das Anpassen der Strategie in Echtzeit. Taktik umfasst den *Inhalt* der Entscheidungen: die Wahl der Formation, das Lesen einer Situation, die Entscheidung anzugreifen oder zu warten. Es ist die Komponente, die für den Gelegenheitszuschauer am unsichtbarsten und für den ernsthaften Beobachter am entscheidendsten ist.

Taktik betrifft *was* entschieden wird, nicht die kognitive Kapazität, über die Zeit weiter zu entscheiden. Letzteres gehört zur Physis, und die Unterscheidung ist wichtig: ein Athlet, der zehn Minuten lang brillante Entscheidungen trifft und dann mental zusammenbricht, hat nur dann ein Taktik-Problem, wenn die Entscheidungen selbst schlecht waren. Wenn die Entscheidungen korrekt waren, aber irgendwann ausgingen, ist das Problem Kapazität, nicht Urteilsvermögen.

### Physis

Die Anforderungen an den menschlichen Körper: Kraft, Ausdauer, Schnelligkeit, Beweglichkeit — und ihre mentalen Entsprechungen. Anhaltende Konzentration, psychische Belastbarkeit unter Druck und die Fähigkeit, über lange Zeiträume kognitiv leistungsfähig zu bleiben, zählen ebenfalls hierher. Der Geist ist Teil des Körpers, und im Sport wird er entsprechend trainiert.

Das ist die kognitive *Kapazitäts*-Dimension, die Taktik ergänzt. Eine fünfstündige Schachpartie stellt enorme Anforderungen an die Physis in diesem Sinn, auch wenn kein Muskel ernsthaft beansprucht wird. Die Qualität der gespielten Züge ist Taktik; die Fähigkeit, in Zug sechzig immer noch gute Züge zu finden, ist Physis.

### Skill

Erlernte menschliche Technik: motorische Kontrolle, Präzision, Koordination und Ausführung. Skill unterscheidet sich von Physis dadurch, dass es um die *Qualität* der Bewegung geht, nicht um die *Kapazität* zu ihr. Der physische Output eines Sprinters ist seine Höchstgeschwindigkeit. Sein Skill ist die Technik, die ihn effizient dorthin bringt.

### Material

Die Rolle externer Ausrüstung beim Zustandekommen kompetitiver Ergebnisse. Diese Komponente erfordert besondere Aufmerksamkeit.

Fast jede Sportart involviert irgendeine Form von Ausrüstung — Schuhe, Bälle, Schläger. Material gilt **nicht** für alle. Es gilt nur dann, wenn die *Qualität oder Spezifikation* der Ausrüstung einen bedeutsamen, direkten Einfluss auf das Ergebnis hat — wenn ein besser ausgerüsteter Athlet einen strukturellen Vorteil gegenüber einem gleich starken mit schlechterer Ausrüstung hat.

Ein Tennisschläger qualifiziert sich nicht. Ein Formel-1-Auto schon. Ein Bob auch. Ein hochwertiges Straßenrad-Setup liegt irgendwo dazwischen und wird entsprechend behandelt.

Noch eine Anmerkung: Trainingsinfrastruktur — Höhencamps, Spezialbahnen, Spitzentrainerstäbe — könnte prinzipiell unter Material fallen. Auf höchstem kompetitiven Niveau konvergieren diese Faktoren jedoch in der Regel. Die Top-Athleten in den meisten Sportarten haben weitgehend vergleichbaren Zugang zu erstklassigen Einrichtungen, was den differenzierenden Effekt begrenzt. Aus diesem Grund ist Trainingsinfrastruktur aus dem Modell ausgeschlossen, sofern sie nicht eine *persistente, strukturelle* Wettbewerbsasymmetrie erzeugt.

---

## Vorbehalte & Anmerkungen

Der Composition Vector ist eine bewusste Vereinfachung. Das ist ein Feature, kein Mangel — aber es hat Konsequenzen, die man explizit benennen sollte. Dieser Abschnitt sammelt die bekannten Grenzen des Modells. Er wird wachsen, sobald die Theorie an weiteren Sportarten getestet wird.

### Das Mannschaftssport-Problem

In Einzelsportarten beschreibt der Composition Vector einen einzelnen Athleten. In Mannschaftssportarten nicht.

Man nehme Taktik im Fußball. Der zugewiesene Wert spiegelt wider, wie stark taktische Qualität das Ergebnis eines Spiels bestimmt. Aber taktische Qualität in einem Mannschaftssport operiert auf zwei unterschiedlichen Ebenen: der **kollektiven Ebene** (Mannschaftsform, Pressing-Struktur, Standardsituationen) und der **individuellen Ebene** (die Positionsentscheidungen eines Spielers innerhalb dieses Systems). Das ist nicht dasselbe. Ein Spieler mit außergewöhnlicher individueller taktischer Intelligenz kann trotzdem deutlich verlieren, wenn die kollektive Struktur seiner Mannschaft schlecht ist.

Das bedeutet, dass der Composition Vector in Mannschaftssportarten die Sportart auf Teamebene beschreibt — also auf der Ebene, auf der Ergebnisse tatsächlich entschieden werden. Die individuellen Beiträge der Athleten sind real, aber sie sind Eingaben in ein kollektives System, nicht direkte Ausgaben.

Eine praktische Folge: Taktik hat in Mannschaftssportarten tendenziell ein größeres Gewicht, als eine naive Lesart vermuten lässt, weil kollektive taktische Organisation individuelle Überlegenheit in anderen Komponenten kompensieren — oder vollständig neutralisieren — kann. Elf individuell überlegene Athleten ohne System verlieren regelmäßig gegen elf organisierte. Das ist kein Mangel im Modell; es ist eine korrekte Abbildung dessen, wie Mannschaftssport funktioniert.

### Material ist nicht symmetrisch zwischen Athleten

Material-Gewichte beschreiben eine Sportart als Ganzes, nicht das Duell zwischen zwei bestimmten Konkurrenten. Diese Unterscheidung ist leicht zu übersehen und sollte explizit benannt werden.

Man nehme Formel 1, wo Material ungefähr die Hälfte des Vektors ausmacht. Diese Zahl spiegelt wider, wie stark die Qualität der Ausrüstung Ergebnisse *im gesamten Feld* prägt: Ein Hinterbänkler-Team und ein Spitzenteam sind in erster Linie durch ihre Autos getrennt, nicht durch das Talent ihrer Fahrer. Innerhalb eines einzelnen Teams fahren zwei Fahrer aber identisches Material. Zwischen ihnen kollabiert die Material-Komponente effektiv auf null, und der Wettkampf wird allein durch Taktik, Physis und Skill entschieden.

Dieselbe Logik gilt überall dort, wo Ausrüstung relevant ist. Ein Top-Rennrad ist entscheidend, wenn man einen Tour-de-France-Fahrer mit einem Amateur vergleicht, aber irrelevant, wenn man zwei World-Tour-Profis vergleicht. Material ist, anders gesagt, eine Eigenschaft des Wettbewerbs als Ganzes — nicht eine Konstante, die jeder Athlet mit sich trägt. Der Composition Vector erfasst die Struktur der Sportart; er beschreibt nicht von sich aus ein bestimmtes Duell innerhalb dieser Sportart.

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

Die folgenden Aufschlüsselungen sind aktuelle Schätzungen. Jede Sportart wird als ein einzelner Balken dargestellt, der in seine Komponenten unterteilt ist.

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
</div>

<div class="sport-entry">
<h3>Basketball</h3>
<p class="sport-meta">5 gegen 5 · hohes Tempo</p>
<div class="stacked-bar-wrap">
  <div class="stacked-bar">
    <div class="seg tactics"  style="width:35%" title="Taktik: 35%"></div>
    <div class="seg physical" style="width:30%" title="Physis: 30%"></div>
    <div class="seg skill"    style="width:35%" title="Skill: 35%"></div>
  </div>
  <div class="seg-legend">
    <span class="leg-item"><span class="leg-dot tactics"></span>Taktik 35%</span>
    <span class="leg-item"><span class="leg-dot physical"></span>Physis 30%</span>
    <span class="leg-item"><span class="leg-dot skill"></span>Skill 35%</span>
  </div>
</div>
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
</div>

<div class="sport-entry">
<h3>Bogenschießen</h3>
<p class="sport-meta">Präzisions-Einzelsport</p>
<div class="stacked-bar-wrap">
  <div class="stacked-bar">
    <div class="seg tactics"  style="width:10%" title="Taktik: 10%"></div>
    <div class="seg physical" style="width:15%" title="Physis: 15%"></div>
    <div class="seg skill"    style="width:65%" title="Skill: 65%"></div>
    <div class="seg material" style="width:10%" title="Material: 10%"></div>
  </div>
  <div class="seg-legend">
    <span class="leg-item"><span class="leg-dot tactics"></span>Taktik 10%</span>
    <span class="leg-item"><span class="leg-dot physical"></span>Physis 15%</span>
    <span class="leg-item"><span class="leg-dot skill"></span>Skill 65%</span>
    <span class="leg-item"><span class="leg-dot material"></span>Material 10%</span>
  </div>
</div>
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
</div>

</div>

<small>* Die Prozentsätze sind kuratierte Schätzungen aus strukturierter qualitativer Analyse. Sie spiegeln die wohlüberlegte Meinung des Autors wider und sollten entsprechend behandelt werden — also ernst, aber nicht zu ernst.</small>

---

## Vergleich

Mit den Beispielvektoren in der Hand lässt sich die ursprüngliche Frage stellen, von der diese Theorie ausgegangen ist: *Wie vergleicht man Sportarten?* Korollar 1 hat behauptet, dass jeder Vergleich wohldefiniert ist. Dieser Abschnitt zeigt, was das konkret bedeutet.

Die folgenden Beobachtungen sind in zwei Teile gegliedert. Der erste Teil ist strikte Konsequenz der Definition — gegeben die Werte aus dem Examples-Abschnitt fallen die Distanzen automatisch heraus. Der zweite Teil (folgt später) bewegt sich auf spekulativerem Boden.

### Strukturelle Distanz

Da jede Sportart als Vektor im selben vierdimensionalen Raum ausgedrückt wird, lässt sich die strukturelle Distanz zwischen je zwei Sportarten als Euklidischer Abstand berechnen:

<div class="math-block">d(S₁, S₂) = √[(T₁−T₂)² + (P₁−P₂)² + (Sk₁−Sk₂)² + (M₁−M₂)²]</div>

Der Wertebereich ist beschränkt. Zwei identische Vektoren haben Distanz 0; das theoretische Maximum liegt bei √2 ≈ 1.414 und wird nur erreicht, wenn zwei Sportarten jeweils vollständig in einer einzigen, unterschiedlichen Komponente liegen — also etwa (1, 0, 0, 0) gegen (0, 1, 0, 0). Reale Sportarten erreichen diesen Wert nie. In der vorliegenden Stichprobe reicht die größte beobachtete Distanz an etwa zwei Drittel dieses Maximums heran.

Die folgende Tabelle zeigt die paarweisen Distanzen für die sieben Beispielsportarten:

<div class="distance-matrix-wrap">
<table class="vector-table distance-matrix">
<thead>
<tr><th></th><th>Fußball</th><th>100m</th><th>Basket.</th><th>Schach</th><th>Bogen.</th><th>Rad</th><th>F1</th></tr>
</thead>
<tbody>
<tr><th>Fußball</th>         <td>—</td>     <td>0.566</td><td class="cell-near">0.122</td><td>0.430</td><td>0.515</td><td>0.300</td><td>0.640</td></tr>
<tr><th>100m Sprint</th>     <td>0.566</td><td>—</td>     <td>0.464</td><td class="cell-far">0.951</td><td>0.620</td><td>0.412</td><td>0.806</td></tr>
<tr><th>Basketball</th>      <td class="cell-near">0.122</td><td>0.464</td><td>—</td>     <td>0.552</td><td>0.430</td><td>0.274</td><td>0.636</td></tr>
<tr><th>Schach</th>          <td>0.430</td><td class="cell-far">0.951</td><td>0.552</td><td>—</td>     <td>0.897</td><td>0.604</td><td>0.815</td></tr>
<tr><th>Bogenschießen</th>   <td>0.515</td><td>0.620</td><td>0.430</td><td>0.897</td><td>—</td>     <td>0.596</td><td>0.682</td></tr>
<tr><th>Straßenradsport</th> <td>0.300</td><td>0.412</td><td>0.274</td><td>0.604</td><td>0.596</td><td>—</td>     <td>0.510</td></tr>
<tr><th>Formel 1</th>        <td>0.640</td><td>0.806</td><td>0.636</td><td>0.815</td><td>0.682</td><td>0.510</td><td>—</td></tr>
</tbody>
</table>
</div>

Aus der Matrix lassen sich drei Beobachtungen ableiten, die für sich allein bereits aufschlussreich sind.

**Fußball und Basketball sind strukturelle Zwillinge.** Ihre Distanz von 0.122 ist mit Abstand die kleinste in der Stichprobe — und liegt deutlich näher beieinander als die nächstkleinere Paarung (Basketball/Straßenradsport, 0.274). Trotz oberflächlich sehr unterschiedlicher Erscheinung — 11 gegen 11 auf großem Feld vs. 5 gegen 5 auf engem Court — sind beide Sportarten in ihrer fundamentalen Anforderungsstruktur fast identisch: ausgewogene Verteilung über Taktik, Physis und Skill, kein Material. Was zwischen ihnen unterscheidet, ist nicht *was* sie verlangen, sondern *wie* sie es einsetzen.

**Schach ist das strukturelle Extrem.** Es taucht in vier der sieben Sportarten als fernster Nachbar auf — gegen Sprint, Bogenschießen, Straßenradsport und Formel 1. Die Distanz zwischen Schach und 100m Sprint (0.951) ist die größte in der gesamten Tabelle und liegt nahe am theoretischen Maximum. Das ist erwartbar: Schach ist die einzige Sportart in der Stichprobe, in der eine einzelne Komponente dominant ist (Taktik mit 80%). Diese Konzentration macht sie zu jedem anderen Vektor extrem unähnlich, mit Ausnahme von Sportarten, in denen Taktik *ebenfalls* schwer wiegt — was unter den Beispielen nur auf Fußball halbwegs zutrifft (Distanz 0.430, der nächste Nachbar von Schach).

**Basketball ist das strukturelle Zentrum.** Mit einer durchschnittlichen Distanz von 0.413 zu allen anderen Sportarten liegt Basketball im Mittel näher an der Gesamtstichprobe als jede andere Disziplin. Fußball folgt knapp dahinter (0.429), Straßenradsport an dritter Stelle (0.449). Am anderen Ende der Skala stehen Schach (0.708) und Formel 1 (0.682) als die strukturell isoliertesten Sportarten. Was diese Beobachtung suggeriert, ist nicht, dass Basketball *typisch* sei — sondern dass eine ausgewogene Verteilung über alle drei menschlichen Komponenten ein gewisses strukturelles Schwerezentrum darstellt, von dem aus Spezialisierung (Schach in Richtung Taktik, Sprint in Richtung Physis, Formel 1 in Richtung Material) jeweils messbare Abweichung bedeutet.

Diese drei Beobachtungen folgen unmittelbar aus den Vektoren — sie sind nicht hinzu-interpretiert, sondern in den Zahlen bereits enthalten.

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

/* ---------- Top controls (language + theme) ---------- */

.top-controls {
  display: flex;
  justify-content: flex-end;
  align-items: center;
  gap: 0.75em;
  margin: -0.5em 0 1.5em 0;
  font-size: 0.85em;
}
.top-controls .lang-link {
  color: var(--text-muted);
  text-decoration: none;
  border-bottom: 1px dotted var(--text-muted);
}
.top-controls .lang-link:hover { color: var(--text-body); border-bottom-color: var(--text-body); }
.top-controls .theme-toggle {
  background: transparent;
  border: 1px solid var(--border-soft);
  color: var(--text-muted);
  padding: 0.25em 0.7em;
  border-radius: 4px;
  cursor: pointer;
  font-size: 0.95em;
  line-height: 1;
}
.top-controls .theme-toggle:hover { color: var(--text-body); border-color: var(--text-body); }
.top-controls .sep { color: var(--text-muted); opacity: 0.5; }
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
    var btn = document.getElementById('theme-toggle');
    if (!btn) return;
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
  });
})();
</script>
