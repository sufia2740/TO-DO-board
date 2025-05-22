# Trello Clone - Kanban Board Application

https://github.com/user-attachments/assets/8ec9fa18-ec73-4d9d-a5ee-f2180d620855

## Project Overview
A fully functional Kanban board application inspired by Trello, built with React and modern web technologies. This project demonstrates advanced front-end development skills including drag-and-drop functionality, state management, and responsive design.

## Key Features
- **Drag & Drop Interface:** Seamless card movement between lists using HTML5 drag-and-drop API  
- **Dynamic Content Management:** Create, edit, and delete cards and lists in real-time  
- **Responsive Design:** Optimized for desktop and mobile devices  
- **Modern UI/UX:** Glassmorphism design with gradient backgrounds and smooth animations  
- **Interactive Elements:** Hover effects, transitions, and visual feedback for better user experience  

## Technical Implementation

### Frontend Technologies
- React 18 with functional components and hooks  
- JavaScript ES6+ for modern syntax and functionality  
- Tailwind CSS for utility-first styling and responsive design  
- Lucide React for consistent iconography  

### Core Functionality
- **State Management:** Complex state handling with React `useState` hook  
- **Event Handling:** Mouse events, drag events, and form submissions  
- **Component Architecture:** Modular, reusable component structure  
- **Conditional Rendering:** Dynamic UI updates based on user interactions  

### Advanced Features Implemented
- **Drag & Drop System:** Custom implementation handling `dragStart`, `dragOver`, and `drop` events  
- **Real-time Updates:** Instant UI updates without page refresh  
- **Form Validation:** Input validation and error handling  
- **Dynamic List Creation:** Users can create unlimited boards and cards  
- **Optimistic UI Updates:** Immediate visual feedback for user actions  

## Code Highlights

### Drag & Drop Logic
```javascript
const handleDragStart = (e, card, fromBoardId) => {
  setDraggedCard(card);
  setDraggedFrom(fromBoardId);
};

const handleDrop = (e, toBoardId) => {
  // Move card between boards with state updates
  // Remove from source, add to destination
};
