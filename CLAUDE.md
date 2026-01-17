# Ralph Wiggum Development Project

## About the Developer
- **Non-developer user** - I rely on Claude Code to write, test, and manage code
- Always explain what you're doing in plain English before executing
- Prefer small, incremental changes that can be easily reviewed
- Ask for confirmation before any destructive or irreversible actions

## Development Workflow
Follow this cycle for all changes:
1. **Understand** - Explain what needs to be done
2. **Plan** - Show me the approach before coding
3. **Implement** - Make small, focused changes
4. **Test** - Run tests after every change
5. **Commit** - Use clear, descriptive commit messages
6. **PR** - Create pull request with summary of changes

## Commands
```bash
# Development
npm run dev          # Start development server
npm run test         # Run test suite
npm run lint         # Check code style

# Git workflow
git status           # Check what's changed
git diff             # Review changes before committing
```

## Code Style Preferences
- Write clear, readable code with comments explaining "why"
- Use TypeScript with strict mode when applicable
- Prefer named exports over default exports
- Keep functions small and focused

## Safety Rules
- **Never** commit secrets, API keys, or credentials
- **Always** run tests before creating a PR
- **Always** explain errors in plain English with suggested fixes
- **Ask** before installing new dependencies

## When Using Ralph Wiggum Plugin
- Set conservative `--max-iterations` (start with 10-20)
- Always define clear completion criteria
- Review git history after autonomous sessions
- Use for: tests, documentation, refactoring
- Avoid for: security code, architectural decisions

## Communication Style
- Explain technical concepts in simple terms
- Provide context for why something is done, not just how
- Offer to explain further if something is unclear
- Celebrate small wins to keep momentum
