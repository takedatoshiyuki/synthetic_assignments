このリポジトリのデータセットは、大学教員がそれぞれの専門分野におけるレポート課題について、生成AIのインパクトを評価する際の参考となるように作成しました。
「生成AIを使ったレポートのレベル感」や「レポート評価支援の生成AI利用の可能性」などの検討の参考資料として、ご自由に利用ください。

データの簡易ブラウジング [https://takedatoshiyuki.github.io/synthetic_assignments/](https://takedatoshiyuki.github.io/synthetic_assignments/) も提供しています。

**注意: 生成AIの性質上、本データセットのコンテンツは正確さに欠ける可能性があります。AI生成物の評価以外の利用時にはご注意ください。**

データセットには、[大学教育の分野別質保証のための教育課程編成上の参照基準](https://www.scj.go.jp/ja/member/iinkai/daigakuhosyo/daigakuhosyo.html) で作成・公表されている33分野の生成データが含まれています。
生成データは、以下のの種類は以下の通りです。

- 生成データ (５種類): シラバス、レポート課題、評価基準、レポート、評価結果
  - このうちレポート課題の種類４種類: 説明型、意見型、応用型、探究型
- 生成AI (６モデル: すべてAPI版): GPT-4o、GPT-4o-mini, o3-mini（OpenAI）、Gemini 1.5 Pro、Gemini 1.5 Flash（Google）、Claude 3.5 Sonnet、Claude 3.5 Haiku（Anthropic）の6種類（シラバスはGemini 1.5 Flashのみ）

生成データ本体は [generated フォルダ](https://github.com/takedatoshiyuki/synthetic_assignments/main/generated) に保存されています。
詳細は、[About](https://takedatoshiyuki.github.io/synthetic_assignments/about)をご参照ください。

docsフォルダは、本データセットの内容の簡易ブラウジング (GitHub Pages利用) のためのものです。

**更新情報**

- 2025/2/12  AIモデルにo3-mini (high) を追加

