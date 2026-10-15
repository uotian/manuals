# OpenAIのAPIキーを入手する方法

[English version](openai-api-key-guide.md)

OpenAI APIをアプリやプログラムから利用するためのキーを作成します。ChatGPTの有料プランとAPIの料金は別です。キーを取得するだけで利用料金が確定するわけではありませんが、APIを使用すると料金が発生する場合があります。

## 手順

1. [OpenAI PlatformのAPIキー画面](https://platform.openai.com/api-keys)を開き、OpenAIアカウントでログインします。
2. 複数の組織・プロジェクトがある場合は、キーを使いたいプロジェクトを選びます。プロジェクトのAPIキー画面が見つからなければ、設定から対象プロジェクトを開き、**API Keys**を選びます。
3. **Create new secret key**（新しいシークレットキーを作成）を押します。名前や対象プロジェクトを指定できる場合は、用途が分かるように設定します。
4. キーの権限を確認して作成します。必要な操作だけを許可したい場合は、**Restricted**（制限付き）を選びます。利用するAPIに必要な権限まで外さないようにしてください。
5. 表示されたキーをコピーし、利用するアプリの**OpenAI APIキー**欄、または安全なシークレット保管先に登録します。**キーの全文が表示されるのは作成時だけ**です。画面を閉じる前に登録を済ませてください。

## 利用前に確認すること

- APIの利用を始める前に、[APIの請求設定](https://platform.openai.com/settings/organization/billing/overview)で利用可能なクレジットや支払い設定を確認します。ChatGPT Plusなどの契約料金にAPI利用料は含まれません。
- APIキーをチャット、メール、スクリーンショット、公開リポジトリに載せないでください。ブラウザ用・モバイル用の公開コードに直接埋め込むことも避けます。
- キーを保存し忘れた場合は、既存のキーの全文を再表示せず、新しいキーを作成して利用先を更新します。古いキーを使っているアプリがないことを確認してから削除します。

## 公式情報

- [OpenAI APIキーの確認・作成](https://help.openai.com/en/articles/4936850-where-do-i-find-my-openai-api-key)
- [プロジェクトとAPIキーの管理](https://help.openai.com/ja-jp/articles/9186755-managing-projects-in-the-api-platform)
- [ChatGPTとAPIの請求の違い](https://help.openai.com/en/articles/9039756-managing-billing-for-chatgpt-and-the-api-platform)

最終確認：2026年10月16日。画面の表示名は変更される場合があります。
