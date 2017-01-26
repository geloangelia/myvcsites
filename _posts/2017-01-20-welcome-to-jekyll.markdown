---
layout: post
title:  "Venture Capital!"
date:   2017-01-20 22:54:29 +0800
categories: jekyll update
---

Francis Angelo G

<table>
{% for list in site.data.vclist %}
  <tr>
   <td>
        {{ list.No }}
    </td>
     <td>
        {{ list.Name }}
    </td>
      <td>
        {{ list.Type }}
    </td>
    <td>
        {{ list.3 Year Funds Offered }}
    </td>
  </tr>
{% endfor %}
</table>
