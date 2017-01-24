---
layout: post
title:  "Venture Capital!"
date:   2017-01-20 22:54:29 +0800
categories: jekyll update
---


<table style="width:100%">
  <tr>
    <th>No.</th>
    <th>Name</th> 
    <th>Type</th>
  </tr>
  <tr>
   {% for items in site.data.vclist %}
    <td>{{ items.No }}</td>
    <td>{{ items.Name }}</td> 
    <td>{{ items.Name }}</td>
  </tr>
  {% end for %}
  </table>

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
