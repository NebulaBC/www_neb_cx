---
title: "What happened to the old neb.cx?"
description: My servers disappeared overnight.
slug: new-blog
categories:
    - Server hosting
tags:
    - Oracle
    - Data loss
    - Blog
date: 2024-03-02T16:34:42Z
image: cover.png
hidden: false
draft: false
---

## My data is gone

On Wednesday, the 28th, I sat down at my computer for a bit of peaceful work on a personal project of mine. All was going well when I went to fire off a search on my personal SearXNG instance and was met by a browser error. I ignored it for a bit, assuming that it was just a bug and would recover. It did not.

Once I was at a good pausing point in my work, I went to SSH into my server to restart SearX. Huh, that's odd. I couldn't. This isn't the oddest thing ever; the VM in question only had a few gigs of RAM, and it wasn't the strangest thing for it to freeze up, though it hadn't happened in quite a while. I decided to log into my web KVM interface to see if I could log in, so I went to cloud.oracle.com, put in my credentials, and was met by a page full of errors. What I came to find out through talking to support is that Oracle Cloud deleted my account and all of my data for... no reason? None that they're willing to tell me at least. Thankfully, all of my data was not stored on Oracle; part of it is stored on OVH and another part on Azure. The largest problem is that even my cloud infrastructure on other platforms didn't work anymore since Oracle was the gateway for everything.

## What did I lose?

In total, I lost:

- All of my websites that were associated with the NebulaBC username.
- All of the data from my git server that was not synced locally.
- A few Minecraft and other assorted game servers, a portion of which were not backed up anywhere,.
- The database for my image server (the images are stored in S3).
- Most of my hosted services.
- My email server.

## Conclusion

This is a common tale of putting all of your eggs in one basket. My data was fairly distributed between servers and even regions. This was not enough. What I really needed was data that was kept away from Oracle, and I'd personally say that my biggest mistake was using Oracle Cloud in the first place. They seemed like a decent platform at first, but it was a mistake to ever trust them in any capacity with my data. It is a mistake that I will not make again. Next time someone I know is looking for a cloud host, they will not even consider Oracle. I most certainly will not recommend Oracle in a professional capacity either. Their support was awful, and they deleted every last byte of my data without so much as an email first.

I've now moved to a smaller host that is run by real people that I can email or call if there is an issue. I will also be keeping multiple full disk backups of my servers locally from now on to avoid this in the future.
