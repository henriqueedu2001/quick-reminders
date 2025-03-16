# Conventional Commits

The commit message structure

```
<type>[optional scope]: <description>

[optional body]

[optional footer]
```

## Types


| Type       | Description                                                                 |
|------------|-----------------------------------------------------------------------------|
| `feat`     | A new feature.                                                              |
| `fix`      | A bug fix.                                                                  |
| `docs`     | Documentation changes (e.g., README, comments).                             |
| `style`    | Changes that do not affect the code's logic (e.g., formatting, linting).    |
| `refactor` | Code changes that neither fix a bug nor add a feature (e.g., restructuring).|
| `test`     | Adding or modifying tests.                                                  |
| `chore`    | Maintenance tasks (e.g., updating dependencies, CI/CD configuration).       |
| `ci`       | Changes to CI/CD configuration or scripts.                                  |
| `build`    | Changes that affect the build system or external dependencies.              |
| `perf`     | Performance improvements.                                                   |
| `revert`   | Reverts a previous commit.                                                  |

## Scope
The `scope` specifies the part of the codebase affected by the commit. For example:
- `feat(api): add user authentication`
- `fix(ui): resolve button alignment issue`

## Description
The description of the change is short and imperative. For example:
- `feat: add user login functionality`
- `fix: prevent null pointer exception`

## Body
The body is a detailed explanation of the changes. Use this for complex commits. For example:
```
feat: add user login functionality

- Implemented JWT-based authentication
- Added login and logout endpoints
- Updated user schema to include tokens
```

## Examples

1. **Simple feature commit:**
   ```
   feat: add dark mode toggle
   ```

2. **Feature commit with scope:**
   ```
   feat(ui): add dark mode toggle
   ```

3. **Bug fix commit:**
   ```
   fix: resolve login button alignment issue
   ```

4. **Commit with body and footer:**
   ```
   feat(api): add user authentication

   - Implemented JWT-based authentication
   - Added login and logout endpoints
   - Updated user schema to include tokens

   Closes #123
   ```