---
layout: page
permalink: /join/
title: Join the Journey
description: How to join my research group at the University of Ottawa.
nav: true
nav_order: 8
nav_highlight: true
chart:
  echarts: true
---

> ⚠️ Please read this page carefully before contacting me. It will also help you write a stronger email!
{: .block-warning }

Thank you for considering joining my research group. I'm genuinely excited to build a lab with curious, motivated people, and I'd love to hear from you if our research interests align.

---

## A Lab Built on Mutual Commitment

*What I offer flows outward; what I look for flows inward; node size reflects relative importance. Click a node to read more below.*

<style>
  .echarts { height: 480px !important; cursor: pointer; }

  .node-detail-panel {
    --detail-color: #8e1336;
    display: none;
    position: relative;
    border: 1px solid var(--global-divider-color);
    border-left: 4px solid var(--detail-color);
    background: var(--global-card-bg-color);
    border-radius: 8px;
    padding: 1.4em 2em 1.4em 1.6em;
    margin: 0.5em 0 2em 0;
  }
  .node-detail-panel.cat-center { --detail-color: #8e1336; }
  .node-detail-panel.cat-offer  { --detail-color: #0a84ff; }
  .node-detail-panel.cat-expect { --detail-color: #ff9500; }
  html[data-theme="dark"] .node-detail-panel.cat-center { --detail-color: #d96280; }
  .node-detail-panel.visible {
    display: block;
    animation: nodeDetailFadeIn 0.25s ease;
  }
  .node-detail-panel h3 {
    margin-top: 0;
    margin-bottom: 0.5em;
    color: var(--detail-color);
  }
  .node-detail-panel p:last-child {
    margin-bottom: 0;
  }
  .node-detail-close {
    position: absolute;
    top: 0.4em;
    right: 0.6em;
    width: 1.8em;
    height: 1.8em;
    background: transparent;
    border: none;
    font-size: 1.3rem;
    line-height: 1;
    cursor: pointer;
    color: var(--global-text-color-light);
    border-radius: 50%;
  }
  .node-detail-close:hover {
    color: var(--global-text-color);
    background: var(--global-divider-color);
  }
  @keyframes nodeDetailFadeIn {
    from { opacity: 0; transform: translateY(6px); }
    to   { opacity: 1; transform: translateY(0); }
  }
</style>

```echarts
{
  "backgroundColor": "transparent",
  "tooltip": { "show": false },
  "legend": [
    {
      "data": ["What I Offer", "What I Look For"],
      "bottom": 4,
      "icon": "roundRect",
      "itemWidth": 16,
      "itemHeight": 10,
      "textStyle": { "fontSize": 12 }
    }
  ],
  "xAxis": {
    "show": false, "type": "value", "min": 0, "max": 1000,
    "splitLine": { "show": false }
  },
  "yAxis": {
    "show": false, "type": "value", "min": 0, "max": 600, "inverse": true,
    "splitLine": { "show": false }
  },
  "grid": { "left": 10, "right": 10, "top": 0, "bottom": 30, "containLabel": false },
  "animationDuration": 1400,
  "animationEasing": "cubicOut",
  "series": [
    {
      "name": "Offer flow",
      "type": "lines",
      "coordinateSystem": "cartesian2d",
      "polyline": false,
      "z": 1,
      "tooltip": { "show": false },
      "effect": {
        "show": true,
        "period": 4.5,
        "trailLength": 0.4,
        "symbol": "arrow",
        "symbolSize": 8,
        "color": "#0A84FF"
      },
      "lineStyle": { "color": "#0A84FF", "width": 1.5, "opacity": 0.32, "curveness": 0.18 },
      "data": [
        { "coords": [[500, 300], [418, 157]] },
        { "coords": [[500, 300], [354, 223]] },
        { "coords": [[500, 300], [335, 300]] },
        { "coords": [[500, 300], [354, 377]] },
        { "coords": [[500, 300], [418, 443]] }
      ]
    },
    {
      "name": "Expect flow",
      "type": "lines",
      "coordinateSystem": "cartesian2d",
      "polyline": false,
      "z": 1,
      "tooltip": { "show": false },
      "effect": {
        "show": true,
        "period": 4.5,
        "trailLength": 0.4,
        "symbol": "arrow",
        "symbolSize": 8,
        "color": "#FF9500"
      },
      "lineStyle": { "color": "#FF9500", "width": 1.5, "opacity": 0.32, "curveness": 0.18 },
      "data": [
        { "coords": [[595, 165], [500, 300]] },
        { "coords": [[659, 257], [500, 300]] },
        { "coords": [[659, 343], [500, 300]] },
        { "coords": [[595, 435], [500, 300]] }
      ]
    },
    {
      "type": "graph",
      "coordinateSystem": "cartesian2d",
      "z": 10,
      "roam": false,
      "label": {
        "show": true,
        "position": "inside",
        "color": "#ffffff",
        "fontSize": 12,
        "fontWeight": 600,
        "lineHeight": 16,
        "fontFamily": "-apple-system, BlinkMacSystemFont, 'SF Pro Display', 'Helvetica Neue', system-ui, sans-serif"
      },
      "edgeSymbol": ["none", "none"],
      "lineStyle": { "opacity": 0, "width": 0 },
      "emphasis": {
        "focus": "adjacency",
        "scale": 1.05,
        "itemStyle": {
          "shadowBlur": 36,
          "shadowOffsetY": 16,
          "shadowColor": "rgba(0, 0, 0, 0.22)"
        },
        "label": { "fontSize": 13 }
      },
      "blur": {
        "itemStyle": { "opacity": 0.18 },
        "label":     { "color": "rgba(255,255,255,0.45)" }
      },
      "categories": [
        {
          "name": "Research Lab",
          "itemStyle": {
            "color": "#8E1336",
            "shadowBlur": 22,
            "shadowOffsetY": 12,
            "shadowColor": "rgba(0, 0, 0, 0.16)",
            "borderColor": "rgba(255, 255, 255, 0.10)",
            "borderWidth": 0.5
          }
        },
        {
          "name": "What I Offer",
          "itemStyle": {
            "color": "#0A84FF",
            "shadowBlur": 16,
            "shadowOffsetY": 9,
            "shadowColor": "rgba(0, 0, 0, 0.12)",
            "borderColor": "rgba(255, 255, 255, 0.10)",
            "borderWidth": 0.5
          }
        },
        {
          "name": "What I Look For",
          "itemStyle": {
            "color": "#FF9500",
            "shadowBlur": 16,
            "shadowOffsetY": 9,
            "shadowColor": "rgba(0, 0, 0, 0.12)",
            "borderColor": "rgba(255, 255, 255, 0.10)",
            "borderWidth": 0.5
          }
        }
      ],
      "data": [
        { "id": "center", "name": "Research\nLab", "value": [500, 300], "symbolSize": 110, "category": 0, "label": { "fontSize": 14 } },
        { "id": "o1", "name": "Impactful\nResearch",    "value": [418, 157], "symbol": "roundRect", "symbolSize": [140, 50], "category": 1 },
        { "id": "o2", "name": "uOttawa\nEnvironment",   "value": [354, 223], "symbol": "roundRect", "symbolSize": [140, 50], "category": 1 },
        { "id": "o3", "name": "Funding",                "value": [335, 300], "symbol": "roundRect", "symbolSize": [140, 50], "category": 1 },
        { "id": "o4", "name": "Mentorship",             "value": [354, 377], "symbol": "roundRect", "symbolSize": [140, 50], "category": 1 },
        { "id": "o5", "name": "Collaboration",          "value": [418, 443], "symbol": "roundRect", "symbolSize": [140, 50], "category": 1 },
        { "id": "e1", "name": "Self-motivation\n& Curiosity", "value": [595, 165], "symbol": "roundRect", "symbolSize": [150, 65], "category": 2 },
        { "id": "e2", "name": "Passion\n& Tenacity",          "value": [659, 257], "symbol": "roundRect", "symbolSize": [125, 58], "category": 2 },
        { "id": "e3", "name": "Technical\nSkills",            "value": [659, 343], "symbol": "roundRect", "symbolSize": [110, 52], "category": 2 },
        { "id": "e4", "name": "Collaboration",                "value": [595, 435], "symbol": "roundRect", "symbolSize": [100, 46], "category": 2 }
      ],
      "links": [
        { "source": "center", "target": "o1" },
        { "source": "center", "target": "o2" },
        { "source": "center", "target": "o3" },
        { "source": "center", "target": "o4" },
        { "source": "center", "target": "o5" },
        { "source": "e1", "target": "center" },
        { "source": "e2", "target": "center" },
        { "source": "e3", "target": "center" },
        { "source": "e4", "target": "center" }
      ]
    }
  ]
}
```

<div id="node-detail-panel" class="node-detail-panel" role="region" aria-live="polite">
  <button class="node-detail-close" aria-label="Close" type="button">×</button>
  <h3 id="node-detail-title"></h3>
  <div id="node-detail-body"></div>
</div>

<script>
  (function () {
    const NODE_CONTENT = {
      "o1": {
        title: "Impactful Research",
        body: "<p>We tackle cutting-edge problems at the frontier of AI and software engineering, with a focus on reliable LLM integration, agentic workflow design, and model-based validation. We publish at top SE and AI venues.</p>"
      },
      "o2": {
        title: "uOttawa Environment",
        body: "<p>The University of Ottawa is among Canada's top research universities, located in the heart of the nation's capital with strong ties to industry, government, and the broader Ottawa tech ecosystem. The EECS school is a collegial, active community with excellent facilities for AI and software engineering research. <a href='https://www.uottawa.ca/study/this-is-uottawa/why-choose-uottawa-international-students' target='_blank' rel='noopener'>Why choose uOttawa →</a></p>"
      },
      "o3": {
        title: "Funding",
        body: "<p>I fund PhD and MSc students through research assistantships, and support strong candidates in applying for external scholarships such as NSERC, OGS, Vanier, and Mitacs. See the <a href='#funding'>Funding &amp; Scholarships</a> section below for the full list.</p>"
      },
      "o4": {
        title: "Mentorship",
        body: "<p>I work closely with students on both research direction and the broader experience of graduate life, from paper writing to career planning. My goal is to grow your independence over time, so by the end of the program, you will be able to drive your own research agenda or career decisions.</p>"
      },
      "o5": {
        title: "Collaboration",
        body: "<p>We collaborate frequently with local and global experts across academia and industry.</p>"
      },
      "e1": {
        title: "Self-motivation & Curiosity",
        body: "<p>Research is full of uncertainty, and much of the work is venturing into the unknown. That makes it essential to work on something that genuinely motivates you. We hope you find the topics we work on exciting, and that your curiosity is what pulls you deeper into them.</p>"
      },
      "e2": {
        title: "Passion & Tenacity",
        body: "<p>Research is all about setbacks, unexpected results, rejected papers, and more. We treat setbacks as data, not defeat. We revisit hard ideas, hold beliefs strongly but loosely, and keep working. Passion fuels the start; tenacity finishes the work. We hope you bring the same energy.</p>"
      },
      "e3": {
        title: "Technical Skills",
        body: "<ul><li>Programming or vibe coding (so long as you understand what's going on)</li><li>One of the following (both is a bonus):<ul><li>Strong grasp of fundamental AI ideas such as NLP, optimization, or LLMs</li><li>Deep understanding of fundamental SE concepts such as software design, modeling, implementation, and testing</li></ul></li><li>Prior research experience (publications, internships, projects) is a plus</li></ul>"
      },
      "e4": {
        title: "Collaboration",
        body: "<p>Group meetings, papers, and code review all happen in English, so <strong>strong written and spoken English is essential</strong>. Beyond language, we look for labmates who give generous feedback and treat the lab as a shared effort.</p>"
      }
    };

    function attachNodeClickHandler(retries = 40) {
      const chartDiv = document.querySelector('.echarts');
      const chart = chartDiv && window.echarts && echarts.getInstanceByDom(chartDiv);
      if (!chart) {
        if (retries > 0) setTimeout(() => attachNodeClickHandler(retries - 1), 100);
        return;
      }

      chart.on('click', { dataType: 'node' }, function (params) {
        const content = NODE_CONTENT[params.data.id];
        if (!content) return;
        const panel = document.getElementById('node-detail-panel');
        document.getElementById('node-detail-title').textContent = content.title;
        document.getElementById('node-detail-body').innerHTML = content.body;

        const id = params.data.id;
        const cat = id === 'center' ? 'cat-center'
                  : id[0] === 'o'   ? 'cat-offer'
                  :                   'cat-expect';
        panel.classList.remove('cat-center', 'cat-offer', 'cat-expect');
        panel.classList.add(cat);

        panel.classList.remove('visible');
        void panel.offsetWidth; // restart animation
        panel.classList.add('visible');
        panel.scrollIntoView({ behavior: 'smooth', block: 'nearest' });
      });

      document.querySelector('.node-detail-close').addEventListener('click', function () {
        document.getElementById('node-detail-panel').classList.remove('visible');
      });
    }

    document.addEventListener('readystatechange', function () {
      if (document.readyState === 'complete') attachNodeClickHandler();
    });
  })();
</script>

---

## Graduate Students (PhD / MSc)

I am actively recruiting for motivated graduate students. A PhD typically takes 4–5 years; an MSc takes about 2 years. I'm committed to working closely with you throughout.

**How to reach out:** Please send me an email with the subject line:

<div style="
  font-family: monospace;
  background: var(--global-code-bg-color);
  border-left: 4px solid var(--global-theme-color);
  border-radius: 0 6px 6px 0;
  padding: 0.6em 1em;
  margin: 1em 0;
  font-size: 0.95rem;
">[Prospective Student] &lt;PhD/MSc&gt; &lt;Start Term&gt; — &lt;Your Name&gt;</div>

Please include:

- A short note about your research interests and why they connect to my work. Mentioning a specific topic you found interesting goes a long way!
- Your CV and transcripts
- Your intended program and start date

I review emails every few weeks and genuinely try to respond when I see a strong fit. Due to volume, I may not always be able to reply. If you don't hear back within 3–4 weeks, it likely means I'm unable to offer a position at this time. I appreciate your understanding.

> 📅 Make sure to check the [program-specific application deadlines](https://www.uottawa.ca/study/graduate-studies/program-specific-requirements) for your targeted start date.International students typically have earlier deadlines.
{: .block-tip }

---

<!-- ## Visiting & Internships

I also welcome short-term visitors and interns who want to engage with our research for a few months. 

### uOttawa undergraduate students

If you're already at uOttawa, there are several ways to get involved:

- **[NSERC Undergraduate Student Research Award (USRA)](https://www.nserc-crsng.gc.ca/students-etudiants/ug-pc/usra-brpc_eng.asp)** — paid 16-week summer research position for Canadian citizens and permanent residents. Apply through your faculty.
- **Course-credit research** — honours projects, capstones (e.g., SEG/ELG 4910/4911), or directed studies (e.g., CSI 4900). A good way to try research before committing to a longer program.

Email me with your CV, transcript, the route you're considering, and a short note about what excites you in the lab's research.

### International undergraduate students

- **[Mitacs Globalink Research Internship](https://www.mitacs.ca/our-programs/globalink-research-internship-students/)** — funded 12-week summer placements for international undergraduates from partner countries.

### Graduate students from other institutions

If you have your own funding (e.g., a CSC scholarship, support from your home institution, or sabbatical leave), please contact me directly with your CV, proposed dates, and funding source. -->

<!-- --- -->

## Funding & Scholarships {#funding}

I typically fund PhD and MSc students through research assistantships. There are also a number of external awards worth pursuing, and I'm happy to support strong candidates in applying:

**For domestic students (Canadian citizens & permanent residents):**
- [NSERC Canada Graduate Research Scholarship – Master's (CGRS-M)](https://www.nserc-crsng.gc.ca/students-etudiants/pg-cs/cgsm-bescm_eng.asp)
- [Vanier Canada Graduate Scholarship](https://vanier.gc.ca/en/home-accueil.html)

**For all students:**
- [NSERC Canada Graduate Research Scholarship – Doctoral (CGRS-D)](https://www.nserc-crsng.gc.ca/students-etudiants/pg-cs/cgsd-bescd_eng.asp)
- [Ontario Graduate Scholarship (OGS)](https://osap.gov.on.ca/OSAPPortal/en/A-ZListofAid/PRDR019245.html)
- [University of Ottawa Admission Scholarships](https://www.uottawa.ca/study/graduate-studies/funding-financing/awards/admission-scholarship) — automatically considered upon admission
- [Mitacs Accelerate](https://www.mitacs.ca/our-programs/accelerate-core-business/) — industry-partnered research funding

> 💰 For a complete list of funding and scholarship opportunities available at uOttawa, see the [Awards and Financial Support](https://www.uottawa.ca/study/graduate-studies/awards-financial-support) page.
{: .block-tip }

---

## International Students

As a former international student, I warmly welcome students from around the world, and I hope you'll seriously consider Ottawa as your next stop. A few practical things to keep in mind:

- **Start early.** Application deadlines for international students are typically earlier than for domestic students, to allow time for visa and study permit processing. Planning 8–12 months ahead is strongly recommended.
- **English proficiency.** If English is not your first language and you haven't completed a degree at an English-language institution, you'll need to submit TOEFL or IELTS scores that meet the University of Ottawa's requirements. Please check the language requirement from [uOttawa website](https://www.uottawa.ca/study/graduate-studies/program-specific-requirements).
- **Funding opportunities.** International students are eligible for the NSERC Doctoral scholar ship, the Ontario Graduate Scholarship, and uOttawa institutional awards including the [Differential Tuition Fee Exemption](https://www.uottawa.ca/study/fees-financial-support/differential-tuition-fee-exemption-scholarship).
- **External funding.** If you are receiving any external funding support, please mention this in your initial email.

---

<!-- ## Get Involved Early: Graph Discussion Group

Not ready to apply yet, but curious about our research? You're welcome to join our [Graph Discussion Group](https://lu.ma/gnn-discussion-group) — a bi-weekly seminar on graph neural networks and their applications, open to anyone interested. It's a low-pressure way to engage with the community, hear about ongoing work, and meet potential collaborators. Feel free to reach out if you'd like to be added to the mailing list or present your own work. -->
