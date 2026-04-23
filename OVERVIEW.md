# Overview

A reverse-engineered Python client for Google Bard's chatbot API. Authentication is done by supplying the `__Secure-1PSID` and `__Secure-1PSIDTS` cookies from an active bard.google.com session. It exposes synchronous (`Chatbot`) and asynchronous (`AsyncChatbot`) APIs, plus a CLI and a "quick mode" driven by environment variables for shell shortcuts.
