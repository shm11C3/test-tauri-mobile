# Tauri-Test

`alpha` 版 `Tauri` の検証用

## 前提条件

- 以下の環境が整っていること
  - Node.js
    - `Node.js 18=<`
  - Rust
    - `rustc 1.67=<`
  - Android Studio
    - Android SDK
    - Android NDK
      - [Setup Android NDK](https://developer.android.com/studio/projects/install-ndk)
  - (Windows) : [Active Developer Mode](https://learn.microsoft.com/en-us/windows/apps/get-started/enable-your-device-for-development)

## 環境変数の設定

### Windows

`$env:SDK_HOME="$env:LocalAppData\Android\Sdk"`

`$env:NDK_HOME="$env:LocalAppData\Android\Sdk\ndk\26.1.10909125"`

## 参考リンク

- [環境構築](https://beta.tauri.app/guides/prerequisites/#android)

- [コマンド](https://beta.tauri.app/2/reference/cli/#android)

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
