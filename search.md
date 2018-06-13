---
layout: page
title: Search
keywords: search
search: "false"
permalink: search.html
---

# Search page
<!-- Html Elements for Search -->
<div id="search-container">
<input type="text" id="search-input" placeholder="search...">
<ul id="results-container"></ul>
</div>

<!-- script pointing to jekyll-search.js -->
<!-- <script src="{{ site.baseurl }}/js/simple-jekyll-search.js"></script> -->
<!-- Configuration -->
<!--
<script>
  SimpleJekyllSearch(
  {
    searchInput: document.getElementById('search-input'),
    resultsContainer: document.getElementById('results-container'),
    json: '{{ site.baseurl }}/search.json'
  })
</script>
-->
<!--  wg 5/25 point script  to page-search.json -->
<script>
  SimpleJekyllSearch(
  {
    searchInput: document.getElementById('search-input'),
    resultsContainer: document.getElementById('results-container'),
    json: '{{ site.baseurl }}/page-search.json'
  })
</script>
