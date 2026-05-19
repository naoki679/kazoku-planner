# 🏡 家族の教育・老後資金プランナー

教育費（4人分）と老後2,000万円目標を **ひとつの画面でリアルタイムにシミュレーション** できる家計プランナーアプリです。

## ✨ 主な機能

- 子ども4人分の教育資金（高校・大学）を個別に試算
- 国公立・私立、奨学金、多子補助金など細かく設定可能
- 老後2,000万円到達シミュレーション（グラフ表示）
- 教育費完了後の老後積立への自動振替シミュレーション
- 投資運用（オルカン等）ありなし比較
- **入力値はlocalStorageに自動保存**（ページを閉じても設定維持）
- スマホ対応・レスポンシブデザイン

## 🚀 公開URL

> デプロイ後にここにURLを記入

## 🛠 技術スタック

- HTML / CSS / Vanilla JavaScript（シングルファイル構成）
- [Chart.js 4.4.1](https://www.chartjs.org/) — グラフ描画
- localStorage — 設定の自動保存
- Vercel — ホスティング

## 📁 ファイル構成

```
/
├── index.html          ← メインアプリ（家計プランナーアプリ.html をリネーム）
├── vercel.json         ← Vercel 設定
├── .gitignore
└── README.md
```

## 💻 ローカルで動かす

ファイルをダブルクリックするだけでブラウザで開けます（サーバー不要）。

```bash
# または Live Server 等で
open index.html
```

## 🌐 Vercel へのデプロイ手順

1. このリポジトリを GitHub に push
2. [vercel.com](https://vercel.com) でアカウント作成
3. 「New Project」→ GitHub リポジトリを選択
4. そのまま「Deploy」ボタンを押すだけ

## 🗺 ロードマップ

| Phase | 内容 | 状態 |
|-------|------|------|
| Phase 1 | Vercel 公開 / localStorage 自動保存 / スマホ対応 | ✅ 完了 |
| Phase 2 | React / Next.js 化・スマホUX向上 | 🔜 予定 |
| Phase 3 | Supabase 会員機能（Google/Apple ログイン・クラウド保存） | 🔜 予定 |
| Phase 4 | Stripe 決済・月額課金・PDF販売・AI相談 | 🔜 予定 |

## 📄 ライセンス

Private — All rights reserved.
