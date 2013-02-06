---
layout: post
title: "Unit testing? Some advices from a Googler"
description: ""
category: 
tags: [unit-testing, testing, google, ios]
---
{% include JB/setup %}

One of the best things of changing your job is meeting new people and learning from them. And if one of your team mates was a Googler almost for 6 years, then it's really exciting the amount of things you can learn in the day-to-day.

This time, I asked my team mates about the approach to start to write automated tests in our iPhone app. Testing is quite fun when you start your project from scratch, it gives you a nice feeling of security, self-confidence, and power. But if your code base is around 15k lines of code, then it isn't so fun.
	
Next is his response. Most things are well known (sure, write a test to validate every bugfix, have a CI server and so on), but I think it's worth reading it once again.

> Here are my thoughts about unittesting.
> 
> **Writing some unittests is better than writing no unittests.** I don't know much (anything) about iOS mocking frameworks, but as long as they work and they seem to do what you need them to do, making a choice is better than spending too much time in analyzing what works and what does not work.
>
> At the same time, I feel that there is such a thing as writing too many unittests. This is something best learned with time and experience.
>
> **Having a Continuous Build somewhere will make everybody happier.** Whether you want to or not, there will be a time when you won't run the unittests before committing. I'll do that, you will do that, we generally suck at self discipline. Having a CB notify you that you broke the build saves that awkward moment a day later when another dev sees that I've checked in code that breaks the tests and they'll feel resentful towards my negligence. Besides, having this CB also helps to immediately notice what change broke what test, which becomes harder and harder when the number of code commits starts being large.
>
> **Writing clean good unittests is an art and it's just as hard as regular software engineering.** Good unittests are small, self contained, clear, the names of unittests need to be good so that when they break it's immediately obvious what broke. This takes time to learn from my experience.
>
> Good unittests are written to test only public interfaces of a class, never private methods. Testing private methods makes classes hard to refactor. Testing only public interfaces makes you think twice about designing the public interface of that class, which leads to better classes and better structure.
>
> A good rule of thumb for writing a test is to write one every time you fix a bug. This can be annoying because sometimes the fix is a one-line change and the test takes you an hour. But it's a good practice that pays off in the long run.
>
> Hope this helps,
> Vivi.

Thanks [Vivi](https://medium.com/octavians-thoughts), it's been an awesome time working together