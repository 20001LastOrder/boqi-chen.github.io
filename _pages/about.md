---
layout: about
title: about
permalink: /
subtitle: University of Ottawa

profile:
  align: right
  image: boqi_chen_1.png
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>email: boqi⚫chen@uottawa⚫ca</p>

news: true # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---
>I am an Assistant Professor in [the School of Electrical Engineering and Computer Science (EECS)](https://www.uottawa.ca/faculty-engineering/school-electrical-engineering-computer-science/directory/boqi-chen) at the University of Ottawa. My research focuses on the **reliable and robust integration of AI component, including LLMs and multi-agent systems, into software engineering processes**, with an emphasis on model-based validation techniques and principled agentic workflow design. I am also broadly interested in evaluating the quality and properties of ML models for software engineering tasks such as code generation, bug detection, and code summarization.

<div class="recruit-callout" style="
  border-radius: 8px;
  padding: 1em 1.5em;
  margin: 1.5em 0;
  clear: right;
">
  <p style="margin: 0; font-size: 1.1rem;">
    🎓 <strong>I am actively looking for motivated PhD and Master's students.</strong>
    If you are passionate about reliable AI systems, agentic workflow design, or AI for software engineering, I'd love to hear from you! See the <a href="/join/">Join the Journey</a> page for details.
  </p>
</div>

I received my PhD in 2025 from the [Department of Electrical and Computer Engineering](https://www.mcgill.ca/ece/) at McGill University, supervised by [Prof. Gunter Mussbacher](https://www.ece.mcgill.ca/~gmussb1/) and [Prof.Daniel Varro](https://liu.se/en/employee/danva91). During my PhD, I worked as an R&D engineer at [Aggregate Intellect](https://www.ai.science/) through a Mitacs grant and as a part-time research associate at _Huawei Waterloo Research Center_. I was also an active contributor to the open-source project [Sherpa](https://github.com/Aggregate-Intellect/sherpa), a large language model framework for robust agentic applications.

---

### my research, in layers
<style>
  :root {
    --layer-system-bg: #fffbe6;
    --layer-system-border: #c9930a;
    --layer-system-heading: #8a6200;
    --layer-comp-sw-bg: #fff2eb;
    --layer-comp-sw-border: #c05c2a;
    --layer-comp-sw-heading: #7a3010;
    --layer-comp-ai-bg: #fdeee6;
    --layer-comp-ai-border: #b84e38;
    --layer-comp-ai-heading: #722818;
    --layer-model-bg: #f9e8f2;
    --layer-model-border: #862a52;
    --layer-model-heading: #5a1035;
  }
  .recruit-callout {
    border: 2px solid #8F1336;
    background-color: #fdf0f3;
    color: #1a1a1a;
  }
  html[data-theme="dark"] .recruit-callout {
    background-color: #2a0a10;
    border-color: #c0395a;
    color: #f5e6ea;
  }
  html[data-theme="dark"] {
    --layer-system-bg: #2e2510;
    --layer-system-border: #c9930a;
    --layer-system-heading: #d4a830;
    --layer-comp-sw-bg: #2e1a0e;
    --layer-comp-sw-border: #c05c2a;
    --layer-comp-sw-heading: #d4844a;
    --layer-comp-ai-bg: #2a150e;
    --layer-comp-ai-border: #b84e38;
    --layer-comp-ai-heading: #c86050;
    --layer-model-bg: #261020;
    --layer-model-border: #862a52;
    --layer-model-heading: #c04080;
  }
</style>

  <div class="research-layers" style="margin: 2em 0;">

    <!-- System Layer -->
    <div style="border-left: 4px solid var(--layer-system-border); background: var(--layer-system-bg); color: var(--global-text-color);
                 padding: 1em 1.5em; border-radius: 0 8px 8px 0; margin-bottom: 0.5em;">
      <h4 style="color: var(--layer-system-heading);">System Layer</h4>
      <p>
      How to integrate AI components into software systems in a reliable and robust way, including reliable workflow construction (<a href="https://arxiv.org/pdf/2509.00272">MODELS'25</a>) and system-level evaluation (<a href="https://arxiv.org/pdf/2508.00630">MODELS'25</a>, <a href="https://arxiv.org/pdf/2411.15368">ICSE'25</a>).
      </p>
    </div>

    <!-- Component Layer: two side-by-side boxes -->
    <div style="display: flex; gap: 0.75em; margin: 0.5em 0 0.5em 2em;">

      <div style="flex: 1; border-left: 4px solid var(--layer-comp-sw-border); background: var(--layer-comp-sw-bg); color: var(--global-text-color);
                   padding: 1em 1.5em; border-radius: 0 8px 8px 0;">
        <h4 style="color: var(--layer-comp-sw-heading);">Traditional Software Component Layer</h4>
        <p>
        Create reliable software components that wrap around AI components to provide assurance, guarantees and fallback mechanisms (<a href="https://marussy.com/papers/ase22.pdf">ASE'22</a>, <a href="https://arxiv.org/pdf/2506.16639">RE'25</a>, <a href="https://arxiv.org/pdf/2508.00255">MODELS'25</a>)
        </p>
      </div>

      <div style="flex: 1; border-left: 4px solid var(--layer-comp-ai-border); background: var(--layer-comp-ai-bg); color: var(--global-text-color);
                   padding: 1em 1.5em; border-radius: 0 8px 8px 0;">
        <h4 style="color: var(--layer-comp-ai-heading);">AI Component Layer</h4>
        <p>
        How to provide reliability and robustness guarantees by design for AI components, including prompting, agentic architecture, and decoding strategies (<a href="https://arxiv.org/pdf/2605.30054">FSE'26 IVR</a>).
        </p>
      </div>

    </div>

    <!-- Model Layer -->
    <div style="border-left: 4px solid var(--layer-model-border); background: var(--layer-model-bg); color: var(--global-text-color);
                 padding: 1em 1.5em; border-radius: 0 8px 8px 0; margin: 0.5em 0 0 4em;">
      <h4 style="color: var(--layer-model-heading);">Model Layer</h4>
      <p>
      Open the black box of AI models to understand their properties and behaviors (<a href="https://arxiv.org/pdf/2405.08645">DMKD 2026</a>) or improve the neural architectures (<a href="https://dl.acm.org/doi/pdf/10.1145/3715773">FSE'25</a>).
      </p>
    </div>

  </div>

----

I also organize a bi-weekly (sometimes weekly) _discussion group on graph models_ and their applications. You can find the scedules [here](https://boqi-chen.notion.site/dg-graph?pvs=32). If you are interested in joining, please subscribe to this [calendar](https://lu.ma/gnn-discussion-group). We are also actively looking for new speakers, so if you are interested in presenting your work or any topics you are interested in, please feel free to reach out to me.
