# The Great Unlearning

> **🧪 Experimental Initiative**: This is a work in progress, born from personal experiences with AI-assisted development and community insights. While our example projects demonstrate these concepts, they might not always perfectly align with all the patterns and guidelines described here. We're learning and adapting as we go, and we invite you to join us in this exploration.

## Rethinking Software Development in the LLM Age

Welcome to The Great Unlearning initiative. This organization explores and defines new patterns for software development in the age of AI Language Models. We're challenging traditional software engineering principles and discovering new ways of working that better suit the emerging paradigm of AI-assisted development.

## About This Initiative

This initiative is an experimental exploration, drawing from real-world experiences with AI-assisted development since the early days of ChatGPT and Claude. The patterns and principles presented here emerge from:

- Hands-on experience with various AI coding tools
- Community discussions and shared experiences
- Observed patterns in successful AI collaborations
- Trial and error in real projects
- Insights from the broader developer community

While our example projects implement these ideas, they serve more as experiments and proofs of concept rather than definitive implementations. Documentation and patterns might evolve or even contradict each other as we learn what works best.

## Why "The Great Unlearning"?

Just as we once transitioned from structured programming to object-oriented design, we're now entering a new era where traditional software engineering principles need reconsideration. This isn't about discarding everything we know, but rather about adapting and evolving our practices for AI-assisted development.

Some traditional principles we're rethinking:
- Information Hiding/Encapsulation
- Deep Inheritance Hierarchies
- Single Source of Truth
- Traditional Code Organization

## Emerging Patterns

### 1. Prompt-Oriented Architecture (POA)
A shift from technical organization to natural language descriptions:
- Components aligned with natural language descriptions
- Documentation integrated with code
- Clear boundaries matching common prompt patterns
```
feature/
├── intent.md         # Purpose in natural language
├── implementation/   # Actual code
├── tests/           # Self-contained tests
└── prompts.md       # Common modification prompts
```

### 2. Context Window Optimization (CWO)
Organizing code to work within LLM context limitations:
- Related code kept within proximity
- Dependencies explicitly stated
- Self-contained modules
```
feature/
├── dependencies.md
├── core-logic/      # Fits in one context window
├── extensions/      # Each fits in one window
└── integration/     # Connection points
```

### 3. Self-Regenerating Modules (SRM)
Modules designed to be recreated by LLMs:
- Complete context included
- Minimal external dependencies
- Clear contracts and business rules
- Self-contained validation

### 4. LLM-Friendly Documentation Pattern (LFDP)
Documentation serving both human and AI readers:
- Natural language descriptions
- Code examples
- Common modification scenarios
- Test cases
- Integration points

### 5. Context-First Design (CFD)
Prioritizing understanding over DRY principles:
- Complete business context with code
- Self-contained implementations
- Explicit dependencies

### 6. Prompt-Driven Testing (PDT)
Tests designed for LLM interaction:
- Natural language scenarios
- Self-contained contexts
- Clear boundaries
- AI-generatable cases

## The Future Developer's Role

The role of developers is evolving:
- From implementation details to system design
- Focus on business value and architecture
- AI orchestration and prompt engineering
- Quality assurance and validation
- System integration and overview

## Example Projects

1. [Whisper API Service](https://github.com/greatunlearning/example-project)
   - Complete example implementing these patterns
   - Production-ready service
   - Full documentation and guidelines

2. [More examples coming soon...]

## Getting Started

### 1. Project Structure
Follow our recommended structure:
```
project/
├── GUIDELINES.md       # LLM interaction rules
├── HOWTO_LLM.md       # Guide for collaboration
├── JOURNAL.md         # Development decisions
├── PROMPT_TEMPLATE.md # Interaction templates
├── TODO.md           # Project roadmap
└── src/              # Implementation following POA
```

### 2. Documentation
Each project should include:
- Clear intent documentation
- Natural language descriptions
- Implementation guidelines
- Common prompts
- Test scenarios

### 3. Development Process
Follow our LLM-assisted development workflow:
1. Define features in natural language
2. Create self-contained modules
3. Document with both humans and AI in mind
4. Implement with LLM assistance
5. Validate and refine

## Contributing

We welcome contributions in several areas:
1. New patterns and principles
2. Example implementations
3. Tools and utilities
4. Documentation and guides
5. Case studies

## Best Practices

1. **Clarity Over Cleverness**
   - Prefer explicit over implicit
   - Clear intent over clever implementation

2. **Context Over Reuse**
   - Prioritize understanding
   - Accept controlled redundancy

3. **Natural Language First**
   - Design for communication
   - Think in conversations

4. **Self-Contained Modules**
   - Complete context
   - Clear boundaries

## Community

- [LinkedIn Articles](https://www.linkedin.com/pulse/great-unlearning-continues-rethinking-software-llm-age-hannes-lehmann-jxjie)
- [Discussion Forum](https://github.com/greatunlearning/discussions)
- [Pattern Catalog](https://github.com/greatunlearning/patterns)

## Vision and Current State

We envision a future where software development seamlessly combines human creativity with AI capabilities. Our goal is to establish patterns and practices that make this collaboration more effective, maintainable, and enjoyable.

### Current Limitations and Challenges

As this is an experimental initiative:
- Patterns may evolve or be replaced as tools improve
- Example projects might not fully implement all patterns
- Documentation might be inconsistent or incomplete
- Some ideas might prove impractical in certain contexts
- Tools and practices are rapidly evolving

We believe in being transparent about these limitations while maintaining our vision for the future of software development.

### Join the Experiment

We encourage you to:
- Try these patterns in your projects
- Share your experiences and insights
- Propose new patterns and improvements
- Help evolve these ideas through practical application
- Be patient with inconsistencies and growing pains

## License

All projects under The Great Unlearning initiative are licensed under [MIT License](LICENSE) unless otherwise specified.

---

*Join us in redefining software development for the AI age. Together, we can establish new patterns that make the most of both human creativity and AI capabilities.*
