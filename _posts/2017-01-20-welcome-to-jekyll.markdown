---
layout: post
title:  "Venture Capital!"
date:   2017-01-20 22:54:29 +0800
categories: jekyll update
---

Francis Angelo G

<table>
{% for member in site.data.vclist %}
  <tr>
    <td>
        {{ member.Est.MostRecentFundDate }}
    </td>
    <td>
        {{ member.InvestorLocation }}
    </td>
    <td>
        {{ member.InvestorCity }}
    </td>
  </tr>
{% endfor %}
</table>
