# PicCute-Feedback

Public **technical support** page for [PicCute](https://github.com/Cooooldo/PicCute) (macOS image compressor). The HTML is static and can be served via **GitHub Pages**.

## App Store Connect

- **Support URL (技术支持网址)** after enabling Pages:  
  `https://cooooldo.github.io/PicCute-Feedback/`  
  (If your username casing differs in the real URL, copy it from **Settings → Pages** after publish.)

- **Feedback:** use [Issues in this repository](https://github.com/Cooooldo/PicCute-Feedback/issues).

## Enable GitHub Pages

1. Push the `main` branch to this repository.
2. On GitHub: **Settings → Pages → Build and deployment**
3. **Source:** Deploy from a branch  
4. **Branch:** `main` / **folder:** `/ (root)`
5. Save. The site will be available at the URL shown on that page (usually after one or two minutes).

## Local preview

```bash
# From this repo root
python3 -m http.server 8080
# Open http://127.0.0.1:8080
```

## 支持邮箱 / Support email

对外支持邮箱：**aimeng661@gmail.com**（已写入 `index.html` 的中英联系区块与 `mailto:`）。若日后更换，请在 `index.html` 中全局替换该地址。

## Files

- `index.html` — Bilingual (简体中文 / English) support page, hash routes `#zh` and `#en`.

When **minimum macOS** or support policy changes, update the “系统要求 / System requirements” section in `index.html` to match the shipping app (see `minimumSystemVersion` in the app’s `tauri.conf.json`).
