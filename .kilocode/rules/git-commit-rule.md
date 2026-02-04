### Objective

Ensure all commit messages follow the Conventional Commits specification.

### Mandatory Rules

- You MUST generate commit messages in this exact format:

  `<type>: <summary>`

- `<type>` MUST be one of:
  - `feat`
  - `fix`
  - `docs`
  - `style`
  - `refactor`
  - `perf`
  - `test`
  - `chore`

- `<summary>` MUST:
  - Be written in an imperative way
  - Be 72 characters or fewer
  - Contain no emojis, markdown, quotes, or explanations

### Output Rules

- When asked to generate a commit message:
  - You MUST output ONLY the final commit message
  - You MUST NOT include commentary, formatting, or extra text
