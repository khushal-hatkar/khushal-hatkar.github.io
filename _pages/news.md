---
layout: page
title: news
permalink: /news/
search_exclude: true
exclude_from_search: true
---

{% include news.liquid %}

<script>
document.addEventListener("DOMContentLoaded", function() {
  let attempts = 0;
  const filterSearch = setInterval(function() {
    const ninjaKeys = document.querySelector('ninja-keys');
    if (ninjaKeys && ninjaKeys.data && ninjaKeys.data.length > 0) {
      ninjaKeys.data = ninjaKeys.data.filter(item => item.section !== 'Books' && item.section !== 'News');
      clearInterval(filterSearch);
    }
    attempts++;
    if (attempts > 20) clearInterval(filterSearch);
  }, 100);
});
</script>
