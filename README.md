# Strapi Expert - Claude Code Skill

A comprehensive Claude Code skill for Strapi v5 plugin development. This skill provides expert-level guidance for building production-grade Strapi plugins, custom APIs, and admin panel extensions.

## Features

- **Document Service API** - Complete guide to Strapi v5's new Document Service
- **Plugin Architecture** - Best practices based on [strapi-community/plugin-todo](https://github.com/strapi-community/plugin-todo)
- **Factory Patterns** - `createCoreService()`, `createCoreController()`, `createCoreRouter()`
- **Admin Panel Integration** - Content Manager injection zones, React Query patterns
- **Real-World Examples** - Complete plugin implementations with all components

## Installation

### Option 1: Clone to Claude Skills Directory

```bash
# Clone to your Claude Code skills directory
git clone https://github.com/YOUR_USERNAME/claude-skill-strapi-expert.git ~/.claude/skills/strapi-expert
```

### Option 2: Manual Installation

1. Create the skills directory if it doesn't exist:
   ```bash
   mkdir -p ~/.claude/skills/strapi-expert
   ```

2. Download the skill files:
   ```bash
   cd ~/.claude/skills/strapi-expert
   curl -O https://raw.githubusercontent.com/YOUR_USERNAME/claude-skill-strapi-expert/main/SKILL.md
   curl -O https://raw.githubusercontent.com/YOUR_USERNAME/claude-skill-strapi-expert/main/patterns.md
   curl -O https://raw.githubusercontent.com/YOUR_USERNAME/claude-skill-strapi-expert/main/examples.md
   ```

### Option 3: Project-Level Installation

Add to your project's `.claude/skills/` directory:

```bash
mkdir -p .claude/skills/strapi-expert
# Copy SKILL.md, patterns.md, examples.md to .claude/skills/strapi-expert/
```

## Usage

Once installed, invoke the skill in Claude Code:

```
/strapi-expert
```

Or Claude will automatically use it when working on Strapi v5 projects.

## Skill Contents

| File | Description |
|------|-------------|
| `SKILL.md` | Core skill definition with Document Service API, plugin structure, routes, controllers, services |
| `patterns.md` | Advanced patterns: lifecycle hooks, queries, React Query, Content Manager integration |
| `examples.md` | Complete plugin examples including the full plugin-todo implementation |

## What You'll Learn

### Server-Side
- Document Service API (replacing Entity Service)
- Factory-based services, controllers, and routers
- Route organization (admin vs content-api)
- Polymorphic relations with `morphToMany`
- Hidden content types for internal plugin data

### Admin Panel
- Plugin registration and bootstrapping
- Content Manager injection zones
- React Query for data fetching
- Strapi Design System components
- Internationalization with `registerTrads()`

## Example Topics

Ask Claude Code questions like:

- "How do I create a Strapi v5 plugin?"
- "Show me how to use the Document Service API"
- "How do I inject a component into the Content Manager?"
- "Create a service with custom methods using factories"
- "How do I set up polymorphic relations?"

## Requirements

- Claude Code CLI
- Strapi v5.x project (for applying the knowledge)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Adding New Patterns

1. Add patterns to `patterns.md`
2. Add real-world examples to `examples.md`
3. Update `SKILL.md` if adding new core concepts

## License

MIT License - see [LICENSE](LICENSE) for details.

## Acknowledgments

- [strapi-community/plugin-todo](https://github.com/strapi-community/plugin-todo) - Reference implementation
- [Strapi Documentation](https://docs.strapi.io/) - Official Strapi v5 docs
- [Claude Code](https://claude.ai/code) - AI-powered coding assistant

## Author

Created by [Your Name]

---

**Note**: This skill is not officially affiliated with Strapi or Anthropic. It's a community resource for Claude Code users working with Strapi.
