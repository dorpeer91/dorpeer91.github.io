---
date: '{{ .Date }}'
draft: false
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
description:
params:
  showDate: true
  project: 
  galleries:
  galleries_includeAll: false
  credits:
    - name: "Dor Pe'er"
      role: "Storyboard, Design and Animation"
    - name: "Camille Gregoire"
      role: "Creative Direction"
    - name: "Big Picture Lab"
      role: "Studio"
    - name: "HPE"
      role: "Client"

---

{{< vimeo 000000 >}}