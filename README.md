# Notes Keeper - React Project

A modern, high-performance note-taking application inspired by Google Keep. This project focuses on **State Management**, **Component-Based Architecture**, and **Data Persistence**.

##  Key Features

* **Persistent Data:** Integrated `localStorage` to ensure notes are saved even after the browser is refreshed or closed.
* **Modular Architecture:** Built using clean, reusable React components (`Header`, `Footer`, `Note`, `CreateArea`) for professional-grade maintainability.
* **Modern UI/UX:** A customized "Blackish" dark-themed interface designed for better readability and reduced eye strain.
* **Interactive Design:** Smooth interactions using Material UI icons and React Zoom/Fab components for a polished feel.
* **Fast Build Performance:** Powered by **Vite** for optimized development and bundling.

## Tech Stack
* **Frontend:** React.js
* **Build Tool:** Vite
* **Icons & UI:** Material UI (@mui/icons-material)
* **Styling:** CSS3 
* **Persistence:** Browser LocalStorage API

## Project Structure

```text
src/
├── components/
│   ├── Header.jsx      # Sticky top navigation
│   ├── Footer.jsx      # Copyright information
│   ├── Note.jsx        # Individual note card template
│   └── CreateArea.jsx  # Input logic and state handling
├── App.jsx             # Main logic, State & LocalStorage persistence
├── index.css          
└── main.jsx            
