# Latent Framework でみた Scrum の構造と限界、及びその補正

---

## 1. 概要

| 視点                   | Scrum が強い層                                  | Scrum が弱い／空白になりやすい層                                                                      |
| -------------------- | ------------------------------------------- | ---------------------------------------------------------------------------------------- |
| **Latent Framework** | 🧵 **Craft**（作業構築）<br>🥼 **Science**（計測・検証） | 📕 **Story**（衝動 / 論理 / 転調）<br>🌾 **Economy**（流通・資本）<br>⚔️ **Force** の一部（Norm・Propaganda） |

### 要点

Scrum は「作る」🧵 と「測る」🥼 の方法論に特化した軽量エンジン。Story（動機・意味）や外部接続（Economy／Force）は 前提 or 外付けモジュール として扱われている。

したがって Story が弱いチームでは “やらされ 🎭  Scrum” に陥りやすく、そして大抵の Project は Story が弱い。

---

## 2. Scrum 10 要素 × Latent 27 要素 マッピング

| #  | Scrum 要素             | 区分       | 対応 Latent 要素                                        | ひと言根拠               |
| -- | -------------------- | -------- | --------------------------------------- | ------------------- |
| 1  | Product Owner        | ロール      | ☝️ Logic ・ 🫱 Reframe ・ 🗝 Authority    | 価値の論理設計・優先順位転換・最終決裁 |
| 2  | Scrum Master         | ロール      | 🛡 Policy ・ 🔗 Control ・ 🙏 Custom      | フレーム順守とチーム文化の維持     |
| 3  | Developers           | ロール      | 🤌 Technique ・ 🧤 Task ・ 📏 Measurement | 実装手技・日常作業・進捗測定      |
| 4  | Sprint Planning      | イベント     | 📐 Design ・ ☝️ Logic                    | 目標を構造化しタスクへ設計       |
| 5  | Daily Scrum          | イベント     | 📏 Measurement ・ 🖥 Information         | 24 h 周期でデータと情報を同期   |
| 6  | Sprint Review        | イベント     | 🖥 Information  ・ 📣 Propaganda              | 成果を公開しフィードバック編集     |
| 7  | Sprint Retrospective | イベント     | 🤔 Prediction ・ 🫱 Reframe              | 学びを抽出し次スプリントへ転調     |
| 8  | Product Backlog      | アーティファクト | 🖥 Information ・ 📦 Flow                | 価値アイテムが流入し続ける情報レーン  |
| 9  | Sprint Backlog       | アーティファクト | 🧤 Task ・ 🖥 Information                | スプリント内タスクと可視情報      |
| 10 | Increment            | アーティファクト | 🛒 Market ・ 🚚 Logistics                | 市場に持ち出せる梱包単位        |


---

## 3. 限界ポイント（Latent 観点）

| 観察点            | 具体症状                        | 根本原因                                      |
| -------------- | --------------------------- | ----------------------------------------- |
| **Story が希薄**  | Sprint Goal が単なる「チケット合算」になる | 👏 Blues 注入の儀式が欠如                         |
| **“作業だけ”の儀式化** | Daily＝進捗報告会、Retro＝KPT 箇条書き  | ☝️ Logic・🫱 Reframe の再確認時間が無い             |
| **スケールで統合遅延**  | 依存タスクが隠れてリリース遅延             | 🔗 Control と 🖥 Information の横串不足         |
| **外部との断絶**     | 法務・資金・宣伝が Sprint 外で孤立       | 🌾 Economy／⚔️ Force（Norm・Propaganda）を扱わない |

### 3.1 Story の傀儡化（Marionette）という構文的リスク

Story が残っているように見えても、「外部の論理や評価軸に操られている語り」は 🎭 Marionette（傀儡）と呼ばれる。

| 状態 | Latent 的な構造 | Scrum 現場での典型例 |
|------|------------------|------------------------|
| 🎭 Marionette | Blues 欠如 / 他者の Logic に従属 | PO がただの仕様窓口 / Sprint Goal が上位からの一方通行な要件になる |

→ Sprint Goal を「誰の語りか？」「誰がうれしいか？」で再点検することで、自チームの Blues を再注入できる。


---

## 4. 補正アプローチ

### 4.1 Story 注入リチュアル

| タイミング              | 実施例                                 | 補完される要素    |
| ------------------ | ----------------------------------- | ---------- |
| **Day 0 Kick-off** | *Why* ワーク：ユーザーの痛みを３段掘り              | 👏 Blues   |
| **Sprint 開始**      | Goal を「問い(Blues)＋価値根拠(Logic)」の２行で宣言 | ☝️ Logic   |
| **Daily 冒頭**       | 「昨日の学び / 今日の仮説」を 1 行共有              | 🫱 Reframe |

### 4.2 Economy & Force の外付けモジュール

| モジュール       | 目的                           | 実装ヒント              |
| ----------- | ---------------------------- | ------------------ |
| 資金・リスクボード   | Capital／Investment 可視化       | CFO・スポンサーと週次更新     |
| リリース横串カレンダー | Flow (Logistics+Market) 見える化 | SoS レベルで１枚ガント維持    |
| 規範チェックリスト   | Law／Custom 違反の早期検知           | Retro の「Done?」欄に組込 |

### 4.3 SoS による Control / Information 拡張

| 追加ルール                      | ねらい     | 最小ガバナンス                   |
| -------------------------- | ------- | ------------------------- |
| **SoS 代表に決裁権**             | ブロッカー即断 | 🗝 Authority              |
| **冒頭30秒で Product Goal 再読** | ゴールずれ防止 | ☝️ Logic                  |
| **依存タスクは48h以内にオーナ指名**      | 遅延連鎖防止  | 🔗 Control＋🖥 Information |

---

## 5. まとめ

1. **Scrum は Craft／Science に尖ったフレーム**。
2. **Story（と Economy／Force の一部）を補完しないと “やらされ” 化する**。
3. \*\*Latent Framework を「前段ブースター」「空欄チェッカー」\*\*として使い、

   * Blues, Logic, Reframe を可視化
   * 資金・規範・情報統制を外付け
4. こうして **Story Driven × Science Based** の回転を取り戻すことができる。


*Scrum の失速はフレームの限界ではなく「補完忘れ」*
