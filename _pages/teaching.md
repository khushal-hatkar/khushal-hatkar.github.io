---
layout: page
permalink: /teaching/
title: Teaching
nav: true
nav_order: 4
# calendar: true
---



<script>
document.addEventListener("DOMContentLoaded", function() {
  const cards = document.querySelectorAll(".card");
  cards.forEach(card => {
    const parentA = card.closest("a");
    if (parentA) {
      parentA.replaceWith(card);
    }
  });
});
</script>

{% include courses.liquid %}

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
