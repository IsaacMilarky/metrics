---
layout: org-report
title: Open Source at CMS Metrics Report for CMSgov | REPORT-2024-07-21
permalink: /CMSgov/

org: CMSgov
reportID: REPORT-2024-07-21
date_stampThisWeek: 2024-07-21
date_stampLastWeek: 2024-07-21
---
<div class="summary-table">
  <table class="usa-table usa-table--borderless">
    <h2> Summary Table </h2>
    <thead>
      <tr>
        <th scope="col">Metric</th>
        <th scope="col">Latest</th>
        <th scope="col">Previous</th>
        <th scope="col">Diff</th>
        <th scope="col">% Diff</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th scope="row">Commits</th>
        <td>53065</td>
        <td>52867</td>
        <td style="color: #45c527" >198</td>
        <td style="color: #45c527" >0.37%</td>
      </tr>
      <tr>
        <th scope="row">Issues</th>
        <td>922</td>
        <td>921</td>
        <td style="color: #45c527" >1</td>
        <td style="color: #45c527" >0.11%</td>
      </tr>
      <tr>
        <th scope="row">Open Issues</th>
        <td>107</td>
        <td>118</td>
        <td style="color: #45c527" >-11</td>
        <td style="color: #45c527" >9.8%</td>
      </tr>
      <tr>
        <th scope="row">Closed Issues</th>
        <td>815</td>
        <td>803</td>
        <td style="color: #45c527" >12</td>
        <td style="color: #45c527" >1.5%</td>
      </tr>
      <tr>
        <th scope="row">Open Pull Requests</th>
        <td>226</td>
        <td>239</td>
        <td style="color: #45c527" >-13</td>
        <td style="color: #45c527" >5.6%</td>
      </tr>
      <tr>
        <th scope="row">Merged Pull Requests</th>
        <td>18926</td>
        <td>18746</td>
        <td style="color: #45c527" >180</td>
        <td style="color: #45c527" >0.96%</td>
      </tr>
      <tr>
        <th scope="row">Closed Pull Requests</th>
        <td>4213</td>
        <td>4174</td>
        <td style="" >39</td>
        <td style="" >0.93%</td>
      </tr>
      <tr>
        <th scope="row">Forks</th>
        <td>563</td>
        <td>572</td>
        <td style="color: #d31c08" >-9</td>
        <td style="color: #d31c08" >1.6%</td>
      </tr>
      <tr>
        <th scope="row">Stars</th>
        <td>1382</td>
        <td>1390</td>
        <td style="color: #d31c08" >-8</td>
        <td style="color: #d31c08" >0.58%</td>
      </tr>
      <tr>
        <th scope="row">Watchers</th>
        <td>1775</td>
        <td>1781</td>
        <td style="color: #d31c08" >-6</td>
        <td style="color: #d31c08" >0.34%</td>
      </tr>
      <tr>
        <th scope="row">Followers</th>
        <td>30</td>
        <td>30</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
    </tbody>
  </table>
</div>
<div class="graph-container">
  <br>
  <h2>Activity Graphs</h2>
  <div class="all-graphs">
    <!--- Issues/PRs Status Breakdown Graph -->
    {% render "graph-section" baseurl: site.baseurl, path: "/CMSgov/CMSgov_issue_gauge.svg", title: "Issues & PRs Status Breakdown" %}
    <!-- New Issues over Last 6 Months -->
    {% render "graph-section" baseurl: site.baseurl, path: "/CMSgov/CMSgov_new_issues_by_day_over_last_six_months.svg", title: "New Issues over Last 6 Months" %}
  </div>
</div>