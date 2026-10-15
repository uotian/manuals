# How to Get an OpenAI API Key

[日本語版](openai-api-key-guide.ja.md)

Create a key to use the OpenAI API from an app or program. ChatGPT subscriptions and API billing are separate. Creating a key does not by itself incur usage charges, but using the API may.

## Steps

1. Open the [OpenAI Platform API keys page](https://platform.openai.com/api-keys) and sign in to your OpenAI account.
2. If you have multiple organizations or projects, select the project where you will use the key. If you cannot find its API keys page, open the project in Settings and select **API Keys**.
3. Select **Create new secret key**. If prompted for a name or project, choose values that make the key's purpose clear.
4. Review the key's permissions before creating it. Choose **Restricted** if you want to allow only the operations you need, but make sure the API you plan to use still has the required permissions.
5. Copy the key and enter it in your app's **OpenAI API key** field or store it in a secure secret manager. **The full key is shown only when you create it**, so save it before closing the dialog.

## Before you use it

- Before using the API, check your available credits and payment settings in [API billing settings](https://platform.openai.com/settings/organization/billing/overview). ChatGPT Plus and other ChatGPT subscriptions do not include API usage.
- Do not share the key in chats, emails, screenshots, or public repositories. Do not embed it directly in publicly accessible browser or mobile app code.
- If you did not save the key, create a new one and update the places that use it; you cannot display the full existing key again. Delete the old key only after checking that no app still depends on it.

## Official references

- [Find or create an OpenAI API key](https://help.openai.com/en/articles/4936850-where-do-i-find-my-openai-api-key)
- [Manage projects and API keys](https://help.openai.com/en/articles/9186755-managing-projects-in-the-api-platform)
- [How ChatGPT and API billing differ](https://help.openai.com/en/articles/9039756-managing-billing-for-chatgpt-and-the-api-platform)

Last checked: October 16, 2026. Interface labels may change.
