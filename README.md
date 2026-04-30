# Privacy Policy

_Last updated: April 30, 2026_

## Overview

This project is a **personal, self-hosted tool** that connects [Anthropic's Claude](https://www.anthropic.com/) to the author's own [Pinterest](https://www.pinterest.com/) account via the Pinterest API. It is intended for **private, single-user use only**. It is not a hosted service, does not have user accounts, and does not collect data from anyone other than the person running it on their own machine.

## What this tool accesses

When you run this tool with your own Pinterest API credentials, it may read:

- Your Pinterest boards
- Your Pinterest pins (including titles, descriptions, links, and images)
- Account metadata required by the Pinterest API (e.g. user ID, board IDs)

It only accesses data belonging to the authenticated Pinterest account — i.e. yours.

## Where data is stored

- **API credentials** (tokens, client IDs, secrets) are stored locally on your machine, typically in environment variables or a local config file. They are never transmitted anywhere except to the Pinterest API.
- **Pinterest data** retrieved by the tool stays on your local machine unless you explicitly send it to Claude during a conversation.
- **No data is sent to the author of this repository**, no telemetry is collected, and there is no analytics layer.

## Third-party services

This tool exchanges data with two third parties on your behalf:

1. **Pinterest API** — to read your account data. Use is subject to the [Pinterest Privacy Policy](https://policy.pinterest.com/en/privacy-policy) and the [Pinterest Developer Terms](https://developers.pinterest.com/terms/).
2. **Anthropic / Claude** — when you choose to share Pinterest data with Claude during a conversation. Use is subject to the [Anthropic Privacy Policy](https://www.anthropic.com/legal/privacy).

You are responsible for understanding what each of these services does with the data you send them.

## Sharing

No data handled by this tool is sold, shared, or disclosed to anyone. The author has no access to your Pinterest account, your tokens, or anything you do with the tool.

## Security

You are responsible for keeping your API credentials secure (e.g. not committing them to git, not sharing your config files). This project provides no warranty; see the LICENSE file for details.

## Changes

This policy may be updated. Material changes will be reflected in the "Last updated" date at the top of this file.

## Contact

For questions about this tool, open an issue on the repository.
