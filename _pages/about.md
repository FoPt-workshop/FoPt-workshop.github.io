---
layout: about
title: About
permalink: /
subtitle: A <a href='https://learningtheory.org/colt2026/'>COLT 2026</a> workshop<br> June 29th, 2026 in San Diego, USA

profile:
  align: top
  image: fopt-bw.png
  image_circular: false # crops the image to make it circular
  more_info:

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts

speaker_horizontal: false
organizer_horizontal: true
---

Welcome to the homepage of the second workshop on the Foundations of Post-training (FoPt 2026). FoPt is located at COLT 2026 and will be organized in San Diego, USA on the 29th of June, 2026. This workshop seeks to explore the theoretical and practical aspects of post-training and reasoning in LLMs, across a diversity of domains and abstractions. The workshop aims to bring together experts from diverse theoretical and practical areas to identify critical research opportunities.

As a part of FoPt 2026, we invite abstract submissions to a single non-archival track. See our [call for abstracts](https://fopt-workshop.github.io/cfp/) for more details. The submission deadline is **Saturday, June 13th, 2026**.<br>

## Workshop details

**Date:** Monday, 29th June, 2026 <br>
**Location:** Bahia Resort, San Diego, USA <br>
<!-- **Schedule:** <br>

| **Duration** |                              **Talk**                               |
| :----------: | :---------------------------------------------------------------------: |
|  35 + 5 min  | [Niladri Chatterji](https://niladri-chatterji.github.io/) |
|  35 + 5 min  |    Invited talk: [Aviral Kumar](https://aviralkumar2907.github.io/)     |
|  35 + 5 min  |       Invited talk: [Zak Mhammedi](https://www.zakmhammedi.com/)        | -->

Detailed schedule TBD.

<br>

## Invited Speakers

{% assign sorted_speakers = site.speakers | sort: "importance" %}

<div style="margin-top: 20px; display: flex; gap: 20px; flex-wrap: wrap; justify-content: center">
  {% for speaker in sorted_speakers %}
    {% include speakers.liquid %}
  {% endfor %}
</div>
<br><br>

## Organizers

{% assign sorted_organizers = site.organizers | sort: "importance" %}

<div style="margin-top: 20px; display: grid; grid-template-columns: repeat(2, max-content); gap: 20px; justify-content: center;">
  {% for organizer in sorted_organizers %}
    {% include organizers.liquid %}
  {% endfor %}
</div>
<br><br>
