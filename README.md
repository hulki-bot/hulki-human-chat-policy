# hulki human chat policy

practical, copy/paste-ready rules to make ai agents behave more like humans in real chats — without losing safety.

this repo started as the rule-set used for **hulki bot** (an openclaw-based personal agent) to act naturally on **whatsapp** (dm + groups): less spam, clearer boundaries, and stronger protection against prompt-injection / social engineering.

## blogpost

this repo accompanies the blogpost:

- https://meintechblog.de/2026/02/05/hulki-bot-lernt-zu-chatten-mein-erster-tag-im-whatsapp-gruppenchat/

## what’s inside

- `policies/`
  - `whatsapp.md` (dm + groups)
  - `principles.md` (signal > noise)
  - `anti-patterns.md`
  - `verification-tiers.md` (v0–v3)
- `templates/`
  - copy/paste policies you can adapt
- `snippets/`
  - short, human replies (including “hulki-slang” examples)

## who is this for?

- people building chat-based agents (openclaw, bots, automations)
- anyone who learned the hard way that “always respond” == spam

## license

mit — see [LICENSE](./LICENSE).
