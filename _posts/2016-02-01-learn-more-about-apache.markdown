---
layout: default
title:  "About Apache: Starting Points For Everything"
date:   2016-02-01 11:22:33
author: Shane Curcuru
categories: info
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

<div class="mdl-cell mdl-cell--3-col mdl-card mdl-shadow--4dp mdl-color-text--grey-800">
  <div class="mdl-card__title mdl-card__title-small"><h4 class="mdl-card__title-text">People</h4></div>
  <div class="mdl-card__supporting-text"><a href="http://home.apache.org/">Apache committer directory and phonebook.</a></div>
</div>

{% include card.html title="Welcome" content='<a href="http://community.apache.org/">Apache Community Development</a> is here to welcome and guide you.' %}

{% capture getcodecard %}
All project code at Apache is publicly available and in <a href="http://www.apache.org/dev/#version-control">Subversion or Git repositories</a>.
{% endcapture %}
{% include card.html title="Get Code" content=getcodecard size="mdl-card-small"%}

{% include card.html title="Find Technology" content='<a href="https://projects.apache.org/">List all 170+ Apache projects</a> and read the <a href="http://www.apache.org/dev/">developer information portal</a>.' %}

### How To Contact Anyone

Everything at Apache happens on [our many mailing lists](http://www.apache.org/foundation/mailinglists.html).
Finding the [right list to use](http://www.apache.org/dev/contrib-email-tips.html#rightlist) is important.  In particular, every Apache project has their own dev@/user@
mailing lists - **all** technical questions should be asked
on that project's list, not an overall Apache one.  Only for cross-project
issues should you contact a [top-level Apache address](http://www.apache.org/foundation/contact).

Most mailing lists are [publicly archived](http://mail-archives.apache.org/mod_mbox/).
          </div><!-- first mdl-grid -->

### Legal Issues

  Virtually everything the ASF produces is under the [Apache License, version 2.0](http://www.apache.org/foundation/contact).  Any questions about
  anything legal related go to the [Legal Affairs Committee](http://www.apache.org/legal/).

### Trademarks Are Important

  The ASF [owns all trademarks on behalf of Apache projects.](http://www.apache.org/foundation/marks/)  The name and
  logo of [every project and software product](http://www.apache.org/foundation/marks/list/) are trademarks or registered
  trademarks of the ASF.

### Press, Analysts, Journalists

  The ASF has an excellent [Media and Analyst relations team](http://www.apache.org/press/) that runs
  [@TheASF](https://twitter.com/TheASF) and the [official Foundation Blog](https://blogs.apache.org/foundation/).

### Corporate Governance

  The ASF is a [501C3 non-profit](http://www.apache.org/foundation/records/), membership corporation and public charity that relies on
  [individual donors](http://www.apache.org/foundation/contributing.html) and [sponsors](http://www.apache.org/foundation/sponsorship.html) for [funding and budgets](https://blogs.apache.org/foundation/entry/the_apache_software_foundation_asf).
  Our Members elect a [Board of Directors](http://www.apache.org/foundation/) that appoints Officers, and a detailed [governance overview and org chart](http://www.apache.org/foundation/governance/) is posted.

### Infrastructure Team &amp; Tools

  The crack [Apache Infrastructure team](http://www.apache.org/dev/#infrastructure) runs all the
  machines, clouds, and services used by the ASF and Apache projects.  Some projects
  run non-critical (testing, additional docs, etc.) resources for themselves.

      </article>
    </div><!-- post-section -->
  </div><!-- post-container mdl-grid" -->
</main>
