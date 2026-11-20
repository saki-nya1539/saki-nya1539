<img src="https://capsule-render.vercel.app/api?type=waving&color=0:98DDCA,50:D5ECC2,100:FFAAA7&height=230&section=header&text=Saki%20Tsunoda&fontSize=60&fontColor=ffffff&fontAlignY=38&animation=twinkling&desc=%E2%9C%BF%20Generative%20AI%20%C3%97%20IaC%20%E2%9C%BF%20Data%20%E2%9C%BF%20Dashboards%20%E2%9C%BF&descSize=18&descAlignY=60" width="100%" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=M+PLUS+Rounded+1c&weight=700&size=22&pause=1200&color=FF8C69&center=true&vCenter=true&width=600&lines=%E3%81%AF%E3%81%98%E3%82%81%E3%81%BE%E3%81%97%E3%81%A6%E3%80%81Saki+Tsunoda+%E3%81%A7%E3%81%99+%F0%9F%8D%91;AI+%C3%97+Infrastructure+as+Code+%E2%98%81%EF%B8%8F;%E3%83%87%E3%83%BC%E3%82%BF%E5%88%86%E6%9E%90+%26+%E4%BA%88%E6%B8%AC+%F0%9F%93%88;15%E4%BB%A5%E4%B8%8A%E3%81%AE%E8%A8%80%E8%AA%9E%E3%81%A7%E3%82%82%E3%81%AE%E3%81%A5%E3%81%8F%E3%82%8A+%F0%9F%A7%A9" alt="Typing SVG" />

<p>
  <img src="https://img.shields.io/badge/Public_Repos-69-FFAAA7?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Focus-AI_%C3%97_IaC-7FCDB5?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Based_in-Japan-F7C59F?style=for-the-badge" />
</p>

<img src="https://komarev.com/ghpvc/?username=saki-nya1539&color=ff8c69&style=flat-square&label=%F0%9F%8D%91+Profile+Views" />

</div>

---

## 🙋‍♀️ About Me

- 🎓 **大学**：東京都市大学
- 🔬 **研究室**：次世代信号処理とソフトウェア研究室 — 組込みシステムのソフトウェア開発手法と信号処理を研究しています
- ☁️ **生成AI × IaC** — 自然言語から Terraform / CloudFormation / CDK / Bicep を生成し、静的解析で自己修正、デプロイ前には必ず人がレビューするツール群「*-genie」シリーズを作っています
- 📈 **データ分析・予測** — 東京電力エリアの電力需要予測を、GitHub Actions で毎日予測・毎週再学習するパイプラインとして運用
- 📊 **Webダッシュボード** — Next.js + TypeScript で、売上分析・会計・不正検知などの可視化アプリを開発
- 🧩 **外部ライブラリなしで作る** — 正規表現エンジン、N体シミュレーション、画像処理などを標準ライブラリだけで実装して、仕組みから学んでいます

## 🛠️ Tech Stack

**Main**
<p>
  <img src="https://skillicons.dev/icons?i=python,ts,nextjs,react,tailwind,nodejs&perline=12" />
</p>

**Cloud / IaC / CI**
<p>
  <img src="https://skillicons.dev/icons?i=aws,azure,terraform,githubactions,git,sqlite&perline=12" />
</p>

**Also built with**
<p>
  <img src="https://skillicons.dev/icons?i=rust,go,cpp,c,cs,kotlin,swift,scala,dart,flutter,r,ruby,php,matlab,js&perline=15" />
</p>

## 🌟 Featured Projects

### ☁️ AI × Infrastructure as Code

<p align="center">
  <a href="https://github.com/saki-nya1539/iac-genie"><img src="https://github-readme-stats.vercel.app/api/pin/?username=saki-nya1539&repo=iac-genie&theme=tokyonight&hide_border=true" /></a>
  <a href="https://github.com/saki-nya1539/tf-review-bot"><img src="https://github-readme-stats.vercel.app/api/pin/?username=saki-nya1539&repo=tf-review-bot&theme=tokyonight&hide_border=true" /></a>
</p>

| Project | 概要 |
|---|---|
| [iac-genie](https://github.com/saki-nya1539/iac-genie) | 自然言語 → AWS Terraform。生成・検証・自己修正し、apply 前に必ず plan をレビュー |
| [cfn-genie](https://github.com/saki-nya1539/cfn-genie) | CloudFormation 版。cfn-lint / checkov で検証、デプロイは change set をレビューしてから |
| [cdk-genie](https://github.com/saki-nya1539/cdk-genie) | AWS CDK (TypeScript) 版。tsc / cdk synth / checkov で検証 |
| [bicep-genie](https://github.com/saki-nya1539/bicep-genie) | Azure Bicep 版。az bicep build / checkov で検証、what-if レビューつき |
| [tf-review-bot](https://github.com/saki-nya1539/tf-review-bot) | Terraform の PR を Claude + checkov で自動レビューする GitHub Action |

### 📈 Data & Dashboards

| Project | 概要 | Stack |
|---|---|---|
| [tepco-demand-forecast](https://github.com/saki-nya1539/tepco-demand-forecast) | 東京電力エリアの翌日24時間の電力需要予測。毎日予測・毎週再学習を自動化 | Python, scikit-learn, GitHub Actions |
| [pulseboard](https://github.com/saki-nya1539/pulseboard) | 複数アプリの売上・LTVを可視化し、AIがグラフの傾向を解説するマーケティング分析ダッシュボード | Next.js, TypeScript, Tailwind |
| [taxbridge](https://github.com/saki-nya1539/taxbridge) | 銀行・カードの取引を自動で仕訳し、青色申告スタイルで集計する個人事業主向けアプリ | Next.js, TypeScript, Tailwind |
| [sentinelpay](https://github.com/saki-nya1539/sentinelpay) | アプリ内購入の不正利用を統計的に検知し、重大度つきでアラートを出す | React (Vite), Hono |

### 🧩 外部ライブラリなしで作ったもの

| Project | 概要 | Lang |
|---|---|---|
| [greprust](https://github.com/saki-nya1539/greprust) | 正規表現エンジンから自作した grep | Rust |
| [cpp-nbody](https://github.com/saki-nya1539/cpp-nbody) | N体シミュレーション（直接法 vs Barnes-Hut 法、ケプラーの法則で検証） | C++17 |
| [pixelforge](https://github.com/saki-nya1539/pixelforge) | BMP画像のフィルタ処理（ぼかし・エッジ検出など） | C |
| [shortgo](https://github.com/saki-nya1539/shortgo) | 標準ライブラリだけで作ったURL短縮APIサーバー | Go |

<details>
<summary>📂 その他のプロジェクト（クリックで開く）</summary>

| Project | 概要 | Lang |
|---|---|---|
| [diskprism](https://github.com/saki-nya1539/diskprism) | 重複ファイルの検出と容量のツリーマップ表示 | C# |
| [signallab](https://github.com/saki-nya1539/signallab) | 信号処理GUI（時間領域／周波数領域の表示、フィルタ） | MATLAB |
| [climater](https://github.com/saki-nya1539/climater) | 気温データのアノマリー・トレンドを分析するCLI | R |
| [flashcarddart](https://github.com/saki-nya1539/flashcarddart) | 間隔反復で学ぶフラッシュカードアプリ | Flutter |
| [budgetscala](https://github.com/saki-nya1539/budgetscala) | JDK標準の HttpServer だけで作った家計簿Webアプリ | Scala |
| [paymiru](https://github.com/saki-nya1539/paymiru) | アプリ内課金の購入履歴を可視化 | Next.js |
| [shooting-game](https://github.com/saki-nya1539/shooting-game) | ブラウザで遊べるシューティングゲーム | JavaScript |

</details>

## 📊 GitHub Stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=saki-nya1539&show_icons=true&hide_border=true&count_private=true&bg_color=FFFBF5&title_color=FF8C69&icon_color=3FBF9F&text_color=5A6B64&border_radius=12" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=saki-nya1539&layout=compact&hide_border=true&langs_count=10&bg_color=FFFBF5&title_color=FF8C69&text_color=5A6B64&border_radius=12" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=saki-nya1539&hide_border=true&border_radius=12&background=FFFBF5&ring=FF8C69&fire=3FBF9F&currStreakNum=FF8C69&sideNums=3FBF9F&currStreakLabel=FF8C69&sideLabels=5A6B64&dates=8FA39A&stroke=FFE0D0" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=saki-nya1539&hide_border=true&area=true&bg_color=FFFBF5&color=5A6B64&line=FF8C69&point=3FBF9F&area_color=FFD3B4&title_color=FF8C69&radius=12" width="100%" />
</div>


<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFAAA7,50:D5ECC2,100:98DDCA&height=120&section=footer" width="100%" />
