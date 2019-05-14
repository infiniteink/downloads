---
# Important: If this is not a draft, comment out next line
draft: true
title: {{ replace .Name "-" " " | title }}
date: {{ dateFormat "2006-01-02" .Date }}
# below are non-built-in parameters
subtitle:
tags:
  - foo
  - bar
---

