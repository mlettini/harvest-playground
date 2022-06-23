---
layout: layouts/harvest.njk
title: Invoices
---

<header id="top-nav">
  <nav>
    <a href="#" class="is-selected">Overview</a>
    <a href="#">Recurring invoices</a>
    <a href="#">Retainers</a>
    <a href="#">Configure</a>
  </nav>
</header>

<main>
  <a href="{{ '/invoices' | url }}" class="back-to mb-16">
    <svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="19" y1="12" x2="5" y2="12"></line><polyline points="12 19 5 12 12 5"></polyline></svg>Invoices
  </a>

  <div class="flex justify-space-between mb-16">
    <div>
      <h1>Invoice #1234</h1>
    </div>
    <button class="button button-icon show-mobile"><svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"></circle><line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg></button>
    <input class="input search show-desktop" type="text" placeholder="Find an invoice…">
  </div>

  <div class="flex justify-space-between filters mt-16">
    <div class="flex">
      <button class="button button-sm primary">
        <svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="22" y1="2" x2="11" y2="13"></line><polygon points="22 2 15 22 11 13 2 9 22 2"></polygon></svg>
        Send invoice
      </button>
      <button class="button button-sm">
        <svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="1"></circle><circle cx="20" cy="12" r="1"></circle><circle cx="4" cy="12" r="1"></circle></svg>
        Actions
      </button>
    </div>
    <div class="flex">
      <button class="button button-sm">
        <svg xmlns="http://www.w3.org/2000/svg" width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="12" y1="2" x2="12" y2="22"></line><path d="M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6"></path></svg>
        Record payment
      </button>
    </div>
  </div>

  <hr class="mt-16 mb-16">
</main>
