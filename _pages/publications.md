---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

中文版成果清单：[我的荟知学术主页](http://www.huezhi.com/profile/XmL4kc51Npn7oak4l51BU55q_GCz-pt4Kwdh4t87QPP7TrnRh_E9pxM5HGmdxvut)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
