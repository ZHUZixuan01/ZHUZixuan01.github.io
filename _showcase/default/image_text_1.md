---
show: true
width: 4
date: 2020-01-12 00:01:00 +0800
---
<div>
  <img data-src="{{ 'assets/images/covers/cover1.jpg' | relative_url }}" class="lazy w-100 rounded-xl" src="{{ '/assets/images/empty_300x200.png' | relative_url }}">

  <div class="card-img-overlay" style="overflow: scroll; background: rgb(255,255,255,0.8)">
    <h5 class="card-title">Bridge</h5>
    <p class="card-text">
      I'm an intermediate bridge player. I represented Germany at the World Youth Championship and did poorly T_T.
    </p>
    #<p class="card-text">
    #  {% raw %}
    #  <code>&lt;img data-src=&quot;[Image URL]&quot; class=&quot;lazy w-100 rounded-xl&quot; src=&quot;{{ '/assets/images/empty_300x200.png' | relative_url }}&quot;&gt;</code>
    #  {% endraw %}
    #</p>
  </div>
</div>
