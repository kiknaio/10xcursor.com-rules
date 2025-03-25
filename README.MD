# 10xCursor.com Rules Directory

A community-maintained collection of rules for enhancing your [Cursor](https://cursor.com/) editor experience. This repository serves as a central hub for discovering, sharing, and collaborating on Cursor rules, that will be automatically visible on [10xCursor.com](https://10xcursor.com).

## What are Cursor Rules?

Cursor rules are customizations that extend the functionality of the Cursor editor. They can help with code formatting, snippet generation, autocompletion, and other productivity enhancements.

## Directory Structure

```
/cursor-rules
  /rules             # Individual rule files
    rule1.json
    rule2.json
    ...
  rules-index.json   # Index of all available rules
  schema.json        # JSON schema for rule validation
  README.md          # What you're reading right now
  CONTRIBUTING.md    # Guide for contributors
```

## How to Use These Rules

### In the Cursor Rules App

1. Visit [10xcursor.com](https://10xcursor.com/rules)
2. Browse or search for rules
3. Click "Install" on any rule you'd like to use
4. Follow the provided instructions to add the rule to your Cursor configuration

### Manual Installation

1. Find a rule you want to use in the `/rules` directory
2. Copy the code portion of the rule
3. Open your Cursor settings
4. Navigate to the custom rules section
5. Paste the rule code
6. Save your settings

## Featured Rules

Here are some of our most popular rules:

<!-- - **Format Code Blocks** - Automatically formats code blocks in comments
- **Auto Import React Components** - Intelligently imports React components as you use them
- **TypeScript Strict Mode Enforcer** - Helps maintain TypeScript best practices -->

## Contributing

We welcome contributions from the community! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to submit new rules or improve existing ones.

### Quick Guide to Contributing

1. Fork this repository
2. Create a new rule file in the `/rules` directory following our schema
3. Submit a pull request with your rule and a description of what it does
4. Our automated validation will check your submission, once it's passed, I will review it manually and approve it.
5. Once approved, your rule will be added to the directory and will be visible on [10xcursor.com](https://10xcursor.com/rules)

## Rule Schema

Each rule follows a standardized JSON schema to ensure consistency. Here's a simplified version:

```json
{
  "id": "unique-rule-id",
  "name": "Human-Readable Rule Name",
  "description": "What this rule does and why it's useful",
  "author": {
    "name": "Your Name",
    "twitter": "https://twitter.com/yourhandle",
    "github": "https://github.com/yourusername"
  },
  "tags": ["category1", "category2"],
  "created": "2025-03-20",
  "rule": "// The actual rule code here"
}
```

For the complete schema, see [schema.json](schema.json).

## License

This repository and all contributions are licensed under the MIT License. See [MIT LICENSE](https://opensource.org/license/mit) for details.

## Acknowledgements

- Thanks to all contributors who have shared their rules
- Special thanks to the Cursor team for creating an amazing editor

## Contact

For questions, suggestions, or support:
- Open an issue in this repository
- Reach out to the maintainers on Twitter: [@kiknaio](https://twitter.com/kiknaio)
- Become an 10x AI-Powered Developer: [10X AI-Powered Developer Newsletter](https://kiknadze.io/subscribe)