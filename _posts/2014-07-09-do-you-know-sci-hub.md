---
layout: post  
title:  "Do you know Sci-Hub?"
description: "Access scientific articles for free."
date:   2014-07-09 20:00:00
tags: [science, chrome extension]
categories: everything-else
math: false
comments: true
image:
    feature: star_trail_f.jpg
---

Two weeks ago I stumbled across an awesome service that allows one to download paid scientific articles for free. It's called Sci-Hub and you can go ahead and access it here: [sci-hub.org].

You may notice the site is Russian, but it is not a problem, as it has a search field and you probably know how to use Google. Don't fear, just search for a paper you are interested in and it will do a search on Google Scholar. 

So what's the deal? The deal is that you have access to all papers returned in the search, even those you wouldn't have if you did a plain search.

Digging a little deeper, you'll notice by the URL that you aren't, in fact, in Google domain. Sci-Hub puts a ".sci-hub.org" after the original domain, in this case after the "scholar.google.com", giving us the URL "scholar.google.com.sci-hub.org".

Now the nice thing: you can do that yourself to access articles from the main journals and publishers directly from their sites. For an example, suppose you want to access The Mathematical Intelligencer journal: [http://link.springer.com/journal/283]. You'll see that each article costs $39.95 to access, which is way too expensive. So, using the amazing Sci-Hub, we can access it for free just appending "sci-hub.org" after the domain "springer.com": [http://link.springer.com.sci-hub.org/journal/283]. Now you'll notice that you can download every article. Keep in mind that in some cases it will redict you straight to the pdf file, instead of reloading the page with unblocked download links.

This is a really useful service. Information should be more open and the high prices major publishers put on their publications doesn't help. For instance, two years ago Harvard announced they couldn't afford to paid all their journals subscriptions, as the cost approached $3.75M per year, suggesting the academic community to change toward open-access journals (see [Infospace's analysis][1]).

## Chrome extension

To make it even easier, I created a Chrome extension to do the job of appending ".sci-hub.org" for us. 

You can [install it via Chrome store]. 

To use, just go to the article's page you want to access and click the extension button.

EDIT: A friend of mine asked for the extension's code, so here is a link to its [Github repo].

[Github repo]:https://github.com/allanino/sci-hub-fy
[1]:http://infospace.ischool.syr.edu/2012/05/29/academic-journals-are-too-expensive-for-harvard-elsevier-is-mega-greedy-and-why-this-stinks-for-future-librarians/
[http://link.springer.com/journal/283]:http://link.springer.com/journal/283
[http://link.springer.com.sci-hub.org/journal/283]:http://link.springer.com.sci-hub.org/journal/283
[sci-hub.org]:http://sci-hub.org
[install it via Chrome store]:https://chrome.google.com/webstore/detail/sci-hub-fy/gnkckjpgnhkgffcomcocdicefajgeokb
