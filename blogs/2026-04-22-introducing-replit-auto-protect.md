---
title: "Introducing Replit Auto-Protect"
url: "https://blog.replit.com/auto-protect"
date: "Wed, 22 Apr 2026 16:15:00 GMT"
author: ""
feed_url: "https://blog.replit.com/feed.xml"
---
Modern applications rely heavily on external packages, often open source and maintained by third parties. When new vulnerabilities - tracked as CVEs (Common Vulnerabilities and Exposures) are disclosed, teams need to act quickly before they can be exploited.

Previously, staying secure required builders to monitor CVEs constantly and manually update dependencies. Now, Replit handles this for you. When a new critical CVE is identified, we automatically check it against your project’s dependencies. If a match is found, once you’ve opted in, we will:

Have Replit Agent automatically prepare and test a patch

Send you a direct link over email to apply the change proposed in the patch

This new workflow allows you to keep your apps safe in two clicks: one to apply changes from the patch, another to republish your app.
