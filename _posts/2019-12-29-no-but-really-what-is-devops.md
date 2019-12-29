---
title: "No, but really—what is DevOps?"
---

In the Art World where I hail from, especially in the drastically underfunded Art World, collaboration is a necessary practice. In smaller art spaces such as non-profit galleries and residency programs, would-be teams often blend together into one mass, where the boundaries of a person's roles or skills are blurred together. Don't know how to spackle a wall? Time to learn, 'cause we need extra hands. Never mounted a photoraph on acid-free paper? Get that measuring tape and razor out. Oh, and don't forget, we're _all_ going to be planning events, managing artists, and taking care of the day-to-day paperwork together. Even the more office-based positions I've held in the Art World have been like this, to a large extent.

This spirit of hypercollaboration is usually admirable, intrinsically comes packed with a series of learning experiences, and absolutely stokes a sense of community within the organization.

In the more traditional Tech World, in my experience, the starting point is the other end of the (what I suppose we're calling) spectrum. Roles are defined in high contrast: the technological limitations to working across team boundaries are matched only by their cultural counterparts.

Coming into this profession more formally during the rise of the DevOps era has therefore been a very interesting experience. It's clear to me that, over at least the past 15 years if not longer, developers and operations (system administrators) people have enjoyed a kind of self-satisfying identity knowing that they're one, and not the other. On the better side, this has bred [enjoyable jokes](https://www.youtube.com/watch?v=TnCY6Apxibk). On the worse side, it shatters the kind of collaborative flow that I had become so accustomed to in the Art World for so long.

This isn't to say that that Art World collaboration was always the best, either. Not knowing where your responsibilities end and your commitments to a community begin can make it tough to know where to set the boundary. This can lead to an imbalance of work; where there is no formal structure, we must rely on our social structures to make up the difference in what's acceptable in a micro-society like a job or other project involving others. Without explicit attentiveness to the way those social structures rush in, without giving form to what pushes down the dam,a practice that takes a lot of time and dedication, people end up drowning in their own workload. So, entering into a Tech World space where those roles were so definitively etched out provided some comfort from that as a possibility.

What excites me most about the DevOps ideology is that it provides a bridge between the purely communal and the purely precise.

But what has been strikingly apparent to me lately is how misunderstood DevOps, as a term, concept, or even as a role, seems to be understood.This is usually true of any new idea as it is encoded into practice.

I've encountered a few places now where "DevOps" just seems to be a buzzwordy replacement for a developer. Maybe sometimes a developer who knows something about Docker, or networking, or Linux.

In other places, the concept is driven by the idea of automating infrastructure, which is closer; but then, the infrastructure is only accounted for on the Ops side (which is really, technically, more like SysOps or Site Reliaibility Engineering). Don't get me wrong: being that my origins are strongly system administrative, I love SysOps/SRE work. But, after having been exposed enough to the differences between that and DevOps, they're truly not the same thing.

So, just what is DevOps, anyway? 

DevOps is the definition of a role that goes between roles. Specifically, it is the work of _automating the development process._ This means that DevOps engineers must work closely with developers in order to automate their development environments, ensuring consistency across stages. DevOps as a method is intended to make the entire development process faster, easier, more consistent, and, via those principles, also more secure. In engineering, I think one of the greatest things to have is _mobility_. In this way, the DevOps mascot maybe ought to be a hummingbird: no directionality is unavailable to them. 

It means not having to rely on local environments, all of which are as different as the human beings working on them, because [we have the technology](https://youtu.be/HoLs0V8T5AA?t=42) to work in abstractions of abstractions, ones where we have all the control. And if that fails, it means the ability to roll back easily after a faulty deploy. It can mean _portability_, the ability to hand an identical Vagrantfile to multiple developers and be confident that there will be far fewer inscrutable "works on my machine" issues.

It is perhaps easier to understand culturally, rather than technically, where the offered definitions of DevOps are often far too tool-dependent: rather than isolating themselves away and focusing purely on infrastructure design and maintenance, DevOps pulls the system administrator into, if not literal code, the _idea_ of code: that is literally what is meant by "Infrastructure as Code".

I think the single most important distinction, though, and the entire driving force behind this blog post here, is the distinction between an SRE and a DevOps Engineer.

SREs are the shepards of deployments onto and automation of _infrastructure_ they know backwards and forwards. DevOps is the sheparding of automated _environments_ for the ease of development.

Unlike _developers_ who are writing code all the time and absolutely need to know their language(s), DevOps Engineers don't _need_ to be experts in any programming languages (except in specific circumstances), but they should have static familarity with more than one. They _need_ to be comfortable with Linux, with the idea of automation, and with the concepts of abstraction. They _need_ to be comfortable with the concept of code, or at least the idea of declarative languages and stateful/lessness.

DevOps Engineers are also required, far more I think than traditional system administrators, to be collaborative with the development team. (It'd be mighty hard to write infrastructure automation for the development team when you don't even know what the development team is doing.)

Is it even useful to argue the semantic finer points? In some other contexts, I might say no. But in a work context (and DevOps is a job-based term), it affects the exact thing I mentioned earlier: knowing your role. I guess that's what got me to writing this today: a process of disambiguation is needed to understand what role I'm in at the moment, or what hat I've got on that day. I might be a SysOps engineer one day, a DevOps engineer the next. The fluidity of these identities is okay so long as the distinction between roles is clear, paving the way for clarity of communication (big for me), as well as self-advocacy on the job.

Moreover, this is an exciting field, and an exciting time to be in this field, but it can get confusing fast without enough exposure to what other people think the title is all about.

Happy automating!
