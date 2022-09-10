# 🦄 Rocket Chat for Virtual Conferences 
Hello, there! This repo is dedicated for final work report submission for the Google Summer of Code - 2022. And would give a brief overview of all the PRs, issues and also the various featured implemented during this season.

## More about Rocket Chat for Virtual Conferences [RC4Conferences] 😮
An open source scaled virtual conferences creation, management, and operation system. It aims to enable online communities to easily run and host virtual events of any size. Built over contemporary ReactJS components with full stack behaviors, powered by NextJS. This project leverages FOSS Asia's excellent open source Event-yay server backend for conference creation and management. For day of conference operations, this project leverage open source Jitsi video's broadcast capability to an RTMP-forest for scaled consumption while embedded Rocket.Chat enables attendees and speakers to mingle and collaborate freely – with full persistent chat history.

### Links to the deployed demo website
1. [HomePage](https://conf.rceng.shop)
2. [Demo Day Event](https://conf.rceng.shop/conferences/c/1)

### Pull Reuqests
<div align="center">

| #  | PR short description | Is merged? |
| :-------------: | ------------- | :---------: |
| [#8](https://github.com/RocketChat/RC4Conferences/pull/8)   | Create and Implement the Components for Event Authentication window, and the Event HomePage  | ✅ |
| [#10](https://github.com/RocketChat/RC4Conferences/pull/10)   | Develop the Component which implements the Event Creation feature  | ✅ |
| [#13](https://github.com/RocketChat/RC4Conferences/pull/13)   | Develop the brand new Event Poster Page and then break down it to many components to make it customisable  | ✅ |
| [#15](https://github.com/RocketChat/RC4Conferences/pull/15)   |  Modify the Strapi CMS codebase to link the top navbar items to the event demo component pages | ✅ |
| [#18](https://github.com/RocketChat/RC4Conferences/pull/18)   | Tidy up the not required components since they were not relevant in this project | ✅ |
| [#20](https://github.com/RocketChat/RC4Conferences/pull/20)   | Develop a SSO for Dockerized Open Event Server and integrate the project with Superprofile - FaunaDB | ✅ |
| [#26](https://github.com/RocketChat/RC4Conferences/pull/26)   | Develop the components for Admin Dashboard which includes features viz. addition of Speaker, deletion of Events & Event Speakers  | ✅ |
| [#27](https://github.com/RocketChat/RC4Conferences/pull/27)   | Tidy up the repository by removing the unrelated GitHub components | ✅ |
| [#28](https://github.com/RocketChat/RC4Conferences/pull/28)   | Implement the Superpofile data intialization logic at start up time using faunadb npm package  | ✅ |
| [#29](https://github.com/RocketChat/RC4Conferences/pull/29)   | Improve the Superprofile data init using fauna development Docker environment  | ✅ |
| [#30](https://github.com/RocketChat/RC4Conferences/pull/30)   | Revert back the PR number #28  | ✅ |
| [#31](https://github.com/RocketChat/RC4Conferences/pull/31)   | Update the docs to add more info about starting the Docker containers and setting up the project  | ✅ |
| [#32](https://github.com/RocketChat/RC4Conferences/pull/32)   | Remove the hardcoded localhost URIs  | ✅ |
| [#33](https://github.com/RocketChat/RC4Conferences/pull/33)   | Publish a unix script to automate the Superprofile development environment init within a single script | ✅ |
| [#34](https://github.com/RocketChat/RC4Conferences/pull/34)   | Improve and refactor the Superprofile init script | ✅ |
| [#35](https://github.com/RocketChat/RC4Conferences/pull/35)   | Develop the Greenroom and Mainstage components and integrate them into the page for handling the Day of Event | ✅ |
| [#36](https://github.com/RocketChat/RC4Conferences/pull/36)   | Fix the backend environment init script  | ✅ |
| [#37](https://github.com/RocketChat/RC4Conferences/pull/37)   | Add support for starting the NextJS and Strapi over different ports instead of the default ones  | ✅ |
| [#38](https://github.com/RocketChat/RC4Conferences/pull/38)   | Publish an script to handle closing the dev environment gracefully, and cleanup all the running processes, and fix the docker error loops | ✅ |
| [#41](https://github.com/RocketChat/RC4Conferences/pull/41)   | Add data init script and functions to initialize the Open Event Server with some dummy event data  | ✅ |
| [#43](https://github.com/RocketChat/RC4Conferences/pull/43)   | Add Google OAuth in place of the legacy RocketChat OAuth  | ✅ |
| | | | 

</div>

<div align="center">

| #  | PR short description | Is merged? |
| :-------------: | ------------- | :---------: |
| [#44](https://github.com/RocketChat/RC4Conferences/pull/44)   | Add Youtube Iconbutton in the session | 🕛 |
| [#4](https://github.com/RocketChat/RC4Conferences/pull/4)   | Implement the required base work for developing the project as an npm package | ⛔ |
| [#3](https://github.com/RocketChat/RC4Conferences/pull/3)   | Implement the required base work for developing the project as an Git Submodule | ⛔ |
| [#44](https://github.com/RocketChat/RC4Conferences/pull/44)   | Add Youtube Iconbutton in the session | ⛔ |
| | | | 



</div>

### Issues
<div align="center">

| #  | Issue short description | Is it accomplished? |
| :-------------: | ------------- | :---------: |
| [#2](https://github.com/RocketChat/RC4Conferences/issues/2)   | Add the Event Authorization component | ✅ |
| [#7](https://github.com/RocketChat/RC4Conferences/issues/7)   | Modify the Event poster display page for Demo Day 2022 | ✅ |
| [#9](https://github.com/RocketChat/RC4Conferences/issues/9)   | Add components to help create Events | ✅ |
| [#11](https://github.com/RocketChat/RC4Conferences/issues/11)   | Improve the Authorization(Sign up) form page | ✅ |
| [#12](https://github.com/RocketChat/RC4Conferences/issues/12)   | Revamp the Mainstage and Greenroom page components | ✅ |
| [#16](https://github.com/RocketChat/RC4Conferences/issues/16)   | Add support for Superprofile different Event Access Roles | ✅ |
| [#21](https://github.com/RocketChat/RC4Conferences/issues/21)   | Add the functions for initializing the Open Event Server with some data programmatically | ✅ |
| [#22](https://github.com/RocketChat/RC4Conferences/issues/23)   | Update docs to include info about starting the Open Event Server | ✅ |
| [#25](https://github.com/RocketChat/RC4Conferences/issues/25)   | Add local FaunaDB Dockerized environment for smooth development experience | ✅ |
| [#39](https://github.com/RocketChat/RC4Conferences/issues/39)   | Improve the development environment start script | ✅ |
| [#40](https://github.com/RocketChat/RC4Conferences/issues/40)   | Make the Day of Event Pages Responsive for different screens | ✅ |
| [#42](https://github.com/RocketChat/RC4Conferences/issues/42)   | Replace existing auth components with Google OAuth, GitHub OAuth | Partially accomplished |
| | | | 
</div>
