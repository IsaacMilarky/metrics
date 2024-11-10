---
layout: org-report
title: Open Source at CMS Metrics Report for CMSgov | REPORT-2024-11-10
permalink: /CMSgov/

org: CMSgov
reportID: REPORT-2024-11-10
date_stampThisWeek: 2024-11-10
date_stampLastWeek: 2024-11-10
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
        <td>54280</td>
        <td>54224</td>
        <td style="color: #45c527" >56</td>
        <td style="color: #45c527" >0.1%</td>
      </tr>
      <tr>
        <th scope="row">Issues</th>
        <td>980</td>
        <td>980</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Open Issues</th>
        <td>109</td>
        <td>109</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Closed Issues</th>
        <td>871</td>
        <td>871</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Open Pull Requests</th>
        <td>194</td>
        <td>194</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Merged Pull Requests</th>
        <td>19816</td>
        <td>19782</td>
        <td style="color: #45c527" >34</td>
        <td style="color: #45c527" >0.17%</td>
      </tr>
      <tr>
        <th scope="row">Closed Pull Requests</th>
        <td>4499</td>
        <td>4496</td>
        <td style="" >3</td>
        <td style="" >0.067%</td>
      </tr>
      <tr>
        <th scope="row">Forks</th>
        <td>581</td>
        <td>580</td>
        <td style="color: #45c527" >1</td>
        <td style="color: #45c527" >0.17%</td>
      </tr>
      <tr>
        <th scope="row">Stars</th>
        <td>1446</td>
        <td>1446</td>
        <td style="" >0</td>
        <td style="" >0%</td>
      </tr>
      <tr>
        <th scope="row">Watchers</th>
        <td>1806</td>
        <td>1806</td>
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
    <!-- Top Committers Bar Graph -->
    {% render "graph-section" baseurl: site.baseurl, path: "/CMSgov/CMSgov_top_committers.svg", title: "Top Committers" %}
    <!-- Libyear Timeline Graph -->
    {% render "graph-section" baseurl: site.baseurl, path: "/CMSgov/CMSgov_libyear_timeline.svg", title: "Dependency Libyears" %}
  </div>
</div>