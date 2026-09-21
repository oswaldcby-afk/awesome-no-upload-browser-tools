# Contribution Guidelines

Thanks for helping improve Awesome No-Upload Browser Tools.

The goal is curation, not exhaustiveness. A tool should be genuinely useful and should fit the local-processing scope clearly.

## Before You Submit

Please check that the tool:

- Performs the core listed task locally in the browser or on the user's device.
- Does not require uploading the user's file or pasted content to the application's server for the core listed task.
- Is usable without creating an account for the core listed task.
- Is currently accessible, maintained, and functional in a modern browser.
- Has a clear public explanation of its local/client-side processing, or has inspectable open-source code that makes the architecture reasonably verifiable.
- Offers enough quality, usefulness, polish, or uniqueness to justify inclusion instead of being one more near-identical clone.

A site may still load JavaScript, WebAssembly, models, fonts, analytics, or other assets over the network. Optional features may also make external requests. If so, the description should not imply that the entire site is offline or network-free.

## Self-Promotion

Self-submissions are allowed, but please disclose your connection to the project in the pull request or issue.

Maintainers and contributors are held to the same standard. A project should not be included simply because its creator contributes to this repository.

## How to Add a Tool

1. Check the existing list and open pull requests for duplicates.
2. Add the tool to the most specific category in `readme.md`.
3. Keep entries in alphabetical order within the category.
4. Use this format:

```markdown
- [Tool Name](https://example.com/) - One concise sentence explaining what it does and why it fits the local-processing scope.
```

5. End the description with a period.
6. Keep the description factual. Avoid marketing claims such as "best," "revolutionary," or "ultimate."
7. In the pull request, include a link to the tool's privacy/local-processing documentation or source code.

## What Usually Does Not Belong

- Tools whose main workflow uploads files to a server.
- Free trials that require an account or payment details for the core function.
- Thin clones with no meaningful advantage over existing entries.
- Abandoned, broken, or archived projects.
- Download-only desktop or mobile apps with no usable browser version.
- Directories that mainly link to other server-side tools without offering meaningful browser-local functionality themselves.
- Products whose local-processing claim cannot be reasonably verified.

## Updating or Removing Entries

Please open an issue or pull request if a listed tool:

- Starts uploading files for a workflow previously handled locally.
- Adds an account wall to the core listed function.
- Goes offline or becomes unmaintained.
- Changes ownership or behavior in a way that makes the description inaccurate.

Privacy and product behavior change over time, so removal is a normal part of maintaining this list.
