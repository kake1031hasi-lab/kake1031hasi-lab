### Hi there 👋 I'm a PT & Data Scientist in Ph.D. course.

**「臨床(Real)」×「データ(Digital)」の架け橋となるプロジェクトマネージャー / 研究者**

臨床経験14年以上の理学療法士としてのドメイン知識と、データサイエンス・生成AIの実装力を武器に、医療現場の課題解決（Medical DX）に取り組んでいます。
また、**1,000名規模の医療グループにおける教育統括・共同研究プロジェクト**をリードし、組織横断的なマネジメントに従事しています。

- 🏥 **Current Work:** 医療法人社団 南淡路病院（グループ学術・教育統括 施設代表 / 臨床研究支援）
- 🎓 **Education:** 神戸大学大学院 保健学研究科 博士後期課程 (D1) / 東京大学GCI修了
- 🏆 **Awards:** 東京大学GCI 2024 Winter コミュニティ貢献賞

## 🛠️ Tech Stack & Skills
* **Languages**: Python, JavaScript, SQL (SQLite)
* **Frameworks/Libraries**: Streamlit, React (Basic), Tailwind CSS, watchdog, python-docx, matplotlib / seaborn
* **Cloud/DB**: Google Cloud Platform (Gemini API), Firebase (Firestore), Google Sheets API, Elasticsearch
* **Analysis**: GLMM (R/Python), Interrupted Time Series Analysis (ITS), **時系列軌跡解析 (Jerk / Speed Peaks)**
* **Management**: Large-scale Education Planning (1000+ PTs), Multi-center Clinical Research

---

## 🚀 Key Projects

### 1. AWA-LINK (ex. Shichifuku)
**慢性期リハビリテーション教育支援AIシステム**
* **Overview**: 教育心理学（Scaffolding）に基づき、新人の臨床推論を支援する生成AIメンター。
* **Tech**: Python, Streamlit, Gemini API, Gspread
* **Highlight**: 通信遮断時のローカルログ保存（Hybrid Logging）と、動的なデータ管理機能。

### 2. Mental Symptom Monitor (MVP)
**精神症状モニタリング・予兆検知システム**
* **Overview**: 精神症状の時系列可視化と、ベースライン比較による再発予兆検知。
* **Tech**: Firebase (Firestore/Auth), Chart.js, Vanilla JS
* **Highlight**: リアルタイム同期と臨床的意思決定支援（CDS）ロジックの実装。

### 3. Wellness Check (PoC)
**高齢者・精神科施設向け体調管理UI**
* **Overview**: デジタルデバイドに配慮したアクセシビリティ重視の入力インターフェース。
* **Tech**: HTML5, Tailwind CSS

### 4. AWAKEN Cognitive Performance Tracker (MVP)
**eスポーツ認知パフォーマンス解析・可視化システム**
* **Overview**: PsychoPy認知テストのリアルタイム自動監視・インジェストから、500Hz軌跡データを用いた数理統計・特徴量解析、およびGeminiによるA2UI（ゲーマー向けAIレポート）の自動生成までを行う統合解析システム。
* **Tech**: Python (watchdog/pandas/numpy), SQLite / Elasticsearch, Gemini API (gemini-1.5-flash), python-docx
* **Highlight**: 500Hz高解像度軌跡データからの躍度（Jerk）や速度微調整回数（Speed Peaks）算出による操作性の定量化、オープン気象APIを用いた環境分析、およびMarkdownからWord（.docx）への自動レイアウト変換。
```
