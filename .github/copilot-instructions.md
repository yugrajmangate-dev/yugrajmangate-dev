# GitHub Copilot instructions

## Project context
- Tech stack: JavaScript/TypeScript, Python, Java, C/C++
- Architecture: Modular design with clear separation of concerns
- Focus: Hackathon projects, competitive programming, and portfolio development

## Coding style
- Use camelCase for JavaScript/TypeScript
- Use snake_case for Python
- Use PascalCase for Java classes
- Prefer meaningful variable and function names
- Keep functions small and focused on single responsibility
- Write clear comments for complex logic

## Testing
- Always add or update tests for new or changed behavior
- Use Jest for JavaScript/TypeScript projects
- Use pytest for Python projects
- Aim for at least 80% code coverage
- Write integration tests for critical features

## Security & reliability
- Never commit API keys, tokens, or secrets to the repository
- Use environment variables for sensitive configuration
- Validate all external input and user data
- Use parameterized queries for database access when applicable
- Follow OWASP security best practices

## Git practices
- Write clear, descriptive commit messages
- Use present tense in commit messages ("Add feature" not "Added feature")
- Keep commits atomic and focused
- Create feature branches for new work
- Ensure all tests pass before creating pull requests

## Documentation
- Add README.md to all projects with:
  - Project description
  - Setup instructions
  - Usage examples
  - Contributing guidelines
- Document complex algorithms or non-obvious code logic
- Keep documentation up to date with code changes

## Performance
- Consider time and space complexity when implementing algorithms
- Use appropriate data structures for the use case
- Avoid hardcoding values; use constants or configuration
- Profile code for optimization in performance-critical sections

## Boundaries (do NOT edit)
- Do not modify GitHub Actions workflows without explicit request
- Do not delete .gitignore files
- Do not commit node_modules, __pycache__, or other generated directories
- Do not modify existing database migration files

## Libraries & dependencies
- Prefer built-in language features and standard libraries
- Justify new dependencies with reasoning before adding
- Keep dependencies up to date but stable
- Avoid deprecated libraries

## How to run checks
- Tests: `npm test` or `pytest`
- Linting: `npm run lint` or similar for your project
- Build: `npm run build` or project-specific build command
- All checks should pass before pushing to main branch
