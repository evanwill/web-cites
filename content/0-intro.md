---
title: Why?
nav: true
lazyload: true
---

# Introduction to Web Archiving

Content on the web is in constant flux: rapidly appearing, updating, and disappearing. 

{% include figure.html img="sam-erwin-q78PYnUehV8-unsplash.jpg" alt="spider web" %}

In some cases these are intentionally time-limited, spontaneous, or ephemeral cultural artifacts that may still hold enduring value and relevance to the historical record.
Others are seemingly stable pages which through a gradual process of theme, data, and platform updates become inadvertently broken or altered.

As the web becomes the primary means of disseminating information this flux can have negative impacts on the sustainability of your data and sources--disrupting the system of citation which validates claims made in research.
For example, a survey of journal articles in 2015 found that: 

> "Over 50% of cited links in Supreme Court opinions no longer point to the intended page. Roughly 70% of cited links in academic legal journals and 20% of all science, technology and medicine articles suffer from link rot." ([Perma.cc](https://perma.cc/))

For decades libraries and archives around the world have been working on the challenge of preserving web resources for current and future generations.
As with all digital information, it is at-risk without active [digital preservation](https://en.wikipedia.org/wiki/Digital_preservation) measures (see [Why Digital Preservation is Important for Everyone](https://youtu.be/qEmmeFFafUs)).
As a solution, libraries have developed harvesting, storage, and access techniques to build web archives.

## Why Web Archive?

Preserving your web citations in a web archive avoids two main issues:

1. Link Rot -- when a given link breaks, pointing to nothing or the wrong page.
2. Reference Rot / Content Drift -- when content on page at a given link has changed, no longer matching the original citation.

Citation is intended to provide evidence of claims made in a paper attesting to the integrity of your research. 
However, with live web content a quote you cite might be deleted, data you used might be altered, or a link redirected to a new (even malicious) location.

Perma.cc provides this basic example that illustrates the idea: 

> Suppose you're a professor working on an article and you want to link to the FBI's Top Ten Most Wanted List. Because that list changes over time, your link is going to rot and your future readers won't be able to access your actual source at the original URL. That's bad for you and your readers.
>
> But if you give Perma.cc the web address - e.g. http://www.fbi.gov/wanted/topten - our software will visit the page, make a record of it and give you a unique URL that points to the preserved record - e.g. perma.cc/T8U2-994F.
> 
> You can add the new Perma Link to your citation, and your future readers will be able to access the intended source no matter what happens to the original page.

Keep in mind that some web resources are difficult to capture, will display anomalies when removed from the live web, or intentionally prevent archiving. 
Social media streams, paywalled resources, streaming videos, and 3rd party embeds are unlikely to be correctly captured.
Some sites add a "noarchive" metatag or "robots.txt" exclusion that explicitly ask archives to not capture their content.
Tools such as [Conifer](https://conifer.rhizome.org/) and [Webrecorder](https://webrecorder.net/tools) can sometimes help avoid issues with this sort of archival preservation.
