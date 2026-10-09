# Get set up

Do this once. Then [pick a prompt](../README.md#pick-your-video).

## 1. Download HyperFrames Studio

Open the [official Studio download page](https://www.hyperframes.dev/studio).

- **Mac:** download the Mac installer and follow its instructions.
- **Linux:** download the AppImage or the `.deb` package for your system. For an AppImage, your file manager may ask you to allow the file to run as a program.

Windows is listed as coming soon.

## 2. Open Studio and sign in

Open the app. Follow its sign-in screen using your HeyGen account if requested.

## 3. Connect your AI

Choose the AI you want to use in Studio's setup screen.

- **Claude Code:** if Studio offers to install it, use that guided step. Then complete the AI sign-in it requests.
- **Codex:** if Studio shows install commands, copy them into Terminal and follow the instructions. Complete Codex sign-in, return to Studio, and click **Check again** if that button appears.

Terminal is the app where you paste install commands. On a Mac, open it through Spotlight by searching for “Terminal.” On Linux, open the Terminal app from your applications menu. Paste a command and press Enter. Read the result before pasting the next one.

## 4. If the guided setup does not work

These commands install Claude Code or Codex on **Mac or Linux**. Install only the one you chose. Studio is a separate download.

### Claude Code

Paste this into Terminal and press Enter:

```sh
curl -fsSL https://claude.ai/install.sh | bash
```

When it finishes, open a new Terminal window. Paste:

```sh
claude
```

Follow the sign-in instructions. See [Anthropic's official setup guide](https://code.claude.com/docs/en/setup) if the installation fails.

### Codex

Paste this into Terminal and press Enter:

```sh
curl -fsSL https://chatgpt.com/codex/install.sh | sh
```

When it finishes, open a new Terminal window. Paste:

```sh
codex
```

Follow the sign-in instructions. See the [official Codex CLI guide](https://learn.chatgpt.com/docs/codex/cli) if the installation fails.

Return to Studio and run its connection check again. Use Studio's project chat to make your video.

Both install commands match the official docs as of October 9, 2026.

### Grok

Grok setup is not documented in this pack. Use Claude Code or Codex, or check Studio's current provider options. See the [source notes](../resources/sources.md#limits) for the scope of this guide.

## Command not found?

Close Terminal, open a new window, and try `claude` or `codex` again. If it still fails, follow the linked tool's installation troubleshooting. A new window helps only when the install succeeded and the old window has not picked up the change.

## Start your first project

Open Studio, start a project, and attach the files your prompt lists. Replace the bracketed blanks, paste the prompt, and send. Stay for the first run so you can review the plan and preview.

If a website cannot be read, attach its text or screenshots instead. If an Excel file cannot be read, save the relevant sheet as a CSV and attach that.
