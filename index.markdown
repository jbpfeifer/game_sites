---
layout: page
title: Game Legal Pages
---

This site hosts privacy policies and legal documents for my mobile games.

- [Impressum / Legal Notice]({{ "/impressum/" | relative_url }})
- [Datenschutzerklaerung / Privacy Notice]({{ "/datenschutz/" | relative_url }})

## Games

{% for game in site.data.games %}
### {{ game.name }}

- Privacy Policy: [Open]({{ game.privacy_policy_url | relative_url }})
- Terms and Conditions: [Open]({{ game.terms_url | relative_url }})
{% endfor %}

## Contact

For legal/privacy inquiries:

- Name: Joseph Pfeifer
- Email: [joseph.b.pfeifer@gmail.com](mailto:joseph.b.pfeifer@gmail.com)
- Address: Krobotek 44, 8282 Weichselbaum, Austria
