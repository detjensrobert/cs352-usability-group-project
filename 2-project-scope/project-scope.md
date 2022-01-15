---
header-includes:
  - \usepackage{setspace}
  - \doublespacing
fontsize: 12pt

numbersections: true

title: CS 352 Project Scope
author:
  - Robert Detjens
  - Alex Graalum
  - Huy Nguyen
---

# Team Details

|                        Team BBB |        |
| ------------------------------: | ------ |
|       Leadership and Management | Robert |
| User Research and Communication | Alex   |
|       UX Design and Prototyping | Huy    |
|        Writing and Deliverables | Robert |

# Project Description

## Project Vision

Our team wants to build an app that will make it easy for tenants and landlords to coordinate bedbug traps. This system
will be used for landlords to order traps to be sent to their tenants, and for the tenants to submit pictures of the
used traps to the app to be forwarded to their landlord.

This application is focused around the traps ordered from the service, as these have a unique barcode on them that will
link it to the landlord who ordered it. When the tenant takes a picture of the trap, the application will read the
barcode and use that to forward the image to their landlord.

There are 3 main screens for this app, with several supporting screens for each:

- Account management
  - Login & signup flow: Landlords will need an account for the service to associate traps with.
  - Account dashboard: This page will show all currently-deployed traps a landlord has ordered and had delivered to
    tenants.
  - Account settings page: The landlord needs some way to configure their locations and ordering information.
- Trap management
  - Trap ordering flow: Traps need to be ordered for delivery, with options for the quantity and delivery location for
    each batch of traps.
  - Trap location configuration page: If not configured when ordering, a landlord will need to associate each trap with
    a property, and possibly a room in the property if the tenant provides that information.
  - Submitted image page: The landlord needs to have a way to view the pictures submitted by tenants in order to examine
    them for bedbugs.
- Tenant submission
  - Image upload page: The tenant needs a way to submit the image
  - Trap feedback page: The landlord needs a way to leave feedback on submitted traps, such as whether there is a
    problem with the picture or if it does indeed have bedbugs and what the next steps will be to resolve that.

## Usability Problems

Landlords who have properties with bedbug problems need to coordinate with the tenants living there for inspections
and/or to setup traps. While possible, having the landlord come in to your apartment every month to do an inspection is
a big pain. This service would make it easier for landlords to send labeled traps to tenants, and for the tenants to
send pictures of the traps back to their landlord for remote inspection.

## Target Audience

This app is targeted at landlords who lives in a climate with massive influxes of bedbugs, or had a previous history
with bedbugs; i.e. landlords with known-high-risk properties. Additionally, the tenant portion of this application is
targeted at all tenants, who may or may not be technologically savvy. Thus, the client portion should be as simple as
possible.

## Facts & Assumptions

This application is meant to be used cooperatively between a landlord and a tenant. We must then assume that the
application will be used by either someone who owns property or is renting property. Our application will need two
different views to present information to the user, depending on their position in the landlord/tenant relationship. The
application will also be designed as a smartphone app, requiring the ownership of a smartphone by the landlord and
tenant. If the landlord and the tenant own a smartphone, they are assumed to be knowledgeable enough to use smartphone
applications, as well as take, access, and send pictures using their smartphone.

In order to use and register with the application, the landlords will have to provide proof of ownership of properties
in order to gain use of the landlord portion of the application, and tenants will only need to submit pictures of their
traps.

## Merit & Contributions

Bedbugs are hard to track, and will become a large and expensive problem if left to become a problematic infestation.
Small occurrences can be mitigated with traps, but for a landlord to track which tenants are currently have bedbug
problems is tricky. While traps are primarily used for mitigation, using smaller traps to catch bedbug infestations in
their early stages can be useful in preventing a much bigger problem.

## Team Success

In order to create a successful project, we created a plan and todo list to keep track of the progress. We will define a
weekly deliverable for the project so we can steadily plan ahead on what needs to be done. We will be meeting up weekly
to work on the tasks for the week, with further individual work as needed. While we have setup specific roles for each
member, all of us will help each other with their task if needed.
