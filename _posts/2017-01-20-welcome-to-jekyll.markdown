---
layout: post
title:  "Venture Capital!"
date:   2017-01-20 22:54:29 +0800
categories: jekyll update
---

Francis

<table>
{% for member in site.data.vclist %}
  <tr>
    <td>
      {{ member.No }}
    </td>
    <td>
      {{ member.Name }}
    </td>
    <td>
        {{ member.Type }}
    </td>
     <td>
        {{ member.3 Year Funds Offered }}
    </td>
   <td>
        {{ member.3 Year Funds Sold }}
    </td>
    <td>
        {{ member.Est. Most Recent Fund Date }}
    </td>
    <td>
        {{ member.Investor Location }}
    </td>
    <td>
        {{ member.Investor City }}
    </td>
  </tr>
{% endfor %}
</table>
