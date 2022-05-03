---
layout: layouts/harvest.njk
title: Expenses
---

<main>
  <div class="flex justify-space-between">
    <div class="flex">
      <h1>Expenses</h1>
    </div>
    <div class="flex">
      <button class="button primary">
        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="12" y1="5" x2="12" y2="19"></line><line x1="5" y1="12" x2="19" y2="12"></line></svg>
        Add expense
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

  <hr class="mt-16 mb-16">

  <div class="flex justify-space-between filters">
    <div class="flex">
      <div class="button-group">
        <button class="button button-sm button-icon is-disabled"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="19" y1="12" x2="5" y2="12"></line><polyline points="12 19 5 12 12 5"></polyline></svg></button>
        <button class="button button-sm button-icon is-disabled"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="12" x2="19" y2="12"></line><polyline points="12 5 19 12 12 19"></polyline></svg></button>
        <button class="button button-sm"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"></rect><line x1="16" y1="2" x2="16" y2="6"></line><line x1="8" y1="2" x2="8" y2="6"></line><line x1="3" y1="10" x2="21" y2="10"></line></svg> All time</button>
      </div>
      <button class="button button-sm"><svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="6" y1="12" x2="18" y2="12"></line><line x1="3" y1="6" x2="21" y2="6"></line><line x1="9" y1="18" x2="15" y2="18"></line></svg> Filter</button>
    </div>
    <div class="flex">
      <button class="button button-sm">Export <svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="8 10 14 16 20 10"></polyline></svg></button>
    </div>
  </div>

  <div class="table-wrapper mt-16">
    <table border="0" class="table expense-table mb-16" cellpadding="0" cellspacing="0">
      <thead>
        <tr>
          <th class="no-width"><input type="checkbox"></th>
          <th class="no-width pr-0 is-sorted">Date <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-arrow-down"><line x1="12" y1="5" x2="12" y2="19"></line><polyline points="19 12 12 19 5 12"></polyline></svg></th>
          <th class="no-width pr-32"></th>
          <th>Category</th>
          <th>Project</th>
          <th class="no-width text-right">Amount</th>
          <th class="no-width no-width text-center">Billable?</th>
          <th class="no-width no-width text-center">Reimbursed?</th>
          <th class="no-width pr-0"></th>
          <th class="no-width"></th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td class="no-width"><input type="checkbox"></td>
          <td class="no-width pr-0 nowrap">30 Mar 2022</td>
          <td class="no-width pr-32"><div class="badge pending">Pending</div></td>
          <td>
            Category name<br>
            <small class="color-secondary">Here are some notes</small>
          </td>
          <td>
            [Code] Project name<br>
            <small class="color-secondary">Client name</small>
          </td>
          <td class="no-width text-right nowrap">
            <h4>$25.00</h4>
          </td>
          <td class="no-width text-center">-</td>
          <td class="no-width text-center"><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align:middle"><polyline points="20 6 9 17 4 12"></polyline></svg></td>
          <td class="text-right no-width pr-0">
            <div class="flex justify-content-end nowrap">
              <a href="#" class="button button-sm button-empty button-icon">
                <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21.44 11.05l-9.19 9.19a6 6 0 0 1-8.49-8.49l9.19-9.19a4 4 0 0 1 5.66 5.66l-9.2 9.19a2 2 0 0 1-2.83-2.83l8.49-8.48"></path></svg>
              </a>
              <a href="#" class="button button-sm button-empty button-icon">
                <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="1"></circle><circle cx="20" cy="12" r="1"></circle><circle cx="4" cy="12" r="1"></circle></svg>
              </a>
            </div>
          </td>
          <td class="no-width text-right">
            <button class="button button-sm">Resubmit</button>
          </td>
        </tr>
        <tr>
          <td class="no-width"><input type="checkbox"></td>
          <td class="no-width pr-0 nowrap">29 Mar 2022</td>
          <td class="no-width pr-32"></td>
          <td>
            Category name<br>
            <small class="color-secondary">Here are some notes</small>
          </td>
          <td>
            [Code] Project name<br>
            <small class="color-secondary">Client name</small>
          </td>
          <td class="no-width text-right nowrap">
            <h4>$4.00</h4>
          </td>
          <td class="no-width text-center"><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align:middle"><polyline points="20 6 9 17 4 12"></polyline></svg></td>
          <td class="no-width text-center">-</td>
          <td class="text-right no-width pr-0">
            <div class="flex justify-content-end nowrap">
              <a href="#" class="button button-sm button-empty button-icon">
                <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="1"></circle><circle cx="20" cy="12" r="1"></circle><circle cx="4" cy="12" r="1"></circle></svg>
              </a>
            </div>
          </td>
          <td class="no-width text-right">
            <button class="button button-sm">Submit</button>
          </td>
        </tr>
        <tr class="locked">
          <td class="no-width"><input type="checkbox"></td>
          <td class="no-width pr-0 nowrap">28 Mar 2022 </td>
          <td class="no-width pr-32"><div class="badge green">Approved</div></td>
          <td>
            Category name<br>
            <small class="color-secondary">Here are some notes</small>
          </td>
          <td>
            [Code] Project name<br>
            <small class="color-secondary">Client name</small>
          </td>
          <td class="no-width text-right nowrap">
            <h4>$123.00</h4>
          </td>
          <td class="no-width text-center"><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align:middle"><polyline points="20 6 9 17 4 12"></polyline></svg></td>
          <td class="no-width text-center"><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align:middle"><polyline points="20 6 9 17 4 12"></polyline></svg></td>
          <td class="text-right no-width pr-0">
            <div class="flex justify-content-end nowrap">
              <a href="#" class="button button-sm button-empty button-icon">
                <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21.44 11.05l-9.19 9.19a6 6 0 0 1-8.49-8.49l9.19-9.19a4 4 0 0 1 5.66 5.66l-9.2 9.19a2 2 0 0 1-2.83-2.83l8.49-8.48"></path></svg>
              </a>
              <a href="#" class="button button-sm button-empty button-icon">
                <svg xmlns="http://www.w3.org/2000/svg" width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-lock"><rect x="3" y="11" width="18" height="11" rx="2" ry="2"></rect><path d="M7 11V7a5 5 0 0 1 10 0v4"></path></svg>
              </a>
            </div>
          </td>
          <td class="no-width text-right">
            <button class="button button-sm button-empty">Withdraw</button>
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</main>
