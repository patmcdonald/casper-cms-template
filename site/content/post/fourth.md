---
title: Site set up
---
To familiarise myself with static site generators, I first read through [Netlify's](https://www.netlify.com/) blog and tutorials.

I was already aware of [Jekyll](https://jekyllrb.com/), but I googled generators a bit more, and found that[Hugo](https://gohugo.io/) seemed to be faster, popular and there was an abundance of [tutorials](https://www.youtube.com/channel/UCvmINlrza7JHB1zkIOuXEbw/playlists?sort=dd&view=50&shelf_id=2) out there too.

While building a site from the [Cli](https://www.netlify.com/docs/cli/) would give me the most control and learning opportunties, I wanted to use a GUI CMS to see how a novice could get up and going with a decent site. I chose [NetlifyCMS](https://www.netlifycms.org/) as it was free, open source and ready to roll on [Netlify](https://www.netlify.com/).

[DATOCMS](https://www.datocms.com/) is another API-based option, but I decided to go with what [Netlify](https://www.netlify.com/) offered for now.

I've this whole task challenging for sure, but very, very rewarding. One challenge that stands out for me in the process was setting up OAuth access to GitHub in the [NetlifyCMS](https://www.netlifycms.org/).
I googled this, but I found the answers there weren't getting me results. Then I had a lightbulb moment!
I searched the [Netlify docs](https://www.netlify.com/docs/) and found the right [Authorization callback URL](https://www.netlify.com/docs/authentication-providers/) - BOOM!

One more thing; I couldn't get my post entries in the CMS admin to persist. So, I added them via my GitHub repo. This is a glitch i'm going to look into soon.

Lesson learned: Always look for local docs first!
