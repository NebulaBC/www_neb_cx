---
title: "GitHub pages... Should I get pro?"
description: SourceHut Pages?? Cron jobs!?
slug: i-hate-github-but-it-feels-so-good
tags:
    - 100DaysToOffload
date: 2024-03-05T18:22:00Z
hidden: false
draft: false
---

Once upon a time my blog page was just a [Hugo](https://gohugo.io/) static site... wait, it still is. Well, either way, it was just running on a VPS and I just edited it through SSH+Vim. Now after my stuff has been mixed around, it's running on GitHub pages. It's been a very nice setup, since I can edit from any editor on any PC and push to GitHub with an automatic rebuild. I love this workflow, besides one slight issue.

I use a lot of drafts. Every post I make for a blog is going to have a draft, and may be written over multiple days. This git setup means that I am stuck either immortalizing my drafts in my git repo, or I have to find some way to run with this workflow privately. Now out of my options I could
a) Fork over $4 a month to GitHub for pro - This is not my ideal solution, I don't like using GitHub at all, and want to pay them money even less regardless of if they let me make a private repo with GitHub pages. 
b) I could set up a git repo on my server, and put it right in my NGINX site path. I could then make a cron job to rebuild it - This would probably be the most practical solution, that said, I'm not entirely focused with practical in this case. I like having a site that is hosted, and I am willing to pay a few dollars to have my site update right away and have a generally better experience.
and c) The last option I've been thinking of is purchasing a [SourceHut](https://sourcehut.org/) account and trying to migrate my blog to SourceHut's pages/CI system - This is a very tempting option for me. SourceHut is a git platform built by [Drew DeVault](https://drewdevault.com/) and seems much more ethical than GitHub... Now, I *do already* run my own git server, and have for over two years. Although I've quite enjoyed that and it *has* been a better solution than GitHub, I think that maybe SourceHut is worth a shot, especially since it includes a CI unlike Gitea/Forgejo. If it can properly build and serve my Hugo page, I will be content.

There may be other solutions that I can not think of, and there may be other software that I can self-host. If this is the case, and you can think of something that I should try, shoot me an email (editing: I actually don't have an email server up right now. My discord is `nebulabc`). I'd love to hear what's out there, and there might be something right in-front of my nose. For now I'm going to be trying out SourceHut to see if it can do the job for me, if it can I *may* consider moving my git content over, or at least mirroring my repos. SourceHut's takes on a traditional git platform (like not including client side JS) are very interesting to me, but if anyone has any opinions on the platform, feel free to speak your voice. I will be doing more research before I settle on a "forever" host.
