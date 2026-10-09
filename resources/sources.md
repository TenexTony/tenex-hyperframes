# Sources and feature notes

Reviewed October 9, 2026. These prompts are suggested starting points. No video was generated to test them while preparing this pack.

## Model and supplied material

- [Muse Personal Agent Starter Kit](https://github.com/tenex-labs/muse-personal-agent-start-kit): short README, numbered first steps, separate guides, practical prompt pages, source notes, and a Tenex footer. Its public file tree did not include a LICENSE file when checked.
- Anthony's supplied kickoff and source prompts: the original ten prompt ideas and his recorded desktop setup and usage observations. New prompts 10–16 are original reusable examples, not reconstructions of his exact build prompts.
- [Ultrathink signup](https://www.tenex.co/ultrathink): working newsletter signup page, also linked by the Muse kit.

## Official references

| Source | What it supports |
| --- | --- |
| [Studio downloads](https://www.hyperframes.dev/studio) | Mac and Linux desktop downloads, including AppImage and `.deb`; Windows listed as coming soon. |
| [HyperFrames introduction](https://hyperframes.heygen.com/introduction) | Agent-built editable projects and rendering from the same project. |
| [Quickstart](https://hyperframes.heygen.com/quickstart) | Free open-source framework; local rendering does not use HeyGen credits; AI and optional services can have costs. |
| [Work on a project in Studio](https://hyperframes.heygen.com/studio) | Visual editing, timeline edits, agent handoff, preview, and rendering. This page describes the framework's Studio surface, not the full desktop onboarding flow. |
| [HyperFrames repository](https://github.com/heygen-com/hyperframes) | Charts, PDF-to-video, website videos, graphics, audio, captions, and supported animation approaches including 3D. |
| [Captions and talking-head footage](https://hyperframes.heygen.com/guides/captions-and-recuts) | Captions and graphic overlays; pause removal and speech reordering need a broader video-edit workflow. |
| [Voice, music, sound, and captions](https://hyperframes.heygen.com/guides/voice-and-audio) | Transcription, corrected captions, audio layers, speech-led timing, and mixing. |
| [Media effects](https://hyperframes.heygen.com/guides/media-effects) | Effects on images and video; grain and vignette are identified under color grading. |
| [Finish and share](https://hyperframes.heygen.com/guides/export-and-share) | Preview, project checks, Studio or agent export, and review of the rendered file. Creation workflows normally ask for render approval. |
| [Claude Code setup](https://code.claude.com/docs/en/setup) | Mac/Linux native installer and starting `claude`. |
| [Codex CLI setup](https://learn.chatgpt.com/docs/codex/cli) | Mac/Linux standalone installer and starting `codex`. |

The Claude Code and Codex fallback commands match the current documentation. They were checked, not executed.

## Limits and unresolved details

- The public framework documentation does not confirm every desktop app feature. The download page confirms platforms, not the whole sign-in and provider-connection flow.
- **TODO (Anthony): confirm current desktop sign-in and HeyGen account requirements.**
- **TODO (Anthony): confirm the guided Claude installer, Codex setup, and “Check again” label.**
- **TODO (Anthony): confirm Grok support, account requirements, and setup.**
- **TODO (Anthony): confirm the drawing/annotation tool and how to open it.**
- **TODO (Anthony): confirm `@` project references and how they reuse assets or styles.**
- Access to websites, spreadsheets, media search, transcription, and generated audio depends on the connected AI and installed tools. Each relevant prompt offers an attachment or clearly marked placeholder fallback. No universal one-click result is promised.
- A presentation workflow can produce an interactive deck. The slide prompts here explicitly ask for an MP4 video instead.
- The unattended prompt expresses approval for a local draft. It cannot remove an app's permission requests or guarantee that every installed workflow runs without stopping.
- The blog link supplied for this pack returned HTTP 404: **TODO (Anthony): publish or confirm https://tenex.co/blog/hyperframes-studio-guide.**

This is an independent Tenex resource, not official HeyGen documentation.
