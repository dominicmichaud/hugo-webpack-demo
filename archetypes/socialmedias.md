---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
type: social_link
section: socialmedias
order: {{ sub (len ( where .Site.Pages "Section" "socialmedias")) 1 }}
social_url: ""
icon_path: ''
active: false
---
