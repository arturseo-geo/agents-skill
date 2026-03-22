# Contributing to agents-skill

Thank you for your interest in improving this skill. Contributions that add new patterns, update framework guidance, fix inaccuracies, or improve examples are welcome.

## How to Contribute

### Reporting Issues
- Use the **Bug Report** template for incorrect or outdated content
- Use the **Framework / Pattern Update** template for new framework versions or emerging patterns
- Include specific file and section references so maintainers can locate the issue quickly

### Submitting Changes
1. Fork the repository
2. Create a feature branch: `git checkout -b update/description`
3. Make your changes
4. Test any code examples to verify they work
5. Submit a pull request using the PR template

### What Makes a Good Contribution

**Content standards:**
- All content must be original writing. Do not copy-paste from documentation, blog posts, or other repositories.
- Code examples should be functional and tested. If an example is pseudocode, mark it as such.
- When referencing frameworks, include the version you tested against.
- Credit sources in the Acknowledgments section of README.md if your contribution was inspired by external work.

**Scope:**
- `SKILL.md` is the core file loaded by Claude Code. Keep it comprehensive but focused. If a topic needs deep detail, add it to the appropriate `references/` file and link from SKILL.md.
- `references/` files provide depth. They can be longer and more detailed than SKILL.md.
- Keep examples practical. Prefer real-world patterns over toy examples.

**Style:**
- Use clear, direct language
- Use code blocks with language tags for syntax highlighting
- Use tables for comparisons
- Use decision trees (if/then) for choosing between approaches
- Avoid marketing language ("revolutionary", "game-changing")

### Areas Where Help is Needed
- New agent patterns emerging in the community
- Framework version updates (LangGraph, CrewAI, AutoGen, Claude Agent SDK)
- Real-world case studies and failure modes
- Evaluation benchmarks and results
- Security patterns for production agents

## Code of Conduct
Be respectful, constructive, and focused on improving the skill for all users.

## License
By contributing, you agree that your contributions will be licensed under the MIT License.
