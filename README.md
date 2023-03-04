<h1>Welcome!</h1>
<!--
**sarahcdev/sarahcdev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

- 🔭 I’m currently working on Java apps and blog posts 
- 💬 Ask me about security
- 📚 My favorite books lately are Spare, Prince Harry; Calypso, David Sedaris 
- 👯 I’m looking to collaborate on getting Ws in Ashika Island
- 📫 How to reach me: <span>sarahc</span><span>.</span><span>io</span><span>.</span><span>contact</span><span>[at]</span><span>gmail</span>


<h1> Blog </h1>
<p>I mostly write about software, video games, and current events. </p>

<div><p>(These are my personal thoughts and they do not necessarily reflect the views of my employer.)</p>
</div>
💻 = Tech, 🎮 = Gaming, 👩🏻‍💻 = Everything else
<div>
<!--<h3>Table of Contents</h3> -->
  <ul>
    <li><a href="#04032023-back">👩🏻‍💻 4 March 2023: I'm Back!</a></li>
  	<li><a href="#13042022-reading">💻 13 April 2022: Reading is Harder than Writing</a></li>
    <li><a href="#10072021-helpdesk">💻 10 July 2021: My Summers on the Help Desk</a></li>
    <li><a href="#09042021-containers">💻 20 April 2021: Solidifying My Understanding of Containers</a></li>
    <li><a href="#09042021-wfh">👩🏻‍💻 9 April 2021: A WFH Vignette</a></li>
    <li><a href="#20022021-vaccine">👩🏻‍💻 20 February 2021: The Vaccine Rollout  *</a></li>
    <li><a href="#23012021-teams">💻 23 January 2021: On Building Good Teams</a></li>
    <li><a href="#02012021-iam2">💻 2 January 2021: IAM is a hard problem - Part 2</a></li>
    <li><a href="#27122020-iam1">💻 27 December 2020: IAM is a hard problem</a></li>
    <li><a href="#23122020-food">👩🏻‍💻 23 December 2020: Food YouTube is Bad [published retroactively] </a></li>
    <li><a href="#14122020-symbolic">💻 14 December 2020: Notes on Symbolic Execution</a></li>
    <li><a href="#29112020-sowh">💻 29 November 2020: Strong Opinions, Weakly Held  *</a></li>
    <li><a href="#15082020-interviewing">💻 15 August 2020: Tech Interviewing is a Life Skill  *</a></li>
    <li><a href="#04082020-nosql">💻 4 Aug 2020: Notes on NoSQL Databases</a></li>
    <li><a href="#03082020-do">💻 3 Aug 2020: DigitalOcean Databases</a></li>
    <li><a href="#01082020-goals2">💻 1 Aug 2020: Checking in on my 2020 goals</a></li>
    <li><a href="#01032020-lambdas">💻 1 March 2020 Lambdas!</a></li>
    <li><a href="#27202020-tests">💻 27 Feb 2020: On Writing Good Unit Tests</a></li>
    <li><a href="#00002020-goals">💻 5 Things I Want to Learn (or improve) in 2020</a></li>

  </ul>
  <p>* = my greatest hits (IMHO) 😊</p>

</div>

<div>
  <h3 id="04032023-back"> 4 March 2023: I'm back! </h3>
  <p> I didn't really go anywhere, but I did take a year off from writing on this blog. I used to host this site on AWS Elastic Beanstalk,
  and I've moved it to GitHub Pages. After a long day doing computers at work, I just didn't want to come home and also work on computers. So I took the site down for a while. Today I woke up with a bunch of stuff on my mind that would make for a nice blog post, so I decided to bring this all back in a more low-maintenance way.</p>

  <p> I'm working on redirecting my domain <a href="https://sarahc.dev">sarahc.dev</a> to this blog. Some day I'll figure it out. </p>
</div>

<div>

  <h3 id="13042022-reading">13 April 2022: Reading is Harder than Writing</h3>
  <p>Ask any developer and they'll tell you: reading code is much harder than writing it. They will probably also say they do not read. There are countless examples -- just check tech Twitter -- of rewrites turning out badly. New code gets inherited, declared to be spaghetti, and rewritten. But during the rewrite, there's not enough time to do everything right. The rewriter cuts corners. They start to see the complexity. They re-write the same spaghetti, sometimes in a modern framework, and pass it on to the next person. I can't say it's not tempting. But I've mostly broken this habit, both because I trust those who wrote the code I'm inheriting, and because I've learned the value of a cohesive, if legacy, codebase. </p>

  <p>When I joined my most recent team, I had a lot to learn very quickly. I was also working remotely in a different timezone than the rest of the team,
   so I was doing a *lot* of observing until I understood anything at all. I would spend hours picking through code, leaving myself a trail of comments as the pieces sort of started to make sense to me. Slowly I became a better reader of Java -- I had spent a few years in C# land between my university Java courses and this role -- and of the idioms that my team used. </p>

  <p>It took me a few months to make any large scale additions or changes (say, more than a few lines or README comments). Once I did, I found a few things out: first, my team had a LOT to say about my PRs. Most of these were suggestions on style but some of them indicated larger mistakes I was making. Often I would get asked, "Why not just use X?" or "You should do it like Y." where the variables represented existing logic in the codebase that kinda, sorta, did what I was trying to do already. Sometimes I just didn't know it had already been done, while other times I didn't want to use it. It always felt like way more effort to understand the existing code and try to reuse it. But following those suggestions about style and reusability led me to have more idiomatic code. The style matched what was already there, reusing where possible. Idiomatic and standardized code is much easier to review and debug.  </p>

  <p>But I'm stubborn and sometimes I don't want to reuse the existing code. I'd have to transform the data or implement the interface or do some other annoying work that I didn't see the payoff for. So I would start rewriting it. I would think, "This makes so much more sense. I would be wasting hours trying to figure out how so-and-so's version of this works, and maybe not even be able to use it." Then I'd notice our classes would start to converge because I was developing for the same constraints that somebody had already worked around. Eventually I'd have a worse version of what already existed. I've done this enough times (and I will probably do it many more) to learn why I shouldn't. </p>

  <p>There's definitely an unknown unknowns effect at play here. A new team member doesn't know what complexities lie ahead or why something needs to be a little convoluted. "This should be easy to understand," I think to myself, "and the fact that it isn't, means that the original code is bad.' Especially with modern IDEs, you should just be able to hover over the token, figure out what it is/does, and move on to the next instruction until the algorithm makes sense. But it's not really that simple, especially in real life environments, especially when you're using other people's libraries. Code that would be super simple when written in terms of 'if' and 'for'-- if not tedious and exponentially complex -- is usually writen much more elegantly using IoC (see the "Replace Conditionals with Polymorphism" refactoring pattern), DI, Streams, and interfaces. And if a codebase is already following these conventions -- relying less on simple programming constructs and more on frameworks and language paradigms -- you'd be producing technical debt by rewriting something simply. It does take time to learn the idioms and rework the logic into those existing frameworks, but time-to-understand isn't a reliable indicator of quality.  </p>

  <p>What if the legacy code isn't better, though? What if the existing logic *is* actually bad, and I actually have a better way of doing it? I've run into that, too, and usually I make the improvements I see fit and let the code review sort out the rest. This is where the trust comes in. Most of the time, the really senior people on my team can be trusted to have implemented things reasonably the first time, with the benefit of history and insight and time to discover corner cases. If I didn't trust my team to write good code, I probably wouldn't learn from their code or find myself unintentionally reimplementing it as I discover the landscape. This allows me to start from a position of assuming the best about the code that's already there, and only change it if it really is bad. It wastes less time to assume it's good and learn that it's bad, rather than assume it's bad and rewrite it only to discover that it's actually good. </p>

  <p>Even with all that said, I wouldn't consider my failed rewrites to be a waste of time. Those painful exercises were important lessons in teamwork, assumptions, conventions, and even the software systems themselves. Implementing something from scratch is good for the brain and the ego, and in really complex systems, it's the only way to fully understand what's going on. </p>


  <p>As I mentioned in my SOWH post, a team needs to be rowing the boat in the same direction. It's equal parts trust, experience, and ability to learn difficult things.</p>

</div>



<br/>

<div>

  <h3 id="10072021-helpdesk"> 10 July 2021: My Summers on the Help Desk</h3>
  <p> It's a common-ish technologist's origin story: My first job was on the help desk. I learned a lot about how enterprise IT works, how the person on the receiving end of your ticket feels, and how people respond to change in their environments. I haven't written too much about it in the past becuase I like to keep this website separate from anything directly going on in my work life except in the abstract sense. But it's been long enough since I've worked in these places, and I'm not going to spill any secrets (not that I really know any).</p>

  <p>What I will say about it is that I worked on the help desk for a widget-making company. This was my summer job in college for two consecutive summers. My tasks included upgrading operating systems and software, as well as doing some general troubleshooting and break/fix. </p>

  <h4>Biggest Successes</h4>
  <ol>
    <li><b> Finding a system that worked for me. </b> The bulk of my time in the first summer was doing a mind-numbingly repetitive upgrade that for whatever reason couldn't be done as a remote push. I had to physically walk from computer-to-computer to do this upgrade, and repeat the steps every time. There were long periods of waiting between steps while something installed. All the moving parts were super overwhelming at first, but I came up with a system where I had the steps written out and I would just follow them, marking off on paper where I was in the process so I could start multiple at a time and go back and forth without losing information. </li>
    <li><b>Being plastic (as in, brain plasticity).</b> This is something I've struggled to hold onto as my career progressed, and I think I may make a longer post to elaborate on this point. But when I was early in my career, I was so much more flexible and adaptable than I am now. Some of that came from an unhealthy inability to say "no" to any request (which I've worked on with the help of some wise advice from more senior coworkers!) but a lot of it was just the help of having a beginner's mind. A newcomer doesn't see departments and titles and the lineage of an application as it grew from an idea to a roadmap to a production service. A beginner sees things as they are, without context, and can offer us some insightful observations that we can't see for ourselves. When I was working on the help desk at this widget factory, I was flexible. Once, a very confused delivery driver came to the wrong parking lot and asked me where he could drop off a package. I had no idea, and we weren't anywhere near the receiving office. He couldn't park in this lot, and I couldn't clearly articulate how to get to the right place. So I accepted the package and walked it to the receiving department myself. But just this week at work, I didn't know how a certain aspect of the QA handoff worked, and I dug around docs and thought about sprint review vs. roadmap vs. test cycle times and syncronizing my communications with the release cycle in the face of a bunch of uncertainty and I sat there scratching my head until I realized I could just SEND AN EMAIL to the QA team to explain my question. That realization would've come a lot quicker to me as a intern, just saying. </li>
  </ol>
  

  <h4>Hardest Challenges</h4>
  <p></p>

  <h4>Some Lessons Learned</h4>
  <ol>
    <li><b>Establish a collegial relationship first, whenver possible.</b> My first task, on my first day, was to map out the network ports of the entire office. Seriously, every single one. I had to walk to every cubicle, introduce myself, and ask to write down the number on the jack next to the person's name on my clipboard. But that meant I met the entire office within a week of working there. I realize now how big of a deal that was, because I will probably never again get the opportunity to meet every single person in any office. 99% of the people I encountered were extremely friendly and happy to meet a new face in the office. This made it a lot easier later in the summer when I needed them to log off so I could do something to their computer. It was still annoying, but I was a pleasant acquaintance annoying them. Not a stranger. That made a big difference. </li>
    <li><b>Change is hard, but it helps if you can be a partner.</b>This goes along with my point above that people <i>hate</i> change. But it's inevitable, and as the agent introducing change to somebody else, you can be a partner in bridging the gap. When people's favorite software was replaced with somebody else, I showed them how the replacement functioned very similarly. When they were too busy to make time for a 4 hour maintenance window, I offered to start it at 5pm at the end of my shift so it would be mostly done when they came in the next morning. <br/> I've carried this skill into my current role and it still helps me. Just recently, I again replaced somebody's favorite software and they told me they were extremely busy with their day-to-day tasks and didn't even begin to understand how to use the new one. Usually I would tell someone, politely, to Read the Fantastic Manual we wrote for it, but I could sympathize with somebody acting in a help desk role themselves, being overwhelmed with tickets due to the remote working model that was new to us all. So I took 45 minutes and walked them through the new software and got them going on their way. I didn't have to do that, and I usually wouldn't, but I've been there and it was the right thing to do. </li>
    <li><b>People want to see you succeed</b></li>
  </ol>

</div>

<br/>

<div>

  <h3 id="09042021-containers"> 20 April 2021: Solidifying My Understanding of Containers </h3>

  <p>Have I used containers? Sure. Do I know, like, 4 different ways to define them? Yup. Can I teach them to other people? Maybe!</p>

  <h4>Kelsey Hightower's definition</h4>
  <p>On episode 042 of Rails with Jason [1], Kelsey Hightower makes an analogy between shipping software and letting somebody borrow your toaster: it would be a lot easier if there were a standard way to package, ship, and run it (OCI, Docker), and even better if there were a way to scale and manage our toaster loan business (Kubernetes). I'd highly recommend this podcast episode to anyone just starting their container journey. </p>

  <p> The standardization aspect of Docker is really important. OCI, the Open Containers Initiative, sets the standard for container formats and runtimes. Docker is one implementation of containers (compliant with OCI standards of course -- they helped craft the standard!), but there are others with varying amounts of tooling/ecosystem built around them. Docker has built up quite a bit of an ecosystem around existing Linux containerization such as cgroups and namespaces. Docker Engine runs on containerd and, at a lower level, uses runc. [2] provides a detailed explanation of the relationship between these container runtimes. </p>

  <h4> So what IS it? </h4>
  <p> A container is an isolated, standalone package of software that contains an application and its dependencies. A container image runs on a container runtime, so a Docker image would run on Docker Engine. Where as virtualization at the VM level "slices up" a physical host's resources and shares them among many instances of an OS, virtualization at the container level shares one OS and one contianer runtime to run many isolated images at once. This decreases the overhead of running an OS (especially if the app itself doesn't need a lot of OS resources) and decouples the application from the server it's actually running on. So if you want to write an app using Python 3.7 and ship it via Docker, you don't have to worry about whether <i>I</i> have Python 3.7 installed on my laptop. </p>

  <h4> But can't I get a Docker image of an OS, like Ubuntu? </h4>
  <p> You can. Might be easier than setting up a hypervisor or dual-boot, if you just need a quick instance of an OS. But that's still running in a container on top of a runtime on top of an OS. Maybe you have OS X installed on your laptop as the boot OS but you want to try out Ubuntu -- go for it.  

  <h4> How's that different from, say, Java's Write Once Run Anywhere? </h4>
  <p>They're similar concepts! Both aim to provide a standardized experience for running code that was written once in a specialized runtime environment that's expected to be the same everywhere, regardless of the operating system or hardware underneath. They're different because the JVM isn't isolated from the rest of the OS when it's running. JVM can be just one of many other processes running on a single OS, whereas a container "thinks" it's running the only process. A fat jar aims to accomplish something similar to contianerization with respect to dependencies. </p>

  <p> If you went the fat jar route instead of using containers, you would still have to use/ write a lot of tooling to build, package, distribute, and manage your fat jars. You'd probably end up using a bunch of other tooling like Ansible, TerraForm (as emphasized in the podcast I mentioned) -- and that's fine! -- but it inflicts a cost on your engineers and operators who have to use and support a custom process. Using Docker and K8s is probably easier in the long run because it's well-known in the industry. </p>

  <p>It's important to remember that most technology isn't magic, even if all the buzz has made it seem that way. Docker undoubtedly uses the underlying OS in clever ways (that I don't understand fully), and that's a big deal. But it's not impossible to start digging into, and that's the only way to start really understanding it. </p>


  <h4> Some good things to know </h4>
  <p>
    <ul>
      <li> <b>Dockerfile -- a collection of commands that are used to build an image, but kept as code for easier management.</b> This is where you tell your image which base image you want to use (FROM), any custom shell commands you need to run while building an image layer -- such as installing software (RUN), commands to run once the image is spun up (CMD as default that can be overwritten, ENTRYPOINT as default that cannot be overwritten), files to copy into the image (ADD or COPY), set the working directory for the RUN, CMD, ENTRYPOINT commands that follow in the Dockerfile (WORKDIR), and more. See the Docker spec for more details on the possibilities. </li>
      <li> Port mapping -- how to redirect traffic between Docker runtime host and container (e.g. if your container is hosting an API) </li>
      <li> Docker volumes -- how to persist data from inside a container </li>
      <li> $ docker ps # see running containers </li>
      <li> $ docker exec it [container id] bash # this is how you can get a shell inside of a running container and poke around. </li>
      <li> $ docker build # build from your Dockerfile </li>
    </ul>
  </p>


  <h4> References </h4>
  <ol> 
    <li>https://faun.pub/docker-containerd-standalone-runtimes -heres-what-you-should-know-b834ef155426 </li>
    <li>https://railswithjason.simplecast.com/episodes/ kelsey-hightower-3PKFlk81</li>
  </ol>

</div>

<br/>
<div>

  <h3 id="09042021-wfh"> 9 April 2021: A WFH Vignette </h3>

  <p>If you have a Zoom meeting with somebody who doesn't know about your excessive notetaking habit, they may get the frustrated impression that they are talking at you while you look at your phone off-camera. So then you might have to awkwardly pick up your notebook to face height, loudly flip a page, and awkwardly write a note in camera view. </p>

  <p>Maybe a new bullet point for those Zoom etiquette articles.</p>

</div>
<br/>

<div>

  <h3 id="20022021-vaccine"> 20 February 2021: The Vaccine Rollout </h3>

  <p> As of today, 13% of the US has received a first dose and 5.1% has received a second dose of the COVID-19 Vaccine [1]. Currenly only the Pfizer-BioNTech and Moderna vaccines are approved for use in the US, under Emergency Use Authorization by the FDA [2][3]. Both of these vaccines use mRNA technology, which is something I only understand at a basic enough level to weigh the pros and cons for myself given the situation the world is currently in. Long story short, I am eligible in the current phase of rollout in my area and I received my first dose of Pfizer yesterday. All things considered, it was a pretty well run operation at the vaccination site, and I'm extremely grateful to have gotten a vaccine. But my experience was still stressful, and it hasn't been easy for anyone. </p>

  <h4> Eligibility </h4>

  <p>I mentioned that I am eligible in the current phase of rollout in my locality. My state has different criteria for eligibility even from our neighboring states. In many places, I would not be eligible for a few more weeks to months, depending on their plan and supply. This has been extremely frustrating for my family living in other states. They are not yet eligible and their states are not receiving enough supply to further open up eligibility any time soon. Some states are prioritizing only by age group and occupation [4], while others include high-risk individuals as defined by the CDC or define their own set of extra occupations that also qualify [5]. The rollout plan is a totally disjointed public health decision that has literal life-or-death consequences, and I have yet to talk to somebody who believes their local government got it right. </p>

  <h4> Science </h4>

  <p>While most people I've talked to are eager to be vaccinated, there are still a lot of unknowns that make the decision complex. I <b>strongly</b> support vaccination in general. Among the many terrible consequences of the "anti-vaxx" movement is the way it has co-opted discourse about vaccine safety, making it difficult for people to sincerely voice their evidence-based concerns about specific vaccines in specific circumtances. One of these concerns is the decision between Pfizer and Moderna. On this subject, I generally agree with the idea that the best vaccine is the one that's in you. But I also know that there are differences in how the shots are tolerated (e.g. Moderna may cause swelling/reactions in people with cosmetic fillers [6]), and that could influence somebody's decision to get a particular vaccine when it's available. </p>

  <p> The decision to get vaccinated at all, or at least any time soon, is also on people's minds. mRNA is a relatively new technology [7], so I can understand people having questions about how it works and why it's being used. The NIH lists three main types of vaccine mechanisms: whole pathogen, subunit, and nucleic acid. mRNA (Pfizer and Moderna) and DNA (Johnson and Johnson) vaccines are both nucleic acid vaccines (RNA = ribonucleic acid, DNA = deoxyribonucleic acid), which instruct the body to create a small, non-infectious part of the virus so that the immune system can learn how to fight it when exposed to the real thing. [8] </p>


  <p> There are other vaccines being developed around the world which do not use the nucleic acid mechanism. For example, NovaVax is a subunit vaccine [15], and Sinopharm is an inactivated virus vaccine [16]. It seems reasonable to me that people would trust these other mechanisms more while the nucleic acid type may be new to them. For now, the decision to get any COVID vaccine in the US is a decision to accept a nucleic acid vaccine. </p>

  <p>If this weren't such an urgent situation, I might think twice about getting a vaccine that is yet only EUA-approved, using a technology that's relatively new. But having followed the COVID pandemic closely in the news for the past year, I know that a COVID infection would be very dangerous to my health and could have lasting long-term effects [10]. It's really a comparison between a vaccine with unknown (and yet unfounded) potential long-term effects vs. a known-to-be-deadly virus with known long-term effects. While it's true that some COVID infections are asymptomatic or mild, I am not willing to take my chances, especially when hospital systems have become overwhelmed due to the number of cases and intensity of care required [11]. </p>

  <h4> Logistics: Getting an Appointment </h4>
  <p>One of the biggest pain points that I've heard (and experienced) is the act of securing an appointment. This is another part of the rollout that has been disjointed and confusing, even within a single state. There are state- and county-run sites, local/regional initiatives put on by universities, individual hospitals and doctors' offices, and retail pharmacies that are offering vaccines in different places. Some of these, at least in my area, have a waitlist while others have appointment websites or hotlines (the difference being a "we'll call you" vs. a "you call us"). I can't speak to the experience of calling the hotlines, but I can speak to the experience online -- and it's rough. Not one of the "we'll call you" sites has yet contacted me. </p>

  <p>Getting an appointment through a website could be a part-time job. Many of these sites will drop appointments at random times or all at once at an unpredictable hour of the day. Others remain full for days until sporadic appointments open due to cancellations. I found myself hitting the refresh button all day, every day, for almost a week until I secured a spot. I stayed up until 1am. I woke up at 5am. I neglected to text my friends back because I was so mentally exhausted from doing this all day. Often times I would find a spot, enter my information, and click Submit only to find that the website wasn't actually holding the appointment for me (which meant somebody else selected the same time but submitted faster). I'm pretty good with filling out forms, typing, etc. but not everybody is, and this makes the process very difficult for someone who is slower at typing or not as familiar with using the internet. Luckily most of these sites try to prevent automation so at least it's other humans that are competing, but CAPTCHAs can present another layer of inaccessibility [17]. One strategy employed by a vaccine site near me is to use a scheduled virtual queue that opens 1 hour before appointments are made available. People enter the queue any time in that hour and are assigned a random number. The queue is processed in order, so theoretically this is more fair because there is no advantage to getting there early. I entered the queue once and my lucky number was >42,000, in a system with 1525 appointments available that day. </p>

  <p>
  Clearly there are some people for whom online scheduling will be an impossible task because of the challenges described above. Even the concept of MyChart (e.g. "Do I need one to make an appointment? "Do I already have one from my last visit to this hospital?" "I don't have an email address.") adds a layer of frustration, since there seems to be a new instance of MyChart for each major hospital system. The MyChart used for scheduling my appointment required me to go through a verification that asked questions about my financial history and past addresses to confirm who I was. This is far too many steps to be reasonably asked of someone who may not even have a computer or email address. For many in this situation, they will have to rely on help from their personal network or kind strangers [9] to do the heavy computer lifting for them, if they are able to find that help at all. </p>

  <h4> Logistics: Standing in Line</h4>
  <p>Once I cleared the hurdle of securing an appointment, I had to actually go get the vaccine. Mine was distributed at a large events complex with support from a local hospital system and the military. I stood in a long line for over an hour, received my shot at a folding table in a large room with probably 20 other vaccine tables, and sat for 15 minutes in an observation area with chairs spaced 6 feet apart. Though nearly everybody in line was wearing a mask and keeping some (not 6 feet, but some) distance, I still felt like I was at high risk for exposure. It's ironic and maddening that the vaccine clinic could be where somebody became infected. Some of the wait was outside in the cold, though I didn't mind this part because being outdoors allows for better ventilation. </p>

  <p>The experience was a little surreal. At times, I found myself realizing that this is what a disaster response looks like: crowded, the military and government are involved, and everything is strictly utilitarian and optimized for the masses. A soldier points a laser thermometer at you before you're allowed in. You don't get your own private room like at a doctor's office. Nobody asks you your medical history except for the screening questions. You are handed a copy of the EUA that outlines the risks and benefits. You are given a CDC-branded vaccination record card and told never to lose it. When your 15 observation minutes are up, you check out with the soldier at the exit and wander back to your car in silence like you didn't just live through a major historical event. </p>

  <h4>Bottom Line: Why I Got it Yesterday</h4>
  <p>After considering all of the risks of COVID, the vaccination, and the exposure of standing in line, I ultimately decided to get my vaccine. I knew I could potentially put it off for a while and let the rush calm down, but since my state is still in Phase 1, I knew there would be a <b>lot</b> of people in line ahead of me if I tried to wait it out. By this summer, who knows what the case numbers or variants [12] will look like. We are in a period of relatively low infection for the US [1] compared to two months ago. And the two-dose mRNA vaccines that are available now are more effective than the single-dose Johnson & Johnson vaccine that was submitted for EUA on Feb 4th [2][3][12][13]. All of these factors together led me to my place in a line, with hundreds of people, at an empty sporting complex, being ushered by the military, receiving a vaccine for the virus that upended my life (and the whole world) over the past year. I got emotional the night before when I realized it was a step forward in a time that has felt so stagnant and hopeless for so long. </p>

  <h4> Sources </h4>
  <p>
  <ol>
    <li>“Breaking News, US News, World News and Videos,” The New York Times. [Online]. Available: http://www.nytimes.com/. [Accessed: 21-Feb-2021]. </li>
    <li>“FACT SHEET FOR HEALTHCARE PROVIDERS ADMINISTERING VACCINE (VACCINATION PROVIDERS) EMERGENCY USE AUTHORIZATION (EUA) OF THE PFIZER-BIONTECH COVID-19 VACCINE TO PREVENT CORONAVIRUS DISEASE 2019 (COVID-19).” [Online]. Available: https://www.fda.gov/media/144413/download. [Accessed: 20-Feb-2021]. </li>
    <li>“FACT SHEET FOR HEALTHCARE PROVIDERS ADMINISTERING VACCINE (VACCINATION PROVIDERS) EMERGENCY USE AUTHORIZATION (EUA) OF THE MODERNA COVID-19 VACCINE TO PREVENT CORONAVIRUS DISEASE 2019 (COVID-19).” [Online]. Available: https://www.fda.gov/media/144637/download. [Accessed: 20-Feb-2021]. </li>
    <li>“OHA 3527A Vaccine Sequencing Infographic.” [Online]. Available: https://sharedsystems.dhsoha.state.or.us/DHSForms /Served/le3527a.pdf. [Accessed: 20-Feb-2021]. </li>
    <li>“Phased Distribution of the Vaccine.” [Online]. Available: https://covid19vaccine.health.ny.gov/phased-distribution-vaccine#phase-1a---phase-1b. [Accessed: 20-Feb-2021]. </li>
    <li>Should You Avoid the COVID-19 Vaccine if You Have Dermal Fillers? [Online]. Available: https://health.clevelandclinic.org/should-you-avoid-the-covid-19-vaccine-if-you-have-dermal-fillers/. [Accessed: 20-Feb-2021]. </li>
    <li>M. D. Anthony Komaroff, “Why are mRNA vaccines so exciting?,” Harvard Health Blog, 19-Dec-2020. [Online]. Available: https://www.health.harvard.edu/blog/why-are-mrna-vaccines-so-exciting-2020121021599. [Accessed: 21-Feb-2021]. </li>
    <li>“Vaccine Types,” National Institute of Allergy and Infectious Diseases. [Online]. Available: https://www.niaid.nih.gov/research/vaccine-types. [Accessed: 21-Feb-2021]. </li>
    <li>NBC New York, “'Strangers Helping Strangers': Facebook Group Helps Those Searching for Elusive COVID Vaccine,” NBC New York, 20-Feb-2021. [Online]. Available: https://www.nbcnewyork.com/news/coronavirus/strangers-helping-strangers-facebook-group-helps-those-searching-for-elusive-covid-vaccine/2900070/. [Accessed: 21-Feb-2021]. </li>
    <li>“COVID-19 (coronavirus): Long-term effects,” Mayo Clinic, 17-Nov-2020. [Online]. Available: https://www.mayoclinic.org/coronavirus-long-term-effects/art-20490351#:~:text=COVID%2D19%20symptoms%20 can,within%20a%20few%20weeks. [Accessed: 21-Feb-2021]. </li>
    <li>“With LA hospitals overwhelmed by COVID-19, EMS told not to transport certain patients,” ABC News. [Online]. Available: https://abcnews.go.com/Health/la-hospitals-overwhelmed-covid-19-ems-told-transport/story?id=75060756. [Accessed: 21-Feb-2021].</li>
    <li>“About Variants of the Virus that Causes COVID-19​​,” Centers for Disease Control and Prevention. [Online]. Available: https://www.cdc.gov/coronavirus/2019-ncov/transmission/variant.html. [Accessed: 21-Feb-2021]. </li>
    <li>“Johnson & Johnson Announces Submission of Application to the U.S. FDA for Emergency Use Authorization of its Investigational Single-Shot Janssen COVID-19 Vaccine Candidate,” Johnson & Johnson. [Online]. Available: https://www.jnj.com/johnson-johnson-announces-submission-of-application-to-the-u-s-fda-for-emergency-use-authorization-of-its-investigational-single-shot-janssen-covid-19-vaccine-candidate. [Accessed: 21-Feb-2021]. </li>
    <li>J. Corum and C. Zimmer, “How the Johnson & Johnson Vaccine Works,” The New York Times, 18-Dec-2020. [Online]. Available: https://www.nytimes.com/interactive/2020/health/johnson-johnson-covid-19-vaccine.html. [Accessed: 21-Feb-2021]. </li>
    <li>“Novavax COVID-19 Vaccine Demonstrates 89.3% Efficacy in UK Phase 3 Trial,” Novavax Inc. - IR Site. [Online]. Available: https://ir.novavax.com/news-releases/news-release-details/novavax-covid-19-vaccine-demonstrates-893-efficacy-uk-phase-3. [Accessed: 21-Feb-2021]. </li>
    <li>J. Corum and C. Zimmer, “How the Sinopharm Vaccine Works,” The New York Times, 30-Dec-2020. [Online]. Available: https://www.nytimes.com/interactive/2020/health/sinopharm-covid-19-vaccine.html#:~:text=A%20Vaccine%20Made %20From %20Coronaviruses,proteins%20that%20stud%20its%20surface. [Accessed: 21-Feb-2021]. </li>
    <li>“Captcha Alternatives and thoughts,” Captcha Alternatives and thoughts - WCAG WG. [Online]. Available: https://www.w3.org/WAI/GL/wiki/ Captcha_Alternatives_and_thoughts. [Accessed: 21-Feb-2021]. </li>
  </ol></p>
</div>
<br/>
<div>

  <h3 id="23012021-teams"> 23 January 2021: On Building Good Teams </h3>

  <p>I've had a lot of thoughts on my mind about software engineering as a practice, team building, and aligning developer interests with business interests. These are mostly separate themes, but they feel tied together for me because they all relate to how I personally want to contribute and learn from being on a team. </p>

  <h4>Part 1: Assets, Practices and Outcomes</h4>

  <p>The first thought I have is about separating assets, practices, and outcomes. In my mind, assets*practices=outcomes. Products then result from outcomes being expertly organized into something sellable and marketable. </p>

  <p>Assets are the tangible things that are created and maintained on a day-to-day basis, in their most raw form. I would consider this to include a code base, infrastructure playbooks, docs, diagrams, and (the nebulous idea of) team knowledge and bond. These are different from products: whereas a product might be Instagram, assets would include the source code, deployed instances of microservices, developer documentation, infrastructure as code, etc. that technologically enable Instagram to exist as an app. </p>

  <p>Practices are the behaviors, rituals and standards that the developers follow day-to-day. Some examples include code reviews, retrospectives, blue/green deployments, incident response procedures, CI/CD, cloud-native architecture, and Agile/Scrum project management. </p>

  <p>Outcomes are the abstract things that are achieved. Outcomes aren't quite products yet, because products require business-savvy people to package up those outcomes into something that can make money. Some examples of outcomes include features, uptime, average daily users, revenue, reputation, company culture, employee retentinion, code maintainability, and code testability. </p>

  <p>Using this framework, I can explain why I think some teams invest in certain assets and practices, but not others, depending on what their objectives are. </p>

  <h4>Part 2: What kind of team am I on?</h4>

  <p>I believe that there are fundamentally different types of tech teams out in the world. I don't think all teams and managers think about it in these terms, but tech teams are fundamentally one type or the other, and that has strong implications on the developers' quality of life while they're on that team. The first type of team is what I would call Product-Oriented, where technology is the means to a business end. This type of team creates a product that requires use of technology in some capacity, but the technology itself isn't the star of the show. An example might be a real estate website, where devs are essential but not necessarily important in the scheme of things. The business is real estate listings, not code for real estate listings. </p>

  <p>The second type of team is the Practice-Oriented team, which has built value over time by investing in sustainable tech practices. The tech drives the value, and just in the, "The whole business revolves around an app" type of way. The reasons to build a Practice-Oriented team are analogous to why Martin Fowler believes in refactoring (as he writes in ch 2 of his book, <i>Refactoring</i>): because it makes it easier to add more features later. Whereas a Product-Oriented team derives its worth from what is, Practice-Oriented teams derive their value from what could be. </p>

  <p>You might be thinking that the difference between these types of teams is so subtle that it's essentially nonexistent. But I think the best way to distinguish between them is to ask, "If this company were to be acquired tomorrow, is the value of the acquisition derived <b>primarily</b> from the product or the technology organization behind the product?" I'm not asking about the code base vs. the product, but the whole of the assets vs. the product. In other words: if you fired all of your developers and burned the docs and handed off the product to a brand new team of reasonably good devs, is it still worth as much? If not, you probably have a Practice-Oriented team.</p>

  <h4>Part 3: Why does it matter?</h4>
  <p>So maybe it's valuable to have a Practice-Oriented team if you plan for your company to get acquired in the near future and you want to include the maturity of your teams as a selling point in the deal. But what about for other companies that aren't looking to be acquired? Does it matter if they have a great product and, well, terrible software practices? I would generally say that yes, it does matter, because bad practices are not sustainable in the long term. And what about for teams that have a great product via bad practices but have managed to set themselves up so they are, in fact,  sustainable in the long term? Isn't the point of all of these practices to drive sustainable business value? I guess so, but I'd be genuintely interested in seeing some examples of bad practices -> smash-hit, profitable, long-lived product with happy developers.</p>

  <p>I would suggest that, hopefully, a team could transition from Product-Oriented to Practice-Oriented over time as they scale their services up. It doesn't make sense for a 3 line Python script to be tested, on CI, code reviewed by 3 people, and written up into a Scrum User Story. But some day when there are dozens of Python scripts containing hundreds of lines of code, best practices will save the team from drowning in technical debt. Analogously, a small team with a simple product might not see the ROI of setting up all these systems to track small amounts of work. It makes sense to create a minimum viable product using minimum viable procedures, especially in a startup environment where nobody knows if the product will even make real money. But if that team wants to later scale and add features quickly, they will need to start adopting best practices <i>at the right times</i> to keep pace with their own growth. It's a delicate balance, investing minimal resources in things that aren't necesssary yet, while heading off the inevitable avalanche of technical debt that will come due quicker and more expensively as the product finds success. </p>

  <h4>Part 4: Don't we all have to be product people? + Aligning incentives </h4>

  <p>I don't think it's always the fault of the team that it's not yet Practice-Oriented. For a lot of companies, and particularly ones that don't consider themselves "tech companies", there's little incentive to invest in practices until the crossover point of cost vs. time between Product-Oriented and Practice-Oriented. I can't argue with that from a business perspective: it's smart not to invest too much in sustainable practices until you know that the product will require sustaining. But for that in-between time, when the product is growing but the team hasn't started investing in good practices, it's painful for developers.</p>

  <p>For me personally as a developer, I hate working on products without the minimum amount of infrastrucutre around them. Unless I am truly working on a small/insignificant personal project, I at the very least need to be able to use version control, write tests, and deploy in a sensible way. I think my tolerance for Product-Oriented development is pretty low in professional settings but higher in personal settings. I guess the stakes are just different. If I break something at work because I didn't follow good practices, that reflects poorly on me, and I'm responsible for making sure it doesn't happen again anyways. If I break something at home because of the same reason, I get to decide if I want to fix it on the fly or invest my own personal time in making it more sustainable. When I'm wearing my Professional Developer hat, I am much happier when I feel like my team is being Practice-Oriented because it reflects well on our collective growth over time, and it's just a better experience for me.</p>

  <p>It seems counterintuitive that I think of Product-Oriented teams as being less mature than Practice-Oriented teams, since it's probably more profitable for developers to understand and sympathize with their customers than to be heads-down, grinding out code. Customer feedback is one of the purposes of Agile: to enable developers to liase directly with stakeholders, respond quickly to changes, and frame features as user stories. But I think that good developers -- even in early stage teams -- are always thinking big-picture. It takes significantly more experience and effort to deliver great big-picture outcomes via sustainable practices. Developers can deliver great products using poor practices, at least in the short term, if they put in overtime and think fast -- like manually restarting services as they see "your product is broken" user tickets rolling in. Practice-Oriented teams can do this indefinitely by making clever use of their time and skills. Some examples of this might include: robust unit and integration testing, which can increase uptime; refactored code that allows for features to be added quickly; automated infrastrucutre playbooks to scale up services during traffic spikes.</p>

  <p>So while it's not always the best business decision <i>in the short term</i> to invest heavily in practices, it is something that improves the quality of life of your developers and prevents too much technical debt from plaguing the product in the future. And while it's definitely possible to over-invest in practices that may not be needed, or lead your developers to have their focus too strictly on the tech than the final product, sustainable practices should be a natural progression for a team that already clearly understands its product and customers. Knowing exactly when the time is right to start investing is wisdom that probably just comes with experience.</p>

  <h4>How to navigate this as a dev</h4>

  <p>It can be difficult to get support for these practices if your team can't see the value proposition yet. The first thing you should do is make sure that the practice you'd like to adopt really honestly will be beneficial in the short, medium, and long term. It helps to know the disposition of your team when it comes to making changes. Maybe your team wants minimal formal practices, so you have to make a case for why your idea is strictly better than what's currently in place. Maybe your idea is only slightly better than the current state of the world, but you'd benefit greatly to learn a new tool so you propose it as a win-win for the team and yourself. My best advice in any case is to keep your finger on the pulse of tech, and to learn how to balance excitement for new and hot technologies with your desire to grow as a developer and with the overall goals of your team at its current maturity.</p>

  <p>And once you start getting significantly slowed down by technical debt, talk to your team about making those investments sooner rather than later.</p>

</div>

<br>

<div>

  <h3 id="02012021-iam2"> 2 January 2021: IAM is a hard problem - Part 2</h3>

  <p>In my last post, I talked about managing identities for services like Postgres and AWS. In this post, I'll talk about managing identities for end users to my app.</p>

  <p>Identity management is not easy, and I don't particularly want to be responsible for managing user ids, passwords, etc. It's not the focus of my app and, like many things in security, it is best left to well-known libraries which implement standards. One way to authenicate on the web is via Open ID Connect (OIDC), which is built on top of OAuth 2.0. OIDC allows an app ("client") to retrieve user data from an identity provider such as Google, enabling end users to authenticate to the client using their Google login.</p>

  <p>I used <a href="https://realpython.com/flask-google-login/">this tutorial</a> from Real Python, which made the setup super easy. </p>

  <p>The auth flow used here is Authorization Code Flow, which does the following <a href="https://rograce.github.io/openid-connect-documentation/explore_auth_code_flow">(this was a good resource for me to learn):</a> </p>

  <ol>
    <li>Client (app) requests auth for end user to IdP (triggered when end user clicks "log in with Google" on app)</li>
    <li>IdP asks end user to authenticate and consent to data being sent to client (end user presented with, e.g. Google login screen hosted by Google)</li>
    <li>IdP returns authorization code to client</li>
    <li>Client uses authorization code to get user info tokens from IdP</li>
    <li>Client uses tokens to get <a href="https://developers.google.com/identity/protocols/oauth2/openid-connect">user info</a> (such as email address, name)</li>
  </ol>

  <p>From there, especially when using the flask session/ user libaries, it's super easy to start using user info in the app. </p>


</div>

<br/>

<div>

  <h3 id="27122020-iam1"> 27 December 2020: IAM is a hard problem</h3>

  <h4>AWS, IAM, and my current example of this problem</h4>
  <p>My current project is a little website that uses a hosted Postgres database. The project turned out, at least on the first day, to be more about AWS IAM and less about websites and databases. AWS IAM itself is pretty good; it's granular, role-based (if you want!), and can be defined as JSON. It also offers a variety of access options, like console/password and API key. Unfortunately, most enterprise software doesn't do identity very well. A lot of applications, such as Postgres, have their own account components. That means more accounts and more passwords and more permissions to manage. When you use Postgres through AWS, for example, you're given a "master" account on the database that has a password. It has nothing to do with any of your AWS IAM accounts that you so lovingly crafted, and that makes your infrastructure less secure. Software (including every AWS account) generally has one master account and key that isn't otherwise attached to an identity provider or directory, and that's a good thing if it's managed correctly. The other accounts, including day-to-day users, would be managed best using some sort of access management system that isn't built into the app.</p>

  <h4>What can be done about it? </h4>
  <p>Typically, integrating account systems like this involves directory mappings, infrastructure "glue", or accepting the fact that you'll need more accounts and passwords (and maybe a password vault/manager). I was glad to find out that the infrastructure "glue" was an option for me with Amazon RDS Postgres, since the other options were infeasible (directory mappings) or undesirable (more passwords) for me. AWS has some glue to integrate existing IAM accounts with Postgres usernames on RDS-hosted Postgres. </p>

  <h4>How it works in this case </h4>
  <p> In AWS, you can <a href="https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/UsingWithRDS.IAMDBAuth.IAMPolicy.html">define a Policy</a> that grants (Effect) connection (Action) on your database ARN (Resource). You have to specify which Postgres user it is mapped to. Then you can apply this Poilcy to users/ groups in IAM, so particular AWS IAM users are allowed to log into the Postgres DB <i>as the Postgres user</i> without having a new password and login. Then you can use your IAM API token to ask AWS for a database auth token. </p>

  <p>This offers several advantages over a username/password situation:
    <ol>
      <li>Users don't have to remember another password</li>
      <li>AWS admin can revoke user's access at any time via the AWS console without touching Postgres (ability to generate db auth token = access)</li>
      <li>Database access can run as its own non-human identity without using a password or affecting existing human users</li>
    </ol>
  </p>

  <p>I'm especially excited about point #3 because I think it's a super bad practice to run apps as human identities, but it's so easy to just use an existing account/password. Running processes as yourself makes you the bottleneck (what if you quit? what if you forget your password?), tends to result in over-permissioning of your own account, and turns simple authorization changes into a complex web of settings that can break other things. You should have an identity for each app in order to keep authorizations simple and permissions at the lowest level possible. </p>

  <h4>Ok, but don't you still have a static AWS API key?</h4>
  <p>So as good a solution this is, it's not the end of keys. There's still that chicken-or-egg authentication problem which requires you(r app) to authenticate to AWS. This particular solution requires that the AWS API key be the initial authentication to AWS. Then AWS generates the database auth token so the IAM user can authenticate to Postgres <i>as the Postgres user</i>. An acceptable way to handle the API keys is via aws configure, which allows the user to store them locally. In my case, I connect to my database from a Python app, so I use boto3 to access my AWS API keys in a cred file. There are <b>no credentials in code ever ever EVER</b>, which makes me happy. If I wanted to be super, extra careful, I could try to store the AWS API keys in a password manager or HSM, but when it comes down to it, there will always be some kind of known key/certificate in order to gain access to the other keys. </p>

  <p>But at least this way, I have a dedicated AWS IAM user, with access to only one AWS resource, that maps to one Postgres user. When I run my Python app, it connects to the database as the mapped user. If I ever need to revoke that user's access, I can disable the IAM user's API key or remove the Policy.</p>

  <h4>But how?</h4>
  <p>I'm not exactly sure how AWS is doing this on the back end, but the database auth token signature looks like it's unique each time it's generated. That's important because it means the tokens are being verified by some kind of cryptography, they can expire, and access can be revoked easily. Probably what's happening is there's an asymmetric keypair between the Postgres db and AWS, which is used to generate and verify the token. If AWS is provided with the correct AWS API keys for an account that has permissions to login to the database under a particular Postgres username, then AWS uses the private key to sign a token and passes the token back to the user. The user passes the token to Postgres, and finally Postgres uses the public key to verify the signature and allow access. AWS-hosted Postgres must also have an AWS IAM role defined so this mapping can work. </p>
</div>

<br/>

<div>
    <h3 id="23122020-food"> 23 December 2020: Food YouTube is Bad [published retroactively] </h3>
    <p><i>I found this draft I wrote about YouTube and parasocial relationships with food content creators in 2020. I'm publishing it now [in 2023]. A lot has happened since December 2020, but it's an interesting window into what the internet was like in 2020. I made some minor edits, but the majority of it is original.</i></p>
    <p>I’ve primarily watched the same 3-4 cooking YouTube channels for a few years now: Bon Appétit (BA), Babish Culinary Universe (Binging with Babish), and Joshua Weissman. I don’t watch much of BA any more since <a href="https://www.washingtonpost.com/news/voraciously/wp/2020/08/06/three-bon-appetit-video-stars-leave-the-test-kitchen-series-due-to-alleged-racial-discrimination/">this all </a> came to light in June, but after I stopped watching it, I had some time to think about it. The BA YouTube channel sold me a lifestyle of expensive materials and self-loathing, much in the way that other mass media organizations sell those doubts about physical appearance and social standing. I picked up a few cooking tricks here and there from BA, but I picked up even more bad attitudes and pseudo-intellectual hot takes about food that do more harm than good for me. The other channels I watch suffer from some of the same problems, but BA does it in a really attractive and deceptive way. I’m not arguing that <i>nobody should watch BA</i>, or that <i>BA is doing something bad for the world.</i> I watched many hours of BA content because I liked it so much! But I do think the Test Kitchen has a complicated relationship with instruction, advertisement, and parasocial interaction. Viewers beware: this relationship may affect how you see yourself and the social context of your own kitchen. </p>
    <p>
    <h4> Them and Us </h4>
    <p>As I've seen others online point out, BA’s running video series’ were more about the chefs’ personalities than the food. The long format episodes of <i>Gourmet Makes</i>, <i>It’s Alive</i> and <i>Alex Eats Everything</i> focused primarily on personas and relationships within the Test Kitchen, making the viewer both want to <i>be with them</i> and <i>be them.</i> The chefs talked directly into the camera to us, hanging out like old friends over dinner. They made a conscious effort to break the fourth wall in every episode, showing clips of the chefs talking to the crew and making jokes about their own blunders. As nice as these unreciprocated relationships may have felt to the viewer, especially in pandemic times, they were advertising a high-class lifestyle by talking down to us. BA made the viewer feel a little too poor, a little too unskilled, and a little too unrefined to stop watching for fear of being left behind. We, the viewers, needed Chris Morocco’s “sensitive” palate and Claire Saffitz’s cultural capital to guide our unsophisticated fingers to the cultural pulse of the cooking world. We didn’t go to culinary school (and neither did Molly Baz, a fact that then Editor-in-Chief Adam Rapoport said on camera <a href="https://www.youtube.com/watch?v=goIN2WGYafg">more than once</a>). We don’t shop at the FiDi Whole Foods. We can’t drive to upstate New York and buy fresh ostrich eggs and then make them into Jean-Georges eggs because we don’t know who Jean-Georges is. The Test Kitchen chefs are better than us, and they know it. But we can have a seat at their table if we buy in, financially and intellectually, to their world.</p>
    <h4>They Hate the Food We Eat</h4>
    <p>A lot of what I dislike about BA and Weissman is the way the chefs dismiss foods that they think are below them. See Weissman's <i>But Better</i> series (granted he also has a <i>But Cheaper</i> series, with good intentions but aspirational accounting methods.) When they cook something quickly with a simple technique, they spin it as a fast recipe that they definitely could do better, if they wanted to.</p>
    <p>Alex Delany’s entire series is about ordering every menu item at some of New York’s best (and kinda expensive) restaurants. This is a lifestyle that I’m not sure Delany himself can afford, given that he revealed his salary in the wake of the June blow-up and often talks about cooking cheap “rent week” meals. </p>
    <p>But Delany’s show is fun to watch because it lets us live vicariously for a little while. What’s insidious about the regular "how to cook" type episodes are the little side comments about which brand/ item is superior. Nothing that you, the home cook, makes could possibly be as good as what they whipped up in the Test Kitchen if only for the simple reason that you don’t have the exact brand of ingredients they do. There are some exceptions, like Sohla El-Waylly’s videos, which show us a variety of brilliant and resourceful ways to make our own versions of Sohla’s recipes. </p>
    <p>Claire Saffitz is so pretentious that I can barely make it through her videos any more. I do not want to read Dessert Person. I do not want to be called a Dessert Person. I do not want to make her terrible-looking corn bread or <a href="https://www.youtube.com/watch?v=xidcMKR8ikM">“tee hee shitty sprinkles!” birthday cake.</a> Do you know what I called those growing up? Sprinkles. Because all I had ever known were normal-people ingredients, before I was some ~self aware~ New Yorker who couldn’t eat a birthday cake without giggling about how ironic it is. </p>
    <h4>They Hate the Way We Talk</h4>
    <p>There’s a lot of uncommon, and frankly, annoying vocabulary in Bon Appetit videos. “Jammy.” “Pullman loaf.” “Maillard reaction.” Brad Leone’s entire on-screen persona is that he’s the rough-around-the-edges outsider from rural New Jersey who can’t pronounce “water” and doesn’t know how to plan ahead. The running joke is that Brad is stupid. The rest of the Test Kitchen shits on him constantly, and I can’t tell if he’s in on the joke. The parasocial dynamic is, as always, confusing. Did you laugh when Adam Rapoport implied Brad wasn’t funny on camera? Do you laugh when he makes fun of Molly for not having attended culinary school? If you don’t — you are the joke. You are Brad and Molly. </p>
    <h4>But Aren't the Experts Allowed to be Pretentious?</h4>
    <p>I respect that the Test Kitchen staff is a highly-skilled, educated set of professionals. They certainly know more about cooking than most of us, and they do have the right to use the correct vocabulary and have opinions about the quality of their ingredients. My problem really is that, a lot of the time, the pretentiousness feels like elitism for elitism’s sake rather than as the natural result of somebody perfecting their craft. They’re putting on a show for us, but drawing us in like we’re good friends with them, while showboating how much better they are than us. Nobody could possibly follow along with these recipes — they’re too fast-paced and disjointed to be instructional. They do reveal some secrets of good cooking. But I don’t think Bon Appetit cares how good we are at cooking. </p>
     <p>Is it cool when Joshua Weissman makes some totally unnecessary food from scratch using super expensive equipment? Is it cool the Nth time? Or do you start to realize what he’s actually saying about the food you eat and the way you eat it?</p>
     <h4> A Few Years Later </h4>
     <p>BA never fully recovered from June 2020. I don't watch much cooking YouTube any more, because over time it has gotten even more overproduced and parasocial. In my own kitchen, I try to focus on recipes that I can actually make from minimally processed ingredients. Minimally processed <i>sometimes</i> implies expensive, but it definitely doesn't imply that we have to be mean about it.</p>
</p>
</div>

<br />

<div>
  <h3 id="14122020-symbolic"> 14 December 2020: Notes on Symbolic Execution </h3>
  <p>This is a first pass at understanding a few papers I’m reading about symbolic execution and its applications. I’m not an expert at this area of security. </p> 

  <h4>Fuzzing</h4>
  
  <ul>
      <li>Software has bugs that can be hard to predict or find </li>
      <li>One technique for discovering bugs is fuzz testing. Fuzzing uses arbitrary inputs to discover the conditions under which a program may crash or behave unexpectedly due to the inputs provided. Fuzzing discovers the ways users may accidentally crash a program by providing input that wasn’t considered or handled in the code. But it also can discover inputs that attackers can use to compromise a program. </li>
      <li>Fuzz testing, especially automated fuzz testing, is a good start. But it’s impossible to test every possible input of every type. A way to fuzz test more quickly is using equivalence classes, which assumes that inputs of the same type (e.g. ints, doubles, strings, edge cases) will behave similarly. No need to test every int if you can test a few expected cases, and maybe some extremes such as 0, 1, -1, maxint, minint.</li> 
      <li>Both fuzzing and fuzzing with equivalence classes are approximations since they do not cover all possible cases. More importantly, they do not guarantee that all possible paths of execution are covered in testing.</li>
  </ul> 

  <h4> Code Coverage & Exponential Blowup </h4>

  <p> It’s hard to trace every possible path in a program. Branching creates exponential blowup of paths. Static analysis tools can warn you of this problem, and code coverage tooling can tell you how much of your source code is executed during testing, but developers do not necessarily test every path through their code as it would be too expensive. Analogously, Mayhem (Cha et al.) checks paths through assembly code via symbolic execution. </p>

  <h4> Bugs -> Exploits </h4>

  <p>While testing execution paths is important to finding bugs, it is also important to finding exploitable vulnerabilities in code. </p>
  <p>The central question about a piece of software w/r/t finding exploits is: is there a set of inputs that, given the structure of this program, execute an exploit?</p>

  <h4> Conditional Jumps </h4>

  <ul>
    <li>Note that the execution paths are both how we get to the exploitable instruction and the exploitable instruction itself. What I mean by that is that we’re not talking about “Which paths take me to a line of insecure code?” but rather, “Which paths lead to a conditional jump whose jump address can be injected by an attacker?” We’re not just searching the codebase for a badly formed line or two of code — that’s what static analysis does. In the context of the Mayhem paper (Cha et al.), we’re searching the paths through the codebase to figure out which paths lead to a symbolic memory address.</li>
    <li>Some examples of these conditional jump-like library calls include variadic functions (like string formatters) and switch statements. (Cha et al.)</li>
    <li>Conditional jumps are dangerous because the address of their next instruction is dependent on the state of the program, including user inputs. </li>
    <li>Buffer overflow -> pointer overwrite is also a huge vulnerability. If an attacker can inject a memory address into a pointer, the program executes attacker code (either at a jump to register or direct memory location). (Cha et al.)</li>
  </ul>

<h4> Symbolic Execution </h4>

<ul>
    <li>Symbolic means it needs to be evaluated to obtain a value (e.g. x + 3) </li>
    <li>Symbolic execution is a way to explore the paths of execution through a program without using concrete inputs. Symbolic execution models the program into a tree of statements, logical expressions, and variable values. (Baldoni et al.) </li>
    <li>There’s a good example of this on page 3 of (Baldoni et al.).</li>
    <li>Once this tree is generated, a model checker (similar to an SMT solver) can identify which paths satisfy or do not satisfy certain conditions. (Baldoni et al.)</li>
    <li>In other words, if you find a path that leads to an exploitable memcmp(), your checker can tell you which inputs and path conditions are required to reach that exploitable instruction. </li>
</ul>

<h4> How this fits into my view of security </h4>
<ul>
    <li>There are security considerations at all levels, from hardware to application. Tainted instruction pointers are a bit deeper in the stack than I’m used to thinking about.</li>
    <li>Injection in general is a really big class of vulnerability, encompassing the vulnerabilities described in Cha et al. but also including SQL injection and XSS. </li>
    <li>Injection attacks are different from some other types of attacks such as password cracking and credential stuffing. I'm used to thinking about attacks that successfully authenticate the attacker can use entitlements of an existing account to attack in a more legitimate-looking way. How can you tell the difference between a request sent by User1-the-human-being vs. User1-the-bot-that-guessed-a-weak-password? Unless you are monitoring behavioral patterns such as time of logon and logon source IP, you wouldn’t be able to tell the difference. </li>
    </ul>

<h4> Sources </h4>
<p>
    <ol>
        <li>Cha, Sang Kil, Thanassis Avgerinos, Alexandre Rebert, and David Brumley. "Unleashing Mayhem on Binary Code." 2012 IEEE Symposium on Security and Privacy (2012). Print.</li>
        <li>Baldoni, Roberto, Emilio Coppa, Daniele Cono D’Elia, Camil Demetrescu, and Irene Finocchi. "A Survey of Symbolic Execution Techniques." ACM Computing Surveys 51.3 (2018): 1-39. Print.</li>
       </ol>
</p>


</div>

<br/>

<div>

  <h3 id="29112020-sowh"> 29 November 2020: "Strong Opinions, Weakly Held" </h3>
  <h4>"There are no atheists"</h4>
  <p>I think a lot of prevailing ideas in the tech world lack a certain self-awareness as to the source of their legitimacy. People in technology love to pretend that they worship nothing and analyze everything. Some groups take this to its logical extreme -- like flat organizations with no managers or companies that operate on near-100% transparency, giving open access to docs, discussions, etc. But I believe <a href="https://www.goodreads.com/quotes/100888-because-here-s-something-else-that-s-weird-but-true-in-the">we all worship something</a>, even if it's at the altar of meritocracy. Look at any company's mission statement; those are commandments, even if they explicitly proclaim not to be. </p>

  <p>A rare gem in the technology zeitgeist that evades this contradiction is the phrase, "Strong Opinions, Weakly Held." (Hereafter referred to as "SOWH".) I see this in core values webpages and job postings all the time. As if to say, "Please have some well-reasoned, carefully-constructed opinions -- but be amenable to other people's well-reasoned and carefully-constructed opinions." I think it's a great philosophy in general -- and in job search terms, it's kind of an unwritten equivalent to soliciting a writing sample or requiring an SAT essay score (in the spirit of, "We don't care what you wrote about, just show us that you can reason and communicate.") </p>

  <p>It's a self-aware statement. It acknowledges that, as well-constructed as your opinion may be, other people will also have well-constructed opinions. You will have to sacrifice your own ideas for the good of the group sometimes, and that's okay. More importantly, the statement acknowledges its own sense of worship ("strong opinions") but offers a healthy way to work around the fact that we all worship something ("weakly held".) </p>

  <h4>No False Dichotomies</h4>

  <p>There's some emotional intelligence to SOWH -- it balances decisiveness with fairness, and leaves room for multiple correct but opposing opinions. </p>

  <p>When we think about how to solve the problem that <i>everyone has an opinion</i>, there are a few options:</p>

  <p>
   <ol>
     <li>Let everyone make a choice in equal measure, round-robin style</li>
     <li>Let nobody make a choice except the appointed leader</li>
     <li>Consensus after analysis</li>
   </ol>
 </p>

 <p>Clearly options #1 and #2 could be disastrous -- a software team would end up with completely disjointed services that simply do not work together resulting from #1 and unified services that work poorly resulting from #2. </p>

 <p>#3 is how most teams do it. But #3 can have some unintended pitfalls: a) The loudest/ most PowerPoint-savvy teammate is the most persuasive -- even if the idea is bad, b) Multiple ideas are good ideas, but a false dichotomy is forced between the "good idea" and the "bad idea" among multiple good ideas, or c) Teammates start putting less effort into decision making because they dislike conflict and/or wasted effort of developing an idea that goes nowhere. </p>

 <p>SOWH is a good tool to ameliorate these dysfunctional dynamics. "Strong Opinions" means the ideas have been researched, tested, and thought-through. Someone with a strong opinion has (hopefully) done sufficient work to recognize when a bad idea is presented beautifully. They also feel like their strong opinion is adding value to the discussion -- even when it isn't actioned -- because it matters to the decision-making process. <b>And most importantly, it leaves room for multiple good ideas, with the implicit acknowledgment that not every good idea can come to fruition.</b> </p>

 <p>Sometimes an idea is good, but it's not good for the product. It may be too complex or time-consuming for what it's worth. But it at the very least gets discussed at the table and filed away in the "good alternatives we used to narrow down our decision" category. For some people, I would imagine, this is incentive enough to the mental work to form a strong opinion even when they can't hold it as strongly as they wish.</p>

 <h4>Software vs. Real Life</h4>

 <p>In my life, I like to hear people's strong opinions. My friends and family certainly have some interesting strong opinions, but some people hold those opinions more weakly than others. When I'm working through a particularly tough problem, both types of people are helpful for me to talk to. The intuitive thinkers, who hold their opinions very strongly, encourage me to trust my own instincts. The curious thinkers validate my ways of thinking and helpfully suggest other ways of looking at the world without forcing an opinion. </p>

 <p> But when you work in software, there's a balance. </p>

 <p>In software, I believe in SOWH, As Long As We're All Rowing The Boat In The Same Direction. </p> 

 <p>I've had the experience of working with some incredibly knowledgeable and open-minded people, but when it comes time to make a decision, I think their (very insightful) opinions are a little too weakly held. I often seek wisdom but come back with validation of my own ideas, making me feel great about myself but confused about where to go next. When I bring an idea to a table of brilliant peers, I want their feedback. I want them to tell me how they would do it, or at least why my idea is good/bad and what the alternatives are. And I especially want them to enforce some decisions across the team. Every team needs standards (a direction in which to row the boat). Even if those standards aren't the best idea or the most agreeable idea, SOWH would probably argue that any decision is better than no decision. (If you couldn't tell, I do not worship at the alter of Flat Organizations). </p>

 <p>Fairness and decisiveness can be reconciled, if SOWH is used correctly. A good leader discusses all the Strong Opinions, validating their merit and helping the group reason through them. A great leader drives the discussion to a conclusion, choosing the Strong Opinion that's the best fit for the product, team and company. And in a culture of SO<b>WH</b>, the owners of the losing ideas will know how to concede and go in the direction of the rest of the team. </p>

 <h4>Wrapping Up</h4>
 <p>In general, I think SOWH is much more subtle and intelligent than it necessarily gets credit for -- it derives its legitimacy from the very thing it cautions us all not to believe in too strongly. In my own SOWH, that makes it even more compelling. But on a less abstract level, SOWH is a great way to make sure your team is having thoughtful discussions that respect everyone's opinion without bending to the compulsive need for directionless fairness. SOWH from the individual indicates careful reasoning; SOWH from the organization indicates respect and an ability (but not necessarily a mandate -- that's still up to the people involved!) to make decisions for the good of the product. </p>
</div>

<br/>

<div>

  <h3 id="15082020-interviewing">15 August 2020: Tech Interviewing is a Life Skill </h3>
  <p>My main point here is that the things that make us good at interviewing are generally things we can learn over time as they are based in critical thinking about, and pattern recognition of, math and science. And while they are not bestowed upon us at birth, they do take many years to develop and therefore some people are in a(n) (dis)advantaged position based on factors largely out of their control. </p>

  <h4> Part I: When You're Surrounded By Perfect Candidates, But You're Not One Of Them </h4>
  <p>I went to college with a lot of really smart people, and I live on planet Earth which has a large pool of really smart people. In general, on Earth, I feel pretty smart. In college I felt like the dumbest one there. Of course when you're in this type of environment, where everyone was their high school valedictorian with high SAT scores and a million extracurriculars, you're no longer going to be #1. But I felt dumb in a new way that I didn't even fully process until after I graduated. I felt dumb not because I was no longer the top of my class, but because only certain types of "smart" really appeared "smart" in a pool of CS students. The types of smart that led to good grades and awards and prestigious internships were the types built up over many years, from early childhood, that compounded lessons from areas outside the standard school curriculum with reasoning and pattern recognition skills that kids pick up quickly when taught by a very educated adult. </p>

  <p>These hyper-intelligent, worldly, majestically-educated students had been doing math for fun since middle school and programming before I ever knew what programming was. But we both got into $Competitive_School and they weren't any smarter than I was. They were just more educated before we arrived as freshmen. </p>

  <p> And it turns out that being hyper-intelligent, worldly, and majestically-educated makes you really, really good at the technical interviews which gatekeep the tech world's most sought-after companies (like the FAANGs). For someone who has been doing math as a practice (and not just in a public school course) for many years, whiteboard questions about graph theory are (I would guess) an exercise of their long-held talents that they can display with some effort. For someone like me, those questions are a nightmare. Data Structures was hard. Discrete Math/ Graph Theory was hard. I'm not good enough at those subjects, nor did I really practice them enough over the course of a semester, to be able to flex that knowledge like it's a muscle. Because while other students were following along with the lectures, I was still years behind on the math and reasoning skills that underlie those subjects. </p>

  <p> So for a very long time now, I have felt like I existed in a world full of extremely well-qualified candidates who could do backflips around me in a whiteboard interview, and I'm starting to understand the reasons why.</p>


  <h4> Part II: Pattern Recognition </h4>
  <p> Whether the interview question is a one-liner about technology X vs. Y, or an infamously fun brain teaser, the most helpful skill will be recognizing a pattern that you've seen before. </p>

  <p> A lot of problems in computer science involve lines of thinking that can be applied to a family of problems. One you understand recursion, you can apply it to a lot of things. Once you understand applying recursion to the Fibonacci problem, you can speak about the limits of it as a tool and alternatives such as memoization. And once you can do that, you can see other problems that would have similar limitations and apply the same thinking. Is it recursive, does it use the result of smaller recursive calls to get bigger answers, and is it exponentially expensive to re-compute every recursive call as n -> inf? Memoization. It seems really counterintuitive at first to memorize the properties of seemingly random problems in computer science, but the payoff comes when you start to see that a lot of these problems are a stand-in for a generic area of CS, and once you learn the concept, your brain will connect the rest of the dots. I wish somebody had told me that before I took Data Structures. </p>

  <h4> Part III: Critical Thinking </h4>
  <p> Another important aspect of being good at technical interviews is being good at reasoning about the problem. It may not always be the case that the question being asked of you is familiar, but it probably has some familiar pieces, and with some reasoning, you can find an answer. 

<p>Critical thinking serves two roles here: </p>

<ol>
    <li> To build an understanding of the foundational patterns/ problems that will be useful later on. This is how those cornerstone problems in CS (such as Fibonacci, O() complexity of algorithms, various problems in graph theory, synchronization mechanisms, et. al.) enter your brain and stay there for future reference. If you really learn these problems thoroughly, they will stick with you and come in handy later. But you have to be able to reason about them and really understand them for that to happen. </li>
    <li> To do the "twisting and turning" of what you already know and understand in order to arrive at the solution. This is the part where the professor solves the problem, and you ask them why, and they pull out a bunch of random theorems from other parts of math that show how they are correct. You would have never gotten there on your own, likely because you either never saw those patterns/ problems before, or because you didn't realize you could apply them to this particular problem. </li>
</ol>


<p>I think the second type of reasoning comes with a lot of practice in the same way that being good at math comes with practice. Sending me through my public school math and then asking me to reason about a math problem in college is like giving someone a lesson on walking in a straight line and then telling them the final exam requires ballroom dancing and a backflip. Sure, I understand most of the mechanics, but I never knew I would have to twist my brain into thinking about the material in that way; I just now learned it could even be done. But with a lot of practice and the help of various problems/ patterns, I've seen myself grow tremendously in this area and it's been really fulfilling to see.</p>

<h4> Part IV: You (Maybe) Learned This As A Kid </h4>
<p> You probably didn't learn all of Data Structures & Algorithms in K-12, but I wouldn't bet money on that based on the people I met in college CS. Still, you may have learned valuable math, logic, or debate skills that come in handy later on in life. I think this is probably especially true of anyone who was really into math programs, but it could also be true of students in certain other extracurriculars. It certainly could be true of more students if their curriculum was redesigned. </p> 

<p> This is definitely a much larger topic than I can cover right now, but I don't like the way math was taught to me as a kid. It was unbearably slow, taught completely by rote, and peppered with random topics that made no sense in the context of when they were taught. I actually had a very good education when it came to verbal skills. I believe that has gotten me very, very far as an adult and I am so grateful for the literacy programs my public school had. But when I think back on it, were these not pretty similar to the math lessons? Sure, some of my teachers had a bias for reading over other subjects, but I don't know if that's the whole story. Reading/ literacy is a skill I learned by long and daunting practice, often employing rote mechanics. I would read for long stretches of time in and out of the classroom, participate in summer reading programs at the library, and write stories for fun. In school we would have quiet reading hour, we would get independent time to read from a special box of stories and test our learning after with a self-administered quiz, and we would get lessons on things like homophones. All pretty rote and autonomous activities for a 7 year old child. Yet these lessons propelled me forward for the rest of my life, and even 10+ years later when I took the SAT, my verbal skills were better than my math skills. I believe these skills made me a better note-taker and a better learner in the lecture/classroom/textbook/essay environment. In contrast, we didn't spend so much time on math. Sure, we had lessons on the chalkboard about how to do arithmetic, we talked about different ways to do the arithmetic and a bit of the underlying math, and we practiced with worksheets in-class. But it wasn't as engaging, it didn't feel as important, and for me, it was so boring. The only rewarding thing about doing math in school was memorizing the steps and getting an A on the test. Engaging with reading and writing felt so natural, and math felt so foreign. There's always the possibility that my brain is just wired for verbal skills more than non-verbal, but I do wonder if I had the parallel experience but with math if I would be one of those Perfect Technical Interview Candidates by now. </p>

<p> And sure, a lot of that last paragraph I just wrote could be brushed off as entirely anecdotal and biased toward my own worldview. Maybe I really was just born with a reading brain and I got lucky because my early education was taught by reading teachers. I'm also pretty good at languages, for what that says about me. But there's some evidence here that might back me up: <a href="https://www.theatlantic.com/ideas/archive/2019/06/phonics-not-whole-word-best-teaching-reading/591127/"> John McWhorter says </a> that learning to read by phonics proves the most effective for students of all backgrounds, which is especially good news for children of lower income households who might not have the huge library at home that could support them in other types of self-directed learning that some school districts try out. That's not to say that other types of reading education don't work, but that phonics works pretty well for the general population when there are not other resources available. Phonics works in a pretty mechanical and rote way: you just sound out the letters and build up words. Phonics is what worked for me. It's how my dad taught me to say "cat" with fridge magnets (thanks dad!), and I should really call him to tell him he nailed it. It's still how I engage with language, how I have always been pretty good at spelling, how I pick up new languages fast, how I am (sort of) trying to get the basics of Hebrew down. So I do believe there is something about repetition and practice that builds up verbal skills in your brain. First and second grade were like verbal skills boot camp for me, and I attribute a lot of my abilities to that. </p>

<p> But I don't think math works that way. I had a rote and mechanical math education, and it was bad. Because my teachers took similar approaches to reading (where, I think, rote works!) and math, I learned how to do things like memorize how to multiply and divide on paper. And while we didn't spend nearly as much time in those early elementary years doing math as we did reading, we did learn these subjects in similar ways, by watching the teacher do it on the board and then repeating the mechanical steps on a worksheet. We would occasionally try something new, like using blocks to understand counting. But the reasoning required to really understand math just never arose from these activities. Math requires an entirely different way of learning, involving pattern recognition and those "twisting and turning" reasoning skills that pass tech interviews. If you don't believe me, pick up a copy of The Art of Problem Solving. </p>

<h4> Part V: The Social Aspect </h4>
<p>So the last thing I’ll say about a technical interview is that you (usually) also need to be likable and good at communicating. These are also skills you build up over time, but in a different way. You have to be able to explain your thinking and build rapport with your interviewer. It also helps to have a bit of humor and warmness to you, so you don’t look like a robot whose sole purpose is passing a technical interview. This is also for you to be able to gauge the person interviewing you — are they a robot? Are they going to treat you like a human? Can they have some humor and warmness? These are important things to look out for, because it’s really difficult to judge your potential new coworkers as coworkers in the power dynamic that an interview creates. </p>

<p> A lot more can be said for other skills that do not shine through in a technical interview. I think a lot of the ways in which I am really smart are hidden by tech interviews, just like they were hidden in college. I'm still a good software engineer, and I am learning these technical interview skills as I go along. Interviewers should certainly be looking for other cues as to candidates' abilities: problem solving, collaboration, communication to name a few. So hopefully a technical interview is just one piece of the puzzle, and the other pieces are what really will make up the bigger picture in the way of matching a candidate to a position. I know I certainly wouldn't work for a company that didn't make an effort to assess me on other qualities, because I don't want to work with colleagues who were hired solely for their ability to ace the whiteboard. </p>

  </div>

  <br/>

  <div>

<h3 id="04082020-nosql"> 4 Aug 2020: Notes on NoSQL Databases </h3>
<p> Notes from watching <a href="https://www.youtube.com/watch?v=qI_g07C_Q5I"> Introduction to NoSQL, Martin Fowler </a>

<p> Problem: Object-relational impedance mismatch (Things are logically organized into objects in code, but those objects have to be split up and stored into tables and mapped by schema.) Hence ORMs. </p>

<p> SQL is designed to run on large servers, not large grids of small hardware which became dominant as large internet companies grew in the 2000s. </p>

<p> Thus Bigtable & Dynamo </p>

<p> NoSQL is hard to define, but it's generally non-relational, cluster-friendly, schema-less, open source. </p>

<p> There are four general categories of NoSQL: </p>
<ol>
    <li> Column-family. Examples: Bigtable  </li>
    <li> Graph. (Node and edge graph model. Good at moving across relationships between things (wherease in relational, you need foreign keys, joins.) Interesting query language for navigating graphs. )Examples: Neo4j </li>
    <li> Document (Typically stored as JSON. You can query into the document structure. An attribute is kind of like a key...) Examples: MongoDB, Dynamo</li>
    <li> Key-value (Like a persistent hashmap. You can usually store metadata about the records, though, so this becomes more like a document database.). Examples: </li>
</ol>

<p> Martin Fowler calls Document, Key-Value and Column-family "Aggregate-Oriented" databases. </p>

<p> Though NoSQL is schema-less, there is an implicit schema in NoSQL dbs that becomes clear when you start querying! For example, querying MongoDB for a particular JSON attribute. </p>

<p> Big advantage of aggregate-oriented is that you can store multiple pieces of information together in a single record, whereas in a relational db, you would need to have two tables and map one row from a table to multiple rows of another table in order to associate the information correctly. </p>

<p> Aggregation makes clustering easy because you know what will need to be stored close together. </p> 

<p> Column-family is also aggregate-oriented. </p>

<p> Aggregation has a drawback: really difficult to slice and dice your data after you've decided on the aggregation. </p>

<p> So how do the different NoSQL models handle relationships? Aggregate-oriented databases are similar to relational dbs, in that you have to associate by attributes or values in the data. Graph databases are oriented toward relationships since they are node-edge models. This is good guide for deciding which db to use. </p>

<p> Consistency in NoSQL: SQL=ACID, NoSQL=BASE. But Martin Fowler isn't a fan of this. Graph db's are ACID. Aggregate-oriented databases don't need ACID quite as much. Aggregations are transaction boundaries! So you shouldn't really need to lock more than one aggregation at a time. If you update multiple documents at a time in document dbs, then you need additional atomicity.</p>

<p> In general, transactions are achieved by letting a user retrieve a versioned record, updating that versioned record, and sending it back. Then when two users have written at the same time to their own copy of the version, you can do whatever conflict resolution you need to. </p>

<p> Logical consistency vs. replication consistency </p>

<p> What if two nodes lose communication with each other? Do you allow both to modify the same object, or neither? This is a tradeoff between consistency and availability. Dynamo needed to guarantee availability in the shopping cart for Amazon. </p>

<p> CAP Theorem: Consistency, Availability, PartitionTolerance. Pick 2. (aka, if you get a network partition (communication failure between nodes), you can either have availability or consistency.) But this is on a spectrum, so it's not always just one or the other. Even if the network is up, you have a performance tradeoff if you want to be 100% consistent since it takes time to absolutely guarantee consistency across nodes. So it's a safety vs. liveness in concurrency issue. </p>

<p> So when to use a NoSQL database? Two drivers: 1. Large amounts of data that can't fit well into a relational database. 2. Natural aggregates, for example when publishing news stories that have metadata and content together. Another reason includes analytics, as an alternative to datawarehousing. </p> 

</div>

<br/>

<div>

<h3 id="03082020-do"> 3 Aug 2020: DigitalOcean Databases </h3>
<p> Just some notes as I try out DigitalOcean's database-as-a-service platform. </p>

<p> General observations: </p>
<ul>
    <li> Pricing is pretty up-front</li>
    <li> They give you a lot of nice little security hints -- allow/deny IPs, use 2FA, put your recovery codes in an encrypted file or pw manager, only showing OAuth token once ever </li>
    <li> Instantly I'm noticing a lack of integrations with any identity platform on the database (but this is a hard problem) </li>
    <li> I can see that the randomly generated database admin pw is pretty strong and can be rotated manually -- auto rotations maybe?</li>
</ul>

<p> What I'm doing: </p>
    <ol>
        <li> Created my DO account </li>
        <li> Created new Postgres 12 db </li>
        <li> Did some initial configs on it (IP allow listing) </li>
        <li> <i> brew install postgres </i> because my college MacBook, where I did all of my college db work, is asleep </li>
        <li> Connect to my new db from the psql client. Pretty smooth; basically what I would expect. </li>
        <li> Found a dataset on Kaggle in CSV format, created a table for it in the db, used \copy command in psql to copy the data in. Now I can query Netflix titles! </li>
        <li> Generated OAuth API Bearer Token and used it to list my database clusters via HTTPS request (note: not immediately clear to me here that I would need to list all clusters first, then get the cluster id, then get more specific details from it. Wish cluster id was available on UI.)</li>
    </ol>

<p> Questions: </p>
<ul>
    <li> What's this .crt file it generated for me? It says it relates to my specific project (unit of organization for DO resources). Is
it to allow my workstation to trust my project? So it's a server certificate? (Is this for machine-to-machine auth when you use other DO resources?)</li>
</ul>

</div>

<br/>

<div>

<h3 id="01082020-goals2"> 1 Aug 2020: Checking in on my 2020 goals </h3>
<p> Wow, it has been a while! As the COVID-19 pandemic completely took over life as we knew it in 2020, I was making sporadic progress on the goals I outlined above. I also have some more clarity on what I'm wanting looking into the future career-wise. So here's what I've been working on: </p>


<ul>
    <li> <b> Configuration management (probably Ansible): </b> A while back, I played around with Ansible on AWS as a way to spin up and configure some EC2 instances.  </li>
    <li> <b> Containers: </b> I did put some time into this one! I got Docker Desktop set up at home and just poked around for a bit with the Flask image and said "hello, world!" from Docker. I also tried out a security product that's distributed as a Docker image. I took a self-paced course on containers and I generally understand the basics now. I know why you'd use one over a VM, where to get images, what a Dockerfile is, how to spin up a container, how to map ports & storage, and how to set up a little environment with multiple containers that communicate with one another (network). Next on my list for this one is: orchestration/k8s. </li>
    <li> <b> (improve) Software design for testability: </b> Are we ever really done with this one? :) Again, nothing really specific here, but I haven't stopped writing tests!</li> 
    <li> <b> API design: </b> Nope. </li> 
    <li> <b> Functions-as-a-Service: (probably AWS Lambda) </b> I did play with this one! See blog posts above. But nothing groundbreaking. </li>
</ul> 

<p> So I guess I've been working on less than I thought?! But I have been busy. At work I have the typical workload (+, you know, the pandemic).</p> 

<p> I've also been working on brushing up on SQL and concurrency. I apparently remember a lot about spin locks and not a lot else (probably because I haven't done much of it outside of college OS class). </p>

  </div>

  <br/>

  <div>

<h3 id="01032020-lambdas"> 1 March 2020 Lambdas! </h3> 
<p> Today I was wandering around my little AWS playground and I was kind of bored by what I was doing (messing with flask and security groups) so I decided to see if I could get a Lambda up and running. Some days I love following tutorials and absorbing every word. Other days, I want to just break things and see how far I can get. Today was one of those days. </p>

<p> So what is a Lambda? It's a function-as-a-service. You give AWS some code to run and it figures out the rest for you. How's that different from running code on EC2 or in a container? Well, it's even easier. There's no infrastructure, OS, or even runtime to worry about. You give AWS the code -- literally the source code -- and it takes care of the rest. </p>

<p> Well you do have to give it a trigger. Otherwise it would just be code that AWS doesn't know when to run. </p> 

<p> Here are (roughly) the steps with commentary, for doing what I did today: </p>   
<ol>
    <li> In the AWS Console, open Lambdas and Create Function</li>
    <li> Author from scratch (it's more fun this way...?) </li>
    <li> Choose a runtime you like (Python here) </li>
    <li> Permissions: Create new with basic Lambda permissions </li>
    <li> Add trigger: API Gateway (trigger this function on an API call) </li> 
    <li> Create new REST API; Open with API Key </li> 
</ol>

<p> So at this point I ostensibly have my own API Gateway backed by a lambda function. But how do I use it? On the function's Configuration tab, there's a Designer diagram. Click the API Gateway icon. It will show some configurations, including the API endpoint. So open up a new tab and try it out! </p>

<p> Well, you'll find that it doesn't work. You get a nice little {"message":"Forbidden"} response from your own API because you set the authorizations to Open with API Key but you didn't provide a key! </p>

<p> Get the key from the AWS Console's API Gateway service and navigating to API Keys. The API Gateway page is also where you can disable API Keys or enable IAM authorizations for your APIs. </p>

<p> One way to provide the API key to the endpoint is in the headers as an x-api-key. You'll notice that <code> curl $ApiEndpoint </code> gives you back the same forbidden response, while <code> curl -i -H "x-api-key: $Key" $Endpoint </code> invokes your Lambda! </p>

<p> At this point your Lambda will execute the boilerplate Hello World python code that gets populated when you create a python Lambda but you can edit it to do whatever you want! </p>

  </div>

  <br/>

  <div>

<h3 id="27202020-tests"> 27 Feb 2020: On Writing Good Unit Tests </h3>
<p> I still remember the day I learned about automated testing. I was in my junior fall semester of college, taking a class about software engineering. All of my other classes up to that point had been very "CS"-y and not very, well, "practical." This particular class required a semester-long software engineering project with CI/CD, testing and (somewhat humorously) UML diagrams. A guest lecturer pulled my group to the side and asked us if we knew how to write a test. And thus the magic of Assert() was revealed to me. Today as a software engineer, I pride myself on the quality of my tests and the efficiency of my CI/CD pipeline. I don't consider a feature "done" unless there are tests. I will not tell you my code is "ready" if I didn't push the play button and wait for a versioned, tested executable to come out of the other end of the pipeline. I definitely think these are some of my strenghts as a software engineer but there are also some things that I'd still like to improve on in this area. </p> 

<p> It's kind of hard to definitively say what a "good" test is but there are some easy ways to identify bad ones. So we can start there. Bad things to do in tests: </p>
<ul>
    <li> Depend on other tests </li>
    <li> Depend on external factors that can change, such as databases or web services</li>
    <li> Only test the positive cases </li>
    <li> Stop writing tests after the initial development (if you find an edge case later, fix it and write a test!) </li> 
</ul>

<p> Here are my tips for good testing (but this is by no means comprehensive!): </p>
<ul>
    <li> Think about equivalence classes & consider some (reasonable) ones </li>
    <li> Fuzz it (aka throw absolute nonsense inputs at it). This one makes more sense if you have user-facing surfaces, but can be useful if you use a data source that could one day feed your program garbage. </li> 
    <li> Consider testing in your initial design (my current favorite framework for this is dependency injection) </li> 
    <li> Write a lot of small tests (hence the name "unit") but also consider some end-to-end tests to make sure your program executes in the way you think it does once it's all put together. I've caught some <b> nasty </b> bugs this way. </li> 
</ul> 

<p> Of course there are still things that mystify me about testing. Here are some of those things: </p>
<ul>
    <li> Exactly which methods should I unit test? Only the external-facing ones? All of them? Even the tiny little helper classes? I tend to try to test every method, but am I doing this wrong? </li> 
    <li> Should I have some integration tests? How would I even achieve that? (I guess this one is pretty project-specific, but I still wonder.) </li>
</ul>

<p> In my personal experience, comprehensive unit testing has saved me a lot of trouble. It's costly to do up-front and your non-developer coworkers might question why simple features tend to take you so long, but you will more than make up for the time when your program works well and you can identify bugs very quickly. I <i>love</i> my end-to-end tests and I would hate to try to "verify" that my program was working by crawling through application logs and hoping everything looked right. When in doubt, write a test! Your future self will thank you. </p> 
  </div>

  <br/>

  <div>

<h3 id="00002020-goals"> 5 Things I Want to Learn (or improve) in 2020 </h3>
<ul>g
    <li> Configuration management (probably Ansible) </li>
    <li> Containers </li>
    <li> (improve) Software design for testability </li> 
    <li> API design </li> 
    <li> Functions-as-a-Service (probably AWS Lambda) </li>
</ul> 
  </div>

</div>
