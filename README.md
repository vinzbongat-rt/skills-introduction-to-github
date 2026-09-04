# GitHub Copilot Skills

A hands-on learning repository for building effective, safe GitHub Copilot habits.

## Learning goals

By working through these skills, you will learn to:

- Give Copilot clear context, constraints, and acceptance criteria.
- Use chat, inline suggestions, and agent mode for the right kind of task.
- Review, test, and refine AI-generated code instead of accepting it blindly.
- Protect secrets, privacy, and project conventions while using AI assistance.

## Skill path

Work through the skills in order. Keep each exercise in a branch and open a pull request when it is complete.

| Skill | Practice | Outcome |
| --- | --- | --- |
| 1. Prompting with context | Ask Copilot to explain a small part of a codebase and propose a scoped change. | A prompt that names the goal, relevant files, constraints, and success criteria. |
| 2. Generating code | Ask Copilot for a small implementation with tests. | A reviewed change where tests describe the intended behavior. |
| 3. Debugging | Provide an error message, reproduction steps, and expected behavior. | A root-cause explanation and a minimal verified fix. |
| 4. Reviewing code | Use Copilot to summarize a diff and identify edge cases. | Review notes that you independently verify before acting on them. |
| 5. Working with agents | Delegate a well-bounded task with repository conventions and validation steps. | A plan, implementation, and evidence that the requested checks pass. |

## Prompt template

Use this template to make requests specific and reviewable:

```text
Goal: <the outcome to achieve>
Context: <relevant files, behavior, or error>
Constraints: <scope, compatibility, style, and dependencies>
Acceptance criteria: <observable results and tests>
Please explain the proposed approach before changing files.
```

## Practice workflow

1. Read the relevant code and existing tests before prompting.
2. Ask for a small, explicit change using the template above.
3. Review the suggestion for correctness, security, and unintended scope.
4. Run the project's existing targeted tests or checks.
5. Record what worked, what you changed, and what you will try differently.

## Responsible use checklist

Before committing AI-assisted work:

- [ ] I understand the code and can explain the change.
- [ ] I checked generated code for correctness, security, and licensing fit.
- [ ] I did not provide secrets, private data, or sensitive customer information.
- [ ] I ran relevant tests and reviewed the diff.
- [ ] I documented any assumptions or follow-up work.

## Suggested first exercise

Choose a small issue in a project you know. Use the prompt template to ask Copilot to propose a minimal fix and a targeted test. Review the proposal, implement only the parts you understand, and open a pull request that explains the validation performed.

## Resources

- [GitHub Copilot documentation](https://docs.github.com/copilot)
- [GitHub Copilot best practices](https://docs.github.com/copilot/using-github-copilot/best-practices-for-using-github-copilot)
