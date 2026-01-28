# withagi-customer-demo

A Node.js based interactive demo replicating the Storylane experience. It showcases WithAGI's ability to take a 1-liner GitHub/Forgejo issue and automate the implementation of UI improvements and new features (like bulk discounting) for an e-commerce site.

## Project Type

Nodejs project

## Getting Started

### Prerequisites

This project uses [MISE](https://mise.jdx.dev/) for environment management.

```bash
# Install MISE (if not already installed)
curl https://mise.run | sh

# Install project tools
mise install

# Trust this directory
mise trust
```

### Development

```bash
# Install dependencies
mise run install

# Run tests
mise run test

# Start development
mise run dev
```

## Project Structure

```
withagi-customer-demo/
├── .mise.toml      # MISE configuration
├── .gitignore      # Git ignore rules
├── .a0proj/        # Agent-Zero project metadata
│   ├── project.json
│   ├── instructions/
│   └── knowledge/
└── README.md       # This file
```

## Created

Created on 2026-01-28 with Agent-Zero MultiAgentDev.
