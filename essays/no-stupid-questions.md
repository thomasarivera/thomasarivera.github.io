---
layout: essay
type: essay
title: 'No "Stupid" Questions?'
# All dates must be YYYY-MM-DD format!
date: 2023-09-06
published: true
labels:
- Personal-Development
- StackOverflow
---

## "There Are No Stupid Questions"
All my life in school, my teachers have said the phrase, "There are no stupid questions." And they are right! There are no stupid questions, but do not expect your question to get a good answer. Asking questions is a crucial task, allowing us humans to communicate clearly and effectively. But the questions we ask should be meaningful.

In the online essay "How To Ask Questions The Smart Way" by Eric Raymond, he puts into perspective what it means to ask a question from a hacker's point of view. Eric points out that the kind of answers you get to your technical questions depends on the way you ask the questions. Hackers have become notorious for answering questions with a snarky or hostile tone, but that may be because you asked a "stupid" question.


## "Smart" and "Not so Smart" Questions
Asking the right questions makes all the difference. Even small questions like "Should I brush my teeth tonight?" the answer is no because I'm lazy, which can have a significant impact. In this example, my question may be considered "stupid" if I'm trying to take care of my teeth. This is because it's asking the wrong question, leading to a bad answer. The smart version of this question is, "Why should I brush my teeth tonight?" The answer is that it prevents cavities, and so yes, I should brush my teeth. 

When it comes to technical questions, like in Software Engineering, asking "smart questions is important. But before you even ask a question, it is also important to do your part. Now, what am I talking about? Shouldn't I be able to just ask the question and have someone answer it for me? No, asking a "smart" question requires you to do your own research first. This includes reading a manual, searching an online forum to see if another person already asked this question, experimenting, or asking a skilled friend. Only after doing everything and still coming up empty-handed should you ask for help.

The next step is creating the question. When writing a "smart" question, Eric Raymond recommends using meaningful, specific subject headers and creating a precise question that is easy to read and reply to. He also mentions how the tone of your question matters: write in a confident and intelligent tone. If I were to look at a question where it was clear the person did not attempt to do anything, I would ignore it. Following these guidelines does a couple of things: it shows to other people that you have put in the effort to solve your question, and your "smart" question is more likely to get an answer. After making a question, it is time to release it to the world. Deciding where to ask is also essential to getting a good solution. When looking, choose based on your skill level, the problem's difficulty, and the question's topic.

## Examples:
On StackOverflow, a question and answer site for programmers, I found a couple of questions that display a “stupid” and a “smart” question. 

"Stupid" Question:
```
Q: Cloudflare, block user IP's not from Cloudflare, but still allow server IP scripts to run locally [closed]

We recently had an DDOS and various other attacks on our website which has a lot of frontend/backend programming. So we now have the Cloudflare Business account using Geo-Blocking, WAF, DDOS protection, rate-limiting, etc.
I know that Cloudflare recommends only allowing their incoming IP's, and to block all other incoming IP's such as the direct server IP so people cannot access or spoof the IP with their host file.
Right now we are running Windows Server 2012 R2 Datacenter.
The problem I have is that I have a lot (around 40 or 50) scripts on the server that are executed using the server IP/Domain (Domain modified on web server using host file so we don't go through Cloudflare) on the server itself, not from the outside world.
They are time consuming scripts that run reports and other things. We have the Cloudflare Business account, but it has a timeout of 100 seconds. These scripts run longer than that otherwise it would not be a problem.

I've done some basic things like not allowing internet users to access the site by the direct IP, but it's still possible to spoof it using the host file if they want on their computers or other compromised computers. This will bypass Cloudflare since they are bypassing the proxy DNS on Cloudflare.
I was wondering if anyone has any ideas on how to block the server IP for internet users, but still allow it to be used internally on the server.
Hopefully that makes sense.
Thank you for your help!
```

This is an example of a “stupid” question. Although the subject title and the explanation of the problem are sufficient, this is not a good question because StackOverflow is not  the correct place for this topic. This is further exemplified by the fact that StackOverflow closed the question due to it not being about programming or software development. A more suitable forum to post this question would have been Server Fault.

“Smart” Question:
```
Q: fatal error: Python.h: No such file or directory

I am trying to build a shared library using a C extension file but first I have to generate the output file using the command below:
gcc -Wall utilsmodule.c -o Utilc
After executing the command, I get this error message:
> utilsmodule.c:1:20: fatal error: Python.h: No such file or directory compilation terminated.
I have tried all the suggested solutions over the internet but the problem still exists. I have no problem with Python.h. I managed to locate the file on my machine.
```

The user asking the question does a good job in his format. First off, the subject title is straightforward and shows what the issue is. It is clear that the user is getting an error from Python and that a directory can not be found. In the question itself, the user informs readers on what they are attempting to do and what steps they have taken to get to. Furthermore, as a show of confidence, the user then explains how he already attempted to find a solution and even searched online. Questions like this are a good example of a “smart” question and the answers that follow show that. 

## Conclusion:
Yes, it is true; there are no stupid questions. However, do not expect to get the answers you want from those questions. Asking the right and “smart” questions is crucial in life and can be a lifesaver when it comes to difficult tasks. When you are asking a question, it takes another person's time and energy to help you, so make sure when you ask a question, make it a “smart” one.
