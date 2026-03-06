# Development Workflow

The Feature Implementation Workflow: research, planning, TDD, code review, then git.

## Feature Implementation Workflow

0. **Research & Reuse** _(mandatory before any new implementation)_
   - **GitHub code search first:** Run `gh search repos` and `gh search code` to find existing implementations before writing anything new.
   - **Check package registries:** Search npm, PyPI, etc. before writing utility code. Prefer battle-tested libraries.
   - **Search for adaptable implementations:** Look for open-source projects that solve 80%+ of the problem.
   - Prefer adopting a proven approach over writing net-new code.

1. **Plan First**
   - Use **planner** agent to create implementation plan
   - Generate planning docs before coding
   - Identify dependencies and risks
   - Break down into phases

2. **TDD Approach**
   - Use **tdd-guide** agent
   - Write tests first (RED) → Implement (GREEN) → Refactor (IMPROVE)
   - Verify 80%+ coverage

3. **Code Review**
   - Use **code-reviewer** agent immediately after writing code
   - Address CRITICAL and HIGH issues
   - Fix MEDIUM issues when possible

4. **Commit & Push**
   - Detailed commit messages, conventional commits format
