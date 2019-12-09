# 進捗管理 2019.12.09

## サイズに関しての調査
### Windows
- [Win32 Standard icon](https://docs.microsoft.com/ja-jp/windows/win32/uxguide/vis-std-icons)

| Context | When to use |
|:---|:---|
| Dialog boxes | Use 32x32 pixel for content area icons; 16x16 pixel for footnote area icons. |
| In-place | Use 32x32 pixel for error pages; 16x16 pixel icons for all others. |
| Notifications | Use 16x16 pixel icons. |
| Balloons | Use 16x16 pixel icons. |
| Banners | Use 16x16 pixel icons. |

これらから判断すると、OS標準のアイコンとみなすサイズの最大値は`32x32 pixel`であると言える

ただし、`32x32 pixel`を超えるアイコンはOSの標準以外では多数存在し、境界値と言えるかどうかは不明である

### Mac
- [Mac OS App Icon size](https://developer.apple.com/design/human-interface-guidelines/macos/icons-and-images/app-icon/)
  - icon sizeについては記述なし
- [IOS App Icon size](https://developer.apple.com/design/human-interface-guidelines/ios/icons-and-images/app-icon/)
  - iPhone: 60x60 pixel
  - iPad Pro: 83.5x83.5 pixel
  - iPad, iPad mini: 76x76 pixel
- [System Icons](https://developer.apple.com/design/human-interface-guidelines/carplay/icons-and-images/system-icons/)
  - System Iconの種類についての記述
- 自分のパソコンのアイコンサイズ
  - `64x64 pixel`

-  `64x64 pixel`以下はアイコンとしてみなして顕著性マップの対象とはしないようにする。どちらか一方が64pixelより小さいものはアイコンと同等のものとみなして顕著性マップ作成の対象とはしないようにする。

## スクリーンショットの取得
- CSVに纏められたリンク先のHPを自動的にDLするシステムの作成
- カテゴリごとにフォルダに自動的に保存される

## 次週までの進捗
- 11日（水）・16日（月）に実験予定
- ウェブページのリンク集の作成とスクリーンショットの取得
- 今回決定した小さな画像（顕著性マップを作成する必要のないもの）の要素化の実装