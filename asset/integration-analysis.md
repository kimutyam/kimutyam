# データ連携の分析

## 1. データ連携方法の分析

データ連携方法をボトムアップ式に分析する手法の紹介です。
以下の分析を経て、データ連携方式(API / RDS; Readonly-Data Store / イベントストーミング)を決定します。

- イベント分析 (対象データにはどのような変更理由があるか。業務を達成するうえで過不足ない状態になっているか)
- 所有分析 (機能的凝集度を踏まえどこで所有するべきか。対象データの利用用途と制約はなにか？)
- データフロー分析 (データの品質特性を踏まえ、データフロー図を組み立てる。最終的にデータフローを俯瞰して実現方法や依存関係の整合性を分析する)
- システムコンテキスト分析 (上記分析結果と、ビジネス観点・チーム体制等を踏まえて、アーキテクチャ構成との整合性をとる)

詳しくは、[そのデータ連携、ホントにそれでいいの？〜データモデル分析の重要性を説く〜](https://speakerdeck.com/kakehashi/how-to-analyse-data-integration)で解説しています。
また、システムコンテキスト分析については、[システムコンテキストの分析](./context-analysis.md)を参考にしてください。

## 2. パターンの適合

- 適合可能な(あるいは、類似する)デザインパターンはなにか？
- デザインパターンは、分割統治したサービスとの関係性にうまく適合できるか？
- デザインパターンは、アーキテクチャ特性を満たしているか？

## Appendix

### APIパターンの例

- REST API
- GraphQL
- Server-Sent Events (SSE)
- WebSocket
- BFFパターン

### RDSパターンの例

- Zero ETL
- ETL/ELTパターン
- DaaS (Data App / Data API etc..)

### イベントストーミングパターンの例

多岐にわたるため、ここでは列挙しません。
以下の資料を参考にしてください。

- [Serverless Land: Event-Driven Architecture Visuals](https://serverlessland.com/event-driven-architecture/visuals)
- [Enterprise Integration Patterns: Messaging](https://www.enterpriseintegrationpatterns.com/patterns/messaging/)
- [JavaEE勉強会有志によるEIPの解説](https://www.wikihouse.com/withoutEJB/index.php?EIP)
