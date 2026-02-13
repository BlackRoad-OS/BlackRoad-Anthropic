# BlackRoad-Anthropic

© 2026 BlackRoad OS, Inc. All rights reserved.

## PRIVATE REPOSITORY

Integration layer between BlackRoad OS and Anthropic AI services.

## Purpose

This repository contains:
- Claude API integrations
- Model orchestration logic
- Prompt engineering templates
- Agent coordination systems
- Performance monitoring

## Contents

- `integrations/` - Claude API client implementations
- `agents/` - Anthropic-powered agent definitions
- `prompts/` - Prompt templates and strategies
- `tools/` - MCP servers and tool integrations
- `monitoring/` - Performance and cost tracking
- `docs/` - Integration documentation

## API Keys

**NEVER commit API keys.** Use environment variables:
- `ANTHROPIC_API_KEY` - Production API key
- `ANTHROPIC_API_KEY_DEV` - Development API key

## Models Supported

- Claude Opus 4.6
- Claude Sonnet 4.5
- Claude Haiku 4.5

## License

See [LICENSE](./LICENSE) - Internal use only
