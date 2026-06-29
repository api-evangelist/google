# Programmatic API Onboarding — Google

A single-file, zero-dependency Node.js (18+) CLI that reproduces SoundCloud's
`sc-api-auth.mjs` pattern for Google: register an application / obtain credentials
programmatically instead of clicking through a dashboard, so agents and developers
can onboard at the command line.

- Script: [`google-oauth-api-auth.mjs`](google-oauth-api-auth.mjs)
- Run `node google-oauth-api-auth.mjs --help` for usage and the required environment variables.
- Story / rationale: https://apievangelist.com/2026/09/08/google-oauth-console-only-service-accounts-scriptable/

Part of the API Evangelist "Programmatic API Onboarding for the Agentic Moment" series.
