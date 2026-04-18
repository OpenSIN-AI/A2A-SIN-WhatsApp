# A2A-SIN-WhatsApp Boundaries

## Role
`A2A-SIN-WhatsApp` owns WhatsApp messaging integration, automation, and WhatsApp-specific contracts.

## This repo should own
- WhatsApp messaging, routing, and automation workflows
- WhatsApp evidence, recovery, auth, and session handling
- WhatsApp contracts used by downstream messaging automation agents
- runbooks tied to WhatsApp delivery, automation, and monitoring

## This repo must not own
- generic messaging ownership outside WhatsApp
- unrelated social, community, or product platform behavior
- organization SSOT docs or architecture canon

## Hard rules
- Keep changes scoped to WhatsApp messaging integration and automation.
- Move non-WhatsApp behavior back to the repos that own those surfaces.
- Keep reusable contracts focused on WhatsApp delivery and automation workflows.
