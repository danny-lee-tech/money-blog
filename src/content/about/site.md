---
title: 'About Site'
description: 'Here is a sample of some basic Markdown syntax that can be used when writing Markdown content in Astro.'
pubDate: 'Aug 10 2025'
heroImage: '../../assets/animeme.jpg'
---
<h3>Considerations</h3>
Prior to this, I was managing a Wordpress instance on AWS Lightsail (which I migrated from EC2 for easy migration/upgrades). To keep costs low, I installed plugins that were free and I used Google's SMTP server to send emails, which isn't ideal to the email quotas. The overall cost was around $8.5/month, which included the domain registration and the Lightsail instance. Using an actual enterprise email server would have cost around an additional $0.10 per 1000 emails (AWS SES), which isn't bad, but I was worried about subscription registration email spam, which had happened in the past, which could have skyrocketed the bill unnecessarily.

I realized that most of my time and effort was protecting against spammers. I could have used plugins to do it, but they would have doubled the overall cost. Again, the reason to protect against spammers was because of the input fields that were on the site, mainly the subscription contact fields and the comment section.

I could have also deployed Wordpress on my home server, but that would mean allowing the world to access my network or buying a separate network just for the server, which would increase cost and effort to setup.

In the spirit of the blog theme, I wanted the upkeep cost and effort to be as low as possible, which is why I decided a static blog site. Less worry about spam attacks (other than maybe DDOS). No worries about email costs.

<h3>Tech Stack Choices</h3>
TBD

<h3>Future</h3>
TBD
