---
layout: twocolumn

title: deneme
---

<div class="row">
  <div class="column" style="background-color:#aba;">

 <h3>Research</h3>
 <ul>
   {% for post in site.posts %}
     {% if post.category == 'outreach' %}
       <a href="{{ post.url }}"><span style="color:black">{{ post.title }}</span></a>
     {% endif %}
   {% endfor %}
 </ul>
 </div>
 <div class="column" style="background-color:#cbc;">
 <h3>Scribbles</h3>
 <ul>
 {% for post in site.posts %}
     {% if post.category == 'blog' %}
       <a href="{{ post.url }}"><span style="color:black">{{ post.title }}</span></a>
     {% endif %}
   {% endfor %}
 </ul>
 </div>
</div>




<!---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}"><span style="color:black">{{ post.title }}</span></a>
    </li>
  {% endfor %}
</ul>
-->

<!---
<iframe width="100%" height="120" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/113787209&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false&amp;visual=true"></iframe>
-->
