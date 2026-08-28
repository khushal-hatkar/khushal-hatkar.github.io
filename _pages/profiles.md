---
layout: profiles
permalink: /people/
title: People
description: members of the lab or group
nav: false
nav_order: 5

profiles:
  # if you want to include more than one profile, just replicate the following block
  # and create one content file for each profile inside _pages/
  - align: right
    image: prof_pic.jpg
    content: about_einstein.md
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>555 your office number</p>
      <p>123 your address street</p>
      <p>Your City, State 12345</p>
  - align: left
    image: prof_pic.jpg
    content: about_einstein.md
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>555 your office number</p>
      <p>123 your address street</p>
      <p>Your City, State 12345</p>
---

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
