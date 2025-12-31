## pre-requisites (not necessarily in this order)

---

- `fabric-ai` github repo
	- [link to repository](https://github.com/danielmiessler/Fabric.git)
- `yt-dlp` install
	- `brew install yt-dlp`
	- [link to repository](https://github.com/yt-dlp/yt-dlp.git)
- `homebrew` install
	- `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
	- [link to repository](https://github.com/Homebrew/homebrew-core.git)
	- [link to installation instructions](https://docs.brew.sh/Installation)
- `lm-studio` install
	- model download
	- [link to official website](https://lmstudio.ai/home)
	- [link to repository](https://github.com/lmstudio-ai/lms.git)

## optional additional improvements (extraneous to a basic introduction to `fabric`)

---

- cloud model providers for speed
	- [e.g. `Cerebras`](https://www.cerebras.ai)
- Tailscale networking for remote
	- SSH connection
	- `brew install tailscale`
- `fabric-ai` server in a Docker container for security
	- introduction to API requests
- `fabric-mcp` server for a mutual relationship between `fabric` and `LM Studio`
- custom patterns and strategies for even more possibilities

## repo workflow

---

1. `homebrew` installation and introduction

2. `yt-dlp` installation

3. `lm-studio` installation and introduction

4. `fabric-ai` installation

5. `fabric-ai --setup`
	- patterns and strategies download (required)
	- AI vendor configuration (required)
		- model configuration (required)
	- `yt-dlp` configuration

6. optional additional improvements
