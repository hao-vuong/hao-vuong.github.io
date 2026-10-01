---
layout: about
title: about
permalink: /
# subtitle: >
#       BSc in Computer Science at <a href='https://vinuni.edu.vn/'>VinUniversity</a> <br>
#       Research Intern at <a href='https://xulabs.github.io/'>Xu Lab @ Carnegie Mellon University</a>
profile:
  align: right
  image: onebeer.jpg
  image_circular: false # crops the image to make it circular
  more_info:  >
     <p><a href="mailto:22hao.vc@vinuni.edu.vn">22hao.vc@vinuni.edu.vn</a></p>


selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts

#  Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

# Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below.

---

<!-- <div class="desc">
  BSc in Computer Science at <a href='https://vinuni.edu.vn/'>VinUniversity</a> <br>
  Research Intern at <a href='https://xulabs.github.io/'>Xu Lab @ Carnegie Mellon University</a>
</div>
<br> -->

BSc in Computer Science at <a href='https://vinuni.edu.vn/'>VinUniversity</a> <br>
Research Intern at <a href='https://xulabs.github.io/'>Xu Lab @ Carnegie Mellon University</a>

I am an undergraduate at [VinUniversity](https://vinuni.edu.vn/), advised by [Prof. Laurent El Ghaoui](https://people.eecs.berkeley.edu/~elghaoui/) and [Prof. Wray Buntine](https://bayesian-models.org/). Currently, I am doing research at [Xu Lab](https://xulabs.github.io/) on embodied AI for autonomous laboratories under [Prof. Min Xu](https://xulabs.github.io/min-xu/). Before this, I did research on 3D Vision with [Boying Li](https://leeby68.github.io/) at [VL4AI Lab](https://vl4ai.erc.monash.edu/index.html) under supervision of [Prof. Hamid Rezatofighi](https://research.monash.edu/en/persons/hamid-rezatofighi).

I aspire to explore that certain internal ”space” of imagination in each of our own minds that only us can ”see” ourselves. AI has excelled at perceiving what is in front of its eyes, but how about behind its mind? I am curious how robots can simulate their own world dynamics in 2D and 3D to infer counterfactuals. Once robots can simulate real physical dynamics correctly, where do we go after? Can we embrace hallucination and expect artificial creativity to emerge? Through my lens, creativity comes after reality. It is only truly defined after one acknowledges reality and decides to go beyond it. <span style="color: var(--global-theme-color);">My motivation in this field is the curiosity in our own minds and our sense of imagination, which is the core of each individual and what defines intelligence, intuition and personality.</span>

<blockquote style="font-size: 1.10rem;">
  Imagination is more important than knowledge. For knowledge is limited,<br>
  whereas imagination embraces the entire world, stimulating progress, giving birth to evolution.<br>
  <footer class="blockquote-footer">Albert Einstein, <cite title="Source Title">Cosmic Religion, 1931</cite></footer>
</blockquote>

<div class="mobile-mail">
  📩 Contact: <a href="mailto:22hao.vc@vinuni.edu.vn">22hao.vc@vinuni.edu.vn</a>
</div>

<!-- <blockquote>
  Imagination is more important than knowledge. <br>
  For knowledge is limited, whereas imagination embraces the entire world, stimulating progress, giving birth to evolution <br>
  Albert Einstein, Cosmic Religion, 1931
</blockquote> -->

<!-- <blockquote>
  Imagination is more important than knowledge.<br>
  For knowledge is limited... while imagination embraces the entire world.<br>
  Albert Einstein
</blockquote> -->

<!-- 📩 Contact: [22hao.vc@vinuni.edu.vn](22hao.vc@vinuni.edu.vn) -->

<!-- {% include bib_search.liquid %} -->

<div class="publications">

<!-- <h2>publications</h2> -->

{% bibliography %}

</div>

<!-- <h2>projects</h2>
<div class="projects">
  {% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
</div> -->

<style>
  .mobile-mail {
    display: none;
  }
  
  @media (max-width: 576px) {
    .profile {
      display: none !important;
    }
    .mobile-mail {
      display: block;
      margin-top: 15px;
    }
  }
</style>