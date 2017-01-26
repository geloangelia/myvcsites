---
layout: post
title:  "Venture Capital!"
date:   2017-01-20 22:54:29 +0800
categories: jekyll update
---

Francis Angelo GG

<table>
{% for list in site.data.vclists %}
  <tr>
   <td>
        {{ list.,No }}
    </td>
    <td>
        {{ list.,3 Year Funds Offered }}
    </td>
    <td>
        {{ list.3 Year Funds Sold }}
    </td>
    <td>
        {{ list.Est. Most Recent Fund Date }}
    </td>
  </tr>
{% endfor %}
</table>
