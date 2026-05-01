# Hey, we're VerifyBlox 👋

We make Roblox verification not suck. Link your Discord server to Roblox identities, auto-assign roles, keep the raiders out, and let your community actually trust who they're talking to.

Verify once. Works everywhere.

---

## What we're building 🛠️

**For server owners:**
- Roblox ↔ Discord account linking via OAuth — no sketchy workarounds
- Auto role assignment based on account age, group membership, group rank, and more
- Alt detection and anti-raid protection out of the box
- Cross-server verification — your members don't have to verify again in every server
- Custom branded verification pages for your community

**For developers:**
- A clean REST API to query verification status, manage bans, and automate moderation from your own bots and apps
- Webhook events so you can react in real time when someone verifies, gets flagged, or loses verification
- Straightforward auth — just grab an API key from your server dashboard and you're good to go

---

## Using the API 🔌

```
Base URL: https://verifyblox.xyz/api
Auth: Bearer <your-api-key>
```

A few things you can do with it:

```js
// Check if a Discord user is verified
GET /user/:discord_id

// Look up by Roblox ID instead
GET /user/roblox/:roblox_id

// List all verified members in your server
GET /guild/:guild_id/members

// Force someone to re-verify
POST /guild/:guild_id/reverify
```

Full docs at [verifyblox.xyz/api-docs](https://verifyblox.xyz/api-docs) — API access is a Premium feature, get your key from the dashboard.

---

## Find us 🔗

- 🌐 Website → [verifyblox.xyz](https://verifyblox.xyz)
- 📖 API Docs → [verifyblox.xyz/api-docs](https://verifyblox.xyz/api-docs)
- 💬 Discord → [discord.gg/verifyblox](https://discord.gg/verifyblox)
- 📊 Status → [status.verifyblox.xyz](https://status.verifyblox.xyz)
- 📝 Blog → [blog.verifyblox.xyz](https://blog.verifyblox.xyz)

---

## Security 🔒

Found a bug or vulnerability? Please don't open a public issue — slide into our [Discord](https://discord.gg/verifyblox) and let us know privately. We take this stuff seriously and we appreciate the heads up.

---

*Built with ☕ and way too many late nights.*
