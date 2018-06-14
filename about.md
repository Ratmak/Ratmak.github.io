---
layout: page
title: Tom
permalink: /about/
tags: about
---

<style>
  .bkgtom {
    {::comment} display: block;
    width: 200px;
    height: 100vh; {:/comment}
    float: left;
    background: url("/images/lightlinetom.svg") left center no-repeat;
    background-size: contain;
    shape-outside: url("/images/lightlinetom.svg");
    shape-margin: 18px;
  }
  @media screen and ( max-width: 750px ) {
    .bkgtom {
      width: 100vw;
      height: 100vh;
      position: fixed;
      z-index: -1;
      opacity: 0.2;
      float: none;
      background-position: top center;
      top: 150px;
      left: 0px;
    }
  }
</style>

<span class="bkgtom"></span>Tom is a friendly guy from New Jersey who likes music and some other things. He works all day and parties[^1] all night, just like you do. He's interested in old stuff and new stuff and is always looking to learn.

[^1]: in this context, *partying* is defined as "sleeping poorly - as with sleep apnea"

This website ~~was~~ is probably still being slapped together using a Jekyll theme named Pixyll that was crafted with <3 by [John Otander](http://johnotander.com)
([@4lpine](https://twitter.com/4lpine)).

I encourage you to check out Pixyll's [Github repository](https://github.com/johnotander/pixyll) to download it,
request a feature, report a bug, or contribute. It's free, and open source
([MIT](http://opensource.org/licenses/MIT)).
