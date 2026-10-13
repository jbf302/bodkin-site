---
layout: page
title: Bodkin
description: Bodkin is a needlepoint app for iPad. Stitch with Apple Pencil on real-looking wool, then stitch it for real.
---
<section class="hero">
  <div>
    <h1>Needlepoint, on your iPad.</h1>
    <p>Pick a thread and stitch with Apple Pencil, one hole at a time. Plump wool-textured stitches, real DMC thread colors, and a calm rhythm. No accounts, no tracking.</p>
    <span class="badge">Coming soon to the App Store</span>
  </div>
  <video src="{{ '/assets/video/stitch.mp4' | relative_url }}" poster="{{ '/assets/video/stitch-poster.jpg' | relative_url }}" autoplay loop muted playsinline aria-label="Stitching a canvas with Apple Pencil"></video>
</section>

{% assign shots = "01-stitch,02-wool,03-canvases,04-finish,05-for-real,06-learn" | split: "," %}

<div class="gallery">
{% for s in shots %}<a href="{{ '/assets/img/' | append: s | append: '.jpg' | relative_url }}"><img src="{{ '/assets/img/' | append: s | append: '-thumb.jpg' | relative_url }}" alt="Bodkin screenshot {{ forloop.index }}" loading="lazy"></a>
{% endfor %}
</div>

## What you can do

<div class="features">
<div class="feature"><h3>Stitch with Apple Pencil</h3><p>Fingers pan and zoom, the Pencil stitches. Hover shows the hole you're aiming for, and double-tap switches between needle and unpick.</p></div>
<div class="feature"><h3>Start anywhere</h3><p>Pick a painted canvas, turn a photo or a stitch chart into a pattern, or design on a blank mesh in 10, 13 or 18 count.</p></div>
<div class="feature"><h3>Real threads</h3><p>Photo colors are matched to actual DMC threads. Mark the skeins in My Stash and shopping lists ask only for what's missing.</p></div>
<div class="feature"><h3>Stitches that feel hand-made</h3><p>Tent, cross, gobelin and French knot are free. Bargello, brick, mosaic, Scotch and Smyrna come with the optional Stitch Pack. Hand-stitched mode makes pressure set the tension.</p></div>
<div class="feature"><h3>Stitch it for real</h3><p>Get a shopping list with DMC and Anchor numbers, canvas and stretcher bar sizes, plus a printable symbol chart.</p></div>
<div class="feature"><h3>New to needlepoint?</h3><p>A two-minute practice lesson and a short primer on the craft, with a practice swatch for every stitch.</p></div>
</div>

## Questions

<dl class="faq">
<dt>Which devices does it run on?</dt><dd>iPad, with Apple Pencil recommended. A finger-stitching mode is available if you don't have one.</dd>
<dt>What does it cost?</dt><dd>The app and its painted canvases are free. The Stitch Pack of decorative stitches is a one-time optional purchase.</dd>
<dt>Do I need an account?</dt><dd>No. Your projects stay on your iPad, and the app doesn't collect any data. See the <a href="{{ '/privacy/' | relative_url }}">privacy policy</a>.</dd>
</dl>

Press or creator? Grab images and video from the [press kit]({{ '/press/' | relative_url }}). Need help? See [support]({{ '/support/' | relative_url }}).
