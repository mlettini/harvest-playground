---
layout: layouts/harvest.njk
title: Time
---

<main>
  <div class="flex justify-space-between mb-16">
    <div class="flex">
      <h1>Timesheet</h1>
    </div>
    <div class="flex">
      <button class="button primary">
        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="12" y1="5" x2="12" y2="19"></line><line x1="5" y1="12" x2="19" y2="12"></line></svg>
        Track time
      </button>
      <button class="button button-icon show-mobile">
        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"></path><circle cx="9" cy="7" r="4"></circle><path d="M23 21v-2a4 4 0 0 0-3-3.87"></path><path d="M16 3.13a4 4 0 0 1 0 7.75"></path></svg>
      </button>
      <button class="button show-desktop">
        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"></path><circle cx="9" cy="7" r="4"></circle><path d="M23 21v-2a4 4 0 0 0-3-3.87"></path><path d="M16 3.13a4 4 0 0 1 0 7.75"></path></svg>
        Teammates
      </button>
    </div>
  </div>

  <div class="tabs mt-16 mb-16">
    <nav>
      <a href="#" class="is-selected">Day view</a>
      <a href="#">Week view</a>
      <a href="#">Calendar view</a>
    </nav>
  </div>

  <div class="flex justify-space-between filters">
    <div class="flex">
      <div class="button-group">
        <button class="button button-sm button-icon"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="19" y1="12" x2="5" y2="12"></line><polyline points="12 19 5 12 12 5"></polyline></svg></button>
        <button class="button button-sm button-icon"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="12" x2="19" y2="12"></line><polyline points="12 5 19 12 12 19"></polyline></svg></button>
        <button class="button button-sm"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"></rect><line x1="16" y1="2" x2="16" y2="6"></line><line x1="8" y1="2" x2="8" y2="6"></line><line x1="3" y1="10" x2="21" y2="10"></line></svg> Today: <span>Thursday, 7 Apr</span></button>
      </div>
      <div class="badge pending ml-4">Pending approval</div>
    </div>
    <div class="flex">
      <button class="button button-sm">Resubmit for approval</button>
    </div>
  </div>

  <div class="tabs time-tabs mt-16">
    <nav>
      <a href="#">Mon 🎉<br>3:54</a>
      <a href="#">Tue 🎉<br>1:00</a>
      <a href="#">Wed 🎉<br>1:00</a>
      <a href="#" class="is-selected">Thu 🎉<br>1:00</a>
      <a href="#">Fri<br>0:00</a>
      <a href="#">Sat<br>0:00</a>
      <a href="#">Sun<br>0:00</a>
      <a href="#">Sat<br>0:00</a>
      <div><span class="nowrap">Week total</span><br>6:54</div>
    </nav>
  </div>

  <div class="table-wrapper">
    <table border="0" class="table time-table" cellpadding="0" cellspacing="0">
      <thead>
        <tr>
          <th class="no-width"><input type="checkbox"></th>
          <th>Task</th>
          <th>Project</th>
          <th class="is-sorted">Timestamps <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-arrow-down"><line x1="12" y1="5" x2="12" y2="19"></line><polyline points="19 12 12 19 5 12"></polyline></svg></th>
          <th class="no-width text-right">Duration</th>
          <th class="no-width no-width text-center">Billable?</th>
          <th class="no-width pr-0"></th>
          <th class="no-width"></th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td class="no-width"><input type="checkbox"></td>
          <td>
            Task name<br>
            <small class="color-secondary">Here are some notes</small>
          </td>
          <td>
            [Code] Project name<br>
            <small class="color-secondary">Client name</small>
          </td>
          <td class="nowrap">
            1:30 – 4:20
          </td>
          <td class="no-width text-right nowrap">
            <h3>3:00</h3>
          </td>
          <td class="no-width text-center">-</td>
          <td class="no-width pr-0">
            <button class="button"><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg> Start</button>
          </td>
          <td class="no-width">
            <a href="#" class="button button-sm button-empty button-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="1"></circle><circle cx="20" cy="12" r="1"></circle><circle cx="4" cy="12" r="1"></circle></svg>
            </a>
          </td>
        </tr>
        <tr class="is-running">
          <td class="no-width"><input type="checkbox"></td>
          <td>
            Task name<br>
            <small class="color-secondary">Here are some notes</small>
          </td>
          <td>
            [Code] Project name<br>
            <small class="color-secondary">Client name</small>
          </td>
          <td class="nowrap">
            4:21 –
          </td>
          <td class="no-width text-right nowrap">
            <h3>0:36</h3>
          </td>
          <td class="no-width text-center"><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align:middle"><polyline points="20 6 9 17 4 12"></polyline></svg></td>
          <td class="no-width pr-0">
            <button class="button running">
              <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
                <circle cx="12" cy="12" r="10"></circle>
                <line x1="12" y1="6" x2="12" y2="12">
                  <animateTransform attributeName="transform" attributeType="XML" type="rotate" from="0 12 12" to="360 12 12" dur="3s" repeatCount="indefinite"></animateTransform>
                </line>
                <line x1="16" y1="14" x2="12" y2="12">
                  <animateTransform attributeName="transform" attributeType="XML" type="rotate" from="0 12 12" to="360 12 12" dur="30s" repeatCount="indefinite"></animateTransform>
                </line>
              </svg>
              Stop
            </button>
          </td>
          <td class="no-width">
            <a href="#" class="button button-sm button-empty button-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="1"></circle><circle cx="20" cy="12" r="1"></circle><circle cx="4" cy="12" r="1"></circle></svg>
            </a>
          </td>
        </tr>
      </tbody>
      <tfoot>
        <tr>
          <td class="no-width"></td>
          <td></td>
          <td></td>
          <td class="text-right"><h3 class="text-400 color-secondary">Total:</h3></td>
          <td class="no-width text-right"><h3>6:36</h3></td>
          <td class="no-width"></td>
          <td class="no-width"></td>
          <td class="no-width"></td>
        </tr>
      </tfoot>
    </table>
    <video class="aura-background" autoplay="" loop="" muted="" poster="">
      <source src="https://www.getharvest.com/hubfs/video/aura-left-right.mp4" type="video/mp4">
    </video>
  </div>
</main>
