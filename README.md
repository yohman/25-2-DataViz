# Data Vizualization – Fall 2025 Course Agenda (Bilingual)

**Instructor**: Yoh  
**Language**: 日本語 + English (50/50 mixed instruction)  
**Tools**: Google Sheets, RawGraphs, Datawrapper, Chart.js, JavaScript, GitHub Pages

---

## Week 1 – What is Data Visualization? / データの可視化とは？

**Lecture**  
- Why visualize? 情報を「見る化」することで何がわかる？  
- Reference: Week 1 slides (Intro) — **Slides 3–17**  
- Examples: Gapminder, Datasaurus, Anscombe’s Quartet  
- Visual thinkingとcommunicationの違いに注目

**Workshop**  
**Same Data, Different Story**  
- 同じ小さなデータセットを使い、それぞれ異なる目的と観衆を想定してビジュアル化  
- 描かれたグラフを比較して、「誰に何を伝えたかったか？」を分析

**Reflection**  
あなたのデザインは何を伝えるためのものでしたか？

**Homework**  
同じデータを2つの目的で可視化（手描き or Google Sheets）し、GitHub Pages に公開  
バイリンガルで意図を解説し、URL を提出

---

## Week 2 – GitHub Pages Setup / GitHub ページの公開準備

**Lecture**  
- GitHub アカウント作成とリポジトリ構造  
- GitHub Pages で HTML を公開する方法  
- GitとGitHubの基本（commit, push, pull）  
- Chart.js や JS-based tools 公開の基礎インフラとしての役割

**Workshop**  
- 各自 GitHub リポジトリ作成  
- `index.html` を作成し公開  
- 自己紹介やビジュアルの一部を反映させる

**Reflection**  
「誰かに見せる」可視化と、自分だけの可視化の違いは？

**Homework**  
GitHub Pages に自己紹介ページを公開し、URL を提出

---

## Week 3 – Data Types and Chart Forms / データ型とチャートの選び方

**Lecture**  
- Categorical / Ordinal / Quantitative  
- Tidy vs Messy data  
- Reference: Week 3 slides (Data Models) — **Slides 6–22**

**Workshop**  
- RawGraphs で複数のチャートタイプ（bar, alluvial, circle）を試す  
- それぞれの encoding の意味と適用の向き不向きを体験

**Reflection**  
「このデータにはこのグラフが合う」と思った理由は？

**Homework**  
同じデータで2種類のチャートを作成し、GitHub Pages に比較と解説を公開  
URL を提出

---

## Week 4 – Exploratory Data Analysis / 探索的データ分析

**Lecture**  
- EDA = 感じる・探る・見つける  
- データの分布、外れ値、クラスタを視覚的に理解  
- Reference: Week 4 slides (EDA) — **Slides 5–16**

**Workshop**  
- Google Sheets で scatter, histogram, boxplot を作成  
- Pivot table でサマリー分析

**Reflection**  
意外な発見や気づきはありましたか？

**Homework**  
自身の選んだデータで EDA を実施し、可視化 2 種 + 解説を GitHub Pages に公開  
URL 提出

---

## Week 5 – Visual Encoding / 視覚変数とその使い方

**Lecture**  
- Position, length, shape, color の使い方  
- Encoding によって意味がどう変わるか？  
- Reference: Week 5 slides (Visual Encoding) — **Slides 4–19**

**Workshop**  
- Datawrapper で同じデータを異なる encoding で再可視化  
- 表現を比較して意図の伝わりやすさを議論

**Reflection**  
どの encoding が一番「伝わった」と思った？ なぜ？

**Homework**  
異なる encoding で 2 種のグラフを作成し、GitHub Pages に比較＋解説を公開

---

## Week 6 – Midterm Project Planning / 中間プロジェクト準備

**Lecture**  
- プロジェクトの設計：データ選定、目的、観衆設定  
- 成功する構成とストーリーフレームの設計

**Workshop**  
- プロジェクトテーマの選定と構成スケッチ  
- 教員やクラスメートとの相談・レビュー

**Reflection**  
「誰に何を伝えたいか？」を言語化できましたか？

**Homework**  
プロジェクト提案ページを GitHub Pages に公開（データソース、目的、構成案を含む）

---

## Week 7 – Midterm Studio / 中間制作スタジオ

**Lecture**  
- フィードバックの受け取り方と反映方法  
- 過去の学生作品から学ぶ改善の視点

**Workshop**  
- 実装作業とピアレビュータイム  
- 教員による個別フィードバック

**Reflection**  
フィードバックによって変更したこと・理由

**Homework**  
中間プロトタイプを GitHub Pages に公開し、URL を提出

---

## Week 8 – Midterm Presentations / 中間発表会

**Activity**  
- 各自 5 分間でプロジェクトを発表（目的・構成・チャート・ユーザー意識）  
- フィードバックシート記入

**Reflection**  
印象に残った作品とその理由／自分の改善点

**Homework**  
自己レビュー（100–150 字）を GitHub Pages に記載

---

## Week 9 – Chart.js Fundamentals / Chart.js 入門

**Lecture**  
- Chart.js の構成要素：canvas, config, dataset  
- JS オブジェクトの基本構文  
- Live coding でサンプル作成

**Workshop**  
- Chart.js テンプレートを編集して自作グラフを作成  
- 軸・色・タイトルなどをカスタマイズ

**Reflection**  
コーディングによる可視化の利点と課題は？

**Homework**  
自作グラフを GitHub Pages に公開（JSコード含む）

---

## Week 10 – Interaction in Visualization / インタラクションの導入

**Lecture**  
- Hover, filter, toggle, drill-down  
- Exploratory vs explanatory の違い  
- Reference: Week 6 slides (Interaction) — **Slides 3–13**

**Workshop**  
- Chart.js + DOM 操作でボタンや UI と連携  
- tooltip や legend filter の実装

**Reflection**  
インタラクションはユーザー体験をどう変えた？

**Homework**  
少なくとも 1 種のインタラクション付きグラフを GitHub Pages に公開

---

## Week 11 – Animation & Transitions / アニメーションによる変化の表現

**Lecture**  
- Why animate? 強調・時系列・注意の誘導  
- Chart.js の transition オプション活用法  
- Reference: Week 10 slides (Animation) — **Slides 3–14**

**Workshop**  
- 時系列データで動きをつける  
- アニメーションを入れた before/after 比較

**Reflection**  
動きによって伝え方がどう変化した？

**Homework**  
アニメーションを含むグラフを GitHub Pages に公開し、解説を加える

---

## Week 12 – Maps & Narrative / 地図とストーリーテリング

**Lecture**  
- Choropleth, symbol maps, tile layers  
- 読者主導／作者主導ナラティブの違い  
- Reference: Week 11 slides (Maps & Narrative) — **Slides 3–15**

**Workshop**  
- Datawrapper で地図付き可視化を作成  
- ステップ型ナラティブや注釈を追加

**Reflection**  
地図を使うことで伝わりやすくなった点は？

**Homework**  
地図付きストーリービジュアライゼーションを GitHub Pages に公開

---

## Week 13 – Final Project Work Session / 最終制作セッション

**Workshop**  
- 最終プロジェクト構築作業（HTML/CSS/JS 調整）  
- Peer QA + 教員レビュー  
- モバイル表示・配色など細部調整

**Reflection**  
「伝えたいこと」に最も力を入れて表現できた部分は？

**Homework**  
最終バージョンを GitHub Pages に公開、URL 提出

---

## Week 14 – Final Presentations / 最終発表会

**Activity**  
- 5分発表（目的・対象・構成・工夫）＋ フィードバック記入  
- 相互評価シートで投票・コメント共有

**Homework**  
自己レビュー（200–300 字）と最終プロジェクトリンクを GitHub Pages に掲載