 

 

 

 

 

Scope, Epics and Stories

for

Orgmatics

 

 

 

 

# **Table of Contents**

 

- Description of the problem in your words                                                                                        

1- Scope                                                                                                                                             2- Key Business Requirements and Processes                                                                                       3-** **System Context Diagram                                                                                                                 4-** **Epics                                                                                                                                              5- User Stories                                                                                                                            6- Risks                                                                                                                                              7- Definitions, Acronyms, Initialisms, and Abbreviations (DAIAs)                                                   

 

## **Description of the problem :**

It is important to help individuals to become interested in lifelong learning, as well as to encourage those educational efforts in a sustained manner. There are a myriad of potential sources of knowledge and education available, and providing a framework in which to situate those sources towards achieving selected learning objective goals is a way of fostering individual interest in learning. By creating a flexible format of setting timetables, learning objectives, and offering curated context to pursue the desired goals, this application will create a platform for a learner to go to for tracking their learning goals.  

Current sources of learning are utilized in a "silo" kind of format, wherein a learner can be pulled into deeper levels of learning offered by a platform while losing track of their original learning intentions. With the myriad of learning resources available to users, it is very easy for a user to lose sight of their learning objectives, become frustrated, and give up. By creating a visual means that allows a learner to see the progress that they are making, utilizing strategic tools and strategies that will optimize the usability of the application, and by creating other approaches (e.g. gamification, social network), this application will help to keep the learning user engaged. In addition, the platform will help to suggest learning options that will enhance the learning user’s experience, “bubbling up” possible learning courses or materials from the confusing myriad of options through crowdsourcing of knowledge and predictive modeling. 

Finally, making this platform as user-friendly and accessible as possible will help business requirements of scalability while attaining project goals of creating supports for as wide-ranging a user base as possible. By stressing a user-experience portal which embraces technology that offers potentiality for allowing users to engage on a global level, to engage in a variety of modalities, and with an architecture emphasizing flexibility, this application will have built-in flexibility around future changing user needs.

## **1) ****Scope**

* *Deliverables:*

    * Software that allows for learner-created learning objectives and chosen curriculum in a flexible time-based format.

    * Business Requirement Document, Architecture documents concerning Conceptual, Information, Software, Security, User Experience, Deployment, Technology Stack Document, and Execution Plan

* *Capabilities*:

    * Select Learning Objective and curriculum from offered or suggested options

    * Create unique Learning Objective and curriculum

    * Interact with learning community via possible groups or leagues, individual conversations, message boards, or by learning module contributions

    * Shared recognition of learning actions and development via in-community acknowledgements (badges, trophies, community-titles)

    * Inclusion of persons with other-abilities and who live in other areas utilizing cutting edge technologies (platform embraces new tools)

* *Tasks:*

    * Research, brainstorming epics and user stories

    * Design UX/UI, NFR/QA, specify business process, and Information Architecture

    * Work on Software architecture, security architecture and deployment architecture

    * Develop the Tech Stack, Architecture Execution Plan and Operationalization Plan

    * Design poster and run Q&A

    * Present!

* *Systems involved:*

    * Cloud architecture

    * Microservice architecture

    * IAM privacy

    * Community module

    * Platform admin interface

    * Learner user interface

    * Data persistence (user profile/data, general learner content: Learning Objectives, discussion board posts)

    * Data analytics for admin, user knowledge, predictive modeling

## **2)** **Key Features and Related Business Processes**

*Key Features:*

* Learning Objective - Application feature that allows flexible creation of big-picture learning goal

* Dashboard - Application feature that allows visual understanding of learning progress, curriculum, access to various platform options with zoom-in/zoom-out capabilities

* Curriculum Builder -Application feature that allows a user to select the steps of learning that will be pursued in achieving learning objective(s)

* Third Party Integration - Application feature that allows for demonstrated learning achieved in other platforms for use in user league & clubs, social community, user profile. User can also share achievements with other platforms.

* Portability - Application feature that allows for utilization with a variety of formats and hardware, from mobile phones to laptops with differing operating systems.

* Accessibility Expansion - Application feature that emphasizes a wide variety of interaction capabilities 

* Learning Application - Application feature that allows a user to apply their learned knowledge in a variety of formats, both using platform-offered options as well as user-initiated ones.

* Learner Engagement - Application feature that dynamically interacts with the user by tracking platform usage and offering methods of keeping user interest alive

* Helper Functions - Application feature(s) that emphasize helper functions built-in to the platform functionality to facilitate ease of use

* Social Network - Application feature that builds opportunities for a learner, if he or she wishes, to engage with other learners who have similar learning objectives.

* Leagues & Clubs - Application feature that adds a competitive and/or community aspect to the user experience as part of adding increased engagement.

* Gamification - Application feature(s) that use working strategies to keep user engagement and interest at a premium

* User Profile - Application feature that allows a user to customize and personalize their online presence on the application platform

* Administrative Tools - Application feature that allows administrators varying IAM access for needed application functionality, smoothing of user experience, and functionality for select community members to take leadership roles within a club or league

*Business Processes:*

* Minimize expense, engage the widest spectrum of potential users as possible

* Minimize human engagement in policing content and creating content, instead using community users as knowledge owners

* Generate innovative ways of implementing learned knowledge through user engagement (i.e. non-profit or individual needing help with x, user creating document or tutorial, user engaging in an activity in the community). 

* Manage new user account set up in terms of password setup, IAM policy for access, 3rd party integration

* Implementation of Machine Learning predictive models using similarities of user profile, learning objective, curriculum content to suggest items of interest or curriculum content

## **3)**  **System Context Diagram** 

![image alt text](image_0.png)

## **4)**  **Epics**

**Epic 01: Learning Target**

User Story 01:  As a learner,I want to create objective, sources, duration

User Story 02:  As a learner,I want to edit, modify attributes

User Story 03:  As a learner,I want the ability to archive Learning Objective 

User Story 04: ( Select recommendations : not in Backlog )

User Story 05: As a learner, I want to be able to publish a learning objective

User Story 06: As a learner, I want to create a LO based on system recommendation

User Story 07: As a learner, I want to be able to rate and comment on LO’s I have used

**Epic 02: Progress Dashboard**

User Story 01: As a learner, I want to be able to access content such as my learning objectives  as a card displaying main information 

User Story 02: As a learner, I want to be able to access curriculum as a card displaying higher-level of curriculum building blocks

User Story 03: As a learner, I want to be able to access a single curriculum module to examine the details and information around that curriculum learning path

User Story 04: As a learner, I want to be able to switch between different views based on filters

User Story 05: As a learner, I want to be able to get more details about my progress and curriculum

**Epic 03: Curriculum Builder**

User Story 01: As a user, can create new curriculum using a given template using community-approved content

User Story 02: As a user, can create unique content using tags

User Story 03: As a user, I can create a new curriculum module/node that can be used by others in the community. For example, reading an article or watching a podcast, and then writing a paper or sharing what has been learned can then be added to Knowledge Pool for usage by other learners.

User Story 04: As an admin, I want to be able to have community experts build the recommended path for a learning objective. 

**Epic 04: 3rd Party Integration**

User Story 01: As a user, I can share a badge or award earned on another platform (Coursera, Udemy, Lynda.com, AWS certification) on my trophy case within the application

**Epic 05: Portability**

User Story 01: As a user I want to be able to access this application on mobile phone, laptops of varying screen sizes and operating systems

**Epic 06: Accessibility Expansion**

User Story 01: As a user with eyesight challenges, I want to be able to view educational content with VR or AR

User Story 02: As a person with particular special needs, I want to be able to control the application and interact with it using voice control 

User Story 03: As a person with color blind vision, I want to have access to color blind mode for increased visual acuity

User Story 04: As a person with visual disabilities, I want to be able to select a different system font

User Story 05: As a user, I want to be able to communicate with individuals from other regions of the world by using texting tools that bridge the communication gap

User Story 06: As an elderly person with knowledge and skills, I want to be able to share my knowledge in very-accessible ways that minimize technological complexity

**Epic 07: Application of Learning**

User Story 01: As a user, I want to be able to put my learned knowledge / experience in new and innovative ways, tutoring and connections

**Epic 08: Engagement**

User Story 01: As a learner, I want to be notified if my deadline set for next objective is approaching, or if I missed a deadline that was declared on curriculum, or if I haven't log in for /two days/, in case I forget my learning things during some busy time.

User Story 02: As a learner, I want to catch up with trending learning resources/learning objectives(e.g. ML is popular right now) by receiving emails(desktop) or receiving notification (phone app), so that I know what type of knowledge and skills is coming in fashion and I could probably consider that as my next learning target.

User Story 03: As an admin, I want to track users' activity data so that I know when to cold/warm follow-up or retain potentially draining users.

User Story 04: As an admin, I want to have a real-time/periodically statistics in terms of what are being discussed on the platform so that I use that to advertise both old and new customers.

**Epic 09: Registration and login**

User Story 01: As an unregistered learner, I want to see a sign-up link on the main page, receive a confirmation email to my registered email address, and guided to new-user landing page

User Story 02: As a registered learner, I want to know all account creating criteria through the registering process.

User Story 03: As an admin, I want to require one click through confirmation email from newly registered learners to ensure register info is valid.

User Story 04: As an admin, I want to define input data fields on a log-in/sign-up screen for a registering learner (e.g. 1.Username(duplicates allowed or not) 2. Password 3. Re-enter Password 4. Security question 5. Security answer)

User Story 05: As an admin, I ask learners to accept the Terms and Conditions before moving on to meet the legacy requirements.

**Epic 10: Helper**

User Story 01: As a new learner who just created an account, I want to be shown a quick and simple guide on the main features of this platform in a logical order (e.g. setting objective first, then building curriculum, then building connections)

User Story 02: As a learner, I want to follow a guide on how to build my own curriculum

User Story 03: As a learner, I want to see hint on all sections of a dashboard/menu/tab

User Story 04: As an admin, I want to offer a helper when a new different devices(desktop, app, AR, other accessible devices) is connected to an account.

User Story 05: As an admin, I give users error messages whenever their action does not meet a requirement.

User Story 06: As an admin, I develop helper to be adaptable to acceptable intelligent devices such as Alexa, Google Home, etc.

**Epic 11: Social Network  / Sharing**

User story 01: As a Learner, I want to create connections with others

User Story 02: As a Learner, I want to see my network (list of connections)

User Story 03 : As a Learner, I want to create a chatroom and invite my connections

User Story 04 : As a Learner, I want to see the top trending LOs in the community (based on filters)

User Story 05 : As a Learner, I can connect to Learners I know from external platforms (LinkedIn, Twitter...Etc)

User Story 06 : As a Learner, I want to broadcast myself to my network

User Story 07 : As a learner, I  want to recognize a Learner for service provided

**Epic 12: Leagues / Club **

User Story 01: As a Learner, I want to be able to register in leagues and compete with other Learners

User Story 02 : As a Learner, I want to be able to create collaboration clubs with other Learners

User Story 03 : As a Learner, I want to be able to compete with other learners in time-based challenges with specific rewards at completion

User Story 04 : As a Learner, I want to have a public discussion space under the League/Club to exchange information and opinions with other Learners

User Story 05 : As a Learner, I want to be able to add/exclude learners from my club

**Epic 13: Gamification**

User Story 01: As a Learner, I want to get rewards (badges, points...etc) for completing specific objectives (learning objective, curriculums, challenges, leagues...etc)

User Story 02 : As a Learner, I want to be able to have progression levels that continually improve as I complete more objectives

User Story 03 : As a Learner, I want to see the reward displayed with each objective

User Story 04 : As a Learner, I want a specific badge/reward after getting x number of recognitions

**Epic 14 : Learner Profile **

User Story 01 : As a Learner, I want to see my personal information profile picture

User Story 02 : As a Learner, I want to see my points, levels, badges/trophy gallery...etc

User Story 03 : As a Learner, I want to change my personal information and profile picture

User Story 04 : As a Learner, I want to hide some of my information from people outside of my network 

**Epic 15 : Platform Administration**

<table>
  <tr>
    <td>User Story 01 : As an admin, I want to track users' activity data so that I know when I should follow up to retain potentially draining users
User Story 02 : As an admin, I want to require one click through confirmation email from newly registered learners to ensure register info is valid
User Story 03 : As an admin, I want to receive content of conversations in the chatbot, and switch it to human assistants whenever possible to offer sufficient help 
User Story 04: As an admin, I want to have a real-time/periodically statistics in terms of trending learning topics/resources on the platform 
User Story 05: As an admin, I want to define input data fields on a log-in/sign-up screen for a registering learner (e.g. 1.Username(duplicates allowed or not) 2. Password 3. Re-enter Password 4. Security question 5. Security answer)
User Story 06: As an admin, I want to create a helper manual that all users have access to
User Story 07: As an admin, I want to ask learners to accept the Terms and Conditions before moving on to meet the legacy requirements
User Story 08: As a Platform Admin, I want to set learning objectives as "archived" for a specific user
User Story 09: As a Platform Admin, I want to see the list of learning objectives per user with all the details and ratings
User Story 10: As a Platform Admin, I want to see a learner's full profile, creation date...Etc
User Story 11 : As a Platform Admin, I want to have the different administration features available (creating/deleting LOs, suspending accounts, adding/removing points...Etc) 
User Story 12 : As a Platform Admin, I want to have access to platform Analytics to track the platform's health, learners activity...Etc
User Story 13 : As a Platform admin, I want to enable multi-factor authentication for Learners
User Story 14 : As a Platform Admin, I want to create time-based challenges with specific rules and requirements (duration, rewards...)
User Story 15 : As a Platform Admin, I want to create the leagues and rules and requirements to be able to join them (topic, duration, learning outcome...Etc)
User Story 16 : As a Platform Admin, I want to change the attributes and metadata of learning objectives by user
User Story 17 : As a Platform Admin, I want to change a Learner's personal information
User Story 18 : As a Platform Admin, I want to be able to reset a Learner's level
User Story 19 : As a Platform Admin, I want to be able to modify or delete a template
User Story 20 : As a Platform Admin, I want to be able to build templates based on specific rules (specific LOs names, specific community ratings...etc)
User Story 21 : As a Platform Admin, I want to be able to add/subtract points/badges...etc to and from specific learners
User Story 22 : As a Platform Admin, I want to add/remove any learner from any League
User Story 23 : As a Platform Admin, I want to add/remove any learner from any Challenge
User Story 24 : As a Platform admin, I want to see each user's network

Epic 16 : Learning Marketplace

User Story 01 : As a Learner, I want to see the different Learning Objectives created by the community, based on areas of learning, duration, sources, ratings...etc</td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
  <tr>
    <td></td>
  </tr>
</table>


## **5)**   **Risks**

 **Privacy**

* Third party integration poses privacy concerns as well as access challenges as the legal and permission environment continues to evolve with prior abuses

* Global regulations around user data privacy needs will need to be navigated (Europe, US, etc) rules and regulations.

* The terms of privacy conflict with 3rd party integration

* Potential user data breach

  **Technical**

* Challenges of the application being cloud-dependent invites the need for data privacy and data security around information security concerns ( need for locked-down implementation, policies)

* Duration for developing the system is too long

* Platform API is not adopted to different types of devices

  **Accessibility/ Inclusion**

* Risk of being too-screen dependent (mobile, laptop) at the risk of not fostering other ways of learning (adaptive technologies).

 ** Quality Control**

* Risk of cross-cultural communication tensions as the application scales to global level

* Risk of intra-platform communication abuses

* NPO offering options for learning praxis

  **Financial **

* Risk of financial non-sustainability without the use of ads

* Administrator liability issues

* The cost of supporting AR and VR can be high compared to the value brought to users. The technical and capital investment on AR and VR development make less sense if the learning contents (e.g. Coursera) themselves don’t support that. (Consistency)

* Lack financial and other resources when building direct content through shared public space learning opportunities for disabled users

** Design **

* User design is not intuitive enough

* Poor user experience (e.g. performance issues, app is slow or lagging, long load times, long registration processes, features are difficult to access)

** Execution**

* Simplicity for special needs (e.g. elder user) is hard to implement

* Poorly executed application launch/onboarding process

* Low-quality or insufficient user data to drive some key features

* Insufficient resources for IoT deployment

 **External Risks**

* Poor level or absence of the user feedback during the testing stage

* Disapproval from 3rd parties/APIs on integration

* Disasters originated from 3rd parties/APIs

 **Administration**

* There is no clear risk owner

* Users’ community involvement violates regulations 

## **6**        **Definitions, Acronyms, Initialisms, and Abbreviations (DAIAs)**

The table/link below contains a collection of Definitions, Acronyms, Initialisms and Abbreviations specific of this project.

* *

<table>
  <tr>
    <td>DAIAs</td>
    <td>Term</td>
    <td>Definition</td>
  </tr>
  <tr>
    <td> </td>
    <td> Learner</td>
    <td>The end user </td>
  </tr>
  <tr>
    <td> </td>
    <td> Platform admin</td>
    <td>The owner of the platform who as administrative privileges </td>
  </tr>
  <tr>
    <td>AR/VR</td>
    <td>Augmented Reality / Virtual Reality</td>
    <td>Cutting edge technologies used in a variety of settings to represent virtual content/visuals</td>
  </tr>
  <tr>
    <td>IoT</td>
    <td>Internet of Things</td>
    <td>Devices capable of transmitting data over the internet</td>
  </tr>
  <tr>
    <td>LO</td>
    <td>Learning Objective</td>
    <td>The smallest component to track a learner’s progress, a learning objective is basically something that a user desires to learn and is defined by many attributes (topic, source, duration...etc)</td>
  </tr>
</table>


