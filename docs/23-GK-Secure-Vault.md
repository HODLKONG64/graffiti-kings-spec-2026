**GK Secure Vault (Sandbox Runner)**

**Tagline:** “Test anything. Risk nothing.”

**Why It Exists**
Users generate code via GitHub Agent and want to test it safely. GK Secure Vault gives a one-click disposable Windows environment using Microsoft’s built-in Windows Sandbox.

**Core Features (MVP)**
- Simple UI: Drag & drop file/folder
- Smart .wsb Generator with safe defaults (network off, read-only, Protected Client)
- Two Preset Modes: Safe Test + AI Coding Mode
- Auto Reports (file hash, timestamp, config used)
- One-Click Codex/OpenAI support with safety warnings

**Safety Rules (Hardcoded)**
- Never map host folders as writeable by default
- Always warn before enabling networking
- Never install drivers or kernel components

**SPARK Example:**
“You just generated some code. Want me to spin up a Secure Vault so you can test it safely first?”