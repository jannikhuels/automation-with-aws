# Why the effort of automation?
Many people may immediately see the advantages automation of infrastructures brings with it. Is that true for you, than please skip this lab. You won't learn anything new. For all the others who read on: Do you really want to continue doing boring stuff ever and ever again?

Nevertheless the beauty of automation comes at certain costs. You have to gain an understanding in tools you use for your automation tasks and a basic knowledge of the many principles on how to deploy your infrastructure. Kief Morris' very great book ["Infrastructure as Code"](https://info.thoughtworks.com/Infrastructure-as-Code-Kief-Morris.html) is a must read if you want to start automating. Or even if you already do and think you have to improve. Treat your tasks of implementing your infrastructure as code and get the full advantages automation is able to deliver.

#### Avoid repeating tasks
In case you find yourself in the situation that you do tasks over and over again you should have had the idea to automate those. It's not easy to do? Then do it with greater effort. Honestly this sounds kind of aggressive. But in the majority of cases the effort you spend automating a task is worth it. Not only from a commercial point of view but also from a social one. Repeating tasks are boring. Even if they are not at the moment they will become in near future. The attention you spend on those tasks will decrease and you will make mistakes. Prevent yourself from making your infrastructure crash by letting a script work for you. Concentrate on making progress and not on repeating yourself over and over again.

#### Make the repository your head monopoly
"Who is capable of creating a new development server?" may your boss shout into the office. Only one person and she is on vacation? For 6 Month? In Honolulu having no internet connection? Waiting is not an option so you have to learn and try to setup the server. Wouldn't it be great if you have had everything documented and ready to go? This may be possible using scripts. Just upload them into your repository, document everything and never ever have one head monopoly again. In fact you do not lose knowledge even in case people leave your company. Furthermore we don't need to talk about the plenty advantages a central repository adds to teamwork.

#### Touch the snowflake
Who does not have it, those servers who seem to run since centuries and the fear to melt them like a frail snowflake every time you touch them? But if you had a script that is capable of immediately creating this server again your problem got lost. Or to stay with images: The server got a huge growler midst of the arctic unable to melt. Even in case you break it, it immediately gets reproduced. No time for fears any longer.

#### Stay consistent
There often exist different environments like development, bugfix, staging or production. Frequently with descending priority which may lead to inconsistent server configurations. In case there is those tiny bug in production which is very hard to find you need to test a lot and thus won't do it in production. But wait - how to ensure that the bugfix you made in any other environment also helps in production when configurations are inconsistent? Thus create scripts to avoid configuration glitches. And move beyond that. Try to convince people to implement immutable server. Don't change a running instance but rework your script and recreate the instance. This may not be suitable for your on-premises datacenter, but with AWS.

#### Gain speed
Once deployed in any environment using scripts the move to production is only a button-press away. Sometimes there is even no button-press needed. The principle of continuous integration is well-adopted in the software development area. Now you have scripts. This is the code that creates your infrastructure. You have automation for everything and thus <ou are only a snap with the fingers away from creating your own pipeline. Once a change is made and pushed to the repository the CI server of your choice immediately creates your development environment again with the latest changes. You can't work faster.

#### Increase reliability  
Let's stay with the pipeline idea. How to ensure that your environment works as expected? Test it. You have the skills to write scripts to create your environments then also use them to test them. Tests should be core of your infrastructure pipeline. This will bring the reliability up to the next level. And it allows you to expand your pipeline to span all environments. Even the production if you are really good.

#### Focus on your business
As soon as you have your pipeline ready you can concentrate on your business. Adding value is now much more convenient. You can concentrate on implementing changes that add value. All the annoying tasks are done by automation. Make your infrastructure facilitate agile project management. Get immediately feedback to new ideas since they are implement immediately. All fast and with little effort.

We do hope that we still have some readers who reached the end of this lab. We promise that this is the last lab without code. During the upcoming labs we try to work up all the advantages we mentioned above. To sum up we think automation improves **speed**, **reliability** and **efficiency** of your daily work. Automation is worth it. Join the next labs in order to see how we think automation should work with AWS.