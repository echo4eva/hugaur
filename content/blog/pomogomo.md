+++
title = 'pomogomo'
date = 2025-02-21T12:00:56-07:00
tags = ['tech']
draft = false
+++

## writeup

While reading "Learning Go: An Idiomatic Approach" by Jon Bodner, I used a pomodoro app on my phone that I found really neat to track my time. The only thing that I didn't like about it is that it didn't count excess time once the countdown reached zero, so I decided to make my own as a [side project to practice Go](https://github.com/echo4eva/pomogomo/).

A blogpost by a good mutual [@kennethnym](https://x.com/kennethnym) on Twitter titled ["the art of programming and why i won't use llm"](https://kennethnym.com/blog/why-i-still-wont-use-llm/) shaped my approach for this project. The approach is basically the meme, "this 97 year old diner still serves their coke the old fashioned way." It's a neat, quick, and raw post, you should read it. For this project, I opted out of LLMs and hunted for GitHub projects, Stack Overflow QAs, Reddit threads, and official documentation for correctness. It was fun using my brain again by scrapping resources together into my own solutions. Knowing that I thought of and wrote every line of code feels rewarding.

![Untitled](/pomogomo.png "a")

For UI inspiration, I really love using tools like lazygit and aider, they're just hot to me. For the statistics page I copied lazygit format wise with controls on the left and info on the right of the screen. I made the timer page look default. The TUI library I used has a very basic and simple modal, so I just slapped the timer on there and called it a day. In my opinion, it looks great as is, I like to have it fullscreen on my monitor while reading and studying, it fits.

For implementation inspiration, I used FocusPomo. It had all the features I loved such as time tracking, daily, weekly, monthly stats, and it also had a regular timer option, but it never tracked overtime which was a turn off from me. I'm a big fan of seeing time tracked on videogames from Steam, so I expected accurate tracking. Imagine if you were tapped in for 4 hours but it only counted for 1 hour? Geez!

To wrap it up, I'm glad how this side project turned out. It's a tool that works and one that I've been regularly using. Refreshing my raw problem solving skills was fun. I finished reading "Learning Go" a while ago and picked up another book, so now it's time to apply what I'm learning from it in my next project! 