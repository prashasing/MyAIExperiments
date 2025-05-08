# Code Style Guidelines

## General Guidelines
- Use descriptive variable and function names.
- Avoid hardcoding; use configuration files where applicable.
- Write clean, readable, and maintainable code.

## C# Specific Guidelines
- Use PascalCase for class names and method names.
- Use camelCase for local variables and parameters.
- Place braces on the next line for methods and class definitions.
- Avoid using `var` unless the type is obvious.
- The controller actions in the web api should accept not more than 3 arguments.

## TSQL Specific Guidelines
- Use uppercase for SQL keywords (e.g., `SELECT`, `INSERT`, `UPDATE`).
- Use meaningful aliases for columns and tables.
- Avoid using `SELECT *`; explicitly specify column names.

## Documentation
- Add XML comments for public methods and classes in C#.
- Ensure all new methods and classes have clear and concise documentation.

## Testing
- Include unit tests for all new features.
- Ensure test coverage is above 90%.
Step 3: Integrate with PR Reviews
Add a PULL_REQUEST_TEMPLATE.md file in the .github directory.
Reference the code style guidelines in the template:
Markdown
## Pull Request Checklist

- [ ] Code adheres to the [Code Style Guidelines](./codestyle-guidelines.md).
- [ ] Tests have been added or updated.
- [ ] All commits are meaningful and follow conventions.

## Additional Notes
Please ensure the PR meets the re