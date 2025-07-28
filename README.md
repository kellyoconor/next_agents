# next_agents
A comprehensive collection of specialized AI agents designed to accelerate and enhance every aspect of rapid development. Each agent is an expert in their domain, ready to be invoked when their expertise is needed.

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
"Create a new app for tracking meditation habits" → rapid-prototyper
"What's trending on TikTok that we could build?" → trend-researcher
"Our app reviews are dropping, what's wrong?" → feedback-synthesizer
"Make this loading screen more fun" → whimsy-injector


**📁 Directory Structure**
Agents are organized by department for easy discovery:







**🔧 Technical Details**
Agent Structure
Each agent includes:

  name: Unique identifier
  description: When to use the agent with examples
  color: Visual identification
  tools: Specific tools the agent can access
  System prompt: Detailed expertise and instructions
**Adding New Agents**
Create a new .md file in the appropriate department folder
Follow the existing format with YAML frontmatter
Include 3-4 detailed usage examples
Write comprehensive system prompt (500+ words)
Test the agent with real tasks



**🔧 Agent File Structure Template**
