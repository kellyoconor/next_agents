# next_agents
A specialized collection of AI agents designed for a fast-moving innovation team. Built for AI-first organizations using dynamic pod structures (Velocity, Adjacent, Moonshot, Enablement) with a focus on rapid prototyping, validated learning, and impact velocity.
**📥 Installation**
Download this repository:

git clone https://github.com/kellyoconor/next_agents.git
Copy to your Claude Code agents directory:

cp -r agents/* ~/.claude/agents/
Or manually copy all the agent files to your ~/.claude/agents/ directory.

Restart Claude Code to load the new agents.

**🚀 Quick Start**
Agents are automatically available in Claude Code. Simply describe your task and the appropriate agent will be triggered. You can also explicitly request an agent by mentioning their name.

📚 Learn more: [Claude Code Sub-Agents Documentation](https://docs.anthropic.com/en/docs/claude-code/sub-agents)


**Example Usage**
"We think busy parents would pay for AI meal planning, but we're not sure" → rapid-validator
"Can we build real-time collaboration features in 2 weeks?" → technical-feasibility-assessor
"Our signup rate is 12% but we don't know what to optimize next" → iteration-advisor
"We need to present our healthcare moonshot to the board" → strategic-narrative-architect

## 📁 Agent Categories

### Core Innovation Agents (`core/`)
Essential agents for the innovation workflow:
- **rapid-validator** - Test assumptions fast and cheap with maximum learning
- **problem-solution-finder** - Validate real problems worth solving and solution fit
- **prototype-planner** - Match prototype fidelity to learning objectives
- **user-research-sprinter** - Get user insights without research overhead
- **technical-feasibility-assessor** - Smart technical decisions for rapid prototyping
- **iteration-advisor** - Data-driven decisions on what to do next

### AI-First Organization Agents (`ai-first/`)
Specialized for AI-augmented innovation teams:
- **impact-velocity-tracker** - Measure concept-to-validation speed and business signals
- **pod-resource-orchestrator** - Dynamic talent allocation across innovation pods
- **ai-capability-amplifier** - Leverage AI to expand team expertise and capabilities
- **business-signal-synthesizer** - Transform experiments into C-Suite intelligence
- **cross-pod-learning-accelerator** - Share learnings across dynamic pod structures

### Bonus Agents (`bonus/`)
Add humor and humanity to intense innovation work:
- **buzzword-bingo-master** - Cut through corporate speak with surgical precision
- **rubber-duck-therapist** - Emotional support debugging with personality
- **hype-train-conductor** - Generate enthusiasm for mundane features
- **meeting-escape-artist** - Diplomatic meeting avoidance strategies
- **startup-stereotype-generator** - Satirical Silicon Valley culture commentary

## 📋 Complete Agent List

### Core Innovation Workflow
- **rapid-validator** - Validate ideas, assumptions, and prototypes with minimal resources
- **problem-solution-finder** - Identify real problems and validate problem-solution fit  
- **prototype-planner** - Plan rapid prototyping approaches with right fidelity levels
- **user-research-sprinter** - Fast user research to validate assumptions and gather insights
- **technical-feasibility-assessor** - Assess feasibility and suggest MVP technical approaches
- **iteration-advisor** - Analyze results and guide strategic iteration decisions

### AI-First Organization Support  
- **impact-velocity-tracker** - Optimize speed from concept to validated prototype
- **pod-resource-orchestrator** - Allocate talent across Velocity/Adjacent/Moonshot/Enablement pods
- **ai-capability-amplifier** - Identify AI opportunities to expand team capabilities
- **business-signal-synthesizer** - Convert innovation experiments into business intelligence
- **cross-pod-learning-accelerator** - Distribute learnings across dynamic pod structures

### Culture & Morale Boosters
- **buzzword-bingo-master** - Translate corporate speak into human language
- **rubber-duck-therapist** - Debugging wisdom with therapeutic snark
- **hype-train-conductor** - Find revolutionary potential in any feature
- **meeting-escape-artist** - Creative excuses to escape unnecessary meetings  
- **startup-stereotype-generator** - Satirical startup culture commentary

## 🎯 Design Philosophy

These agents are built for innovation teams that need to:

### Speed & Velocity
- Move from concept to validated prototype in days/weeks, not months
- Run multiple promising threads in parallel
- Generate clear business signals quickly

### AI-First Operations
- Prove AI cannot do the job before adding resources
- Expand expertise through AI augmentation rather than hiring
- Focus human effort on creative and strategic work

### Dynamic Pod Structure
- Flow talent to innovation opportunities as they emerge
- Share learnings across Velocity, Adjacent, Moonshot, and Enablement pods
- Maintain team cohesion through fluid organizational boundaries

### Validated Learning
- Test assumptions systematically with minimal investment
- Balance exploitation of known successes with exploration of new opportunities
- Make data-driven decisions about pivoting, persevering, or killing initiatives

## 💡 Best Practices

### Agent Collaboration Patterns
1. **Research → Prototype → Test → Iterate**
   - `problem-solution-finder` → `prototype-planner` → `rapid-validator` → `iteration-advisor`

2. **Technical Feasibility Check**
   - `technical-feasibility-assessor` works with any other agent when building is involved

3. **Business Case Development**
   - `business-signal-synthesizer` + `impact-velocity-tracker` for executive communication

4. **Resource Optimization**
   - `pod-resource-orchestrator` + `ai-capability-amplifier` for team efficiency

### Innovation Velocity Tips
- **Start with validation** before building anything substantial
- **Use AI augmentation** before hiring additional specialists  
- **Focus on learning speed** over feature completeness
- **Measure business signals** not just user engagement
- **Share insights across pods** to prevent duplicate work

## 🔧 Technical Details

### Agent Structure
Each agent includes:
- **name**: Unique identifier for Claude Code
- **description**: When to use with specific usage examples
- **tools**: Access to web_search, repl, google_drive_search, etc.
- **System prompt**: Comprehensive expertise and methodology (500+ words)

### Usage Examples
Every agent includes detailed usage examples showing:
- Real team conversations that would trigger the agent
- Specific, actionable outputs the agent provides
- Context about why that example matters for innovation teams

### Cross-Agent Integration
Agents are designed to work together seamlessly:
- **Sequential workflows** for complex innovation challenges
- **Parallel execution** when testing independent hypotheses  
- **Knowledge sharing** between agents working on related problems

## 📊 Success Metrics

Track innovation effectiveness through:

### Impact Velocity
- Concept-to-prototype time
- Validation cycle speed  
- Parallel thread capacity
- Business signal quality

### Resource Efficiency
- Learning-per-dollar-spent
- AI augmentation adoption
- Cross-pod knowledge sharing
- Meeting time reduction

### Business Impact
- Revenue potential signals
- Cost reduction opportunities
- Competitive advantage development
- C-Suite decision influence

## 🛠️ Customizing for Your Organization

### Required Customizations
- [ ] **Company Context**: Update examples to reflect your industry and products
- [ ] **Pod Structure**: Modify if you use different organizational models  
- [ ] **Success Metrics**: Align with your specific KPIs and business objectives
- [ ] **Tool Access**: Ensure agents have access to your internal tools and platforms

### Optional Customizations
- [ ] **Agent Personality**: Adjust tone and style for your company culture
- [ ] **Domain Expertise**: Add industry-specific knowledge and frameworks
- [ ] **Process Integration**: Align with existing innovation and product development processes
- [ ] **Compliance Requirements**: Add regulatory or legal constraints specific to your industry

## 🚦 Implementation Stages

### Stage 1: Core Innovation (Week 1-2)
Deploy the 6 core innovation agents for immediate impact on prototype velocity

### Stage 2: AI-First Transformation (Week 3-4)  
Add AI-first organization agents to optimize team structure and capabilities

### Stage 3: Culture & Sustainability (Week 5-6)
Introduce bonus agents to maintain team morale and prevent burnout

### Stage 4: Optimization (Ongoing)
Customize agents based on usage patterns and team feedback

## 🤝 Contributing

To improve existing agents or suggest new ones:

1. **Follow Usage Patterns**: Study how teams actually interact with agents
2. **Test Thoroughly**: Validate with real innovation challenges
3. **Document Impact**: Measure improvements in velocity and business outcomes
4. **Share Learnings**: Contribute successful patterns back to the community

### Agent Development Guidelines
- **Specificity over Generality**: Agents should excel in narrow domains
- **Action over Analysis**: Focus on actionable outputs, not just insights
- **Speed over Perfection**: Optimize for innovation velocity and learning speed
- **Business Impact**: Connect all agent outputs to measurable business outcomes


*Built for innovation teams that measure success by impact velocity: How quickly can we move from concept to validated prototype while generating clear signals about revenue potential and competitive advantage.*
