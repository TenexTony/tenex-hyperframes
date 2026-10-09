# Pack handoff

Prepared October 9, 2026. Includes 17 prompt files and two podcast follow-up snippets.

Local folder: `tenex-hyperframes` inside the video workspace.

Repository: [TenexTony/tenex-hyperframes](https://github.com/TenexTony/tenex-hyperframes). Created as private. Matt handles beehiiv delivery.

## Files

| File | Contents |
| --- | --- |
| [README.md](../README.md) | Beginner introduction, requirements, steps, every prompt, learning links, and Tenex footer. |
| [.gitignore](../.gitignore) | Excludes common private inputs, credentials, and generated media. |
| [LICENSE](../LICENSE) | Pending-license note; replace after choosing a license. |
| [CONTRIBUTING.md](../CONTRIBUTING.md) | Plain-language editing and source-checking guidance. |
| [guides/setup.md](../guides/setup.md) | Desktop download, AI connection, checked fallback commands, and troubleshooting. |
| [guides/tips.md](../guides/tips.md) | Planning, brand direction, visual fixes, footage, reasoning, reuse, and export review. |
| [prompts/00-work-unattended.md](../prompts/00-work-unattended.md) | Optional instruction for a local draft while the reader is away. |
| [prompts/01-ai-clip-to-social-post.md](../prompts/01-ai-clip-to-social-post.md) | Image or clip to a 20-second vertical post. |
| [prompts/02-spreadsheet-to-chart.md](../prompts/02-spreadsheet-to-chart.md) | CSV to a 15-second animated chart. |
| [prompts/03-slides-to-explainer.md](../prompts/03-slides-to-explainer.md) | PDF slides to a 60-second widescreen explanation. |
| [prompts/04-blog-post-to-teaser.md](../prompts/04-blog-post-to-teaser.md) | Blog post to a 30-second vertical announcement. |
| [prompts/05-testimonial-card.md](../prompts/05-testimonial-card.md) | Approved customer quote to a 12-second square card. |
| [prompts/06-event-promo.md](../prompts/06-event-promo.md) | Event brief to a 15-second vertical announcement. |
| [prompts/07-fix-generic-ai-video.md](../prompts/07-fix-generic-ai-video.md) | Brand revision of an existing launch project. |
| [prompts/08-talking-head-edit.md](../prompts/08-talking-head-edit.md) | Captions and graphics over a 30-second phone video. |
| [prompts/09-make-it-feel-3d.md](../prompts/09-make-it-feel-3d.md) | Depth treatment without changing the existing edit's timing. |
| [prompts/10-product-launch.md](../prompts/10-product-launch.md) | Website and real product assets to a 30-second launch video. |
| [prompts/11-spreadsheet-to-slideshow.md](../prompts/11-spreadsheet-to-slideshow.md) | Excel or CSV findings to a 45-second update. |
| [prompts/12-blog-post-to-infographic.md](../prompts/12-blog-post-to-infographic.md) | Blog ideas to a 45-second animated explanation. |
| [prompts/13-newsletter-page-to-ad.md](../prompts/13-newsletter-page-to-ad.md) | Newsletter page to a 20-second signup ad. |
| [prompts/14-webinar-page-to-promo.md](../prompts/14-webinar-page-to-promo.md) | Event page to a 30-second live-event or replay promo. |
| [prompts/15-podcast-edit.md](../prompts/15-podcast-edit.md) | Main podcast edit prompt plus two separate refinement prompts. |
| [prompts/16-app-promo.md](../prompts/16-app-promo.md) | Real screenshots or recording to a 20-second app showcase. |
| [resources/sources.md](sources.md) | Official evidence, reviewed date, and unresolved desktop details. |
| [resources/launch-copy.md](launch-copy.md) | Signup box and five-sentence welcome email for Matt. |
| [resources/handoff.md](handoff.md) | File inventory, all outstanding tasks, and validation results. |

## All open Anthony tasks

Repeated TODO notes in the pack are grouped here by the decision or asset they need.

1. **License:** choose the license and replace the pending note in [LICENSE](../LICENSE). The model repo has no LICENSE file to match.
2. **Blog URL:** publish or confirm the supplied blog URL. It returned 404. Notes appear in [README](../README.md) and [sources](sources.md).
3. **Video URL:** add the live HyperFrames Studio video link in [README](../README.md).
4. **Desktop sign-in:** confirm the current screen and HeyGen account requirement in [sources](sources.md).
5. **AI connection flow:** confirm Studio's guided Claude installer, Codex steps, and “Check again” label in [sources](sources.md).
6. **Grok:** confirm support, account requirements, and setup before listing it as supported in [sources](sources.md).
7. **Drawing:** confirm the desktop annotation tool and how to open it in [sources](sources.md).
8. **Project references:** confirm `@` project references and their behavior in [sources](sources.md).
9. **Reader access:** the repo URL is filled in [launch copy](launch-copy.md). Make the repository accessible to subscribers before Matt sends the email.
10. **Campaign signup and email delivery:** have Matt confirm the campaign signup URL and connect delivery in beehiiv. The general Ultrathink signup URL works. See [launch copy](launch-copy.md).
11. **Example GIFs:** supply and insert a GIF from `hyperframes-blog-images` for each of the 17 prompt files listed above, 00 through 16. Each file has its own Example TODO.

These are reusable prompts. They should not be described as verbatim prompts from the recorded builds.

## Checks completed

- All 17 prompt files use the five requested sections. Each has one main copy-paste block; the podcast file also includes two separately copyable follow-ups.
- The README links to every prompt. Local file links and heading anchors resolve.
- Spelling was checked for Tenex and HyperFrames. Prompt files contain no Tenex-only colors, URLs, or product details.
- Text was scanned for common secret/key patterns, email addresses, and private filesystem paths. None were found. Review found no client names or private account details.
- Beginner instructions explain attachments, blanks, Terminal, preview approval, and MP4 export. They distinguish the desktop app from the fallback AI installers.
- Both supplied fallback install commands match current official docs. No installer was executed.
- All 16 distinct external Markdown links were checked. Fifteen returned HTTP 200, including redirects. The supplied blog URL returned 404 and is explicitly marked as a TODO.
- No actual HyperFrames video was generated to test these prompts. Capability claims were checked against the cited docs; uncertain desktop claims remain labeled.

The license note, missing links, app confirmations, and example GIFs remain for Anthony and Matt.

## Writing audit

- Removed the README slogan and repeated explanations of the drafting process.
- Replaced vague animation directions with slides, fades, zooms, and specific places for graphics.
- Shortened the setup guide and moved unconfirmed feature notes into sources.md.
- Corrected the spreadsheet slideshow to describe three findings plus opening and closing cards.
- Kept repeated export instructions where each copied prompt needs them.
- Checked all prompt timelines, required inputs, links, and placeholders after editing.
