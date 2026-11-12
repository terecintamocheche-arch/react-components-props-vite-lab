# Underreacted – Personal Blog

A simple React blog website built using functional components and props. The project demonstrates how data can be passed from a parent component to child components.

## Features

- Displays the blog name.
- Shows the blog logo and description.
- Displays a list of blog articles.
- Uses reusable React components.
- Passes data between components using props.
- Includes responsive styling.

## Components

### 1. App
The main parent component. It imports the blog data and passes information to Header, About, and ArticleList.

### 2. Header
Displays the blog name received through props from App.

### 3. About
Displays the blog logo and description received through props from App.

### 4. ArticleList
Receives the posts array from App. It uses `map()` to display each post using the Article component.

### 5. Article
Displays an individual article's title, date, and preview. It receives these details through props from ArticleList.

## Component Structure

```text
App
├── Header
├── About
└── ArticleList
    ├── Article
    ├── Article
    └── Article
```

## Technologies Used

- React
- JavaScript
- HTML
- CSS
- Vite
- Vitest

## How to Run the Project

1. Clone the repository.
2. Open the project folder in your terminal.
3. Install dependencies:

```bash
npm install
```
