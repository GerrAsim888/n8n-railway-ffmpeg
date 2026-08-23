# YAN Analytics GPT — Privacy Policy

**Last updated:** August 23, 2026

## Purpose

YAN Analytics GPT is a read-only analytics assistant that retrieves advertising statistics from the Yandex Advertising Network (YAN / РСЯ) Statistics API when the user requests an analysis.

## How the Action works

The GPT Action sends requests directly from ChatGPT to the official Yandex Partner API at `partner.yandex.ru`. The GPT creator does not operate an intermediary proxy or analytics server for these requests.

Authentication is configured as a secret in the GPT Action settings and is sent to Yandex in the `Authorization` request header. Users should not place OAuth tokens or other credentials in chat messages.

## Data processed

Depending on the user's request, the Action may process:

- requested reporting dates and report parameters;
- advertising statistics returned by Yandex, such as revenue, requests, impressions, viewability metrics, clicks, RPM/eCPM and related report fields;
- report groupings such as domain, page, ad block, device, browser, operating system or geography when requested and supported by the Yandex API.

## Data storage by the GPT creator

The GPT creator does not intentionally store YAN report responses, reporting history, or OAuth credentials in a separate database, snapshot store, proxy service, or analytics backend operated for this GPT.

Statistics are requested from Yandex on demand for the period needed to answer the user's current request.

## Third-party processing

Requests and responses are processed by OpenAI as part of ChatGPT and by Yandex as the provider of the Yandex Partner Statistics API. Their handling of data is governed by their respective terms and privacy policies.

- OpenAI Privacy Policy: https://openai.com/policies/privacy-policy/
- Yandex Privacy Policy: https://yandex.com/legal/confidential/

## Security

The Action is intended for read-only statistics access. The GPT does not require the user to disclose the Yandex OAuth token in conversation. Credentials should be configured only in the protected authentication settings of the GPT Action.

## Changes to this policy

This policy may be updated if the GPT's data flows or integrations change. The latest version will be published at this URL.

## Contact

Questions about this GPT or this policy can be submitted through the GitHub profile of the GPT creator:

https://github.com/GerrAsim888
