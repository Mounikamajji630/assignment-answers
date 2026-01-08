# assignment-answers
some of the important question and answers
a) Research and summarize the benefits of using a decoupled architecture (React frontend + Django REST backend) for a non-profit organization. You can also express if something else is better. 
solution for this :
Decoupled architecture means the frontend and backend are developed seperately
Using React for frontend and Django REST for backend is useful for a non-profit organization because:
It gives a better and faster user experience
The website becomes easy to maintain and update
Frontend design changes do not affect backend logic
The system can grow in the future (more users, features)
It is cost-effective because both React and Django are open-source

Visit the current development site: dev.bharatyuva.org
b) UI/UX Audit: List 3 major frontend flaws in the current design that impact user experience.
UI/UX Issues Identified:
Poor content hierarchy on the homepage
Complex and cluttered navigation menu
Outdated design with low user engagement

Database Management: How do you handle a "Migration Conflict" in Django when multiple developers are working on the same database schema?
A migration conflict occurs when multiple developers create migrations for the same app.
It is resolved by pulling latest changes, running makemigrations --merge, reviewing the merge migration, and applying it.


 API Integration: In a Django + React setup, how would you handle Cross-Origin Resource Sharing (CORS) issues?
Use CORS_ALLOW_ALL_ORIGINS = True only in development

Always specify allowed domains in production

Use HTTPS in production

Combine with proper authentication (JWT, sessions)
