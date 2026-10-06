---
date: '{{ .Date }}'
draft: true
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
description:
layout: blogPost
params:
  showDate: true
  project: 
  galleries:
  galleries_includeAll: false
---
