# GeminiのAPIキーを入手する方法

[English version](gemini-api-key-guide.md)

Gemini APIをアプリやプログラムから利用するためのキーを、Google AI Studioで確認・作成します。キーはGoogle Cloudプロジェクトにひも付きます。利用できる無料枠や料金はモデルとプロジェクトの設定によって異なります。

## 手順

1. [Google AI StudioのAPIキー画面](https://aistudio.google.com/api-keys)を開き、Googleアカウントでログインして、必要なら利用規約に同意します。
2. **Dashboard → API Keys**でキーと対象プロジェクトを確認します。初めて利用するアカウントでは、既定のプロジェクトとキーが自動作成される場合があります。
3. 新しいキーが必要なら、**Create API key**（APIキーを作成）を押し、使用するプロジェクトを選んで作成します。既存のGoogle Cloudプロジェクトが表示されない場合は、**Dashboard → Projects → Import projects**から先にインポートします。
4. 作成・表示されたキーをコピーし、利用するアプリの**Gemini APIキー**欄、または安全なシークレット保管先に登録します。利用先で接続を確認してください。

## 利用前に確認すること

- 無料枠で使えるモデルや上限は限られます。有料枠が必要なときだけ、対象プロジェクトの**Set up billing**から[課金設定](https://ai.google.dev/gemini-api/docs/billing?hl=ja)を確認します。支払い方式や前払い残高の要否はアカウントの案内に従ってください。
- APIキーをチャット、メール、スクリーンショット、公開リポジトリに載せないでください。ブラウザ用・モバイル用の公開コードに直接埋め込むことも避けます。
- **Create API key**が押せない場合は、対象プロジェクトでキーを作る権限が不足している可能性があります。プロジェクト管理者に確認してください。

## 公式情報

- [Gemini APIキーの作成と管理](https://ai.google.dev/gemini-api/docs/api-key?hl=ja)
- [Gemini APIの課金と利用枠](https://ai.google.dev/gemini-api/docs/billing?hl=ja)

最終確認：2026年10月16日。画面の表示名は変更される場合があります。
