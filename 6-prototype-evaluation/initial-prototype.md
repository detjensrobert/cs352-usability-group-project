---
title: Pest Control Communication
group: Team BBB
author:
  - Robert Detjens
  - Alex Graalum
  - Huy Nguyen

csl: ieee.csl
bibliography: sources.bib

abstract: |
  For the Pest Tracker application, our team created three mobile application designs, each focused on the communication between landlords and tenants surrounding the need for pest control. After multiple design iterations, we have decided on a final concept to iterate on and flesh out. This document details this improved design, and the tests we will use to evaluate its effectiveness.

keywords:
  - TENANT
  - LANDLORD
  - PEST CONTROL
  - COMMUNICATION
  - MESSAGING

header-includes:
  - \usepackage{pdfpages}
---

# Introduction

The Pest Tracking System is a mobile- and web-based application that will ease the coordination between landlords and tenants when the need for pest control arises. Using a preference of either mobile push notifications, automated emails, or both, landlords and tenants can keep in contact about any pests located on the rented property and coordinate the delivery, installation, observation, and disposal of any pest traps required. The application will have an automated reminder system to remind users to keep track of when traps need to be checked or when they need to be replaced. In the case of an emergency, perhaps when a pest situation must be dealt with immediately, the tenant will be able to access a provided list of emergency pest control contacts which will be provided and maintained by the landlord.

Based on interviews and observations of the tenants and landlords, our group have a better understanding about the relationship between the tenants and the landlords. From this understanding, we created three revised designs. After peer feedback on these, we refined and combined our initial prototypes into one concept, presented in this document.

## Prototype URL

[Link to interactive Figma prototype](https://www.figma.com/proto/jtvyDb0Iw8zp9G3xuGY8DW/Concept---Week-6---Evaluation?scaling=scale-down)

# Prototype Description

## 1. Login

The application starts at the login page, prompting the tenant to sign in with their phone number/email and password. They may also choose to sign up, or go through the "forgot password" process.

## 2. Sign Up

The second screen is the sign up page, where the tenant will provide their email address, phone number, and password to create an account with the service. The password is entered twice to confirm it was entered correctly. There is a back button at the top left of the page which will clear the form and return to the login page.

## 3. Landing Page

The main page, shown after logging in or when opening the app if a user is already logged in, provides the tenant with quick actions for the three functions this app provides. These are: file a new report of a pest problem, view previously reported pest problems, or access general communication between the user and their landlord. There is a settings button at the top left which opens the settings overlay.

## 4. New Report

This screen allows the tenant to file a new pest control report. The page requires the user to provide:

- a written description of the issue
- the type of pest being reported via a dropdown menu
- the affected location(s) via a dropdown menu
- attached images of the pest and its location

A back button is located at the top left of the screen which will cancel the report and return to the main page. The confirm button in the top right creates the new report and sends it to the landlord.

## 5. Past Reports

The past reports screen will show the list of all previous pest control reports filed by the tenant, sorted by date. Each report can be selected to view the information in more detail. A back button in the top left corner will return the user to the main page.

## 6. Report Details

This screen will allow the tenant to view what information they provided for the selected pest report. A back button is located in the top left corner which will return the user to the user to the Past Reports page.

## 7. General Chat

This screen will function as a chat application between the user and landlord, much like an IM messenger such as Discord or Slack. Messages from the landlord and tenant are shown in different colors as to easily distinguish between users. There is a text box at the bottom of the page for the tenant to compose new messages, and an attach button (the paperclip) will open a file selector to attach files to the message.

## 8. Settings

This state is an overlay that appears on the main page. The tenants name and profile picture are displayed at the top, with an option to edit their information below. A following button will take the tenant to the past reports page. The overlay can be closed by tapping outside the overlay or via the back button located at the top right.

## 9. Settings Logout Confirmation

This state exists between the setting state and the login page. Its purpose is to keep the tenant from accidentally logging themselves out of the application when in the settings state by asking for a confirmation of their choice.

## 10. Help Page

The help page is a collection of resources for the user in regards to the application. There is an FAQ that will open to a website with a list of frequently asked questions. Contact Support will open the user's email program to send an email to the developers.

# Usability Test Plan

To evaluate the effectiveness of this app prototype, the team will be conducting user observations to observe how effective our application is, and whether our functionalities require improvements. In order to achieve this usability testing, the team will be observing how participates react when using the prototype, and have the participants share their thoughts about the application after the evaluation. Additionally, we will record any issues from the participants' experiences in order to identify the parts of the applications that users have trouble with. The team will ask the participant a questionnaire after the evaluation. The end goal of this usability testing will be identifying the portions of the app that hinder the user experience. With this in mind, the team will have different components for usability testing purposes.

**Components:**

- Research Subjects

- User Scenarios

- User Tasks

- Research Methods

## Research Subjects

Currently, our team are planning to conduct usability testing with three subjects from our target audience. These subjects are college students, considering many are living out of campus and live under contract with a landlord. By conducting usability testing with the subjects, the constant communication between the subjects and the team will allow accurate feedback on the application. Subjects will be recruited through an existing university social media community on Discord.

Due to the current complication with COVID-19, the usability testing will be conducted remotely to ensure safety for both the subjects and the team. The testing will be done with the Figma prototype detailed previously in this report and the Appendix. As this will be delivered remotely, the meeting will be held through Zoom or Discord to allow for the participants and the Team to interact. Additionally, the subjects will be asked to share their screen while interacting with the prototype in order to show how they interact with the prototype. Before the evaluation, the subjects will be asked for consent to perform and record the evaluation so the team can use the session for analysis.

## User Scenarios and Tasks

- Filing a new pest report

- Accessing past pest reports using two different methods

## Research Methods

For testing usability, we will be using post-test questionnaire and critical thinking as our research methods. By having
the participants express their thoughts as they go along it will give us insights into the mental model they have of the
application. We can see where they are successful and where they struggle along the way instead of relying on their
recall at the end. In addition we will ask questions at the end to make sure we cover certain areas if the user didn’t
report anything about them during the experiment.

- Post-test Questions:

1. What are your thoughts on our application?
2. Would you use this application if it was available for your device?
3. What are your thoughts on our screens?
4. How did using the app make you feel?
5. What did you think about how long it took you to complete the tasks?
6. Which screens did you like the best or least?
7. If the app was designed specifically for you what would you like to see in it?
8. If a person you know was using the app what do you think that they would like to see in it?
9. What changes would you like to see?
10. What would make you want to use the app more?
11. What are your thoughts on the colors used in the app?
12. What did you think about the icons in the app?
13. What are your thoughts on the organization/layout of the screens?
14. What are your thoughts on the name of the application?
15. What do you think about the size of the font used?
16. Is there anything else you would like to share about the app?

# Heuristic Evaluation Plan

In addition to the user testing in the Usability Test Plan, we also plan to invite multiple experts to evaluate and review the function of our application. We will be using the following heuristic evaluation criteria, adapted from @heuristics. Our experts will evaluate how well our prototype design follows these attributes:

## Visibility of System Status

The design of this app should provide feedback or otherwise notify the user on the state of the app. The app should not leave users guessing as to what the app is doing, but provide clear feedback on any action the app is taking, such as showing a loading icon or progress bar. This allows the user to feel in control of what is happening and feel that the app is reacting to their actions.

## Match System and Real World

The design of this app should mirror how interactions work in the real world. This means using familiar language, icons, and conventions in a way that matches how users are expecting the interface to work. Users expect a question mark icon to designate some form of help menu, or a check icon to confirm something.

## User Control and Freedom

The design of the app should have a clear and easy way for users to back out of an action. Users make mistakes, and the interface needs to be designed in such a way that when the user does make a mistake, the erroneous action can be undone. This lets users feel in control of their actions and prevent them from feeling stuck.

## Consistency and Standards

The design of this app should follow industry conventions and maintain consistency both within the app and with other interfaces. This reduces the "cognitive load" [@heuristics] on users and does not make them learn a completely new interface.

## Error Prevention

The design of this app should be aware that users commonly make unintentional mistakes and provide clear defaults and error messages to help the user recognize the accidental error, and learn to perform correctly in the future.

## Recognition, not Recall

The design of this app should keep information visible and not force the user to commit things to memory. A user should be able to find what they are looking for without having to remember what page of the app the information is present on and go hunting for it, forcing the need to remember where everything is location and how to get there. Information should be presented on all pages where it is needed, and locations should be easily recognizable and quick to navigate to.

## Flexibility and Efficiency

The design of this app should provide shortcuts and customization for power users. This allows the interface to be simplifed by default for novice users while still allowing experts to quickly move about the interface at the speed they want.

## Aesthetic and Minimalist

The design of this app should focus on the content rather than the UI. Users are using the application to interact with the service this app is presenting, not with how the UI of the app looks. The design should not distract or get in the way of the content being presented.

## Recognize, Diagnose, and Recover from Errors

The design of this app should present clear and understandable error messages to the user and show them how to fix the problem. When users interact with the interface incorrectly, the app should provide clear and actionable feedback on what the error was so the user understands what exactly they did that was wrong.

## Help and Documentation

The design of this app should ideally not need any external documentation, being self-explanatory; if documentation is needed, it should be clear and concise. The help should also be provided in context so the user can quickly access the relevant documentation for elements of the interface they are unclear on.

\pagebreak

# References

\small

::: {#refs}
:::

# Appendix

## Design Frames

\begin{minipage}{\textwidth}
  \includepdf[pages={1-},scale=0.63,nup=4x3,delta=2em 2em,offset=0px -9em,frame]{figma-frames.pdf}
\end{minipage}
