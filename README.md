# HCI Exercise 3 — Thinking Aloud Test
**Group G1-09 | alza.at | HCI SS 2026**

## Current status

Tests done (2026-05-08). Now in analysis + report writing phase.

**For the detailed checklist of what is done and what is still pending, see [`ex3a-requirements.md`](ex3a-requirements.md).**

**Who has what:**
- External video recordings (DJI): Dawid - in `g1-09-ta-full-videos/external-videos/` (NOT in git, too large)
- Session recordings (OBS): Google Drive - https://drive.google.com/drive/folders/1JMPyzQlClZbJ3457T1XaM_4ivU3aFHoi?hl=pl

---

## Repo structure

```
g1-09-ta/               submission folder (zip this for TeachCenter)
  ta.html               main report
  report.css            stylesheet (do not modify)
  orient.html           orientation script (read from screen, facilitator only)
  background.html       background questionnaire
  interview.html        interview script (read from screen, facilitator only)
  feedback.html         feedback questionnaire
  checklist.html        session checklist
  consent-ta.pdf        consent form template
  external-tasks-ta.pdf task slips for test users
  do-not-disturb.pdf    door sign for test room
  data-ta.xlsx          spreadsheet for results analysis
  hci-validate.json     report validator config
  bq/                   scans of filled background questionnaires (tp1-bq.pdf ... tp5-bq.pdf)
  fq/                   scans of filled feedback questionnaires (tp1-fq.pdf ... tp5-fq.pdf)
  images/               test room photos + browser screenshot
  videos/               video clips illustrating findings (max 20s, max 10MB each)
  presentation/         g1-09-ta-slides.pptx

g1-09-ta-full-videos/   USB stick folder (NOT zipped, hand in physically at M3)
  consent/
    users.html          mapping of tp aliases to real names (fill in your tester!)
    tp1-consent.pdf     signed consent forms (scan as PDF, push to repo)
    ...
    tp5-consent.pdf
  external-videos/      DJI face camera recordings — NOT in git (too large, ~10 GB each)
    tp1-ext.mp4         pilot (done, H.264)
    tp2-ext.mp4 ... tp5-ext.mp4
  session-videos/       OBS screen recordings — NOT in git
    tp1.mp4 ... tp5.mp4
```

## USB stick checklist (hand in physically at M3)

- Format: NTFS or exFAT, label: `HCI 2026 G1-09`
- All videos: MP4, H.264, AAC audio, 720p–1080p
- `external-videos/` — 5 DJI recordings (tp1–tp5-ext.mp4)
- `session-videos/` — 5 OBS recordings (tp1–tp5.mp4)
- `consent/` — 5 signed consent PDFs + users.html

## Before tests

**Print (x5 each):**
- `consent-ta.pdf` — one per tester, signed before session starts
- `external-tasks-ta.pdf` — one set of task slips per session
- `background.html` — facilitator fills it out during session
- `feedback.html` — tester fills it out themselves at the end

**Print (x1):**
- `do-not-disturb.pdf` — put on the door

**Prepare:**
- Write TPID on each consent form before session: `HCI-SS2026-G1-09-TP1` to `TP5`
- Assign a fictional first name alias to each tester
- Prepare 5 fictional identities (name, address, email) for Task 5 (checkout)
- One shared alza.at account — delete and recreate between sessions
- Configure screen recording: MP4, H.264, 1920×1080, 20fps, 5Mbps
- Browser: light mode, no ad blocker, all extensions disabled
- External camera on tripod + external microphone + mirror next to monitor

## During each session (~60 min)

1. Start external camera recording (records entire session, from user entering to leaving)
2. Greet user, read `orient.html`
3. Consent form (TPID pre-filled) → user signs
4. Background questionnaire — facilitator holds pen, fills it out
5. Demo thinking aloud
6. Reset browser (clear cookies, cache, history → set start page to google.com)
7. Start screen recording
8. Tasks 1–5 via task slips (read aloud, place next to keyboard)
9. Interview — start with "So, how was it?", then `interview.html` questions
10. Feedback questionnaire — hand pen to user, they fill it out themselves
11. Stop recordings

## After tests

**Scan to PDF:**
- All 5 background questionnaires → `bq/tp1-bq.pdf` ... `bq/tp5-bq.pdf`
- All 5 feedback questionnaires → `fq/tp1-fq.pdf` ... `fq/tp5-fq.pdf`
- Must be proper scans, not photos

**Analyse:**
- Fill `data-ta.xlsx` with questionnaire data and task success metrics
- Watch session recordings, collect findings with timestamps
- Each member rates severity/positivity individually (0–4), then average
- Extract video clips: max 20s, max 10MB, MP4 H.264, blur faces
- Name clips: `n-tpY-keywords.mp4` / `p-tpY-keywords.mp4`, add number after ranking

**Report (`ta.html`):**
- Top 3 positives, top 5 problems with video clips embedded
- Test room photos in `images/`
- All clips in `videos/`

**Presentation:**
- PowerPoint `.pptx`, 16:9, light mode, videos embedded
- Save as `g1-09-ta-slides.pptx` in `presentation/`
- 15 min presentation at M3

**Hand in:**
- Zip `g1-09-ta/` → `g1-09-ta.zip` (max 500 MB) → upload to TeachCenter
- USB stick: `g1-09-ta-full-videos/` with `session-videos/`, `external-videos/`, `consent/` → hand in physically at M3
