# Polishr Privacy Policy

_Last updated: 16 May 2026_

Polishr is a Chrome extension that rewrites user-selected text into clearer, more professional language. This policy explains what data the extension handles, how it is transmitted, and what it is used for.

## What data we handle

When you invoke Polishr on a piece of selected text (via the right-click menu or the keyboard shortcut), the following data is sent to our backend:

- The text you have selected on the current webpage.
- Basic technical data from the request itself (IP address, user-agent), which is standard for any HTTPS request.

We do **not** collect, transmit, or store:

- Your name, email address, or any account information (Polishr does not have user accounts).
- The URL or content of pages you visit.
- Your browsing history.
- Clicks, scrolls, keystrokes, or any other behavioral data.
- Selected text from pages where you have not invoked Polishr.

## How data is used

The selected text you submit is sent over HTTPS to the Polishr backend at `https://polishr.duckdns.org`. The backend uses a large language model (LLM) to generate a polished rewrite, which is streamed back to the extension and displayed in a panel on the page.

The selected text is processed only to generate the rewrite. It is not used for advertising, sold to third parties, used to train models, or analyzed for any other purpose.

## Third-party processors

To generate the rewrite, the Polishr backend forwards the selected text to a third-party large language model provider: **Anthropic** (Claude API). The text is sent over an encrypted connection. Anthropic's data-handling commitments, including their commitment not to train on API inputs by default, are available at [https://www.anthropic.com/legal/privacy](https://www.anthropic.com/legal/privacy) and [https://privacy.anthropic.com](https://privacy.anthropic.com).

No other third parties receive your data.

## Data retention

The selected text is processed in memory and is not stored on our servers after the response is returned. Standard request logs (timestamp, IP address, response status) may be retained for up to 30 days for operational and security purposes, after which they are deleted.

## Your rights

Because Polishr does not have user accounts and does not retain submitted text, there is no stored personal data tied to you. If you have any questions or concerns, you can contact us at the address below.

## Contact

Email: **polishr.support@gmail.com**

## Changes to this policy

If this policy is updated, the "Last updated" date at the top of this page will change. Significant changes will be communicated via the extension's listing on the Chrome Web Store.
