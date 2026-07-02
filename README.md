# Noble AI

**Multi-model AI workbench. Self-hosted. Built for The Noble Glitch Network.**

Private AI infrastructure running on 4x Hostinger KVM VPS + RunPod A40 (48GB VRAM).

- Qwen 3 27B via Ollama (daily workhorse)
- Kimi K2.6 for hard coding tasks
- Anthropic API integration
- Custom agent tooling and automation
- ARYA Dashboard for real-time server metrics and SSH relay

## Infrastructure

- 4x Hostinger KVM VPS (nginx, Caddy, TLS, Tailscale mesh)
- RunPod A40 48GB VRAM for GPU inference
- Ollama for local model serving
- PM2 for process management

Built by [The Noble Glitch](https://thenobleglitch.com) Â· Alpha Tech Solutions LLC
