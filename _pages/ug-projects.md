---
layout: page
permalink: /ug-projects/
title: undergraduate projects
description: Project course opportunities for uOttawa undergraduate students.
nav: false
---

<style>
  .ugp-section-note {
    color: var(--global-text-color-light);
    margin-top: -0.4em;
  }

  .ugp-card {
    border: 1px solid var(--global-divider-color);
    border-left: 4px solid var(--global-theme-color);
    border-radius: 8px;
    background: var(--global-card-bg-color);
    padding: 1.1em 1.4em;
    margin: 1em 0;
  }
  .ugp-card.filled { border-left-color: var(--global-divider-color); opacity: 0.7; }
  .ugp-card h3 { margin: 0 0 0.4em 0; font-size: 1.15rem; }
  .ugp-card p { margin-bottom: 0.6em; }
  .ugp-card ul { margin-bottom: 0.6em; padding-left: 1.2em; }
  .ugp-card .ugp-label { font-weight: 600; font-size: 0.9rem; }

  .ugp-pill {
    display: inline-block;
    vertical-align: middle;
    font-size: 0.75rem;
    font-weight: normal;
    line-height: 1.6;
    padding: 0 0.65em;
    border-radius: 999px;
    border: 1px solid var(--global-divider-color);
    color: var(--global-text-color-light);
  }

  .ugp-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 1em;
    margin: 1em 0;
  }
  .ugp-grid .ugp-card { margin: 0; border-left-width: 1px; }
  .ugp-grid .ugp-card h3 { font-size: 1.05rem; }

  .ugp-subject {
    font-family: monospace;
    background: var(--global-code-bg-color);
    border-left: 4px solid var(--global-theme-color);
    border-radius: 0 6px 6px 0;
    padding: 0.6em 1em;
    margin: 1em 0;
    font-size: 0.95rem;
  }
</style>

If you are interested in doing an undergraduate project course with me (e.g., SEG 3904 or CSI 4900), browse the projects or one of the long-term research ideas below, then [email me](#contact). If none of them fit, you are welcome to propose your own idea.

---

## Open Projects

<p class="ugp-section-note">I am actively looking for students for these projects.</p>

{% for p in site.data.ug_projects.active %}
<div class="ugp-card{% if p.status == 'filled' %} filled{% endif %}">
  <h3>{% if p.link %}<a href="{{ p.link }}" target="_blank" rel="noopener">{{ p.title }}</a>{% else %}{{ p.title }}{% endif %}{% if p.status == 'filled' %} <span class="ugp-pill">Filled</span>{% endif %}</h3>
  {{ p.summary | markdownify }}
  {% if p.tasks %}
  <span class="ugp-label">What you'll do</span>
  <ul>{% for t in p.tasks %}<li>{{ t | markdownify | remove: '<p>' | remove: '</p>' }}</li>{% endfor %}</ul>
  {% endif %}
</div>
{% else %}
<p><em>No open projects right now. Have a look at the research directions below, or bring your own idea.</em></p>
{% endfor %}

---

## Ongoing Research Directions

<p class="ugp-section-note">Long-term efforts that are always open to new contributors. We will scope a semester-sized piece together.</p>

<div class="ugp-grid">
{% for p in site.data.ug_projects.ongoing %}
  <div class="ugp-card">
    <h3>{% if p.link %}<a href="{{ p.link }}" target="_blank" rel="noopener">{{ p.title }}</a>{% else %}{{ p.title }}{% endif %}</h3>
    {{ p.summary | markdownify }}
  </div>
{% endfor %}
</div>

{% if site.data.ug_projects.past.size > 0 %}
---

## Past Projects

{% for p in site.data.ug_projects.past %}
- **{{ p.title }}**{% if p.students %} by {{ p.students }}{% endif %}{% if p.term %} ({{ p.term }}){% endif %}{% if p.link %} · [link]({{ p.link }}){% endif %}
{% endfor %}
{% endif %}

---

## How to Apply {#contact}

Send me an email at **boqi⚫chen@uottawa⚫ca** with the subject line:

<div class="ugp-subject">[UG Project] &lt;SEG 3904/CSI 4900&gt; &lt;Term&gt; — &lt;Your Name&gt;</div>

Please include:

- The project(s) you are interested in, and why
- Your unofficial transcript
- Relevant experience: courses, side projects, internships, or a GitHub link
- The term you plan to take the course

> 💡 **Have your own idea?** I'm happy to supervise student-proposed projects that relate to AI and software engineering. Describe the problem and what you would like to build or study in a few sentences, and we can shape it into a project together.
{: .block-tip }
