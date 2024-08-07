---
layout: repo-report
title: Open Source at CMS Metrics Report for design-system | REPORT-2024-07-21
permalink: /CMSgov/design-system/

org: CMSgov
repo: design-system
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
        <td>2279</td>
        <td>2265</td>
        <td style="color: #45c527" >14</td>
        <td style="color: #45c527" >0.62%</td>
      </tr>
      <tr>
        <th scope="row">Issues</th>
        <td>241</td>
        <td>241</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Open Issues</th>
        <td>5</td>
        <td>17</td>
        <td style="color: #45c527" >-12</td>
        <td style="color: #45c527" >110%</td>
      </tr>
      <tr>
        <th scope="row">Closed Issues</th>
        <td>236</td>
        <td>224</td>
        <td style="color: #45c527" >12</td>
        <td style="color: #45c527" >5.2%</td>
      </tr>
      <tr>
        <th scope="row">Open Pull Requests</th>
        <td>6</td>
        <td>8</td>
        <td style="color: #45c527" >-2</td>
        <td style="color: #45c527" >29%</td>
      </tr>
      <tr>
        <th scope="row">Merged Pull Requests</th>
        <td>2160</td>
        <td>2145</td>
        <td style="color: #45c527" >15</td>
        <td style="color: #45c527" >0.7%</td>
      </tr>
      <tr>
        <th scope="row">Closed Pull Requests</th>
        <td>648</td>
        <td>642</td>
        <td style="" >6</td>
        <td style="" >0.93%</td>
      </tr>
      <tr>
        <th scope="row">Forks</th>
        <td>84</td>
        <td>84</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Stars</th>
        <td>304</td>
        <td>302</td>
        <td style="color: #45c527" >2</td>
        <td style="color: #45c527" >0.66%</td>
      </tr>
      <tr>
        <th scope="row">Watchers</th>
        <td>57</td>
        <td>57</td>
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
    {% render "graph-section"  baseurl: site.baseurl, path: "/CMSgov/design-system/issue_gauge_design-system_data.svg", title: "Issues & PRs Status Breakdown" %}
    <!--- Contributor Activity Line Graph -->
    {% render "graph-section" baseurl: site.baseurl, path: "/CMSgov/design-system/commit_sparklines_design-system_data.svg", title: "Commits by Month" %}
    <!--- First Response For Closed PR Scatterplot -->
    {% render "graph-section" baseurl: site.baseurl, class: "firstResponsePRCrop", path: "/CMSgov/design-system/firstResponseForClosedPR_design-system_data.png", title: "First Response For Closed PR" %}
    <!--- Line Complexity Graphs -->
    {% render "graph-section" baseurl: site.baseurl, path: "/CMSgov/design-system/total_line_makeup_design-system_data.svg", title: "Line Complexity" %}
    <!--- New Commit Contributors by Day over Last Month and Last 6 Months -->
      {% assign optionsArray = '1 Month, 6 Month' | split: ',' %}
      {% assign graphsArray = '/CMSgov/design-system/new_commit_contributors_by_day_over_last_month_design-system_data.svg, /CMSgov/design-system/new_commit_contributors_by_day_over_last_six_months_design-system_data.svg' | split: ',' %}
      {% render "graph-toggle", baseurl: site.baseurl, name: "new-contributors" options: optionsArray, graphs: graphsArray, title: "Number of Contributors Joining per Interval" %}
</div>