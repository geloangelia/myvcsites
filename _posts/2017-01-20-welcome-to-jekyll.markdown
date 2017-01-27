---
layout: post
title:  "Venture Capital!"
date:   2017-01-20 22:54:29 +0800
categories: jekyll update
---
<h1>Venture Capital List.</h1>

<table align="left">
<thead align="left">
      <tr>
          <th>No</th>
          <th>Name</th>
          <th>Type</th>
          <th>3 Year Funds Offered</th>
          <th>3 Year Funds Sold</th>
          <th>Est Most Recent Fund Date</th>
          <th>Investor Location</th>
          <th>Investor City</th>
          <th>Investor State</th>
          <th>Investor Country</th>
          <th>Portfolio Size</th>
          <th>Number of Deals</th>
          <th>Website</th>
          <th>Average Growth Score</th>
      </tr>
  </thead>
  <tbody align="left">
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
  </tbody>
</table>
