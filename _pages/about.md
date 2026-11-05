---
permalink: /
title: "Welcome!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a freelance, social science researcher specializing in data analysis and visualization; previous academic appointments include Clemson University, the Albert Einstein College of Medicine, and New York University. My research focuses on comparative European politics and political economy to develop a greater understanding of the causal mechanisms that effect political behavior and institutional change. I am a member of the [American Political Science Association](https://apsanet.org/) (APSA) and the [International Political Science Association](https://www.ipsa.org/) (IPSA).    

Updates
======
<style>
.home-update {
  display: flow-root;
}

.home-update img {
  float: left;
  width: 300px;
  height: 220px;
  object-fit: cover;
  object-position: 50% 25%;
  margin: 0 22px 14px 0;
  border: 1px solid #aaa;
  border-radius: 8px;
}

@media (max-width: 600px) {
  .home-update img {
    float: none;
    display: block;
    width: 100%;
    margin: 0 0 16px;
  }
}
</style>

<div class="home-update">
  <img
    src="https://github.com/user-attachments/assets/26bb0e05-6f9a-47c9-9026-6e318a903c22"
    alt="City skyline and historic buildings"
  >

  <p><strong>Your update title</strong></p>

  <p>
    Write your descriptive text here. Describe the location,
    event, or research update associated with the photograph.
  </p>

  <p>
    Add any further details here. Longer text will wrap
    alongside the photograph and continue beneath it.
  </p>
</div>


Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting
