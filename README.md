# 阆风八字排盘 App

八字排盘安卓应用，基于 Capacitor 构建。

## 项目结构

- `www/` - 网页文件（已包含八字排盘页面）
- `android/` - Android 原生项目
- `.github/workflows/` - GitHub Actions 自动构建

## 本地开发

```bash
# 安装依赖
npm install

# 同步到 Android
npx cap sync android

# 打开 Android Studio
npx cap open android
```

## 自动构建

推送代码到 GitHub 后，GitHub Actions 会自动构建 APK。

## 技术栈

- Capacitor 8.x
- 纯 HTML/CSS/JavaScript 八字排盘
