---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
type: card
section: services
order: {{ (where .Site.Pages "Section" "services" ) | len }}
---
