---
layout: about
title: about
permalink: /
subtitle: McGill University #<a href='#'>Affiliations</a>. Address. Contacts. Moto. Etc.

profile:
  align: right
  image: boqi_chen.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>email: boqi⚫chen@mail⚫mcgill⚫ca</p>

news: true # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---
>✨ I will be joining the University of Ottawa as a tenure-track Assistant Professor in [the School of Electrical Engineering and Computer Science (EECS)](https://www.uottawa.ca/faculty-engineering/school-electrical-engineering-computer-science) starting May 2026!
> If you are interested in working with me, please feel free to reach out!

I received my PhD from the [Department of Electrical and Computer Engineering](https://www.mcgill.ca/ece/) at McGill University, supervised by [Prof. Gunter Mussbacher](https://www.ece.mcgill.ca/~gmussb1/) and [Prof. Daniel Varro](https://liu.se/en/employee/danva91). My research focuses on the reliable and robust integration of AI components, including LLMs, in software engineering applications, with an emphasis on model-based validation techniques and principled agentic workflow design. I am also broadly interested in evaluating the quality and properties of ML models for software engineering tasks such as code generation, bug detection, and code summarization.

During my PhD, I worked as an R&D engineer at [Aggregate Intellect](https://www.ai.science/) through a Mitacs grant and as a part-time research associate at _Huawei Waterloo Research Center_. I was also an active contributor to the open-source project [Sherpa](https://github.com/Aggregate-Intellect/sherpa), a large language model framework for robust agentic applications.

I believe reliable and robust integration of AI components requires a layered approach, as illustrated below.
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
        <h4 style="color: var(--layer-comp-sw-heading);">Traditional Software Component</h4>
        <p>
        Create reliable software components that wrap around AI components to provide assurance, guarantees and fallback mechanisms (<a href="https://marussy.com/papers/ase22.pdf">ASE'22</a>, <a href="https://arxiv.org/pdf/2506.16639">RE'25</a>, <a href="https://arxiv.org/pdf/2508.00255">MODELS'25</a>)
        </p>
      </div>

      <div style="flex: 1; border-left: 4px solid var(--layer-comp-ai-border); background: var(--layer-comp-ai-bg); color: var(--global-text-color);
                   padding: 1em 1.5em; border-radius: 0 8px 8px 0;">
        <h4 style="color: var(--layer-comp-ai-heading);">AI Component</h4>
        <p>
        How to provide reliability and robustness guarantees by design for AI components, including prompting, agentic architecture, and decoding strategies.
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

I also organize a bi-weekly (sometimes weekly) _discussion group on graph neural networks_ and their applications. You can find the scedules [here](https://boqi-chen.notion.site/dg-graph?pvs=32). If you are interested in joining, please subscribe to this [calendar](https://lu.ma/gnn-discussion-group). We are also actively looking for new speakers, so if you are interested in presenting your work or any topics you are interested in, please feel free to reach out to me.

<!-- Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](http://reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder. -->

<!-- Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically. -->

<!-- Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. -->
