---
layout: layouts/harvest.njk
title: Team
---

<main>
  <div class="flex justify-space-between">
    <div class="flex">
      <h1>Team</h1>
    </div>
    <div class="flex">
      <button class="button primary">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-user-plus"><path d="M16 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"></path><circle cx="8.5" cy="7" r="4"></circle><line x1="20" y1="8" x2="20" y2="14"></line><line x1="23" y1="11" x2="17" y2="11"></line></svg>
        Invite teammate
      </button>
      <button class="button button-icon show-mobile"><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"></circle><line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg></button>
      <input class="input search show-desktop" type="text" placeholder="Find a teammate…">
    </div>
  </div>

  <div class="tabs mt-16 mb-16">
    <nav>
      <a href="#" class="is-selected">Active <div class="badge">5</div></a>
      <a href="#">Archived</a>
    </nav>
  </div>

  <div class="flex justify-space-between filters">
    <div class="flex">
      <div class="button-group">
        <button class="button button-sm button-icon"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="19" y1="12" x2="5" y2="12"></line><polyline points="12 19 5 12 12 5"></polyline></svg></button>
        <button class="button button-sm button-icon"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="12" x2="19" y2="12"></line><polyline points="12 5 19 12 12 19"></polyline></svg></button>
        <button class="button button-sm"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"></rect><line x1="16" y1="2" x2="16" y2="6"></line><line x1="8" y1="2" x2="8" y2="6"></line><line x1="3" y1="10" x2="21" y2="10"></line></svg> This week: <span>1 – 7 Mar 2021</span></button>
      </div>
      <button class="button button-sm"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="6" y1="12" x2="18" y2="12"></line><line x1="3" y1="6" x2="21" y2="6"></line><line x1="9" y1="18" x2="15" y2="18"></line></svg> Filter</button>
      <button class="button button-sm"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="4" y1="21" x2="4" y2="14"></line><line x1="4" y1="10" x2="4" y2="3"></line><line x1="12" y1="21" x2="12" y2="12"></line><line x1="12" y1="8" x2="12" y2="3"></line><line x1="20" y1="21" x2="20" y2="16"></line><line x1="20" y1="12" x2="20" y2="3"></line><line x1="1" y1="14" x2="7" y2="14"></line><line x1="9" y1="8" x2="15" y2="8"></line><line x1="17" y1="16" x2="23" y2="16"></line></svg> Customize</button>
    </div>
    <div class="flex">
      <button class="button button-sm"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M19 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h11l5 5v11a2 2 0 0 1-2 2z"></path><polyline points="17 21 17 13 7 13 7 21"></polyline><polyline points="7 3 7 8 15 8"></polyline></svg> Save view</button>
      <button class="button button-sm">Export <svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="8 10 14 16 20 10"></polyline></svg></button>
    </div>
  </div>

  <div class="summary mt-16 mb-16">
    <div class="summary-box">
      Total hours<br>
      <h2>123.45</h2>
      <div class="flex justify-space-between mt-8">
        Billable <strong>3.00</strong>
      </div>
      <div class="flex justify-space-between">
        Non-billable <strong>0.00</strong>
      </div>
    </div>
    <div class="summary-box">
      Billable utilization<br>
      <h2>65%</h2>
      <div class="pt-8"><div class="meter" style="width:100%"></div></div>
      <div class="flex justify-space-between">
        Total capacity <strong>123.00</strong>
      </div>
    </div>
  </div>

  <div class="table-wrapper">
    <table border="0" class="table" cellpadding="0" cellspacing="0">
      <tbody>
        <tr>
          <th class="no-width"><input type="checkbox"></th>
          <th class="no-width"></th>
          <th class="no-width"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="margin-top:-2px;vertical-align:middle;"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg></th>
          <th class="is-sorted nowrap">
            Pinned (3)
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-arrow-down"><line x1="12" y1="5" x2="12" y2="19"></line><polyline points="19 12 12 19 5 12"></polyline></svg>
          </th>
          <th class="no-width text-right nowrap">Utilization</th>
          <th class="no-width"></th>
          <th class="no-width text-right nowrap">Total hours</th>
          <th class="no-width text-right nowrap">Billable hours</th>
          <th class="no-width text-right">Capacity</th>
          <th class="no-width">Permission</th>
          <th class="no-width"></th>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td class="no-width"><input type="checkbox"></td>
          <td class="no-width"><svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-linecap="round" stroke-width="2" style="vertical-align:middle;"><path d="M7 6.1V5c0-1.1.8-2 2-2h6a2 2 0 0 1 2 2v1.1c0 .5-.3.9-.8.9h-.3c-.3 0-.6.3-.6.7 0 .2 0 .4.2.5 1 .8 2.6 2.5 3.2 4.8.3 1-.6 2-1.7 2H7c-1.1 0-2-1-1.7-2 .6-2.3 2.1-4 3.2-4.8l.2-.5c0-.4-.3-.7-.6-.7h-.3a.9.9 0 0 1-.9-.9ZM12 15v6"></path></svg></td>
          <td class="no-width"><div class="team-running-timer"></td>
          <td>
            <div class="flex nowrap">
              <img src="https://matthewlettini.me/images/matthew-lettini-avatar.jpg" width="30" height="30" class="avatar mr-4">
              Person Name
            </div>
          </td>
          <td class="no-width text-right">65%</td>
          <td class="no-width"><div class="meter"></div></td>
          <td class="no-width text-right">12.34</td>
          <td class="no-width text-right">2.34</td>
          <td class="no-width text-right">35.00</td>
          <td class="no-width">Manager</td>
          <td class="no-width">
            <a href="{{ '/team-analysis' | url }}" class="button button-sm button-empty button-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="1"></circle><circle cx="20" cy="12" r="1"></circle><circle cx="4" cy="12" r="1"></circle></svg>
            </a>
          </td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <th class="no-width"><input type="checkbox"></th>
          <th class="no-width"></th>
          <th class="no-width"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="margin-top:-2px;vertical-align:middle;"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg></th>
          <th class="is-sorted nowrap">
            Employees (3)
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-arrow-down"><line x1="12" y1="5" x2="12" y2="19"></line><polyline points="19 12 12 19 5 12"></polyline></svg>
          </th>
          <th class="no-width text-right nowrap">Utilization</th>
          <th class="no-width"></th>
          <th class="no-width text-right nowrap">Total hours</th>
          <th class="no-width text-right nowrap">Billable hours</th>
          <th class="no-width text-right">Capacity</th>
          <th class="no-width">Permission</th>
          <th class="no-width"></th>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td class="no-width"><input type="checkbox"></td>
          <td class="no-width"></td>
          <td class="no-width"><div class="team-running-timer"></td>
          <td>
            <div class="flex nowrap">
              <img src="https://matthewlettini.me/images/matthew-lettini-avatar.jpg" width="30" height="30" class="avatar mr-4">
              Person Name
            </div>
          </td>
          <td class="no-width text-right">65%</td>
          <td class="no-width"><div class="meter"></div></td>
          <td class="no-width text-right">12.34</td>
          <td class="no-width text-right">2.34</td>
          <td class="no-width text-right">35.00</td>
          <td class="no-width">Admin</td>
          <td class="no-width">
            <a href="{{ '/team-analysis' | url }}" class="button button-sm button-empty button-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="1"></circle><circle cx="20" cy="12" r="1"></circle><circle cx="4" cy="12" r="1"></circle></svg>
            </a>
          </td>
        </tr>
        <tr>
          <td class="no-width"><input type="checkbox"></td>
          <td class="no-width"></td>
          <td class="no-width"><div class="team-running-timer running"></td>
          <td>
            <div class="flex nowrap">
              <img src="https://matthewlettini.me/images/matthew-lettini-avatar.jpg" width="30" height="30" class="avatar mr-4">
              Person Name
            </div>
          </td>
          <td class="no-width text-right">65%</td>
          <td class="no-width"><div class="meter"></div></td>
          <td class="no-width text-right">12.34</td>
          <td class="no-width text-right">2.34</td>
          <td class="no-width text-right">35.00</td>
          <td class="no-width">Admin</td>
          <td class="no-width">
            <a href="{{ '/team-analysis' | url }}" class="button button-sm button-empty button-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="1"></circle><circle cx="20" cy="12" r="1"></circle><circle cx="4" cy="12" r="1"></circle></svg>
            </a>
          </td>
        </tr>
        <tr>
          <td class="no-width"><input type="checkbox"></td>
          <td class="no-width"></td>
          <td class="no-width"><div class="team-running-timer"></td>
          <td>
            <div class="flex nowrap">
              <img src="https://matthewlettini.me/images/matthew-lettini-avatar.jpg" width="30" height="30" class="avatar mr-4">
              Person Name
            </div>
          </td>
          <td class="no-width text-right">65%</td>
          <td class="no-width"><div class="meter"></div></td>
          <td class="no-width text-right">12.34</td>
          <td class="no-width text-right">2.34</td>
          <td class="no-width text-right">35.00</td>
          <td class="no-width">Member</td>
          <td class="no-width">
            <a href="{{ '/team-analysis' | url }}" class="button button-sm button-empty button-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="1"></circle><circle cx="20" cy="12" r="1"></circle><circle cx="4" cy="12" r="1"></circle></svg>
            </a>
          </td>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <th class="no-width"><input type="checkbox"></th>
          <th class="no-width"></th>
          <th class="no-width"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="margin-top:-2px;vertical-align:middle;"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg></th>
          <th class="is-sorted nowrap">
            Contractors (3)
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-arrow-down"><line x1="12" y1="5" x2="12" y2="19"></line><polyline points="19 12 12 19 5 12"></polyline></svg>
          </th>
          <th class="no-width text-right nowrap">Utilization</th>
          <th class="no-width"></th>
          <th class="no-width text-right nowrap">Total hours</th>
          <th class="no-width text-right nowrap">Billable hours</th>
          <th class="no-width text-right">Capacity</th>
          <th class="no-width">Permission</th>
          <th class="no-width"></th>
        </tr>
      </tbody><tbody>
        <tr>
          <td class="no-width"><input type="checkbox"></td>
          <td class="no-width"></td>
          <td class="no-width"><div class="team-running-timer"></td>
          <td>
            <div class="flex nowrap">
              <img src="https://matthewlettini.me/images/matthew-lettini-avatar.jpg" width="30" height="30" class="avatar mr-4">
              Person Name
            </div>
          </td>
          <td class="no-width text-right">65%</td>
          <td class="no-width"><div class="meter"></div></td>
          <td class="no-width text-right">12.34</td>
          <td class="no-width text-right">2.34</td>
          <td class="no-width text-right">35.00</td>
          <td class="no-width">Admin</td>
          <td class="no-width">
            <a href="{{ '/team-analysis' | url }}" class="button button-sm button-empty button-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="1"></circle><circle cx="20" cy="12" r="1"></circle><circle cx="4" cy="12" r="1"></circle></svg>
            </a>
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</main>
