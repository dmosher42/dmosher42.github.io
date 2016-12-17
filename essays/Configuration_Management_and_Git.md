---
layout: essay
type: essay
title: Configuration Management and GitHub\: Do you "Git" it?
date: 2016-09-15
labels:
  - Open Source
  - GitHub
  - Git
  - Learning
---

“Configuration management” is a central software engineering skill. Without effective configuration management, it would be almost impossible for teams to build large and complex software systems and maintain them over time.
	
Git is currently the most popular technology for configuration management, and GitHub is currently the most popular cloud-based software hosting platform. Git and Github are very useful tools for configuration management and team collaboration. There have been several projects where I felt our team would have benefited from configuration management tools. One project I feel strongly about this was a quadcopter control program that we worked on. We were primarily writing our code for Arduino and sharing different versions via Dropbox or thumb drive. While this worked, it didn’t have version control. I still am confused which version of the code is the final version with all the finalized features and I’d be pretty hard pressed to investigate it now because everyone in the team has moved onto other projects. Had we used a version control system like Git, I would be able to see specifically who worked on what, what features were implemented and what version it was.

Github is most likely popular due to its reliability, convenience (No servers to set up, no ports to forward, no git server software to install, just make a new repo and you or your teammates can access it from anywhere with an internet connection), ease of use (Github provides a Git system that utilizes the an OS’s window and GUI instead of requiring the user to muck around with the terminal. This helps make it accessible to non-programmers) and the sense of community it provides.

One other Git hosting provider I’m familiar with is Bitbucket. The main difference between Bitbucket and GitHub is the business plan. Bitbucket charges by the number of users, with their free plan limited to only 5 read-write users (I believe other users can clone but not fork). The big difference is private repos: Bitbucket gives free users unlimited PRIVATE repos, while Github allows for unlimited PUBLIC repos. Private repos on Github are $7.00 a month. This may explain why Github appears to be more popular; it makes more sense for open source projects where the source is open to anyone who wants to use it. Bitbucket would be better suited for closed source software being made by companies who don’t want random people seeing or making changes to the code. These company projects’ development is usually handled by a few people behind closed doors. This may be reenforced in how the two handle users: Github just says who has contributed what while Bitbucket has a tighter group system that allows you to specifically control who has access to your repo. The main private code in GitHub is your local repo.
