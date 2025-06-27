# ShowTube - Netflix Clone

ShowTube is a Netflix-inspired video streaming platform built using modern web technologies like React, Redux Toolkit, Firebase, Styled Components, Axios, Node.js, Express, and MongoDB. This project replicates core functionalities of Netflix, including user authentication, category-based browsing, a personalized "My List," and a polished, responsive UI.

## Features

- **Modern UI/UX:** Built with React and styled-components for a Netflix-like, responsive user interface.
- **Authentication:** Secure email/password authentication using Firebase.
- **Browse & Search:** Explore movies and TV shows by categories/genres with search functionality.
- **Personal List:** Users can add or remove movies from their personal "My List."
- **Backend API:** Node.js & Express server for backend logic and MongoDB for persistent storage.
- **State Management:** Redux Toolkit for efficient and scalable state management.
- **API Integration:** Uses Axios to fetch and manage data.
- **Deployment Ready:** Easily deployable to modern web hosts.

## Tech Stack

- **Frontend:** React, Redux Toolkit, styled-components, Axios
- **Backend:** Node.js, Express.js
- **Authentication & Hosting:** Firebase
- **Database:** MongoDB

## Getting Started

### Prerequisites

- Node.js (LTS recommended)
- npm or yarn
- MongoDB instance (local or cloud)
- Firebase account/project

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/satya12345678-bot/showtube_netflix_clone.git
   cd showtube_netflix_clone
   ```

2. **Install dependencies for both client and server:**
   - For React UI:
     ```bash
     cd showtube\(netflix\ clone\)/showtube\(netflix\ clone\)/showtube.ui
     npm install
     ```
   - For backend (adjust path as needed):
     ```bash
     cd ../../server
     npm install
     ```

3. **Configure Firebase and MongoDB:**
   - Update your Firebase credentials in the frontend configuration file.
   - Update MongoDB URI in your server's config.

4. **Start the development servers:**
   - **Frontend:**
     ```bash
     npm start
     ```
     Open [http://localhost:3000](http://localhost:3000) in your browser.
   - **Backend:**
     ```bash
     npm run dev
     ```
     (Or the script specified in your server package.json)

## Available Scripts (Frontend)

- `npm start` - Runs the app in development mode.
- `npm test` - Launches the test runner in interactive watch mode.
- `npm run build` - Builds the app for production.
- `npm run eject` - Ejects the app from Create React App (irreversible).

## Folder Structure (Simplified)

```
showtube_netflix_clone/
├── showtube(netflix clone)/
│   └── showtube(netflix clone)/
│       └── showtube.ui/            # React frontend app
│       └── ... (other folders)
├── server/                         # Node.js/Express backend
└── README.md
```

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

This project currently does not have a license specified.

---

*Inspired by Netflix for learning and educational purposes only. Not affiliated with or endorsed by Netflix, Inc.*
