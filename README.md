# ヘルパーステーション欅 シフト表

## GitHub Pages で公開する手順

### 1. GitHubにリポジトリを作る
1. https://github.com にログイン
2. 右上「+」→「New repository」
3. Repository name: `shift-board`（任意）
4. **Public** を選択 → 「Create repository」

### 2. ファイルをアップロード
1. リポジトリページで「Add file」→「Upload files」
2. `index.html` と `README.md` をドラッグ＆ドロップ
3. 「Commit changes」を押す

### 3. GitHub Pages を有効にする
1. リポジトリの「Settings」タブ
2. 左メニュー「Pages」
3. Source:「Deploy from a branch」→ Branch:`main` / `/(root)` → 「Save」
4. 数分後に以下のURLでアクセス可能
   → `https://あなたのユーザー名.github.io/shift-board/`

---

## データ保存について
- シフトデータはブラウザの **localStorage** に自動保存されます
- 同じブラウザ・同じURLでアクセスすればデータは残ります
- 異なる端末間での共有はできません

## 主な機能
- シフト表（月表示・週表示）
- 週間ガントチャート
- 希望休管理
- シフト種別のカスタマイズ（追加・編集・削除）
- 個人制約設定（勤務日数・時間・連続勤務・曜日制限）
- 制約ベース自動生成
- CSV出力 / プレビュー印刷
- スタッフ枠・事務職枠の独立管理
