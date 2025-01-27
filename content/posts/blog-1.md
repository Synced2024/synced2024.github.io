+++
date = '2025-01-22T15:38:01-08:00'
draft = false
title = 'Building a Modern App with Flutter: Blog 1'
+++

The current method of sharing an online calendar is very cumbersome. A professor who wants to share his updated office hours needs to spend a lot of time managing that information and how it is found. A group of friends who want to start a club need to share a lot of data about their current schedules which is error prone. What happens if one event changes time? The whole process of figuring out when needs to restart! 

Our Synced App is here to solve that problem.

## The App Concept

For the past few months, our team has been hard at work developing the features which will power our app. These are the following:

- Projects: Projects are the “groups” of the program. They include adding users, removing users, setting goals, and hooks for notifications for completion and project completion notifications.  

- Calendar: The calendar sync feature allows users to share specific availability time slots, link with Google or Outlook (depending on API access), and manage/update work assignments (projects, plans, events, and groups). 

- Notifications: Updates changes in the calendar for all users: send updates on group work/events, new events/groups created, events completed, the schedule being shared, and scheduling updates. 

- Accounts: Basic account management features including account creation, account deletion, login flows, signout flows, settings, and account links. 

To build these features we decided to use the mobile application framework [Flutter](https://flutter.dev/). This lets us target iOS and Android, the leading smartphone operating systems, and provide a path to support web in the future.

# The Technical Implementations

The past week we migrated our previous codebases to a combined repository. This meant we needed to work together to resolve any code errors and deliver a unified experience. We did this by separating the features into four tabs. This allowed us to work on our features and ensure a successful merge. In future sprints, we aim to correct the UX flow.

<!-- {{ $image := $image.Fit "600x400" }} -->
<!-- ![Events page](/images/blog-1-events-page.png "The events page") -->
<img src="/images/blog-1-events-page.png" alt="events" width="200"/>

# A Technical Delema

However, not everything was smooth sailing. There was one disagreeing use of packages in the previous month's work. This let to the use of both the `provider` and the `riverpod` flutter packages. This was problematic as riverpod is the successor to provider and is not compatible. Rewriting the provider code was challenging under such short time constraints.


# The Final Progress

Here is a few screenshots of the various implemented screens:

<img src="/images/blog-1-login-page.png" alt="login" width="200"/>

# The Future Plans

For the next sprint we hope to finish the following features:

1. Calendar view​ - A user is able to view verify their imported calendar view

2. Calendar importing​ - A user is able to import their calendar from either Google Calendar or Outlook

3. QR Code generation - A user is able to generate a QR code from their account to share their calendar

4. Additional UX/UI changes to improve the user experience
