# Ambi — team handoff

Ambi: Life Together, published by CodeCrusher LLC.

## Public Supabase connection

Copy `.env.example` into your project root as `.env`:

```env
EXPO_PUBLIC_SUPABASE_URL=https://stfwqhaqrfaetwducmlp.supabase.co
EXPO_PUBLIC_SUPABASE_ANON_KEY=sb_publishable_jVKuVYiu8d7hUQikOWQB3g_o1srQuga
```

This is a public client/publishable key, not a backend admin credential. Database access remains governed by Supabase authentication and row-level security. Never add a service-role key to a client app.

## Project and assets

- Original source repository: https://github.com/devmansoor404/ambi
- iOS bundle identifier: `co.codecrusher.ambi`
- [App assets](assets/): icon, splash, illustrations, and sounds.
- [App Store screenshots](app-store-screenshots/): five native iPhone screenshots, 1206 × 2622 JPEG.
- [Download this handoff](https://github.com/haris-bit/ambi-team-handoff/archive/refs/heads/main.zip)

This repository contains the public connection details and assets only. The original source repository may not contain all subsequent local development changes. Do not treat it as the complete current release source.

Private credentials, signing files, reviewer logins, and local machine paths are intentionally excluded. Asset inclusion does not grant an additional license; obtain permission from CodeCrusher LLC before reuse outside the team’s project.
