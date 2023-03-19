# 最終更新日

2023 年 3 月 19 日

---

# 基本情報

| key      | value                     |
| -------- | ------------------------- |
| 名前     | 西邨悠哉                  |
| 年齢     | 満 22 歳                  |
| 出身地   | 兵庫県                    |
| 最終学歴 | 徳島大学 理工学部　情報系 |

---

# 業務経歴

私は、Fiah 株式会社https://fiah.ai/
にて、七ヶ月ほどエンジニアのインターンを行っています。 以下に、過去のインターンにおいて、携わらせていただいたプロジェクトに関する概要と詳細を記 載しています。


## プロジェクト概要

履歴書作成サービスのバグ回収業務・新機能の実装

### プロジェクト期間

2022 年 11 月 15 日 〜 現在進行中

### 活動頻度

週 4 から 5 回(3~5 時間/day)

### 使用技術

- Ruby
- Ruby on Rails
- React
- Next.js
- Typescript
- styled-components
- Storybook
- Recoil
- React Hooks
- TanStack Query(旧React Query)
- aspida

### 実装内容

- 職歴ページの新規実装
- 各ページの入力項目・機能の追加
- RailsAPI側との連携・非同期処理
- カスタム hook の作成
- バグ・スタイル修正

### 担当業務

エンジニア 3 人(フロント×1, フロント&バック×2, PM×1, リーダー×1)でのチーム開発であった 。私は、バックエンドとフロントエンドの両方で主にバグ回収がメインの業務だった。迅速対応を 行うことで、品質向上に貢献した。また、Biz 側と連携し、UIの修正なども行った。また、新規 のページの追加や既存のページの入力項目の追加、また、それら必要なカスタム hook の作成も行 っている。開発フローとしては、OpenAPI の yaml ファイルを submodule で取り込み、そのファイ ルから aspida により、型定義ファイルを作成した上で、機能の追加を行っている。

---

## プロジェクト概要

SPI 対策(問題集・解説)サービスのバグ回収業務・新機能の実装

### プロジェクト期間

2022 年 10 月 〜 2022 年 11 月 15 日まで(約 1 ヶ月半ほど)

### 活動頻度

週５から 7 回(3~7 時間/day)

### 使用技術

- Ruby
- Ruby on Rails
- React
- Next.js
- Typescript
- styled-components
- Storybook
- Recoil
- React Hooks
- React Hook Form
- SWR
- aspida

### 実装内容

- 10 個ほどの共通コンポーネントの実装
- 10 個ほどの共通コンポーネントのストーリーファイル作成
- 6 つのページの新規実装(新規登録画面)
- バグ・スタイル修正
- React Hook Form を用いた、プロフィール・ログインフォームの実装 ・Rails と連携した機能(ログイン・ログアウトなど)の実装

### 担当業務

フロントエンドを担当した。その中で主に新機能の追加実装を行った。アトミックデザインが導入 されていたため、既存のコンポーネントを利用し、また足りない箇所に関しては、自分で作成しな がら、それを組み合わせることで新規登録画面のページの作成を行った。新規登録におけるサイン アップやログイン・ログアウトの処理に関しては、stoplight で作られえたエンドポイントを参考に リクエストの処理を実装した。また、リリース前には、スタイルやバグ修正を迅速に行うことでプ ロダクトの品質向上に貢献した。

---

## プロジェクト概要

エントリーシートを自動採点してくれるモバイルアプリにおけるバックエンド部分の新規開発

### プロジェクト期間

2022 年 8 月 〜 2022 年 10 月まで(約 2 ケ月ほど)

### 活動頻度

週５回(8 時間/day)

### 使用技術

- Ruby
- Ruby on Rails
- Rspec
- Rubocop
- JWT
- ECS(Fargate)
- Terraform/Terragrunt
- GithubActions
- Docker
- Faraday

### 実装内容

- DB 設計
- エンドポイント設計
- JWT を用いた認証(フロントがモバイルのため匿名認証+会員認証)とそれに伴うアクセス制御 ・faraday を用いて、外部 API(ES を自動採点する lamda)との連携
- ES やそれらをグルーピングするフォルダの一覧機能の実装
- 会社の検索機能
- Rspec によるテスト

### 担当業務

この PJ では、DB 設計・エンドポイント設計・実装・テスト・デプロイまでを上司に相談しながら 、一人で担当した。最初は miro を用いて DB 設計を行い、その後 stoplight を用いて、OpenAPI に y よるエンドポイント設計をした。次に設計したものを参考に実装を行い、OpenAPI と Rspec を連携 し、テストの追加も行った。初めての業務だったため、周辺ツールの使い方など、覚えることが多 かったが迅速にキャッチアップしデプロイまで行った。

