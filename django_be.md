# AgrexAI Django Hiring Test

## Problem Statement

Create a Django application called `LibraryManager` that serves as a backend and frontend for managing a library's book inventory. The application should allow users to perform CRUD (Create, Read, Update, Delete) operations on books. Each book record should contain the following information:

- Title
- Author
- ISBN
- Publication Date
- Genre
- Quantity in Stock

Certainly, to further assess the advanced knowledge of Django ORM,

1.  Implement a model relationship system where each `Book` can have multiple `Authors` and each `Author` can have a biography associated with them. Show queries that involve joining across these relationships.

2.  Create API/Endpoint to calculate : 
    - The total number of books for each author.
    - The average number of books across all genres.
    - The total number of books checked out in the current month.
    - Implement a search feature that allows users to filter books by partial matches of title and author's name.
    - Add a feature to filter books based on publication date ranges (e.g., books published in the last five years).
    - GET a list of authors who have written more than five books.
    - Update the quantity of books in stock based on checkouts and returns 
    - Create a custom lookup that allows users to search for books based on a rating system (e.g., highly rated books).


## Frontend Requirements

- Develop a simple and clean user interface using Django Templates.
- Code should be clean and efficient

## Backend Requirements

- Use Django 4.x or newer and Python 3.8+.
- Use PostgreSQL as the database backend.
- Write custom model manager methods to encapsulate common queries.
- Include an admin interface with customized admin models.

## Git Guidelines

- Use a public GitHub repository for the project.
- Structure commits with clear and descriptive messages.
- Implement feature branches for development of new features.
- Merge features into the main branch using Pull Requests (PRs).
- Each PR should pass all tests and include updated documentation before merging.

## README Requirements

- Detailed project setup instructions.
- Explanation of the ORM advanced features used.
- Description of RESTful endpoints and how to interact with them.
- Guide to navigating the admin interface.
- Optional: Include a Postman collection or Swagger documentation for API endpoints.

## Bonus Points

- Write unit tests and integration tests for the application.
- Use Django's class-based views or viewsets where appropriate.
- Implement caching to optimize performance.
- Provide a docker-compose.yml for easy setup.

## Submission Instructions

- Provide the GitHub repository URL with your completed project.
- Ensure the repository is public and can be cloned without restrictions.
- Your submission should be a fully functional Django application that meets all of the above requirements.
- Bonus points will be awarded for additional features, clean code, adherence to best practices, and comprehensive documentation.
- Email the test at : aryan@agrexai.com
