# Character Queries

This directory contains GraphQL queries for retrieving character data from the Rick and Morty API.

## Queries

### 0. Get a Specific Character by ID

These queries demonstrate how to fetch the details of a single character using their unique ID.

**Files:**
- `character-id-1.graphql`
- `character-id-1-output.json`
- `character-id-2.graphql`
- `character-id-2-output.json`
- `character-id-3.graphql`
- `character-id-3-output.json`
- `character-id-4.graphql`
- `character-id-4-output.json`

### 1. Get a List of All Characters

These queries show how to fetch a paginated list of all characters.

**Files:**
- `characters-page-1.graphql`
- `characters-page-1-output.json`
- `characters-page-2.graphql`
- `characters-page-2-output.json`
- `characters-page-3.graphql`
- `characters-page-3-output.json`
- `characters-page-4.graphql`
- `characters-page-4-output.json`
alx-graphql-0x00/episode/README.md
Markdown

# Episode Queries

This directory contains GraphQL queries for retrieving episode data from the Rick and Morty API.

## Queries

### 2. Get a Specific Episode by ID

These queries demonstrate how to fetch the details of a specific episode using its unique ID.

**Files:**
- `episode-page-1.graphql`
- `characters-page-1-output.json`
- `characters-page-2.graphql`
- `characters-page-2-output.json`
- `characters-page-3.graphql`
- `characters-page-3-output.json`
- `characters-page-4.graphql`
- `characters-page-4-output.json`
alx-graphql-0x01/alx-rick-and-morty-app/README.md
Markdown

# alx-rick-and-morty-app

This project is a Next.js application that uses GraphQL to fetch and display data from the Rick and Morty API. It is set up with TypeScript, ESLint, and Tailwind CSS.

## Getting Started

To get the project running on your local machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/alx-graphql-0x01.git](https://github.com/alx-graphql-0x01.git)
    cd alx-graphql-0x01/alx-rick-and-morty-app
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    npm install @apollo/client graphql
    npm install @types/graphql
    ```
3.  **Run the development server:**
    ```bash
    npm run dev
    ```
4.  **Open in browser:**
    Open your web browser and navigate to `http://localhost:3000` to see the application.

## Technologies Used

* **Next.js:** A React framework for building full-stack web applications.
* **TypeScript:** A strongly typed programming language that builds on JavaScript.
* **Tailwind CSS:** A utility-first CSS framework for rapidly building custom designs.
* **Apollo Client:** A comprehensive state management library for JavaScript that enables you to manage both local and remote data with GraphQL.
* **GraphQL:** A query language for your API.
alx-graphql-0x02/alx-rick-and-morty-app/README.md
Markdown

# alx-rick-and-morty-app

This project is an extension of the previous Next.js application. It demonstrates how to query the Rick and Morty GraphQL endpoint to retrieve episode data and display it in a user-friendly interface with pagination.

## Features

* Fetches and displays a list of Rick and Morty episodes.
* Paginated navigation to browse through different pages of episodes.
* Uses Apollo Client for GraphQL queries.
* Responsive design with Tailwind CSS.
* Clear and reusable components for better code organization.

## Getting Started

To get the project running on your local machine, follow these steps:

1.  **Duplicate the repository:**
    ```bash
    cp -r alx-graphql-0x01 alx-graphql-0x02
    cd alx-graphql-0x02/alx-rick-and-morty-app
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Run the development server:**
    ```bash
    npm run dev
    ```
4.  **Open in browser:**
    Open your web browser and navigate to `http://localhost:3000` to see the application.

## Technologies Used

* **Next.js:** A React framework.
* **TypeScript:** A strongly typed programming language.
* **Tailwind CSS:** A utility-first CSS framework.
* **Apollo Client:** A state management library for GraphQL.
* **GraphQL:** A query language for your API.
