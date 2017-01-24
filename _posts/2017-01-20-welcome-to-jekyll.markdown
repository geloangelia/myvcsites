---
layout: post
title:  "Venture Capital!"
date:   2017-01-20 22:54:29 +0800
categories: jekyll update
---


<table style="margin:auto">
    <tr>
     {% for items in site.data.vclist %}
        <td>
            <ul>
                <li style="float:left;display:inline">{{ items.No }}</li>
            </ul>
        </td>
        
        <td>
            <ul>
                <li style="float:left;display:inline">{{ items.Name }}</li>
            </ul>
        </td>
         {% endfor %}
    </tr>
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
