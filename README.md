Meteor Blaze App (Simple Todos) - README

A simple task management application built using Meteor.js (Blaze front-end).

FEATURES
- Create new tasks (todos)
- Mark tasks as completed
- Delete tasks
- Real-time UI updates
- Simple Blaze templating

TECH STACK
- Meteor.js
- Blaze (Frontend)
- MongoDB (MiniMongo in development)
- JavaScript (ES6)
- HTML & CSS

PROJECT SETUP

1. Clone the repository:
git clone https://github.com/your-username/simple-todos-blaze.git
cd simple-todos-blaze

2. Install Meteor:
curl https://install.meteor.com/ | sh

3. Run the project:
meteor npm install
meteor run

Open in browser:
http://localhost:3000

GITHUB AUTHENTICATION FIX

GitHub no longer supports password authentication.
Use a Personal Access Token (PAT) instead.

Steps:
- Go to GitHub Settings → Developer Settings
- Generate a PAT token
- Use it as password when Git prompts

PROJECT STRUCTURE
simple-todos-blaze/
│── client/
│── server/
│── imports/
│── public/
│── package.json
│── meteor.config.js
│── README.md

FUTURE IMPROVEMENTS
- Add user authentication
- Add task categories
- Deploy on Galaxy or Vercel
- Add due dates and reminders

AUTHOR
Your Name
GitHub: https://github.com/SasiDeepikaVasantha
