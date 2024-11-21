Core Principles
Write concise, technical responses with accurate Python examples.
Prioritize SOLID principles and clean architecture.
Follow Python best practices (PEP 8) to ensure consistency and readability.
Design for scalability and maintainability to allow the system to grow with ease.
Prefer iteration and modularization over duplication to promote code reuse.
Use consistent and descriptive names for variables, methods, and classes to improve readability.
Dependencies
Use a dependency manager like pip or poetry.
Target Python 3.9+.
Follow framework-specific recommendations (e.g., FastAPI, Flask, Django).
Python Standards
Leverage Python 3.9+ features when appropriate (e.g., type annotations, dataclasses, structural pattern matching).
Adhere to PEP 8 for code style and PEP 484 for type hints.
Always enable strict typing with type annotations for functions, methods, and variables.
Use virtual environments (venv or poetry) for dependency isolation.
Implement robust error handling and logging:
Use Python's logging module for structured logging.
Create custom exceptions when necessary.
Employ try-except blocks for expected exceptions.
Follow framework-specific conventions for project structure and file naming.
Python Best Practices
Use frameworks and libraries suited to the project (e.g., FastAPI for APIs, SQLAlchemy for ORM).
Adhere to RESTful or GraphQL principles when building APIs.
Optimize performance with caching solutions like redis or memcached.
Use asynchronous programming with asyncio or frameworks like FastAPI to handle concurrent operations efficiently.
Design reusable components and implement Service and Repository patterns.
Implement comprehensive testing using pytest for unit and integration tests.
Leverage task queues (e.g., Celery, RQ) for background tasks and long-running processes.
Use descriptive docstrings and comments to improve code clarity and maintainability.
Code Architecture
Naming Conventions:
Follow PEP 8 guidelines:
Classes: PascalCase.
Functions and variables: snake_case.
Constants: UPPER_SNAKE_CASE.
Organize project files by feature or module.
Use descriptive names for modules, packages, and classes.
Controller/Service Design (FastAPI/Django):
Keep controllers (e.g., API endpoint handlers) thin.
Use service classes or modules for complex business logic.
Avoid injecting dependencies directly into controllers; use dependency injection frameworks or decorators.
Models and Database:
Use an ORM like SQLAlchemy or Django ORM for database interactions.
Define clear relationships (e.g., OneToMany, ManyToMany).
Implement database migrations using tools like Alembic or Django migrations.
Optimize queries with indexes and query optimization techniques.
Type Declarations:
Use explicit type hints for functions, method arguments, and return types.
Leverage Python's typing module (Optional, Union, TypedDict, etc.) for clarity.
Use dataclasses (dataclasses.dataclass) for structured data representation.
Error Handling:
Use structured logging with the logging module for monitoring.
Create custom exceptions for domain-specific errors.
Use try-except blocks to handle expected errors gracefully.
Log errors and provide appropriate error responses in APIs.
Key Points
Follow an MVC or similar architecture to separate concerns cleanly.
Implement request validation using libraries like pydantic (e.g., FastAPI) or Django forms.
Use Python's standard library or frameworks for authentication and authorization.
Build REST APIs with consistent response formats using serializers (pydantic, marshmallow, etc.).
Leverage Python's schedule or Celery for task scheduling and automation.
Implement database transactions with ORM methods or raw SQL for data integrity.
Use caching solutions for performance optimization.
Follow a versioning strategy for APIs to maintain backward compatibility.
Ensure comprehensive logging and error handling throughout the application.
