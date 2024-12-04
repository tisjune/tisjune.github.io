---
layout: post
title:  "On research, advising, and routes through a landscape"
date:   2021-11-27
description: Thoughts on research and potential PhD students.
categories: blog
---

Hello from the future (December 2024). I occasionally re-read this blog post and am struck by what's changed and what's remained constant. Different now: a much more focused engagement with the political terms on which language use and social interaction happens, and is examined/theorized/commodified; much less patience with approaches (including mine) that fail to reckon with their politics. Constant: a continued fascination with "the tangly bits of social interaction;" a persistent attachment to metaphors that have to do with navigating physical space. If nothing else, I'm proud of how this piece articulated the contingent nature of one's research agenda, and of how my route (4) led me to more interesting places.

-----

So it occurs to me that since I’m going to be a professor (at the University of Michigan’s [School of Information](https://www.si.umich.edu/), starting September 2022), one big thing I should be thinking about is recruiting (and subsequently mentoring) students. To people who've emailed and asked, I've been equivocal on whether I'll actually take students in the coming year. In this post, I hope to provide a more helpful answer. 

I'd like to try and explain where I am right now, intellectually: what types of research questions resonate with me; what are problems and challenges I’m trying to work through. These things directly feed into how I expect to relate with advisees. They also inform what type of lab I want. In very concrete terms, I intend to ease into it: I don't expect to take more than a few (if any) students in my first year. But I do want to leave the door open for people whose interests mesh with mine, in ways that I'll use this post to explain.

For the 2022 cycle I realize this comes quite late (the UMSI deadline is Dec 1). Sorry about that--it honestly took me a while to gather my thoughts here. With that said, I'm intending for different groups of people to take away different things from the post:
* If you're applying for PhD programs for 2022, and weren't considering UMSI, please _do not_ take this writeup as a prompt to start your application. Trust the decisions that led to the shortlist of places where you're actually sending your materials. 
* If you were already planning to apply to UMSI, and some part of this post resonates with you, then I really encourage you to put my name down as a potential advisor. Being on similar wavelengths about what's interesting and--crucially--what's hard is a precious thing in academia. I think that's a strong signal that we'd work well together, and that I can help you become a fantastic researcher. 
* If you're planning to apply to PhD programs in a future cycle, then I hope that I've given you plenty of time to chew on what I've said, consider whether you'd like to work with me, and follow up with any questions. 
* More broadly, and in a somewhat different vein: if you're someone who's been trying to articulate your research tastes and map out the intellectual landscape you occupy, then I think we're in the same boat. I hope that some of the questions I motion towards here sound like some of the questions you've been thinking about too.

---

I'd like to start with some inferences you might've made from my existing publications.
I study conversations; my experience is in developing NLP methods to examine social uses of language. Throughout my PhD, 
I’ve collaborated with people from other disciplines who have particular access to, and perspectives on, settings with conversation data. 

If you work with me, here's what I think life will therefore look like in the foreseeable future. You are likely going to be delving into linguistic data of social interactions, using primarily computational methods, with an eye towards publication venues like ACL and CSCW. You should expect to be at the centre of interdisciplinary collaborations; my hope is that they'll teach you a lot about language use, methodology, and what constitutes meaningful research. This space, if we were to summarize it in a few words, might be something like "social applications of NLP" or "computational studies of social data." 

I think it would be helpful to locate myself more precisely in this very broad space. In my [dissertation](http://tisjune.github.io/papers/phd-thesis.pdf), I draw a map of different routes that people might choose to take through the landscape. The relevant bit is Section 1.2, but by no means do you need to read it, or the rest of the dissertation. I'll recap it here:

**A cartography of routes**

**Route 1**. Perhaps you’d like to find ways of improving social interactions. Here, you might draw on work in HCI in designing systems (e.g., for facilitating conversations, moderating discussions, ...). You might choose to rigorously inform these efforts by drawing on fields like causal inference. You may aim to contribute actual interventions, or--as I’ve put it--“actionable insights” that inform interventions. 

**Route 2**. Or perhaps you resonate more with the goals of artificial intelligence--in line with how much of NLP is framed. Maybe you’d like to develop systems that understand human language use or generate humanlike language. Maybe you're particularly fascinated by the prospect of applying these systems in realistic social situations. 

**Route 3**. Perhaps you’re fascinated by sociolinguistic ideas and want to study them at scale, on the web, with a quantitative clarity. Your work might then revolve around operationalising these ideas as computational methods. Here, I always think back to my advisor’s work on [linguistic change in beer communities](https://www.cs.cornell.edu/~cristian/Linguistic_change.html)--where a method to track linguistic change is proposed, and used to empirically illustrate a Picasso quote in a beer review forum (...just read the paper, it's a lot of fun). 

**Route 4**. Or, perhaps, you’d like to describe the various processes, complexities, and quirks that social interaction is comprised of. The quote that I think best captures this goal comes from Harvey Sacks, whose work was central to sociological studies of conversations: the focus is on “[constructing] the objects that get used to make up [interactions], and then [seeing] how it is these objects get used.” Maybe you think that empirical, large scale analysis--alongside the intricate, detail-oriented approach that conversation analysts like Sacks take--has useful things to say about social theory too.

You might try and situate other professors you're considering along one of these routes. That could useful for your decision-making. The exercise will probably also prove to you empirically that routes are very complicated in practice, that they are prone to change, and that individuals are messier than maps of them. The paths I've traced are steered by my own interests--but also, the interests of my collaborators, the venues I publish to, and my own academic background in computer science (if any of these things are ever cleanly separable from each other). Routes merge and fork in surprising ways. They are prone to hard-to-explain detours. 

Caveats in hand, I think I most often find myself along route 4. What animates me is explaining what makes conversations work or fall apart; in short, identifying the objects that make them up. This is the type of work I most enjoy reading and the type of idea I find myself most wanting to further develop; when faced with a fork in the road, this is the type of path my gut would most likely tell me to take. In darker times, I have seriously considered getting a different PhD that would've make me a more adept route 4 traveller. Don’t worry, I promise won’t. 

To put it another way: say you walked into a meeting with me right now and proposed some research ideas. I'd probably be excited by lots of them. But the ideas I would resonate with the most have to do with this particular type of descriptive task--of accounting for how conversations work. 

---

I’ll illustrate by example. During my PhD, I worked with a service called Crisis Text Line to analyse conversations between people in mental health crises and counsellors who volunteer with the service. My core focus was on the fascinating and challenging interactions that counsellors, and those they support, have to navigate through. A few papers came out of this collaboration. The one I'll focus on here has to do with a particular challenge that counsellors face, in [balancing conversational objectives](https://www.cs.cornell.edu/~cristian/Orientation.html). In the paper, we propose a method to quantify how counsellors manage this challenge at each turn of the conversation.

What I got out of the project, that’s closest to my heart, is this. Conversations are full of such challenges; devising ways to rigorously describe them helps us come to a richer understanding of how people use language to interact. In particular, I thought our theoretical framework (of describing this difficulty as a forwards-backwards tension along an axis) was very neat. I was so fascinated by our methodological idea (of accounting for an utterance’s conversational context as a way of characterising it) that Chapters 2-5 of my dissertation are devoted to unspooling and extending it, and probing its limits. Having had my fill of seeing where this computational description led, I then spent Chapters 6 and 7 taking stock of the conversational complexities it could not account for, the fissures between representation and reality. Again, you don't need to read the dissertation. The point I want to make with this snapshot of it is that this was very much a route 4 type of endeavour, even if I was going down that route in a haphazard, clumsy way.

Naturally, working on this research and telling its story was not purely a route 4 thing. The paper is therefore a sum of this and all the other roads sort of taken. Perhaps, to tease out some of these alternate stories: 

**Route 1.** Ultimately, we did want to somehow help counsellors have better conversations--this was, after all, a key premise underlying our collaboration with Crisis Text Line.

**Route 3.** As we describe in the paper, the framework can be read as an empirical realisation of various dynamics previously noted in literature on discourse and counselling--a clear way to legitimise the work in the eyes of our intended academic audience. 

**Route 2.** What better reason for seeking a _computational_ approach than the possibility that it automates a human-level understanding of a conversational tension, for the sake of large-scale analysis--a raison d’être embedded in the NLP roots of the methods we used?

(As I outline below, there are also compelling reasons for not setting a course straight and narrow down route 4. And, if you happen to be a social scientist, you might raise your eyebrows at the prospect of a computer scientist trying to play your game. I completely understand.)

All of these alternate framings reflect a mix of genuine interest and reluctant compromises in the name of audience design (for instance, I’ve always found the “computation is needed for necessary large-scale analysis” story to be somewhat unsatisfying and circular). One of the most valuable lessons I learned from my advisor was how to understand and address these other perspectives while still producing research that was as true to us as possible. I’m not totally sure how he did it: my guess is some mix of extremely careful paper-editing and lively discussions about “getting the story right.” I hope to do that for my students too: I want to help you get lost in the woods without losing your way. 

---

If you're interested in working with me, here's what I think I'm looking out for. I'm interested in applicants that are fascinated by the tangly bits of social interaction, and who'd like to take a stab at describing just what's going on. I'd probably work best with people who have computational backgrounds, who in particular can wade their way into a very large and messy dataset. I really want to emphasise, though, that the point isn't coming up with fancy algorithms. I want to see a genuine curiosity in the social phenomena we're studying. I'd like us to be proud of having the courage to stick around when our models rub up against the real world and spark uncomfortable, generative frictions.

Maybe you don't feel that this perfectly describes you. Perhaps you are uncertain about your computational skills, or have doubts about your ability to navigate through different literatures on social interaction. Please don't rule yourself out; if even one of these points strikes you as something you'd really be interested in, it would still be good to talk. It's more about what keeps me up at night, what questions I think I’ll likely ask you at meetings, and what questions you’d hence most enjoy answering. It's also about what you'd teach me, too, in the parts where we don't match. Would we both get something out of wandering through the woods together? 

For instance, maybe you'd like to build conversational AIs (a very "route 2" thing). However, you'd like to go beyond whatever standards are set by the zoo of NLP benchmarks and AGI aphorisms: you believe that chatbots should be held accountable to the complexities inherent in human interactions. It’s not like the chatbot you want to build for your dissertation picks up a few social quirks here and there on its way to the Alexa prize. Rather, it somehow takes seriously, perhaps foundationally, what Suchman talks about in [_Plans and Situated Actions_](https://www.cambridge.org/us/academic/subjects/psychology/developmental-psychology/human-machine-reconfigurations-plans-and-situated-actions-2nd-edition?format=HB&isbn=9780521858915)--that purportedly humanlike AI systems embed assumptions that are disconnected from how humans actually (inter)act.

If this sort of thing resonates, then I think we see the landscape in similar-enough ways: I can help you explore it.
I don't know what such a dissertation would look like, but we rarely know from the start. That's what makes it interesting and PhD-worthy.

---

This--a route 4 take on social interaction and computational methods--is hard to traverse. If you’d like to work together, I think it’s worth recognising some of the challenges that I’d expect you to weather through with me. I'll try my best to support you through them, but know that they're always on my mind and in the way.

First, there are epistemological challenges. What types of methods can actually generate the types of social theories I’d like to produce along route 4?  If you read through Harvey Sacks’ [lectures](https://www.jstor.org/stable/20009056?seq=1) (hard recommend), he goes through all of these intricate qualities of conversations that are meaningful for making sense of them, and that ought to be accounted for. That implies a very fine-tuned, largely qualitative approach. My gut sense is that computational methods are useful too, but it's more a hypothesis than an a-priori commitment. The type of question we’d ask--and agonise over--again and again isn’t “how can computational methods help?” but rather this:  “well, more fundamentally, can they?” 

There are also practical challenges. What sorts of audiences are going to take up this sort of work? Or, more concretely, where the heck are we going to publish it? For lots of academic communities (spanning venues like ACL and CSCW), algorithmic innovations and design implications are currency. These are extremely generative standards to measure your work against, but things won't ever feel like a perfect fit. And if there are other standards--like whether the frameworks you propose have any theoretical _oomph_--I'm less fluent in the language and culture of communities who can evaluate and appreciate that.
If you're excited and nervous about navigating intellectual landscapes in this way, then I think it will be fun and rewarding to navigate together. But it will also be frustrating. 

I want to be upfront about this part of my PhD experience. I've spent countless hours mired in--no, _completely paralysed_ by these challenges. I don't have a recipe for navigating through them, except to say that I've learned to value the time I spend away from my research. If your PhD experience is anything like mine, you'll end up here too. I also think that I'm now in a place where I can help you get out of that swamp. 

---

A word about the department. I chose to join UMSI because I felt that it would be a great place to develop my research agenda and work through its constituent challenges. There are lots of very cool people in SI and elsewhere in the university, doing amazing work that both advances fields like NLP, HCI, sociology and political science, and that enriches critiques of them. I think that also makes SI a great setting for a student with these sorts of interests to thrive. Something else that drew me to SI is the support it provides, beyond just in the academic sense. There are many faculty members who are savvy to the tangles that come with being a part of the university, and who have a track record of selflessly helping students through them. 

If you resonate with anything I’ve said, and have weighed these thoughts in conjunction with everything else that should be on your mind as an applicant (my former officemate, Maria Antoniak, has a great [writeup](https://maria-antoniak.github.io/2020/11/27/phd-applications.html) on this)--then I really encourage you to apply to UMSI and put my name down as a potential advisor. I’ll look forward to reading your application and potentially working together. Of course, feel free to contact me with any questions; I promise that my emails aren't usually this long. 

And whatever you choose to do--good luck!

