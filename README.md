# star-wing-tournament
個人星の翼大会サイト
あなた（GitHub Copilot）は、近未来SF・メカアクションゲーム『星の翼』の雰囲気を持ったWebサイトを制作するUI/UXデザイナーおよびフロントエンドエンジニアです。

以下の配色ガイドラインおよび仕様に従って、Webサイトのデザインシステム（CSS変数/Tailwind設定）と基本CSSコンポーネントをコードで作成してください。

---

### 1. 配色デザインシステム（CSS Variables）
以下のカラーパレットを定義してください。

- **Background (Base):** `#0B0F19`（宇宙をイメージした濃紺）
- **Background (Surface/Card):** `#161F33`（パネル・カード用ネイビー）
- **Text (Primary):** `#FFFFFF`（見出し用純白）
- **Text (Secondary):** `#E2E8F0`（本文用オフホワイト）
- **Text (Muted):** `#94A3B8`（補足・注釈用グレー）
- **Accent Primary (Cyan Neon):** `#00F0FF`（SFエネルギー・主要アクセント）
- **Accent Secondary (Magenta):** `#FF007A`（対戦・熱量を表すCTAアクセント）
- **Accent Purple:** `#7000FF`（グラデーション用パープル）
- **Border / Line:** `#1E293B`（セクション区切り用）

---

### 2. スタイル仕様（SF / サイバーUIエフェクト）
- **Glow Effect (発光):** Accent Primary (`#00F0FF`) や Magenta (`#FF007A`) を使ったネオン風のグロー効果（`box-shadow`, `text-shadow`）。
- **Gradient:** シアンからパープル (`#00F0FF` -> `#7000FF`) への45度グラデーション。
- **Grid / Scanline:** 微かなサイバー風背景グリッド。

---

### 3. 出力してほしい成果物
1. **`variables.css` または `globals.css`**
   - 上記の配色とグローエフェクト用のCSS変数を定義したルート設定コード。
2. **ボタンコンポーネント (CSSまたはTailwind)**
   - ネオン発光効果（ホバー時に光る）付きのプライマリボタン（Cyan）およびCTAボタン（Magenta）。
3. **カードコンポーネント (CSSまたはTailwind)**
   - 背景 `#161F33` で、枠線にうっすら光るエフェクトが付いたキャラクター・ニュース掲載用カード。

上記コードを記述し、簡単な使用例（HTML構造）も提示してください。