---
layout: layouts/harvest.njk
title: Reports
---

<main>
  <div class="flex justify-space-between">
    <div class="flex">
      <h1>Reports</h1>
    </div>
    <div class="flex">
      <button class="button primary">
        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="12" y1="5" x2="12" y2="19"></line><line x1="5" y1="12" x2="19" y2="12"></line></svg>
        Create report
      </button>
    </div>
  </div>

  <hr class="mt-16 mb-16">

  <nav class="reports-list">
    <a href="{{ '/report-summary' | url }}" class="report-box">
      <img src="{{ '/images/snap.png' | url }}">
      <div>
        <h4>Summary report</h4>
        <span class="text-secondary">Some text about the report here.</span>
      </div>
    </a>
    <a href="{{ '/report-detailed' | url }}" class="report-box">
      <img src="{{ '/images/snap.png' | url }}">
      <div>
        <h4>Detailed time report</h4>
        <span class="text-secondary">Some text about the report here.</span>
      </div>
    </a>
    <a href="#">Detailed expense</a>
    <a href="{{ '/projects' | url }}">Project budget <svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"></path><polyline points="15 3 21 3 21 9"></polyline><line x1="10" y1="14" x2="21" y2="3"></line></svg></a>
    <a href="{{ '/team' | url }}">Team utilization <svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"></path><polyline points="15 3 21 3 21 9"></polyline><line x1="10" y1="14" x2="21" y2="3"></line></svg></a>
    <a href="#">Compliance</a>
    <a href="#">Contractor</a>
    <a href="#">Invoiced</a>
    <a href="#">Uninvoiced</a>
    <a href="#">Payments</a>
  </nav>

</main>
