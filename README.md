# LAIMAŹ

**Where dating finds direction.**

LAIMAŹ is an India-first, intentional dating product for adults who want genuine connection and are open to building a lasting relationship, with marriage in mind.

## Product direction
- Modern dating experience, not a matrimonial directory
- Personality-led profiles and meaningful conversations
- Choice, clarity, privacy, consent and safety as core principles
- Adults 18+; age assurance and moderation are launch requirements

## Current prototype
- `index.html`: responsive brand landing page
- `auth.html`: existing Supabase email sign-up, password login and email sign-in-link flow

## Important limitations
The current prototype does not yet implement dating profiles, discovery, likes, matching, chat, verification, moderation or safety workflows. Do not present these as available until they are built and tested.

## Development notes
- Preserve existing Supabase Auth users and profile data.
- Review database schema and Row Level Security policies before adding dating features.
- Never expose service-role credentials in browser code.
- Keep private data, exact location and sensitive preferences out of public profile queries.
- Complete legal, privacy, safety and age-assurance review before public launch.

## Deployment
The repository is currently configured for GitHub Pages. The existing Supabase project and authentication redirect configuration must be reviewed before changing production URLs or domains.
