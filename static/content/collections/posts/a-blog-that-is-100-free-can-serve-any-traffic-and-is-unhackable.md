---
title: 'A blog that is 100% free, can serve any traffic and is unhackable'
created_at: 2018-10-09T19:08:21.817Z
tags:
  - qards
  - free
  - free blog
  - free website
authors: Romeo Mihalcea
categories: Qards
meta:
  description: >-
    With Qards you can have a free blog in a matter of minutes, a blog that is
    100% free, can serve any traffic and is unhackable
  keywords: 'qards, free, free blog, free website'
isPage: false
isFeatured: false
hero:
  alt: 'a blog that is 100% free, can serve any traffic and is unhackable'
  image: /images/uploads/lalo-hernandez-972496-unsplash.jpg
excerpt: >-
  With Qards you can have a free blog in a matter of minutes without having to
  worry about servers, databases or traffic.
---
My initial idea (selling point) with Qards was the widgets that allows publishers to express themselves without restraints. This comes from the fact that I hate WYSIWYG editors with a passion and I hate writing posts that limit me to images and text.

I don't have much time to start open source projects and Qards was born out of necessity for my private projects which all start the same way (website + blog) and I had enough of repeating myself. 

The fact that it all came together at a time when static apps are cool and trendy is a mere coincidence. The fact that it doesn't cost you anything to run a static website is another coincidence. The fact that, when I started working on Qards, **Ghost** announced their version that does similar things and **Wordpress** announced Gutenberg which does similar things is...another coincidence. 

{"widget":"qards-reference","config":"eyJyZWZlcmVuY2UiOiJRYXJkcyB2cyBvdGhlciBwbGF0Zm9ybXMifQ=="}

{"widget":"qards-section-heading","config":"eyJ0aXRsZSI6IkEgYmxvZyB0aGF0IGlzIDEwMCUgZnJlZSIsInN1YnRpdGxlIjoiRnJlZSB0byBydW4sIGZyZWUgdG8gaG9zdCwgZnJlZSB0byBvcGVyYXRlIiwidHlwZSI6InByaW1hcnkifQ=="}

I know the word free is often a catch-phrase but, in this case, it is not. Qards is free, it is based on [GatbyJs](https://www.gatsbyjs.org/) and [Netlify CMS](https://www.netlifycms.org/) which are both free and can be hosted on Netlify or any other CDN without spending a dime.

{"widget":"qards-reference","config":"eyJyZWZlcmVuY2UiOiJQcm9kdWN0IHVwZGF0ZTogTmV0bGlmeSBDTVMgZGVmYXVsdCBjb250ZW50IG1hbmFnZXIifQ=="}

{"widget":"qards-section-heading","config":"eyJ0aXRsZSI6IlNlcnZlIGFueSB0cmFmZmljIiwidHlwZSI6InByaW1hcnkifQ=="}

No matter what your traffic is, hundreds or millions per day, Qards does not sweat...at all. It is compiled at build time and optimized to be fast and scalable. Static websites are just HTML, CSS and JS files that are cached and served closest to the user's location. There is no dynamic content involved and this down the response time to a minimum. No databases or wasted times in requests.

{"widget":"qards-section-heading","config":"eyJ0aXRsZSI6IlNhZmUgYW5kIHNlY3VyZSIsInR5cGUiOiJwcmltYXJ5In0="}

Since your entire website is composed of static files everything is secure and, pretty much, unhackable because...there is nothing to hack.

{"widget":"qards-section-heading","config":"eyJ0aXRsZSI6IlRoZSBjdXJyZW50IHN0YXR1cyBvZiBRYXJkcyIsInN1YnRpdGxlIjoiUmVhbGx5IGNsb3NlIHRvIGEgYWxwaGEgcmVsZWFzZSIsInR5cGUiOiJwcmltYXJ5In0="}

There is still a long road ahead but I'm satisfied with the progress so far. I'm at the point (still pre-release though) where I can just `git clone` and `netlify deploy` to have a fully functional website with blog without having to worry about servers, scaling, databases and monthly payments. Qards is themable now and configurable but I'm not satisfied with the "templating" aspect. It's not that easy to change its design yet and I'll have to address this issue before an official release. I kept putting it further back on my list because I'm not sure how to address the "templating" part on a react project.
