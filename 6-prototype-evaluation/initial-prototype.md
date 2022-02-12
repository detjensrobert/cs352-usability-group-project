---
title: Pest Control Communication
group: Team BBB
author:
  - Robert Detjens
  - Alex Graalum
  - Huy Nguyen

csl: ieee.csl
# bibliography: example.bib

abstract: |
  stuff

keywords:
  - TENANT
  - LANDLORD
  - PEST CONTROL
  - COMMUNICATION
  - MESSAGING
---

\pagebreak

# Introduction

The Pest Tracking System is a mobile- and web-based application that will ease the coordination between landlords and tenants when the need for pest control arises. Using a preference of either mobile push notifications, automated emails, or both, landlords and tenants can keep in contact about any pests located on the rented property and coordinate the delivery, installation, observation, and disposal of any pest traps required. The application will have an automated reminder system to remind users to keep track of when traps need to be checked or when they need to be replaced. In the case of an emergency, perhaps when a pest situation must be dealt with immediately, the tenant will be able to access a provided list of emergency pest control contacts which will be provided and maintained by the landlord.

Based on interviews and observations of the tenants and landlords, our group have a better understanding about the relationship between the tenants and the landlords. From this understanding, we created three initial design concepts with different focuses on the relationship. These were later improved upon with peer examination and feedback.

# Prototype Description


# Prototype Screens/States

**1. Login**

The application starts at the login page, prompting the tenant to sign in with their phone number/email and password. They may also choose to sign up, or go through the "forgot password" process.

**2. Sign Up**

The second screen is the sign up page, where the tenant will provide their email address, phone number, and password to create an account with the service. The password is entered twice to confirm it was entered correctly. There is a back button at the top left of the page which will clear the form and return to the login page.

**3. Landing Page**

The main page, shown after logging in or when opening the app if a user is already logged in, provides the tenant with quick actions for the three functions this app provides. These are: file a new report of a pest problem, view previously reported pest problems, or access general communication between the user and their landlord. There is a settings button at the top left which opens the settings overlay.

**4. New Report**

This screen allows the tenant to file a new pest control report. The page requires the user to provide:

- a written description of the issue
- the type of pest being reported via a dropdown menu
- the affected location(s) via a dropdown menu
- attached images of the pest and its location

A back button is located at the top left of the screen which will cancel the report and return to the main page. The confirm button in the top right creates the new report and sends it to the landlord.

**5. Past Reports**

The past reports screen will show the list of all previous pest control reports filed by the tenant, sorted by date. Each report can be selected to view the information in more detail. A back button in the top left corner will return the user to the main page.

**6. Report Details**

This screen will allow the tenant to view what information they provided for the selected pest report. A back button is located in the top left corner which will return the user to the user to the Past Reports page.

**7. General Chat**

This screen will function as a chat application between the user and landlord, much like an IM messenger such as Discord or Slack. Messages from the landlord and tenant are shown in different colors as to easily distinguish between users. There is a text box at the bottom of the page for the tenant to compose new messages, and an attach button (the paperclip) will open a file selector to attach files to the message.

**8. Settings**

This state is an overlay that appears on the main page. The tenants name and profile picture are displayed at the top, with an option to edit their information below. A following button will take the tenant to the past reports page. The overlay can be closed by tapping outside the overlay or via the back button located at the top right.

**9. Settings Logout Confirmation**

This state exists between the setting state and the login page. Its purpose is to keep the tenant from accidentally logging themselves out of the application when in the settings state by asking for a confirmation of their choice.

**10. Help Page**

The help page is a collection of resources for the user in regards to the application. There is an FAQ that will open to a website with a list of frequently asked questions. Contact Support will open a shortcut to **do the thing**.

# Usability Test Plan



# Heuristic Evaluation Plan



\pagebreak

# Appendix
