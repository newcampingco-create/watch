# Repository instructions

This repository contains the `watch` skill. Read `SKILL.md` before processing media.

For an attached local audio file, run:

```bash
python3 scripts/setup.py --json
python3 scripts/watch.py "<absolute-file-path>" --detail transcript --whisper groq
```

For video, follow the full workflow in `SKILL.md` and inspect the generated frames.

Never print, echo, log, or commit `GROQ_API_KEY`. Use the environment variable configured in the Codex environment. Summarize the transcript in Persian unless the user requests another language.
