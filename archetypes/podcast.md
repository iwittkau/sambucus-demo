---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
subtitle: ""
date: {{ .Date }}
draft: true
mp3: "{{ .Site.BaseURL }}mp3/episode_{{ replace .TranslationBaseName "-" " " | title }}.mp3"
size: 1024
duration: 0:00
episode: {{ replace .TranslationBaseName "-" " " | title }}
type: "full|trailer|bonus"
chapters: []
---

Short description of the episode.

<!--more-->

{{< hosts >}}
{{< show >}}
{{< /hosts >}}

Longer text after the fold, here.

# Shownotes