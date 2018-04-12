---
layout: page
title: Search
permalink: /search/
---

# Search page

<!-- Html Elements for Search -->
<div id="search-container">
<input type="text" id="search-input" placeholder="search...">
<ul id="results-container"></ul>
</div>

<!-- script pointing to jekyll-search.js -->
<script src="{{ site.baseurl }}/js/simple-jekyll-search.js"></script>
<!-- Configuration -->
<script>
  SimpleJekyllSearch(
  {
    searchInput: document.getElementById('search-input'),
    resultsContainer: document.getElementById('results-container'),
    json: '{{ site.baseurl }}/search.json'
  })
</script>
