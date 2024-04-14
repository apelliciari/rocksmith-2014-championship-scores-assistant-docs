---
layout: default
title: The Scraper
---

# The Scraper

The main goal of the scraper is to grab all the images in the posts of a championship' week and save them to [[firestore]].

Some notes about it:

* it saves every image that it's not quoted (because we can assume that that image should be already scraped)
* it saves also all the information related to the image (author, commentId, link, date, etc)
* it splits multiple images from the same post and give a serial number to them
* it doesn't discriminate between images (if they are a score or not), that's the job of the [[detector]]

It's written in Typescript and uses Puppetter to scrape the images.
It runs as Google Cloud Function in prod.
