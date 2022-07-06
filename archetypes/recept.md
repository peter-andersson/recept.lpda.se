---
date: {{ .Date }}
draft: true
title: "{{ replace .Name "-" " " | humanize | title }}"
från: # Varifrån recept kommer
frånurl: # Url ifall receptet kommer från en webbsida
portioner: 4
tid: 30 # tid i minuter

ingredienser:
- ingredient 1
- ingredient 2

steg:
- steg 1
- steg 2
---
