---
layout: cv
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: /assets/pdf/Khushal_Hatkar_CV.pdf
cv_format: rendercv # options: rendercv, jsonresume
toc:
  sidebar: left
---

<script>
document.addEventListener("DOMContentLoaded", function() {
  document.querySelectorAll('.interest-item, .skill-item').forEach(function(item) {
    let strong = item.querySelector('strong');
    if (strong) {
      let textNode = strong.nextSibling;
      if (textNode && textNode.nodeType === 3) {
        let text = textNode.textContent.trim();
        if (text && text.includes('|')) {
          let items = text.split('|').map(s => s.trim()).filter(s => s.length > 0);
          let ul = document.createElement('ul');
          ul.style.marginTop = '0.5rem';
          ul.style.marginBottom = '0.5rem';
          ul.style.paddingLeft = '1.5rem';
          items.forEach(function(i) {
            let li = document.createElement('li');
            li.textContent = i;
            ul.appendChild(li);
          });
          textNode.remove();
          item.appendChild(ul);
        }
      }
    }
  });
});
</script>
