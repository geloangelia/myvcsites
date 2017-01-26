---
layout: post
title:  "Venture Capital!"
date:   2017-01-20 22:54:29 +0800
categories: jekyll update
---
Venture Capital List.

<table  align="left">
  <th>
   {{ Header }}
  </th>	
  <tr>
  {% for list in site.data.vclist %}
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
        {{ list.3YearFundsOffered }}
    </td>
    <td>
        {{ list.3YearFundsSold }}
    </td>
     <td>
        {{ list.EstMostRecentFundDate }}
    </td>
    <td>
        {{ list.InvestorLocation }}
    </td>
    <td>
        {{ list.InvestorCity }}
    </td>
      <td>
        {{ list.InvestorState }}
    </td>
     <td>
        {{ list.InvestorCountry }}
    </td>
     <td>
        {{ list.PortfolioSize }}
    </td>
       <td>
        {{ list.NumberofDeals }}
    </td>
    <td>
        {{ list.Website }}
    </td>
    <td>
        {{ list.AverageGrowthScore}}
    </td>
  </tr>
  {% endfor %}
</table>
