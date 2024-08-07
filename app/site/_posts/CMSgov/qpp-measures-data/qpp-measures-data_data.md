---
layout: repo-report
title: Open Source at CMS Metrics Report for qpp-measures-data | REPORT-2024-07-21
permalink: /CMSgov/qpp-measures-data/

org: CMSgov
repo: qpp-measures-data
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
        <td>1690</td>
        <td>1668</td>
        <td style="color: #45c527" >22</td>
        <td style="color: #45c527" >1.3%</td>
      </tr>
      <tr>
        <th scope="row">Issues</th>
        <td>17</td>
        <td>17</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Open Issues</th>
        <td>0</td>
        <td>0</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Closed Issues</th>
        <td>17</td>
        <td>17</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Open Pull Requests</th>
        <td>1</td>
        <td>0</td>
        <td style="" >1</td>
        <td style="" >200%</td>
      </tr>
      <tr>
        <th scope="row">Merged Pull Requests</th>
        <td>645</td>
        <td>638</td>
        <td style="color: #45c527" >7</td>
        <td style="color: #45c527" >1.1%</td>
      </tr>
      <tr>
        <th scope="row">Closed Pull Requests</th>
        <td>89</td>
        <td>89</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Forks</th>
        <td>46</td>
        <td>46</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Stars</th>
        <td>87</td>
        <td>87</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Watchers</th>
        <td>73</td>
        <td>73</td>
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
    {% render "graph-section"  baseurl: site.baseurl, path: "/CMSgov/qpp-measures-data/issue_gauge_qpp-measures-data_data.svg", title: "Issues & PRs Status Breakdown" %}
    <!--- Contributor Activity Line Graph -->
    {% render "graph-section" baseurl: site.baseurl, path: "/CMSgov/qpp-measures-data/commit_sparklines_qpp-measures-data_data.svg", title: "Commits by Month" %}
    <!--- First Response For Closed PR Scatterplot -->
    {% render "graph-section" baseurl: site.baseurl, class: "firstResponsePRCrop", path: "/CMSgov/qpp-measures-data/firstResponseForClosedPR_qpp-measures-data_data.png", title: "First Response For Closed PR" %}
    <!--- Line Complexity Graphs -->
    {% render "graph-section" baseurl: site.baseurl, path: "/CMSgov/qpp-measures-data/total_line_makeup_qpp-measures-data_data.svg", title: "Line Complexity" %}
    <!--- New Commit Contributors by Day over Last Month and Last 6 Months -->
      {% assign optionsArray = '1 Month, 6 Month' | split: ',' %}
      {% assign graphsArray = '/CMSgov/qpp-measures-data/new_commit_contributors_by_day_over_last_month_qpp-measures-data_data.svg, /CMSgov/qpp-measures-data/new_commit_contributors_by_day_over_last_six_months_qpp-measures-data_data.svg' | split: ',' %}
      {% render "graph-toggle", baseurl: site.baseurl, name: "new-contributors" options: optionsArray, graphs: graphsArray, title: "Number of Contributors Joining per Interval" %}
</div>