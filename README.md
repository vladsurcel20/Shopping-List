# Shopping List App

## Overview
The Shopping List App is a simple web application designed to help users manage their shopping lists efficiently. It provides a user-friendly interface for adding and deleting items from the list, as well as marking items as purchased. The app aims to streamline the shopping experience and improve organization.

## Technologies Used
- **Frontend**: React.js
- **Backend**: JSON Server
- **Styling**: CSS

## Features
 ### Item Management
- Add Item: Users can add new items to the shopping list by entering the item name and clicking the "Plus" button.
- Delete Item: Items can be removed from the list by clicking on the delete icon next to the item.
- Mark as Purchased: Users can mark items as purchased by clicking on the checkbox next to the item.

### Search Functionality
- Search Items: Users can search for specific items on the list by typing in the search box. The list dynamically updates to display matching items.

### Error Handling
- Validation: Input data is validated to ensure accuracy and prevent errors.
- Error Messages: Informative error messages are displayed to users in case of invalid input or other issues.

### User Interface
- Intuitive Design: The interface is designed to be user-friendly and easy to navigate.

## Installation and Setup
1. Clone the repository: `git clone <URL_REPO>`
2. Navigate to the project directory: cd shopping-list-app
3. Install dependencies: npm install
4. Start the JSON server: `npx json-server -p 3500 -w data/db.json`
5. Start the React application: `npm start`
