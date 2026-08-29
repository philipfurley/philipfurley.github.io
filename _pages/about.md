---
layout: about
title: about
permalink: /
subtitle: <a href='#'>German Sport University Cologne</a>. Institute of Exercise Training and Sport Informatics.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>+49 221 4982-4310>
    <p>Am Sportpark Müngersdorf 6</p>
    <p>50933 Köln, Germany</p>

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
---
<a href="mailto:p.furley@dshs-koeln.de">p.furley@dshs-koeln.de</a>

I am a professor (PD Dr.) at the German Sport University Cologne, where I serve as Deputy Head of the Institute of Exercise Training and Sport Informatics. My work has been recognized with the highest honor in German sport science—the DOSB Science Award—and is supported by major competitive grants, including funding from the German Research Foundation (DFG).

My research program advances our understanding of human emotion, nonverbal expressions, visual attention, and cognitive functioning under high pressure. A cornerstone of my work is the application of an in situ ethological approach within the rich, ecologically valid context of competitive sport. By taking psychological inquiry out of artificial laboratory environments and examining high-stakes athletic scenarios, my lab leverages sports as a naturalistic lens to decode fundamental principles of human psychology, affective processes, nonverbal communication, and executive functioning. Ultimately, this research seeks to bridge the gap between basic cognitive-affective science and real-world human performance, offering novel insights into how individuals adapt, communicate, and excel when stakes are high.

<!-- Selected papers section -->
{% if page.selected_papers %}
  <h2><a href="{{ '/publications/' | relative_url }}" style="color: inherit;">selected publications</a></h2>
  {% bibliography -f papers -q "@*[selected=true]" %}
{% endif %}
