
---
layout: home
---
このリポジトリのデータセットは、大学教員がそれぞれの専門分野におけるレポート課題について、生成AIのインパクトを評価する際の参考となるように作成しました。
「生成AIを使ったレポートのレベル感」や「レポート評価支援の生成AI利用の可能性」などの検討に使っていただけます。__データの利用許諾は不要です。__

**注意: 生成AIの性質上、本データセットのコンテンツは正確さに欠ける可能性があります。AI生成物の評価以外の利用の際はご注意ください。**

データセットには、大学教育の分野別質保証のための教育課程編成上の参照基準で作成・公表されている33分野の生成データが含まれています。
生成データは、以下のの種類は以下の通りです。

- 生成データ (５種類): シラバス、レポート課題、評価基準、レポート、評価結果
  - このうちレポート課題の種類４種類: 説明型、意見型、応用型、探究型
- 生成AI (６モデル: すべてAPI版): GPT-4o、GPT-4o-mini, o3-mini (high)（OpenAI）、Gemini 1.5 Pro、Gemini 1.5 Flash（Google）、Claude 3.5 Sonnet、Claude 3.5 Haiku（Anthropic）の6種類（シラバスはGemini 1.5 Flashのみ）

本データセットの詳細は、[About](/About)をご参照ください。

データはGitHubの [https://github.com/takedatoshiyuki/synthetic_assignments](https://github.com/takedatoshiyuki/synthetic_assignments) で公開しています。

** 更新情報 **

- 2025/2/12  AIモデルにo3-mini (high) を追加


    

|生成レポート課題 | 生成データ (GitHub) | 参照基準 |
|:-------------|--------------------|--------|
| [経営学](contents/経営学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/経営学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h157.pdf)|
| [言語・文学](contents/言語・文学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/言語・文学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h166-3.pdf)|
| [法学](contents/法学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/法学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h166-2.pdf)|
| [家政学](contents/家政学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/家政学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h130515-1.pdf)|
| [機械工学](contents/機械工学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/機械工学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h130819.pdf)|
| [数理科学](contents/数理科学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/数理科学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h130918.pdf)|
| [生物学](contents/生物学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/生物学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h131009.pdf)|
| [土木工学・建築学](contents/土木工学・建築学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/土木工学・建築学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h140319.pdf)|
| [経済学](contents/経済学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/経済学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h140829.pdf)|
| [地域研究](contents/地域研究) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/地域研究) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h140903.pdf)|
| [歴史学](contents/歴史学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/歴史学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h140909.pdf)|
| [材料工学](contents/材料工学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/材料工学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h140901-1.pdf)|
| [政治学](contents/政治学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/政治学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h140910.pdf)|
| [地理学](contents/地理学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/地理学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h140930-7.pdf)|
| [文化人類学](contents/文化人類学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/文化人類学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h140930-6.pdf)|
| [社会学](contents/社会学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/社会学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h140930-5.pdf)|
| [心理学](contents/心理学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/心理学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h140930-4.pdf)|
| [地球惑星科学](contents/地球惑星科学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/地球惑星科学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-22-h140930-2.pdf)|
| [社会福祉学](contents/社会福祉学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/社会福祉学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-23-h150619.pdf)|
| [電気電子工学](contents/電気電子工学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/電気電子工学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-23-h150729.pdf)|
| [情報学](contents/情報学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/情報学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-23-h160323-2.pdf)|
| [哲学](contents/哲学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/哲学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-23-h160323.pdf)|
| [統計学](contents/統計学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/統計学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-23-h151217.pdf)|
| [農学](contents/農学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/農学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-23-h151009.pdf)|
| [物理学・天文学](contents/物理学・天文学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/物理学・天文学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-23-h161003.pdf)|
| [計算力学](contents/計算力学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/計算力学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-23-h170808.pdf)|
| [薬学](contents/薬学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/薬学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-23-h170817.pdf)|
| [サービス学](contents/サービス学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/サービス学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-23-h170908.pdf)|
| [歯学](contents/歯学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/歯学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-23-h170929-8.pdf)|
| [看護学](contents/看護学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/看護学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-23-h170929-9.pdf)|
| [医学](contents/医学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/医学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-23-h170930.pdf)|
| [化学](contents/化学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/化学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-24-h190221.pdf)|
| [教育学](contents/教育学) | [データ](https://github.com/takedatoshiyuki/synthetic_assignments/tree/main/generated/教育学) | [参照基準](https://www.scj.go.jp/ja/info/kohyo/pdf/kohyo-24-h200818.pdf)|

