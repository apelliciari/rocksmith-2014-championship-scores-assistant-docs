---
layout: default
title: The Detector
---

# The Detector

The main goal of the detector is to take the images and try to recognized and classify them into valid scores.

It uses Cloud Vision to detect text and a lot of regular expression to find the desired text.

Then, if there's not exact match with the songs of the weeks, it uses GPT to find a match.

It's written in python, runs on Docker in local and as a Google Cloud Function in prod.