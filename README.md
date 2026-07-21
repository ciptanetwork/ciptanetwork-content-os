# Cipta Network Content OS

## Overview
This repository manages the content production system for 4 websites in the Cipta Network.

## Sites Managed
1. **ciptavisual.com** - English | Design & Marketing for SMEs
2. **idenusa.com** - Indonesian | Design & Marketing for Creators
3. **kitiranmedia.com** - Indonesian | AI for Creators
4. **depotopic.com** - English | AI for Creators

## How AI Agents Should Use This System

### Critical First Step
**ALWAYS determine which site you're working on by checking the Site ID.**

### Standard Workflow
1. Read `_sites/sites_manifest.md` for site overview
2. Load specific site's `_site_identity.md` - THIS IS YOUR PRIMARY CONTEXT
3. Follow `_global/workflows/workflow_write_article.md`
4. Reference global standards but apply site-specific overrides

### Important Rules
- **NEVER TRANSLATE** - Write directly in the target language naturally
- **ALWAYS CHECK SITE IDENTITY** - Each site has unique tone, audience, and market
- **RESPECT TONE DIFFERENCES** - What works for KITIRAN won't work for CIPTA
- **MAINTAIN UNIQUENESS** - No duplicate content across sites

### Site ID Reference
| ID | Domain | Language | Tone | Market |
|----|--------|----------|------|--------|
| CIPTA | ciptavisual.com | EN | Santai & Formal | Global |
| IDENUSA | idenusa.com | ID | Santai & Formal | Indonesia |
| KITIRAN | kitiranmedia.com | ID | Santai & Gaul | Indonesia |
| DEPOTOPIC | depotopic.com | EN | Santai & Formal | Global |

## AI Agent Instructions

When prompted, you must:
1. Ask for the Site ID if not provided
2. Load the appropriate site identity file
3. Apply all site-specific rules
4. Write in the correct language NATURALLY
5. Verify tone matches site identity

## Architecture Diagram