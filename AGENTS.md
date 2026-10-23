# English readings workflow

## Scope and authorization

- This repository stores Victor’s English reading articles and concise Chinese close-reading notes.
- The user has authorized committing the two existing completed readings and all future completed reading Markdown files directly to `main`, without asking again for routine confirmation.
- Here, publishing means committing Markdown to this repository. Do not create a website, enable GitHub Pages, change repository visibility, or modify unrelated repositories.

## Article workflow

- Select recent articles from The Economist, The New Yorker, and The Atlantic. Rotate publications and issue dates, favor politics and public policy, and aim for B2+ with some C1 vocabulary.
- First provide the verified publication, issue, title, and source links. Wait for the user’s TXT before preparing the full reading Markdown.
- Check the supplied TXT against a verified complete source for missing, repeated, or truncated paragraphs. If no full comparison source is available, say the check is preliminary. Do not invent missing text.
- Preserve the supplied article wording and relevant subtitle; remove subscription prompts and other webpage clutter. Do not treat a third-party archive’s license as a license for magazine content.
- Use the concise format of `election-games.md`: title; one line for publication, author when known, and issue; original article; short main idea and argument order; 5–8 useful vocabulary items in a table; two brief syntax explanations; exactly five self-check questions without answers.
- Keep processing notes, completeness reports, learning instructions, and other extra commentary out of the article file. Report the completeness check briefly in chat.

## GitHub synchronization

- Whenever a requested reading Markdown is completed or revised, actually commit it to this repository’s `main` branch and verify the resulting file. Do not merely promise an upload.
- Use lowercase English filenames with hyphens at repository root, following `election-games.md` and `tote-bags.md`. Reuse an existing path for the same article. Add files to the README table without duplicate entries or unrelated rewrites.
- Read the latest branch and affected files before writes. Preserve user edits and unrelated content. Use the current blob SHA when replacing an existing file; resolve conflicts against the latest contents and never force push.
- Submit only finished reading Markdown, relevant assets if any, and the README update. Do not commit raw TXT, temporary files, credentials, private source identifiers, or chat-only citation markup.
- If existing completed readings have not yet been synchronized, add the missing finished files; recommendations without completed Markdown are not finished readings.
- Verify actual GitHub contents after a successful write and reply briefly with links. If a connection or write fails, state what remains incomplete and do not claim it succeeded.
