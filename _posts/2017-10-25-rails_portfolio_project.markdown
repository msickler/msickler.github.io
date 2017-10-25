---
layout: post
title:      "Rails Portfolio Project "
date:       2017-10-25 19:45:36 -0400
permalink:  rails_portfolio_project
---


Oh, where to begin. 
I started blank, I just couldn't think of what the project should be about. And I did not want to make a lifeless project that meets the criteria but has nothing fun about it. Nope, I've always been a writer, won my schools' creative writing competitions...  It's probably my favorite thing in the world, creating new things (mostly, before starting here, stories). So, I really will not take a lifeless project for a portfolio project unless I have absolutely no choice.
Anywho, when pondering what to develop, I asked what worked with the previous two projects. What is something I like that the rest of the world (some of it) likes too? And how can I make something useful for/from that doesn't exist (to my knowledge) quite yet? 
Ding, ding ding. Why not a website that acts like the perfect, unbiased middle-person, medium, matchmaker, whatever you prefer to call it, between two types of people. 
More specifically, for people who like to travel, like myself. For the maniacs that are insanely good at organizing and coming up with itineraries, or planning the whole trip for a group of friends. 
You know the kind, the one friend that was stuck planning the whole graduation weekend trip for everyone to enjoy, and a lot of them forgot to thank that person, except for that one kid that always feels bad for everything, but really, in reality that person didn't mind taking care of all the technical stuff (related to the trip) because they knew they wouldn't have it any other way... 
Yeah, those, the Planners. 
And, the ones that just like to enjoy the ride, depend on the responsible one of the pack to take care of business and sit back. Not that there's anything wrong with that, because honestly (from experience), I would much rather have that type of person sitting back than messing with the plans and trying to schedule impossible itineraries, or unrealistic budgets. Please, sit back, I'll do this for free. Yeah, those are the Goers. 

Well, I wanted to make a website for those two types of travellers, so that Goers can find Planners to do the work (maybe pay them, AdSense, Patreon, or something) and Planners can find Goers to have a job. Like online freelance writing, you're good at it, you might as well make some extra income from it, in your free time, from home. 
I made it work. This project. 
It took way too many hours, and I mean, dedicating a full 8 hours a day, more than 4 days. 
Because I wanted my structure so separate, the goers with the goers and the planners with the planners, I started with two wholly separate user types. That lead to two separate controllers sessions and a bunch of complications and WET code everywhere. 
Okay, 50 pages of code later, so maybe not.
What then? STI, I tried implementing the single table inheritance (which I wasn't really familiar with to begin with), but I read as much about it as I could. 
Still, I was getting errors and bugs and WETness all over my code. 
Okay, so I scheduled a 1:1, I desperately wanted the opinions and suggestions of an expert, or somebody that knows more than me. 
I wasn't messing around, I wanted to get this done. I hate wasting my time sitting around waiting for the appointment date to come around. So I ended up scheduling 2 meetings in a row. Since each is only 30 minutes, and from experience I know we never achieve what I wanted to achieve in those 30 minutes. (I mean, come on, the first 5 minutes go waiting for the meeting to open up properly and 3 to 5 more minutes go by trying to brief the instructor as fast as I can in what I'm trying to make and what I have issues with. Then 10 more trying to make yourself understood on what you want or need... the 30 minutes go by and you're lucky if you got 2 out of 6 questions in.) 
Okay, so I was up for the hour appointment, but I didn't really get what I needed. Which was an honest opinion in whether or not I should be using STI, should I use something else, what do you think? 
I got "umms" and "errs".
Maybe it's just not possible to make your plans understood in such a short time. There's no one to blame, we're students but not elementary students. 
But either way, I came out still not sure if STI was the right way to go or if there was something better. 
I had foreseen this happening (the meeting not covering what I need it to cover) so I already had scheduled yet another session for the next day. 
It ended up being a different instructor. He almost cancelled on me. I got a last-minute email explaining they couldn't make it and I could reschedule for tomorrow or for that same day, but later in the evening. 
I'm not going to pretend, this is my blog after all, that was pretty frustrating because I was counting down the hours for the meeting, to finally have some assistance and not feel like I was stuck.
Obviously, I replied to the email asking to please do it that same night. 
The good thing that came out of this was that, maybe because it was later and the instructor didn't have other meetings, they were able to stay 1 hour. Very generous, but also, just fair considering we, as students, can't cancel last minute, but somehow the other party can. 
Alright, by that point, because I had the whole day to wait for the meeting and the answers, I had re-done my project in a separate repository entirely. This time to restructure everything with user roles, not STI and not separate types of user, just one user class but different roles. 
I took the whole day to actually go through the learn.co lessons on Rails, one by one. Looking at all the labs I had done for each lesson, seeing how that would apply in my project. Again, one by one. Going as carefully as I could. 
Well, I made my own life easier with the new structure, I just wish I had heard it as, at least, a suggestion in the previous sessions, so I could have started refactoring earlier. To use roles.
I was able to get to other smaller questions I had for the project. What I did to get the most out of a session was just ask about 1 example from the 1 type of issue or question I had and see how it can be done then mentally note it, leave it and move on to next 1 small example for 1 question. 
So you don't actually fix things while in sessions, you're not really testing properly either, just try to get as many answers or examples as you can, then you'll apply them later.
I always learn faster by observing, seeing other examples and then implementing that in my own case. 
Thank god, I felt like I was a car running low on oil, or just no oil and that session got me the oil I needed to get rolling. 
Things started moving again and the next day, today, I was sure I was going to finish the project fully. I woke up at 8am and started. 8 hours in a row, 2 breaks of about 20 minutes. And I was done. 
Things are working well in my website. 
I applied my own authorizations and permissions. I loved working with the CSS, I loved working on my theme. I had fun with class methods. And I'm proud of my work.
Proud enough that I would show it to my friends (and I'm typically too shy to share these things, lol)
I learned a lot, so much debugging, because I had so much newbie plumbing issues. 
But it is done, and I think the biggest lesson here is to start big, as big as you can, then make it small and smaller, then let it naturally become big again. 
The ideas, the code, the structure, the ideas again. 

Here is the link to my [Rails Project](https://github.com/msickler/plan-me) 


