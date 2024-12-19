# Django Assessment: Book Borrowing API

## Overview

This assessment is designed to evaluate your expertise in building a Django web application while adhering to **clean architecture principles**, maintaining **clean code**, and implementing **design patterns** such as the **repository pattern**. The focus is on creating a simple and functional RESTful API for managing books and borrowing records.

---

## Functional Requirements

1. **Manage Books**:
   - Add, edit, delete, and view books.
   - Each book should have:
     - `Title`
     - `Author` (string input)
     - `ISBN`
     - `Available copies`.

2. **Borrow Books**:
   - Allow members to borrow books, decreasing the available copies.
   - Ensure no member borrows more than **2 books** at a time.

3. **List Borrowed Books**:
   - Provide an endpoint to list all books borrowed by a specific member.

---

## Technical Requirements

1. **Project Structure**:
   - Use **clean architecture** principles:
     - `core` for business logic.
     - `application` for services (e.g., borrowing logic).
     - `infrastructure` for database operations (Django models).
     - `interfaces` for API endpoints.

2. **Repository Pattern**:
   - Implement repositories to abstract data access for books and borrowing records.

3. **REST API**:
   - Build RESTful APIs using Django REST Framework (DRF) for:
     - Managing books.
     - Borrowing books.
     - Listing borrowed books.

4. **Postman Collection**:
   - Provide a Postman collection covering all API endpoints with example requests and responses.

5. **Documentation**:
   - Use **Swagger** or DRF schema generation for API documentation.

6. **Testing**:
   - Write basic unit tests for the repository and service logic.

---
## Deliverables

1. **Codebase**:
   - A well-structured project adhering to clean architecture.
   - Meaningful commit messages.

2. **Postman Collection**:
   - A collection covering all endpoints, including sample requests and responses.

3. **Testing**:
   - Unit tests for repositories and service logic.

---

## Acceptance Criteria

- Clean and modular code following clean architecture principles.
- Proper abstraction of data access using the repository pattern.
- RESTful API design with appropriate HTTP methods and status codes.
- Functional endpoints for managing books, borrowing books, and listing borrowed books.
- Unit tests demonstrating proper functionality.
- A working Postman collection with valid sample payloads.

---

## Evaluation Criteria

1. **Clean Architecture**:
   - Proper separation of concerns and modular design.

2. **Code Quality**:
   - Readable, maintainable, and well-documented code.

3. **Repository Pattern**:
   - Effective abstraction of data access logic.

4. **API Design**:
   - RESTful principles and clear endpoint definitions.

5. **Testing**:
   - At least basic unit tests for repository and service logic.

6. **Postman Collection**:
   - Properly configured with sample requests and responses.

---

## Timeline

This assessment is designed to be completed within **10 hours**.

---

## Submission Instructions

1. Fork this repository to your GitHub account.
2. Complete the assessment in your forked repository.
3. Ensure your repository includes:
   - The full codebase.
   - Unit tests.
   - Postman collection (`postman_collection.json`).
   - Any additional documentation or notes in the `README.md`.
4. Share the link to your forked repository with us.

---

## Questions?

If you have any questions about the assessment, feel free to reach out!
