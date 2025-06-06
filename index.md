# Background and Getting Started 
  Welcome! The primary goal of this site is to communicate progress on a summer-long project whose purpose is twofold: build professional skills and explore my current interests and goals. Read on for weekly updates to this end to see this project's genesis to completion. The first post will serve to outline the scope of the project. Following posts will describe weekly progress, lessons learned, and insights into the build process. 
  
# Project Proposal 
Project Proposal – Matter.js Games with AWS Integration
Vision Statement
This project’s scope includes building a web application that leverages React for the frontend, AWS for backend services written in Java (Cognito for user authentication and S3 for storage/retrieval), and Matter.js for rendering simple physics-based games including Pong, Flappy Bird, and Pool.

The application will allow users to:

Log in

Play games

Track scores on a personal dashboard

All of these technologies are new to the author, so in addition to researching and learning new languages and frameworks, this will enhance professional skills in:

Full-stack web development

Game physics implementation

Cloud architecture

User experience design

Software lifecycle management

Motivation
By providing simple, interactive games with accessible, clearly defined logic and results displayed on a centralized dashboard, this project aims to provide both entertainment and learning.

Matter.js allows fine-tuning of physical constants.

Users can toggle these settings to understand how physical laws describe reality.

A friendly UI and visual feedback aim to bridge the gap between gameplay and learning physics.

From a development perspective, it serves as a proof of learning in:

Cloud computing

Web development

Game logic

Systems integration

Risks to Completion
Several risks could impact the project, ranked by priority:

Scope Creep – Expanding features too early can lead to delays.

Integration Complexity – Connecting the frontend to AWS may present challenges.

Performance Limitations – Rendering issues may occur with Matter.js.

Authentication Errors – Misconfigured AWS Cognito can break access.

Time Management – Balancing work between game logic, backend, and UI can be difficult.

Mitigation Strategies
Risk	Mitigation Strategy
Scope Creep	Limit games to the three proposed; focus on minimum viable product (MVP).
Integration Complexity	Review AWS documentation and test each component in isolation before integrating.
Performance Limitations	Simplify UI elements and focus on core physics functionality.
Authentication Errors	Follow AWS best practices; test auth flows early.
Time Management	Use a weekly roadmap with clear milestones. Prioritize MVP consistently.

Evaluation Criteria
Category	Criteria
Functionality	Users can log in, play all three games, and view a score dashboard.
Integration	AWS services (Cognito, S3, API) work seamlessly with React and Java backend.
Code Quality	Modular, readable code with testing and edge case handling.
UI/UX Design	Clean, intuitive, and visually cohesive interface.
Bonus	Allow users to toggle physical constants and save preferences.

Project Schedule
The schedule allows one extra buffer week if needed.

Week	Dates	Focus	Milestones / Tasks
Week 1	June 6 – June 13	Project Setup & Planning	- Finalize game rules and app structure
- Initialize React app with routing
- Set up Java backend structure
- Test Matter.js integration
Week 2	June 14 – June 20	Game Prototypes	- Build basic Pong, Flappy Bird, Pool logic
- Set up score state in React
- Render game scenes with Matter.js
Week 3	June 21 – June 27	AWS Cognito Auth Integration	- Set up AWS Cognito user pool
- Implement login/signup/logout in React
- Protect game/dashboard routes
Week 4	June 28 – July 4	Backend API & Score Storage	- Create REST API endpoints (Java)
- Set up DynamoDB or RDS
- Deploy backend to AWS
- Token-based API access
Week 5	July 5 – July 11	Score Sync & Dashboard	- Send score to backend after each game
- Build dashboard with score history
- Add basic analytics
Week 6	July 12 – July 18	Game Logic & Reset Flows	- Polish physics and collisions
- Add start/reset logic to games
- Refactor shared game logic
Week 7	July 19 – July 25	UI/UX Styling	- Improve layout using Tailwind or similar
- Style dashboard and game pages
- Add responsive design
Week 8	July 26 – August 1	Testing & Optimization	- Write unit/integration tests
- Optimize Matter.js rendering
- Handle auth and network errors
Week 9	August 2 – August 8	Final Integration & Deployment	- Deploy frontend (Amplify/S3/Netlify)
- Final bug fixes
- Document app
- Run demos/user tests
