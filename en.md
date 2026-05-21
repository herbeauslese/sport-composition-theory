---
layout: default
permalink: /en/
lang: en
title: Sport Composition Theory
description: A framework for decomposing any sport into its fundamental components.
---

# Sport Composition Theory

*A framework for understanding what any sport is actually made of.*

<div class="top-controls">
  <a class="lang-link" href="{{ '/' | relative_url }}" hreflang="de" lang="de">Deutsch</a>
  <span class="sep">·</span>
  <button id="theme-toggle" class="theme-toggle" type="button" aria-label="Toggle theme">Theme: Auto</button>
</div>

---

## Background

I have always been a fan of sport — not one sport, but many. Football, cycling, chess, athletics, motorsport. The full, chaotic spectrum. And for a long time, I found myself asking a question that seemed simple but turned out to be surprisingly difficult: how do you actually compare them?

Not in terms of which is more exciting, or more demanding, or more prestigious. But structurally. What does it take to be good at something? What kind of demands — in the broadest sense — does each sport place on the athlete?

Consider a sprinter and a Formula 1 driver. Both are elite athletes competing at the absolute limit of human performance. But the nature of their excellence is radically different. The sprinter has refined their body over years to produce a single explosive output lasting under ten seconds. The Formula 1 driver must process a torrent of sensory information at 300 km/h, making tactical decisions in fractions of a second — decisions that have to hold up across an entire race strategy built over dozens of laps. And then there is the chess player: no physical output to speak of, no machine, no course — just pure cognitive warfare conducted across a board, where a single positional miscalculation made on move twelve can silently unravel everything by move forty.

Three athletes. Three completely different skill sets. And yet all three are competing, winning, and losing based on something that can be measured and compared.

That question — what exactly is being measured — led to this theory.

> *"What does it take to win? The answer is always the same components. Just in different proportions."*

---

## The Theory

### Assumptions

Before the theory can be applied, two foundational assumptions must be accepted. They cannot be proven — they are the starting point, not the conclusion. A formal definition and one direct consequence follow from them.

**Assumption 0 — Scope.**
Every sport is evaluated in the form in which it is professionally and competitively practiced at the highest level. Recreational or informal variants are excluded — not because they are less interesting, but because the competitive form is the most clearly defined and most consistently comparable across athletes.

Road cycling, for instance, is a team sport at the professional level. A domestique sacrifices their own result to protect a team leader; tactics operate across an entire roster, not just a single rider. Evaluating road cycling as a solo physical effort would produce a fundamentally different — and less accurate — vector.

Where a sport exists in meaningfully distinct competitive forms, each version must be named and evaluated separately. Beach volleyball and indoor volleyball share a name but differ structurally. The 100m and 400m sprint reward different physical profiles. Treating them as interchangeable would undermine the precision the model depends on.

**Assumption 1 — Decomposability.**
Any competitive sport can be fully and meaningfully described by four components: Tactics, Physical, Skill, and Material. Nothing essential falls outside these four categories. This is the core claim of the theory, and the only one that requires genuine agreement before proceeding.

This assumption is not self-evident. One could argue that certain sports resist reduction — that the psychological dimension of competition, or the intangible quality of teamwork, cannot be captured by four numbers. We argue that these dimensions are already contained within the components as defined. But we acknowledge the assumption for what it is.

**Definition — The Composition Vector.**
Given Assumption 1, any sport *S* can be formally represented as a tuple:

<div class="math-block">S = (T, P, Sk, M)</div>

where *T* = Tactics, *P* = Physical, *Sk* = Skill, *M* = Material, and:

<div class="math-block">T + P + Sk + M = 1</div>

All values are real numbers in the interval [0, 1]. For most sports, M = 0, reducing the representation to a three-component vector.<sup><a href="#fn1" id="fn1ref">1</a></sup>

**Corollary 1 — Comparability.**
From Assumption 1 and the Definition it follows directly that any two sports can be meaningfully compared. Because every sport is expressed in the same four-dimensional space, the structural similarity or distance between any two sports is well-defined. A sport dominated by Physical and one dominated by Tactics are not just qualitatively different — they are measurably far apart.

**A note on theory and application.**
Everything above is exact. The Composition Vector is defined over real numbers, and any assignment satisfying the constraints is formally valid. Assigning concrete weights to a real sport is a different matter — it is a judgement, not a measurement. That step is treated separately, under Methodology.

---

### Tactics

Decision-making, planning, reading opponents, and adapting strategy in real time. Tactics covers the *content* of decisions: the choice of formation, the read of a situation, the decision to attack or to wait. It is the component most invisible to the casual observer, and most decisive to the serious one.

Tactics is concerned with *what* is decided, not with the cognitive capacity to keep deciding over time. The latter belongs to Physical, and the distinction matters: an athlete who makes brilliant decisions for ten minutes and then collapses mentally has a Tactics problem only if the decisions themselves were poor. If the decisions were correct but ran out, the limitation is one of capacity, not of judgement.

### Physical

The demands placed on the human body: strength, endurance, speed, agility — and their mental equivalents. Sustained concentration, psychological resilience under pressure, and the capacity to perform cognitively over long periods all count here too. The mind is part of the body, and in sport, it is trained accordingly.

This is the cognitive *capacity* dimension that complements Tactics. A five-hour chess game places enormous demands on Physical in this sense, even though no muscle is meaningfully strained. The quality of the moves played is Tactics; the ability to keep finding good moves on move sixty is Physical.

### Skill

Learned human technique: motor control, precision, coordination, and execution. Skill is distinct from Physical in that it concerns the *quality* of movement, not the *capacity* for it. A sprinter's physical output is their top speed. Their skill is the technique that gets them there efficiently.

### Material

The role of external equipment in producing competitive outcomes. This component requires special attention.

Almost every sport involves some equipment — shoes, balls, rackets. Material does **not** apply to all of them. It applies only when the *quality or specification* of the equipment has a meaningful, direct effect on competitive outcome — when a better-equipped athlete has a structural advantage over an equivalently skilled one with inferior gear.

A tennis racket does not qualify. A Formula 1 car does. A bobsled does. A high-end road cycling setup sits somewhere in between, and is treated accordingly.

One further note: facilities and training environments — altitude camps, specialist tracks, elite coaching infrastructure — could in principle be counted under Material. At the highest levels of competition, however, these tend to converge. The top athletes in most sports have broadly comparable access to top-tier facilities, which means the differentiating effect is limited. For this reason, training infrastructure is excluded from the model unless it creates a *persistent, structural* competitive asymmetry.

---

## Caveats & Considerations

The Composition Vector is a deliberate simplification. That is a feature, not a flaw — but it comes with consequences worth stating explicitly. This section collects the known limitations of the model. It will grow as the theory is stress-tested against more sports.

### The Team Sport Problem

In individual sports, the Composition Vector describes a single athlete. In team sports, it does not.

Consider Tactics in football. The value assigned reflects how much tactical quality determines the outcome of a match. But tactical quality in a team sport operates on two distinct levels: the **collective level** (team shape, pressing structure, set piece design) and the **individual level** (a player's positional decisions within that system). These are not the same thing. A player with exceptional individual tactical intelligence can still lose comprehensively if their team's collective structure is poor.

This means that in team sports, the Composition Vector describes the sport at the team level — which is the level at which outcomes are actually decided. The individual contributions of athletes are real, but they are inputs into a collective system, not direct outputs.

A practical consequence: Tactics tends to carry more weight in team sports than a naive reading might suggest, because collective tactical organisation can compensate for — or completely negate — individual superiority in other components. Eleven individually superior athletes without a system regularly lose to eleven organised ones. This is not a flaw in the model; it is an accurate reflection of how team sports work.

### Material Is Not Symmetric Between Athletes

Material weights describe a sport as a whole, not the matchup between two specific competitors. This distinction is easy to miss and worth stating explicitly.

Consider Formula 1, where Material accounts for roughly half of the vector. That figure reflects how much equipment quality shapes outcomes *across the grid*: a backmarker team and a frontrunner team are separated primarily by their cars, not by the talent of their drivers. But within a single team, two drivers race identical machinery. Between them, the Material component effectively collapses to zero, and the contest is decided by Tactics, Physical, and Skill alone.

The same logic applies wherever equipment matters. A high-end road bike is decisive when comparing a Tour de France rider to an amateur, but irrelevant when comparing two World Tour professionals. Material, in other words, is a property of the competition as a whole — not a constant carried by each athlete. The Composition Vector captures the structure of the sport; it does not by itself describe any particular duel within it.

---

## Methodology

For each sport, four guiding questions are applied — one per component:

**Tactics:** How much does a superior strategic approach — independent of physical ability — determine the outcome of a contest?

**Physical:** How much does a measurable difference in athletic or mental conditioning affect the result, holding all else equal?

**Skill:** How much is the outcome determined by the precision and quality of learned human technique?

**Material:** How much would a significant disadvantage in equipment — independent of the athlete — change the result?

The resulting values are curated estimates, reported on a 5% grid. False precision (writing 23.7% when one means *roughly a quarter*) would suggest a measurement procedure that does not exist. The estimates are informed by observation, reasoning, and the kind of arguments that tend to happen when someone who watches too much sport has too much time to think. They are offered in good faith, and revised when better arguments appear.

---

## Examples

The following breakdowns represent current estimates. Each sport is shown as a single bar divided into its components.

<div class="sport-charts">

<div class="sport-entry">
<h3>Football (Soccer)</h3>
<p class="sport-meta">11v11 · 90 minutes</p>
<div class="stacked-bar-wrap">
  <div class="stacked-bar">
    <div class="seg tactics"   style="width:45%" title="Tactics: 45%"></div>
    <div class="seg physical"  style="width:25%" title="Physical: 25%"></div>
    <div class="seg skill"     style="width:30%" title="Skill: 30%"></div>
  </div>
  <div class="seg-legend">
    <span class="leg-item"><span class="leg-dot tactics"></span>Tactics 45%</span>
    <span class="leg-item"><span class="leg-dot physical"></span>Physical 25%</span>
    <span class="leg-item"><span class="leg-dot skill"></span>Skill 30%</span>
  </div>
</div>
</div>

<div class="sport-entry">
<h3>100m Sprint</h3>
<p class="sport-meta">Pure athletic event</p>
<div class="stacked-bar-wrap">
  <div class="stacked-bar">
    <div class="seg tactics"  style="width:5%"  title="Tactics: 5%"></div>
    <div class="seg physical" style="width:65%" title="Physical: 65%"></div>
    <div class="seg skill"    style="width:30%" title="Skill: 30%"></div>
  </div>
  <div class="seg-legend">
    <span class="leg-item"><span class="leg-dot tactics"></span>Tactics 5%</span>
    <span class="leg-item"><span class="leg-dot physical"></span>Physical 65%</span>
    <span class="leg-item"><span class="leg-dot skill"></span>Skill 30%</span>
  </div>
</div>
</div>

<div class="sport-entry">
<h3>Basketball</h3>
<p class="sport-meta">5v5 · high tempo</p>
<div class="stacked-bar-wrap">
  <div class="stacked-bar">
    <div class="seg tactics"  style="width:35%" title="Tactics: 35%"></div>
    <div class="seg physical" style="width:30%" title="Physical: 30%"></div>
    <div class="seg skill"    style="width:35%" title="Skill: 35%"></div>
  </div>
  <div class="seg-legend">
    <span class="leg-item"><span class="leg-dot tactics"></span>Tactics 35%</span>
    <span class="leg-item"><span class="leg-dot physical"></span>Physical 30%</span>
    <span class="leg-item"><span class="leg-dot skill"></span>Skill 35%</span>
  </div>
</div>
</div>

<div class="sport-entry">
<h3>Chess</h3>
<p class="sport-meta">Included as a boundary case</p>
<div class="stacked-bar-wrap">
  <div class="stacked-bar">
    <div class="seg tactics"  style="width:80%" title="Tactics: 80%"></div>
    <div class="seg physical" style="width:10%" title="Physical: 10%"></div>
    <div class="seg skill"    style="width:10%" title="Skill: 10%"></div>
  </div>
  <div class="seg-legend">
    <span class="leg-item"><span class="leg-dot tactics"></span>Tactics 80%</span>
    <span class="leg-item"><span class="leg-dot physical"></span>Physical 10%</span>
    <span class="leg-item"><span class="leg-dot skill"></span>Skill 10%</span>
  </div>
</div>
</div>

<div class="sport-entry">
<h3>Archery</h3>
<p class="sport-meta">Precision individual sport</p>
<div class="stacked-bar-wrap">
  <div class="stacked-bar">
    <div class="seg tactics"  style="width:10%" title="Tactics: 10%"></div>
    <div class="seg physical" style="width:15%" title="Physical: 15%"></div>
    <div class="seg skill"    style="width:65%" title="Skill: 65%"></div>
    <div class="seg material" style="width:10%" title="Material: 10%"></div>
  </div>
  <div class="seg-legend">
    <span class="leg-item"><span class="leg-dot tactics"></span>Tactics 10%</span>
    <span class="leg-item"><span class="leg-dot physical"></span>Physical 15%</span>
    <span class="leg-item"><span class="leg-dot skill"></span>Skill 65%</span>
    <span class="leg-item"><span class="leg-dot material"></span>Material 10%</span>
  </div>
</div>
</div>

<div class="sport-entry">
<h3>Road Cycling</h3>
<p class="sport-meta">Grand Tour stage race</p>
<div class="stacked-bar-wrap">
  <div class="stacked-bar">
    <div class="seg tactics"  style="width:30%" title="Tactics: 30%"></div>
    <div class="seg physical" style="width:40%" title="Physical: 40%"></div>
    <div class="seg skill"    style="width:15%" title="Skill: 15%"></div>
    <div class="seg material" style="width:15%" title="Material: 15%"></div>
  </div>
  <div class="seg-legend">
    <span class="leg-item"><span class="leg-dot tactics"></span>Tactics 30%</span>
    <span class="leg-item"><span class="leg-dot physical"></span>Physical 40%</span>
    <span class="leg-item"><span class="leg-dot skill"></span>Skill 15%</span>
    <span class="leg-item"><span class="leg-dot material"></span>Material 15%</span>
  </div>
</div>
</div>

<div class="sport-entry">
<h3>Formula 1</h3>
<p class="sport-meta">Includes driver and constructor</p>
<div class="stacked-bar-wrap">
  <div class="stacked-bar">
    <div class="seg tactics"  style="width:20%" title="Tactics: 20%"></div>
    <div class="seg physical" style="width:10%" title="Physical: 10%"></div>
    <div class="seg skill"    style="width:15%" title="Skill: 15%"></div>
    <div class="seg material" style="width:55%" title="Material: 55%"></div>
  </div>
  <div class="seg-legend">
    <span class="leg-item"><span class="leg-dot tactics"></span>Tactics 20%</span>
    <span class="leg-item"><span class="leg-dot physical"></span>Physical 10%</span>
    <span class="leg-item"><span class="leg-dot skill"></span>Skill 15%</span>
    <span class="leg-item"><span class="leg-dot material"></span>Material 55%</span>
  </div>
</div>
</div>

</div>

<small>* Percentages are curated estimates derived from structured qualitative analysis. They reflect the author's considered opinion and should be treated as such — which is to say, seriously, but not too seriously.</small>

---

<div class="footnotes">
<p id="fn1"><sup>1</sup> For the precise conditions under which Material takes a non-zero value, see the Material section above. <a href="#fn1ref">↩</a></p>
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
