---
title: "{{ replaceRE "(?:\\d+-){3}" "" .Name | replaceRE "-" " " | title }}"
date: {{ .Date }}
tags:
draft: true
---
