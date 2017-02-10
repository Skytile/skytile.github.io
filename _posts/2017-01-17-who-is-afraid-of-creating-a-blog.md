---
layout: post
title:  "Who's Afraid of Creating a Blog?"
date:   2017-01-17 13:16:01 -0600
img: post03.jpg
thumb: thumb03.jpg
categories: meta
---
## Story
I've always had a dream of having my own website. It felt like an online safe-space where I could do anything I wanted and write anything I wanted. There was always something holding me back, though... it's just incredibly frightening to think of all the separate pieces that need to be properly put together to create something functional. I'm not afraid of learning a new language and writing new code because as an Android developer, I know I just need to be able to properly form a Google search. I was just terrified of figuring out the server aspect. It wasn't until a friend of mine was complaining about the difficulty of exactly this problem I've described that another friend made a suggestion that made me finally take action: "What about GitHub Pages?"

I looked into it and found out how easy it was to do the exact thing that made me drag my heels. This is the easiest list of steps I can think of to set up your website/blog. Any optional items are included if you want to use a custom domain.

# Easy Steps
1. (Optional) [Find](https://domainr.com/) and [purchase](https://domains.google/) a domain.
2. Create a [GitHub repository](https://pages.github.com/) that will contain all the code for your website.
3. (Optional) Go to your DNS settings on the site with which you've registered your domain and add the [IP Addresses](https://help.github.com/articles/setting-up-an-apex-domain/#configuring-a-records-with-your-dns-provider) that GitHub gives you to your custom resource records. (It's at the bottom of the Google Domains page in the DNS area.)
4. Enforce HTTPS. Because we love security. There's a checkbox in your repo setting if you're using GitHub's domain. If you have a custom domain, sign up for a free [CloudFlare](https://www.cloudflare.com/) account and just follow their instructions. You will probably need to wait an hour or so to see results.
5. Pick a Jekyll theme in your repo settings.
6. Create an index.html file with anything in the root of your repo. This will be your homepage.
7. Create a \_posts folder in the root of your repo and create a file in the format of YEAR-MONTH-DAY-title.md (Example: 2017-01-17-who-is-afraid-of-creating-a-blog.md).

Congratulations! You can now create blog posts in the exact same way you create beautiful READMEs or Reddit posts. You can obviously get more nitty-gritty in your setup, but I wanted to show you how easy it is to get going! I already had step number one done (remember, it was my dream, so I obviously took a step or two...), and it took me less than a day to set everything up enough to get going. I'm not even paying for anything other than my $12 per year for my domain registration. You can set up your own highly customizable website or blog for free!
