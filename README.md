# RealTreats WhatsApp Manager

A React + Vite dashboard backed by Supabase for managing approved WhatsApp business workflows.

## Setup

1. Copy `.env.example` to `.env.local`.
2. Set the Supabase project URL and publishable/anon key. Never put a service-role key or WhatsApp access token in browser environment variables.
3. Run `npm install` and `npm run dev`.

## Current scope

- Supabase email/password authentication
- Workspace onboarding
- Unified inbox shell with account, conversation and message views
- Contact details and approval-first reply drafts
- WhatsApp connection status placeholders

## Safety

This frontend does not directly connect to WhatsApp or send messages. A trusted server-side connector and verified webhooks are required. Keep AI reply mode set to approval-required. Never expose provider tokens or Supabase service-role credentials in the browser.
