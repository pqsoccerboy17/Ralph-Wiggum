# Ralph Wiggum Task Prompt

## Task
[DESCRIBE YOUR TASK HERE]

## Success Criteria
- [ ] Criterion 1
- [ ] Criterion 2
- [ ] Criterion 3

## Constraints
- Run tests after each change
- Commit working increments to git
- Do not modify files outside of [SCOPE]

## Completion
When ALL success criteria are met:
1. Run final test suite
2. Commit all changes
3. Output: <promise>COMPLETE</promise>

---

## Example: TDD Feature Implementation

### Task
Implement user profile page with the following features:
- Display user name and email
- Allow editing of display name
- Show account creation date

### Success Criteria
- [ ] Profile page renders without errors
- [ ] User data displays correctly
- [ ] Edit name form works and saves
- [ ] All tests pass
- [ ] No TypeScript errors

### Constraints
- Run `npm run test` after each change
- Commit working increments to git
- Only modify files in `/src/pages/profile/` and `/src/components/profile/`
- Follow existing code style in CLAUDE.md

### Completion
When ALL success criteria are met:
1. Run `npm run test && npm run lint`
2. Commit: `git add . && git commit -m "feat: add user profile page"`
3. Output: <promise>COMPLETE</promise>
