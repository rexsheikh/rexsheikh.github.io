[Home](./index.md)|[Project Proposal](./projectPosts.md/) | [Download Resume](/rsheikh-resume.pdf/) 
## Post 1 (05.31.2025)
First, I spent some time familiarizing myself with the course structure and expectations which included watching the course origins video and learning about past projects. I was grateful to see past projects were indeed wide-ranging and seemed to be tailored toward student interest. I’ve never worked without at least some constraints, so I immediately found myself nearly lost in potential projects I might find interesting. I decided to set some parameters at this point to narrow the decision-making process. In rank order, here is the criteria I came up with:

1. **Interesting** – Making something tailored to my interests for credit is not only a unique opportunity but should make progress feel less like homework and more like genuine exploration.
2. **Feasible** – I won’t be solving cold fusion. Whatever I decide to make will need to be executable within (roughly) 40 hours of dedicated work. I should have a fair degree of confidence, based on prior projects and academic work, that I can reach a minimum viable product.
3. **Challenging** – If I expect to learn something, I should also expect to run into things I haven’t seen before. This clashes with (2), but I think I can find a balance.
4. **Extendable** – A project that can naturally support additions later on removes the pressure of doing everything this summer. A project that is inherently limited in scope might stifle momentum if I want to explore different aspects of a language, framework, or technology.

I’ve already made a good deal of progress this week with the above criteria. The specifics of eliminating potential projects to land on just a few candidates included a fair amount of research and unexciting details of which I’ll spare the reader. I had no problem thinking of interesting projects, but balancing the next three criteria was much harder.

I decided that I want to learn more about cloud-based services, specifically AWS. I have some experience with React, but my last foray did not instill confidence. Lastly, I wanted to integrate a physics engine for simple 2D games, and after some searching found Matter.js to be a prime candidate. A natural project, then, would be a game or suite of games that leveraged Matter.js to render game pieces while using popular AWS services like Cognito, S3, and Lambda for authentication, storage, and game logic respectively. I plan to learn more about these, decide which games to implement, and build a schedule that captures the project scope

__Are there any impediments in your way__

My impediments right now include a lack of familiarity with chosen technologies, frameworks, and libraries. I am stepping through React tutorials, familiarizing myself with the AWS console, and tinkering with some of the demo code for Matter.js. Also, I need to decide which games to pursue. Their logic should be straightforward and unambiguous. It’s not that these games are secondary, but I need to focus on core functionality rather than a brand new game whose logic is undefined. I’ve found defining that logic to be hugely consequential and nonintuitive in the past and I would like to avoid getting bogged down there. I am thinking of making clones of popular 2D mobile games or boardgames right now.

__Reflection on the process you used last week, how can you make the process work better__

The initial list of potential projects was quite long and I began to explore each one without method or reason. It was a frantic, unorganized combination of Google searches, notebook sketches, and other references. It had been several hours before I stopped myself to realize this was far from efficient. I have a tendency to do this, look at the nearest clock, and say “wow, I did not achieve nearly as much as I’d hoped today.” So, in terms of process I’m aiming to take a wider view of the problem and approach it methodically.

## Post 2 (06.05.2025)

Last week included refining my project scope to better define what exactly the minimum viable product will look like. This included some references to what I know about React and chosen AWS technologies to determine if I can confidently implement features efficiently. After, and as a part of the project proposal, I built a schedule.

This next week, I plan to move forward with that schedule by finalizing game logic and starting the React frontend and some basic tests using Matter.js. Also, I'd like to refine my project website to include some more background into the project's motivation.

I was pretty happy with my process this week. Splitting time between making a schedule, writing the project proposal, and reading references to not only learn about these new technologies but write a schedule I am confident with felt productive.

I don't have any impediments right now, although the volume of material to get through and learn feels daunting at the moment.

## Post 3 (06.12.2025)

Last weeek I started to build an understanding of Matter.js to implement some simple features while creating a rough scaffolding of the site. I focused on getting some early wins with a simple navigation bar in React and a simple penduluum demo to get a feel for how Matter.js renders objects to apply physical constants. The most difficult piece, though, was setting up React and learning how to create and consume components. The syntax is not straightforward to me and there are more curly braces than I care for. Still, it became very apparent to me why React is so popular. The investment upfront to build a good component does indeed make them highly reusable and easily configurable. I spent this week refining my understanding of React by completing some tutorials, notably a tic-tac-toe game that shows how to use state. I also did a great deal of research in AWS integration. I expect some difficulties integrating the frontend and backend and I've found time spent with familiarization saves time in implementation in these cases. 

My process was good this week, although I'm feeling a bit behind. Moving forward, I hope to increase the frequency between learning something and testing a simple implementation. The simple demos integrated with React proved that to me and it felt like my time was better spent there rather than reading docs and doing tutorials for a considerable amount of time. I have to remind myself that this software can break and proper version control via git offers rollbacks to safe points of progress. 

I don't have any significant impediments, but like I mentioned before, accelerating the learning to testing cycle frequency would more efficiently chip away at the volume of material I have to move through. 

## Post 4 (06.19.2025)
Last week I spent some time creating my personal website. I started with some research into Jekyll themes and made a simple nav bar to link to project posts, proposal, and landing page a short 'about me' section, highlights from my resume, and finally a link for a downloadable resume pdf. It was nice to see immediate results. I'm still doing a fair amount of learning before implementing in my project so having a vision and seeing it deployed was refreshing. I'd like to spend more time this weekend refining the site to add some project demo gifs and showcase some other work I have on github. Related to the project, I continud to build out components for demos. I have a good grasp of how different paramaters like elasticity and gravity affect objects. I've been pretty impressed with Matter.js overall. I'm still finding React to be less than intuitive with a great deal of time spent debugging for simple syntax errors. 

My progress was not quite where I wanted it to be this week. In addition to a weekly schedule, I need to start dedicating time deliberately to project development. Further, I think I need to get to a lower level of specificity within a weekly plan. I'm spending too much time to spin up, remember what I was doing, and begin productive work. I'm still on pace but I do feel that I'm eating up some buffer time earlier than I would like this summer. This weekend I hope to catch up with some AWS integration and get at least one game (pong) fully operational. That should give me good momentum going into next week. 

I don't have any significant impediments right now other than optimizing my time between work, school, and life in general. 

## Post 5 (06.26.2025)
Last week I ran into some tricky configuration issues mostly related to launching my react app with vite. Throughout the react tutorials, I was using 'create-react-app', a simple but somewhat outdated way to begin. I was familiar with the necessary setup and saw some unexpected issues when using vite. I decided to start a new react app with the setup I was familiar with and transfer components over. I was thankful to see everything was working properly. I started the project with vite because it seemed more amenable to later AWS integration. I'm planning to tackle that issue next week with AWS accounts ready to go. 

Another major change was deciding against using AWS Cognito for two reasons. First, I thought it would be more interesting to have an arcade style setup where users can play games then add their name to post their scores to see how they compare to others. It's much simpler and eliminates the need to authenticate users. Secondly, I found the workflow between AWS console and local development to a bit tedious in this case only to provide a feature that was likely far too robust for this project. I built some familiarity with the Cognito and I'm grateful for that but I just don't think it fits well with the overall project. 

I did manage to add a few features to the site this week. I adapted [this example](https://brm.io/matter-js/demo/#slingshot) from matter.js to make a simple free throw game. I added a sensor for the basket and a simple counter. It's pretty clumsy right now and very difficult to score but it works. This wasn't a game I originally set out to make but adapting from the javascript in the example to react was very doable. I spend some more time reviewing the examples on matter.js's github and saw some more potential adaptations. I stil want to implement the games I set out to but felt encouraged by this approach. I should be able to add more than I originally set out to. Next, I added some simple styling and navigation. There were still some syntax errors leftover from the first build and moving over components. 

Next week, I hope to add a few more games. I need to add timers and solidify scoring mechanisms. Next, I need to start integration with AWS S3. Once I have scoring mechanisms and timers in place, I can then ask a user for their name as they would like it to appear on the high scores page. 

My process was much better this week. One improvement would be to isolate styling and logic efforts. I had to switch back and forth this week just to see some results but I didn't set a clear stopping point. The resulting process was a bit inefficient. I find there are some switching costs between these two efforts.

## Post 6 (07.03.2025)
This week was again not as productive as I would have hoped but I did make some good progress in some key areas. I have a nearly finished free throw game. The upside is the components I built in React to make that game should be extensible to the pong game at least. I made some simple calls to an S3 bucket for proof of concept, too. 

Next, I hope to tackle the pool game and get a working scoreboard so users can post high scores as they are stored in S3. Again, this is now all arcade style so there is no login or authentication via email. I'm happy I made that change not only for time constraints but because it feels way more approachable to simply start playing. I definitely gained some familiarity with AWS Cognito and the AWS Console as a whole which is good. I hope to install and start using the AWS CLI this week for more programmatic testing before making a full effort for scoreboard display. 

I don't have any blockers currently and my process has been decent. I have a routine with time set aside for this project but I still feel a bit behind. I'm grateful to have chosen an interesting project as I expect to work some nights and weekends in the near future to catch up. 

## Post 7 (07.10.2025)
Last week, I decided to tackle some basic UI problems I have been putting off. Since starting this project, I have only implemented the most basic form of each game and webpage. I don't think I have a great sense of what will look good and what won't, so UI involves a lot of trial and error for me. I didn't touch any functional pieces of code, though, so I didn't experience any major breaking changes.

This week, I plan to finalize remaining game logic. This will allow me to focus on backend integration and more UI work (which never seems complete). From there, it will be a more of a refinement effort in tweaking parameters and display to make for good game experiences. 

I currently do not have any impediments in my way. 

My process was good last week and I think I will continue to draw a hard line between function and UI in the future. I sometimes find I try to do everything at once which is neither manageable or productive. It's natural for me to realize some functionality that should be integrated while working on UI or vice versa. My solution was just to keep a markdown file open to note anything to come back to it later. Some of these ideas I have on the fly require further thought, some are good, and some are bad. In any case, this approach deferred that thinking to a later time to allow me to focus on the task for this week. 