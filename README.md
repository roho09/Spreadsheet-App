Spreadsheet App
Overview

This project is a spreadsheet application built using Next.js, Tailwind CSS, and Zustand for state management. The app provides features for rendering a grid of cells, cell editing, dynamic updates, and styling with state persistence.
Features

    Grid Rendering: Displays a grid of 1000 blank cells.
    Cell Editing: Allows users to edit cell content.
    Dynamic Updates: Updates the grid dynamically based on user interactions.
    Styling: Applies styling to cells based on properties.
    Undo/Redo Functionality: Manages changes to cell data with undo and redo options.
    Search and Filter: Provides search functionality for cell content.
    Pagination: Includes pagination controls for efficient data handling.

Setup and Installation
Prerequisites

    Node.js (v14.x or later)
    npm or Yarn

Installation

    Clone the repository:

    bash

git clone https://github.com/your-username/spreadsheet-app.git

Navigate to the project directory:

bash

cd spreadsheet-app

Install dependencies:

bash

    npm install
    # or
    yarn install

Running the Application

    Start the development server:

    bash

npm run dev
# or
yarn dev

Open your browser and navigate to:

arduino

    http://localhost:3000

Usage
Grid Rendering

The app displays a grid of cells which can be edited. You can interact with the cells directly in the browser.
Cell Editing

Click on a cell to edit its content. The changes will be saved and applied dynamically.
Undo/Redo

Use the undo and redo buttons to manage changes made to the cell data.
Search and Filter

Use the search bar to filter cells based on their content.
Pagination

Navigate through the grid using pagination controls if the data exceeds the viewable area.
Project Structure

The project structure is as follows:

lua

assignment
├── .next
├── node_modules
├── public
│   ├── next.svg
│   └── vercel.svg
├── src
│   ├── app
│   │   ├── spreadsheet
│   │   │   ├── layout.tsx
│   │   │   └── page.tsx
│   │   ├── store
│   │   │   └── useStore.ts
│   │   ├── styles
│   │   │   └── globals.css
│   │   └── utils
│   ├── components
│   │   ├── cell.tsx
│   │   ├── grid.tsx
│   │   ├── Pagination.tsx
│   │   ├── SearchBar.tsx
│   │   └── UndoRedo.tsx
│   ├── store
│   │   └── useStore.ts
│   ├── styles
│   │   └── globals.css
│   └── utils
├── .eslintc.json
├── .gitignore
├── next-env.d.ts
├── next.config.js
├── package-lock.json
├── package.json
└── postcss.config.js

Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.
License

This project is licensed under the MIT License - see the LICENSE file for details.
Contact

For any questions or issues, please contact rohitkulkarni979@gmail.com
