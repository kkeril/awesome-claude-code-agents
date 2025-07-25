# 🤖 Awesome Claude Agents

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Claude Compatible](https://img.shields.io/badge/Claude-Opus%204-blue)](https://www.anthropic.com)

A curated collection of prompts, patterns, and examples for building powerful agents with Claude.

## 📚 Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Prompt Categories](#prompt-categories)
  - [Basic Agents](#basic-agents)
  - [Advanced Agents](#advanced-agents)
- [Best Practices](#best-practices)
- [Contributing](#contributing)
- [Resources](#resources)

## 🎯 Introduction

This repository contains battle-tested prompts for creating Claude agents that can:
- 🔧 Use tools and APIs effectively
- 🧠 Perform complex reasoning tasks
- 🔄 Handle multi-step workflows
- 📊 Process and analyze data
- 🤝 Collaborate in multi-agent systems

## 🚀 Getting Started

### Prerequisites
- Claude API access (Opus 4 recommended)
- Basic understanding of prompt engineering
- Python 3.8+ (for example scripts)

### Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/awesome-claude-agents.git

# Navigate to the project
cd awesome-claude-agents

# Install dependencies (optional, for testing scripts)
pip install -r requirements.txt
```

## 📂 Prompt Categories

### Basic Agents

Simple, single-purpose agents that excel at specific tasks.

| Name | Description | Tools Required | Link |
|------|-------------|----------------|------|
| Code Reviewer | Reviews code for best practices and bugs | None | [View](prompts/code-reviewer-agent.md) |
| Data Analyst | Analyzes datasets and provides insights | None | [View](prompts/data-analyst-agent.md) |
| Creative Writer | Generates creative content | None | [View](prompts/creative-writer-agent.md) |

### Advanced Agents

Complex agents that handle multi-step reasoning and decision-making.

| Name | Description | Tools Required | Link |
|------|-------------|----------------|------|
| Research Assistant | Conducts comprehensive research | Web Search, Analysis | [View](prompts/aresearch-assistant-agent.md) |
| Project Manager | Plans and tracks project progress | None | [View](prompts/project-manager-agent.md) |
| System Architect | Designs software architectures | None | [View](prompts/system-architect-agent.md) |

## 💡 Best Practices

### Prompt Engineering Tips

1. **Be Specific**: Clearly define the agent's role and constraints
2. **Use Examples**: Include few-shot examples when appropriate
3. **Structure Output**: Define expected output formats
4. **Handle Edge Cases**: Include error handling instructions
5. **Iterate and Test**: Continuously refine based on results

### Example Prompt Structure

```markdown
You are a [ROLE] expert specializing in [DOMAIN].

Your primary objectives are:
1. [Objective 1]
2. [Objective 2]
3. [Objective 3]

Guidelines:
- [Guideline 1]
- [Guideline 2]
- [Guideline 3]

Output Format:
[Specify the expected output structure]

Examples:
[Provide 1-3 examples if needed]
```

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### How to Contribute

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingPrompt`)
3. Commit your changes (`git commit -m 'Add some AmazingPrompt'`)
4. Push to the branch (`git push origin feature/AmazingPrompt`)
5. Open a Pull Request

### Contribution Ideas

- New agent prompts
- Improved versions of existing prompts
- Real-world examples
- Documentation improvements
- Testing scripts

## 📚 Resources

### Official Documentation
- [Claude Documentation](https://docs.anthropic.com)
- [Prompt Engineering Guide](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)

### Community
- [Anthropic Discord](https://discord.gg/anthropic)
- [Claude Subreddit](https://reddit.com/r/claudeai)

### Related Projects
- [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook)
- [Claude Tools Collection](https://github.com/example/claude-tools)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=kkeril/awesome-claude-agents&type=Date)](https://star-history.com/#yourusername/awesome-claude-agents&Date)

---

<div align="center">
Made with ❤️ and Claude
</div>
