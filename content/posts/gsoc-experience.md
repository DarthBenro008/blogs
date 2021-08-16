---
title: "Google Summer of Code 2021 with Cloud Native Compute Foundation — My experience with LitmusChaos"
date:  2021-08-15T20:41:26+05:30
tags: ["Google Summer of Code","Open Source","journey"]
categories: ["Open Source Program Experiences"]
author: "Hemanth Krishna"
TocOpen: false
draft: false
hidemeta: false
description: "My Experience in Google Summer of Code 2021"
canonicalURL: "https://canonical.url/to/page"
hideSummary: false
cover:
    image: "/images/gsoc/gsoc_exp_banner.png"
    alt: "GSoC Experience Banner" 
    hidden: false
---

Hey Folks! I am Hemanth Krishna 👋, a junior undergrad student pursuing Computer Science at the time of writing this article. I recently participated in Google Summer of Code 2021 where I worked on a project named [LitmusChaos](https://github.com/litmuschaos/litmus/), which is an Open Source Chaos Engineering tool. Lots of new terms to take in 😅? Let’s break it down one by one!

## What is Google Summer of Code?

Two words, **_Open-Source Software_** and **_Students_**. Google Summer of Code is a global programme by Google (duh) to bring these two terms together. It provides a great platform and exposure to encourage students to participate in Open Source Software development and inculcate the Open Source culture amongst young budding minds during their summer break.

{{< figure src="/images/gsoc/gsoc_exp_header.jpeg" caption="Google Summer of Code Logo" >}}

To give a gist, major open source projects and organisations (such as CNCF) participate in this programme and put up project ideas. The projects and mentors are selected and put up on the [GSoC (Google Summer of Code) website](https://summerofcode.withgoogle.com/).

Students have almost a month-long time to explore these projects and submit a proposal of a project idea, it may be a completely new idea or something that the organisation has put up (you will find mine below)

The Mentors of the organisation then review these proposals and select a mentee to mentor them and overlook the completion of the proposed idea in a specific duration, it was 10 week for the 2021 programme. That is it! It’s a straight forward simple process. You can find more about the timeline and previous year projects over [here](https://summerofcode.withgoogle.com/).

Now we know what GSoC is, I had submitted my project idea proposal to a project named LitmusChaos which is a sandbox project of CNCF. Does that sound confusing🤔? Don’t worry, let’s break it down one by one!

## What is Cloud Native Compute Foundation (CNCF) ?

[CNCF](https://cncf.io/) (Cloud Native Computing Foundation) is an organisation that houses the fastest-growing open-source projects that shape the future of cloud computing and the world of DevOps. Some famous projects used worldwide housed by CNCF are [Kubernetes](https://kubernetes.io/), [Prometheus](https://prometheus.io/), [Envoy](https://www.envoyproxy.io/), and, [much more](https://www.cncf.io/projects/)!

{{< figure src="/images/gsoc/gsoc_exp_cncf_logo.jpg" caption="Cloud Native Computing Foundation Logo" >}}

You probably guessed it right! LitmusChaos is also a project (sandbox) housed by CNCF similar to Kubernetes or Prometheus. Hence, my project idea proposal was on LitmusChaos, whose parent organisation is CNCF.

{{< figure src="/images/gsoc/gsoc_exp_umbrella.jpeg" caption="Umbrealla Organisation" >}}

## What is LitmusChaos?

{{< figure src="/images/gsoc/gsoc_exp_litmus_logo.jpg" caption="Litmus logo" >}}

Litmus is a Chaos Engineering Platform, which takes a cloud-native approach to create, manage and monitor chaos. In layman terms, LitmusChaos is a tool that helps you stress-test your infrastructure and prevent potential outages. It is a tool SRE (Site Reliability Engineers) and Developer have fun with as they witness the strengths, efficiency and resiliency of their codebase and infrastructure.

One can run various experiments hosted on [hub.litmuschaos.io](https://hub.litmuschaos.io/) (Chaos Experiments are more fun than your high school lab experiments 😛)

You can learn more about LitmusChaos by visiting the [project on GitHub](https://github.com/litmuschaos/litmus/) or by checking out the [Litmus YouTube Channel](https://www.youtube.com/channel/UCa57PMqmz_j0wnteRa9nCaw)

If you are interested, come to and say “Hi” by joining the [slack community](https://slack.litmuschaos.io/) and attending the [weekly sync up meets](https://github.com/litmuschaos/litmus/#community-meetings)! 😃

## My Acceptance into the program

{{< figure src="/images/gsoc/gsoc_exp_gsoc_timeline.jpeg" caption="Simple timeline of the program" >}}

As a tech enthusiast along with my interest in open-source tools, I keep exploring various frameworks and tools that enables me to develop applications that aim to solve some real-life problems. I encountered litmus, while I was exploring the concept around Chaos engineering.

As the first steps, I followed [this page](https://summerofcode.withgoogle.com/organizations/?sp-page=2) to check if any tools align with my skills and interests to apply to the Google Summer of Code programme, I started this process around 3–4 weeks before the application deadline. I saw litmus was listed with a project, reading the project description I had few ideas of my own, and started looking into the codebase of litmus.

As any new open-source developer to a new tool, I tested out litmus myself as a consumer of the tool, then later went through [good-first-issues](https://github.com/litmuschaos/litmus/labels/good%20first%20issue) so that I can familiarise myself with the codebase. I eventually ended up contributing and got around 3–4 PRs merged and involved myself within the community.

I carefully prepared my proposal covering the requirements along with my ideas that could benefit the project and had submitted it on the Google Summer of Code dashboard. You can find my submitted proposal below

[Click here to view my GSoC Proposal](https://drive.google.com/file/d/1Mb-DsRLv8fCxhsnqMgQYXR7i7DKhUk_C/view?usp=sharing)

Eventually, the mentors of the litmus project had contacted me for a quick call regarding my application where I expressed my interest, my experience with the required skillset and why I think I would be a good fit as a mentee to execute and implement the project.

After the meet, I was given a small task to implement a basic Oauth authentication system in GoLang and was given about 24–36 hours for the same. I completed the task, hosted it on Azure and had sent the link to the mentors and had minimal hopes regarding my application.

It was around 11:30 PM, I was in the middle of completing my university assignment which was to be submitted by 11:59 PM (your typical engineering student 😓) and suddenly I receive this email into my inbox!

{{< figure src="/images/gsoc/gsoc_exp_acceptance_email.png" title="My acceptance email in Google Summer of Code 2021" >}}

I still remember being really happy and enthusiastic about learning something new for the summer and being mentored by some cool engineers.

After few days of acceptance, my name and project were updated on the GSoC 2021 Projects page

[Click here to view my GSoC Projects Page](https://summerofcode.withgoogle.com/projects/#5058541729087488)

## What did I do for 10 weeks?

My initial primary task was to refactor the litmus-portal authentication server and integrate an flexible and scalable OAuth2 based authentication system to the server, but my task grew into something later on different where I learnt a lot of new things.

Eventually, with further discussion with my mentors and community, I re-wrote the entire authentication server instead of refactoring for better performance, the average response time for an request was initially whooping 9 seconds! and this was bought down to sub-second response times. You can find more details about this on the GitHub PR

[My Pull Request for Phase 1](https://github.com/litmuschaos/litmus/pull/2867)

{{< figure src="/images/gsoc/gsoc_exp_pr_merge.png" title="My PR for first phase of GSoC 2021" >}}

This task is what served as my first evaluation checkpoint, and I passed this evaluation with generous and motivating comment from my mentor!

My secondary task, was integrating an flexible OAuth2, initially, I followed basic OAuth2 system of GoLang and created a Proof-of-concept

[Click here to view Proof-of-concept](https://github.com/DarthBenro008/go-oauth)

The flow architecture that I proposed is shown below

{{< figure src="/images/gsoc/gsoc_exp_approach1.jpeg" caption="Proposed Approach for Auth Server" >}}

Later on, we came across an Cloud Native OIDC Provider named [Dex](https://github.com/dexidp/dex). This allowed us to add various authentication features, and I also customised the server to match litmus-portal theme.

Hence, the new architecture proposed turned out to be like the following image:

{{< figure src="/images/gsoc/gsoc_exp_approach2.jpeg" caption="Authentication Server with Dex Integrated" >}}

Eventually, I presented my integration to the litmus team over a call, and got some takeaways and green flag for the integration 😃

{{< figure src="/images/gsoc/gsoc_exp_dex_slide.png" caption="My presentation of Dex Integration with litmus team" >}}

I learnt a lot over the period of these 10 weeks regarding GoLang APIs, OIDC Providers, various system architecture patterns and how to write better code! The fact that the code I write is in use by various developers and companies to run and test their system amuses me 😯, You will probably find me contributing to litmus after my GSoC Period too! 😄

## Should I apply for GSoC? If yes, then how?

{{< figure src="/images/gsoc/gsoc_exp_oss_meme.jpg#center" >}}

If you are a student who is enthusiastic about software development, technology in general, would love to explore and be part of open source. You should definitely apply for Google Summer of Code! It is really cool to get mentored by project maintainers who have a great experience in various fields.

Here are few perks of Google Summer of Code:

* **Learning:** One get’s to learn a lot while contributing, with every PR of mine getting merged, I learnt a lot of new different things becoming better at what I do step-by-step.
* **Networking:** This is one of the under-rated perks of any Open Source Programmes. Networking and interacting with the community improves one’s soft skills and promotes growth when you hear different views, opinions, and approach on solving a problem.
* **Stipend:** Who does not love a stipend while learning 😉, GSoC pays a great stipend, but I would really advise participating in this programme not for the stipend but for the above points.

Now, coming to the question of “how?”, the approach differs from person to person, but some traits common amongst all is _the willingness to learn, network and, giving back to the community_. You ideally need to not know every nitty-gritty detail of a programming language or a framework, or the whole codebase of the project for your proposal to get accepted. Here are few pointers that might help you with getting accepted into GSoC:

* **Understand your interests:** Finding the right project is very important, jot down your experience in various languages, frameworks and interests and start looking into the projects that align with the same. If you think a project is perfect for you, always first try out the project as a consumer and see what the tool/software exactly does, this would give you a great boost in understanding the codebase and would help innovate in scopes of improving the project.
* **Interact with the community:** Make sure to sign yourself up onto the community slack/discord/Jitter and try to attend weekly community meetings if there are any. This would give you a great insight into what all developments are occurring and you would be able to network with people.
* **Innovate and discuss your proposal:** Make a decent proposal that also consists of a timeline, divides your implementation down to different phases that you can follow in the duration of the programme.
* **Make the most of your time:** Getting selected or not, you learn a lot of things that facilitate personal as well as professional growth when you participate in Open source development, so ensure you are enjoying what you are doing irrespective of the selection and make the most of your time!

## Sayonara! 👋

Overall my journey has been a great experience and I would like to thank my mentors [Raj Babu Das](https://twitter.com/rajdas98), [Soumya Ghosh Dastidar](https://twitter.com/gdsoumya), and, [Ajesh Baby](https://twitter.com/ajeshbaby) for guiding me throughout, I would like to thank the community that’s always active and helps for the betterment of such tools, and, I would like to thank you, for reading till here 😃.

This summarized my journey as a Google Summer of Code Mentee and I hope this blog was informative. If you have any questions regarding my project, Cloud Computing, or would like to discuss tech in general, you can find me on:

* _GitHub:_ [https://github.com/DarthBenro008](https://github.com/DarthBenro008)
* _Twitter:_ [https://twitter.com/hemanth\_kri](https://twitter.com/hemanth_kri)
* _LinkedIn:_ [https://www.linkedin.com/in/darthbenro008/](https://www.linkedin.com/in/darthbenro008/)
