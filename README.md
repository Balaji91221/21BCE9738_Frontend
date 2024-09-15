# Trademarkia Frontend Intern Task 

## Project Overview

This is a **React** frontend application built to replicate the Trademarkia Search Page. The application allows users to search for trademarks and filter results based on **owner**, **law firm**, **attorney**, and **status**. It integrates the **Trademarkia API** to fetch and display trademark data dynamically.

### Features
- A **search bar** for querying trademarks.
- Filters for **owner**, **law firm**, **attorney**, and **trademark status**.
- Displays search results based on user input.
- Responsive design using **Chakra UI** for consistent styling.
- **Loading states** and error handling for API requests.
- **Redux** for state management, using **Thunk** for asynchronous API calls.

## Tech Stack
- **React** (UI framework)
- **Chakra UI** (UI component library)
- **Axios** (for API requests)
- **Redux** (for state management)
- **Redux Thunk** (for handling asynchronous logic)

## Getting Started

### Prerequisites
- **Node.js** (v14 or higher) installed on your machine.

### Usage

- **Search for Trademarks:**  
  Enter a search query (e.g., a brand name) into the search bar, and the results will appear dynamically.

- **Apply Filters:**  
  Use filters for **owner**, **law firm**, **attorney**, and **status** to refine your search results.

- **Status Indicators:**  
  The page will display messages like "Searching...", "No Results Found", or "Error Occurred" to inform users about the search progress.

### API Integration

The application uses **Axios** to communicate with the Trademarkia API.

- **API Endpoint:**  
  `https://vit-tm-task.api.trademarkia.app/api/v3/us`

  
### Contributing
Feel free to fork this repository and create a pull request if you’d like to contribute!

