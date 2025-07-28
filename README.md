# Innovation Team Sub-Agents - Starter Pack

A focused collection of 2 essential AI agents designed for fast-moving innovation teams. Built for rapid prototyping, validated learning, and eliminating common innovation bottlenecks.

## 📥 Installation

1. **Download this repository:**
   ```bash
   git clone https://github.com/your-org/innovation-agents.git
   ```

2. **Copy to your Claude Code agents directory:**
   ```bash
   cp -r innovation-agents/* ~/.claude/agents/
   ```
   
   Or manually copy all the agent files to your `~/.claude/agents/` directory.

3. **Restart Claude Code** to load the new agents.

## 🚀 Quick Start

Agents are automatically available in Claude Code. Simply describe your innovation challenge and the appropriate agent will be triggered. You can also explicitly request an agent by mentioning their name.

📚 **Learn more:** [Claude Code Sub-Agents Documentation](https://docs.anthropic.com/en/docs/claude-code/sub-agents)

### Example Usage
- "We think busy parents would pay for AI meal planning, but we're not sure" → `rapid-validator`
- "We need to test if users understand our onboarding flow" → `prototype-planner`
- "Can we build real-time collaboration features in 2 weeks?" → `prototype-planner`
- "Our signup rate is 12% but we don't know what to optimize next" → `rapid-validator`

## 📁 Agent Categories

### Essential Innovation Workflow (`core/`)
The 2 most critical agents for innovation teams:
- **rapid-validator** - Test assumptions fast and cheap with maximum learning
- **prototype-planner** - Match prototype approach to learning objectives with AI tool recommendations

## 📋 Complete Agent List

### Core Innovation Workflow
- **rapid-validator** - Validate ideas, assumptions, and prototypes with minimal resources
- **prototype-planner** - Plan rapid prototyping approaches with optimal AI tool selection

## 🎯 Design Philosophy

These agents are built for innovation teams that need to:

### Speed & Velocity
- Move from assumption to validated learning in hours/days, not weeks
- Eliminate tool selection paralysis with instant AI tool recommendations
- Generate clear signals quickly with minimal investment

### Learning Optimization
- Test the riskiest assumptions first with systematic experimentation
- Match prototype fidelity to specific learning objectives
- Balance speed with quality of insights

### Resource Efficiency
- Use existing AI tools (v0, Lovable, Bolt, Cursor, Claude Artifacts) optimally
- Minimize waste on over-engineered or under-engineered prototypes
- Maximize learning per dollar spent

## 💡 Best Practices

### Agent Collaboration Patterns
- **Assumption Testing**: `rapid-validator` designs experiments → `prototype-planner` builds the right prototype type
- **Learning Cycles**: `prototype-planner` creates testable prototype → `rapid-validator` measures results

### Innovation Velocity Tips
- **Start with validation** before building anything substantial
- **Use AI tools optimally** - let prototype-planner choose the right tool for your goal
- **Focus on learning speed** over feature completeness
- **Measure assumptions tested** not just features built

## 🔧 Technical Details

### Agent Structure
Each agent includes:
- **name**: Unique identifier for Claude Code
- **description**: When to use with specific usage examples
- **tools**: Access to web_search, repl, google_drive_search, etc.
- **System prompt**: Comprehensive expertise and methodology (500+ words)

### AI Tool Integration
The `prototype-planner` includes intelligent recommendations for:
- **v0**: Quick React components and UI testing
- **Lovable**: Full-stack apps with backend and database
- **Bolt**: Interactive demos and presentations
- **Cursor**: AI-assisted development for complex logic
- **Claude Artifacts**: Data visualization and algorithm testing
- **Replit**: Collaborative development and experimentation

### Usage Examples
Every agent includes detailed usage examples showing:
- Real team conversations that would trigger the agent
- Specific, actionable outputs the agent provides
- Context about why that example matters for innovation teams

## 📊 Success Metrics

Track innovation effectiveness through:

### Learning Velocity
- Assumption-to-validation time
- Prototype creation speed with optimal AI tools
- Experiment cycle time

### Resource Efficiency
- Learning-per-dollar-spent
- AI tool selection time savings
- Prototype iteration speed

### Decision Quality
- Percentage of assumptions validated before building
- Prototype-to-insight conversion rate
- Tool selection accuracy

## 🛠️ Future Expansion

### Next Agents to Add (Based on Usage)
- **problem-solution-finder** - Ensure you're solving real problems
- **user-research-sprinter** - Get user feedback fast
- **technical-feasibility-assessor** - Ensure technical viability
- **iteration-advisor** - Guide next steps based on results

### Planned Enhancements
- **AI tool intelligence** expansion to other agents
- **Cross-agent workflows** for complex innovation challenges
- **Real-time learning analytics** and recommendation optimization

## 🚦 Implementation Strategy

### Phase 1: Core Validation & Prototyping (Current)
Deploy `rapid-validator` and `prototype-planner` for immediate impact on innovation velocity

### Phase 2: Research & Analysis (Next)
Add `problem-solution-finder` and `user-research-sprinter` based on team usage patterns

### Phase 3: Technical & Strategic (Future)
Expand to `technical-feasibility-assessor` and `iteration-advisor` for complete innovation workflow

### Phase 4: AI-Native Innovation (Advanced)
Integrate AI tool intelligence across all agents for maximum automation and speed

## 📞 Support

For questions, customization help, or sharing success stories:
- **Internal Teams**: Contact your innovation team leads
- **Community**: Share patterns and improvements through your organization's knowledge sharing platforms
- **Technical Issues**: Follow standard Claude Code troubleshooting procedures

## 🎯 Expected Impact

### Week 1: Tool Selection Elimination
- Teams stop debating which AI tool to use for prototypes
- 2-3 hour time savings per prototype with optimal tool selection

### Month 1: Validation Culture
- Teams systematically test assumptions before building
- 50% reduction in time from idea to validated learning

### Quarter 1: Innovation Velocity
- Multiple prototype iterations per week instead of per month
- Clear learning signals that drive strategic decisions

---

*Start with 2 essential agents. Learn from usage. Expand based on real team needs.*
