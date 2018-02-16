---
layout: default
title:  "About Apache: Starting Points For Every FAQ"
date:   2016-02-01 11:22:33
author: Shane Curcuru
categories: Info
image:  img/heart-1050338_1920.jpg
excerpt: Master FAQ of FAQs about Apache Anything
---

<!-- This post builds it's own grid of subjects from layout:default, not using article class=post-content -->
<div class="post-ribbon"></div>
<main class="post-main mdl-layout__content">
  <div class="post-container mdl-grid">
    <div class="post-section mdl-color--white mdl-shadow--4dp content mdl-color-text--grey-800 mdl-cell mdl-cell--1-offset mdl-cell--10-col">
      <article class="post-content">
      <h3>How To Find The Right FAQ</h3>
        <div class="mdl-grid">

{% include card.html title="Welcome" content='<a href="https://community.apache.org/">Apache Community Development</a> is here to welcome you; see <a href="https://lists.apache.org/list.html?dev@community.apache.org">past questions on the mailing list</a>.' size="mdl-card-small" %}

{% capture getcodecard %}
All Apache code is in our <a href="https://svn.apache.org/viewvc">Subversion</a> or <a href="https://github.com/apache/">Git</a> repositories. How to <a href="https://www.apache.org/dev/#version-control">Setup SVN or Git access</a>.
{% endcapture %}
{% include card.html title="Get Code" content=getcodecard size="mdl-card-small"%}

{% include card.html title="Find Projects" content='<a href="https://projects.apache.org/">See all 190+ Apache software projects</a> and read the <a href="https://www.apache.org/dev/">developer information portal</a>.' size="mdl-card-small" %}

{% include card.html title="Find People" content='Read the <a href="https://whimsy.apache.org/foundation/orgchart/">ASF Org Chart of officers</a>, lookup the <a href="https://home.apache.org/">Apache committer directory</a>, read <a href="https://planet.apache.org/committers/">Planet Apache blogs</a>.' size="mdl-card-small" %}

{% capture contactcard %}
Everything happens on <a href="https://www.apache.org/foundation/mailinglists.html">our mailing lists</a>.
Find the <a href="https://www.apache.org/dev/contrib-email-tips.html#rightlist">right list to use</a>.
<strong>Technical</strong> questions <strong>always</strong> go to a project's dev@ list. Or, <a href="https://www.apache.org/foundation/contact">ask cross-project questions</a>.
<a href="https://lists.apache.org/">Read all Apache mail archives</a>.
{% endcapture %}
{% include card.html title="Contact Us" content=contactcard size="mdl-card-small" %}


{% include card.html title="Legal Questions" content='Apache software uses the <a href="https://www.apache.org/licenses/">Apache License, version 2.0</a>.  Questions? <a href="https://www.apache.org/legal/">Contact the Legal Affairs Committee</a>. Apache PMCs with <em>specific</em> questions: <a href="https://issues.apache.org/jira/projects/LEGAL/">open a LEGAL Jira</a>.' size="mdl-card-small" %}

{% include card.html title="Trademark Questions" content='The ASF <a href="https://www.apache.org/foundation/marks/">owns Apache trademarks</a>, which includes <a href="https://www.apache.org/foundation/marks/list/">all Apache project and software product names and logos</a>. Read <a href="https://www.apache.org/foundation/marks/resources">useful trademark resources</a>.' size="mdl-card-small" %}

{% include card.html title="Press, Analysts, Journalists" content='Our <a href="https://www.apache.org/press/">Media and Analyst relations team</a> runs <a href="https://twitter.com/TheASF">@TheASF on Twitter</a> and writes an <a href="https://blogs.apache.org/foundation/">official Foundation Blog</a>.' size="mdl-card-small" %}

{% include card.html title="Corporate Governance" content='The ASF is a <a href="https://www.apache.org/foundation/records/">501C3 non-profit public charity</a>.  Members elect a <a href="https://www.apache.org/foundation/">Board of Directors</a> that <a href="https://whimsy.apache.org/foundation/orgchart/">appoints Officers</a>. Read about our <a href="https://www.apache.org/foundation/governance/">governance and org chart</a>.' size="mdl-card-small" %}

{% include card.html title="Infrastructure Team" content='The crack <a href="https://www.apache.org/dev/#infrastructure">Apache Infrastructure team</a> runs everything, and protects our servers from rogue gnomes; you can <a href="https://www.apache.org/dev/infra-contact#misdirected">contact Infra here</a>.' size="mdl-card-small" %}

{% include card.html title="The Apache Way" content='Learn about <a href="https://theapacheway.com/">The Apache Way</a>, our community-led consensus behaviors that make Apache projects so efficient and long-lived, or <a href="http://shaneslides.com/2017/04/History-Of-The-Apache-Way/">view presentations about the ApacheWay</a>.' size="mdl-card-small" %}

{% capture yourcard %}
Our non-profit relies on <a href="https://www.apache.org/foundation/contributing">individual Donors</a> and <a href="https://www.apache.org/foundation/sponsorship">annual Sponsors</a> for our<a href="https://blogs.apache.org/foundation/entry/the-apache-software-foundation-operations2">funding and budgets</a>. <a href="https://donate.apache.org/">Donate today!</a> (Often tax-deductible in the US!)
{% endcapture %}
{% include card.html title="Donate Today" content=yourcard size="mdl-card-small" %}

        </div><!-- first mdl-grid -->
        <p>Have another useful explanation or link, or a question not answered here? <a href="{{ site.github_forkurl }}">Submit a PR on github</a>!</p>
      </article>
    </div><!-- post-section -->
  </div><!-- post-container mdl-grid" -->
</main>
