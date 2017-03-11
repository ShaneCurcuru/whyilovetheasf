---
layout: default
title:  "About Apache: Starting Points For Everything"
date:   2016-02-01 11:22:33
author: Shane Curcuru
categories: Info
image:  img/heart-1050338_1920.jpg
excerpt: A permuted index of topics at Apache
---

<!-- This post builds it's own grid of subjects from layout:default, not using article class=post-content -->
<div class="post-ribbon"></div>
<main class="post-main mdl-layout__content">
  <div class="post-container mdl-grid">
    <div class="post-section mdl-color--white mdl-shadow--4dp content mdl-color-text--grey-800 mdl-cell mdl-cell--1-offset mdl-cell--10-col">
      <article class="post-content">
        <div class="mdl-grid">

{% include card.html title="Welcome" content='<a href="http://community.apache.org/">Apache Community Development</a> is here to welcome and guide you.' size="mdl-card-small" %}

{% capture getcodecard %}
All project code at Apache is publicly available and in <a href="http://www.apache.org/dev/#version-control">Subversion or Git repositories</a>.
{% endcapture %}
{% include card.html title="Get Code" content=getcodecard size="mdl-card-small"%}

{% include card.html title="Find Technology" content='<a href="https://projects.apache.org/">List all 170+ Apache projects</a> and read the <a href="http://www.apache.org/dev/">developer information portal</a>.' size="mdl-card-small" %}

{% include card.html title="People" content='<a href="http://home.apache.org/">Apache committer directory and phonebook</a>, <a href="http://planet.apache.org/committers/">Planet Apache blog aggregator</a>.' size="mdl-card-small" %}

{% capture contactcard %}
Everything at Apache happens on <a href="http://www.apache.org/foundation/mailinglists.html">our mailing lists</a>.
Find the <a href="http://www.apache.org/dev/contrib-email-tips.html#rightlist">right list to use</a>.
<strong>Technical</strong> questions go to a project's dev@ list. Or, <a href="http://www.apache.org/foundation/contact">ask cross-project questions</a>.
<a href="http://mail-archives.apache.org/mod_mbox/">Read the public list archives</a>.
{% endcapture %}
{% include card.html title="How To Contact Anyone" content=contactcard size="mdl-card-small" %}


{% include card.html title="Legal Issues" content='The ASF uses the permissive <a href="http://www.apache.org/licenses/">Apache License, version 2.0</a>.  Legal questions go to the <a href="http://www.apache.org/legal/">Legal Affairs Committee</a>.' size="mdl-card-small" %}

{% include card.html title="Trademarks Are Important" content='The ASF <a href="http://www.apache.org/foundation/marks/">owns all Apache trademarks</a>. <a href="http://www.apache.org/foundation/marks/list/">All Apache project and software product names are trademarks</a>. Read <a href="http://www.apache.org/foundation/marks/resources">useful trademark resources</a>.' size="mdl-card-small" %}

{% include card.html title="Press, Analysts, Journalists" content='Our <a href="http://www.apache.org/press/">Media and Analyst relations team</a> runs <a href="https://twitter.com/TheASF">@TheASF on Twitter</a> and writes an <a href="https://blogs.apache.org/foundation/">official Foundation Blog</a>.' size="mdl-card-small" %}

{% include card.html title="Corporate Governance" content='The ASF is a <a href="http://www.apache.org/foundation/records/">501C3 non-profit public charity</a>, that relies on <a href="http://www.apache.org/foundation/contributing">individual donors</a> and <a href="http://www.apache.org/foundation/sponsorship">sponsors</a> for <a href="https://blogs.apache.org/foundation/entry/the_apache_software_foundation_asf">funding and budgets</a>.  Members elect a <a href="http://www.apache.org/foundation/">Board of Directors</a> that appoints Officers. Read our <a href="http://www.apache.org/foundation/governance/">governance overview and org chart</a>.' size="mdl-card-small" %}

{% include card.html title="Infrastructure Team &amp; Tools" content='The crack <a href="http://www.apache.org/dev/#infrastructure">Apache Infrastructure team</a> runs everything, and protects our servers from rogue gnomes.' size="mdl-card-small" %}

{% include card.html title="The Apache WAy" content='Learn about <a href="http://theapacheway.com/">The Apache Way</a>, the community-led consensus techniques that make Apache projects so efficient and long-lived.' size="mdl-card-small" %}

{% capture yourcard %}
Have another useful explanation or link? <a href="{{ site.github_forkurl }}">PR me on github</a>!
{% endcapture %}
{% include card.html title="Your Ideas" content=yourcard size="mdl-card-small" %}

        </div><!-- first mdl-grid -->
      </article>
    </div><!-- post-section -->
  </div><!-- post-container mdl-grid" -->
</main>
