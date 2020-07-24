---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
type: card
section: services
card_img: "" #/img/services/IMAGE-NAME.extension
order: {{ sub (len ( where .Site.Pages "Section" "services")) 1 }}
---
