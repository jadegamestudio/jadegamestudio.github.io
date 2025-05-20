**Privacy Policy & Data Handling Statement for VisaOne Gmail Responder (Personal Use)**

**Effective Date:** [20-May-2025]

This document outlines how "VisaOne Gmail Responder" (referred to as "the App" or "the Script"), a Python application developed and used solely by Charles Agaton (referred to as "I," "me," "my"), accesses, uses, stores, and handles data from my own Google Gmail account.

This statement is primarily for personal record-keeping and to ensure compliance with the Google API Services User Data Policy.

**1. Purpose of the App**

VisaOne Gmail Responder is a Python application I created and run for my personal use. Its sole purpose is to:
*   Access my Gmail inbox.
*   Read incoming emails.
*   Analyze the content of these emails.
*   Automatically generate and send replies from my Gmail account based on predefined logic and the content of the received emails.
The App is authorized by me to access my own Gmail account to automate email responses and improve my personal productivity.

**2. Information Accessed**

When I authorize the App, it accesses the following information from my Gmail account:

*   **My Gmail Account Information:** My email address and Google OAuth 2.0 authentication tokens. These tokens are stored locally on my personal computer/server where the script runs, solely to maintain an active session and avoid manual re-authentication.
*   **My Email Content:**
    *   **Incoming Emails:** Subject lines, sender addresses, recipient addresses, email bodies, and attachments of emails received in my Gmail inbox. This access is solely for the purpose of analyzing the email content to determine and generate an appropriate reply.
    *   **Outgoing Emails:** The content of replies generated and sent by the App on my behalf from my Gmail account.
*   **Metadata:** Timestamps and other metadata associated with my emails, as necessary for processing.

**3. How My Information is Used**

The information accessed is used exclusively for the following purposes:

*   **To Operate the App for My Benefit:**
    *   To connect to my Gmail account.
    *   To read my incoming emails.
    *   To analyze the content of my emails to understand their context and determine an appropriate automated response.
    *   To compose and send replies to emails from my Gmail account as per the App's logic.
*   **Local Storage of Authentication Tokens:** To avoid repeated manual authentication, the OAuth 2.0 tokens are stored securely on the local system where the Script runs. I am responsible for the security of this local system.

**The App's use and transfer to any other app of information received from Google APIs will adhere to the Google API Services User Data Policy, including the Limited Use requirements.** This means:
*   The App will only use access to read, write, modify, or control Gmail message bodies (including attachments), metadata, headers, and settings to provide its intended email processing and replying functionality *for me*.
*   This Gmail data will **not** be transferred to others unless doing so is necessary for me to (a) provide or improve these features (e.g., if I integrate a new personal tool), (b) comply with applicable law, or (c) as part of a merger, acquisition, or sale of assets (though this is highly unlikely for a personal script).
*   The App does **not** use this Gmail data for serving advertisements.
*   As I am the sole operator and developer, I am the only human who might read this data during development, debugging, or normal operation of the Script on my own account. This access is inherent to my use and control of the Script for its intended purpose.

**4. Information Sharing**

Since this App is for my personal use only:

*   **No Sharing with Third Parties:** My email data processed by this App is not shared with any external third parties, other than Google itself as a necessary part of using the Gmail API.
*   **Google:** Information is inherently exchanged with Google's servers to use the Gmail API. This is governed by my agreement with Google and Google's Privacy Policy.

**5. Data Security**

I take reasonable measures to secure the App and the data it handles:

*   **OAuth 2.0:** The App uses Google's secure OAuth 2.0 protocol for authentication. My Gmail password is never stored or accessed by the App.
*   **Local Token Storage:** Authentication tokens are stored on my local machine/server. I am responsible for securing this environment.
*   **Limited Scope:** The App is designed to request only the permissions necessary for its functioning.

**6. Data Retention**

*   **Email Content:** The App processes email content in real-time (or near real-time) and does not store email bodies or attachments beyond the transient memory usage required for analysis and reply generation. The original emails remain in my Gmail account, subject to my Gmail settings.
*   **Authentication Tokens:** OAuth tokens are stored locally on my system until I de-authorize the App, delete the tokens manually, or the tokens expire/are revoked.
*   **Logs:** The script may generate local logs for debugging or operational monitoring. I am responsible for managing these logs.

**7. My Rights and Control**

As the sole user and operator:

*   **Full Control:** I have full control over the App's code, its operation, and the data it accesses.
*   **Revoke Access:** I can revoke the App's access to my Gmail account at any time through my Google account security settings ([https://myaccount.google.com/permissions](https://myaccount.google.com/permissions)). This will prevent the App from further accessing my Gmail data.
*   **Data Deletion:** I can delete any locally stored data (like authentication tokens or logs) at any time. Email data itself resides within my Gmail account.

**8. Changes to This Statement**

If I modify the App's functionality in a way that materially changes how it handles my data, I will update this statement accordingly for my records.

**9. Contact (Self-Reference)**

For any questions or clarifications regarding this App's data handling, I will refer to my own understanding and documentation of the script.

Developer & Sole User: Charles Agaton
Contact: charlesagaton@gmail.com
