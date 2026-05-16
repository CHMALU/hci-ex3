# Ex3a Requirements Checklist

## Test Users
- [x] 5 users total: 1 pilot + 4 real (TP1–TP5 done)
- [x] Pilot: from the middle of the user group (not the extremes)
- [x] 4 real users: span the full range of the user group
- [x] At least 18 years old
- [x] Native or proficient speaker of the test language (EN or DE)
- [x] Experienced in using computers and the web
- [x] Not currently taking the HCI course this semester
- [x] Not serving as a test user for another HCI group this semester
- [x] Assign fictitious first name aliases (different from real names)

## Test Environment
- [x] Same room, device, and browser for all 5 users
- [x] PC (desktop or laptop, Windows/macOS/Unix)
- [x] Chrome, Firefox, or Safari — light mode (dark text on light background)
- [x] No ad blocker
- [x] Cookies — let the user decide
- [x] At least 1 full day between pilot test and real tests
- [x] All 4 real tests run on the same day

## Session Capture (Screen Recording)
- [x] MP4, H.264 video + AAC audio, FullHD 1920×1080 (confirmed from tp5.mp4)
- [x] 20 fps, VBR, 5000 Kbps video bitrate
- [x] Audio: Stereo, AAC, 44100 Hz, ~160 Kbps (confirmed for tp5.mp4; bits_per_raw_sample N/A is normal for AAC)
- [x] Mouse cursor visible (optionally enlarged), mouse trails OFF — verify visually
- [x] No watermark
- [x] Browser window + webcam overlay (bottom-right corner) in recording
- [x] Nothing outside the browser (taskbar, desktop icons) except the webcam overlay — **potential issue flagged previously**

## External Video Recording (Tripod Camera)
- [x] Record the entire session from user entering to user leaving the room
- [x] Tripod mandatory — no handheld, no unnecessary panning/zooming
- [x] Mirror next to the monitor to capture facial expressions
- [x] Camera over user's shoulder: screen, keyboard, and face in mirror all visible
- [x] External microphone, audio levels checked before recording
- [x] MP4, H.264 + AAC, FullHD 1920×1080, landscape — verify format of external videos
- [x] Resolution: min 1280×720, max 1920×1080 (all tp1–tp5-ext.mp4 confirmed 1920×1080)
- [x] Turn off camera overlays (date, time, mode, etc.) — verify visually
- [ ] Take photos of the test room with all equipment set up (JPEG) — **MISSING: no testroom photos in images/, only browser-version.png exists**

## Materials to Prepare
- [x] `orient.html` — adapted (Dawid as facilitator name confirmed)
- [x] `background.html` — extended with 3 domain-specific questions (online shopping frequency, known e-shops, important factors)
- [x] `interview.html` — extended to 4 questions (how was it, particularly good, particularly bad, navigation/search, would you use alza.at)
- [x] `feedback.html` — extended with 2 domain-specific questions (product relevance, product properties listing, filtering options)
- [x] External task slips (`external-tasks-ta.pdf` present)
- [x] Fictitious identity for each user (for registration tasks)
- [x] Separate email addresses if email verification is required

## Consent Form
- [x] TPID in top-right corner: `HCI-SS2026-G1-09-TPn`
- [x] User reads and signs the form (`consent-ta.pdf` present, scans in `bq/`)
- [x] Inform user that personal data will be deleted after 1 year

## Analysis
- [ ] Each team member rates severity (0–4) and positivity (0–4) individually — **DC done, SJ/LR/FM partially done, group ranking meeting still needed**
- [ ] Calculate mean to 2 decimal places — **pending full ratings**
- [ ] Sort tables in descending order by mean — **pending full ratings**
- [ ] At least 1 video clip per user who experienced each finding — **only TP1/TP2/TP5 clips exist so far (TP3/TP4 pending from Luca)**

## Video Clips
- [x] MP4, H.264 + AAC, max FullHD resolution
- [x] **Max 20 seconds** (all clips verified OK)
- [x] **Max 10 MB (10,000,000 bytes)** (all clips verified OK)
- [x] Faces blurred (webcam overlay blurred on all TP5 clips; TP1/TP2 clips by Fabian/Sven — verify their blurring)
- [x] Temporary naming: `n-tpY-keywords.mp4` / `p-tpY-keywords.mp4`
- [ ] Final naming after ranking: `nXX-tpY-keywords.mp4` / `pXX-tpY-keywords.mp4` — **pending group ranking meeting**
- [ ] Poster image (JPEG) for each clip used in top 3 positives / top 5 negatives — **none created yet**
- [x] Clips extracted from session capture video

## Report (`ta.html`)
- [] UTF-8 encoding
- [] Plain HTML (no JS, no frames, not exported from Word or LaTeX)
- [] 2 spaces for indentation, no Tab characters
- [] Keep `<section>` structure and `<section id>` attributes intact
- [] Do not modify `report.css`, do not add `<style>` elements
- [ ] Remove all `{instructions in curly brackets}` before submission — **54 still present**
- [ ] Validate HTML
- [ ] All links local (relative), report is fully self-contained — **asset links OK, but video/poster files missing**
- [ ] Top 3 positives and top 5 negatives use `<video>` element with `poster` attribute — **still template content, 1 video missing poster**
- [] CC BY 4.0 statement at the bottom

## Report Content
- [x] Title info: group number, topic, names of all group members — date set to 20th May 2026
- [ ] **Executive Summary** (max 25% about procedure, rest about findings) — missing
- [x] **3.1 Methodology** — thinking aloud methodology, **at least 2 own literature references** — done (Bar2020, Dum1999, Eri1993)
- [x] **2 Introduction** — site description and language paragraph done
- [x] **3.2 User Profiles** — types of users the site targets, their goals and typical tasks — done
- [x] **3.3 Test Users** — background questionnaire data in table form, fictitious aliases — done
- [ ] **3.4 Test Environment** — hardware, software version, room, session + external recording description — table + 3 text paragraphs done, only missing testroom photo
- [x] **3.5 Training** — what training each user received (interface, domain, thinking aloud) — done (no interface training, TA demo via ta-demo-keith.mp4, no practice round)
- [x] **3.6 Tasks** — internal task list + task descriptions given to users — done
- [x] **3.7 Interview Questions** — questions asked at the post-test interview — done (links to appendix)
- [x] **3.8 Feedback Questionnaire** — the questionnaire given at the end — done (links to appendix)
- [x] **3.9 Data Collection** — how data and data protection are handled — done
- [x] **4.1 Task Completion** — overview of task completion rates — done
- [ ] **4.2 First Impressions** — summary for each TP after Task 1 — TP1/TP2 partial, TP3/TP4/TP5 empty (need Luca's data)
- [ ] **4.3 Top Positive Findings** — for each: diagnosis, video clip, individual ratings, timestamps, number of users affected, optional quote — still template content, not our findings
- [ ] **4.4 List of All Positives** — TP5 done, TP1/TP2 missing, ratings incomplete
- [ ] **4.5 Top Negative Findings** — for each: diagnosis, video clip, individual ratings, timestamps, number of users affected, optional quote, **recommended improvements** — still template content, not our findings
- [ ] **4.6 List of All Problems** — TP5 done, TP1/TP2/TP3/TP4 missing, ratings incomplete
- [ ] **4.7 Interviews** — summary of post-test interview comments and suggestions — template text with wrong aliases (Stuart/Silvia/Sally), need real content
- [ ] **4.8 Feedback Questionnaires** — summary of questionnaire responses — only 3 of ~14 questions filled
- [x] Background questionnaire scans as PDF: `bq/tp1-bq.pdf`, `bq/tp2-bq.pdf`, ...
- [x] Feedback questionnaire scans as PDF: `fq/tp1-fq.pdf`, `fq/tp2-fq.pdf`, ...
- [x] Scans only — no photos!

## Directory Structure
```
g1-09-ta/
  background.html
  checklist.html
  consent-ta.pdf
  external-tasks-ta.pdf
  feedback.html
  interview.html
  orient.html
  report.css
  ta.html
  bq/
    tp1-bq.pdf
    tp2-bq.pdf
    ...
  fq/
    tp1-fq.pdf
    tp2-fq.pdf
    ...
  images/
    browser-version.png
    testroom01.jpg
    testroom02.jpg
    ...
  presentation/
    g1-09-ta-slides.pptx
  videos/
    nXX-tpY-keywords.jpg
    nXX-tpY-keywords.mp4
    ...
    pXX-tpY-keywords.jpg
    pXX-tpY-keywords.mp4
    ...
```
- [ ] No junk files, backup files, or temporary files

## Zip and Submission
- [ ] Zip includes the directory itself: `g1-09-ta.zip`
- [ ] **Max 500 MB**
- [ ] Upload to TeachCenter before the deadline
- [ ] Single group submission (one zip file)
- [ ] Any changes after the deadline = late submission with point deduction
- [ ] Submissions not accepted more than 6 hours after the deadline

## Presentation (`g1-09-ta-slides.pptx`)
- [ ] PowerPoint (.pptx) — NOT Google Slides
- [ ] 16:9 aspect ratio, light mode, large font
- [ ] Videos and images embedded (not linked)
- [ ] Tables as actual tables, not images
- [ ] Title slide: web site URL, names, group number, HCI SS 2026, date of presentation
- [ ] Required talking points: methodology, test users, tasks, test environment, first impressions, **top 2 positives**, **top 4 negatives**, feedback questionnaire summary
- [ ] 15-minute presentation, in English
- [ ] Hand in on USB stick at M3

## USB Stick (Ex3b)
- [ ] 16 or 32 GB, NTFS or exFAT format
- [ ] Directory name: `g1-09-ta-full-videos/`
- [ ] Subdirectories: `session-videos/`, `external-videos/`, `consent/`
- [ ] Hand in physically at M3
