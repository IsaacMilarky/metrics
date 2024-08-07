---
layout: repo-report
title: Open Source at CMS Metrics Report for metrics | REPORT-2024-07-21
permalink: /DSACMS/metrics/

org: DSACMS
repo: metrics
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
        <td>933</td>
        <td>926</td>
        <td style="color: #45c527" >7</td>
        <td style="color: #45c527" >0.75%</td>
      </tr>
      <tr>
        <th scope="row">Issues</th>
        <td>34</td>
        <td>34</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Open Issues</th>
        <td>23</td>
        <td>24</td>
        <td style="color: #45c527" >-1</td>
        <td style="color: #45c527" >4.3%</td>
      </tr>
      <tr>
        <th scope="row">Closed Issues</th>
        <td>11</td>
        <td>10</td>
        <td style="color: #45c527" >1</td>
        <td style="color: #45c527" >9.5%</td>
      </tr>
      <tr>
        <th scope="row">Open Pull Requests</th>
        <td>13</td>
        <td>4</td>
        <td style="" >9</td>
        <td style="" >110%</td>
      </tr>
      <tr>
        <th scope="row">Merged Pull Requests</th>
        <td>129</td>
        <td>127</td>
        <td style="color: #45c527" >2</td>
        <td style="color: #45c527" >1.6%</td>
      </tr>
      <tr>
        <th scope="row">Closed Pull Requests</th>
        <td>14</td>
        <td>14</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Forks</th>
        <td>2</td>
        <td>2</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Stars</th>
        <td>6</td>
        <td>6</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Watchers</th>
        <td>6</td>
        <td>5</td>
        <td style="color: #45c527" >1</td>
        <td style="color: #45c527" >18%</td>
      </tr>
    </tbody>
  </table>
</div>
<div class="graph-container">
  <br>
  <h2>Activity Graphs</h2>
  <div class="all-graphs">
    <!--- Issues/PRs Status Breakdown Graph -->
    {% render "graph-section"  baseurl: site.baseurl, path: "/DSACMS/metrics/issue_gauge_metrics_data.svg", title: "Issues & PRs Status Breakdown" %}
    <!--- Contributor Activity Line Graph -->
    {% render "graph-section" baseurl: site.baseurl, path: "/DSACMS/metrics/commit_sparklines_metrics_data.svg", title: "Commits by Month" %}
    <!--- First Response For Closed PR Scatterplot -->
    {% render "graph-section" baseurl: site.baseurl, class: "firstResponsePRCrop", path: "/DSACMS/metrics/firstResponseForClosedPR_metrics_data.png", title: "First Response For Closed PR" %}
    <!--- Line Complexity Graphs -->
    {% render "graph-section" baseurl: site.baseurl, path: "/DSACMS/metrics/total_line_makeup_metrics_data.svg", title: "Line Complexity" %}
    <!--- New Commit Contributors by Day over Last Month and Last 6 Months -->
      {% assign optionsArray = '1 Month, 6 Month' | split: ',' %}
      {% assign graphsArray = '/DSACMS/metrics/new_commit_contributors_by_day_over_last_month_metrics_data.svg, /DSACMS/metrics/new_commit_contributors_by_day_over_last_six_months_metrics_data.svg' | split: ',' %}
      {% render "graph-toggle", baseurl: site.baseurl, name: "new-contributors" options: optionsArray, graphs: graphsArray, title: "Number of Contributors Joining per Interval" %}
</div>