# Idea Vomit Desk

**For short-form content.** A free desk for creators. Dump messy thoughts, get hooks and scripts that sound like **you**, and track which reels actually worked.

It runs inside your own Claude account. No sign-up, no API key, nothing to pay for beyond the Claude plan you already have.

## What it does

- **Dump**: write whatever's in your head. It pulls out up to four video ideas, says which are worth filming, and gives you two hook lines for each, written from your own words.
<img width="795" height="945" alt="image" src="https://github.com/user-attachments/assets/c609e6a7-bd36-4a39-843d-4846df512f2f" />

- **Pieces**: one saved page per video. Brief, hook, script, caption. Every version is kept.
- **Hook markup**: scores your hook on five things (stops the scroll, opens a question, matters to a stranger, specific, works on mute), shows the weak words, and gives three edits of *your* line.
- **Script**: start from your rough version, let it interview you first, or draft from the hook. Lines it wrote are marked, so you always know what's yours.
- **Voice**: paste how you actually talk; it builds a voice brief that goes into every request. Mark any line "Sounds like me" or "Not me" and it learns.
- **My reels**: log your reels and their numbers. Feedback gets compared against your own results.
- **Playbook**: 20 short framework cards with a drill each.

## Set it up (about 5 minutes)

You need a Claude account (claude.ai or the Claude desktop app).

1. Download `idea-vomit-desk.html` from this repo (click it, then the download button).
2. Open a new chat in Claude, attach the file, and paste this:

   > Publish this HTML file as a private artifact called "Idea Vomit Desk", exactly as it is, without changing the code. Give it the capabilities sample, db, user and downloads.

3. Open the artifact Claude gives you. Allow it to use Claude when it asks; that's how it writes hooks.
4. Go to **Voice** first and paste 5 to 10 of your own captions or transcripts. Then log a few reels in **My reels**. The more of you it has, the less generic it gets.

Everything you write saves to your own account. Use **Settings → Download a backup** now and then.

## Good to know

- Every request runs on your own Claude usage. Pick **Quick**, **Balanced** or **Deep** next to any button; Balanced is the default.
- It needs to run inside Claude. Opening the HTML file straight from your computer shows the app, but the writing features won't work.
- If Claude can't publish artifacts on your plan, the setup in step 2 won't work. Open an issue and say what you saw.

## License

MIT. Use it, change it, share it; keep the credit. See [LICENSE](LICENSE).

## Hook templates

[HOOKS.md](HOOKS.md) has 40 fill-in hook templates, five for each of eight types. Use them for structure, then say the line out loud and rewrite anything that sounds like a template.

---

Made by Harshwardhan. I post about building things and testing them on myself: [@byhrshwrdhn on Instagram](https://www.instagram.com/byhrshwrdhn/).
