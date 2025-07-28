
# DevSec Scanner

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/YOUR_USERNAME/devsec-scanner.svg)](https://github.com/YOUR_USERNAME/devsec-scanner/stargazers)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/YOUR_USERNAME/devsec-scanner/pulls)

> AI-powered security scanner that finds actually exploitable vulnerabilities

## 🚀 The Problem We Solve
83% of applications have critical security vulnerabilities in production, but existing tools overwhelm developers with 1000+ theoretical issues while missing the 5 critical ones that actually get you hacked.


## 🚀 Value Proposition
- **Finds real, exploitable bugs** (not just noise)
- **AI-powered fix suggestions** for every finding
- **Fast, modular, and easy to use**
- **Supports Firebase, AWS S3, Git, APIs, Docker, MongoDB**

## 📦 Installation

### From PyPI (coming soon)
```sh
pip install devsec-scanner
```

### From Source
```sh
git clone https://github.com/yourusername/devsec-scanner.git
cd devsec-scanner
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## ⚡ Quick Start

```sh
devsec --help
devsec scan firebase ./my-firebase-app
devsec scan git ./my-repo
devsec scan s3 my-bucket
devsec scan all ./my-project
```

## 🔑 Configuration

Set your API keys and credentials via environment variables, `.env` file, or config YAML/JSON:

```env
OPENAI_API_KEY=sk-...
AWS_ACCESS_KEY_ID=...
AWS_SECRET_ACCESS_KEY=...
FIREBASE_SERVICE_ACCOUNT_PATH=path/to/serviceAccount.json
```

Or use a config file:
```yaml
OPENAI_API_KEY: sk-...
AWS_ACCESS_KEY_ID: ...
AWS_SECRET_ACCESS_KEY: ...
```

## 🛡️ Supported Platforms
- Firebase
- AWS S3
- Git repositories
- APIs (coming soon)
- Docker (coming soon)
- MongoDB (coming soon)

## 📝 Contributing
We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 📄 License
MIT License. See [LICENSE](LICENSE) for details.
