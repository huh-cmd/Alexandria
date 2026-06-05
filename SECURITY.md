# Security and Publication Boundary

Alexandria is designed to keep public documentation separate from private working material.

## Public Repository Rule

This repository should contain only reviewed, public-safe material:

- architecture summaries
- templates
- diagrams
- validation summaries
- principles
- dummy examples

It should not contain raw vault state, personal logs, credentials, account details, screenshots, private project plans, or live operational files.

## Never Publish

- API keys, tokens, passwords, or credential fragments
- local machine paths
- account names or private URLs
- screenshots with private tabs or system details
- raw session logs
- raw queue files
- raw agent memory
- client, prospect, or private business material
- device, network, or VPS details

## Reporting a Concern

If you see sensitive material in this repository, open an issue with the file path and a short description. Do not paste the sensitive value into the issue.

## Maintainer Rule

Public docs should be derived from sanitized summaries, not copied directly from a private vault.

