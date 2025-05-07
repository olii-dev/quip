---
description: Having issues? This page will be able to help.
---

# ❗ Errors

### Errors & How to Fix Them

{% tabs %}
{% tab title="Authentication Failed" %}
**Error Message:**

`authentication failed. please check your api key.`

**What It Means:**

This error occurs when the API key provided is invalid or missing.

**How to Fix:**

1. Go to the **Settings** page.
2. Ensure you have entered a valid API key.
3. If you don’t have an API key, follow the steps in the **How to Get an API Key** section in the settings.
{% endtab %}

{% tab title="Rate Limit Exceeded" %}
**Error Message:**

`rate limit exceeded. please wait before sending more requests.`

**What It Means:**

You have exceeded the allowed number of requests to the API within a specific time frame.

**How to Fix:**

1. Wait for a few minutes before trying again.
2. If this happens frequently, consider switching to a different AI model or contacting OpenRouter for higher rate limits.
{% endtab %}

{% tab title="Server Error" %}
**Error Message:**

`server error: <status code> - <status text>`

**What It Means:**

The server encountered an issue while processing your request. This could be due to temporary server downtime or an internal error.

**How to Fix:**

1. Wait a few minutes and try again.
2. If the issue persists, check [OpenRouters status page](https://status.openrouter.ai/) for updates.
3. Consider switching to a different AI model if the issue is specific to one model.
{% endtab %}

{% tab title="Endpoint Not Found" %}
**Error Message:**

`endpoint not found. please check the api url.`

**What It Means:**

The API endpoint being used is incorrect or no longer exists.

**How to Fix:**

1. Verify that the API URL in the code is correct.
2. If you are unsure, refer to the API documentation for the correct endpoint.
{% endtab %}

{% tab title="Unexpected Error" %}
**Error Message:**

`unexpected error: <status code> - <status text>`

**What It Means:**

An error occurred that does not fall into any predefined category. This could be due to an unhandled status code or an unexpected server response.

**How to Fix:**

1. Try clearing your chat history and contacting the AI again.
2. If the issue persists, switch to a different AI model.
3. Contact support with the error details for further assistance.
{% endtab %}

{% tab title="Unknown Error" %}
**Error Message:**

`an unknown error occurred. please contact support if the issue persists.`

**What It Means:**

An error occurred that could not be identified or categorized.

**How to Fix:**

1. Ensure your API key and settings are correct.
2. Try switching to a different AI model.
3. If the issue persists, contact support with the error details.
{% endtab %}
{% endtabs %}
