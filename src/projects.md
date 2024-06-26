---
layout: layouts/harvest.njk
title: Projects
---

<main>
  <div class="flex justify-space-between">
    <div class="flex">
      <h1>Projects</h1>
    </div>
    <div class="flex">
      <button class="button primary">
        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="12" y1="5" x2="12" y2="19"></line><line x1="5" y1="12" x2="19" y2="12"></line></svg>
        New project
      </button>
      <button class="button button-icon show-mobile"><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"></circle><line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg></button>
      <input class="input search show-desktop" type="text" placeholder="Find a project…">
    </div>
  </div>

  <div class="tabs mt-16 mb-16">
    <nav>
      <a href="#" class="is-selected">Active <div class="badge">57</div></a>
      <a href="#">Budgeted <div class="badge">42</div></a>
      <a href="#">Templates <div class="badge">2</div></a>
      <a href="#">Stale <div class="badge">23</div></a>
      <a href="#">Archived</a>
    </nav>
  </div>

  <div class="flex justify-space-between filters">
    <div class="flex">
      <button class="button button-sm"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="6" y1="12" x2="18" y2="12"></line><line x1="3" y1="6" x2="21" y2="6"></line><line x1="9" y1="18" x2="15" y2="18"></line></svg> Filter</button>
      <button class="button button-sm"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="4" y1="21" x2="4" y2="14"></line><line x1="4" y1="10" x2="4" y2="3"></line><line x1="12" y1="21" x2="12" y2="12"></line><line x1="12" y1="8" x2="12" y2="3"></line><line x1="20" y1="21" x2="20" y2="16"></line><line x1="20" y1="12" x2="20" y2="3"></line><line x1="1" y1="14" x2="7" y2="14"></line><line x1="9" y1="8" x2="15" y2="8"></line><line x1="17" y1="16" x2="23" y2="16"></line></svg> Customize</button>
    </div>
    <div class="flex">
      <button class="button button-sm"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M19 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h11l5 5v11a2 2 0 0 1-2 2z"></path><polyline points="17 21 17 13 7 13 7 21"></polyline><polyline points="7 3 7 8 15 8"></polyline></svg> Save view</button>
      <button class="button button-sm">Export <svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="8 10 14 16 20 10"></polyline></svg></button>
    </div>
  </div>

  <div class="table-wrapper mt-16">
    <table border="0" class="table" cellpadding="0" cellspacing="0">
      <tbody>
        <tr>
          <th class="no-width"><input type="checkbox"></th>
          <th class="no-width"></th>
          <th class="is-sorted">Pinned <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-arrow-down"><line x1="12" y1="5" x2="12" y2="19"></line><polyline points="19 12 12 19 5 12"></polyline></svg></th>
          <th>Clients</th>
          <th class="no-width text-right">Progress</th>
          <th class="no-width"></th>
          <th class="no-width text-right">Budget</th>
          <th class="no-width text-right">Spent</th>
          <th class="no-width text-right">Remaining</th>
          <th class="no-width"></th>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td class="no-width"><input type="checkbox"></td>
          <td class="no-width"><svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-linecap="round" stroke-width="2" style="vertical-align:middle;"><path d="M7 6.1V5c0-1.1.8-2 2-2h6a2 2 0 0 1 2 2v1.1c0 .5-.3.9-.8.9h-.3c-.3 0-.6.3-.6.7 0 .2 0 .4.2.5 1 .8 2.6 2.5 3.2 4.8.3 1-.6 2-1.7 2H7c-1.1 0-2-1-1.7-2 .6-2.3 2.1-4 3.2-4.8l.2-.5c0-.4-.3-.7-.6-.7h-.3a.9.9 0 0 1-.9-.9ZM12 15v6"></path></svg></td>
          <td>[Code] Project name</td>
          <td>Client name</td>
          <td class="no-width text-right">65%</td>
          <td class="no-width"><div class="meter"></div></td>
          <td class="no-width text-right">$30,000.00</td>
          <td class="no-width text-right">$10,000.00</td>
          <td class="no-width text-right nowrap">$20,000.00</td>
          <td class="no-width">
            <a href="{{ '/project-analysis' | url }}" class="button button-sm button-empty button-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="1"></circle><circle cx="20" cy="12" r="1"></circle><circle cx="4" cy="12" r="1"></circle></svg>
            </a>
          </td>
        </tr>
        <tr>
          <td class="no-width"><input type="checkbox"></td>
          <td class="no-width"><svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-linecap="round" stroke-width="2" style="vertical-align:middle;"><path d="M7 6.1V5c0-1.1.8-2 2-2h6a2 2 0 0 1 2 2v1.1c0 .5-.3.9-.8.9h-.3c-.3 0-.6.3-.6.7 0 .2 0 .4.2.5 1 .8 2.6 2.5 3.2 4.8.3 1-.6 2-1.7 2H7c-1.1 0-2-1-1.7-2 .6-2.3 2.1-4 3.2-4.8l.2-.5c0-.4-.3-.7-.6-.7h-.3a.9.9 0 0 1-.9-.9ZM12 15v6"></path></svg></td>
          <td>[Code] Project name</td>
          <td>Client name</td>
          <td class="no-width text-right">65%</td>
          <td class="no-width"><div class="meter"></div></td>
          <td class="no-width text-right">$30,000.00</td>
          <td class="no-width text-right">$10,000.00</td>
          <td class="no-width text-right nowrap">$20,000.00</td>
          <td class="no-width">
            <a href="{{ '/project-analysis' | url }}" class="button button-sm button-empty button-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="1"></circle><circle cx="20" cy="12" r="1"></circle><circle cx="4" cy="12" r="1"></circle></svg>
            </a>
          </td>
        </tr>
        <tbody>
        <tr>
          <th class="no-width"><input type="checkbox"></th>
          <th class="no-width"></th>
          <th class="is-sorted">Projects <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-arrow-down"><line x1="12" y1="5" x2="12" y2="19"></line><polyline points="19 12 12 19 5 12"></polyline></svg></th>
          <th>Clients</th>
          <th class="no-width text-right">Progress</th>
          <th class="no-width"></th>
          <th class="no-width text-right">Budget</th>
          <th class="no-width text-right">Spent</th>
          <th class="no-width text-right">Remaining</th>
          <th class="no-width"></th>
        </tr>
      </tbody>
        <tr>
          <td class="no-width"><input type="checkbox"></td>
          <td class="no-width"></td>
          <td>[Code] Project name</td>
          <td>Client name</td>
          <td class="no-width text-right">65%</td>
          <td class="no-width"><div class="meter"></div></td>
          <td class="no-width text-right">$30,000.00</td>
          <td class="no-width text-right">$10,000.00</td>
          <td class="no-width text-right nowrap">$20,000.00</td>
          <td class="no-width">
            <a href="{{ '/project-analysis' | url }}" class="button button-sm button-empty button-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="1"></circle><circle cx="20" cy="12" r="1"></circle><circle cx="4" cy="12" r="1"></circle></svg>
            </a>
          </td>
        </tr>
        <tr>
          <td class="no-width"><input type="checkbox"></td>
          <td class="no-width"></td>
          <td>[Code] Project name</td>
          <td>Client name</td>
          <td class="no-width text-right">65%</td>
          <td class="no-width"><div class="meter"></div></td>
          <td class="no-width text-right">$30,000.00</td>
          <td class="no-width text-right">$10,000.00</td>
          <td class="no-width text-right nowrap">$20,000.00</td>
          <td class="no-width">
            <a href="{{ '/project-analysis' | url }}" class="button button-sm button-empty button-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="1"></circle><circle cx="20" cy="12" r="1"></circle><circle cx="4" cy="12" r="1"></circle></svg>
            </a>
          </td>
        </tr>
        <tr>
          <td class="no-width"><input type="checkbox"></td>
          <td class="no-width"></td>
          <td>[Code] Project name</td>
          <td>Client name</td>
          <td class="no-width text-right">65%</td>
          <td class="no-width"><div class="meter"></div></td>
          <td class="no-width text-right">$30,000.00</td>
          <td class="no-width text-right">$10,000.00</td>
          <td class="no-width text-right nowrap">$20,000.00</td>
          <td class="no-width">
            <a href="{{ '/project-analysis' | url }}" class="button button-sm button-empty button-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="1"></circle><circle cx="20" cy="12" r="1"></circle><circle cx="4" cy="12" r="1"></circle></svg>
            </a>
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</main>
