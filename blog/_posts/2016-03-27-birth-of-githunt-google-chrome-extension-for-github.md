---
layout: post
title: Birth of Githunt - A Google Chrome extension for Github
comments: true
---

I usually scour Github in my free time in the gaze of what interesting stuff people have been building. Not only that it helps me *sort of* keep up with what's happening around and broaden my horizon, but also more often than not I come across some really interesting and handy project for use in my projects. 

## The Problem

You might be aware of [Github's trending page](http://github.com/trending) that shows the trending Github projects. But there are a few *snags* in using it to keep up with the trending projects

- It only shows the currently (current day, week or month) trending projects. You can't check what was trending in the past
- There is no detail such as number of forks, stars and issues on the page. You have to navigate to the project page for that.
- Most important of all, being lazy, filled with the *sluggishness*, one might not visit the website specifically to check the trending page and easily miss to discover stuff.


## Birth of Githunt

I had an idea to create a browser extension that will replace your browser's new tab with trending opensource projets on Github so that you can feast your eyes with the awesome stuff people are building in the technologies of your liking without any effort.

This weekend, I finally got the time to work on my idea and behold, [Githunt](http://github.com/kamranahmedse/githunt) is born.

> Githunt is an extension that replaces the new tab of your browser with the trending github repositories. 

![Banner](http://i.imgur.com/ha6ti77.png)

You can look through the trending repositories for any technology of your liking and for any period of time; be it in the present or past. By default it shows the trending repositories (most starred repositories created in the given period of time) for the last week and as you keep scrolling, you will be presented with the popular repositories of the consecutive past weeks.

There are language and time jump filters, all you have to do is select how you would like to see the repositories (monthly, weekly or yearly) and the language, it will remember your choice and will show you the trending repositories in that category whenever you will open the new tab. 

Below is how your new tab will look like after installation of extension:

![Githunt - New Tab](http://i.imgur.com/FA2OTWX.png)

## Installation

The extension has been deployed on the Chrome Webstore and you can install it by [following this link](https://goo.gl/e7YP1h). Also, if you like to take a look at what's powering it, [source code is available on github](http://github.com/kamranahmedse/githunt).

## What do people say?

I posted the link to the project repository on [Reddit](https://www.reddit.com/r/javascript/comments/4byk8v/githunt_chrome_extension_to_replace_your_new_tab/) yesterday and it turned out that people were looking for something like this and it had been trending all day yesterday. Also, it has been on the top of the list [amongst the trending github projects](https://github.com/trending/html) since yesterday (Update &ndash; Now 5th).

So go ahead, [install the extension and go for the hunt](http://github.com/kamranahmedse/githunt).

## Can I help?

You sure can - the source code is available on [Github](http://github.com/kamranahmedse/githunt). This is the very first version of the extension, so there might be bugs, quirks or unexpected behavior. Also I wanted to put it out as soon as possible so I did not pay heed to aesthetics, need to improve that as well. If you are willing to help, be sure to get in touch with me.