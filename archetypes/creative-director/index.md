---
date: '{{ .Date }}'
draft: false
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
description:
params:
  showDate: true
  project: 
  galleries:
  credits:
    - name: "Dor Pe'er"
      role: "Creative Director"
    - name: "Camille Gregoire"
      role: "Creative Direction"
---

{{< vimeo 000000 >}}