---
title: 'Preview: keep your blog posts relevant and future-proof with smart tokens'
created_at: 2018-10-02T12:31:31.370Z
tags:
  - blog
  - post
  - tokens
authors: Romeo Mihalcea
categories: Qards
meta:
  description: >-
    Showcase of a cool feature we just introduced that allows you to insert
    tokens into certain areas of your post
  keywords: 'Qards, preview, features, blogging platform'
isPage: false
isFeatured: false
hero:
  alt: keep your blog posts relevant and future-proof with smart tokens
  image: /images/uploads/xyhknws.jpg
excerpt: >
  Showcase of a cool feature we just introduced that allows you to insert tokens
  into certain areas of your post
---
Today I had the pleasure of pushing to our repository a small, cool feature that allows you to use smart tokens in certain places when creating a post.

Before going any further I will first try to explain the source of my inspiration for this new feature.

{"widget":"qards-section-heading","config":"eyJ0aXRsZSI6Ikxpc3RzIGFyZSBob3QgcmlnaHQgbm93Iiwic3VidGl0bGUiOiJCbG9nZ2VycyB1c2UgdGhlbSwgR29vZ2xlIHNlZW1zIHRvIGZhdm9yIHRoZW0iLCJ0eXBlIjoicHJpbWFyeSJ9"}

There is a shift in the way bloggers write content. We always try to adapt in order to please the search engines and this new trend seems to favor lists. A lot! It's natural if you think of it. People ask the search engines questions and it responds with "steps" to solve it.

These steps are taken from the articles normally by identifying headings (`h1`, `h2`, `h3` etc) or lists (`ul`, `ol`). Whoever makes a better list wins (now you know why Qards has a table of contents placed on every page).

{"widget":"qards-section-heading","config":"eyJ0aXRsZSI6Ikxpc3RzIGFyZSBhbHNvIGNvdW50ZXJzIiwidHlwZSI6InNlY29uZGFyeSJ9"}

One of the ways to make your content unique is by inserting a counter that represents the items in your list, hence the myriad of articles that are titled like `xxx tools to help you write` where `xxx` stands for a counter.

This is also where I took inspiration from. Qards operates with widgets and everything has a name, type, configuration and order of placement. We know each section and we can count...stuff. This means that you can structure your content in such a way that would allow you to extract a counter out of it.

{"widget":"qards-section-heading","config":"eyJ0aXRsZSI6IldoYXQgdG9rZW5zIGFyZSBhdmFpbGFibGUgYW5kIGhvdyB0byB1c2UgdGhlbSIsInR5cGUiOiJwcmltYXJ5In0="}

The list of supported tokens is currently small because I don't want to add useless things until I get feedback from the community. Qards supports the placing of such tokens in the following sections:

* title
* excerpt
* section-headers (title, subtitle)

{"widget":"qards-section-heading","config":"eyJ0aXRsZSI6IkF2YWlsYWJsZSB0b2tlbnMiLCJ0eXBlIjoicHJpbWFyeSJ9"}

* `{cardsNum}` - this represents the number of cards are in your post where a card is a section that contains multiple widgets (headers. paragraphs, images etc). By controlling the number of cards and how you section your content you can have a title (or any other supported section) that updates itself whenever you change your content.
* `{created_at:dateFormat}` - this is the date when the post was created. The `dateFormat` section supports a string that allows you to control what parts of that date you want. for example: `YYYY` will print out just the year. Have a look at the format() method for moment which is the library we use.
* `{currentDate:dateFormat}` - you probably guessed it, it uses the current date. This one is very useful when you wish to keep your articles relevant. Something like "**Best tools of 2018**" will become "**Best tools of 2019**" when the year changes, without your intervention. This might be quite handy especially when we're talking about a big list of articles under your management.

{"widget":"qards-section-heading","config":"eyJ0aXRsZSI6IkhvdyB0byB1c2UgdGhlc2UgdG9rZW5zIiwic3VidGl0bGUiOiJEZWFkIHNpbXBsZS4uLmp1c3QgcGFzdGUgdGhlbSB3aGVyZSB5b3Ugc2VlIGZpdCJ9"}

{"widget":"image","config":"eyJzcmMiOiIvaW1hZ2VzL3VwbG9hZHMvc2NyZWVuc2hvdC1mcm9tLTIwMTgtMDktMDktMDEtMTktNTUucG5nIiwiYWx0IjoiQXJ0aWNsZSB0b2tlbnMifQ=="}

You have the list of places where tokens are inserted and you know the tokens. Just paste them where you see fit and our platform will do the rest. Since Qards is a static site don't expect to have a real-time date because your assets are compiled and uploaded to production but, with formats that target bigger time frames, you should be fine and ready to conquer ranks.
