---
layout: about
title: about
permalink: /
subtitle: A <a href='https://learningtheory.org/colt2025/'>COLT 2025</a> workshop<br> June 30th, 2025 in <a href='https://www.ens-lyon.fr/'>Lyon, France</a>

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

Welcome to the homepage of the first workshop on the Foundations of Post-training (FoPt 2025). FoPt is located at COLT 2025 and will be organized in the beautiful city of Lyon, France on the 30th of June, 2025. This workshop seeks to explore the theoretical and practical aspects of the post-training of LLMs, across a diversity of domains and abstractions. The workshop aims to bring together experts from diverse fields including theoretical reinforcement learning, optimization, statistical learning theory, as well as more empirical directions, to identify critical research opportunities.

As a part of FoPt 2025, we invite abstract submissions to a single non-archival track. See our [call for abstracts](https://fopt-workshop.github.io/cfp/) for more details. The submission deadline is **Monday, May 19th, 2025**.

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
<div style="margin-top: 20px; display: flex; gap: 20px; flex-wrap: wrap; justify-content: center">
  {% for organizer in sorted_organizers %}
    {% include organizers.liquid %}
  {% endfor %}
</div>
<br><br>
