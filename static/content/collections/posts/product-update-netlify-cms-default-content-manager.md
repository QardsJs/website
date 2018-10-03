---
title: 'Product update: Netlify CMS default content manager'
created_at: 2018-10-03T06:04:18.665Z
tags:
  - netlify cms
  - cms
  - content manager
  - admin
authors: Romeo Mihalcea
categories: Qards
meta:
  description: Netlify CMS is now the default content manager for Qards
  keywords: 'netlify cms, cms, content manager, admin'
isPage: false
isFeatured: false
hero:
  alt: Netlify cms
  image: /images/uploads/netlify-cms3.png
excerpt: Netlify CMS is now the default content manager for Qards
---
After my initial "word out" campaign on producthunt and the amazing (unexpected) success I had with it I had the pleasure of talking with a lot of people that are interested in Qards and came to the conclusion that Netlify CMS would be a better default option as a content manager.

Most of the complaints were from the fact that Qards is advertising a totally free experience and the content manager at the time (Contentful) is a third party with marketing goals that may or may not ditch the free plan which was also limiting some of the users (I found it very generous to be honest). This, coupled with the fact that there is currently an issue with how related content can be added in Contentful, led me to branch out into testing the Netlify CMS a bit and see what it has to offer so I'll state the good and bad.

{"widget":"qards-section-heading","config":"eyJ0aXRsZSI6IlRoZSBnb29kIHN0dWZmIiwic3VidGl0bGUiOiJUaGluZ3MgdGhhdCBJIGxpa2VkIG1vc3QgYWJvdXQgTmV0bGlmeSBDTVMiLCJ0eXBlIjoicHJpbWFyeSJ9"}

{"widget":"qards-section-heading","config":"eyJ0eXBlIjoic2Vjb25kYXJ5IiwidGl0bGUiOiJFdmVyeXRoaW5nIGlzIGZyZWUiLCJzdWJ0aXRsZSI6IlRydWUgdG8gb3VyIGluaXRpYWwgZ29hbCBvZiBoYXZpbmcgYSBibG9nZ2luZyBwbGF0Zm9ybSB0aGF0IGlzIG1vZGVybiwgZmFzdCBhbmQgZnJlZSJ9"}

The CMS is now part of the project itself and is committed with the code. There are some required integrations with the Netlify platform but I'm still 100% on path to providing a totally free platform for bloggers that is modern, fast and can be updated by publishers without coding experience.

{"widget":"qards-section-heading","config":"eyJ0aXRsZSI6IlRoZSBwdWJsaXNoaW5nIGV4cGVyaWVuY2UgaXMgYmV0dGVyIiwidHlwZSI6InNlY29uZGFyeSJ9"}

With Netlify CMS I was able to create the preview exactly how I wanted. The preview panel actually uses the same template and cards that the post page uses which means that your publishers are able to preview their entries without alteration or surprises. This was a real challenge with Contentful because of their current structure but I had amazing experience with these guys over on their slack channel and they are addressing the issue (they were already working on it) by adding the concept of `Structured text` which allows you to embed child content directly into your text. Long story short: it was hard to publish content to Qards from Contentful but they are addressing it in the future.

{"widget":"qards-section-heading","config":"eyJ0eXBlIjoic2Vjb25kYXJ5IiwidGl0bGUiOiJZb3VyIGNvbnRlbnQgaXMgdmVyc2lvbmVkIiwic3VidGl0bGUiOiJNZXJnZSwgcHVsbCwgZGlmZiwgY29tbWl0LCByZXZlcnQifQ=="}

Since the backend is a Github repo you get all the benefits that come with it. We have no databases or servers and everything you create will be pushed to a repository of yours. This means that you can see changes and even go back in time without issues. There are adapters for Bitbucket and Gitlab as well.

The publishing experience does not require any `git` experience. Everything is done by Netlify under the hood. When you hit `Save`, actually, a commit is created and, when you hit `Publish`, a merge of that commit is created.

{"widget":"qards-section-heading","config":"eyJ0aXRsZSI6Ik1vcmUgY29udHJvbCB0byB0aGUgZGV2ZWxvcGVycyIsInR5cGUiOiJzZWNvbmRhcnkifQ=="}

Breaking free of third parties means that I regain more control over the shape and future of Qards. I no longer have to align, adapt or wait for [implementations](https://github.com/gatsbyjs/gatsby/issues/8070) that may change at any time. This allows me to take better decisions since I control and can give shape to the entire experience.

{"widget":"qards-section-heading","config":"eyJ0aXRsZSI6IlRoZSBiYWQiLCJ0eXBlIjoicHJpbWFyeSJ9"}

Most of these points in this section are inconsistencies that will be addressed soon by the maintainers of Netlify CMS so they reflect the current state of the project.

{"widget":"qards-section-heading","config":"eyJ0eXBlIjoic2Vjb25kYXJ5IiwidGl0bGUiOiJJdCdzIGNsb3NlbHkgdGllZCB0byBOZXRsaWZ5Iiwic3VidGl0bGUiOiJXZSdyZSBzdGlsbCBhdCB0aGUgbWVyY3kgb2YgYSB0aGlyZCBwYXJ0eSB3aXRoIG1hcmtldGluZyBnb2FscyJ9"}

Even though I'm a big Netlify fan I can't be sure that their current plans will remain the same. I already see "marketing" pouring in bit by bit (they have to pay salaries after all) and certain restrictions taking place.
