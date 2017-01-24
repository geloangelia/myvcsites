---
layout: post
title:  "Venture Capital!"
date:   2017-01-20 22:54:29 +0800
categories: jekyll update
---
  
  <dl>
  {% for items in site.data.vclist %}
  <dt>{{ items.No }}</dt>
    {% end for %}
    
      {% for items in site.data.vclist %}
  <dd>{{ items.Name }}</dd>
  {% end for %}
</dl>

<table>
  <thead>
    <tr>
    {% for header in site.data.vclist.keys %}
      <td>{{header}}</td>
    {% endfor %}
    </tr>
  </thead>
  <tbody>
    {% for row in site.data.vclist.content %}
    <tr>
    {% for column in row %}
      <td>{{column}}</td>
    {% endfor %}
    </tr>
    {% endfor %}
  </tbody>
</table>
