# Rightbrain API Collection

[<img src="https://fetch.usebruno.com/button.svg" alt="Fetch in Bruno" style="width: 130px; height: 30px;" width="128" height="32">](https://fetch.usebruno.com?url=git%40github.com%3ARightbrainAI%2Fbruno.git "target=_blank rel=noopener noreferrer")

This repository contains a [Bruno](https://www.usebruno.com/) collection for interacting with the [Rightbrain API](https://docs.rightbrain.ai/) API. [Rightbrain](https://rightbrain.ai/) allows you to build and deploy LLM features rapidly by turning prompts into production-ready APIs.

## Getting Started

Follow these steps to get the collection running, whether you cloned the repository or used the "Fetch in Bruno" button.

**Step 1: Install Bruno**

*   If you haven't already, download and install the Bruno API client from [www.usebruno.com](https://www.usebruno.com/).

**Step 2: Load the Collection**

*   **Using Fetch Button:** Clicking the "Fetch in Bruno" button above should automatically load the collection into Bruno.
*   **Cloning Repository:** If you cloned the repository, open Bruno, click "Open Collection", and select the folder where you cloned it.

**Step 3: Configure Environment Variables (⚠️ Mandatory)**

This is a crucial step required for **all users**, including those who used the Fetch button.

1.  **Locate `.env.example`:** Find this file within the collection folder.
    *   *If Cloned:* It will be in the root directory you cloned.
    *   *If Fetched:* Check the "Env & Vars" tab for the collection within Bruno.
2.  **Create `.env`:** Make a copy of `.env.example` and rename the copy to `.env`.
3.  **Add Credentials:** Open the `.env` file and fill in your Rightbrain API credentials:
    *   New users: You can get these when [onboarding to Rightbrain](https://app.rightbrain.ai/).
    *   Existing users: Go to the [API Client section](https://app.rblocal.dev/preferences?tab=api-clients) in your Rightbrain dashboard, select or create a Client Credentials API client, and click "Copy all" to get the necessary values.

**Step 4: Run Requests!**

*   Select the `Dynamic` environment in the top-right dropdown in Bruno.
*   Choose a request from the collection panel on the left.
*   Click "Send".

## Contributing

Contributions, issues, and feature requests are welcome!

## Resources

*   [Rightbrain Website](https://rightbrain.ai/)
*   [Rightbrain App](https://app.rightbrain.ai/)
*   [Rightbrain API Documentation](https://docs.rightbrain.ai/)
*   [Bruno Documentation](https://docs.usebruno.com/)

## Exporting Collection

Bruno allows you to export this collection for use in other tools or formats:

*   **Postman:** You can export the collection to a Postman format.
*   **OpenAPI:** Export to OpenAPI v3 specification.
*   **Curl:** Generate curl commands for individual requests.

Refer to the [Bruno Export Documentation](https://docs.usebruno.com/exporting-collections) for detailed instructions on how to export.
