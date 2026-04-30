# Renovate Config

Centralized Renovate configuration repository for managing dependency updates across MattWhite-personal's wider repository ecosystem.

## Overview

This repository serves as a single source of truth for Renovate configuration, allowing consistent and maintainable dependency management across multiple repositories without duplicating configuration files.

## Usage

To use this configuration in your repositories, reference it in your `renovate.json` or `renovate.json5` file:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>MattWhite-personal/renovate-config"]
}
```

## Configuration Files

Store your shared Renovate configurations in this repository:
- `default.json` - Base configuration applied across all repositories
- Other specialized configurations as needed

## License

MIT