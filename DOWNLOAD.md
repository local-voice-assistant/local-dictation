# 下载与安装

**当前版本**：0.1.0  
**系统要求**：Apple Silicon · macOS 13 或更新

## 获取安装包

[前往 GitHub Releases](https://github.com/local-voice-assistant/local-dictation/releases/latest)

下载 `LocalDictation-0.1.0-arm64.dmg`，并核对 [`latest.json`](latest.json) 里的 sha256。

安装包里已经带有本机识别模型（Paraformer、Silero、GTCRN）。

## 打开

1. 打开 dmg，把「本地听写」拖到「应用程序」
2. 第一次若被拦截：右键图标 → 打开；或到「系统设置 → 隐私与安全性」点「仍要打开」
3. 必要时在终端执行：

```bash
xattr -dr com.apple.quarantine "/Applications/本地听写.app"
```

返回 [首页](README.md)
