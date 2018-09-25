---
title: UCSB CS Transfer Student Resources
---

<div id="about" data-role="collapsible" data-collapsed="true" markdown="1">
<h2>About this website</h2>

This website provides information for transfer students to provide a smooth transition into the Computer Science program.  Some of the information may also be of use to transfer students in Computer Engineering, and for that matter, to anyone taking course work in CS at UCSB.


</div><!-- about -->


<div id="topics" data-role="collapsible" data-collapsed="false">
  <h2>Topics</h2>
  <ul>
   {% for topic in site.topics %}
     <li {% if topic.indent %} class="indent" {% endif %}><a href="{{topic.url}}">{{ topic.topic }}</a>&mdash;{{topic.desc}}</li>
   {% endfor %}
  </ul>
</div>


<div id="resources" data-role="collapsible" data-collapsed="false">
  <h2>Resources</h2>
  <ul>
   {% for topic in site.resources %}
     <li {% if topic.indent %} class="indent" {% endif %}><a href="{{topic.url}}">{{ topic.topic }}</a>&mdash;{{topic.desc}}</li>
   {% endfor %}
  </ul>
</div>

