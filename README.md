# SOEN_341
SOEN 341 — Event Management & Ticketing Web App (Team Project)

Bouchera Hazzab (40282895) @bouchera2,

Nkrumah Leugoue Nougoue (40258711) @LNN10,

Elizabeth Tremblay (40117481) @liztremblay,

Mahdi Djellab (40254945) @rabzouuuz,

Elias Nasrallah (40233118) @Eliasn20,

Georgy Khoder (40248521) @Georgii77,

Mohammed Mrani Alaoui (40279836) @momrania,

M-Amar Kseibi (40276594) @3Ammar3

## <ins>Language and techniques </ins> 

Backend: Node.js, Express.js, Typescript, Firebase Admin SDK, RESTful API architecture

Database: FireBase Firestore, Firebase authentication, Firebase Cloud storage

Framework for the backend: React

Frontend: TypeScript, JavaScript, CSS, HTML, Axios/ fetch API, 

Framework for the frontend: React, Bootstrap

# Project Description
You are implementing a Campus Events & Ticketing Web Application designed to help students discover, organize, and attend events on campus. The system enables students to browse events, save them, claim free or paid tickets, and check in using QR codes. Organizers can create and manage events, track attendance, and access analytics through dashboards, while administrators moderate content and oversee organizations. The application streamlines event management, improves student engagement, and provides valuable insights for both organizers and campus administration.

As an example, you can take a look at: https://www.campusgroups.com

## **Core Features** 
We identify three primary users: Students, Organizers, and Administrators.

**1. Student Event Experience**

<ins>Event Discovery</ins>

 -Browse and search events with filters (date, category, organization).

<ins>Event Management</ins> 

 -Save events to a personal calendar.
 
 -Claim tickets (free or mock paid).
 
 -Receive a digital ticket with a unique QR code.


**2. Organizer Event Management**

<ins>Event Creation</ins>

 -Enter event details: title, description, date/time, location, ticket capacity, ticket type (free or paid).

<ins>Event Analytics</ins>

 -Dashboard per event with stats: tickets issued, attendance rates, and remaining capacity.

<ins>Tools</ins>

 -Export the attendee list in CSV.
 
 -Integrated QR scanner for ticket validation (for simplicity, you can assume the QR code image can be provided via file upload).

**3. Administrator Dashboard & Moderation**

<ins>Platform Oversight</ins>

 -Approve organizer accounts.
 
 -Moderate event listings for policy compliance.

<ins>Analytics</ins>

 -View global stats: number of events, tickets issued, and participation trends.

Management
 -Manage organizations and assign roles.

## Additional Feature
### AI Chatbot

 Users will have access to an AI chatbot which will give information about the events and can recommend events based on the users database. The AI will save users information to personalize the answers to the user. 

## My Contributions

- Managed GitHub issues and sprint workflow
- Worte user stories + acceptance criteria
- Documented feature behavior and edge cases
- Built organizer dashboard UI components (React)
- Fixed bugs and improved UI/UX consistency
- Implemented Export Attendee List to CSV (Issue #14)
- Added CVS Export Trigger in Frontend (#69)
- Debugged and implemented user role assignment and user ID handling (Fix for Issue #111)
- Participated in implementing claim ticket flow (Issue #8)
  

## How to Run
Frontend
- cd frontend 
- npm install 
- npm start (runs on https://localhost:3000)
Backend
- cd backend 
- npm install
- Add Firebase Admin SDK private key (for local deployement) to seviceAccountKey.json
- npm run dev (runs on https://localhost:3002)
