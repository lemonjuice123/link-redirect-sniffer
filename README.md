# linktracko 🔗

`linktracko` is a simple yet powerful CLI tool to **trace the redirect chain** of any URL.  
Inspired by tools like `yt-dlp` and `ani-cli`, it lets you see exactly where a shortened or obfuscated link leads.

---

## ✨ Features

- Show full redirect chain (step by step).
- `-s / --simple` mode → compact path (just the URLs).
- `--json` mode → machine-readable output.
- `--headers` option → view response headers at each step.
- Choose between `GET` and `HEAD` requests for speed.

---

## 🔧 Installation

### From source
Clone the repo:
```bash
git clone https://github.com/yourusername/linktracko.git
cd linktracko
