# Contributing

This repository accepts documentation corrections, integration examples, and
reproducible bug reports for the public CLI and MCP interfaces.

Before opening a pull request:

1. Keep product behavior claims consistent with `commentscraper platforms` and
   the current Adlicio documentation.
2. Do not include account tokens, scraped personal data, browser profiles, or
   proprietary implementation code.
3. Keep the files under `skills/` concise and focused on reusable agent behavior.
4. Validate the skills, `server.json`, and the plugin manifests before submitting.
   Run `claude plugin validate .` for the plugin files.

The proprietary CLI implementation is maintained separately and is not open to
source-code contributions in this repository.
