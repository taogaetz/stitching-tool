Project: StitchFiddle Clone
Overview
Build a cross-stitch pattern design tool using PixiJS for canvas rendering and Tailwind CSS for UI components, all in a single HTML file using CDNs.
Goals

Create an interactive grid-based canvas for designing cross-stitch patterns
Implement color palette selection and management
Add pattern saving, loading, and export functionality
Build zoom/pan controls for easy pattern navigation
Include undo/redo functionality
Create a user-friendly, responsive interface

Technologies

PixiJS for canvas rendering (via CDN)
Tailwind CSS for styling (via CDN)
Local storage for pattern saving
Vanilla JavaScript (ES6+)
Single HTML file implementation

Architecture
The application should be organized in a modular way within a single file:

Canvas Module: Grid-based drawing area using PixiJS
Toolbar Module: Tools for drawing, erasing, filling, and selecting
Color Palette Module: Color selection and management
Pattern Management Module: Save, load, and export patterns

Implementation Plan
Phase 1: Project Setup

Create a single HTML file with necessary CDN links
Set up basic page structure using Tailwind
Initialize PixiJS container
Create application state management

Phase 2: Canvas Implementation

Create a PixiJS canvas that displays a grid
Implement cell selection and coloring
Add zoom and pan functionality
Handle window resizing properly

Phase 3: UI Components

Build toolbar with basic tools (pencil, eraser, fill, select)
Create color palette with standard cross-stitch thread colors
Add pattern dimension controls
Implement responsive layout for different screen sizes

Phase 4: Pattern Management

Add pattern saving to localStorage
Implement pattern loading functionality
Create export options (PNG, PDF)
Add pattern metadata (name, dimensions, thread count)

Phase 5: Advanced Features

Implement undo/redo system
Add symbol overlay for color representation
Create pattern preview mode

Coding Standards

Use well-organized vanilla JavaScript with clear function separation
Implement module pattern or namespaces to avoid global scope pollution
Use consistent naming conventions
Add comprehensive comments
Create reusable utility functions
Ensure responsive design works on all devices
Use event delegation where appropriate for UI elements

Claude Instructions
When asked to implement specific components:

Provide complete implementation for a single HTML file
Include all necessary CSS (using Tailwind classes)
Include all JavaScript in appropriate script tags
Explain key design decisions
Consider edge cases and error handling
Make UI components responsive and accessible
Prefer simple, clean solutions over complex ones
Ensure all features work within a single file architecture
Include clear documentation on usage
