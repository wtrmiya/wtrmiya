# iOS Developer Showcase

## 自己紹介

宮腰　航

## スキル
### Swift Frameworks & Libraries
- SwiftUI / UIKit / AutoLayout
- Modern Concurrency / Concurrency
- CoreData / Realm / SwiftData
- URLSession
- Combine / RxSwift
- Local Push / Remote Push
- Widget
- Quick Actions / Universal Link / Custom URL Scheme
- Notification
- Kingsfisher / SwiftLint / MarkdownUI / LicenseList

### Source Control
- Git

### CI/CD
- fastlane / GitHub Actions / Bitrise

### クラウド
- Firebase
  - Authentication
  - Firestore
  - Storage
  - Cloud Messaging
  - Crashlytics
- AWS
  - 環境設計・構築・運用

### OS
- MacOS
- Windows
- Linux

### 他の使用可能言語
- Python
- HTML / CSS / JavaScript

### デザイン
- Figma

### 開発環境構築
- docker

### ネットワークユーティリティ
- postman / curl

## Sample Project1: NewsApp

<img width="300" src="https://github.com/user-attachments/assets/b82c4d68-7ebd-4be2-a843-220731aa5601">
<img width="300" src="https://github.com/user-attachments/assets/62410fa8-bf2e-48e6-9602-c9ba593d0228">
<img width="300" src="https://github.com/user-attachments/assets/44927690-f36b-4e15-b923-8b7d3e81bd81">

### URL
https://github.com/wtrmiya/NewsApp

### 概要
ニュースビューアサンプルプロジェクト
- ニュースソース: News API (https://newsapi.org/)

### 仕様・考慮点

- Firebaseを使用したアカウント管理・データ管理
  - Configuration切り替えによるFireabse接続先の切り替え(開発・本番)
  - Firebase Authenticationによるアカウント管理
  - Firebase Firestoreによるユーザ設定情報、ブックマークの管理
  - Firebase Firestoreによる利用規約の提供(不要なアプリアップデートの回避)
- ログイン状態に対応した機能制限
- fastlaneによる自動ユニットテスト実行(GitHubへのpush時)
- URLSessionによる外部API(News API)からの情報取得
- Dependency ContainerによるInitializer Injectionの実現
- Architecture: MVVM
- Figmaによるデザインおよび、SwiftUIによるデザイン実装
  - デザイン参考元: https://ground.news/app
- ダークモード実装
- Gitへのシークレット情報登録除外(API key、Firebase設定ファイル)
- トーストによる操作結果通知

## Sample Project2: 最近の飲みかた - DrinkingLog

![drinkingLog_1](https://github.com/user-attachments/assets/28e60d2a-7e9f-45f6-b001-341622e27b71)
![drinkingLog_2](https://github.com/user-attachments/assets/38b3b05e-8f6f-41fe-8772-172eb56a8d4b)
![drinkingLog_3](https://github.com/user-attachments/assets/053498b8-7950-4dc3-934f-945bfad1e153)

### URL
https://apps.apple.com/jp/app/%E6%9C%80%E8%BF%91%E3%81%AE%E9%A3%B2%E3%81%BF%E3%81%8B%E3%81%9F/id1670227819

iOSのみ利用可能

### AppStore
https://github.com/wtrmiya/NewsApp

### 概要
ライフログ系サンプルプロジェクト


### 仕様・考慮点
- App Storeへのリリース作業内容確認を目的とする
- Realmによる永続化対応
- 日本語・英語の国際化対応
- Firebase Crashlytics

## Other Sample Projects
### LaunchPractice
#### Summary
UIKitおよび、SwiftUIベースで作成したiOSアプリプロジェクトのそれぞれについて、AppDelegate、SceneDelegate有無におけるデリゲートメソッドの実行順序を調査した。

#### URL
https://github.com/wtrmiya/LaunchPractice




