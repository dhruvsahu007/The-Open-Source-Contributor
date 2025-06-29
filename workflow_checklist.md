# Open Source Contribution Workflow Checklist

## Phase 1: Project Selection and Setup

### Research Phase
- [ ] Browse GitHub for suitable projects
- [ ] Evaluate project activity (recent commits, responsive maintainers)
- [ ] Check for "good first issue" or "help wanted" labels
- [ ] Read project README and CONTRIBUTING guidelines
- [ ] Check project's code of conduct
- [ ] Verify the project is in a language/framework you're comfortable with
- [ ] Look for projects with clear documentation and setup instructions

### Project Evaluation
- [ ] Check last commit date (should be within last 3 months)
- [ ] Review recent issues and PRs for maintainer responsiveness
- [ ] Look for existing "good first issues" or beginner-friendly tasks
- [ ] Verify the project has tests and CI/CD setup
- [ ] Check if the project has a community (Discord, Slack, etc.)
- [ ] Ensure the project has clear contribution guidelines

### Setup Phase
- [ ] Fork the repository on GitHub
- [ ] Clone your fork locally
- [ ] Set up the development environment
- [ ] Install dependencies
- [ ] Run the project locally to ensure it works
- [ ] Open the project in Cursor
- [ ] Allow Cursor to index the entire codebase
- [ ] Test that Cursor's AI features work (@ referencing, repo-wide chat)

## Phase 2: Issue Analysis and Selection

### Issue Research
- [ ] Browse open issues in the repository
- [ ] Look for issues labeled "good first issue", "help wanted", or "bug"
- [ ] Read issue descriptions thoroughly
- [ ] Check for recent activity on issues
- [ ] Look for issues that are well-described and scoped appropriately
- [ ] Avoid issues that are too complex or require deep domain knowledge

### Issue Selection Criteria
- [ ] Issue is clearly described with steps to reproduce
- [ ] Issue is within your skill level
- [ ] Issue hasn't been assigned to someone else
- [ ] Issue is recent and still relevant
- [ ] Issue has enough context to understand the problem
- [ ] Issue doesn't have conflicting solutions already proposed

### Pre-Work Communication
- [ ] Comment on the issue expressing interest
- [ ] Ask clarifying questions if needed
- [ ] Mention your experience level and approach
- [ ] Wait for maintainer response before starting work
- [ ] Get confirmation that the issue is still available

## Phase 3: Codebase Understanding

### Initial Analysis
- [ ] Use Cursor's AI features to understand the project structure
- [ ] Ask AI about the main entry points and architecture
- [ ] Identify key modules and their purposes
- [ ] Understand the project's coding conventions and style
- [ ] Look at existing tests to understand testing patterns
- [ ] Review similar functions or features to understand patterns

### Deep Dive
- [ ] Use @ referencing to explore specific functions and classes
- [ ] Ask AI about the files involved in your issue
- [ ] Understand how different parts of the code interact
- [ ] Look at the git history for context on recent changes
- [ ] Check for related issues or PRs
- [ ] Understand the project's dependency structure

### Issue-Specific Analysis
- [ ] Identify all files that need to be modified
- [ ] Understand the root cause of the issue
- [ ] Plan your approach to fixing the issue
- [ ] Consider edge cases and potential side effects
- [ ] Think about testing strategy
- [ ] Consider documentation updates needed

## Phase 4: Development

### Branch Setup
- [ ] Create a new branch from the main branch
- [ ] Use a descriptive branch name (e.g., `fix-issue-123` or `add-feature-x`)
- [ ] Ensure you're working on the latest version of the main branch
- [ ] Set up your development environment for the specific changes

### Implementation
- [ ] Write code following the project's style and conventions
- [ ] Use Cursor's AI to help with code generation and style matching
- [ ] Make small, focused commits with clear messages
- [ ] Test your changes as you go
- [ ] Ask AI for help when you encounter issues
- [ ] Keep changes minimal and focused on the specific issue

### Code Quality
- [ ] Follow the project's coding standards
- [ ] Add appropriate comments and documentation
- [ ] Ensure your code is readable and maintainable
- [ ] Use meaningful variable and function names
- [ ] Avoid code duplication
- [ ] Consider performance implications

## Phase 5: Testing

### Test Development
- [ ] Write unit tests for your changes
- [ ] Follow the project's testing conventions
- [ ] Ensure good test coverage
- [ ] Test edge cases and error conditions
- [ ] Use AI to help generate comprehensive tests
- [ ] Make sure tests are clear and well-documented

### Test Execution
- [ ] Run the existing test suite to ensure nothing is broken
- [ ] Run your new tests to verify they pass
- [ ] Run integration tests if applicable
- [ ] Test manually to verify the fix works
- [ ] Test on different environments if possible
- [ ] Check for any linting or style issues

### Quality Assurance
- [ ] Review your own code before submitting
- [ ] Use AI to review your changes for potential issues
- [ ] Check that your solution actually fixes the issue
- [ ] Ensure you haven't introduced new bugs
- [ ] Verify that your changes don't break existing functionality
- [ ] Consider the impact on other parts of the system

## Phase 6: Documentation

### Code Documentation
- [ ] Add or update code comments where necessary
- [ ] Update function/class documentation if needed
- [ ] Ensure your code is self-documenting
- [ ] Add inline comments for complex logic
- [ ] Update API documentation if applicable

### Project Documentation
- [ ] Update README if your changes affect setup or usage
- [ ] Update any relevant documentation files
- [ ] Add examples if you've added new features
- [ ] Update changelog if the project has one
- [ ] Consider adding migration guides if needed

## Phase 7: Pull Request Preparation

### Pre-Submission Checklist
- [ ] All tests pass locally
- [ ] Code follows project style guidelines
- [ ] Changes are focused and minimal
- [ ] Commit messages are clear and descriptive
- [ ] Branch is up to date with main
- [ ] No unnecessary files are included

### Pull Request Creation
- [ ] Push your branch to your fork
- [ ] Create a pull request against the main repository
- [ ] Write a clear and descriptive PR title
- [ ] Write a detailed PR description explaining:
  - What the issue was
  - How you fixed it
  - What changes you made
  - How to test the changes
- [ ] Reference the issue number in the PR description
- [ ] Add appropriate labels if the project uses them
- [ ] Request review from maintainers if applicable

### PR Description Template
```
## Description
Brief description of what this PR does.

## Related Issue
Fixes #[issue number]

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Test addition

## Testing
- [ ] All existing tests pass
- [ ] New tests added for new functionality
- [ ] Manual testing completed

## Checklist
- [ ] Code follows project style guidelines
- [ ] Self-review completed
- [ ] Documentation updated if needed
```

## Phase 8: Review and Iteration

### Responding to Reviews
- [ ] Read all review comments carefully
- [ ] Respond to each comment professionally
- [ ] Make requested changes promptly
- [ ] Ask for clarification if needed
- [ ] Push updates to your branch
- [ ] Thank reviewers for their feedback

### Iteration
- [ ] Make any necessary changes based on feedback
- [ ] Test changes after modifications
- [ ] Update PR description if needed
- [ ] Keep the conversation professional and constructive
- [ ] Be patient with the review process

## Phase 9: Completion and Follow-up

### After Merge
- [ ] Celebrate your contribution!
- [ ] Update your contribution tracker
- [ ] Document what you learned
- [ ] Consider what you could improve next time
- [ ] Look for other issues you could work on

### Continuous Improvement
- [ ] Reflect on the process and identify areas for improvement
- [ ] Document effective AI prompts and techniques
- [ ] Consider contributing to the same project again
- [ ] Share your experience with others
- [ ] Apply lessons learned to future contributions

## Phase 10: Documentation and Reflection

### Project Documentation
- [ ] Update your contribution tracker with final results
- [ ] Document the entire process in your README
- [ ] Include links to your pull requests
- [ ] Summarize what you learned
- [ ] Note any challenges and how you overcame them

### Personal Reflection
- [ ] What went well?
- [ ] What could have been better?
- [ ] How effective were the AI tools?
- [ ] What would you do differently next time?
- [ ] What skills did you develop?

---

**Remember**: This checklist is a guide. Adapt it to your specific project and needs. The key is to be thorough, professional, and focused on making meaningful contributions to the open source community. 