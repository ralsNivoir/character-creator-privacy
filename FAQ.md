# AI Usage FAQ

AI tools were used during the development of **5e Character Creator & Sheet**. This page explains where they were involved and, just as importantly, where they were not.

## Does the app itself use AI?

No. The app does not generate rules, character options, calculations, or descriptions while it is being used. Its core features run from regular Flutter code and a bundled rules database, while characters are stored locally on the user's device.

There is no AI account requirement, AI API, or connection to an AI service built into the app.

## How was AI used to make the app?

ChatGPT/Codex and Claude were used as development tools. They assisted with:

- planning features and data structures;
- writing and revising Dart, JSON, scripts, tests, and documentation;
- finding broken references, inconsistent formatting, encoding problems, and incomplete entries;
- comparing similar features and bringing them into a consistent format;
- troubleshooting Android, iOS, build, and release issues.

AI was useful for working through a large amount of repetitive code and game data, but it did not determine the direction of the project.

## Who made the final decisions?

The developer, Rammy Canales, decided what the app should include, how its systems should behave, UI design, database architecture and which suggestions or changes to accept. AI suggestions were often corrected, rewritten, or rejected when they did not fit the project.

## Was the rules database written by AI?

AI helped transcribe, reorganize, summarize, and audit parts of it. The database was also repeatedly compared with source material and manually reviewed.

It is a large database with many interacting rules, so mistakes are still possible. AI assistance and manual review reduce errors, but neither makes the app infallible.

## Is character data shared with an AI provider?

No. Character sheets, notes, images, backups, and exported character files are not sent to OpenAI, Anthropic, or another AI provider. They remain part of the app's local storage and user-controlled file features.

## Will the app add AI features later?

There are no runtime AI features in the current app. If that changes in a future version, the new feature and any effect on data handling or privacy will be documented.

## How can a mistake be reported?

Bugs, incorrect rules, incomplete mechanics, or other feedback can be sent to **5echaractercreator@gmail.com**.

Useful reports include the affected race, class, feature, feat, spell, item, or screen, along with what the app displayed and what was expected instead.
