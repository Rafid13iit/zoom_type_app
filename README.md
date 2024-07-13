<img src="https://github.com/Rafid13iit/zoom_type_app/blob/master/public/Cover.png?raw=true" width="750" height="400" align="center">

# BOOM the-zoom-type-app

Zoom Type App is a Next.js application that allows users to create, schedule, and join meetings, as well as view meeting recordings.

## Features

- Instant Meetings
- Scheduled Meetings
- Join Meetings via Link
- View and Manage Recordings

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine
- Stream API key and secret
- Clerk API keys for authentication

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Rafid13iit/zoom_type_app.git
   cd zoom_type_app
2. Install dependencies:
    ```bash
    npm install
3. Create a .env.local file in the root directory and add your environment variables:
    ```bash
    NEXT_PUBLIC_BASE_URL=http://localhost:3000
    STREAM_API_KEY=your_stream_api_key

    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
    CLERK_SECRET_KEY=your_clerk_secret_key

    NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

    NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
    STREAM_SECRET_KEY=your_stream_secret_key

    NEXT_PUBLIC_BASE_URL=http://localhost:3000
4. Run the development server:
    ```bash
    npm run dev
Open your browser and go to http://localhost:3000.

## Usage
Home Page: Choose to start an instant meeting, schedule a meeting, view recordings, or join a meeting.
Schedule Meeting: Provide a description and select a date and time for the meeting.
Join Meeting: Enter the meeting link to join.
View Recordings: Access and manage your past meeting recordings.

## Acknowledgements
Special thanks to **Adrian Hajdin** for his helpful tutorials and guidance on YouTube.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any features, bug fixes, or improvements.