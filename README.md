# YouTubeClone-NullClass

## Introduction

This project involved enhancing a YouTube-inspired web application with three primary features: a points allocation system for watching videos, a custom video player with gesture-based controls, and a VoIP feature for video calls and screen sharing. The objective was to create an engaging and interactive user experience while maintaining functionality and ease of use.

## Features

### Core Video Platform Features

Video Upload & Management - Users can upload, edit, and manage their videos
Video Streaming - Custom video player with advanced controls
Video Discovery - Search functionality and video recommendations
Video Categories - Organized content browsing

### User Management System

User Authentication - Sign up, login, and profile management
Channel Creation - Users can create and customize their channels
User Profiles - Personal profile pages with user information
Subscription System - Subscribe to channels and get notifications

### Interactive Features

Comments System - Like, reply, and manage video comments
Like/Dislike - React to videos with thumbs up/down
Watch Later - Save videos for later viewing
History Tracking - Track watched videos
Liked Videos - Collection of liked content

### Advanced Features

Points System - Earn points for watching videos (5 points per video)
Custom Video Player - Gesture-based controls:
Double tap: Skip forward/backward 10 seconds
Single tap: Pause/play
Triple tap: Next video, close site, show comments
Hold gestures: Speed control (2x/0.5x)
Location/weather display on tap

### Communication Features

Video Calling - VoIP feature for video calls
Screen Sharing - Share screen during calls
Call Recording - Record video calls
Time-based Calling - Calls enabled 6PM-12AM only

## Technical Architecture

Frontend: React.js with Redux state management
Backend: Node.js with Express and MongoDB
Real-time: Socket.io for live features
File Upload: Multer for video uploads
Authentication: JWT-based authentication
Video Processing: Video.js integration

2. Install dependencies:
   - Frontend:
     ```sh
     cd client
     npm install
     npm start
     ```
   - Backend:
     ```sh
     cd server
     npm install
     npm start
     ```

## Challenges and Solutions

### Challenge 1: Implementing Gesture Controls

**Solution:** Implemented gesture controls by adding reference to the video element and handling taps with conditional statements.

### Challenge 2: VoIP Feature

**Solution:** Used React Media Recorder for recording and ensured that both video and audio streams were recorded.

### Challenge 3: Implementing Video Stream on Vercel

**Solution:** Used UseEffect hooks to ensure correct stream rendering on load.

### Challenge 4: Hosting and Deployment

**Solution:** Deployed backend on Render and frontend on Vercel due to static file serving issues with Vercel.

## Skills and Competencies

- Proficiency in React.
- Experience with video player libraries and custom gesture controls.
- Knowledge of WebRTC for VoIP features.
- Understanding of hosting web applications on platforms like Netlify or Vercel.
