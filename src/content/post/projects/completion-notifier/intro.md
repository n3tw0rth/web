---
title: Completion Notifier
description: A implementation to send notifications on process completion
publishDate: "2025-01-21 22:20"
tags: ["rust","completion-notifier","projects"]
---

I started this project to provide a solution to one of the issues i had running terraform runs. When running terrafrom runs i easily get distracted by having to context switch between other tasks.

So here is the result [Completon Notifier](https://github.com/n3tw0rth/completion-notifier). Started as a simple rust implementation to send a desktop notification once a specific process completed, in my use case after ending terraform process either with successful completion  or a error. And it works.

hmm, but sending a desktop notification is not just enough, then i started working improving the program to notificaitons to multiple destinations. With that, now the project make a lot of sense. and there is a lot to work on. Same as the other projects, i am expecting to write some posts on this project in the future, describing the features, improvements and possibly what's next. see you there.
