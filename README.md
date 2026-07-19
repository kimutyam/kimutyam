<!--
**kimutyam/kimutyam** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

## 🧑🏻‍💼 略歴

- 2021年~ カケハシ
  - Data Reliability Engineering (プロダクトマネジメント・テックリード)
  - 顧客への配信基盤チームのイネーブルメント (プロダクトマネジメント・テックリード)
  - 開発組織全体の技術戦略を推進 (技術戦略室 / Chief Architect)
  - 顧客データ基盤のData as a Productの立ち上げ (アーキテクト)
  - プラットフォームドメインチーム/データ基盤チーム (アーキテクト)
  - 医療品発注・管理最適化領域の新規事業の立ち上げ (テックリード)
- 2018年~ エフ・コード
  - 開発組織の再編とプロダクトのリニューアルを担当  (VPoE)
  - CDP (Customer Data Platform) の開発を主導 (VPoE)
- 2012年~ セプテーニ (以降分社化。現、FLINTERS)
  - データ基盤事業立ち上げ
  - ソーシャルゲーム、SNS、広告配信サービスの開発

SaaS事業を支えるためのプラットフォーム基盤・データ利活用のための分析基盤の企画・設計・開発、開発など、幅広い領域で経験を積んできました。
現場で手を動かす時は、テックリードとPdMを兼務することが多く、探索的なモデリングを通じてプロダクトビジョンを具体化し、コードに落とし込むことを得意としています。
アプリケーション開発においては、関数型ドメインモデリングを用いた設計については約8年の実務経験があり、Scala や TypeScript を中心としたバックエンド開発において、ドメイン駆動設計と関数型プログラミングの設計手法を実践・体系化してきました。
データプラットフォームの基盤構築からETL設計、データオブザーバビリティの設計まで、データエンジニアリングの幅広い領域で経験を積んできました。
また、現職はアーキテクトとして100程度のアーキテクチャのレビューを担当し、システムの分割統治やそれを実現するアーキテクチャスタイルの選定などに貢献しています。

## 🌲大切にしていること

### アーキテクチャ特性駆動の設計・運用

私は、技術を選ぶ前に「何を解くべきか」「なぜその選択が必要か」を明らかにすることを大切にしています。
事業やプロダクトの目的、ドメインの構造、データの所有と流れ、求める品質、運用するチーム、そして時間やコストの制約までを捉え、それぞれの関係とトレードオフを踏まえて設計します。
それらをアーキテクチャ特性にまとめ、特性の優先度を明確にすることで、技術選定や設計の判断を一貫して行えるようにしています。
インフラ構成やアーキテクチャスタイルの選定、APIやイベント駆動の方式の具体的な設計は、アーキテクチャ特性で論拠となった判断をもとに行います。

### データ利用・制約をアプリケーション開発でシフトレフト

アプリケーションの機能に最適化された状態管理だけをしている場合は大抵、データ利活用で必要な業務知識が十分に反映されません。
例えば、「注文をキャンセルする」業務をアプリケーションで「注文データの削除」をしている場合は、「キャンセルした」業務の事実がデータとして残らず、後続の分析や意思決定に必要な情報が欠落します。
現場では、業務上の出来事をモデリングし、アプリケーション内で構造化した上でイベントデータの記録・伝達を行う仕組みを取り入れています。
また、法令や利用規約の制約によってデータの返却・破棄を行うことがありますが、これらは未然に設計していなければ取り返しのつかないことになります。
データ管理・利活用の観点をアプリケーション開発の初期段階から取り入れることを支援しています。

### モデルを論拠とした分割統治の設計

事業ドメインの概念 (問題) をそのまま組織体制に反映させると、コンウェイの法則が働き、組織の境界がシステムの境界に影響を与えます。
分割統治法 (問題を分割する方法は解を合成する方法に依存する) に基づき、問題をそのままにせずに、解決領域のモデル(ドメインモデル)を整理し、
逆コンウェイの法則を意識して、コミュニケーション境界を定めます。

## 📖 書籍レビュー

- 執筆中: バックエンドTypeScriptの設計本 (2026年内に出版予定)
- レビュー参加: [データプラットフォーム技術バイブル ～要素技術の解説から実践的な構築法、利活用まで～](https://book.mynavi.jp/ec/products/detail/id=147013)

## 🔗 メディア

- [Zenn](https://zenn.dev/kimutyam)
- [Medium](https://kimutyam.medium.com/)
- [Speaker Deck](https://speakerdeck.com/kimutyam)

#### メディア記事の抜粋

- 2024-02-26 [ZodでAlways-Valid Domain Modelを実現する](https://zenn.dev/kimutyam/articles/zod-domain-model)
- 2021-12-02 [【応用編】fp-tsのEitherを使った異常系処理](https://kimutyam.medium.com/fp-ts-either2-6d48e8297a01)
- 2021-12-01 [【基礎編】fp-tsのEitherを使った異常系処理](https://kimutyam.medium.com/fp-ts-either1-767570abeffb)
- 2020-10-17 [実践Scio (基礎編)](https://kimutyam.medium.com/scio-in-practice-9f60888ad7db)
- 2018-12-25 [コンテキストマップの目的再考と運用ヒント](https://kimutyam.medium.com/%E3%82%B3%E3%83%B3%E3%83%86%E3%82%AD%E3%82%B9%E3%83%88%E3%83%9E%E3%83%83%E3%83%97%E3%81%AE%E7%9B%AE%E7%9A%84%E3%81%AE%E5%86%8D%E8%80%83%E3%81%A8%E9%81%8B%E7%94%A8%E3%81%AE%E3%83%92%E3%83%B3%E3%83%88-59fb49dbcb00)
- 2018-10-23 [Scrumにおいてのストーリーポイントの効果](https://kimutyam.medium.com/scrum%E3%81%AB%E3%81%8A%E3%81%84%E3%81%A6%E3%81%AE%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AA%E3%83%BC%E3%83%9D%E3%82%A4%E3%83%B3%E3%83%88%E3%81%AE%E5%8A%B9%E6%9E%9C-fc1bb13b677a)

#### 勤め先への寄稿記事・インタビュー

- 2026-05-20 [ETL 変換処理の設計原則 — PySpark を例に](https://kakehashi-dev.hatenablog.com/entry/2026/05/20/093000)
- 2026-02-02 [「もし、○○な仕様のサービスを立ち上げるなら、あなたはどんなアーキテクチャを組みますか？」著名企業のエンジニアに聞いた ~ 急成長中のBtoC ECサイト運営企業にデータ分析基盤をゼロから構築するなら~ ](https://findy-tools.io/articles/architecture-ogiri-2/191)
- 2025-07-02 [一休の伊藤直也氏に聞く、フルベットしない技術ポートフォリオ戦略　〜実践から学ぶ、医療変革プラットフォーマーの次なる一手〜](https://kakehashi-dev.hatenablog.com/entry/2025/07/02/150912)
- 2025-05-27 [CTO・チーフアーキテクト・VPoTが語り明かす、カケハシの技術戦略と組織ビジョン](https://kakehashi-dev.hatenablog.com/entry/2025/05/27/110000)
- 2025-02-17 [データ資産をシームレスに伝達するためのイベント駆動型アーキテクチャ](https://speakerdeck.com/kakehashi/event-driven-architecture)
- 2024-12-24 [技術戦略策定のリアル：カケハシの開発組織が歩んだ軌跡と、戦略の策定プロセス](https://kakehashi-dev.hatenablog.com/entry/2024/12/24/090000)
- 2024-08-22 [そのデータ連携、ホントにそれでいいの？ 〜データモデル分析の重要性を説く〜](https://speakerdeck.com/kakehashi/how-to-analyse-data-integration)
- 2024-05-15 [ドメインイベントを伝達するためのモデリング技法](https://kakehashi-dev.hatenablog.com/entry/2024/05/15/090000)
- 2023-12-24 [アーキテクチャの進化はドメインイベントが起点になる](https://kakehashi-dev.hatenablog.com/entry/2023/12/24/091000) 
- 2023-07-05 [80歳までものづくりに携わり続けたい〜アーキテクト・木村彰宏〜｜月イチ！カケハシさん](https://blog.kakehashi.life/n/n2ea5f0ad663d)
- 2022-12-24 [マイクロサービスを考慮した認可の設計](https://kakehashi-dev.hatenablog.com/entry/2022/12/24/000000) 
- 2022-03-07 [なぜバックエンドTypeScriptか？技術選定背景と実践例を紹介します](https://kakehashi-dev.hatenablog.com/entry/2022/03/07/100000)
- 2021-12-12 [データ構造を踏まえてIDを設計しよう](https://kakehashi-dev.hatenablog.com/entry/2021/12/12/080000) 
- 2017-02-21 [単一責任の原則(SRP)についての見解と方法論](https://blog.flinters.co.jp/entry/2017/02/21/164127)

### 😼 資格

- Certified Scrum Master
