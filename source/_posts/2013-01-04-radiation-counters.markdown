---
layout: post
title: "Radiation counters"
date: 2013-01-04 22:51
comments: true
categories: hardware
author: Gergely Imreh
---
Recently I was thinking what kind of projects would fit the local environment the best, what technology and science related topics can be on people's mind in Taiwan. One that keeps popping up is the issue of nuclear power and its dangers.

I'm a physicist, and the professors at my [university][university] had a relatively close contact with [Hungary's single nuclear power plant][nuclear], and we had a good training about nuclear energy and engineering. Because of this it annoyed me to no end to see the "No nukes" slogens everywhere in Taiwan for a long time, mostly because I felt people misunderstood things - let's start with that "nukes" are "nuclear weapons", not nuclear power... The more I encountered the protests, and the more I thought about it, there's a point, though. The biggest practical reason for people to oppose that technology is because its implementation here is bad: bad choice of location, bad management, bad practices. I don't know whether it is really so, but those are at least sound things to discuss.

After the [Fukushima disaster][fukushima], I was in touch with a bit with the [Tokyo Hackerspace][thacker] and [Freaklabs][freaklabs] acting on their behalves. We sent some supplies there, and followed their project of making a lot of portable [Geiger radiation counters][geiger]. It was very impressive, and I do belive as well, that everything that makes people be better informed is a good ideas. It was covered in the [Make: blog][thgeiger].

While searching for more about that project, I found [Safecast][safecast], "a global sensor network for collecting and sharing radiation measurements to empower people with data about their environments." Really think that Taiwan could use something similar.

So, how difficult it is to build a Geiger counter? Haven't done one yet myself, from the tutorials on the net it looks relatively straightforward once one has the actual detector unit, while there is still space for innovation if someone wants to make more efficient, cheaper, or scrappy units.

### bGeigie nano

[bGeigie nano][bgeigie], really cool looking one on Google+, that kickstarted my recent thinking. Not much linked there, should find out more about this.

{% img /blogimg/bGeigi500o.jpg 500 375 "bGeigie nano by Pieter Franken" %}

### DIYGeigerCounter

[DIYGeigerCounter][diy] is an entire kit with information, layout, parts and all

{% img /blogimg/diygeigercounter500o.jpg 500 301 "the DIY kit" %}

### Make Blog coverage of DIY Geiger Counters

There's a big collection of [DIY counters][makediy] in another post on Make:. The whole spectrum is represented from prototipy to professional, 

{% img /blogimg/strawberrylinux500o.jpg 500 375 "Strawberry Linux counter" %}

### Instructables

The [Tweeting Geiger Counter][tweeting] was an entry to Adafruit+Instructables Make It Tweet Challenge. Those are two companies that should be very familiar to every maker anyways, I take a lot of inspiration from them.

Instructables have a few more related projects. [Build a Pocket Ionizing Radiation Detector (PIRD)][pocketion] can be very handy to take it with you.

{% img /blogimg/pocketion500o.jpg 500 375 "Pocket Ionizing Radiation Detector" %}

The signal from the counter can also be used for other purposes, like interesting ways to decorate your environment like [this one][decoration1] or [this one][decoration2].

{% img /blogimg/geigerdecor500o.jpg 500 375 "Geiger counter triggered LED decorations" %}

Also, [Nixie-tubes][nixie] just make everything look cooler.

{% img /blogimg/nixiegeiger500o.jpg 500 375 "Nixe tube Geiger counter" %}

## Build one

I'm pretty sure that there are much more versions than a quick research like this could bring up. On the other hand, the basics are pretty much the same for all of them, so the next step should be indeed to make one. Let's see if there's anything worrying in the air (hope not, but better to know:)

This would probably make a very good workshop as well - a bit of physics training, a bit of soldering, networking, data monitoring. Probably the biggest issue would be getting the parts, need to look into sourcing them, and not the eBay-type one-by-one, but somewhere where we can have a few.

[university]: http://www.unideb.hu/ "University of Debrecen, Hungary"
[nuclear]: http://paksnuclearpowerplant.com/ "Paks Nuclear Power Plant"
[fukushima]: http://en.wikipedia.org/wiki/Fukushima_Daiichi_nuclear_disaster "Fukushima on Wikipedia"
[thacker]: http://tokyohackerspace.org/
[freaklabs]: http://freaklabs.org/
[geiger]: http://en.wikipedia.org/wiki/Geiger_counter "Geiger counter on Wikipedia"
[thgeiger]: http://blog.makezine.com/2011/08/09/tokyo-hackerspaces-geiger-counter-project-continues-to-evolve/
[safecast]: http://blog.safecast.org/
[bgeigie]: https://plus.google.com/107771797789108794103/posts/ZZaxz8exNQq
[diy]: https://sites.google.com/site/diygeigercounter/
[makediy]: http://blog.makezine.com/2011/04/14/diy-geiger-counters-take-center-stage/
[tweeting]: http://www.adafruit.com/blog/2011/05/19/netduino-tweeting-geiger-counter-adafruit-instructables-make-it-tweet-challenge/
[pocketion]: http://www.instructables.com/id/Build-a-Pocket-Ionizing-Radiation-Detector-PIRD/
[decoration1]: http://www.instructables.com/id/Geiger-counter-triggered-LED-decorations/
[decoration2]: http://www.instructables.com/id/Star-Jar-Geiger-counter-triggered-LED-decoration-/ "Star Jar Geiger counter triggered LED decoration (2012 remix)"
[nixie]: http://www.instructables.com/id/Nixie-Tube-Geiger-Counter/ "Nixie Tube Geiger Counter"