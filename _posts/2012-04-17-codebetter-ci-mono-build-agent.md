---
layout: post
title: CodeBetter CI Mono Build Agent
---

I am happy to announce that the [CodeBetter CI Server](http://codebetter.com/codebetter-ci/) now has a [Mono](http://mono-project.com) build agent.  I know what you're all thinking.

<img src="http://ragan.io/images/post-assets/2012-04-17-codebetter-ci-mono-build-agent/time-has-come.jpg"/>

### Background
A couple months back, Andreas Håkansson, AKA [The Code Junkie](https://twitter.com/#!/thecodejunkie), asked me if I'd be up to setting this up.  He wanted to make sure that all changes that [Nancy](http://nancyfx.org) saw didn't break any Mono compatibility.  I happily obliged to help out, but had to get a few other things done first.

I finally got some time this past weekend after putting the finishing touches on the [mope and mono-build release](http://ragan.io/log/introducing-mope-and-mono-build).  I figured, there couldn't be a better time to use what I just coded.

### Who Benefits?
Not only does Nancy and all the current projects on the CodeBetter CI Server benefit from this, but we all do.  This allows us to be more confident that the open-source projects we use within ours, will work no matter what environment we prefer to run our projects in.

If you're an open-source .NET developer, I urge you to [sign-up](http://teamcity.codebetter.com/registerUser.html) and [submit](https://docs.google.com/spreadsheet/viewform?hl=en_US&formkey=dERWT1Nmc08tQ2RzV29aWElWdjg3amc6MQ#gid=0) your project onto the CodeBetter CI Server if you haven't yet.  It will make your project better!

### Who's Paying?
I am also happy to say that all hosting costs for the build agent will be footed by [Monkey Square](http://monkeysquare.org), the parent organization of [Monospace](http://monospace.us).

Enjoy!