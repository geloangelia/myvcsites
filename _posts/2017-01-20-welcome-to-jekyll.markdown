---
layout: post
title:  "Venture Capital!"
date:   2017-01-20 22:54:29 +0800
categories: jekyll update
---

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
  </tr>
{% endfor %}
</table>
