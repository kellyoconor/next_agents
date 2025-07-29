# Agent Workflows for Product Builders

Five real-world scenarios showing how to chain Claude Code sub-agents for maximum efficiency in product development workflows.

## Scenario 1: Feature Concept to Launch

**Situation:** You have a new feature idea but need to validate it before investing development time.

### Workflow Chain
```
ai-dev-task-master → frontend-prototype-builder → docs-expert → presentation-architect
```

### Step-by-Step Process

**Step 1: `ai-dev-task-master`**
- **Input:** "Plan an AI-powered expense categorization feature for my fintech app"
- **Output:** 
  - Comprehensive PRD with user stories and technical requirements
  - Structured task breakdown with 43 development tasks across 6 phases
  - Architecture analysis and integration considerations
- **Decision Point:** PRD looks solid, proceed to prototyping

**Step 2: `frontend-prototype-builder`**
- **Input:** "Create a mobile interface for AI expense categorization based on the PRD"
- **Output:**
  - Interactive mobile prototype with expense entry flows
  - AI suggestion interface with confidence indicators
  - Professional styling with Ionicons and smooth animations
- **Decision Point:** Prototype tests well with users, proceed to documentation

**Step 3: `docs-expert`**
- **Input:** "Document the expense categorization feature for end users"
- **Output:**
  - User guide explaining how AI categorization works
  - Troubleshooting guide for categorization errors
  - API documentation for third-party integrations
- **Decision Point:** Documentation is clear, prepare stakeholder presentation

**Step 4: `presentation-architect`**
- **Input:** "Create a presentation showing the feature concept and user validation results"
- **Output:**
  - Professional HTML presentation with user testing metrics
  - Interactive charts showing accuracy improvements
  - Executive summary with implementation timeline

**Timeline:** 2-3 hours for complete feature planning and validation package

---

## Scenario 2: User Research Analysis to Product Decision

**Situation:** You've collected user feedback and need to turn insights into actionable product decisions.

### Workflow Chain
```
[External research] → presentation-architect → ai-dev-task-master → frontend-prototype-builder
```

### Step-by-Step Process

**Step 1: Data Collection (External)**
- User interviews with 25 customers
- Survey responses from 200 users
- Analytics data showing drop-off points

**Step 2: `presentation-architect`**
- **Input:** "Analyze user research data and create insights presentation" + CSV uploads
- **Output:**
  - Interactive dashboard showing user pain points
  - Chart visualizations of feature request priorities
  - Executive presentation with clear recommendations
- **Decision Point:** Data shows clear need for improved onboarding

**Step 3: `ai-dev-task-master`**
- **Input:** "Plan a redesigned user onboarding flow based on research insights"
- **Output:**
  - PRD addressing specific user pain points identified
  - Technical requirements for personalized onboarding
  - Task breakdown for implementation across mobile and web
- **Decision Point:** Onboarding plan addresses key issues, build prototype

**Step 4: `frontend-prototype-builder`**
- **Input:** "Create an interactive onboarding prototype with personalization"
- **Output:**
  - Multi-step onboarding flow with progress indicators
  - Personalization questions with dynamic UI
  - Mobile-optimized interface ready for user testing

**Timeline:** 1-2 hours for complete research analysis and solution prototyping

---

## Scenario 3: Rapid Competitive Response

**Situation:** Competitor launched a feature you need to match quickly while maintaining your product advantage.

### Workflow Chain
```
ai-dev-task-master → frontend-prototype-builder → presentation-architect
```

### Step-by-Step Process

**Step 1: `ai-dev-task-master`**
- **Input:** "Plan a social sharing feature that competes with [Competitor] but fits our privacy-first approach"
- **Output:**
  - Competitive analysis with privacy-focused differentiation
  - Technical requirements for privacy-preserving social features
  - 3-week implementation plan with MVP and iteration phases
- **Decision Point:** Plan differentiates while meeting competitive need

**Step 2: `frontend-prototype-builder`**
- **Input:** "Build a social sharing interface emphasizing privacy controls"
- **Output:**
  - Sharing flow with granular privacy settings
  - Visual privacy indicators and user education
  - Prototype demonstrating competitive advantages
- **Decision Point:** Prototype shows clear privacy advantage, prepare pitch

**Step 3: `presentation-architect`**
- **Input:** "Create executive presentation comparing our approach to competitor feature"
- **Output:**
  - Competitive comparison with privacy advantages highlighted
  - User research data supporting privacy-first approach
  - Implementation timeline and resource requirements

**Timeline:** 1-2 hours for complete competitive response strategy

---

## Scenario 4: Technical Debt to User Value

**Situation:** Engineering team wants to refactor a complex system, but you need to show user-facing value to justify the work.

### Workflow Chain
```
ai-dev-task-master → frontend-prototype-builder → docs-expert → presentation-architect
```

### Step-by-Step Process

**Step 1: `ai-dev-task-master`**
- **Input:** "Plan a API architecture refactor that also enables new user-facing features"
- **Output:**
  - Technical refactoring plan with user-visible improvements
  - New capabilities enabled by cleaner architecture
  - Phased approach balancing technical debt and feature delivery
- **Decision Point:** Plan shows clear user value alongside technical improvements

**Step 2: `frontend-prototype-builder`**
- **Input:** "Create interface prototypes for new features enabled by API refactor"
- **Output:**
  - Performance improvement demonstrations
  - New feature interfaces not possible with old architecture
  - Before/after user experience comparisons
- **Decision Point:** Prototypes clearly show user experience improvements

**Step 3: `docs-expert`**
- **Input:** "Document the new API capabilities and migration guide"
- **Output:**
  - Developer documentation for new API features
  - Migration guide for existing integrations
  - User-facing feature documentation
- **Decision Point:** Documentation supports smooth transition

**Step 4: `presentation-architect`**
- **Input:** "Present technical debt resolution with user value metrics"
- **Output:**
  - Executive presentation justifying refactor investment
  - Performance metrics and user experience improvements
  - ROI analysis for technical debt resolution

**Timeline:** 2-3 hours for complete technical debt justification package

---

## Scenario 5: Stakeholder Alignment to Implementation

**Situation:** You need to align diverse stakeholders on a complex product initiative before development begins.

### Workflow Chain
```
ai-dev-task-master → presentation-architect → frontend-prototype-builder → docs-expert
```

### Step-by-Step Process

**Step 1: `ai-dev-task-master`**
- **Input:** "Plan a multi-tenant enterprise feature with complex permission system"
- **Output:**
  - Comprehensive PRD with enterprise requirements
  - Security and compliance considerations
  - Resource requirements and timeline estimates
- **Decision Point:** Requirements are comprehensive, need stakeholder buy-in

**Step 2: `presentation-architect`**
- **Input:** "Create stakeholder presentation for enterprise feature approval"
- **Output:**
  - Executive summary with business case and ROI
  - Implementation timeline with milestones
  - Risk analysis and mitigation strategies
- **Decision Point:** Stakeholders approve concept, need detailed prototype

**Step 3: `frontend-prototype-builder`**
- **Input:** "Build enterprise admin interface with permission management"
- **Output:**
  - Complex admin dashboard with role-based views
  - Permission management interface with visual hierarchy
  - Enterprise-grade styling and accessibility features
- **Decision Point:** Prototype validates complexity, prepare implementation docs

**Step 4: `docs-expert`**
- **Input:** "Create enterprise feature documentation for customers and internal teams"
- **Output:**
  - Enterprise admin guides with permission workflows
  - Integration documentation for customer IT teams
  - Internal implementation guidelines for support teams

**Timeline:** 3-4 hours for complete enterprise feature alignment and planning

---

## Workflow Selection Guide

### When to Start With Each Agent

**Start with `ai-dev-task-master` when:**
- You have a feature concept but need structure
- Requirements are unclear or complex
- You need technical feasibility analysis
- Multiple stakeholders need alignment on scope

**Start with `frontend-prototype-builder` when:**
- You have clear UI/UX requirements
- Need immediate user testing capability
- Stakeholders need visual demonstration
- Concept validation is the primary goal

**Start with `docs-expert` when:**
- You have working features that need explanation
- API documentation is blocking integrations
- User adoption is limited by unclear instructions
- Knowledge sharing is the immediate need

**Start with `presentation-architect` when:**
- You have data that needs interpretation
- Stakeholder communication is the priority
- Results need to be shared with executives
- Decision-making requires visual evidence

### Parallel vs Sequential Workflows

**Sequential (Most Common):**
- Each agent builds on the previous agent's output
- Clear dependencies and logical progression
- Best for comprehensive product development

**Parallel (When Time-Constrained):**
- Multiple agents work on independent aspects
- Requires clear scope separation
- Best for urgent competitive responses or crisis situations

### Quality Gates Between Agents

- **Review outputs** before moving to the next agent
- **Validate assumptions** with real users when possible
- **Iterate based on stakeholder feedback** before final implementation
- **Document decisions** made during the workflow for future reference

## Success Metrics

Track the effectiveness of your agent workflows:
- **Time to prototype**: From concept to testable interface
- **Stakeholder alignment**: Reduced rounds of feedback and revision
- **Implementation accuracy**: How closely final product matches planned scope
- **User validation success**: Prototype feedback quality and actionability
