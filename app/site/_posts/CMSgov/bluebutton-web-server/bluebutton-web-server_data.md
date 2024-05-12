---
layout: repo-report
title: Open Source at CMS Metrics Report for bluebutton-web-server | REPORT-2024-05-12
permalink: /CMSgov/bluebutton-web-server/

org: CMSgov
repo: bluebutton-web-server
reportID: REPORT-2024-05-12
date_stampThisWeek: 2024-05-12
date_stampLastWeek: 2024-05-12
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
        <td>3470</td>
        <td>3466</td>
        <td style="color: #45c527" >4</td>
        <td style="color: #45c527" >0.12%</td>
      </tr>
      <tr>
        <th scope="row">Issues</th>
        <td>26</td>
        <td>26</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Open Issues</th>
        <td>0</td>
        <td>4</td>
        <td style="color: #45c527" >-4</td>
        <td style="color: #45c527" >200%</td>
      </tr>
      <tr>
        <th scope="row">Closed Issues</th>
        <td>26</td>
        <td>22</td>
        <td style="color: #45c527" >4</td>
        <td style="color: #45c527" >17%</td>
      </tr>
      <tr>
        <th scope="row">Open Pull Requests</th>
        <td>4</td>
        <td>9</td>
        <td style="color: #45c527" >-5</td>
        <td style="color: #45c527" >77%</td>
      </tr>
      <tr>
        <th scope="row">Merged Pull Requests</th>
        <td>960</td>
        <td>956</td>
        <td style="color: #45c527" >4</td>
        <td style="color: #45c527" >0.42%</td>
      </tr>
      <tr>
        <th scope="row">Closed Pull Requests</th>
        <td>206</td>
        <td>200</td>
        <td style="" >6</td>
        <td style="" >3%</td>
      </tr>
      <tr>
        <th scope="row">Forks</th>
        <td>24</td>
        <td>24</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Stars</th>
        <td>37</td>
        <td>37</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Watchers</th>
        <td>25</td>
        <td>25</td>
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
    {% render "graph-section"  baseurl: site.baseurl, path: "/CMSgov/bluebutton-web-server/issue_gauge_bluebutton-web-server_data.svg", title: "Issues & PRs Status Breakdown" %}
    <!--- Contributor Activity Line Graph -->
    {% render "graph-section" baseurl: site.baseurl, path: "/CMSgov/bluebutton-web-server/commit_sparklines_bluebutton-web-server_data.svg", title: "Commits by Month" %}
    <!--- First Response For Closed PR Scatterplot -->
    {% render "graph-section" baseurl: site.baseurl, class: "firstResponsePRCrop", path: "/CMSgov/bluebutton-web-server/firstResponseForClosedPR_bluebutton-web-server_data.png", title: "First Response For Closed PR" %}
    <!--- Line Complexity Graphs -->
    {% render "graph-section" baseurl: site.baseurl, path: "/CMSgov/bluebutton-web-server/total_line_makeup_bluebutton-web-server_data.svg", title: "Line Complexity" %}
    <!--- New Commit Contributors by Day over Last Month and Last 6 Months -->
      {% assign optionsArray = '1 Month, 6 Month' | split: ',' %}
      {% assign graphsArray = '/CMSgov/bluebutton-web-server/new_commit_contributors_by_day_over_last_month_bluebutton-web-server_data.svg, /CMSgov/bluebutton-web-server/new_commit_contributors_by_day_over_last_six_months_bluebutton-web-server_data.svg' | split: ',' %}
      {% render "graph-toggle", baseurl: site.baseurl, name: "new-contributors" options: optionsArray, graphs: graphsArray, title: "Number of Contributors Joining per Interval" %}
</div>