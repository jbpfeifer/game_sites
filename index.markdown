---
layout: page
title: Joseph Pfeifer Games
---

# Hi, welcome.

This is a small corner of the internet for the games I make.

I first put this site together because app stores ask for the usual official things, but I did not want it to feel like a dead paperwork page.

So this is both: a practical place for privacy, support, and verification, and a simple home for the games themselves.

If you landed here through Google Play, an app listing, or a support link, you are exactly where you are supposed to be.

## What you can find here

- [Impressum / Legal Notice]({{ "/impressum/" | relative_url }})
- [Datenschutzerklaerung / Privacy Notice]({{ "/datenschutz/" | relative_url }})
- [app-ads.txt]({{ "/app-ads.txt" | relative_url }})

## Games

{% for game in site.data.games %}
### {{ game.name }}

- Game page: [Open]({{ "/games/" | append: game.slug | append: "/" | relative_url }})
- Privacy Policy: [Open]({{ game.privacy_policy_url | relative_url }})
- Terms and Conditions: [Open]({{ game.terms_url | relative_url }})
{% endfor %}

## A small note

Game development comes with a surprising amount of admin around it: legal pages, contact details, store verification, and advertising transparency.

That part matters, so it is all here. But I also like the idea of giving my projects a quiet little place of their own.

## Contact

For support, legal, privacy, or business inquiries:

- Name: Joseph Pfeifer
- Email: [joseph.b.pfeifer@gmail.com](mailto:joseph.b.pfeifer@gmail.com)
- Address: Krobotek 44, 8282 Weichselbaum, Austria
