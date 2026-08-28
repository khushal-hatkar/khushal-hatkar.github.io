---
layout: book-shelf
title: My Space
permalink: /books/
nav: true
nav_order: 6
collection: books
---

> What an astonishing thing a book is. It's a flat object made from a tree with flexible parts on which are imprinted lots of funny dark squiggles. But one glance at it and you're inside the mind of another person, maybe somebody dead for thousands of years. Across the millennia, an author is speaking clearly and silently inside your head, directly to you. Writing is perhaps the greatest of human inventions, binding together people who never knew each other, citizens of distant epochs. Books break the shackles of time. A book is proof that humans are capable of working magic.
>
> -- Carl Sagan, Cosmos, Part 11: The Persistence of Memory (1980)

## Books that I am reading, have read, or will read

<script>
document.addEventListener("DOMContentLoaded", function() {
  document.querySelectorAll('h1 > a').forEach(function(link) {
    if (link.getAttribute('href') && link.getAttribute('href').includes('/books/')) {
      let span = document.createElement('span');
      span.innerHTML = link.innerHTML;
      span.style.color = 'inherit';
      link.replaceWith(span);
    }
  });
});
</script>

<br>
<hr>

## My Activities

<div class="row mt-3">
  <div class="col-sm mt-3 mt-md-0">
    <figure>
      <picture>
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/Run.jpg' | relative_url }}" alt="Running track in IISc during sunset">
      </picture>
      <figcaption class="caption" style="text-align: center; margin-top: 5px; font-style: italic; color: var(--global-text-color-light);">Running track in IISc during sunset</figcaption>
    </figure>
  </div>
  <div class="col-sm mt-3 mt-md-0">
    <figure>
      <picture>
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/Badminton.jpg' | relative_url }}" alt="Badminton">
      </picture>
      <figcaption class="caption" style="text-align: center; margin-top: 5px; font-style: italic; color: var(--global-text-color-light);">Badminton</figcaption>
    </figure>
  </div>
</div>
