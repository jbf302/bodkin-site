---
layout: page
title: Bodkin Press Kit
permalink: /press/
description: Screenshots, videos and descriptions for writing about Bodkin, a needlepoint app for iPhone and iPad.
---
Feel free to use these when writing about Bodkin. Contact: [bodkin.support@gmail.com](mailto:bodkin.support@gmail.com)

## About

**One line:** Bodkin is a needlepoint app for iPhone and iPad.

**Short:** Bodkin lets you stitch painted canvases, photos or your own designs with a fingertip or Apple Pencil. Stitches look like real wool, colors match actual DMC threads, and when you finish you can get a shopping list and printable chart to stitch the design for real. It has no accounts and collects no data.

**Facts:** iPhone and iPad (including iPhone Duo) · free, with two optional one-time purchases: Bodkin Pro ($14.99 US) and the Stitch Pack ($4.99 US), no subscription · a growing collection of free painted canvases · 10, 13 and 18 mesh · stitch types: tent, cross, gobelin, French knot, bargello, brick, mosaic, Scotch, Smyrna · no account, no ads, no data collected.

## Screenshots

{% assign shots = "01-stitch,02-wool,03-canvases,04-finish,05-for-real,06-learn" | split: "," %}

**iPhone** (6.9", 1320 × 2868 PNG)

<div class="kit phone">
{% for s in shots %}<figure><a href="{{ '/assets/press/screenshots/iphone/' | append: s | append: '.png' | relative_url }}"><img src="{{ '/assets/img/iphone/' | append: s | append: '-thumb.jpg' | relative_url }}" alt="Bodkin on iPhone, screenshot {{ forloop.index }}" loading="lazy"></a><figcaption>{{ s | slice: 3, 20 | replace: "-", " " | capitalize }} (PNG)</figcaption></figure>
{% endfor %}
</div>

**iPad** (13", 2064 × 2752 PNG)

<div class="kit">
{% for s in shots %}<figure><a href="{{ '/assets/press/screenshots/ipad/' | append: s | append: '.png' | relative_url }}"><img src="{{ '/assets/img/ipad/' | append: s | append: '-thumb.jpg' | relative_url }}" alt="Bodkin on iPad, screenshot {{ forloop.index }}" loading="lazy"></a><figcaption>{{ s | slice: 3, 20 | replace: "-", " " | capitalize }} (PNG)</figcaption></figure>
{% endfor %}
</div>

## Videos and social images

<div class="kit">
<figure><a href="{{ '/assets/press/video/stitch-square-1080.mp4' | relative_url }}"><img src="{{ '/assets/video/stitch-poster.jpg' | relative_url }}" alt="Square video"></a><figcaption>Square video, 1080 × 1080 MP4</figcaption></figure>
<figure><a href="{{ '/assets/press/video/stitch-vertical-1080x1920.mp4' | relative_url }}"><img src="{{ '/assets/video/stitch-poster.jpg' | relative_url }}" alt="Vertical video"></a><figcaption>Vertical video, 1080 × 1920 MP4</figcaption></figure>
<figure><a href="{{ '/assets/press/video/stitch-square.gif' | relative_url }}"><img src="{{ '/assets/video/stitch-poster.jpg' | relative_url }}" alt="Animated GIF"></a><figcaption>Animated GIF</figcaption></figure>
<figure><a href="{{ '/assets/press/social/square-1080.png' | relative_url }}"><img src="{{ '/assets/press/social/square-1080.png' | relative_url }}" alt="Square post image" loading="lazy"></a><figcaption>Square post, 1080 × 1080</figcaption></figure>
<figure><a href="{{ '/assets/press/social/portrait-1080x1350.png' | relative_url }}"><img src="{{ '/assets/press/social/portrait-1080x1350.png' | relative_url }}" alt="Portrait post image" loading="lazy"></a><figcaption>Portrait post, 1080 × 1350</figcaption></figure>
<figure><a href="{{ '/assets/press/social/landscape-1920x1080.png' | relative_url }}"><img src="{{ '/assets/press/social/landscape-1920x1080.png' | relative_url }}" alt="Landscape post image" loading="lazy"></a><figcaption>Landscape post, 1920 × 1080</figcaption></figure>
<figure><a href="{{ '/assets/press/social/story-1080x1920.png' | relative_url }}"><img src="{{ '/assets/press/social/story-1080x1920.png' | relative_url }}" alt="Story image" loading="lazy"></a><figcaption>Story, 1080 × 1920</figcaption></figure>
<figure><a href="{{ '/assets/press/social/link-card-1200x630.png' | relative_url }}"><img src="{{ '/assets/press/social/link-card-1200x630.png' | relative_url }}" alt="Link card" loading="lazy"></a><figcaption>Link card, 1200 × 630</figcaption></figure>
</div>
