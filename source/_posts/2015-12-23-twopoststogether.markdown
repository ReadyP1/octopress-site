---
layout: post
title: "Two Posts Together: Welp + Whew"
date: 2015-12-23 10:16:57 -0800
comments: true
categories: technical
---
As the title states, this is two posts quickly slapped into one, since I don't have much time.

## Post One: Welp

Well, know I know two things:

- If I have to include a picture that's big, gotta scale it down and include it locally instead of linking "out"
- Certain features of GitHub-Flavored Markdown, as anticipated, don't work. Namely:
  - Emoji
  - Complete and incomplete list items

## Post Two: Whew!

I just saved myself from having to pay some money!

I just realized that in the Rake task that I use to deploy this site from its little folder on the Mac I'm currently borrowing from my grandma, I had it set to use reduced-redundancy file hosting on S3. Currently, I'm on the AWS free tier, which only provides for *standard* hosting on S3. In the same `rake deploy` task that is sending this post up to S3, it's set back to normal. Now, that means:

1. I don't have to pay for this website while it's up and running (Woo! Free stuff!)
2. Higher storage class = more redundancy = higher uptime!
