# Progress Documentation

## Roadmap

- [x] Develop basic scraper with Puppeteer
- [x] Integrate MongoDB for data storage
- [x] Set up Express server for serving data and static files
- [x] Add data visualization capabilities
- [x] Add a frontend for better user experience

---

## 1. Project Overview

### Objective
The project aims to show all weather data. We use Puppeteer to scrape data, MongoDB to store it, and Express to serve both the data and the frontend.

---

## 2. Features Implemented

### a. **Data Scraper (Puppeteer)**

- **Description**: Developed a basic scraper to collect data using Puppeteer. 
- **Status**: Completed.
- **Key points**: 
  - The scraper collects data from weather.com.
  - Data extraction logic based on page structure.
  
---

### b. **MongoDB Integration**

- **Description**: Integrated MongoDB to store scraped data.
- **Status**: Completed.
- **Key points**: 
  - MongoDB stores data in a specific format.
  - Connected MongoDB with the Express server for data fetching.
  
---

### c. **Express Server Setup**

- **Description**: Set up an Express server to serve scraped data and static frontend files.
- **Status**: Completed.
- **Key points**: 
  - API endpoints are created to serve data from MongoDB.
  - Static file hosting for frontend UI.
  
---

### d. **Data Visualization**

- **Description**: Implemented data visualization features to display scraped data.
- **Status**: Completed.
- **Key points**: 
  - Used Css for visualisation
  - Visualizations include a table & text form visualisation.

---

### e. **Frontend Development**

- **Description**: Added a frontend for better user experience.
- **Status**: Completed.
- **Key points**: 
  - Integrated with Express server to display data visualizations.
  
---

## 3. Code Quality

- **Conventions Followed**: 
  - Code follows consistent naming conventions (camelCase).
  - Proper organization of files and modules.
  
- **Version Control**: 
  - Regular commits with clear, concise commit messages following [Conventional Commits] guidelines.
  - Feature branches used for individual tasks.

---

## 4. Documentation

- **README**: 
  - Updated to include setup instructions, installation steps, and feature explanations.
  
- **Code Documentation**: 
  - Documented key functions, classes, and modules in the codebase.

---
