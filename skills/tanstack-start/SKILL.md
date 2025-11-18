---
name: TanStack Start
description: |
  [⚠️ RC STATUS - MONITORING FOR v1.0 STABLE] Full-stack React framework built on TanStack Router with official Cloudflare Workers support. This skill will be published when v1.0 stable is released and critical issues are resolved. Use when: building full-stack React applications, need SSR with Cloudflare Workers, want type-safe server functions, or migrating from Next.js. Currently monitoring: GitHub #5734 (memory leak), "needed-for-start-stable" issues.
license: MIT
allowed-tools: [Bash, Read, Write, Edit]
metadata:
  version: 0.9.0
  author: Jeremy Dawes | Jezweb
  last-verified: 2025-11-18
  production-tested: false
  status: draft
  package: "@tanstack/react-start"
  current_version: "1.136.9"
  keywords:
    - tanstack start
    - tanstack react start
    - tanstack router
    - full-stack react
    - ssr
    - server-side rendering
    - cloudflare workers
    - cloudflare vite plugin
    - server functions
    - api routes
    - type-safe server
    - react framework
    - next.js alternative
    - vite
    - vinxi
    - nitro
    - server components
    - streaming ssr
    - hydration
    - file-based routing
    - react server functions
    - cloudflare d1
    - cloudflare kv
    - cloudflare r2
    - workers assets
---

# TanStack Start Skill [DRAFT - NOT READY]

⚠️ **Status: Release Candidate - Monitoring for Stability**

This skill is prepared but NOT published. Waiting for:
- ⏸️ v1.0 stable release (currently RC v1.136.9 as of 2025-11-18)
- ❌ GitHub #5734 resolved (memory leak with TanStack Form - OPEN as of 2025-11-02)
- ⏸️ Critical bugs stabilization period
- ⏸️ Template/reference content creation

**Current Package:** `@tanstack/react-start@1.136.9` (Nov 18, 2025)

**DO NOT USE IN PRODUCTION YET** - RC status, active memory leak issue

---

## Skill Overview

TanStack Start is a full-stack React framework with:
- Client-first architecture with opt-in SSR
- Built on TanStack Router (type-safe routing)
- Server functions for API logic
- Official Cloudflare Workers support
- Integrates with TanStack Query

---

## When v1.0 Stable

This skill will provide:
- Cloudflare Workers + D1/KV/R2 setup
- Server function patterns
- SSR vs CSR strategies
- Migration guide from Next.js
- Known issues and solutions

---

## Monitoring

Track stability at: `planning/stability-tracker.md`

**Check weekly:**
- Package: `npm view @tanstack/react-start version`
- [TanStack Start Releases](https://github.com/TanStack/router/releases)
- [Issue #5734](https://github.com/TanStack/router/issues/5734) - Memory leak blocker

---

## Installation (When Ready)

```bash
npm create cloudflare@latest -- --framework=tanstack-start
```

---

**Last Updated:** 2025-11-18
**RC Announced:** September 22, 2025
**Expected Stable:** Pending issue #5734 resolution + final RC feedback
