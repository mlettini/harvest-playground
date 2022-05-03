---
layout: layouts/harvest.njk
title: More
---

<header id="top-nav">
  <nav>
    <a href="#" class="is-selected">Tasks</a>
    <a href="{{ '/more-categories' | url }}">Categories</a>
    <a href="#">Contacts</a>
    <a href="#">Roles</a>
    <a href="#">Item types</a>
    <a href="#">Colors</a>
  </nav>
</header>

<main>
  <div class="flex justify-space-between">
    <div class="flex">
      <h1>Tasks</h1>
    </div>
    <div class="flex">
      <a href="#" class="button primary is-disabled">
        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="12" y1="5" x2="12" y2="19"></line><line x1="5" y1="12" x2="19" y2="12"></line></svg>
        New task
      </a>
      <button class="button button-icon show-mobile"><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"></circle><line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg></button>
      <input class="input search show-desktop" type="text" placeholder="Find a task…">
    </div>
  </div>

  <div class="tabs mt-24 mb-16">
    <nav>
      <a href="#" class="is-selected">Active <div class="badge">20</div></a>
      <a href="#">Stale <div class="badge">9</div></a>
      <a href="#">Archived</a>
    </nav>
  </div>

  <div class="flex justify-space-between filters">
    <div class="flex">
      <button class="button button-sm is-filtered"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="6" y1="12" x2="18" y2="12"></line><line x1="3" y1="6" x2="21" y2="6"></line><line x1="9" y1="18" x2="15" y2="18"></line></svg> Filter</button>
    </div>
    <div class="flex">
      <button class="button button-sm">Export <svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="8 10 14 16 20 10"></polyline></svg></button>
    </div>
  </div>

  <div class="table-wrapper mt-16">
    <table border="0" class="table" cellpadding="0" cellspacing="0">
      <tbody>
        <tr>
          <th class="no-width"><input type="checkbox"></th>
          <th class="is-sorted">Tasks <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-arrow-down"><line x1="12" y1="5" x2="12" y2="19"></line><polyline points="19 12 12 19 5 12"></polyline></svg></th>
          <th>Default hourly rate</th>
          <th class="no-width text-center pr-32 nowrap">Billable by default</th>
          <th class="no-width text-center pr-32">Common</th>
          <th class="no-width"></th>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td class="no-width"><input type="checkbox"></td>
          <td>Task name</td>
          <td>$100,000.00 USD</td>
          <td class="no-width text-center pr-32"><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align:middle"><polyline points="20 6 9 17 4 12"></polyline></svg></td>
          <td class="no-width text-center pr-32"><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align:middle"><polyline points="20 6 9 17 4 12"></polyline></svg></td>
          <td class="no-width">
            <a href="#" class="button button-sm button-empty button-icon">
              <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="1"></circle><circle cx="20" cy="12" r="1"></circle><circle cx="4" cy="12" r="1"></circle></svg>
            </a>
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</main>

<div class="dialog-backdrop">
  <div class="dialog">
    <h2 class="mb-16">New task</h2>
    <div class="mb-16">
      <strong>Task name</strong>
      <input class="input" autofocus>
    </div>
    <div class="mb-24">
      <strong>Default hourly rate</strong>
      <div>
        <div class="input-group">
          <span>$</span>
          <input class="input" placeholder="0.00" style="width:100px">
          <span>USD</span>
        </div>
      </div>
    </div>
    <div>
      <div>
        <label>
          <input type="checkbox" checked="checked"> This task is billable by default
        </label>
      </div>
      <div>
        <label>
          <input type="checkbox"> This is a common task and should be added to all future projects
        </label>
      </div>
      <div>
        <label>
          <input type="checkbox"> Add this task to all existing active projects now
        </label>
      </div>
    </div>
    <div class="mt-24">
      <a href="{{ '/more-tasks' | url }}" class="button primary">Save task</a>
      <a href="{{ '/more-tasks' | url }}" class="button">Cancel</a>
    </div>
  </div>
</div>
