---
layout: post
title:  "Venture Capital!"
date:   2017-01-20 22:54:29 +0800
categories: jekyll update
---

Francis Angelo

<table>
{% for member in site.data.vclist %}
  <tr>
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
