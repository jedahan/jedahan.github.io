---
layout: default
title: Home
---

a [hacker][me] of Computational Machinations, Digital Arts and Electronic Sounds, hailing from [Brooklyn][]

I am a programmer who likes to connect random inputs and outputs to see what people will do with them. I often take virtual streams and provide them physical facilities to exaggerate their impact on our lives. I am equally uncomfortable coding in C, C++, Rust, Javascript, Coffeescript, Python, Piet, Basic, Hypercard, and Bash. I painted a simple [echo program][] and could very easily see myself holed up for the winter just with canvas and wine.

Some communities I'm a part of and love include [the school for poetic computation](sfpc.io), [hacker school](hackerschool.com), [arthackday](arthackday.net), [the medialab at the met](http://www.metmuseum.org/about-the-museum/museum-departments/office-of-the-director/digital-media-department/digital-underground/posts/2013/introducing-the-media-lab), [itp camp](http://itp.nyu.edu/camp2014/). If you are interested in chatting about any of these, please reach out!

## [Resume](/resume)

A more traditional [resume](/resume), [pdf](/resume.pdf)

## [Blog](/blog)

{% for post in site.posts limit: 5 %}
- [{{post.title}}]({{post.url}})
> {{ post.excerpt }}
{% endfor %}
- [...more posts](/blog)

Creations and Consumptions
--------------------------
- [code][github]
- [short thoughts][twitter] and [slightly longer thoughts](/blog)
- [where i've been][foursquare]
- [oscillations][soundcloud], [static visuals][flickr], and [motion pictures][youtube]

Endeavours
----------
- teaching at [parsons][]
- did not graduate [hackerschool][] :-P
- attended the [school for poetic computation][]: first class
- taught at the [school for poetic computation][]
- founded [Island Labs][labs], a [long island][] [hackerspace][]
- maintain an unofficial package repository for [exherbo][] linux
- symposium [on programming old computers](https://www.youtube.com/watch?v=N6lX-Gxo3uM)

<div style="display: none;">
  <p>This is for <a href="https://indieauth.com">IndieAuth</a> support.</p>
  <link rel="authorization_endpoint" href="https://indieauth.com/auth">
  <a rel='me' href="https://github.com/jedahan">github</a>
</div>

[exherbo]: http://exherbo.org
[foursquare]: http://foursquare.com/jedahan
[facebook]: http://facebook.com/jedahan
[flickr]: http://www.flickr.com/photos/37234044@N07/sets/
[github]: http://github.com/jedahan
[hackerspace]: http://en.wikipedia.org/HackerSpace
[labs]: http://islandlabs.org
[long island]: https://www.google.com/maps/place/Long+Island/
[me]: images/me.jpg
[brooklyn]: https://www.openstreetmap.org/node/2946313743#map=14/40.6604/-73.9946&layers=T
[reddit]: http://www.reddit.com/user/jedahan/
[soundcloud]: http://soundcloud.com/jedahan
[tumblr]: http://jedahan.tumblr.com
[meetup]: http://www.meetup.com/members/14261502/
[twitter]: http://twitter.com/jedahan
[youtube]: http://youtube.com/jedahan
[echo program]: piet.png
[parsons]: http://jedahan.github.io/pucd2035d
[hackerschool]: http://hackerschool.com
[school for poetic computation]: http://sfpc.io
