---
title: "re:mixing Line Drawings with AI"
disable_link: false
excerpt: "using the Dall-E API"
collection: tangents
custom_css: custom-art
classes: art-page
layout: single
---

<style>
.centered-image {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 25%; /* Adjust this value as needed */
}
.large-centered-image {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 75%; /* Adjust this value as needed */
}
.image-gallery {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}
.image-gallery figure {
  margin: 10px;
  width: 25%; /* Adjust this value as needed */
}
figcaption {
  font-size: 1.2em; /* Increase caption size */
  text-align: center; /* Center the caption text */
  margin-top: 5px; /* Add some space between image and caption */
}
.centered-caption {
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>

I wanted to see if I could get anything interesting from remixing my partner's unfinished line drawings. 

<figure class="centered-caption">
  <img src="{{ site.baseurl }}/images/art/baker.png" alt="Original line drawing of a baker" class="centered-image">
  <figcaption>Original line drawing by my partner</figcaption>
</figure>

## AI Remixes

I asked the DALL-E API to remix it, masking various parts of the image and auto-generating prompts using GPT-3. Here are the results:

<div class="image-gallery">
  <figure>
    <img src="{{ site.baseurl }}/images/art/first_edits/edits_1_545cd3b7.png" alt="AI-remixed line drawing: sushi chef">
    <figcaption>Sushi chef?</figcaption>
  </figure>

  <figure>
    <img src="{{ site.baseurl }}/images/art/first_edits/edits_4_ab1adbd3.png" alt="AI-remixed line drawing with text attempt">
    <figcaption>Love it when AI tries to do text</figcaption>
  </figure>

  <figure>
    <img src="{{ site.baseurl }}/images/art/first_edits/edits_2_12896581.png" alt="AI-remixed line drawing with color">
    <figcaption>A splash of color, please</figcaption>
  </figure>
</div>

To be honest, they aren't that cool. My sense is that the appeal of generative AI in art is that it brings the cost (and skill) of remixing towards zero. So I decided to make a collage of many of the remixes — which would maybe drive a gestalt

<figure class="centered-caption">
  <img src="{{ site.baseurl }}/images/art/baker/collage_3.png" alt="Collage of AI-remixed drawings" class="large-centered-image">
  <figcaption>Collage of AI remixes</figcaption>
</figure>

She didn't seem particularly moved by any of this, but was quite supportive