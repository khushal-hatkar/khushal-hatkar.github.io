---
layout: book-shelf
title: My Space
permalink: /books/
nav: true
nav_order: 6
collection: books
search_exclude: true
exclude_from_search: true
---

> "The most exciting phrase to hear in science... is not 'Eureka!' but 'That's funny...'"
>
> — Isaac Asimov

Growing up, I always aspired to excel in science and research, hone this craft, and take it a step further. Several of my teachers at my school helped me pursue this ambitious journey, and in 11th grade, I secured an All-India Rank of 297 in the prestigious KVPY exam in 2020.

Life at IISc has had its share of ups and downs along the way, and I'm deeply grateful for the guidance of my professors and the steady support of friends who kept me going through it - a debt I don't think I'll ever fully repay. I was always fascinated by the world of physics and wanted to pursue something in that. However, when I first had the maiden class of materials science, I realised- this is what I want to end up doing. I was mesmerised by this world we constantly see and interact with every day, and yet never think about. Eventually, after choosing materials science as my major in my 2nd year, I took courses in solid-state physics and electron microscopy, where my ultimate passion took shape.

Outside the lab, I split my time between chess and badminton, a running habit that mostly happens on the IISc track at sunset, and whatever book I'm currently working through. I also like to play board games (my favourite being Secret Hitler). I was also part of Grain Boundary, the Materials Engineering department's student-run club, where we would have discourse sessions or 'discos' to disseminate our knowledge and expertise and also understand what is happening across various labs in the Materials Engineering Department at IISc. I also volunteer with Notebook Drive, supporting underprivileged students across Bengaluru and giving back to the community that has helped me grow so far. Looking ahead, I want to stay in electron microscopy - where I've only just dipped my toes so far, and take a real deep dive, ideally through a PhD, where I can push further.

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

  const activities = document.getElementById("my-activities-section");
  const article = document.querySelector("article");
  if (activities && article) {
    article.appendChild(activities);
  }
});
</script>

<div id="my-activities-section">
<br>
<hr>

<h2>My Activities</h2>

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

<div class="row mt-3">
  <div class="col-sm mt-3 mt-md-0">
    <figure>
      <picture>
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/GB.jpg' | relative_url }}" alt="Grain Boundary session- Student-run Club of the Materials Engineering Department.">
      </picture>
      <figcaption class="caption" style="text-align: center; margin-top: 5px; font-style: italic; color: var(--global-text-color-light);">Grain Boundary session- Student-run Club of the Materials Engineering Department.</figcaption>
    </figure>
  </div>
  <div class="col-sm mt-3 mt-md-0">
    <figure>
      <picture>
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/NBD.jpg' | relative_url }}" alt="Notebook Drive - Helping underprivileged students in and around Bengaluru, India.">
      </picture>
      <figcaption class="caption" style="text-align: center; margin-top: 5px; font-style: italic; color: var(--global-text-color-light);">Notebook Drive - Helping underprivileged students in and around Bengaluru, India.</figcaption>
    </figure>
  </div>
</div>

</div>

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
