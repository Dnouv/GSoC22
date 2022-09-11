<div align="center">

[<img alt="alt_text" width="95px" src="https://user-images.githubusercontent.com/61188295/189516421-c5f7caf9-a8ab-48ec-a8d7-f36a6d9a2040.png" />](https://github.com/RocketChat/RC4Conferences)
[<img alt="alt_text" width="100px" src="https://github.githubassets.com/images/modules/logos_page/Octocat.png" />](https://github.com/RocketChat/RC4Conferences)

Rocket Chat for Virtual Conferences Project in GSoC 2022

</div>
<div align="center">
  
# 🦄 Rocket Chat for Virtual Conferences - [RC4Conferences](https://github.com/RocketChat/RC4Conferences) 🦄
</div>
  Hello, there! This repo is dedicated for final work report submission for the Google Summer of Code - 2022. And would give a brief overview of all the PRs, issues and also the various featured implemented during this season.

<div align="center">

## 🖇️Links to the deployed demo website🖇️
</div>

1. [HomePage](https://conf.rceng.shop)
2. [Demo Day Event](https://conf.rceng.shop/conferences/c/1)

<!-- ![](https://github.githubassets.com/images/modules/logos_page/Octocat.png) -->

<div align="center">

## 🚀 More about RC4Conferences 😮
</div>
An open source scaled virtual conferences creation, management, and operation system. It aims to enable online communities to easily run and host virtual events of any size. Built over contemporary ReactJS components with full stack behaviors, powered by NextJS. This project leverages FOSS Asia's excellent open source Event-yay server backend for conference creation and management. For day of conference operations, this project leverage open source Jitsi video's broadcast capability to an RTMP-forest for scaled consumption while embedded Rocket.Chat enables attendees and speakers to mingle and collaborate freely – with full persistent chat history.

<div align="center">

## 📦Deliverables📦
  
</div>

- Event Authentication Component - Component which handles sign up and sign in with Open Event Server for the users, and stores the token recieved from the server in the cookies.
- Event Create Component - Component which helps to mutate the Open Event Server with Event Data, and Speakers data.
- Event Display Component - Component that diplays the events created based on the event id, and includes different tabs viz. About, Sessions, Speakers
- Event Admin Dashboard Component - A set of component which enables the event creator/admin to edit and delete events and event related data, currently only speakers details can be edited.
- Day of Event Components - A jitsi window component to catch the streams of Speakers, and broadcast them using RTMP to the second component which did the task of catching this stream and broadcast it to the Event attendees.

Some wonderful features suggested by Mentors:
- Integration with Superprofile for a better role based access to different user routes.
- Storing encrypted cookies instead of raw user data.
- Dockerizing almost all the backend and frontend services except for Strapi, for a smooth development environment setup.
- Setting up a docker user-defined network for internal communication between various containers.

<div align="center">

## 💡Pull Reuqests💡

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
----

</div>

<br />

<div align="center">

| #  | PR short description | Is merged? |
| :-------------: | ------------- | :---------: |
| [#44](https://github.com/RocketChat/RC4Conferences/pull/44)   | Add Youtube Iconbutton in the session | 🕛 |
| [#4](https://github.com/RocketChat/RC4Conferences/pull/4)   | Implement the required base work for developing the project as an npm package | ⛔ |
| [#3](https://github.com/RocketChat/RC4Conferences/pull/3)   | Implement the required base work for developing the project as an Git Submodule | ⛔ |
| [#44](https://github.com/RocketChat/RC4Conferences/pull/44)   | Add Youtube Iconbutton in the session | ⛔ |
----



</div>

<div align="center">

## 🤺 Issues 🤺

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
----
</div>

<div align="center">

## 📹 Some Feature Demo Clips 📹
</div>

### Creating a Event
All the data recieved from the Event basic details form are used for mutating the Open Event Server with Event Details. This demo shows the Event Authorization component on the page, `/conferences/create` when the user clicks on the "Create Event", followed by the Event Create component once the user fills in all the details this component handles doing the mutation by interacting with Open Event Server and prompting a success event creation message.

https://user-images.githubusercontent.com/61188295/189488217-b5ce263a-64f6-485d-a65c-5b382ca239ec.mp4


### Admin Dashboard
A walkthrough of the options available on the Admin Dashboard. The Demo displays the Event Admin components, from where the Event owner is able to "Add Speaker", "Delete Speakers", "Delete Events", and "Preview Events".

https://user-images.githubusercontent.com/61188295/189500874-0a1298e0-e455-4a7e-9e08-ea456febe3b2.mp4


### Event Display Poster Page
Features available on the Event Poster page, with many different tabs viz. About, Sessions, and Speakers. The Demo displays the implemented Event Display Poster component, which handles fetching the event details and rendering it in a nice UI.

https://user-images.githubusercontent.com/61188295/189488239-0aa31cf8-a8fe-42bf-95ab-65c9f03797b2.mp4


### Demo of Role based access to different day of event pages
As shown in demo a not signed in user won't be able to access either the __Mainstage__ or __Greenroom__ page. This Demo shows the role based access which is based upon the FaunaDB Superprofile, we have three Roles "Admin", "Speaker" and "Attendees".
- "Admin", "Speaker" : Able to access the Greenroom page, the page which opens up after "Join as a Speaker"
- "Attendee": Only able to view the Mainstage page, the page which opens up after "Join as a Attendee"

https://user-images.githubusercontent.com/61188295/189488258-b0e8535a-c7f6-4174-84d6-c3d93e92c484.mp4


### Demo of the Speaker Greenroom Page and the Mainstage page
Demo includes how an Admin starts the live stream and chats with the other Attendees on the Mainstage page, where the attendees are viewing the live broadcast.
The Greenroom page deploys an Jitsi call, which handles all the video and audio processing and transmission using RTMP which is later on broadcasted on the Mainstage Page, both the pages has an RocketChat Embedded Chat window to interact with each other during the event.

https://user-images.githubusercontent.com/61188295/189488270-5a33ede0-9a8b-40ad-9604-1d4d4fb6ec31.mp4


<div align="center">

## 🌊 The tides (challenges) I sailed across this GSoC season 🌊
</div>

1. Decide how to develop the project whether to develop it as an npm module, or Git Submodule or independent repository.
2. Implement a secure role based access.
3. Dockerizing the Superprofile - FaunaDB.
4. Figuring out how to initialize the Open Event Server with some dummy data.
5. Exploring the huge codebase of Open Event Server to figure out how it works.

<div align="center">

## 🔮 Challenges in the future bag 🔮
</div>

1. Improving the NextJS docker files.
2. Adding event email notification.
3. Improving the documentations.
4. Enhancing the Admin Dashboard.
5. Providing event stream analytics.

<div align="center">

## ✨Mentors✨
  
</div>

I am grateful to have got a chance to work under my two super knowledgeable and experienced mentors. They helped me throughout the whole GSoC season, and not only with technical development they also took care of developing my soft skills, which was certainly helpful.
Under their guidance, I sailed across the GSoC sea, and successfully learned many new things which include but are not limited to Docker, Software development flow, creating a better UX, docker networks, and best security practices.

The Astounding mentors:
1. Sing Li ([GitHub](https://github.com/Sing-Li), [Rocket.Chat](https://open.rocket.chat/direct/sing.li))
2. Marcos Defendi ([GitHub](https://github.com/MarcosSpessatto), [Rocket.Chat](https://open.rocket.chat/direct/marcos.defendi))

<div align="center">

## 👋Let's talk👋
  
</div>

Hello, there I am a final year undergraduate B.Tech student @ NITR based in Mumbai; if you are interested or want to drop by to say Hi, please feel free to contact me on any of the following mediums, I will look forward to your message.

<div align="center">


| GMail  | LinkedIn | RocketChat |
| :-------------: | :-------------: | :------: |
| [<img alt="alt_text" width="45px" src="https://user-images.githubusercontent.com/61188295/189502370-f4218b1c-d57a-43fa-a895-049a71f0bc64.png" />](mailto:sdevanshu90@gmail.com)  | [<img alt="alt_text" width="35px" src="https://user-images.githubusercontent.com/61188295/189502377-1de8ed4c-0726-4a92-945e-33f6aa976a31.png" />](https://www.linkedin.com/in/shade00)  | [<img alt="alt_text" width="35px" src="https://user-images.githubusercontent.com/61188295/189502616-a9dbea03-a4b6-489a-8c8c-e4675b7cfc1c.png" />](https://open.rocket.chat/evan.shu) |

</div>


<div align="center">

## 🔗Additional Links🔗
  
</div>

Link to Rocket Chat GSoC'22 [Demo Day slides](https://docs.google.com/presentation/d/1_fevhXOHLVgbhaOFGL40FDgPPUiWbhO1g5cFrJCGCF8/edit?usp=sharing) .



