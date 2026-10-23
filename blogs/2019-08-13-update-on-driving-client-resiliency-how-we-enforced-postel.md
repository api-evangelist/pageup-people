---
title: "Update on Driving Client Resiliency: How we enforced Postel’s Law by violating Postel’s Law"
url: "https://medium.com/pageup-tech/update-on-driving-client-resiliency-how-we-enforced-postels-law-by-violating-postel-s-law-7cd51bf15baa?source=rss----84affb3f167c---4"
date: "2019-08-13"
author: "Tal Rotbart"
feed_url: "https://medium.com/feed/pageup-tech"
---
pngtree.com " src="https://cdn-images-1.medium.com/max/1024/1*GpFw_wwlcRr4n5dQ-PcnJg.jpeg" /> Over three years ago, we embarked on an experiment of utilising counter-measures to prevent badly written clients to our RESTful APIs. Bad clients are ones that make unhealthy assumptions about property ordering and presence, and violate Postel’s Law , thus creating a blocker to having evolvable APIs. Since then, new APIs that we’ve released have implemented these counter-measures (which we’ve open-sourced here ) and I’m happy to report that they seem to be working.
