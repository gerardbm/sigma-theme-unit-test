---
layout: post
title: "Post: Image (Linked with Caption)"
categories:
  - Post formats
tags:
  - image
  - Post Formats
---

{% capture fig_img %}
<a data-flickr-embed="true" href="https://www.flickr.com/photos/142409708@N08/32308109307/in/photolist-RdXvin-Yd3xxN-22MjHAn-243XZe2-2fjNpSW-Yin9TQ-2fqtJeh-TN81k9-2hs7Qm7-XW1nMB-EA2xJa-YB5Xp6-Y2s5io-Ma2YbV-FUf75G-24jWTh6-XWyUaM-PjoEc9-nhxqhD-XPZ9Hi-YbiMqn-oJhvco-p5T2Kk-XZowV7-2h46t5h-iGrsd8-ngXaLL-EpKJeD-RvkS23-XFhE87-XRy4yi-dvChEZ-24eYnHo-XXaH74-ebfyi7-XfZ9Sp-X41XWA-24oRXLU-txZU1r-iJJWGZ-nopCEU-nuaepU-2dno7KD-X1zYaU-27aCa6c-Y29Bw4-4PVc2z-vQ16nb-6jAtGJ-pp3Z3U/" title="Barcelona"><img src="https://live.staticflickr.com/7812/32308109307_a46e4257ee_z.jpg" width="640" height="427" alt="Barcelona"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>
{% endcapture %}

{% capture fig_caption %}
Picture from Barcelona.
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>{{ fig_caption | markdownify | remove: "<p>" | remove: "</p>" }}</figcaption>
</figure>
