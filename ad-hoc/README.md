# Ad hoc Userscripts Collection

This repository contains ad hoc userscripts for fixing web annoyances or bugs.

---

## 🚀 Getting Started
1. Install a userscript manager, such as [Tampermonkey](https://www.tampermonkey.net/) or [Violentmonkey](https://violentmonkey.github.io/).
2. Click the install link for any script below or browse the scripts in this directory.

---

## 📜 Available Scripts

### Fix Double-Encoded Characters in URLs
Fixes a Microsoft Edge bug where URLs with Chinese characters (漢字/中文字) become double-encoded. Resolves Wikipedia errors like `請求的頁面標題包含無效的字元` that can occur after clicking links from Google search results.

- [Install Fix Double-Encoded Characters in URLs](https://greasyfork.org/en/scripts/539005-fix-double-encoded-characters-in-urls)
- The script runs automatically on any URL (e.g., [These](https://answers.microsoft.com/zh-hant/microsoftedge/forum/all/edge%E6%96%BCyt%E8%A7%80%E7%9C%8B%E7%9B%B4/1a38b32b-3da0-4e2f-9a00-e550c06b5426)) containing double-encoded characters.
- No configuration needed; it will attempt to fix the URL and reload the page if necessary.

---