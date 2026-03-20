<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>History of Atomic Theory — Interactive Timeline</title>
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Arial, sans-serif;
      background: #f5f4f0;
      color: #1a1a18;
      min-height: 100vh;
      padding: 2rem 1rem 3rem;
    }

    .page-header {
      max-width: 780px;
      margin: 0 auto 1.8rem;
      text-align: center;
    }

    .page-header h1 {
      font-size: 1.75rem;
      font-weight: 700;
      color: #1a1a18;
      margin-bottom: 0.35rem;
      letter-spacing: -0.01em;
    }

    .page-header p {
      font-size: 0.9rem;
      color: #5f5e5a;
      line-height: 1.5;
    }

    .container { max-width: 780px; margin: 0 auto; }

    /* Legend */
    .legend {
      display: flex;
      gap: 0.9rem;
      flex-wrap: wrap;
      margin-bottom: 1.1rem;
      padding: 0.7rem 1rem;
      background: #fff;
      border-radius: 10px;
      border: 0.5px solid #d3d1c7;
      font-size: 11.5px;
    }

    .leg-item { display: flex; align-items: center; gap: 6px; color: #5f5e5a; }

    .leg-dot {
      width: 11px; height: 11px;
      border-radius: 50%; flex-shrink: 0;
    }

    /* Filter bar */
    .filter-bar { display: flex; gap: 7px; flex-wrap: wrap; margin-bottom: 1.4rem; }

    .filter-btn {
      font-size: 11.5px;
      font-family: inherit;
      padding: 5px 13px;
      border: 0.5px solid #b4b2a9;
      background: transparent;
      color: #5f5e5a;
      border-radius: 20px;
      cursor: pointer;
      transition: all 0.15s;
    }

    .filter-btn:hover { background: #ebe9e3; color: #1a1a18; }

    .filter-btn.active {
      background: #1a1a18;
      color: #fff;
      border-color: #1a1a18;
    }

    /* Timeline */
    .timeline { display: flex; flex-direction: column; }

    .tl-entry { display: flex; gap: 14px; align-items: stretch; }

    .tl-connector {
      display: flex; flex-direction: column;
      align-items: center; width: 18px;
      flex-shrink: 0; padding-top: 19px;
    }

    .tl-dot {
      width: 13px; height: 13px;
      border-radius: 50%; border: 2.5px solid;
      flex-shrink: 0;
    }

    .tl-line {
      width: 2px; flex: 1;
      min-height: 14px; margin-top: 4px;
    }

    .tl-card {
      flex: 1;
      background: #fff;
      border: 0.5px solid #d3d1c7;
      border-radius: 12px;
      padding: 13px 15px;
      margin-bottom: 12px;
      cursor: pointer;
      transition: border-color 0.15s, box-shadow 0.15s;
    }

    .tl-card:hover {
      border-color: #888780;
      box-shadow: 0 2px 8px rgba(0,0,0,0.07);
    }

    .tl-card-top {
      display: flex; align-items: center;
      gap: 9px; margin-bottom: 4px; flex-wrap: wrap;
    }

    .tl-year { font-size: 11.5px; font-weight: 700; min-width: 66px; }

    .tl-tag {
      font-size: 10.5px; font-weight: 700;
      padding: 2px 8px; border-radius: 10px;
    }

    .tl-name { font-size: 14.5px; font-weight: 700; color: #1a1a18; margin-bottom: 2px; }

    .tl-person { font-size: 11.5px; color: #888780; margin-bottom: 6px; }

    .tl-desc { font-size: 13px; color: #3d3d3a; line-height: 1.65; }

    .tl-exp-wrap {
      display: none; margin-top: 10px;
      padding: 10px 12px; border-radius: 8px;
      font-size: 12.5px; line-height: 1.65;
    }

    .tl-card.expanded .tl-exp-wrap { display: block; }

    .expand-hint {
      font-size: 10.5px; color: #b4b2a9;
      margin-top: 7px; transition: color 0.15s;
      user-select: none;
    }

    .tl-card:hover .expand-hint { color: #888780; }
    .tl-card.expanded .expand-hint { display: none; }

    /* Highlight box for Bohr/Mendeleev — still-used today */
    .still-used {
      margin-top: 10px; padding: 8px 11px;
      border-radius: 7px; font-size: 12px;
      font-weight: 600; display: none;
      border-left: 3px solid;
    }

    .tl-card.expanded .still-used { display: block; }

    /* Section dividers */
    .section-label {
      font-size: 11px; font-weight: 700;
      text-transform: uppercase; letter-spacing: 0.08em;
      color: #888780; padding: 0.5rem 0 0.3rem;
      margin-bottom: 0.5rem;
      border-bottom: 0.5px solid #d3d1c7;
    }

    /* Category colours */
    /* Ancient Greek */
    .cat-greek .tl-dot  { background: #888780; border-color: #444441; }
    .cat-greek .tl-line { background: #b4b2a9; }
    .cat-greek .tl-year { color: #444441; }
    .cat-greek .tl-tag  { background: #d3d1c7; color: #2c2c2a; }
    .cat-greek .tl-exp-wrap { background: #f1efe8; color: #2c2c2a; }

    /* Alchemy */
    .cat-alchemy .tl-dot  { background: #ef9f27; border-color: #854f0b; }
    .cat-alchemy .tl-line { background: #fac775; }
    .cat-alchemy .tl-year { color: #854f0b; }
    .cat-alchemy .tl-tag  { background: #faeeda; color: #412402; }
    .cat-alchemy .tl-exp-wrap { background: #faeeda; color: #412402; }

    /* Lavoisier / early modern */
    .cat-early .tl-dot  { background: #5dcaa5; border-color: #0f6e56; }
    .cat-early .tl-line { background: #9fe1cb; }
    .cat-early .tl-year { color: #0f6e56; }
    .cat-early .tl-tag  { background: #e1f5ee; color: #085041; }
    .cat-early .tl-exp-wrap { background: #e1f5ee; color: #04342c; }

    /* Atomic models */
    .cat-model .tl-dot  { background: #7f77dd; border-color: #534ab7; }
    .cat-model .tl-line { background: #afa9ec; }
    .cat-model .tl-year { color: #534ab7; }
    .cat-model .tl-tag  { background: #eeedfe; color: #26215c; }
    .cat-model .tl-exp-wrap { background: #eeedfe; color: #26215c; }
    .cat-model .still-used { background: #eeedfe; border-color: #7f77dd; color: #26215c; }

    /* Periodic table / electron config */
    .cat-periodic .tl-dot  { background: #85b7eb; border-color: #185fa5; }
    .cat-periodic .tl-line { background: #b5d4f4; }
    .cat-periodic .tl-year { color: #185fa5; }
    .cat-periodic .tl-tag  { background: #e6f1fb; color: #042c53; }
    .cat-periodic .tl-exp-wrap { background: #e6f1fb; color: #042c53; }
    .cat-periodic .still-used { background: #e6f1fb; border-color: #85b7eb; color: #042c53; }

    footer {
      max-width: 780px; margin: 2rem auto 0;
      text-align: center; font-size: 11.5px;
      color: #b4b2a9; padding-bottom: 1rem;
    }

    @media (max-width: 520px) {
      .page-header h1 { font-size: 1.3rem; }
      .tl-card { padding: 11px 12px; }
    }
  </style>
</head>
<body>

  <div class="page-header">
    <h1>History of Atomic Theory</h1>
    <p>Follow the journey from ancient philosophy to the model we use today.<br>
    <em>Click any card to reveal the key experiment or evidence behind the idea.</em></p>
  </div>

  <div class="container">

    <div class="legend">
      <div class="leg-item">
        <div class="leg-dot" style="background:#888780;border:2px solid #444441;"></div>
        Ancient Greek philosophy
      </div>
      <div class="leg-item">
        <div class="leg-dot" style="background:#ef9f27;border:2px solid #854f0b;"></div>
        Alchemy
      </div>
      <div class="leg-item">
        <div class="leg-dot" style="background:#5dcaa5;border:2px solid #0f6e56;"></div>
        Lavoisier &amp; early chemistry
      </div>
      <div class="leg-item">
        <div class="leg-dot" style="background:#7f77dd;border:2px solid #534ab7;"></div>
        Atomic models
      </div>
      <div class="leg-item">
        <div class="leg-dot" style="background:#85b7eb;border:2px solid #185fa5;"></div>
        Periodic table &amp; electrons
      </div>
    </div>

    <div class="filter-bar">
      <button class="filter-btn active" data-cat="all">All</button>
      <button class="filter-btn" data-cat="cat-greek">Ancient Greek</button>
      <button class="filter-btn" data-cat="cat-alchemy">Alchemy</button>
      <button class="filter-btn" data-cat="cat-early">Lavoisier</button>
      <button class="filter-btn" data-cat="cat-model">Atomic models</button>
      <button class="filter-btn" data-cat="cat-periodic">Periodic table &amp; electrons</button>
    </div>

    <div class="timeline" id="timeline"></div>

  </div>

  <footer>IB MYP Science — Atoms &amp; Periodic Table Unit</footer>

  <script>
    const entries = [

      // ─── ANCIENT GREEK PHILOSOPHY ───────────────────────────────
      {
        cat: "cat-greek",
        section: "Ancient Greek philosophy",
        year: "~585 BCE",
        name: "Thales — everything is water",
        person: "Thales of Miletus — Ancient Greece",
        tag: "Philosophy",
        desc: "One of the very first philosophers to ask 'what is everything made of?' Thales proposed that water is the fundamental substance underlying all matter. Everything in the world is a form of water — solids, liquids, and gases are just different states of it.",
        exp: "<strong>Evidence / reasoning:</strong> Thales observed that water can exist as solid, liquid, and vapour; that living things need water; and that the earth appeared to float on water. No experiments — pure philosophical reasoning. His importance is not the answer (which was wrong) but the question: he was the first to seek a natural explanation for matter rather than a mythological one.",
        stillUsed: null
      },
      {
        cat: "cat-greek",
        year: "~450 BCE",
        name: "Empedocles — four elements",
        person: "Empedocles — Ancient Greece",
        tag: "Philosophy",
        desc: "Proposed that all matter is made from four basic substances: earth, water, air, and fire. These could be mixed in different proportions to produce every material in the world.",
        exp: "<strong>Evidence / reasoning:</strong> Pure philosophical observation — no experiments. Empedocles noticed that materials seemed to burn (fire), dry out (earth), flow (water), or evaporate (air), and concluded these were the building blocks of everything.",
        stillUsed: null
      },
      {
        cat: "cat-greek",
        year: "~430 BCE",
        name: "Democritus — the atom",
        person: "Democritus — Ancient Greece",
        tag: "Philosophy",
        desc: "Proposed that matter cannot be divided forever — eventually you would reach the smallest possible particle, which he called <em>atomos</em> (ἄτομος, meaning 'uncuttable'). These atoms were indestructible, differed in shape and size, and moved through empty space (the void).",
        exp: "<strong>Evidence / reasoning:</strong> Thought experiment — if you kept cutting something in half, you couldn't go on forever. Therefore a smallest unit must exist. This was radical thinking but had no experimental backing. His idea was largely ignored for 2,000 years.",
        stillUsed: null
      },
      {
        cat: "cat-greek",
        year: "~350 BCE",
        name: "Aristotle — no void, no atoms",
        person: "Aristotle — Ancient Greece",
        tag: "Philosophy",
        desc: "Rejected atomism completely. Agreed with Empedocles' four elements but added that nature 'abhors a vacuum' — empty space cannot exist. Matter is continuous; there is no smallest particle. Because of Aristotle's enormous authority, his view dominated science for nearly 2,000 years.",
        exp: "<strong>Why Aristotle 'won':</strong> Aristotle wrote extensively and his ideas were adopted by both the Church and Islamic scholars throughout the Middle Ages. Anyone who questioned his views risked being seen as challenging religious authority. This is a key Nature of Science point — the acceptance of an idea is shaped by culture and authority, not just evidence.",
        stillUsed: null
      },

      // ─── ALCHEMY ────────────────────────────────────────────────
      {
        cat: "cat-alchemy",
        section: "Alchemy",
        year: "~800–1700 CE",
        name: "Alchemy — transforming matter",
        person: "Islamic, European &amp; Chinese scholars (many centuries)",
        tag: "Alchemy",
        desc: "Alchemists believed that the four elements of Aristotle and Empedocles could be rearranged to transform one substance into another. Their great goals were turning base metals (like lead) into gold, and finding an 'elixir of life'. They kept Aristotle's four-element model alive and built on it.",
        exp: "<strong>What alchemists actually contributed:</strong> Despite their mistaken goals, alchemists made important practical advances — they developed early laboratory techniques (distillation, filtration, crystallisation), refined and concentrated substances like acids and alcohol, and carefully recorded chemical observations. Their work laid the practical foundation for modern chemistry, even if their theory was wrong.",
        stillUsed: null
      },
      {
        cat: "cat-alchemy",
        year: "~1600s–1700s",
        name: "Phlogiston theory",
        person: "Johann Becher (1667) &amp; Georg Ernst Stahl (1703) — Germany",
        tag: "Alchemy",
        desc: "Becher proposed that flammable materials contain a combustible substance; Stahl developed this into <em>phlogiston theory</em>. When something burns, it releases phlogiston into the air. A candle goes out in a closed jar because the air becomes saturated with phlogiston and can absorb no more. When metals rust, they too were thought to release phlogiston, leaving behind a 'calx' (what we now call a metal oxide).",
        exp: "<strong>The problem:</strong> If burning and rusting both release phlogiston, the products should be <em>lighter</em> than the original material. But metals actually <em>gain</em> mass when they rust — the opposite of what phlogiston theory predicted. This anomaly was noticed but explained away for decades. Phlogiston theory is a great example of how scientists can patch a wrong model with extra assumptions rather than abandon it.",
        stillUsed: null
      },

      // ─── LAVOISIER ──────────────────────────────────────────────
      {
        cat: "cat-early",
        section: "Lavoisier contradicts the alchemists",
        year: "1774–1789",
        name: "Lavoisier — oxygen &amp; the end of phlogiston",
        person: "Antoine Lavoisier — France",
        tag: "Modern chemistry",
        desc: "Lavoisier disproved phlogiston theory and replaced it with a new explanation based on careful measurement. He showed that burning and rusting are not about <em>releasing</em> phlogiston — they are about <em>combining with oxygen</em> from the air. He also proved that mass is conserved in all chemical reactions (nothing is created or destroyed).",
        exp: "<strong>Key experiment:</strong> Lavoisier carefully weighed substances before and after burning in sealed containers. When mercury was heated in a fixed amount of air, it formed a red powder (mercury oxide) and the remaining air shrank by exactly the volume needed to explain the mass gain. He isolated the gas responsible and named it <em>oxygène</em>. Total mass of reactants always equalled total mass of products — the Law of Conservation of Mass. This directly contradicted phlogiston theory and ended it.",
        stillUsed: null
      },

      // ─── ATOMIC MODELS ──────────────────────────────────────────
      {
        cat: "cat-model",
        section: "Atomic models",
        year: "1803",
        name: "Dalton's Billiard Ball model",
        person: "John Dalton — England",
        tag: "Model 1",
        desc: "The first scientific atomic model. Dalton proposed that all matter is made of atoms; atoms of the same element are identical; atoms of different elements have different masses; atoms join in whole-number ratios to form compounds; atoms cannot be created, destroyed, or split.",
        exp: "<strong>Key evidence:</strong> Elements always combine in fixed mass ratios (Law of Definite Proportions). When two elements form more than one compound, the ratios are always small whole numbers — only possible if you are counting individual particles. <strong>Limitation:</strong> The 'billiard ball' atom has no internal structure and cannot explain electricity or light.",
        stillUsed: null
      },
      {
        cat: "cat-model",
        year: "1869",
        name: "Mendeleev's Periodic Table",
        person: "Dmitri Mendeleev — Russia",
        tag: "Periodic table",
        desc: "Mendeleev arranged the 63 known elements in order of increasing atomic mass and noticed that properties repeated in a regular (periodic) pattern. He was brave enough to leave gaps for elements not yet discovered — and to predict their properties in advance.",
        exp: "<strong>Key evidence:</strong> When arranged by mass, elements with similar properties fell into the same columns. Mendeleev predicted gallium (discovered 1875) and germanium (discovered 1886) — both matched his predictions almost exactly. This was powerful evidence that the table revealed a deep truth about atomic structure.",
        stillUsed: "The Periodic Table is still used today — now arranged by atomic number (number of protons). The repeating patterns of properties are explained by electron configuration: elements in the same group have the same number of electrons in their outer shell."
      },
      {
        cat: "cat-model",
        year: "1897",
        name: "Thomson's Plum Pudding model",
        person: "J.J. Thomson — England",
        tag: "Model 2",
        desc: "Thomson discovered that atoms contain tiny <em>negatively</em> charged particles — electrons. This shattered Dalton's idea of an indivisible atom. Thomson pictured the atom as a positive 'pudding' (sphere) with electrons embedded in it like plums — hence the name.",
        exp: "<strong>Key experiment: Cathode ray tube.</strong> Thomson passed electric current through a vacuum tube. A beam (cathode ray) shot from the negative end. He bent the beam using electric and magnetic fields and calculated the charge-to-mass ratio of the particles — it was the same regardless of which metal electrode was used. This proved electrons are a universal part of all atoms.",
        stillUsed: null
      },
      {
        cat: "cat-model",
        year: "1909–1911",
        name: "Rutherford's Nuclear model",
        person: "Ernest Rutherford — New Zealand / England",
        tag: "Model 3",
        desc: "Rutherford discovered that almost all of an atom's mass is concentrated in a tiny, dense, positively charged <em>nucleus</em> at the centre. The atom is mostly empty space, with electrons somewhere on the outside — like planets around a sun.",
        exp: "<strong>Key experiment: Gold foil experiment.</strong> Rutherford fired positively charged alpha particles at a very thin sheet of gold foil, with detectors surrounding it. Expected result (if Thomson's model was right): all particles should pass straight through with slight deflection. Actual result: most passed through, but about 1 in 20,000 bounced almost straight back. Rutherford's conclusion: the atom must have a tiny, dense, positive nucleus — most of the atom is empty space.",
        stillUsed: null
      },
      {
        cat: "cat-model",
        year: "1913",
        name: "Bohr's Shell model",
        person: "Niels Bohr — Denmark",
        tag: "Model 4",
        desc: "Bohr improved Rutherford's model by adding rules about where electrons can be. Electrons can only orbit the nucleus in specific, fixed <em>energy levels</em> (shells). They cannot exist between shells. When an electron jumps from a higher shell to a lower one, it releases a specific amount of energy as light.",
        exp: "<strong>Key evidence: Emission spectra.</strong> When hydrogen gas is energised (by passing electricity through it in a discharge tube), it emits light — but only at very specific colours (wavelengths), not a continuous rainbow. Each colour corresponds to an electron dropping between specific energy levels. Bohr's calculated energy levels matched the observed spectral lines of hydrogen exactly. <strong>Why Bohr's model still matters:</strong> The shell model is the basis for electron configuration diagrams and explains chemical bonding and the periodic table.",
        stillUsed: "We still use the Bohr shell model today to draw electron configuration diagrams and explain why elements react the way they do — this links directly to the Periodic Table."
      },

      // ─── PERIODIC TABLE & ELECTRONS ─────────────────────────────
      {
        cat: "cat-periodic",
        section: "Periodic table &amp; electron configuration",
        year: "Today",
        name: "Electron configuration diagrams",
        person: "Based on Bohr's shell model",
        tag: "Used today",
        desc: "We use the Bohr shell model to show how electrons are arranged around the nucleus in energy levels (shells). Shell 1 holds up to 2 electrons, shell 2 holds up to 8, shell 3 holds up to 8. The number of electrons in the outer shell determines an element's chemical properties and its position in the Periodic Table.",
        exp: "<strong>How to use it:</strong> Find the element's atomic number (= number of protons = number of electrons in a neutral atom). Fill the shells from the inside out: shell 1 fills first (max 2), then shell 2 (max 8), then shell 3 (max 8). Example — sodium (Na) has 11 electrons: 2 in shell 1, 8 in shell 2, 1 in shell 3. That lone outer electron is why sodium is so reactive.",
        stillUsed: "This is the model you will use in class to draw electron diagrams and explain why elements in Group 1 are all reactive metals, why noble gases are unreactive, and how bonding works."
      }

    ];

    const timeline = document.getElementById('timeline');

    function render(filter) {
      timeline.innerHTML = '';
      const data = filter === 'all' ? entries : entries.filter(e => e.cat === filter);
      if (!data.length) {
        timeline.innerHTML = '<p style="text-align:center;color:#888780;padding:2rem;font-size:14px;">No entries for this filter.</p>';
        return;
      }

      let lastSection = null;

      data.forEach((e, i) => {
        // Section divider
        if (e.section && e.section !== lastSection) {
          const sec = document.createElement('div');
          sec.className = 'section-label';
          sec.textContent = e.section;
          timeline.appendChild(sec);
          lastSection = e.section;
        }

        const isLast = i === data.length - 1;
        const wrap = document.createElement('div');
        wrap.className = `tl-entry ${e.cat}`;
        wrap.innerHTML = `
          <div class="tl-connector">
            <div class="tl-dot"></div>
            ${!isLast ? '<div class="tl-line"></div>' : ''}
          </div>
          <div class="tl-card" onclick="this.classList.toggle('expanded')">
            <div class="tl-card-top">
              <span class="tl-year">${e.year}</span>
              <span class="tl-tag">${e.tag}</span>
            </div>
            <div class="tl-name">${e.name}</div>
            <div class="tl-person">${e.person}</div>
            <div class="tl-desc">${e.desc}</div>
            <div class="tl-exp-wrap">${e.exp}</div>
            ${e.stillUsed ? `<div class="still-used">${e.stillUsed}</div>` : ''}
            <div class="expand-hint">+ Click to reveal key experiment / evidence</div>
          </div>
        `;
        timeline.appendChild(wrap);
      });
    }

    document.querySelectorAll('.filter-btn').forEach(btn => {
      btn.addEventListener('click', () => {
        document.querySelectorAll('.filter-btn').forEach(b => b.classList.remove('active'));
        btn.classList.add('active');
        render(btn.dataset.cat);
      });
    });

    render('all');
  </script>

</body>
</html>
