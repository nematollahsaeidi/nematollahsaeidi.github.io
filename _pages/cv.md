---
layout: cv
permalink: /cv/
title: CV
nav: true
nav_order: 1
cv_pdf: /assets/pdf/Nematollah_Saeidi_CV.pdf # you can also use external links here
cv_format: rendercv # options: rendercv, jsonresume
description: Curriculum vitae of Emad (Nematollah) Saeidi.
toc:
  sidebar: left
---

<style>
  /* ── حذف کامل نقاط timeline در کل صفحه CV ── */

  /* لیست‌های اصلی timeline و list-group */
  .cv ul.list-group,
  .cv ul.timeline,
  .cv ul {
    list-style: none !important;
    padding-left: 0 !important;
  }

  .cv ul.list-group > li.list-group-item,
  .cv ul.timeline > li,
  .cv li.list-group-item {
    list-style: none !important;
    position: relative;
  }

  /* مخفی کردن نقطه و خط عمودی (pseudo-elements) */
  .cv ul.list-group > li.list-group-item::before,
  .cv ul.list-group > li.list-group-item::after,
  .cv ul.timeline > li::before,
  .cv ul.timeline > li::after,
  .cv li.list-group-item::before,
  .cv li.list-group-item::after {
    display: none !important;
    content: none !important;
    width: 0 !important;
    height: 0 !important;
    border: none !important;
    background: none !important;
  }

  /* مخفی کردن ::marker مرورگر */
  .cv ul.list-group > li.list-group-item::marker,
  .cv ul.timeline > li::marker,
  .cv li.list-group-item::marker {
    content: "" !important;
    font-size: 0 !important;
  }

  /* اگر هنوز نقطه باقی مانده بود */
  .cv .timeline-dot,
  .cv .dot,
  .cv .timeline-marker {
    display: none !important;
  }
</style>
