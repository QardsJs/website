---
title: 'Preview: Add a countdown to your special events'
created_at: 2018-10-03T10:53:45.816Z
tags:
  - countdown
  - widget
  - card
  - qards
authors: Romeo Mihalcea
categories: Qards
meta:
  description: >-
    Qards now has a countdown widget that you can use to track your special
    events
  keywords: 'countdown, widget, card, qards'
isPage: false
isFeatured: false
hero:
  alt: countdown widget
  image: /images/uploads/steve-johnson-541507-unsplash.jpg
excerpt: Qards now has a countdown widget that you can use to track your special events
---
I'm a big UFC fan and always find myself converting timezones and trying to see what's the countdown to a certain event. The 229 is the biggest war in UFC history so I check that countdown a lot. Inspired by this I decided to have fun coding such a widget that would allow publishers to create a live countdown of their events.

{"widget":"qards-countdown","config":"eyJldmVudCI6IjIwMTgtMTAtMDdUMDI6MDA6MDAuMDAwWiIsInRpdGxlIjoiVUZDIDIyOSBLaGFiaWIgVlMgTWNHcmVnb3IiLCJzdWJ0aXRsZSI6IkNvdW50ZG93biB0byBiaWdnZXN0IFVGQyBldmVudCBpbiBoaXN0b3J5In0="}

It's simple and could probably make use of some other options but I don't want to pollute the code with useless features so I'll just wait for feedback and see how far we can go with this widget.

{"widget":"qards-section-heading","config":"eyJ0aXRsZSI6IlRoZSBpbXBvcnRhbnQgcGFydHMgZGlzcGxheWVkIiwidHlwZSI6InByaW1hcnkifQ=="}

Apart from the countdown itself, I find equally important to have the date displayed and also for it to be adjusted for my current timezone. It will still show the timezone (even though some might consider this info redundant) to make things absolutely clear.

Working with dates can be very confusing and I had my share with this plugin as some code was doing monkey business underneath but it works now as expected :).
