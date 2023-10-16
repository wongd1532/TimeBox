# TimeBox
A web app calendar web app that facilitates nested calendar events, shareable calendar templates, and command line operability.

## About the Project
TimeBox is currently under development by a team of 7 student engineers and designers. TimeBox is a prospective startup so due to the proprietary nature of the project, the source code is currently not available to the public.

The TimeBox team uses the following technologies:
- Figma for user flow and wireframe prototyping
- BitBucket repository for source control
- Jira for issue tracking and assignment
- Atlassian Confluence for documentation and project design
- React Bootstrap framework for frontend
- Django REST framework for backend

## Current State
### Login
Users are required to login. Upon submitting a user's credntials, they're routed to the calendar page.
![login](https://github.com/wongd1532/TimeBox/assets/99998284/688b4c19-b0e4-4171-96af-3bcf1b2bd973)
### Calendar
The calendar reflects the current month and week of the user's local time. Dummy event data stored in the backend is requested and is rendered in the calendar grid.
![calendar](https://github.com/wongd1532/TimeBox/assets/99998284/38dbf670-ab05-4b06-887b-beb803c9517b)
A number of pages (stopwatch, analytics, register, profile) are in the early stages of development.

## My Contribution
I began working on TimeBox in May with no previous project experience. I had some computer science fundamentals from intoductory computer science courses, but no practical development experience. I began by learning about the [Git workflow]([url](https://www.atlassian.com/git/tutorials/comparing-workflows)) and various technologies for developing frontend and backend features.
### Frontend - Right bar
I learned about React Bootstrap's grid system, vertical stacks, buttons, and how to use .svg files in React to code this feature. The buttons are functional routes to the stopwatch and analytics page.
![calendar - right bar](https://github.com/wongd1532/TimeBox/assets/99998284/c7bb66f5-b8a6-4464-b667-47167f432ef7)
### Frontend - Create button
![calendar - Create](https://github.com/wongd1532/TimeBox/assets/99998284/0cb8ecf3-a0b5-4d1c-9ec2-84622ad04d04)
I used what I had previously learned about buttons and .svg files to code this feature. I also learned about modals, form, and input to create what will be the basis of TimeBox's command-line interface.
![calendar - create modal](https://github.com/wongd1532/TimeBox/assets/99998284/967e2a11-fb3f-422c-8dc7-39a490a1ea0b)
### FullStack - Moving Frontend Dummy Event Data to Backend (API)
The dummy event data was previously housed in a frontend .jsx file. To move the dummy data to the backend, I learned about axios html requests and responses to pull the dummy data from an APIView. The next step in this feature is to write models and serializers to house event data in the database.
### Database Design
As we continue to roll out new features, our database design is constantly evolving and changing to accomodate these new features. I am learning about database design, ERDs, and database normalization to design and structure a robust and efficient database.
![erd](https://github.com/wongd1532/TimeBox/assets/99998284/46a87987-4d7f-4209-a943-102073d05d3f)
