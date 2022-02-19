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

# Prototype Summary & Revisions

# Usability Test Plan

To evaluate the effectiveness of this app prototype, the team will be conducting user observations to observe how effective our application is, and whether our functionalities require improvements. In order to achieve this usability testing, the team will be observing how participates react when using the prototype, and have the participants share their thoughts about the application after the evaluation. Additionally, we will record any issues from the participants' experiences in order to identify the parts of the applications that users have trouble with. The team will ask the participant a questionnaire after the evaluation. The end goal of this usability testing will be identifying the portions of the app that hinder the user experience. With this in mind, the team will have different components for usability testing purposes.

**Components:**

- Research Subjects

- User Scenarios

- User Tasks

- Research Methods

# Usability Test

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

# Heuristic Evaluation

# Evaluation Results

# Insights/Design Recommendations

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
