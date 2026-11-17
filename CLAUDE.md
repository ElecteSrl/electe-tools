# CLAUDE.md

Standing rules for agents working in this repository. They are Fabio's, recorded in every ElecteSrl repository; the
fuller record of the estate's conventions is `electe.net`'s and `electe-migration`'s `CLAUDE.md`.

## Standing rules for agents

- **NEVER merge a pull request without Fabio's explicit instruction for THAT specific pull request, in the current
  conversation.** Merging is his call, every time.
- **NEVER open a pull request without asking Fabio first** (2026-11-11). Ask in the conversation, naming the branch and
  what it carries, and open it only after his yes for THAT pull request. Pushing to a session's own branch needs no
  question.
- **Open every pull request as a DRAFT, and push to it as few times as the work allows** (Fabio, 2026-11-17:
  *"remember to open pr as draft until i tell you otherwise"*, *"In every claude md, for every repo in this session"*).
  The organisation's GitHub Actions budget for the month (50,000) was spent by 2026-11-17: on `electe.net` every push to
  an open pull request starts about 48 jobs, and one session pushed to #270 about ten times in a day (Fabio: *"This is
  not sustainable"*). So: create the pull request with `draft: true`; verify before pushing, in the container or in a
  Daytona sandbox, not on the runners; batch fixes into one push; never push to see what CI says, and never re-run a
  job to see whether it passes now. Marking a draft "Ready for review" is Fabio's click, or done only when he says so
  for that pull request. The workflows do not skip drafts yet (to be tested in December 2026); until they do, a draft
  still costs a run per push, which is the reason to batch.
