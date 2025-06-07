# Project Proposal 
Project Proposal – Matter.js Games with AWS Integration

__Vision Statement__
This project’s scope includes building a web application that leverages React for the frontend, AWS for backend services written in Java (Cognito for user authentication and S3 for storage/retrieval), and Matter.js for rendering simple physics-based games to include Pong, Flappy Bird, and Pool. The application will allow users to log in, play games, and track scores on a personal dashboard. All of these technologies are new to the author, so in addition to researching and learning new languages and frameworks, this will enhance professional skills in full-stack web development, game physics implementation, cloud architecture, user experience design and software lifecycle management.

__Motivation__
By providing a simple, interactive games with accessible, clearly defined logic with results displayed on a centralized dashboard, this project should provide entertainment to the user. Additionally, Matter.js can be fine-tuned to different physical constants. Allowing the user to toggle settings should provide a means to build a sense of how these constants and other physical laws describe reality. In short, it aims to bridge a gap between gameplay and learning physics. It will aim to do so through a friendly UI and clear visual feedback. Lastly, cloud integration will serve to make the experience one that user’s can return to. For the author, it will serve as a project that demonstrates a willingness to learn new skills in cloud computing, web development, game logic and systems integration. 

__Risks to Completion__
There are several risks to this project. In rank order, these include scope creep, integration complexity, performance limitations, authentication errors, and time management. Expanding features early could result in significant delays if there are unexpected delays or unforeseen complexities in execution. There are several technologies that need to be integrated and doing so may not be straightforward or seamless. Specifically, connecting the frontend to AWS services might include time-consuming issues. Related are authentication errors. The choice to use AWS for authentication means that configuration is key and small errors could mean complete failure to authenticate properly. Lastly, balancing workloads between the frontend, backend, and game logic implementation will take real planning efforts and dedicated workloads. 

__Mitigation Strategies__
Scope creep can be mitigated by limiting the type and number of games offered on the platform. The games listed above have well-defined logic and physics associated with them. While it may be tempting to add more, the minimum-viable product will include these three. Integration complexity can be lessened with proper review of relevant AWS documentation, free online trainings, and testing each piece in isolation before combining them. Matter.js might see issues with rendering objects in game leading to performance issues. Writing games with very simple UI characteristics that still capture core functionality can serve to mitigate this risk. Lastly, time management can be mitigated through a weekly development roadmap with real milestones included. Throughout, the minimum viable product will be prioritized. See below for a schedule.

__Evaluation Criteria__
Functionality, integration, code quality, and UI/UX design can serve as evaluation criteria. If users can log in, play all three games, and see their dashboard with updated scores, the project can be said to be functional. A bonus or stretch feature will be to toggle physical constants or characteristics, save those, and run the games in different modes. If React and AWS technologies work together to create this functionality, it will be a success. Code quality will be a part of this effort as well. Edge-cases should be well-defined and tested. Lastly, a simple but intuitive UI/UX should showcase these technologies working together well. 

The schedule allows one extra buffer week if needed.

| Week   | Dates               | Focus                         | Milestones / Tasks                                                                 |
|--------|---------------------|-------------------------------|-------------------------------------------------------------------------------------|
| Week 1 | June 6 – June 13    | Project Setup & Planning      | - Finalize game rules and app structure<br>- Initialize React app with routing<br>- Set up Java backend structure<br>- Test Matter.js integration |
| Week 2 | June 14 – June 20   | Game Prototypes               | - Build basic Pong, Flappy Bird, Pool logic<br>- Set up score state in React<br>- Render game scenes with Matter.js |
| Week 3 | June 21 – June 27   | AWS Cognito Auth Integration  | - Set up AWS Cognito user pool<br>- Implement login/signup/logout in React<br>- Protect game/dashboard routes |
| Week 4 | June 28 – July 4    | Backend API & Score Storage   | - Create REST API endpoints (Java)<br>- Set up DynamoDB or RDS<br>- Deploy backend to AWS<br>- Token-based API access |
| Week 5 | July 5 – July 11    | Score Sync & Dashboard        | - Send score to backend after each game<br>- Build dashboard with score history<br>- Add basic analytics |
| Week 6 | July 12 – July 18   | Game Logic & Reset Flows      | - Polish physics and collisions<br>- Add start/reset logic to games<br>- Refactor shared game logic |
| Week 7 | July 19 – July 25   | UI/UX Styling                 | - Improve layout using Tailwind or similar<br>- Style dashboard and game pages<br>- Add responsive design |
| Week 8 | July 26 – August 1  | Testing & Optimization        | - Write unit/integration tests<br>- Optimize Matter.js rendering<br>- Handle auth and network errors |
| Week 9 | August 2 – August 8 | Final Integration & Deployment| - Deploy frontend (Amplify/S3/Netlify)<br>- Final bug fixes<br>- Document app<br>- Run demos/user tests |