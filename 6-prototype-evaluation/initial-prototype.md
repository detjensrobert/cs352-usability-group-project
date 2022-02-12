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

The application starts at the login page, prompting the tenant to sign in with their phone number and password. They may also select the sign up option, or start the password recovery process.

**2. Sign Up**

The second screen is the sign up page where the tenant will provide their email address, phone number, and password. The password is entered twice to confirm the tenants password creation. There is a left facing arrow button at the top left of the page which will remove entered information and go back to the login page.

**3. Landing Page**

The main page, which is shown after logging in, provides the tenant with options to file a new report of a pest problem, view previously reported pest problems, or access general communcation between the landlord and themselves. There is a settings button at the top right which opens the settings overlay.

**4. New Report**

This screen allows the tenant to file a new pest control report. The page requires the user to provide:
- what type of pest is being reported via a dropdown menu
- a written description of the pest for visual aid
- a written description of the pests location on the property
- attached images of the pest, its location, and other relevant pictures
The send report button is in the top right which will send the report and then return to the main page. A left facing arrow button is located at the top left of the screen which will remove entered information and return to the main page.

**5. Past Reports**

The past reports screen will be an archive of the previous pest control reports that have been filed by the tenant. Each report can be selected to view the information in more detail. A left facing arrow button is located in the top left corner to return to the main page.

**6. Report Details**

This screen will allow the tenant to view what information they provided for the selected past report. A left facing arrow button is located in the top left corner to return to the page which lists all past reports.

**7. General Chat**

This screen will function like a normal texting application

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