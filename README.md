# Innovation Team Sub-Agents - Complete Toolkit

# Claude Code Sub-Agents

A collection of 4 specialized sub-agents for Claude Code that handle the complete product development workflow - from planning to presentation.

## Quick Start

1. Copy the agent files to your `.claude/agents/` directory (project-level) or `~/.claude/agents/` (user-level)
2. Use `/agents` command to manage and configure
3. Agents will activate automatically based on your requests

## The 4 Core Agents

### 🎯 `ai-dev-task-master`
**Creates comprehensive development plans from feature requests**

- Transforms complex features into detailed PRDs and structured task breakdowns
- Provides architectural guidance with code examples
- Researches best practices and analyzes existing codebases
- Delivers complete roadmaps ready for implementation

**Example:** *"Build user authentication with social logins"* → Complete PRD + 47 structured development tasks

---

### 🚀 `prototype-builder` 
**Builds production-ready interactive prototypes**

- Creates sophisticated HTML prototypes using modern web technologies
- Professional iconography with Ionicons (1,300+ icons)
- Interactive components with smooth animations and responsive design
- Delivers working prototypes that feel like real products

**Example:** *"Create a dashboard for expense tracking"* → Complete interactive prototype with charts and navigation

---

### 📚 `docs-expert`
**Creates clear, practical documentation**

- Generates complete documentation files with working examples
- API references, user guides, tutorials, and technical documentation  
- Progressive complexity with practical examples throughout
- Professional formatting ready for immediate use

**Example:** *"Document our authentication API"* → Complete API docs with examples and integration guides

---

### 📊 `presentation-architect`
**Builds professional HTML presentations**

- Creates complete presentation files using Reveal.js and Chart.js
- Interactive data visualizations from uploaded files
- Professional styling with speaker notes and mobile responsiveness
- Self-contained files ready for immediate presentation

**Example:** *"Present Q4 results to the board"* → Professional HTML presentation with interactive charts

## Workflow Examples

### Complete Feature Development
```
1. ai-dev-task-master: "Plan user onboarding system"
   → Get PRD + task breakdown

2. prototype-builder: "Create onboarding prototype" 
   → Get working interactive prototype

3. docs-expert: "Document the onboarding API"
   → Get complete documentation

4. presentation-architect: "Create stakeholder presentation"
   → Get professional presentation
```

### Validation & Testing
```
1. prototype-builder: "Build concept prototype for testing"
   → Get testable prototype

2. docs-expert: "Create user testing guide"  
   → Get testing documentation
   
3. presentation-architect: "Present testing results"
   → Get results presentation
```

## Agent Capabilities

| Agent | Input | Output | Tools Used |
|-------|-------|--------|------------|
| `ai-dev-task-master` | Feature requests | PRDs + Task lists + Code examples | `repl`, `google_drive_search`, `web_search` |
| `prototype-builder` | Concept descriptions | Working HTML prototypes | `repl` |
| `docs-expert` | Documentation needs | Complete documentation files | `repl`, `google_drive_search`, `web_search` |
| `presentation-architect` | Data + presentation needs | Professional HTML presentations | `repl`, `google_drive_search` |

## Installation

### Project-Level (Recommended)
```bash
# Copy agents to your project
cp agents/*.md .claude/agents/
```

### User-Level  
```bash
# Copy agents to your user directory
cp agents/*.md ~/.claude/agents/
```

### Verification
```bash
# List available agents
claude /agents
```

## Best Practices

### When to Use Each Agent

**Use `ai-dev-task-master` when:**
- Breaking down complex features into manageable tasks
- Creating technical requirements and specifications
- Planning development workflows and architecture

**Use `prototype-builder` when:**
- Testing concepts with interactive demos
- Creating stakeholder presentations that need interaction
- Building proof-of-concepts for validation

**Use `docs-expert` when:**  
- Creating API documentation or user guides
- Writing technical tutorials and getting started guides
- Documenting complex features or processes

**Use `presentation-architect` when:**
- Presenting data-driven insights to stakeholders
- Creating board presentations or investor decks
- Visualizing metrics, results, or strategic analysis

### Agent Chaining
Agents are designed to work together in workflows:
- `ai-dev-task-master` → `prototype-builder` (plan then build)
- `prototype-builder` → `docs-expert` (build then document)  
- Any agent → `presentation-architect` (create then present)

## Technical Details

- **File Format**: Markdown with YAML frontmatter
- **Context**: Each agent uses separate context windows  
- **Tools**: Agents inherit tools from main thread unless specified
- **Priority**: Project-level agents override user-level agents

## Contributing

1. Test agents thoroughly with realistic use cases
2. Ensure outputs are immediately usable without additional setup
3. Follow the established quality standards for each agent type
4. Update documentation with new capabilities or workflows

## License

MIT License - Use freely in your projects and share with your team.
