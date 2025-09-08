---
show: true
width: 4
date: 2022-01-12 00:01:00 +0800
---

{% assign publications = include.publications %}
<div class="my-3 p-0 bg-white shadow-sm rounded-xl">
    <h6 class="border-bottom border-gray p-3 mb-0">
        {% if include.title %}{{ include.title }}{% else %} Blogs{% endif %} 
    </h6>
    {% for item in publications limit:include.limit %}
        {% include showcase/default/Blogs_item.html item=item first=false last=false %}    
    {% endfor %}
    <h6 class="d-block p-3 mt-0 text-right">
        <a href="{{ 'publications' | relative_url }}">All blogs <i class="fas fa-angle-double-right"></i></a>
    </h6>
</div>
