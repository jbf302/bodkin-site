---
layout: page
title: Bodkin
description: Bodkin is a needlepoint and cross-stitch app for iPhone and iPad. Stitch with a fingertip or Apple Pencil in real-looking wool or floss, then stitch it for real.
---
<section class="hero">
  <div>
    <h1>Needlepoint and cross-stitch, on your iPhone and iPad.</h1>
    <p>Pick a thread and stitch one hole at a time with a fingertip or Apple Pencil. Plump wool on needlepoint canvas or little crosses on Aida, real thread colors, and a calm rhythm. No accounts, no tracking.</p>
    {% if site.app_store_url %}<a class="badge" href="{{ site.app_store_url }}">Download on the App Store</a>{% else %}<span class="badge">Coming soon to the App Store</span>{% endif %}
  </div>
  <video src="{{ '/assets/video/stitch.mp4' | relative_url }}" poster="{{ '/assets/video/stitch-poster.jpg' | relative_url }}" autoplay loop muted playsinline aria-label="Stitching a whale canvas in Bodkin"></video>
</section>

{% assign shots = "01-stitch,02-wool,03-canvases,04-finish,05-for-real,06-learn" | split: "," %}

<h2 class="gallery-title">On iPhone</h2>
<div class="gallery gallery-phone">
{% for s in shots %}<a href="{{ '/assets/img/iphone/' | append: s | append: '.jpg' | relative_url }}"><img src="{{ '/assets/img/iphone/' | append: s | append: '-thumb.jpg' | relative_url }}" alt="Bodkin on iPhone, screenshot {{ forloop.index }}" loading="lazy"></a>
{% endfor %}
</div>

<h2 class="gallery-title">On iPad</h2>
<div class="gallery">
{% for s in shots %}<a href="{{ '/assets/img/ipad/' | append: s | append: '.jpg' | relative_url }}"><img src="{{ '/assets/img/ipad/' | append: s | append: '-thumb.jpg' | relative_url }}" alt="Bodkin on iPad, screenshot {{ forloop.index }}" loading="lazy"></a>
{% endfor %}
</div>

## What you can do

<div class="features">
<div class="feature"><h3>Stitch your way</h3><p>Stitch with a fingertip on iPhone or iPad. On iPad, Apple Pencil takes over the stitching as soon as it touches the screen: hover shows the hole you're aiming for, and double-tap switches between needle and unpick.</p></div>
<div class="feature"><h3>Start anywhere</h3><p>Pick a painted canvas or a cross-stitch chart, turn a photo or a picture of a chart into a pattern, import an .oxs chart file, or design your own on blank canvas or Aida.</p></div>
<div class="feature"><h3>Real threads</h3><p>Photo colors are matched to real threads: Appleton or Persian wool or DMC for needlepoint, DMC floss for cross-stitch. Mark the skeins in My Stash and shopping lists ask only for what's missing.</p></div>
<div class="feature"><h3>Stitches that feel hand-made</h3><p>Needlepoint's tent, cross, gobelin and French knot are free, and so are cross-stitch's full and half crosses, ¾ and ¼ stitches, backstitch and French knots. Beads are free in both crafts. In Hand-Stitched mode your pull sets each stitch's tension, and Even Tension keeps things neat while you get the feel of it.</p></div>
<div class="feature"><h3>Design mode</h3><p>Paint a canvas or chart your own design square by square, with draw, erase, fill and pick, in a choice of brush sizes. Swap one thread for another, or merge two, everywhere at once.</p></div>
<div class="feature"><h3>Track a real project</h3><p>Stitching a chart on real fabric or canvas? Mark squares off as you go, keep your place with a row guide, park your threads, and see your pace and a projected finish date.</p></div>
<div class="feature"><h3>Stitch it for real</h3><p>Get a shopping list with real thread numbers and the canvas or Aida you need, plus a printable symbol chart.</p></div>
<div class="feature"><h3>New to stitching?</h3><p>A two-minute practice lesson, plus Needlepoint 101 and Cross-Stitch 101, with a practice swatch for every stitch.</p></div>
<div class="feature"><h3>Folds with you</h3><p>On iPhone Duo, stitch on either screen in any orientation. Half-fold it like a book and the controls sit on one side, your stitching on the other.</p></div>
<div class="feature"><h3>Made for everyone</h3><p>VoiceOver can stitch along with you and tell you when a color is finished. Voice Control, Dynamic Type, Increase Contrast, Reduce Motion and Smart Invert are supported throughout.</p></div>
</div>

## Questions

<dl class="faq">
<dt>Which devices does it run on?</dt><dd>iPhone and iPad. Apple Pencil is optional: a fingertip works everywhere.</dd>
<dt>What does it cost?</dt><dd>The app, its painted canvases and charts, and the basic stitches of both crafts are free, and so are your first five projects from photos, chart pictures or blank canvas or Aida, and your first imported chart file. Two optional one-time purchases, with no subscription: <strong>Bodkin Pro</strong> (unlimited photo, chart and blank projects, as many imported chart files as you like, Design mode on any design, lettering names and dates onto a design, a choice of stitched app icons, and the Stitch Pack stitches) and the <strong>Stitch Pack</strong> (decorative and specialty stitches for both crafts: ten for needlepoint, like Bargello, Scotch and Milanese, and five for both, like Double Cross, Rhodes and Long-Arm Cross). Both work with Family Sharing.</dd>
<dt>Do I need an account?</dt><dd>No. Your projects stay on your device, and the app doesn't collect any data or show ads. See the <a href="{{ '/privacy/' | relative_url }}">privacy policy</a>.</dd>
</dl>

What's in the latest version? See [what's new]({{ '/whats-new/' | relative_url }}). Press or creator? Grab images and video from the [press kit]({{ '/press/' | relative_url }}). Need help? See [support]({{ '/support/' | relative_url }}).
