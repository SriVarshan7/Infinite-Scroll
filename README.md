# Social Media Feed with Infinite Scrolling

A React-based social media feed application that includes an infinite scrolling feature. This app dynamically loads posts as the user scrolls down the page, enhancing user experience and performance.

## Features

- **Infinite Scrolling**: Automatically loads more posts as the user reaches the end of the feed.
- **Social Media Feed**: Displays a list of posts with user avatars, content, and styling.
- **Responsive Design**: Works well on desktop and mobile devices.
- **Lazy Loading**: Posts are loaded in batches, reducing the initial page load time.
- **React Intersection Observer**: Used to detect when the user reaches the bottom of the feed and trigger the loading of new posts.

## Tech Stack

- **Frontend**: React, React Intersection Observer
- **Others**: CSS for styling, Web Vitals for performance monitoring

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/social-media-feed.git
    cd social-media-feed
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

## Running the Application

1. Start the development server:

    ```bash
    npm start
    ```

2. Open your browser and navigate to `http://localhost:3000` to view the social media feed.

## Usage

- The feed will display posts, and as you scroll down, more posts will be loaded dynamically.
- Infinite scrolling is implemented using the **React Intersection Observer**. It detects when the user reaches the bottom of the page and loads more content.

## Project Structure

```bash
social-media-feed/
├── public/          # Public assets (index.html, favicon, etc.)
├── src/             # React components and styles
│   ├── App.js       # Main component
│   ├── Feed.js      # Component to display the feed
│   ├── index.js     # Entry point for React app
│   ├── App.css      # Styles for the app
├── package.json     # Project dependencies and scripts
└── README.md        # This file
