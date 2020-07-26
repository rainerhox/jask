---
layout: search
title: Search
permalink: /search/
---
<!-- Script pointing to jekyll-search.js -->
<script src="{{ site.baseurl }}/search.js" type="text/javascript"></script>

SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: '/search.json',
})
