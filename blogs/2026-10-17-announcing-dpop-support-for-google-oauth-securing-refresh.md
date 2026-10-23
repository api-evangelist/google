---
title: "Announcing DPoP Support for Google OAuth: Securing Refresh Tokens"
url: "https://developers.googleblog.com/announcing-dpop-support-for-google-oauth-securing-refresh-tokens/"
date: "2026-10-17"
feed_url: "https://developers.googleblog.com/feeds/posts/default"
---
Google OAuth Platform now supports DPoP (Demonstrating Proof-of-Possession) to sender-constrain refresh tokens, neutralizing Infostealer malware and adversary-in-the-middle attacks. By cryptographically binding long-lived refresh tokens while maintaining short-lived access tokens as standard Bearer tokens, developers achieve robust credential security without incurring high-QPS API performance overhead. Additionally, developers integrating multi-agent or Model Context Protocol (MCP) workloads can use Google Cloud Secure Token Service (STS) to handle secure token delegation across agent chains.
