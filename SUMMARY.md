# Hebrew Speech Recognition on iPad: current maintenance context

Read this file, then SKILL.md, README.md and linked implementation/validation guides.

## Original project and preservation

Historical Hebrew dictation project by Nadav Merlis and Liora Neeman, supervised by Aaron Wetzler. Only description/credits/thumbnail were recovered; original recognizer, model, report, training data and source are missing. Preserve the archival spelling of Koby Kramer with its qualifier.

## Current work — 2026-11-17

The new browser interface supports RTL text editing, a newly written sample and UTF-8 export. Optional dictation uses the browser vendor speech service, not recovered research code; audio may be processed remotely by that vendor. Read-aloud is an additional system-voice feature. Live recognition, accuracy and actual iPad use remain untested.

Aaron requested concise natural README prose and a runnable demo in each Updated section. A real tools-disabled Claude review and follow-up inform the wording; factual suggestions are checked against source and records. The previous full README is preserved as PROJECT_RECORD.md. Existing updated-guide anchors remain available; lengthy implementation/recovery records are linked rather than repeated in the main README.

## Checks and maintenance

Preserve thumbnail and attribution; the thumbnail creator is unrecorded and no blanket license is added. Do not infer the original model, method, vocabulary or accuracy. Never present typed sample text as recognition output. Speech capture must start only on explicit request, with the vendor-service disclosure visible. Keep editing/export usable without microphone or installed Hebrew voice.

New static demonstration checks are in updated/demo/VALIDATION.json when present. Actual Chrome desktop/390-pixel interactions were checked; a narrow viewport is not a physical device. No hardware, live microphone/camera recognition or cross-browser coverage is added. Review and synchronize SUMMARY.md and SKILL.md before every commit. Keep private evidence, account details and machine paths outside the repository.
