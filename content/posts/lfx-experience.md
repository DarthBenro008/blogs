---
title: "Linux Foundation’s CNCF Mentee — My Experience with Keptn"
date:  2021-07-16T12:04:00+05:30
tags: ["CNCF","DevOps","journey"]
categories: ["Open Source Program Experiences"]
author: "Hemanth Krishna"
TocOpen: false
draft: true
hidemeta: false
description: "My experience being an LFX Mentee"
canonicalURL: "https://canonical.url/to/page"
hideSummary: false
cover:
    image: "images/lfx/lfx_exp_banner.png"
    alt: "LFX Experience Banner" 
    hidden: false
---


Hey Folks! I am Hemanth Krishna 👋, a sophomore undergrad student pursuing Computer Science at the time of writing this article. I recently graduated from the Linux Foundation’s CNCF Mentorship Programme where I worked on a project and contributed to [Keptn](https://keptn.sh), an awesome Open Source tool that’s a control plane for DevOps automation of cloud-native applications. That’s a lot of information in few sentences 😅, let’s break it down one by one!

## LFX Mentorship? What’s that

[The LFX Mentorship Programme](https://lfx.linuxfoundation.org/tools/mentorship/)  is an Open Source Programme that occurs every quarter of the year organised by The Linux Foundation. The whole goal of this programme is to promote the Open Source culture around the globe and show people the beauty behind the curtains of amazing tools that are powered by the Open Source Community.

{{< figure src="/images/lfx/lfx_exp_lfx_logo.jpg" caption="The Linux Foundation Logo" >}}

In this programme, you get the opportunity to work on Open Source Tools and get personal mentorship from the project maintainers for 3 months! Organisations such as [CNCF](https://www.cncf.io/), [Hyperledger](https://www.hyperledger.org/), [Open Mainframe](https://www.openmainframeproject.org/), etc participate which just makes it more exciting than ever to work on tools used worldwide.

## Okay, I get the LFX part, what’s CNCF?

[CNCF](https://cncf.io) (Cloud Native Computing Foundation) is an organisation that houses the fastest-growing open-source projects that shape the future of cloud computing and the world of DevOps. Some famous projects used worldwide housed by CNCF are [Kubernetes](https://kubernetes.io/), [Prometheus](https://prometheus.io/), [Envoy](https://www.envoyproxy.io/), and, [much more](https://www.cncf.io/projects/)!

{{< figure src="/images/lfx/lfx_exp_cncf_logo.jpg" caption="Cloud Native Computing Foundation Logo" >}}

But wait, how is _CNCF related to LFX_? CNCF was founded by The Linux Foundation! The LFX Mentorship for CNCF projects was previously known as Community Bridge.

## My acceptance into the programme

As a tech enthusiast, I was exploring the field of Cloud Computing and DevOps and had used tools like Kubernetes, Prometheus, Keptn previously in my projects, and the idea of contributing to such tools was pretty exciting to me, but being a sophomore student and a DevOps newbie, I wasn’t having high hopes of getting selected into this programme, but I decided to give my best and try to make the most from the learning experience!

As the first steps, I followed [this repository](https://github.com/cncf/mentoring), where all the projects were listed. I browsed through the issues and projects, it was initially very intimidating to understand huge codebases and to familiarise myself with the project’s design and working principles. Eventually, I came across [this](https://github.com/cncf/mentoring/tree/master/lfx-mentorship/2021/01-Spring#generate-service-skeleton-via-cli) issue. It seemed a perfect fit for me as I was developing some CLI’s in GoLang and the project description did not sound very intimidating to me.

{{< figure src="/images/lfx/lfx_exp_project_listing.png" caption="Keptn Project participating in LFX Mentorship Programme Q1'21" >}}

I started contributing to Keptn by starting with [good-first-issues](https://github.com/keptn/keptn/labels/good%20first%20issue) in order to explore and understand the codebase and the working principles underneath the tool.

It felt great when my first PR was was merged! This fuelled my excitement and motivated me to work on more issues and understand the tool better, eventually, I got _5 PR’s merged_ into Keptn before the acceptance into the programme. Keptn had their weekly community developer meetings and I was invited to present my work in one of the features I added to the Keptn CLI. It was an exciting and fun experience to present my work live. I eventually joined Keptn’s slack workspace where I interacted with the community and the project maintainers.

{{< figure src="/images/lfx/lfx_exp_first_pr.png" caption="My first Pull Request at Keptn Project" >}}

Once the application process began, I drafted a nice proposal and cover letter that included my motivation towards working on the project and why I think I deserve to be a Mentee. I simply submitted my application keeping my hopes minimum.

{{< figure src="/images/lfx/lfx_exp_acceptance.png" caption="The email informing my acceptance into LFX Mentorship Programme" >}}

After a few days, I was sipping on some tea in the evening and my phone buzzed. I was immensely filled with joy as I received my acceptance email into the programme. It felt great and I was excited that I will be learning and be mentored by Project Admins and Contributors of a CNCF Project.

## What is Keptn?

[Keptn](https://keptn.sh/) (pronounced similar to Captain, who controls your docker ships) is a [CNCF Sandbox project](https://www.cncf.io/sandbox-projects/), but what does it do? It is a control plane for DevOps automation of cloud-native applications. Sounds complex? In a nutshell, Keptn automates and provides an event-based declarative approach to automate your SLO-driven multi-stage delivery and operations, DevOps automation in its true essence! I liked the approach and problem Keptn aims to solve.

{{< figure src="/images/lfx/lfx_exp_keptn_logo.jpg" caption="Keptn Logo" >}}

At the time of writing this article Keptn has [filed a PR](https://github.com/cncf/toc/pull/670) to become a CNCF Incubation project. You can find more about Keptn [here](https://keptn.sh/why-keptn/), and check out the [official GitHub repository](https://github.com/keptn/keptn).

Additionally, if interested, feel free to dip into the [Weekly Community Developer and Monthly User Group meetings](https://keptn.sh/community/meetings/) to gain more insights!

## What did I do for 3 months?

My primary task was to add functionality to the Keptn CLI that allowed users to generate a [_keptn-service_](https://medium.com/keptn.sh/docs/0.8.x/manage/service/) and automatically set it up for them so that they can dive right into developing the core logic of their service they wish to onboard onto Keptn, all from a single command.

{{< figure src="/images/lfx/lfx_exp_work_desc.png" caption="A simple TL;DR of my project" >}}

I had an amazing experience working on this project and being mentored by Jürgen Etzlstorfer, Johannes Bräuer, and, Florian Bacher. We had weekly sync-up calls where we discussed our projects and resolved any road-blockers I faced during the implementation of the same. I was able to complete the first half of the task within a month, which I presented to the Keptn community in one of the community developer meetings!

{{< tweet 1377639333956575234 >}}

After few weeks of work, I was able to complete my project and soon one might be [able to generate](https://github.com/keptn/keptn/pull/3584) a _keptn-service_ right from their CLI and start developing the same. I thought of adding another feature where the user can locally test their service directly by talking to the keptn cluster. This involved exposing the Keptn nats-cluster via a Load Balancer. Hence I opened another PR regarding the same and the feasibility of this feature is still in discussion and also has been discussed in my final presentation of the work I have done during the past 3 months.

{{< youtube id="J72SZD3p3Lw?start=1371" >}}

My presentation for the project at Keptn Community Meeting

And after my final presentation, few days later I received my graduation email 😃

{{< figure src="/images/lfx/lfx_exp_graduation_email.png#center" caption="The email informing my successful graduation from the LFX CNCF Mentorship Programme" >}}

## Should you apply for LFX Mentorship Programme too?

Are you interested in Open Source, Cloud Computing, and, the world of DevOps? Then, a Simple answer — Yes! Definitely try applying for the programme.

{{< figure src="/images/lfx/lfx_exp_oss_meme.jpeg#center" caption="The email informing my successful graduation from the LFX CNCF Mentorship Programme" >}}

I am glad that I got this opportunity and have learnt a lot during the span of 3 months. I think it’s a really cool opportunity that you personally get mentored by amazing engineers who build tools to solve problems. Some perks of participating in the LFX Mentorship Programme include:

* **Learning**: Being a newbie to the world of DevOps, I certainly have gained a lot of knowledge by exploring and working alongside the people
* **Networking**: This is one of the under-rated perks of any Open Source Programmes. Networking and interacting with the community improves one’s soft skills and promotes growth when you hear different views, opinions, and approach on solving a problem.
* **Stipend**: Who does not love a stipend while learning 😉, the LFX Mentorship Programme pays a great stipend, but I would really advise participating in this programme not for the stipend but for the above points.

## Is it difficult to get accepted into this programme?

Definitely **not!**

I started checking out the participating projects just a few weeks before the applications started and I did not have any sort of professional-level experience in GoLang either, but I was able to make it through.

Personally, I think the only requirements for one to get accepted into the LFX CNCF Programme are _Willingness to Learn, Patience, Open to network, and, willing to give back to the community_. That summarises the important skills for one to contribute in Open Source.

## Sayonara

Overall my journey has been a great experience and I would like to thank my mentors [Jürgen Etzlstorfer](https://github.com/jetzlstorfer), [Johannes Bräuer](https://github.com/johannes-b), [Florian Bache](https://github.com/bacherfl)r for guiding me throughout, I would like to thank the community that’s always active and helps for the betterment of such tools, and, I would like to thank you, for reading till here 😃.

This summarized my journey as a Linux Foundation’s CNCF Mentee and I hope this blog was informative. If you have any questions regarding my project, Cloud Computing in general, you can find me on:

* **_GitHub:_** [https://github.com/DarthBenro008](https://github.com/DarthBenro008)
* **_Twitter:_** [https://twitter.com/hemanth\_kri](https://twitter.com/hemanth_kri)
* **_LinkedIn:_** [https://www.linkedin.com/in/darthbenro008/](https://www.linkedin.com/in/darthbenro008/)

May the source be with you 😄
