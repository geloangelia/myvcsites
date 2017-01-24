---
layout: post
title:  "Venture Capital!"
date:   2017-01-20 22:54:29 +0800
categories: jekyll update
---


<ul>
   {% for items in site.data.vclist %}
   <li>{{ items.No }} </li>
   <li>{{ items.Name }} </li>
  {% end for %}
  </ul>

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
