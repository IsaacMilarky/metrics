---
layout: org-report
title: Open Source at CMS Metrics Report for CMSgov | REPORT-2024-12-01
permalink: /CMSgov/

org: CMSgov
reportID: REPORT-2024-12-01
date_stampThisWeek: 2024-12-01
date_stampLastWeek: 2024-12-01
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
        <td>83</td>
        <td>54372</td>
        <td style="color: #d31c08" >-54289</td>
        <td style="color: #d31c08" >200%</td>
      </tr>
      <tr>
        <th scope="row">Issues</th>
        <td>0</td>
        <td>983</td>
        <td style="color: #d31c08" >-983</td>
        <td style="color: #d31c08" >200%</td>
      </tr>
      <tr>
        <th scope="row">Open Issues</th>
        <td>0</td>
        <td>106</td>
        <td style="color: #45c527" >-106</td>
        <td style="color: #45c527" >200%</td>
      </tr>
      <tr>
        <th scope="row">Closed Issues</th>
        <td>0</td>
        <td>877</td>
        <td style="color: #d31c08" >-877</td>
        <td style="color: #d31c08" >200%</td>
      </tr>
      <tr>
        <th scope="row">Open Pull Requests</th>
        <td>5</td>
        <td>196</td>
        <td style="color: #45c527" >-191</td>
        <td style="color: #45c527" >190%</td>
      </tr>
      <tr>
        <th scope="row">Merged Pull Requests</th>
        <td>79</td>
        <td>19914</td>
        <td style="color: #d31c08" >-19835</td>
        <td style="color: #d31c08" >200%</td>
      </tr>
      <tr>
        <th scope="row">Closed Pull Requests</th>
        <td>11</td>
        <td>4530</td>
        <td style="color: #45c527" >-4519</td>
        <td style="color: #45c527" >200%</td>
      </tr>
      <tr>
        <th scope="row">Forks</th>
        <td>3</td>
        <td>584</td>
        <td style="color: #d31c08" >-581</td>
        <td style="color: #d31c08" >200%</td>
      </tr>
      <tr>
        <th scope="row">Stars</th>
        <td>0</td>
        <td>1449</td>
        <td style="color: #d31c08" >-1449</td>
        <td style="color: #d31c08" >200%</td>
      </tr>
      <tr>
        <th scope="row">Watchers</th>
        <td>3</td>
        <td>1882</td>
        <td style="color: #d31c08" >-1879</td>
        <td style="color: #d31c08" >200%</td>
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
    <!-- Top Committers Bar Graph -->
    {% render "graph-section" baseurl: site.baseurl, path: "/CMSgov/CMSgov_top_committers.svg", title: "Top Committers" %}
    <!-- Libyear Timeline Graph -->
    {% render "graph-section" baseurl: site.baseurl, path: "/CMSgov/CMSgov_libyear_timeline.svg", title: "Dependency Libyears" %}
  </div>
</div>