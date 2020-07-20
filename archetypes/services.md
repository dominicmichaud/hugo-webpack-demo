---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
type: card
section: services
card_img: "https://bulma.io/images/placeholders/1280x960.png" #/img/services/IMAGE-NAME.extension
order: {{ sub (len ( where .Site.Pages "Section" "services")) 1 }}
---
