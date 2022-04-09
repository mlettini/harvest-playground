---
layout: layouts/harvest.njk
title: More
---

<header id="top-nav">
  <nav>
    <a href="{{ '/more-tasks' | url }}">Tasks</a>
    <a href="#" class="is-selected">Categories</a>
    <a href="#">Contacts</a>
    <a href="#">Roles</a>
    <a href="#">Item types</a>
    <a href="#">Colors</a>
  </nav>
</header>

<main>
  <div class="flex justify-space-between">
    <div class="flex">
      <h1>Expense categories</h1>
    </div>
    <div class="flex">
      <button class="button primary">
        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="12" y1="5" x2="12" y2="19"></line><line x1="5" y1="12" x2="19" y2="12"></line></svg>
        New category
      </button>
      <input class="input search" type="text" placeholder="Find a category…">
    </div>
  </div>

  <div class="tabs mt-24 mb-16">
    <nav>
      <a href="#" class="is-selected">Active (20)</a>
      <a href="#">Unit priced (5)</a>
      <a href="#">Archived</a>
    </nav>
  </div>

  <div class="flex justify-space-between filters">
    <div class="flex">
      <button class="button button-sm is-disabled"><svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="1"></circle><circle cx="20" cy="12" r="1"></circle><circle cx="4" cy="12" r="1"></circle></svg> Bulk actions</button>
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
          <th class="is-sorted">Category <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-arrow-down"><line x1="12" y1="5" x2="12" y2="19"></line><polyline points="19 12 12 19 5 12"></polyline></svg></th>
          <th>Unit price</th>
          <th class="no-width"></th>
        </tr>
      </tbody>
      <tbody>
        <tr>
          <td class="no-width"><input type="checkbox"></td>
          <td><strong>Category name</strong></td>
          <td>$0.485 USD per mile</td>
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
  <dialog open>
    <div class="mb-16">
      <strong>New category</strong>
      <input class="input" placeholder="Category name">
    </div>
    <div class="mb-24">
      <strong>Default hourly rate</strong>
      <div class="input-group">
        <span>$</span>
        <input class="input" placeholder="0.00" style="width:clamp(100px, 25%, 300px)">
        <span>USD</span>
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
      <a href="{{ '/more-categories' | url }}" class="button primary">Save category</a>
      <a href="{{ '/more-categories' | url }}" class="button">Cancel</a>
    </div>
  </dialog>
</div>