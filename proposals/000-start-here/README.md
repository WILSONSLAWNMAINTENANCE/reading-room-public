<div align="center">

<img src="../assets/icons/compass.svg" width="64" height="64" alt="">

# Start here

### How this folder reads, how to answer if you ever want to, and how to bring your helper along

*Read this one once. Every other proposal assumes you have.*

![Proposal](https://img.shields.io/badge/Proposal-000-65a30d?style=flat-square)
![Status](https://img.shields.io/badge/Status-evergreen-365314?style=flat-square)
![Updated](https://img.shields.io/badge/Updated-2026--11--04-4d7c0f?style=flat-square)
![For](https://img.shields.io/badge/For-Jeff_and_his_helpers-64748b?style=flat-square)

</div>

---

## <img src="../assets/icons/compass.svg" width="26" height="26" alt=""> TL;DR

> [!TIP]
> **Five lines, if that's all you read.**
>
> 1. <img src="../assets/icons/book-open.svg" width="16" height="16" alt=""> **A proposal is one folder with one page.** The five-line TL;DR comes first, the detail folds away underneath, and the same page is a **PDF** in `pdf/` for anyone who would rather not open GitHub.
> 2. <img src="../assets/icons/gift.svg" width="16" height="16" alt=""> **Nothing here is an ask.** Everything written for Wilson's Lawn Maintenance is offered. *"Not now"* is a complete answer, and so is silence: nothing changes until Jeff says so.
> 3. <img src="../assets/icons/bot.svg" width="16" height="16" alt=""> **Bring your helper.** If you use ChatGPT, Claude or another assistant, it can read these pages with you, never more than you can (below).
> 4. <img src="../assets/icons/printer.svg" width="16" height="16" alt=""> **The markdown travels with the PDF.** When a proposal is sent as a PDF, the `.md` goes with it, so a helper reads the words, not a picture of a page.
> 5. <img src="../assets/icons/shield-check.svg" width="16" height="16" alt=""> **Nothing is published by a proposal.** A proposal offers; the owner decides. The business's bank, its prices and its customers are never touched from here.

---

## <img src="../assets/icons/book-open.svg" width="26" height="26" alt=""> How a proposal is shaped

| Part | What it is for |
|---|---|
| <img src="../assets/icons/compass.svg" width="16" height="16" alt=""> **TL;DR** | five lines or fewer; if you read nothing else, read these |
| <img src="../assets/icons/sparkles.svg" width="16" height="16" alt=""> **What's offered** | the idea in plain words: how things are today, beside what is offered |
| <img src="../assets/icons/map-pin.svg" width="16" height="16" alt=""> **Itinerary** | the stops, each lighting up as it is done |
| <img src="../assets/icons/message-circle-question.svg" width="16" height="16" alt=""> **Questions** | usually none; when there is one, it says who could answer it and that "not now" is fine |
| <img src="../assets/icons/scroll-text.svg" width="16" height="16" alt=""> **Decisions log** | what was chosen, when, and by whom; blank until Jeff chooses |
| <img src="../assets/icons/wrench.svg" width="16" height="16" alt=""> **Details** | the technical material, folded into sections you can open or ignore |
| <img src="../assets/icons/search.svg" width="16" height="16" alt=""> **Sources** | where each fact came from, with the date it was read |

The icons beside each idea are a reading aid, not decoration: the same icon means the same thing on every page.

### Status words

<img src="../assets/icons/status-from-you.svg" width="22" height="22" alt="">&nbsp;**offered**: written, waiting on nothing but the owner's interest &nbsp;·&nbsp; <img src="../assets/icons/status-next.svg" width="22" height="22" alt="">&nbsp;**proposed**: written, a choice is open &nbsp;·&nbsp; <img src="../assets/icons/status-partly.svg" width="22" height="22" alt="">&nbsp;**in progress**: agreed and under way &nbsp;·&nbsp; <img src="../assets/icons/status-ready.svg" width="22" height="22" alt="">&nbsp;**done** &nbsp;·&nbsp; <img src="../assets/icons/circle-dashed.svg" width="22" height="22" alt="">&nbsp;**idea**: not yet shared with anyone

---

## <img src="../assets/icons/message-circle-question.svg" width="26" height="26" alt=""> How to answer, if you want to

```mermaid
flowchart LR
  R["you read<br/>(the TL;DR is enough)"] --> A["one line, in your own words<br/>'yes' · 'not now' · 'ask me later'"]
  A --> K["to Christopher, the way you already talk"]
  A -. "once you have a seat" .-> I["an Issue on this repository"]
  K --> L["the decisions log,<br/>with the date and your words"]
  I --> L
```

1. **Read the TL;DR.** If it is enough, answer from it, or don't answer at all.
2. **One line each**, in any order, in your own words: *"001 yes, later"*.
3. **Send it the way you already talk:** to Christopher. Once you have your own seat here, an Issue on this repository works too.
4. **Then the proposal changes, not before.** Your answer goes into its decisions log with the date.

---

## <img src="../assets/icons/bot.svg" width="26" height="26" alt=""> Bring your helper (three steps)

> [!IMPORTANT]
> **Your AI helper can read these pages with you.** Any assistant that can read a PDF or connect to GitHub (ChatGPT,
> Claude, and others) can summarise a proposal, explain a word, and help you answer in your own words.
>
> 1. **Give it the page.** The simplest way: hand it the PDF *and* the `.md` beside it. Once you have your seat, a helper
>    can also be connected to GitHub with read-only access to the reading room ([SOP-IT-002](https://github.com/WILSONSLAWNMAINTENANCE/ops-standard-operating-procedures/blob/main/IT/SOP-IT-002-reading-room-and-helper-access.md)).
> 2. **Paste a first message:** *"Read Start here, then tell me in five lines what is in this folder and whether anything
>    is waiting on me. Don't change anything."*
> 3. **Ask in your own words.** A helper never needs a password, a sign-in code or a bank login, and never gets one.

---

## <img src="../assets/icons/printer.svg" width="26" height="26" alt=""> The markdown beside the PDF

Every proposal exists twice: the `README.md` you are reading, and `pdf/NNN-name.pdf`, rendered from it. The PDF is for
eyes; the markdown is for helpers. A helper given only a PDF has to rebuild the words from a picture of a page, and loses
the links and the exact phrasing. So whenever a proposal is sent on, **both files go**. The full note:
[Markdown beside the PDF](https://github.com/drasticstatic/my-template/blob/main/walkthroughs/MARKDOWN-BESIDE-PDF.md).

---

## <img src="../assets/icons/git-branch.svg" width="26" height="26" alt=""> Five GitHub words, and no more

| Word | Plain meaning |
|---|---|
| <img src="../assets/icons/folder-lock.svg" width="16" height="16" alt=""> **Repository** | a folder with a memory: every change to every file, with who made it and when |
| <img src="../assets/icons/git-branch.svg" width="16" height="16" alt=""> **Branch** | one line of that history; `main` is the copy everyone treats as real |
| <img src="../assets/icons/git-pull-request.svg" width="16" height="16" alt=""> **Pull request** | *"please look at this change and, if you agree, make it the real one"*; a person says yes |
| <img src="../assets/icons/message-circle-question.svg" width="16" height="16" alt=""> **Issue** | a numbered conversation attached to a repository; the simplest way to ask or answer |
| <img src="../assets/icons/git-merge.svg" width="16" height="16" alt=""> **Merge** | accepting a pull request, so the change lands; a person does it, never a helper |

That is all a reader needs. [SOP-COM-001](https://github.com/WILSONSLAWNMAINTENANCE/ops-standard-operating-procedures/blob/main/COM/SOP-COM-001-new-to-github-your-first-hour.md)
is the first hour on GitHub, whenever it is wanted.

---

## <img src="../assets/icons/route.svg" width="26" height="26" alt=""> Where things live

| | Place | What it holds |
|---|---|---|
| <img src="../assets/icons/book-open.svg" width="18" height="18" alt=""> | [this repository](https://github.com/WILSONSLAWNMAINTENANCE/proposals) (`WILSONSLAWNMAINTENANCE/proposals`, private) | every proposal written for the business, numbered, with the index on its front page |
| <img src="../assets/icons/door-open.svg" width="18" height="18" alt=""> | [`WILSONSLAWNMAINTENANCE/reading-room`](https://github.com/WILSONSLAWNMAINTENANCE/reading-room) (private) | the gift, the words of web3, and a copy of these proposals and the procedures: the one place to read everything |
| <img src="../assets/icons/scroll-text.svg" width="18" height="18" alt=""> | [`WILSONSLAWNMAINTENANCE/ops-standard-operating-procedures`](https://github.com/WILSONSLAWNMAINTENANCE/ops-standard-operating-procedures) (private) | the procedures: how a change travels, what the business never needs to do |
| <img src="../assets/icons/presentation.svg" width="18" height="18" alt=""> | [github.com/WILSONSLAWNMAINTENANCE](https://github.com/WILSONSLAWNMAINTENANCE) (public) | the business's profile and its decks |
| <img src="../assets/icons/sparkles.svg" width="18" height="18" alt=""> | [`brand-assets`](https://github.com/WILSONSLAWNMAINTENANCE/brand-assets) (public) | the logo and the photos, and who may use them |
| <img src="../assets/icons/file-text.svg" width="18" height="18" alt=""> | [`ONBOARDING.md`](https://github.com/WILSONSLAWNMAINTENANCE/.github/blob/main/ONBOARDING.md) (public) | the welcome for people and helpers: who is who, what is private, how the work is done |

A private link shows a 404 to anyone not signed in with a seat; that means "not yet", not "broken".

---

<div align="center">
<sub>Wilson's Lawn Maintenance on GitHub · kept by the drasticstatic lab, a brother's gift · Icons: Lucide (ISC). This page follows the pattern every organisation's proposals repository opens with; the template lives in <a href="https://github.com/drasticstatic/my-template/tree/main/proposals-template">my-template</a>.</sub>
</div>
