---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
slug: {{ now.Format "2006-01-02" }}-{{ .Name | urlize }}
type: posts
draft: true
summary: PUT HERE SUMMARY
categories:
  - default
tags:
  - default
---
