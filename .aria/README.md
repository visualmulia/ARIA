# A.R.I.A — Automated Responsive Intelligence Assistant

Personal AI co-pilot for Ardyan @ Masbro Studio, Bali.

## Stack

- OpenClaw 2026.5.28 (gateway)
- Anthropic Claude Opus 4-8
- WhatsApp via Baileys (personal number)

## Setup untuk developer lain

1. `npm install -g openclaw@latest`
2. `openclaw plugins install @openclaw/whatsapp`
3. Copy semua file dari `.aria/` ke `~/.openclaw/workspace/`
4. Copy `openclaw.json.example` → `~/.openclaw/openclaw.json`
5. Isi API key Anthropic + nomor WA
6. `openclaw gateway install && openclaw gateway start`

## File Structure

.aria/
├── SOUL.md # Kepribadian & konteks ARIA
├── IDENTITY.md # Identity config
├── AGENTS.md # Agent definitions
├── TOOLS.md # Available tools
├── USER.md # User profile
├── HEARTBEAT.md # Heartbeat config
├── openclaw.json.example
├── memory/
│ └── projects.md # Proyek aktif Masbro Studio
└── README.md
