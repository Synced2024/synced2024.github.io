+++
date = '2025-03-04T5:38:01-08:00'
draft = false
title = 'Building a Modern App with Flutter: Blog 3'
+++

In our previous blog, we discussed what would be worked on in the **Synced App**. Since then, our team has made great progress towards reaching our MVP through our updates.

This blog will give insight into the app’s **current features and improvements** while discussing **what’s coming next**.

---

##  **Current Features and Improvements**

### **Calendar**

- **Refactored Sign-In Flow:** Users can now add their calendars through our syncing feature by adding their email to the app. This is the only way the app can access the user's information so that there isn't a chance of a data leak.

- **Website Creation:** We've created a website that connects to our firestore so that we can use a web version of the app to test our two use cases.

- **Synced Calendar View** We've connected our syncing page with our calendar so that it is all on the same page. This allows users are able to see their calendar update with its new projects added without having to change screens.


### **Projects**

- **Restyled Project Page** We've restructured the projects page to be what the final look will be. It now displays all created projects for the user as well as allows the creator of the project to set a single or recurring time for each project. 

- **QR Share Button** We've added a share button that is inside each created project that allows users to either email or send a QR code to others to join their project.

- **QR Schedule Moved** We moved the scannable QR schedule code to a widget to help declutter the page.


### **Future Improvements and Features**

For our next **sprint**, we aim to develop these key features:

- **Finish Profile View** as well as save the user's email to the provider.

- **Create Algorithm to Update Calendar** so that when new projects are made and edited, the saved changes are shown in the calendar and for those that sync the changes to their calendars.

- **Notify Group of Calendar Changes** so that the changes to the user's calendar do not go unnoticed.

- **Connect QR code to Project** so that we can see user's calendars update with their added projects.


Stay tuned for our **next update** as we work to **finalize the Synced App** 