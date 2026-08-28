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
