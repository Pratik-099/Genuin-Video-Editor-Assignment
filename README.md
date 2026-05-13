Genuin Video Editor Assignment 
Project Overview
This project is a web-based video editor built using React and TypeScript. The application allows users
to upload media files, preview videos in real time, apply filters, trim videos, add overlays, and export
edited content.
Features
- Video Upload
- Audio Upload
- Real-Time Preview
- Video Trimming
- Playback Speed Control
- Filters & Effects
- Export Functionality
- Responsive UI
- Lazy Loaded Components
Tech Stack
Frontend: React, TypeScript, Tailwind CSS, Vite
State Management: React Context API
Folder Structure
src/
  components/
  context/
   pages/
  services/
  utils/
   App.tsx
Setup Instructions
1. git clone <repository-url>
2. npm install
3. npm run dev
Performance Optimizations
- Lazy loading using React.lazy and Suspense
- Modular component structure
- Efficient state handling using Context API
Design Decisions
Context API was used for managing shared editor state. Lazy loading was implemented to improve
performance and reduce initial bundle size.
Challenges Faced
Managing real-time preview updates and synchronizing media state across multiple components.
Future Improvements
- Multi-track timeline editing
- Undo/Redo support
- Cloud storage
- Collaborative editing
Author
Pratik Joshi
