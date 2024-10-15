# Quicksell Frontend Assignment
# Table of Contents
* Introduction
* Features
* Live Demo
* Repository
* Tech Stack
* Getting Started
* Prerequisites
* Installation
* Running the Application
* Usage
* Grouping Options
* Sorting Options
* User View State Persistence
* Available User Indicator
* API Integration
* Screenshots
* Contributing
* License
* Acknowledgements
# Introduction
Quicksell Frontend Assignment is an interactive Kanban board application built with React.js and SCSS. It allows users to dynamically group and sort tickets based on their preferences, leveraging the Quicksell API for real-time data. The application offers a visually appealing and responsive user interface, ensuring a seamless user experience across devices.
# Features
* Conditional Rendering:Components are rendered based on the application's state and user preferences.
* Dynamic Grouping:
   * By Status: Group tickets based on their current status.
   * By User: Arrange tickets according to the assigned user.
   * By Priority: Group tickets based on their priority level.
* Dynamic Ordering:
   * Priority: Arrange tickets in descending order of priority.
   * Title: Sort tickets in ascending order based on their title.
* View State Persistence: The application saves the user's view state, ensuring 
  preferences are maintained even after a page reload.
* Dynamic Data Fetching: Integrates with the Quicksell API to fetch and display real-time data.
* Custom Spinner: An engaging spinner enhances user experience during data fetching or other waiting times.
* Available User Indicator: Displays the availability status of users currently using the application.

# Live Demo
 Experience the application live: https://assignment-quicksell-3ydkvzqsq-reetis-projects-5729c72f.vercel.app/
# Repository
Access the source code on : https://github.com/reetreet123/Assignment_quicksell
# Tech Stack
 * JavaScript
 * React.js
 * SCSS (CSS Preprocessor)
 * HTML
# Getting Started
# Prerequisites
Ensure you have the following installed on your machine:

* Node.js (v14 or later)
* npm or Yarn

# Usage
 # Grouping Options
Users can group tickets in three distinct ways:

By Status: Groups tickets based on their current status (e.g., Open, In Progress, Closed).
By User: Arranges tickets according to the assigned user.
By Priority: Groups tickets based on their priority level (Urgent, High, Medium, Low, No Priority).
To apply a grouping:

Click the "Display" button.
Select your preferred grouping option from the dropdown.
The Kanban board will dynamically adjust to reflect your selection.

# Sorting Options
Users can sort the displayed tickets in two ways:

* Priority: Arranges tickets in descending order of priority (Urgent to No Priority).
* Title: Sorts tickets in ascending alphabetical order based on their title.
To apply sorting:

Click the "Sort" button.
Choose either "Priority" or "Title" from the dropdown.
User View State Persistence
The application saves your view preferences (grouping and sorting options). Even after refreshing or reopening the page, your selected view state remains intact, ensuring a consistent user experience.

# Available User Indicator
An indicator displays which users are currently available or active within the application, providing real-time insights into user activity.

# API Integration
The application interacts with the Quicksell API to fetch and manage ticket data. Ensure you have access to the API endpoint: (https://api.quicksell.co/v1/internal/frontend-assignment).

# Priority Levels
Tickets have the following priority levels:

4 - Urgent
3 - High
2 - Medium
1 - Low
0 - No Priority
These values are fetched directly from the API and are used to group and sort tickets accordingly.


# Acknowledgements
React.js
SCSS
Quicksell API
Create React App
