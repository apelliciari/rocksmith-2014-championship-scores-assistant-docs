---
layout: default
title: Home
---

# Welcome to Rocksmith 2014 Championship Score Assistant Docs

This is the documentation of the Score Assistant project for the [Rocksmith 2014 Championship](https://customsforge.com/index.php?/forum/38-rocksmith-championship/).

The frontend app (UI) is located at: https://rocksmith-cf-champ-assistant.web.app/
Dev documentation can be found on the README of the main repository:

https://github.com/rocksmith-2014-championship/rocksmith-2014-championship-scores-assistant

## Features

- **Automatic download from Customsforge Forums**
- **Reliable score OCR via AI**: To extract artist, song, path, accuracy etc.
- **Week Songs Recognition**: Songs of the week are validated.
- **UI Interface for human review**: To fix scores not detected properly
- **Automatic push to the week google sheet**

## Getting Started

* Understand the [possible states](score-states.md) of a score.
* Discover the [flow of the application](flow.md)
* Read about the 3 main components:
    * the [Scraper](scraper.md)
    * the [Detector](detector.md)
    * the [Validator](validator.md) (the UI)