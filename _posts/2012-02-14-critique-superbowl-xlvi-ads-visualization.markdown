---
title: 'Critique: Superbowl XLVI ads visualization'
date: '2012-02-15T02:02:48.000+00:00'
categories:
  - Data Visualization Thoughts
---

Take a look at <a href="http://hotspots.io/superbowl">this</a> fascinating visualization of last weekend's Superbowl ads created using a new startup tool called <a href="http://hotspots.io">Hotspots.io</a>. What's unique about this visualization is that it provides an interactive, feature-rich multimedia presentation of social media reaction in real time as it relates to live events. The sheer amount of data displayed – from the total reach, to total mentions, to the amount of money each company spent on advertising – is impressive enough in its own right. What's more, because of the way the data is organized into the drop down menu on the left-sidebar, the user is able to view it in separate bits without having to split attention between multiple data points.

All of that goes without mentioning what's most unique about this visualization: Its ability to display Twitter data in a chronological timeline and line graph, complete with YouTube embeds of the ads that corresponded to each point on the timeline. From a programming standpoint, the visualization relies mainly on well-written javascript, which in itself is nothing novel. But what really makes this visualization stand out to me as a developer is its ability to tap into the Twitter API to display various statistics that may not be immediately scrapeable on the surface, such as the rate of increase of mentions and reach in real-time. I'm guessing the developers of the Hotspots.io tool that created this have built some sort of algorithm into their application that takes basic Twitter stream data, computes it into various user-defined statistics, then spits it back out on command. However the developers did it, though, it's impressive. I've submitted my email address to them in hopes that I can be a beta tester of the new tool. I'll let you know when I get my hands on it.

