[welcom-badge]:  https://img.shields.io/badge/PRs%20&%20Issues-welcome-brightgreen.svg?style=flat-square
[welcome-link]:  https://github.com/Rishabh04-02/The-Beginners-Guide-to-Google-Summer-of-Code-GSoC?style=flat-square
[travis-badge]: https://travis-ci.com/Rishabh04-02/The-Beginners-Guide-to-Google-Summer-of-Code-GSoC.svg?branch=master
[travis-link]: https://travis-ci.com/Rishabh04-02/The-Beginners-Guide-to-Google-Summer-of-Code-GSoC
[hit-count-image]: http://hits.dwyl.io/Rishabh04-02/The-Beginners-Guide-to-Google-Summer-of-Code-GSoC.svg
[hit-count-link]: http://hits.dwyl.io/Rishabh04-02/The-Beginners-Guide-to-Google-Summer-of-Code-GSoC

# The Beginners Guide to Google Summer of Code (GSoC) [![Build Status][travis-badge]][travis-link] [![HitCount][hit-count-image]][hit-count-link] [![PRs & Issues Welcome][welcom-badge]][welcome-link]

![GSoC Logo](gsoclogo.svg)

## Introduction
This is the beginners guide to Google Summer of Code (GSoC). The Google Summer of Code is an annual global program sponsored and managed by Google. The program focuses on bringing more student developers into open source project development. In this program, the students work with an Open source organization under the guidance of mentors (selected organization members) on a 3-month programming project in Summers. 

## Motivation
It all started with a blog post. I was writing a blog post "the beginners guide to GSoC" to help various students (who otherwise reach us on various social media platforms to ask queries and for the students of NITH and IIITU) get all the information and resources at one place. Then I thought to create this repo so that other knowledgeable people can also contribute and to maximize its reach.
Me and the other collaborators of this repo are all GSoC students from NITH and IIITU. So, we'll try to provide accurate, to the point and as much information as we can.

## Table of Contents
* [What is Open Source](#what-is-open-source)
	* [Why Should we Care](#why-should-we-care)
	* [How to make a contribution](#how-to-make-a-contribution)
	* [Difference between Open Source, Freeware and Other Softwares](#difference-between-open-source-freeware-and-other-softwares)
* [What is git and GitHub](#what-is-git-and-github)
	*  [Version control systems](#version-control-systems)
* [What is Google Summer of Code](#what-is-google-summer-of-code)
	* [Eligibility criteria](#eligibility-criteria)
	* [Am I good Enough](#am-i-good-enough)
	* [Benefits of GSoC](#benefits-of-gsoc)
	* [Required Skills](#required-skills)
* [How to Start](#how-to-start)
	* [Selecting the Project and Organization](#selecting-the-project-and-organization)
	* [Understanding the Project](#understanding-the-project)
	* [Drafting the Project Proposal](#Drafting-the-project-proposal)
	* [Getting Selected](#getting-selected)
* [Useful Links](#useful-links)
* [Terminologies](#terminologies)

## What is Open Source
The term Open Source means the source code of the software is freely available to its users, and anyone can modify it. Open Source software can also be redistributed after modifying the original software. The Open Source Softwares are usually available to the users for free, and this software has no licensing fee or other restrictions as they use [open source licenses](https://en.wikipedia.org/wiki/Open-source_license). To know the detailed definition of Open Source, you can visit this [link - opensource.org](https://opensource.org/osd).

Few examples of open source softwares which you might be using on a daily basis are:

* [Mozilla Firefox web browser](https://www.mozilla.org/en-US/firefox/) -  It has 665,020 commits made by 7,369 contributors representing 20,505,182 lines of code. [Reference](https://www.openhub.net/p/firefox)
* [VLC media player](https://www.videolan.org/index.html) - It has 82,544 commits made by 524 contributors and has 50 releases. [Reference](https://github.com/videolan/vlc)
* Almost all the Linux distributions. [Reference](http://glug.nith.ac.in/getting-started)

### Why Should we Care
**Why Should we care if a software is open source?**

As the source code of open source software is freely available. Then there is a negligible chance that the software is not respecting the user privacy. Which means that the software can't do something like this [These 6 popular browser extensions are selling your data](https://www.digitaltrends.com/news/popular-browser-extensions-are-selling-your-data/) and this [Uninstall These Eight Browser Extensions That Stole Data from Millions](https://lifehacker.com/uninstall-these-eight-browser-extensions-that-stole-dat-1836539093).

However, this does not mean that open source software is more secure than closed source software. As in case of open source, the code is freely available so the threat actor can easily find vulnerabilities in it when compared to it being closed source. However, almost all of the popular open-source software is developed by the "best of the brains" on earth.

There is another reason we should care about these softwares, as most of these softwares are created and maintained by developers who don't get paid for anything or organizations which rely on donations to keep their projects alive. This software is not created to earn money and make profits; instead, they are created to help/ease the lives of other people. To understand this better, you should have a look at the [History of Firefox](https://itsfoss.com/history-of-firefox/).

The Open source projects benefit users in the way that they are free, can be modified and redistributed (but to modify any software one should know it better, not everyone can modify a software), provide flexibility. These projects also benefit large corporations, eg. Microsoft edge is based on Chromium an open-source browser. These corporations can use the source code of open source software without any restrictions, license issues or copyright infringement. 

### How to make a contribution
Contributing to open source helps the contributor learn and gain experience about the language, product OR skill. However, before trying to contribute to open source, you have to learn a few elementary skills. E.g., git, GitHub, a programming language (not necessary for everyone, but essential for GSoC aspirants), basic knowledge of IRC(Internet Relay Chat), Basic knowledge of Bug tracking tools.

Reference to learn about [git and github](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners).

The best way to contribute to an open-source project is by getting to know the project and then finding a mentor (who may be an existing contributor to the project). The mentor helps you know the project better and guides you through it i.e., which bugs you should work on, how to fix a particular bug, how to submit your patch <sup>[1]</sup> (following the organization contribution guidelines). Working with a mentor helps you a lot. Moreover, if your mentor belongs to an organization that gets selected for GSoC, then you'll have the edge over other participants who are trying to get into GSoC.

If you are unable to find a mentor, then you have to join the project community which can be on IRC(Internet Relay Chat), Slack, Gitter, etc. For Example, the project community of [The Libreswan Project](https://libreswan.org/wiki/IRC) is on IRC. Then you can ask a question related to the project or organization. However, don't ask the too obvious question. By Obvious question, I mean the question which can be quickly answered by reading about the project on the organization website or project README.md. E.g. "What does this project do?".

Once there, you could ask questions related to bugs for beginners, etc. Usually, the organization members take the time to respond to such questions. So, after asking the question, wait for 24-48 hours (Keeping in mind the timezone difference).

Once you reach there, start solving the easy bugs OR bugs for beginners and submit your patch (or pull request).

**If you want to make your first contribution without getting involved with the organization members, then there is a way.**

* Visit [Github:firstcontributions](https://github.com/firstcontributions/first-contributions) and follow the instructions.
* Visit [firsttimersonly.com](https://www.firsttimersonly.com) and follow the instructions.

You can find various such repositories on GitHub or GitLab with a simple web search.

There is a guide on [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/) where you can find the detailed description of everything.

### Difference between Open Source, Freeware and Other Softwares
* **Open Source Softwares** - The source code of these softwares is freely available to its users, and anyone can modify and redistribute it. These softwares use open source licenses which don't have any licensing fee. E.g., Mozilla Firefox web browser.

* **Freeware Softwares** - These are the softwares which are free to use. However, their source code is not available and is protected with proprietary rights, license, and copyrights. E.g., WinRAR.

* **Proprietary software** - These are the softwares which are not free to use, and their source code is protected with proprietary rights, license, and copyright. The user needs to pay a specific amount to use the software. They often have limitations on its use; e.g., it can be installed only on one PC. These softwares are also called closed-source softwares. E.g., Microsoft Office.

## What is git and GitHub
Git is an open-source version control system. Its main aim is to handle various kinds of projects with speed and efficiency.

GitHub is a web-based hosting service for version control using git.

### Version control systems
**What are version control systems?**

The version control system is a category of software tools that keeps track of changes done to a file/files over time.

The main benefit it provides is that at any time we can view/revert to any available versions of a file/files while other benefits are branching, merging, and traceability.

To read about version control systems in detail, visit [Getting Started about version control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) or [What is version control](https://www.atlassian.com/git/tutorials/what-is-version-control).

## What is Google Summer of Code
Google Summer of Code (GSoC) is an annual global program sponsored and managed by Google. The program focuses on bringing more student developers into open source project development. In this program, the students work with an Open source organization under the guidance of mentors (selected organization members) on a 3-month programming project in Summers. In this program, Google also awards stipends to students in 3 rounds or evaluations. The amount of Stipend depends on students geographical location. 

The whole program is divided into 3 evaluations or coding stages. Students plan & code for 1st month and then mentors review their work and provide their evaluation feedback and status to Google. The evaluation feedback and status(Passed/Failed) is then provided to the student on her dashboard. The students also submit the evaluation of their mentor, but those are just a few questions related to the project and mentor's performance. This whole process happens 3 times, and then the results are announced by Google.

### Eligibility criteria
* **Requirements** - To participate in the program, a student must:

1. be eighteen (18) years of age or older upon registration for the program;
2. be enrolled in or accepted into an accredited institution, including a college, university, masters program, Ph.D. program, or undergraduate program, as of the Acceptance Date;
3. for the duration of the program, be eligible to work in the country in which he or she resides; and
4. not be an Organization Administrator or Mentor in the Program.

* **Ineligible Individuals** - A Student may not participate in the program if he or she is:

1. a resident of a United States embargoed country;
2. ordinarily resident in the United States embargoed country; or
3. otherwise prohibited by applicable export controls and sanctions programs.
4. Employee (including intern), contractor, officer, or director of Google or its affiliates, or an organization or any of its affiliates.
5. Immediate family member (including a parent, sibling, child, spouse, or life partner) of a Mentor or Organization Administrator with the same Organization or a member of the same household (whether related or not) as a Mentor or Organization Administrator with the same Organization.
6. Has previously participated as a Student in Google Summer of Code two (2) or more times.

To know the complete rules visit the [GSoC Rules Page](https://summerofcode.withgoogle.com/rules/).

### Am I good Enough
If you are familiar with the technologies mentioned in the section - [How to make a contribution](#how-to-make-a-contribution), have experience contributing to open source and know how to program, then you are good to go.

There are various other skills required to plan for the project and complete the project. However, you'll learn them on the way.

There is more information available on the context at [GSoC Guides](https://google.github.io/gsocguides/student/am-i-good-enough).

### Benefits of GSoC
There are various benefits of completing GSoC.

* The recognition: GSoC is recognized worldwide, so when applying for jobs you'll get an advantage. However, GSoC students are more preferred by Startups than well-established organizations because, in startups like GSoC, you have to learn new skills and technologies very fast and become good at it.

* The network: After completing GSoC you now have many connections which help you and can provide recommendation when needed.

* The Stipend: They pay well.

* The referral: After completing the program you are given a one-time referral which you can use within 6 years for any job at Google.

* The Exposure: When working on the project with experienced developers, you get to learn a lot and get the industry's exposure.

* The Swag: What do developers like more than swag or goodies. You'll get a GSoC T-shirt and a certificate.

* Chance to Mentor: You can also be a mentor the next time or in GCI by Google.

### Required Skills
Few of the skills are mentioned in the section - [How to make a contribution](#how-to-make-a-contribution). E.g., git, GitHub, a programming language, basic knowledge of IRC(Internet Relay Chat), Basic knowledge of Bug tracking tools, git, and GitHub.

You should also be familiar with the basics of [Software/System development life cycle](https://en.wikipedia.org/wiki/Systems_development_life_cycle) (This will help you in drafting an impressive and detail-oriented project proposal), MS Word/Google Docs.

Also, the knowledge of the skills required for the project would be an added advantage.

E.g. An example from my project proposal.

```
The basic tasks required for this project involves ​creating python/shell scripts, 
working with LetsEncrypt and OpenSSL, creating and modifying configuration files, 
working with Libreswan. I’ve worked on all of the above-mentioned tasks, some in 
my projects(including Libreswan Managing Interface) and on some while contributing 
to other open source projects.
```

## How to Start
The most challenging part of GSoC is Stage 1 - "The journey from the beginning to selecting the project of your interest". This is the most frustrating part where the students have to search for various projects and see if they are interested in it. Also, this is the stage where most of the aspiring GSoC students quit.

The most common mistake students make in this stage is that they limit their search to specific programming languages. They only search for projects in a specific programming language rather than searching for the project of their interest. 

**Why should you choose a project based on your interest?**

There are two reasons for this:
1. If you know, programming, then the language should not be a barrier in selecting the projects. You should be adaptive and fast learners, and these skills matter in GSoC.
2. It will help you in drafting a good proposal. If you are interested in the project, then you'll learn a lot about it and will explore it. However, if you select a project based on language, then you'll do the necessarily required stuff and that so without much interest. 
3. During the program, there will be times when you'd want to quit. The project will be getting hard, and you'll have a difficult time keeping up with it. At this point, it's only the interest that will keep you going, and if you had selected the project based on language with no interest in it, then you'll inevitably quit. I've seen many GSoC students quit the project because the project has become hardened, and they don't have interest in it.

### Selecting the Project and Organization
**How to select the project or organizations?**

This stage of searching won't be easy, so you have to be patient. 

First of all, you need to choose an organization (which might be doing work related to your interests) for that the best way is to visit [GSoC Archive](https://summerofcode.withgoogle.com/archive/) and see the completed projects and then visiting the website of the organization and searching for GSoC projects. If you didn't find any of the projects listed, then you can contact the organization members and ask them about the projects. This process will take weeks, but it is a sure way you can find the projects of your interest. 

Note - 

* Don't forget to ask the organizations members whether they'll be taking part in the next GSoC or not.
* Start searching the archive in the order latest to oldest i.e., 2019 to 2009.

I had written a blog post describing my experience when I was in the stage of searching for the project and organization. [GSoC - Selecting the project and organization
](https://therishabh.in/gsoc_selecting_the_project_and_organization/)

### Understanding the Project
Once you have completed Stage 1 ([Selecting the Project and Organization](#selecting-the-project-and-organization)), then the next thing is to understand the project, organization, and development technologies used by the organization.

To achieve this aim you can read about the organization and its projects on their website or repositories or the web. Once you've gathered all the necessary knowledge about the organization and its projects, then gather as much knowledge as possible about the project you want to contribute. You can do this by asking a sensible question about the project to the organization members/Admins, once you've done this start contributing to the project. To make your first contributions, you should fix easy bugs in the project. 

If your project is new and hasn't been started yet, then it's better to learn about it as much as you can, the organization members can help you with it. This thing happened to me in GSoC 2018, my project wasn't started, and the GSoC task was to build it. I gather information about it as much as I can and then drafted the project proposal. During the process, I was continuously asking the questions and clearing my doubts about the project by asking them to the organization Admin. You can also contribute to other organization projects if it helps in GSoC, ask the organization members about it.

I had written a blog post about the same. [GSoC - Initial phase and getting selected](https://therishabh.in/gsoc_initial_phase_and_getting_selected/)

### Drafting the Project Proposal
Drafting the Project Proposal is the most critical part of GSoC, as all your efforts and progress until now depends on the proposal. Everything you've learned from the mentors, community, peers about the project should reflect in the project proposal. If you've learned a lot about the project and that too in detail, but you fail to represent all that in the proposal, then it won't help you.

Usually, organizations have their project proposal formats, and it's good if you stick to it. But if your organization doesn't have a project proposal format, then below are a few things you can include in your project proposal:

* **Background** - A little ( <150 words) background always helps. You can also add it to the description section of the GSoC dashboard.
* **Objectives** - Clear and concise objectives will help others (including organization members) understand your project-related goals better.
* **Technical Components/Modules** - It is always better to divide the whole project into few (<10) components. It'll help you and your mentor to keep track of your progress, and you'll be able to achieve the Objectives in a precise and planned way.
* **Sub components/sub modules** - Further divide the components and modules into sub-components and sub-modules to the point that each sub-module is an independent entity/task.
* **Use references** -  When explaining any task/module it's better to provide some references. A reference can be code snippet of similar nature (i.e., it represents some similar implementation) from the same or different project.
* **Timeline** - It is distributing all the above tasks/components/modules over 12 weeks.
* **Evaluation** - It just represents the above timeline in GSoC Evaluation periods. So, you and your mentors can track how many tasks are completed in a specific period of time.
* **Personal** - You can also include some essential personal information.
* **Social Profiles** - You can mention the links to your GitHub, Website, etc. and your email address.
* **Timezone** - It'll help your mentor to schedule calls/meetings with you.
* **Some Essential Information** - The information like your comfort working with a remotely available mentor, Your native language, Are you likely to finish the project in the allotted time, etc. will help you a lot.

I've attached a [sample proposal for your reference](https://github.com/Rishabh04-02/The-Beginners-Guide-to-Google-Summer-of-Code-GSoC/blob/master/Sample-GSoC-Project-Proposal.pdf).

### Getting Selected
If you get selected then you'll be able to see various details and options in the GSoC dashboard, and you'll get an mail from Google open source regarding the next steps; you have to follow them. And the best thing is you'll get some time for community bonding with the organization and mentors, use that time to clear all your doubts (if any) regarding the project, organizations, etc. This is an excellent time to discuss your roadmap (Timeline) with your mentors and fix slots for weekly or bi-weekly meetings.

If you are not selected for the project, introspect and try to know the reasons for your failure and ask yourself a question "Why do you want to be a Google Summer of Code Student?". Learn from those failures and try again.

Remember one thing "Success consists of going from failure to failure without loss of enthusiasm." - Winston Churchill

## Useful Links
1. [An Introduction to Open Source](https://www.digitalocean.com/community/tutorial_series/an-introduction-to-open-source)
2. [Learn about git and GitHub](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)
3. [GSoC Guides](https://google.github.io/gsocguides/student/)
4. [Introduction to Open Source - A Series by DigitalOcean](https://www.digitalocean.com/community/tutorial_series/an-introduction-to-open-source)
5. [Contribute to Open Source. Search issue labels to find the right project for you!](http://issuehub.io)
6. [Awesome First PR Opportunities](https://github.com/mungell/awesome-for-beginners)
7. [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)

## Terminologies
1. patch - It is a set of changes to a computer program or its supporting data designed to update, fix, or improve it.

## Contribute
You have something to share? 
Open an Issue or Create PR.

## License
This project is licensed under [MIT License](https://github.com/Rishabh04-02/The-Beginners-Guide-to-Google-Summer-of-Code-GSoC/blob/master/LICENSE)
