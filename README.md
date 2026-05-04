# Festival HQ

Festival HQ is a team workspace application designed for festival organizers. It provides tools for team management, task tracking, and real-time (local-only) communication.

## Features

- **Team Management**: Join different teams (Marketing, Entertainment, Decor, etc.) or create your own custom teams.
- **Task Tracking**: Create, complete, and delete tasks for each team. Track progress with a visual progress bar.
- **Team Chat**: Communicate with your team members in a team-specific chat room.
- **Notifications**: Stay updated with a notification system that tracks task additions, completions, and messages.
- **Persistence**: Your data is saved locally in your browser's local storage.

## Getting Started

### Prerequisites

To run this application locally, you need a web browser. For development and testing, you can use a simple HTTP server.

### Running Locally

1. Clone this repository.
2. Open `index.html` directly in your browser or serve the directory using a web server.
3. For example, using `npx`:
   ```bash
   npx http-server .
   ```
4. Navigate to `http://localhost:8080` (or the port specified by your server).

## Testing

Verification tests are written using Playwright. To run them:

1. Install dependencies:
   ```bash
   npm install
   ```
2. Run the tests:
   ```bash
   npx playwright test
   ```
