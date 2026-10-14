# kazuhitotakao

**Webアプリケーション開発・個人開発**

PHP / LaravelでのWebアプリケーション開発と、Nuxt / Vue.js / TypeScriptを使った個人開発に取り組んでいます。学習成果物として予約・フリマ・勤怠管理アプリを制作し、個人開発ではブラウザゲーム「こうちゃんの大冒険」を公開しています。

公開コードを通じて、画面づくりやデータ管理などの実装内容を紹介します。Vue.jsは使用経験があり、Reactは現在勉強中です。

## 使用技術・学習中

以下の使用技術は、掲載作品のREADMEと公開コードで確認できるものです。個人開発・学習での使用経験として記載しています。

| 分野 | 使用技術 | 主な実装内容 |
| --- | --- | --- |
| フロントエンド | Nuxt 3 / Vue.js 3 / TypeScript / HTML / CSS | ゲーム画面、状態管理、ブラウザ内への進行保存、画面サイズに応じた表示 |
| バックエンド・データベース | PHP / Laravel / MySQL | 認証、出品・購入、飲食店予約、勤怠記録、CSV取り込み |
| 外部サービス連携 | Stripe | フリマアプリのテスト決済 |
| 開発環境 | Docker / Docker Compose / nginx | Laravelアプリの開発環境構築 |

**学習中：React**  
コンポーネントの考え方や状態管理などの基礎を学んでいます。

## 作品一覧

### 1. こうちゃんの大冒険（kouchan-game）｜個人開発

こうちゃんと公園を探検する、選択式のブラウザゲームです。遊びや休憩を選びながら、子どもの体力・機嫌と親の体力・余裕を考えて進めます。

- **主な実装**：行動による時間・ステータスの変化、進行の保存・再開、ミニゲームの解放、PWA対応
- **使用技術**：Nuxt 3 / Vue.js 3 / TypeScript / CSS
- **URL**：[公開コード](https://github.com/kazuhitotakao/kouchan-game) · [ゲームを遊ぶ](https://kouchan-game.vercel.app/)

### 2. coachtechフリマ（flea-market）｜学習成果物

商品の出品から購入までの流れを実装したフリマアプリです。

- **主な実装**：商品検索、画像付き出品、お気に入り・コメント、購入履歴、Stripeのテスト決済
- **使用技術**：PHP / Laravel / MySQL / Docker / Stripe
- **URL**：[公開コード・README](https://github.com/kazuhitotakao/flea-market)

### 3. Rese｜学習成果物

飲食店の検索・予約ができるアプリです。利用者向けの機能に加え、店舗代表者・管理者向けの画面を実装しています。

- **主な実装**：予約・変更・キャンセル、お気に入り、画像付き口コミ、店舗情報のCSV取り込み
- **使用技術**：PHP / Laravel / MySQL / Docker
- **URL**：[公開コード・README](https://github.com/kazuhitotakao/Rese)

### 4. Atte（attendance）｜初級模擬案件

出退勤と休憩時間を記録する勤怠管理アプリです。

- **主な実装**：メール認証、勤務・休憩の開始と終了、日付別・ユーザー別の勤怠一覧、ユーザー検索
- **使用技術**：PHP / Laravel / MySQL / Docker
- **URL**：[公開コード・README](https://github.com/kazuhitotakao/attendance)

## 現在の学習方針

既存作品の改善を通じて、Vue.js / Nuxt / TypeScriptの理解を深め、読みやすく保守しやすいコードを目指します。PHP / Laravelでは認証やデータ管理の基礎を固めながら、Reactの基礎学習も進めています。

このプロフィールREADMEは、[kazuhitotakao](https://github.com/kazuhitotakao/kazuhitotakao)で管理しています。
