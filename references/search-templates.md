# 搜索模板合集

> 使用拼好码流程第二步时直接复制使用。按能力领域分类，覆盖常见搜索场景。

## 通用搜索

```
# 搜 CLI 工具
web_search_plus(query="<能力> CLI tool OR command line 2025")

# 搜 npm 包
web_search_plus(query="<能力> npm package OR node.js library 2025 2026")

# 搜 Python 包
web_search_plus(query="<能力> Python library OR pip package 2025 2026")

# 搜 Rust 工具
web_search_plus(query="<能力> cargo crate OR Rust CLI 2025")

# 搜 Go 工具
web_search_plus(query="<能力> Go library OR Go CLI 2025")

# 搜横向对比
web_search_plus(query="<能力> vs OR comparison OR alternatives OR best 2025")

# 搜 GitHub（高星仓库）
mcp_github_search_repositories(query="<能力> language:python stars:>500 sort:stars")

# 搜 GitHub（按最近更新）
mcp_github_search_repositories(query="<能力> language:typescript sort:updated")
```

## 按能力领域

### 文件处理

```
# PDF 处理
web_search_plus(query="PDF extract text Python library comparison 2025")
mcp_github_search_repositories(query="PDF processing Python stars:>1000")

# 图片处理
web_search_plus(query="image processing CLI tool OR Python library 2025")
mcp_github_search_repositories(query="image processing CLI stars:>2000")

# 视频处理
web_search_plus(query="video editing CLI OR Python library FFmpeg alternative 2025")

# 格式转换
web_search_plus(query="markdown to HTML converter CLI 2025")
web_search_plus(query="document format conversion CLI tool 2025")
```

### AI/模型推理

```
# 本地 LLM
web_search_plus(query="local LLM inference CLI tool GGUF 2025")
mcp_github_search_repositories(query="LLM inference local CLI stars:>2000")

# Whisper STT
web_search_plus(query="whisper speech to text CLI faster whisper comparison 2025")

# TTS
web_search_plus(query="text to speech CLI local open source 2025")
```

### 网络/代理

```
# 系统代理切换
web_search_plus(query="Windows proxy switch CLI tool OR command line 2025")

# 网络诊断
web_search_plus(query="network diagnostic CLI tool traceroute alternative 2025")

# 下载工具
web_search_plus(query="video download CLI tool yt-dlp alternatives 2025")
```

### 数据处理

```
# JSON 处理
web_search_plus(query="JSON CLI processor jq alternatives 2025")

# CSV 处理
web_search_plus(query="CSV CLI tool miller alternative 2025")

# 文本搜索
web_search_plus(query="text search grep alternative ripgrep comparison 2025")
```

### DevOps/部署

```
# CI/CD
web_search_plus(query="CI/CD CLI tool GitHub Actions local runner 2025")

# 容器
web_search_plus(query="container management CLI podman vs docker 2025")

# 配置管理
web_search_plus(query="dotfiles management CLI tool 2025")
```

## 平台特定

### Windows

```
# Windows 自动化
web_search_plus(query="Windows automation CLI tool PowerShell alternative 2025")

# Windows 包管理
web_search_plus(query="Windows package manager CLI scoop vs winget vs chocolatey 2025")

# Windows 注册表
web_search_plus(query="Windows registry CLI tool 2025")
```

### macOS

```
# macOS 包管理
web_search_plus(query="macOS package manager CLI brew alternatives 2025")

# macOS 自动化
web_search_plus(query="macOS automation CLI tool 2025")
```

## 快速验证

```
# 查 stars + 更新日
terminal(command="curl -s https://api.github.com/repos/<owner>/<repo> | python3 -c \"import sys,json; d=json.load(sys.stdin); print(f'Stars: {d[chr(115)+chr(116)+chr(97)+chr(114)+chr(115)]}, Updated: {d[chr(112)+chr(117)+chr(115)+chr(104)+chr(101)+chr(100)+chr(95)+chr(97)+chr(116)]}')\"")
```

---

*拼好码(code-assembly) · 步骤 2 配套模板*
