# FullStack Camp💪 をやってみた①

「1つのアプリを違うフレームワークで🔥」

#### 🎯概要
フルスタックエンジニアとして実践的なスキルを習得するためのプログラムを考えました。

- 技術力を向上させたい
- 開発を経験したい
- フルスタックエンジニアへの憧れ

## FullStack Campとは？

GitHubの人気レポジトリRealWorldを参考にフルスクラッチでアプリ開発

#### RealWorld
参照：
[GitHub](https://github.com/gothinkster/realworld/blob/main/README.md)

>While most "todo" demos provide an excellent cursory glance at a framework's capabilities, they typically don't convey the knowledge & perspective required to actually build real applications with it.

>RealWorld solves this by allowing you to choose any frontend (React, Angular, & more) and any backend (Node, Django, & more).

#### 翻訳
>ほとんどの「ToDo」デモは、フレームワークの機能をざっと見るのには適していますが、それを使って実際のアプリケーションを構築するために必要な知識や視点を十分に伝えることはできません。

>RealWorld はこの問題を解決するために、あらゆるフロントエンド（React、Angular など）と、あらゆるバックエンド（Node、Django など）を自由に選択できるようにしています。

#### -> 別名：「デモアプリの母」

## 何を作るか？📲
#### SNSのデモアプリ
- ユーザー認証
- プロフィール作成
- 投稿
- リアルタイム通知
- タイムライン取得

技術選定から開発、デプロイまでを全て一人で行う。

## どんな技術で作るか？💻

**Spring**と**TypeScript**を検討
<br>
#### Webアプリ
バックエンド

| 技術            | 有用性 |
|-----------------|--------|
| Spring Boot     |RestAPIの高速開発
| GraalVM         |起動時間短縮&メモリ消費削減
| Spring Data JPA |投稿などのデータ管理
| Spring Security |認証や不正アクセスi防止
---
##### Q.フロントエンドでは以下4つのうち何を選ぶべきか？
1. Angular
2. Next.js
3. React
4. Vue.js
#### ChatGPTに聞いてみた
| 技術    | Springとの相性     | ユースケース                   |
| ---     | ---                | -                              |
| Angluar | ⭐︎⭐︎⭐︎⭐︎（良い）   | 大規模な管理画面
| Next.js | ⭐︎⭐︎⭐︎⭐︎⭐︎（最高） | SEOを重視するWebアプリ
| React   | ⭐︎⭐︎⭐︎⭐︎（良い     | シングルページアプリケーション
| Vue.js  | ⭐︎⭐︎⭐︎（普通）     | 小規模なWebアプリ

### 【採用】Next.js㊗️
---
#### 次回

