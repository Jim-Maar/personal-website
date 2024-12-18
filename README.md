# personal-website
This will become my personal website. I don't have any web-dev experience, so let's see how this goes. My mission is to have an About tab, a Blog tab, and a tab where you can play some random game.

## Why
- I want to do a completely finished project that I can show to people.
- I want to learn web-dev on the way.
- I would like to write some blog posts, and making a personal website with an empty blog tab kind of forces my hand.

## How
- My plan is to complete a series of challenges that start with just writing an HTML file and end with a fully functional website. I created a list of challenges using ChatGPT and but I will probably change it as I go along.

---

## Challenges
### Basics
- [x] Create a simple HTML file.
- [x] Create a simple HTML file with some CSS.
- [x] Add CSS as a stylesheet.
- [x] Get this website to run on my local machine.
  - **Useful link:** [Live Server for VS Code](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [x] Add some tabs to navigate between the pages.

---

### JavaScript Basics
Before moving to TypeScript or React, it's essential to learn some JavaScript basics:
- [ ] Learn how to manipulate the DOM using JavaScript.
  - **Useful link:** [MDN DOM Manipulation](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
- [ ] Practice basic JavaScript concepts like variables, functions, and events.
  - **Useful link:** [JavaScript Basics on MDN](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
- [ ] Create a small interactive component, such as a button that changes text or toggles a color.

---

### TypeScript Basics
Start using TypeScript before switching to React to understand its features:
- [ ] Learn the basics of TypeScript, such as types, interfaces, and enums.
  - **Useful link:** [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
- [ ] Convert a small JavaScript project into TypeScript to see the benefits of type safety.
- [ ] Use TypeScript with a simple DOM manipulation script.

---

### Bootstrap Styling
- [ ] Replace CSS with Bootstrap for better styling.
  - **Useful link:** [Bootstrap Documentation](https://getbootstrap.com/docs/)
- [ ] Use Bootstrap's navbar for navigation.
  - **Useful link:** [Bootstrap Navbar Example](https://getbootstrap.com/docs/5.3/components/navbar/)
- [ ] Add responsiveness with Bootstrap utilities.

---

### Flask Basics
Learn how to use Flask for the backend:
- [ ] Set up a basic Flask application and run it locally.
  - **Useful link:** [Flask Quickstart Guide](https://flask.palletsprojects.com/en/2.3.x/quickstart/)
- [ ] Learn how to define routes and render HTML templates using Jinja2.
  - **Useful link:** [Flask Templating with Jinja2](https://flask.palletsprojects.com/en/2.3.x/templating/)
- [ ] Use Flask to create a simple REST API.
  - **Useful link:** [Flask REST API Guide](https://flask-restful.readthedocs.io/en/latest/)
- [ ] Practice sending data from the frontend to Flask and receiving responses.

---

### React Basics (Switching from Vanilla TypeScript)
After learning JavaScript and TypeScript, move to React for the frontend:
- [ ] Learn how to create components and manage state in React.
  - **Useful link:** [React Docs: Main Concepts](https://react.dev/learn)
- [ ] Use TypeScript with React to type props, state, and events.
  - **Useful link:** [React TypeScript Cheatsheet](https://react-typescript-cheatsheet.netlify.app/)
- [ ] Create a small React application with TypeScript to practice:
  - Example: A to-do list or a counter app.
- [ ] Use React Router to add navigation between pages.
  - **Useful link:** [React Router Documentation](https://reactrouter.com/)
- [ ] Add Bootstrap styling to React components.

---

### Blog (Flask + React)
- [ ] Set up a Flask backend to serve blog content dynamically.
  - **Useful link:** [Flask Quickstart Guide](https://flask.palletsprojects.com/en/2.3.x/quickstart/)
- [ ] Use Flask to provide APIs for fetching blog data (titles, images, and content).
  - **Useful link:** [Flask REST API Guide](https://flask-restful.readthedocs.io/en/latest/)
- [ ] Implement the blog frontend in React with TypeScript:
  - [ ] Create a Blog page that fetches and displays blog titles (and optional pictures) via Flask APIs.
  - [ ] Add clickable links to navigate to individual blog posts.
  - [ ] Dynamically render blog posts in React by fetching markdown files through Flask APIs.
  - **Useful link:** [React Markdown Library](https://github.com/remarkjs/react-markdown)
- [ ] Add Bootstrap styling to the blog list and post views in React.
- [ ] Test the Flask + React integration locally.

---

### Game Tab (Flask + React + TypeScript)
This section outlines four types of games to progressively implement. The frontend will be in React (using TypeScript), while the backend will use Flask for logic and communication. I don't know yet which one I want to do.

#### 1. Very Simple Turn-Based Game Without RL
- [ ] Create a basic turn-based game (e.g., Tic-Tac-Toe or Rock-Paper-Scissors) in React.
  - Use React state to manage game logic.
  - **Useful link:** [React Tic-Tac-Toe Tutorial](https://react.dev/learn/tutorial-tic-tac-toe)
- [ ] Add Bootstrap styling to the game UI.
- [ ] Deploy the game as part of the static website.

#### 2. Turn-Based Game With RL
- [ ] Implement a turn-based game (e.g., Chess or Connect Four) with backend logic in Flask.
- [ ] Train a reinforcement learning (RL) agent using PyTorch to play the game.
  - **Useful link:** [PyTorch RL Examples (Stable-Baselines3)](https://stable-baselines3.readthedocs.io/en/master/)
- [ ] Use Flask APIs to integrate the RL agent for calculating moves.
- [ ] Implement the frontend in React with TypeScript for interacting with the game and making API calls to Flask.

#### 3. Real-Time Game Without RL
- [ ] Implement a real-time game (e.g., Pong or a simple shooter) using React with TypeScript and the HTML Canvas API.
  - **Useful link:** [React and Canvas Tutorial](https://medium.com/@pdx.lucasm/canvas-with-react-js-32e133c05258)
- [ ] Use Flask-SocketIO to enable real-time communication between the client and server.
  - **Useful link:** [Flask-SocketIO Documentation](https://flask-socketio.readthedocs.io/en/latest/)
- [ ] Render game states dynamically on the React frontend.

#### 4. Real-Time Game With RL
- [ ] Create a real-time game (e.g., a strategy or 2D action game) with backend logic in Flask.
- [ ] Train an RL agent to play the game in real time using PyTorch.
- [ ] Use Flask-SocketIO to send real-time updates to the React frontend.
- [ ] Implement dynamic rendering of the RL agent's actions using React and Canvas.

---

### Final Touches
- [ ] Enhance the Blog tab with tags/categories and search functionality.
- [ ] Test and debug the full website (About, Blog, Game).
- [ ] Deploy the final version of the website:
  - Use Flask to serve APIs and static files.
  - Use Vercel, Netlify, or similar to deploy the React frontend.
  - **Useful link:** [Deploy Flask with React](https://blog.miguelgrinberg.com/post/how-to-deploy-a-react--flask-project)
  - **Useful link:** [Render for Flask App Deployment](https://render.com/)

---

## Notes
- **JavaScript > TypeScript > React:** You'll start with plain JavaScript, move to TypeScript, and finally adopt React with TypeScript for dynamic UI.
- **Flask for backend:** Flask will handle APIs for the blog and games, as well as backend game logic.
- **Bootstrap:** Styling will rely on Bootstrap for a clean and responsive design.