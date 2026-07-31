# Privilege Escalation via Replay of Saved Admin Request

## Overview
An access control vulnerability (Privilege Escalation / IDOR) in GraphQL mutations allowing downgraded users to retain administrative capabilities through replaying authorized requests.

## Key Concepts
- **Vulnerability Type:** Broken Access Control (Privilege Escalation)
- **Protocol / API:** GraphQL Mutation
- **Impact:** Critical - Unauthorized admin user creation & persistence
