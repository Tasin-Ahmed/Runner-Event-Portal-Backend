
# Runner Event Portal-Backend

This website is built for a running community that wants to showcase its members, teams, and sponsors in a professional and engaging way. The primary goals are to promote the community, attract potential sponsors, and highlight past and upcoming events.

In addition to marketing, the website will serve several practical functions—such as providing runner IDs for event participants, distributing event certificates, and sharing event photos. Since the platform will handle a large number of images and downloadable files, it will be optimized for high media volume and file management.

## Features

- **Admin Authentication & Role Management:** Secure login system with role-based access control for managing admin-level permissions.
- **Participant Ticket Upload System:** Admins can upload pre-generated Runner ID tickets (PDF or image format) to the system, organized by event, for runners to download prior to participation.
- **Certificate Management System:** Admin panel to upload certificate and generate downloadable certificates post-event.
- **Event Management Module:** Create, update, and manage event details including dates, locations, participating teams, and registration info.
- **Team & Member Directory:** Database-driven system to store and manage profiles of teams with edit and approval workflows.
- **Sponsor Management:** CRUD functionality for sponsor listings including logo uploads, website links, and visibility settings.
- **Media Upload & File Handling:** Robust file handling system to upload, store, and serve high-resolution images and downloadable content efficiently.
- **API for Frontend Integration:** RESTful APIs to provide structured data to the frontend for real-time rendering of runners, teams, certificates, and galleries.
- **Data Security & Validation:** Input validation, file type restrictions, and secured endpoints to ensure safe and clean data entry.
- **Scalable Database Structure:** Optimized schema design to efficiently handle growing numbers of events, users, and media files.
- **Admin Dashboard:** A centralized admin dashboard for managing all backend processes, including user management, event data, and media uploads, with reporting tools for easy data visualization.
- **Scalable Infrastructure:** Built on a scalable backend architecture to handle increasing data volume, user traffic, and the addition of future features without compromising performance.

## Tech Stack

**Server:** Node, Express

**Database:** MongoDB, Mongoose ODM
## Acknowledgements

 - [Node JS Documentaion](https://nodejs.org/docs/latest/api/)
 - [Express ](https://expressjs.com/)
 - [Npm packages](https://www.npmjs.com/)
 - [Mongoose](https://mongoosejs.com/)

## Versions
- **Node:** v22.16.0
- **Npm:** 11.4.1
## Installation

Setting up the Project with npm
```bash
  npm init
```
Initializing Git Repo
```bash
  git init 
```
    