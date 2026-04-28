# Example Pull Request

## How to Create a Pull Request

1. **Fork the repository** (if you don't have write access)
2. **Create a new branch** from the main branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes** and commit them:
   ```bash
   git add .
   git commit -m "Add: descriptive commit message"
   ```

4. **Push your branch** to GitHub:
   ```bash
   git push origin feature/your-feature-name
   ```

5. **Open a Pull Request** on GitHub:
   - Go to the repository on GitHub
   - Click "Compare & pull request"
   - Fill out the PR template
   - Click "Create pull request"

## Example PR Title and Description

**Title:** `Add user authentication system`

**Description:**
```markdown
## Description
Implemented a complete user authentication system with login, registration, and password reset functionality.

## Type of Change
- [x] New feature (non-breaking change which adds functionality)

## Changes Made
- Added user registration endpoint with email validation
- Implemented JWT-based authentication
- Created login/logout functionality
- Added password reset via email
- Updated database schema with users table
- Added authentication middleware

## Testing
- [x] I have tested these changes locally
- [x] I have added/updated tests for my changes
- [x] All existing tests pass
- [x] I have tested edge cases

## Related Issues
Closes #123
Resolves #456
```

## Best Practices

- Keep PRs focused and small when possible
- Write clear, descriptive titles
- Provide detailed descriptions
- Include tests for new functionality
- Update documentation as needed
- Respond to review feedback promptly
- Keep your branch up to date with the main branch