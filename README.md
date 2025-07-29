# Claude Code Sub-Agents for Product Builders

A collection of 4 specialized sub-agents designed for hybrid product/engineers who build products end-to-end - from concept validation to stakeholder presentation.

## Who This Is For

**Product builders who code** - the hybrid product/engineers who:
- 🚀 Build products from idea to launch (not just implement tickets)
- 🧪 Need to validate concepts before heavy development investment
- 💼 Present progress to stakeholders, investors, and users
- 📋 Plan features and break down complex product requirements
- 🎨 Create prototypes for user testing and concept validation
- 📖 Document products for non-technical users and team members

**Not for** pure developers who focus solely on implementation within existing codebases.

## Quick Start

1. Copy the agent files to your `.claude/agents/` directory (project-level) or `~/.claude/agents/` (user-level)
2. Use `/agents` command to manage and configure
3. Agents will activate automatically based on your requests

## The 4 Product Building Agents

### 🎯 `ai-dev-task-master`
**Transforms product ideas into structured development plans**

Perfect for breaking down that ambitious feature idea into actionable development work.

- Creates comprehensive PRDs from rough product concepts
- Generates structured task breakdowns with clear implementation order
- Provides architectural guidance and identifies technical dependencies
- Researches industry patterns and analyzes existing product architecture

**Product Builder Scenario:** *"I want to add AI-powered expense categorization to my fintech app"* → Complete PRD + 47 structured development tasks with technical guidance

---

### 🚀 `prototype-builder` 
**Builds testable product prototypes for validation**

Essential for testing product concepts before committing to full development.

- Creates sophisticated interactive prototypes that feel like real products
- Uses professional iconography (Ionicons) and modern web technologies
- Responsive design with smooth animations and micro-interactions
- Perfect for user testing, stakeholder demos, and investor presentations

**Product Builder Scenario:** *"I need to test if users understand my onboarding flow"* → Working interactive prototype ready for user testing

---

### 📚 `docs-expert`
**Creates user-facing product documentation**

Bridges the gap between technical implementation and user understanding.

- Generates complete user guides, API documentation, and feature explanations
- Progressive complexity that works for both technical and non-technical audiences
- Working examples and practical use cases throughout
- Professional formatting ready for customer-facing documentation

**Product Builder Scenario:** *"I need to document our API for third-party developers"* → Complete API docs with examples and integration guides

---

### 📊 `presentation-architect`
**Builds data-driven stakeholder presentations**

Turn your product metrics and progress into compelling stakeholder communications.

- Creates professional HTML presentations with interactive data visualizations
- Processes uploaded data (CSV, Excel) into Chart.js visualizations
- Self-contained presentations ready for board meetings or investor updates
- Mobile-responsive with speaker notes and professional styling

**Product Builder Scenario:** *"Present our user growth metrics to investors"* → Professional presentation with interactive charts and executive summary

## Product Development Workflows

### 💡 Concept to Launch
```
1. ai-dev-task-master: "Plan social login feature"
   → Get comprehensive development roadmap

2. prototype-builder: "Create login flow prototype" 
   → Get testable prototype for user validation

3. [Build the actual feature based on validated prototype]

4. docs-expert: "Document authentication for developers"
   → Get customer-facing API documentation

5. presentation-architect: "Present feature impact metrics"
   → Get stakeholder presentation showing results
```

### 🧪 Rapid Validation Cycle
```
1. prototype-builder: "Build concept prototype for user testing"
   → Get working prototype

2. [Test with actual users]

3. prototype-builder: "Iterate based on user feedback"
   → Get improved prototype

4. presentation-architect: "Present validation results"
   → Get stakeholder presentation with learnings
```

### 📈 Feature Planning & Execution
```
1. ai-dev-task-master: "Break down marketplace feature"
   → Get structured development plan

2. [Execute development in phases]

3. docs-expert: "Create user guide for marketplace"
   → Get user-facing documentation

4. presentation-architect: "Show marketplace adoption metrics"
   → Get results presentation for stakeholders
```

## When Product Builders Use Each Agent

| Product Challenge | Agent Solution | Typical Output |
|------------------|----------------|----------------|
| "This feature idea is too complex to start coding" | `ai-dev-task-master` | Structured development plan with clear phases |
| "I need to test this concept with users first" | `prototype-builder` | Interactive prototype for user testing |
| "Users don't understand how to use this feature" | `docs-expert` | Clear user guides and tutorials |
| "I need to show progress to investors/stakeholders" | `presentation-architect` | Professional presentation with metrics |

## Product Builder Personas

### 🦄 **Solo Founder**
Building an MVP and wearing all hats - PM, designer, engineer, marketer
- Uses all 4 agents throughout the product development cycle
- Relies heavily on prototyping for validation before building
- Needs professional presentations for fundraising

### 👥 **Small Team Technical Lead** 
Leading product development in a 2-5 person startup
- Uses task-master for feature planning and team coordination
- Creates prototypes for stakeholder alignment
- Documents features for non-technical team members

### 🛠️ **Product Engineer**
Technical team member who bridges product and engineering
- Breaks down product requirements into technical tasks
- Builds prototypes for design and user research collaboration
- Creates technical documentation for product features

### 🚀 **Indie Hacker**
Building products independently for specific markets
- Heavy prototype usage for market validation
- Documentation for users and potential customers
- Presentations for partnerships and business development

## Installation & Setup

### Project-Level (Recommended for product teams)
```bash
cp agents/*.md .claude/agents/
```

### User-Level (For individual product builders)
```bash
cp agents/*.md ~/.claude/agents/
```

### Verify Installation
```bash
claude /agents
```

## Product Development Best Practices

- **Start with validation**: Use `prototype-builder` before heavy development investment
- **Plan before building**: Use `ai-dev-task-master` to avoid scope creep and technical debt
- **Document as you go**: Use `docs-expert` to create user-facing documentation alongside development
- **Communicate progress**: Use `presentation-architect` to keep stakeholders aligned and engaged

## Contributing

Contributions should focus on real product building workflows and challenges. Test with actual product development scenarios, not just technical implementation tasks.

## License

MIT License - Build great products!
