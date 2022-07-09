![](https://github.com/kusamahubteam/kusamahubteam/blob/9b26c430f2c8b59f4e84012a4288839b17a25749/images/logo/kh_logo.png) <br />
<br />

KusamaHub is a web app for Kusama network NFTs projects with analytics tools.
We collect all NFT projects information from Twitter, Discord, Telegram, websites and, even more important, we provide the users with the opportunity to communicate and discuss certain projects from both Collector's and Creator's sides.
Based on this we make detailed analytics, which helps estimate NFT project or creator, get all
information about sales, prices changes, holders. KusamaHub provides different tools, such as
Calendar, News, Users Reviews and more.
Our goal is to give to the community a better analytics tool with information about Kusama NFT Projects and creators.
<br />

- [Tools](#tools)
  * [News](#1-news)
  * [Analytics](#2-analytics)
  * [Users Ratings](#3-users-ratings)
  * [Editors Ratings](#4-editors-ratings)
  * [Users Reviews and Comments](#5-users-reviews-and-comments)
  * [Verifying Process](#6-verifying-process)
  * [Calendar](#7-calendar)
- [Design](#design)
  * [Cards](#1-cards)
  * [Project Card and Project Page](#2-project-card-and-project-page)
  * [Creator Card and Creator Page](#3-creator-card-and-creator-page)
  * [Themes](#4-themes)
  * [Mobile-first](#5-mobile-first)
  * [PWA](#6-pwa)
  * [Accessibility](#7-accessibility)
- [Privacy](#privacy)
- [Techical part](#techical-part)
- [Roadmap](#roadmap)
  * [First Close Beta Test](#1-first-close-beta-test)
  * [Second Close Beta Test](#2-second-close-beta-test)
  * [Open Beta Test](#3-open-beta-test)
  * [Editors Raitings and Verifying Process](#4-editors-raitings-and-verifying-process)
  * [Closing Beta test and announce Leaderboards](#5-closing-beta-test-and-announce-leaderboards)
  * [Making improvements](#6-making-improvements)

# Tools

Kusama Hub provides different tools for the community.

## 1. News
- We deliver News about Kusama. 
- We get information from Telegram, Discord, YouTube, Twitter and official projects websites. 

Users get latest updates from sources above. Verified projects and Creators have ability to setup official
News channel to instant news delivery.
Our goal is give community a best analytics and full information about Kusama NFT projects and
Creators and let them interact inside the platform.

![](https://github.com/kusamahubteam/kusamahubteam/blob/9b26c430f2c8b59f4e84012a4288839b17a25749/images/readme/News.png)<br /><br />

## 2. Analytics
We get information about all transactions with NFTs in every project to give user detailed information about Sales, Holders and more. Many type of information have graphs among with detailed analysis. Based on this information we provide users with statistic about top sales, top creators, top projects and more on main page.

![](https://github.com/kusamahubteam/kusamahubteam/blob/9b26c430f2c8b59f4e84012a4288839b17a25749/images/readme/Analytics.png)<br /><br />

## 3. Users Ratings
All users can connect personal Kusama wallet to submit a rating to all projects and creators. Simple system Like / Dislike which shows users confidence to project or creator.

![](https://github.com/kusamahubteam/kusamahubteam/blob/9b26c430f2c8b59f4e84012a4288839b17a25749/images/readme/Ratings.png)<br /><br />

## 4. Editors Ratings
This is special type of raiting, which gives to all projects and creators by KusamaHub Editors. It’s can’t be edited by users and shows actually trust-meter for project or creator based on different categories: Project have active sales, active community, social media, verified by owner on KusamaHub and more. Like Users Ratings this info helps users get a right decision about a project.

![](https://github.com/kusamahubteam/kusamahubteam/blob/9b26c430f2c8b59f4e84012a4288839b17a25749/images/readme/EditorsRatings.png)<br /><br />

## 5. Users Reviews and Comments
All users can leave comment (aka review) about NFT project or creator. Reviews system devided on three tabs with special flairs: User have NFT, User sold NFT and User don’t have NFT. If user have NFT from collection which he comment, he’s review gets special tag, which give more honest grade and confidence to review. Also, we have hidden filters to reduce spam attack in comments.

![](https://github.com/kusamahubteam/kusamahubteam/blob/9b26c430f2c8b59f4e84012a4288839b17a25749/images/readme/Comments.png)<br /><br />

## 6. Verifying Process
Every creator can verify his own collection or profile via our special form. Verifyng gives users more info and gives transparency about Creator or NFT project. KusamaHub verifying affects to Editors Raitings. Verified projects can be shown in Trending block on main page. Verified Creators can edit their profiles. Only verified projects can display upcoming events in Calendar.

![](https://github.com/kusamahubteam/kusamahubteam/blob/9b26c430f2c8b59f4e84012a4288839b17a25749/images/readme/Verify.png)<br /><br />

## 7. Calendar
We collect and provide users information about NFT announces, airdrops, mints and more. On main page KusamaHub have NFT Calendar with all projects upcoming events. User can select Day, Month, check info about event and create notification. Every Project and Creator Pages have Calendar card with they upcoming events.

![](https://github.com/kusamahubteam/kusamahubteam/blob/9b26c430f2c8b59f4e84012a4288839b17a25749/images/readme/Calendar.png)<br /><br />

# Design

We are trying to build simple, user-friendly, available for all web application. Our goal is provide big amount of data as simple as it’s possible to users.

## 1. Cards
All information on our side delivers in Cards. Cards have different settings, stylings and functions. Cards have divided on categories which helps to see similar type of information in one place. For example, Ratings and Reviews shows together, so user immediately see useful information. Some cards have visual settings, they can be reordered or hidden. Visual settings displays only for each users and stores in user account.

![](https://github.com/kusamahubteam/kusamahubteam/blob/9b26c430f2c8b59f4e84012a4288839b17a25749/images/readme/Cards.png)<br /><br />

## 2. Project Card and Project Page
KusamaHub generates page for all NFT projects, which stores in the Blockchain. When the Project Pages are generated, we collect information and provide Analytics, Ratings, NFTs in project, Events and more. If a project has social media, we automatically add it to the Project Page to deliver the last news into the Project Card. If some information are incorrect or incomplete, the Creator can simply verify his ownership and edit the information, highlight NFTs and reorder links. Project Card are equally shown all over KusamaHub app and can be shared on Social media.

![](https://github.com/kusamahubteam/kusamahubteam/blob/9b26c430f2c8b59f4e84012a4288839b17a25749/images/readme/ProjectCard.png)<br /><br />

## 3. Creator Card and Creator Page
Like Projects, we generate pages for all Creators. It has same design like Project
Page, but contains information about Creator - projects, social media, news and etc. When
Creator connects his wallet, he already can edit information on his page, like name, social media,
highlights and etc. Every Creator can verify his profile which gives more trust in community. Every
Creator have Creator Card, which can be shared in
Social Media.

![](https://github.com/kusamahubteam/kusamahubteam/blob/9b26c430f2c8b59f4e84012a4288839b17a25749/images/readme/CreatorCard.png)<br /><br />

## 4. Themes
KusamaHub support Light and Dark theme, which automatically switch according to devices settings. Users can switch theme manually.

![](https://github.com/kusamahubteam/kusamahubteam/blob/9b26c430f2c8b59f4e84012a4288839b17a25749/images/readme/DarkMode.png)<br /><br />

## 5. Mobile-first
We building KusamaHub as Mobile-First, so it’s looks perfect on all Screen sizes and Devices.

![](https://github.com/kusamahubteam/kusamahubteam/blob/9b26c430f2c8b59f4e84012a4288839b17a25749/images/readme/Mobile.png)<br /><br />

## 6. PWA
KusamaHub can be added as application on Home Screen.<br />

Learn more about PWA: <br />
https://web.dev/progressive-web-apps/ <br />
https://www.w3.org/TR/appmanifest/ <br />

![](https://github.com/kusamahubteam/kusamahubteam/blob/9b26c430f2c8b59f4e84012a4288839b17a25749/images/readme/PWA.png)<br /><br />

## 7. Accessibility
We are trying to make our app available for all, so KusamaHub provide Accessibility support. We have
high-contrast theme, support of all OS Accessibility systems and provided detailed description for
all images and elements on page.
We are using W3 guidlines for make KusamaHub available for all.
<br /><br />
Learn more:<br />
https://www.w3.org/WAI/standards-guidelines/wcag/ <br />
https://www.w3.org/WAI/fundamentals/accessibility-intro/ <br />


# Privacy

Users privacy is a must. We don’t have ads or trackers. We do not collect users information like emails, names and etc.
We store little amount of information to provide users social functions like User Ratings and Users Reviews.
When user connect wallet, we store Kusama wallet address in our database, to connect User's Rating and User's Reviews.
We store Projects and Creators information about social links, Upcoming Events and Editors rating to provide full access to this functions.

# Techical part

We are an open source project, so every one can see our code and suggest how to improve it. All code is
available on GitHub, so every one can check what we do. <br />
KusamaHub is a web-based project. We receive information from Kusama blockchain and sort it to
show Projects Pages information, Creators Pages information.<br />
We don’t takes permissions to receive or transfers NFTs. <br />
All information strongly secured in our database and nobody, besides developers of KusamaHub,
have access to it.

# Roadmap

## 1. First Close Beta Test
After development of main functions of KusamaHub, we will announce a closed beta test for users,
who will apply on our site. All fully information of Closed Beta Test we will be provided right after the announcement.
On this step we will test all site stability, user logins, Project Pages, Creator Pages and Analytics.

## 2. Second Close Beta Test
On this step we will test Users Raitings and Reviews System. Also will testing Accessibility on all
devices.

## 3. Open Beta Test
After closed beta tests we will fix all bugs and provide access to all users.
On this step we will test KusamaHub stability, all functions from previous Closed Tests, News
parcing, Calendar, Analytics Graphs.

## 4. Editors Raitings and Verifying Process
On this step we launch KusamaHub Editors Raitings and Verifying Process. All users will get
more info about projects, Creators will recive Verify tool to they projects and personal pages.

## 5. Closing Beta test and announce Leaderboards
On this step we are finishing Beta tests and KusamaHub goes officially live! Users can use all
KusamaHub tools, main page will get Top stats.

## 6. Making improvements
On this and next steps we will trying to make KusamaHub improvements based on community needs.
