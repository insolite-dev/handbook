# Engineering

Welcome to the Engineering section of the Insolite Company Handbook. This section provides an overview of our company's general engineering best practices and technology stack, which apply across all projects.

## Best Practices
At Insolite, we prioritize minimalist, well-documented, and easily testable code to ensure the highest quality and maintainability of our projects.
Here is some projects that applies our prefered style codes:
- [notya](https://github.com/insolite-dev/notya) - Go(lang)
- [mate](https://github.com/theiskaa/mate) - Rust
- [field_suggestion](https://github.com/insolite-dev/field_suggestion) - Dart/Flutter
- [hidable](https://github.com/insolite-dev/hidable) - Dart/Flutter

## Source Management Best Practices
In order to maintain clean and organized version control, we have established a set of guidelines for committing and branching in our projects.

### Commits
We use a standardized commit message template to help track changes and maintain a clean history. Here are the guidelines:

- For new feature implementations, use `feat: <your-message-here>` as the commit message.
- For bugfixes or small changes, use `bugfix: <your-message-here>` or `hotfix: <your-message-here>`.
- For non-feature or non-bugfix changes, use `chore: <your-message-here>`.

Please note that each commit should include only one change or topic to ensure clear and concise version control.

### Branching

Our repository follows a branching structure designed to promote efficient and organized development. Here is an overview of the branches:
- `main`: The release branch. Only develop can be merged directly into main.
- `develop`: The active development branch that may contain bugs or incomplete features.
- `feature/...`: Branches created for specific feature implementations.
- `bugfix/...`: Branches created for fixing specific bugs.
- `bump/v1...`: Branches created for version bumps.

All `feature/...`, `bugfix/...`, and `bump/v1...` branches must be merged into develop and not main.

By following these guidelines, we can ensure a clean and organized version control history, making it easier to track changes and collaborate with others.

## Technology Stack
At Insolite, we aim to build high-performance and scalable applications, and our technology stack is carefully chosen to provide a solid foundation for achieving these goals.
While we typically prefer to use **Rust** as our primary programming language for all aspects of our projects, including web, CLI, and backend development, we remain open to exploring alternative technologies when appropriate.
For example, we have used **Go**, **TypeScript**, and **Flutter/Dart** in certain cases for their unique strengths and benefits.

We're committed to staying up-to-date with the latest tools and technologies in the industry, as well as experimenting with new options that can improve our development process and project outcomes. Our team is always eager to receive suggestions and feedback from our community, so if you have any questions or ideas about our tech stack, please don't hesitate to reach out to us.
