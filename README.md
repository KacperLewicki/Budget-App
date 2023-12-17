# Budget App Documentation

## Introduction

This document provides an overview and usage guidelines for the Budget App, a React-based web application designed for personal finance management. The app allows users to add, view, and manage financial transactions across various budget categories. It utilizes a mock JSON database for data persistence and showcases dynamic data updates.

## System Architecture

### Frontend

- **Technology** : React (with Hooks)
- **Main Features** :
- Interactive UI with four main tabs: Homepage, Budget, Add Transaction, and View Transactions.
- Real-time data representation of budget categories and transactions.
- Support for multi-language localization.

### Data Management

- **Database** : Mock JSON database (`db.json`)
- **Features** :
- Stores and updates user transactions and budget categories.
- Facilitates real-time UI updates upon data modifications.

## Application Setup

### Prerequisites

- Node.js and npm installed.
- A basic understanding of React and its ecosystem.

### Installation and Configuration

- Clone the repository or download the source code.
- Navigate to the project directory in the terminal.
- Run `npm install` to install dependencies.
- Ensure that the `db.json` file is properly set up to mock the database.

## Running the Application

- Execute **npm start** and **npm run start:db** to run the app in development mode.
- Access the app through the web browser at the local server address provided in the terminal.

## Usage

### Adding a New Transaction

- Navigate to the 'Add new transaction' tab.
- Fill out the form with the transaction's description, amount, category, and date.
- Submit the form to record the transaction in the budget.

### Viewing Transactions

- The 'Budget' tab displays all transactions under their respective categories.
- Users can view detailed transaction entries and the total budget summary.

### Localization

- Users can switch between available languages using the language selection buttons.

## Technical Details

### React Components and Hooks

- Functional components with React Hooks for state and effect management.
- Use of `useState` for local component state management.
- Use of `useEffect` for side effects and data fetching.

### Data Flow

- Data is fetched from and updated to the `db.json` using React's state management.
- The app reacts to state changes and renders UI updates accordingly.

## Future Developments

- Implementation of a backend server for handling authentication and real data persistence.
- Enhanced data filtering and sorting within the budget and transaction views.
- Expansion of localization to include more languages.
