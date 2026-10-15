# How to Get a Gemini API Key

[日本語版](gemini-api-key-guide.ja.md)

Find or create a key for the Gemini API in Google AI Studio. The key belongs to a Google Cloud project. Free-tier availability and pricing vary by model and project settings.

## Steps

1. Open the [Google AI Studio API keys page](https://aistudio.google.com/api-keys), sign in with your Google account, and accept the terms if prompted.
2. Under **Dashboard → API Keys**, check your keys and their projects. A default project and key may already have been created when you first used AI Studio.
3. If you need a new key, select **Create API key** and choose the project where you will use it. If an existing Google Cloud project is missing, import it first under **Dashboard → Projects → Import projects**.
4. Copy the key and enter it in your app's **Gemini API key** field or store it in a secure secret manager. Verify the connection in the app where you will use it.

## Before you use it

- Free-tier models and limits are restricted. If you need paid access, check [billing](https://ai.google.dev/gemini-api/docs/billing) through **Set up billing** for the relevant project. Follow the account-specific instructions for payment options and any required prepaid balance.
- Do not share the key in chats, emails, screenshots, or public repositories. Do not embed it directly in publicly accessible browser or mobile app code.
- If **Create API key** is unavailable, you may lack permission to create keys in that project. Ask the project administrator.

## Official references

- [Create and manage Gemini API keys](https://ai.google.dev/gemini-api/docs/api-key)
- [Gemini API billing and tiers](https://ai.google.dev/gemini-api/docs/billing)

Last checked: October 16, 2026. Interface labels may change.
