# Macbeth Recall

A revision game for the 24-quotation GCSE *Macbeth* quote bank. Every mode makes you recall the answer before you see it.

**Play it now:** https://raw.githack.com/arjuns4ndhu/random-claude/claude/wonderful-rubin-fonxkh/play/index.html

(Once GitHub Pages is switched on in Settings → Pages → Source: GitHub Actions, it is also at https://arjuns4ndhu.github.io/random-claude/)

## Modes

- **Daily Recall**: spaced repetition. Finish the line, name the quotation from its cue, or unpack its method, meaning and themes, then rate yourself.
- **Gap Fill**: random words go missing each time; Enter jumps between gaps.
- **Lightning Round**: 60 seconds of "who says it?" and "which act?".
- **Theme Hunt** and **Context Links**: find every quotation that fits a theme or a Jacobean context point.
- **Play Order**: put five quotations in the order they appear.
- **Exam Plan**: choose three quotations for an essay question, then analyse one.
- **Quote Bank**: filter and group by character, theme or act, and cover quotes or notes to test yourself.

Progress is saved in your browser. When the game is opened as a Claude artifact, it can also sync progress to your Claude account and give examiner-style feedback on written answers; on the public site those extras are hidden.

`play/index.html` is the same game wrapped as a full web page. The source is a single file: [`macbeth-recall/index.html`](macbeth-recall/index.html). The GitHub Pages workflow wraps it in a full HTML document and publishes it on every push.

## Instagram agent skills

This repo also carries the [instagram-agent-skill](https://github.com/postzen-dev/instagram-agent-skill) pack (MIT, by PostZen) as project-local Claude Code skills in `.claude/skills/ig-*`. The PostZen MCP server is registered in `.mcp.json`.

To finish setup on your machine: open the repo in Claude Code, run `/mcp`, pick `postzen`, choose Authenticate, sign in and grant Read & Write. Then copy `.claude/instagram-agent/voice.md` to `~/.instagram-agent/voice.md` and fill it in. Skills: `/ig-reel`, `/ig-caption`, `/ig-carousel`, `/ig-story`, `/ig-repurpose`, `/ig-viral`, `/ig-profile`, `/ig-plan`, `/ig-audit`, `/ig-comment`, `/ig-reply`, `/ig-dm`, `/ig-human`, `/ig-publish`.
