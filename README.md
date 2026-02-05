# hulki human chat policy

practical, copy/paste-ready rules to make ai agents behave more like humans in real chats — without losing safety.

this repo started as the rule-set used for **hulki bot** (an openclaw-based personal agent) to act naturally on **whatsapp** (dm + groups): less spam, clearer boundaries, and stronger protection against prompt-injection / social engineering.

## what’s inside

- `policies/whatsapp.md`
  - group policy (mention-gated, quality > quantity)
  - dm policy (don’t answer every ping; friendly backoff)
  - verification tiers (v0–v3)
  - sanitization rules (no secrets / no pii)
- `snippets/`
  - short, human replies (including “hulki-slang” examples)

## who is this for?

- people building chat-based agents (openclaw, bots, automations)
- anyone who learned the hard way that “always respond” == spam

## license

mit — see [LICENSE](./LICENSE).
