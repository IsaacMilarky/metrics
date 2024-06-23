---
layout: org-report
title: Open Source at CMS Metrics Report for CMSgov | REPORT-2024-06-23
permalink: /CMSgov/

org: CMSgov
reportID: REPORT-2024-06-23
date_stampThisWeek: 2024-06-23
date_stampLastWeek: 2024-06-23
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
        <td>52702</td>
        <td>52692</td>
        <td style="color: #45c527" >10</td>
        <td style="color: #45c527" >0.019%</td>
      </tr>
      <tr>
        <th scope="row">Issues</th>
        <td>914</td>
        <td>914</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Open Issues</th>
        <td>127</td>
        <td>127</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Closed Issues</th>
        <td>787</td>
        <td>787</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Open Pull Requests</th>
        <td>244</td>
        <td>243</td>
        <td style="" >1</td>
        <td style="" >0.41%</td>
      </tr>
      <tr>
        <th scope="row">Merged Pull Requests</th>
        <td>18669</td>
        <td>18659</td>
        <td style="color: #45c527" >10</td>
        <td style="color: #45c527" >0.054%</td>
      </tr>
      <tr>
        <th scope="row">Closed Pull Requests</th>
        <td>4159</td>
        <td>4159</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Forks</th>
        <td>572</td>
        <td>572</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Stars</th>
        <td>1383</td>
        <td>1382</td>
        <td style="color: #45c527" >1</td>
        <td style="color: #45c527" >0.072%</td>
      </tr>
      <tr>
        <th scope="row">Watchers</th>
        <td>1780</td>
        <td>1780</td>
        <td style="" >0</td>
        <td style="" >0%</td>
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