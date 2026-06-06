# YouTube Removal Analysis — `qoeQG08aVvg`

**Prepared:** 2026-06-06
**Analyst role:** YouTube content-removal & platform-policy (India / IT Rules 2021)
**Requester:** The SUBJECT of the video — "RJ Siddhant Sharma" (also written "RJ Sidhhant" / "Siddharth Sharma" in the video). Based in India.
**Scope limit:** This analysis is built on the **audio transcript + metadata + comments only**. On-screen text, displayed chat screenshots, and any faces/visuals were **NOT** assessed (see Section F).

> ⚠️ **Honesty up front:** YouTube does **not** remove videos for "defamation" on a normal flag. It removes for a *specific named Community Guideline* violation or on a *court / legal order*. On the audio alone, this video reads mostly as **opinion / "expose" commentary in a creator-vs-creator feud**, which YouTube generally treats as permitted speech. The realistic removal lever here is the **legal / court-order route**, not a content flag. Details below — no false hope.

---

## A. Caption availability summary

| Track | Type | Language | Formats |
|---|---|---|---|
| `hi-orig` | **Auto-generated** (ASR) | Hindi/Chhattisgarhi (original spoken) | vtt, srt, ttml, srv3, srv2, srv1, json3 |
| `hi` | **Auto-generated** | Hindi | vtt, srt, ttml, srv3, srv2, srv1, json3 |

- **Manual / uploader-provided subtitles: NONE** (`has no subtitles`).
- Only **auto-captions** exist. They were downloaded successfully (`captions.hi-orig.srv1`). Auto-captions of mixed Hindi/Chhattisgarhi speech contain recognition errors — treat exact wording as indicative, not court-grade. For any legal filing, get a **certified human transcription/translation**.
- STOP condition (no captions at all) was **not** triggered — a usable transcript exists.

> Note on retrieval: this datacenter IP was repeatedly rate-limited / bot-challenged by YouTube ("Sign in to confirm you're not a bot"). Metadata, captions and comments were obtained via the `android` player client with retries. Some heavy calls were flaky; the data below was captured on successful attempts.

---

## B. Metadata block

| Field | Value |
|---|---|
| Video ID | `qoeQG08aVvg` |
| Title | **RJ SIDHHANT EXPOSED! फर्जी Chhattisgarhiya Content का पर्दाफाश, Strike देकर Channel हटाने की साज़िश?** |
| Channel / uploader | **PublicSwar** (`@PublicSwar`) |
| Channel ID | `UCk6Blw-KZiDx9OtGZ1TJ-yA` |
| Channel URL | https://www.youtube.com/channel/UCk6Blw-KZiDx9OtGZ1TJ-yA |
| Host named | **Rohit Soni** (edit: Brijbhushan); presented as "Public Swar & The PS Show" |
| Upload date | **2025-11-14** |
| Duration | 1064 s (~17 min 44 s) |
| View count | 12,799 |
| Likes | 506 |
| Comment count | 170 (120 retrieved) |
| Tags | Public Swar, CG NEWS, CHHATTISGARH NEWS, CG NEWS TODAY, ABHANPUR, ABHANPUR NEWS, RAIPUR NEWS, **ROHIT SONI**, CHHATTISGARH NEWS LIVE, CHHATTISGARH NEWS TODAY, **MANISH SAHU** |
| URL | https://www.youtube.com/watch?v=qoeQG08aVvg |

**Description highlights (relevant to removal):**
- Explicitly names the subject: "RJ सिद्धांत", "RJ Siddhant Sharma".
- Claims: subject came on their podcast, then "अचानक हमारे चैनल पर **Copyright Strike** डालना शुरू कर दिया … चैनल को बार-बार Strike देकर हटाने की साज़िश में लगा था" (suddenly started filing **copyright strikes** on our channel … was in a conspiracy to take the channel down by repeatedly striking it).
- Says it shows "सिद्धांत के इंग्लिश में लिखे असली चैट के सबूत" (**proof of Siddhant's actual chats written in English**) → indicates **on-screen display of private chat screenshots** (must be checked visually — Section F).
- Hashtags include `#rjsidhhantexposed #RJSiddhantExpose #FakeChhattisgarhiya #RJSiddhantSharma #ExposeVideo`.
- Ends with a **self-serving legal disclaimer** ("इस वीडियो को … मानहानि के रूप में न लिया जाए" / "do not treat this as defamation; all claims based on real records"). This shows the uploader is *aware* of defamation risk — useful evidence in a legal claim, but it does **not** make the video flag-removable.

---

## C. Clean transcript

- **File:** `video_evidence/transcript_clean.txt` (354 timestamped lines, `[mm:ss]`, consecutive duplicates removed, from `hi-orig`).
- **What the video claims (summary):** It is a ~17-minute **monologue by host Rohit Soni (The PS Show / Public Swar)** attacking the requester, "RJ Siddhant/Siddharth Sharma," as a **"fake Chhattisgarhiya" (फर्जी छत्तीसगढ़ियावाद)** — i.e., someone faking Chhattisgarhi regional identity for clout/earnings. The narrative:
  1. The subject *himself requested* (via Instagram, in English) to appear on their podcast; they hosted him.
  2. On the show he allegedly **couldn't answer simple Chhattisgarhi culture questions** (folk riddles "जनौला", "सिक्का माला", a folk verse "नानचक टुरी…") → presented as proof he's fake.
  3. **After** the episode, the subject allegedly **filed strikes / a "conspiracy" (साज़िश/षड्यंत्र) to get The PS Show channel deleted.**
  4. Accusations of **double standards** (criticizes others for using Hindi while earning in Hindi himself; a "Switzerland / Chhattisgarhi dish" anecdote).
  5. Repeated **call to the audience to comment "बॉयकॉट फर्जी छत्तीसगढ़ियावाद" (Boycott fake Chhattisgarhi-ism)** and to "boycott" such people.
- It is framed as **opinion + factual allegation ("fact-based expose")**, not a news report and not (in the audio) sexual, and not containing spoken phone numbers/addresses.

---

## D. Policy-mapping table

Subject is referred to as **"RJ सिद्धांत / सिद्धार्थ शर्मा"** throughout. Glosses are of auto-captioned Hindi/Chhattisgarhi; `[unclear]` marks low-confidence ASR.

| Timestamp | Quote (original) → English gloss | Type | Guideline triggered | Strength |
|---|---|---|---|---|
| Title / 00:15, 17:00+ | "फर्जी छत्तीसगढ़ियावाद … RJ Siddhant EXPOSED" → "Fake Chhattisgarhi-ism … RJ Siddhant exposed" | Opinion / insult (name-calling) | None firmly. (Harassment only if part of sustained malicious targeting) | **Low** |
| 01:41 / 03:21 / 12:30 | "आरजे सिद्धांत शर्मा … इंस्टा में मैसेज करे … हम टीम ला समय मिलिस तब … सिद्ध शर्मा ला दे" → "RJ Siddhant Sharma messaged us on Insta; when our team had time we gave him a slot" | Factual claim stated as fact | None (mundane) | **Low** |
| ~01:00 / 04:02 / 13:56; desc. | "सिद्धार्थ शर्मा हम चैनल मा … स्ट्राइक दिस … प्लान रही कि … खत्म कर दिया जाए" + desc "बार-बार Strike देकर हटाने की साज़िश" → "Siddharth Sharma struck our channel … planned to get it shut down … conspiracy to remove it by repeated strikes" | Factual accusation of malicious conduct (potentially defamatory **if false**) | Not a CG violation. Defamation = **legal route only** | **Med** (legal), N/A (flag) |
| 01:08 / 04:54 / 16:24+ | Folk riddle/verse mockery: "नानचक टुरी … जनौला के उत्तर नहीं दे पाई … मालूम ही नहीं" → "couldn't answer the folk riddles … doesn't even know" | Opinion / mockery / commentary | None (criticism of a public persona) | **Low** |
| 07:55–12:30 | "कमाए पर हिंदी में … डबल मापदंड … दोहरा" → "earns in Hindi … double standards / hypocrisy" | Opinion/commentary | None | **Low** |
| 15:30–15:40 | "ऊपर वाला के लाठी चली ना तो नहीं बचते … वो लाठी से डर" → "when God's stick falls, no one is spared … fear that stick" | Veiled karmic/religious warning | **Not** a credible/specific true threat → fails "Threats/Violence" bar | **Low** |
| 17:00, 17:20+ | "कमेंट मा लिखना है बॉयकॉट फर्जी छत्तीसगढ़ियावाद … आइसने आदमी मन के बॉयकॉट करो" → "comment 'Boycott fake Chhattisgarhi-ism' … boycott such people" | Call to action against a **named** individual | **Harassment & Cyberbullying** (mobilising viewers to target an identifiable person) | **Med-Low** |
| 02:18 / 06:24 / 14:10; desc. | "इंग्लिश में लिख के भेजे … मैसेज दिखाओ … चैट के सबूत" → "shows screenshots of his English chat messages" (audio only references them; they are **displayed on screen**) | Possible privacy / sharing private communications | **Privacy** OR **Harassment (revealing info)** — *only if visuals expose PII* | **Conditional — see F** |
| Comments | e.g. `@villain_563`: "सिद्धार्थ के सतौरि धरा जहि" → roughly "Siddharth will be caught/exposed" `[unclear idiom]`; many "farzi/boycott" pile-on comments | Pile-on / opinion | Mass-comment harassment threshold **not** met from what's visible; no PII/threats seen | **Low** |

**Nothing in the audio is:** sexual content; a protected-attribute (caste/religion/etc.) hate attack — note "Chhattisgarhiya" is invoked as *regional pride*, and the attack is "you are a **fake** Chhattisgarhiya," i.e. an authenticity accusation, **not** hate speech against a protected group; or a specific, credible threat of violence.

---

## E. Verdict — strongest removal route

**Single strongest realistic route: the LEGAL / COURT-ORDER path under India's IT Rules 2021 — NOT a Community-Guidelines flag.**

Why: The content is, in substance, an **opinion-driven "expose" in a creator dispute**, mixing insults ("fake Chhattisgarhiya"), folk-quiz mockery, and one serious **factual allegation** (that the subject ran a strike "conspiracy" to delete their channel). YouTube routinely declines to remove this category as **commentary/criticism of a public-facing personality**, and it will **not** adjudicate whether the "strike conspiracy" / "fake" claims are true. That truth question is exactly what **defamation law** decides — so the lever that actually moves YouTube is a **court order / legal notice**, not the report button.

**Ranked routes:**

1. **Legal route (STRONGEST, but requires action & cost) — Court order via IT Rules 2021 ladder.**
   - File a written grievance with **YouTube/Google's Resident Grievance Officer (India)** identifying the URL, the defamatory factual statements (the "strike conspiracy" / "fake" assertions presented as fact), and the unauthorised display of private chats; demand removal within the IT-Rules timelines.
   - If rejected/unsatisfactory, escalate to the **Grievance Appellate Committee (GAC) at gac.gov.in** within 30 days.
   - In parallel, pursue a **civil defamation suit seeking an interim injunction** (and/or criminal defamation under **BNS §356**). A court order/injunction submitted to YouTube's Legal Removals process is what reliably forces takedown of defamatory content.
   - **Honest probability:** This is the only route with a *real* chance of removal — but it requires a lawyer, time, and money, and success turns on proving the factual claims are false (truth is a defence).

2. **Community-Guidelines flag — Harassment & Cyberbullying (backup, weak).**
   - Best hook: content that **names and targets an identifiable individual** combined with an **explicit call to "boycott" him** (17:00+). Report via *⋮ → Report → Harassment or bullying*, and file the dedicated harassment form citing: targeting by name + incitement of the audience against him.
   - **Honest probability:** Low–Medium. YouTube usually classifies "expose"/criticism of a self-promoting public figure as allowed. A flag alone rarely succeeds without a pattern across multiple videos.

3. **Privacy complaint — CONDITIONAL (file only if visuals confirm it).**
   - If the **on-screen chat screenshots reveal personal info** (personal phone number, personal email, home/address, private images, or content identifying him beyond his public RJ persona), file a **Privacy Complaint** (youtube.com → Privacy Complaint Process), which is separate from a CG flag and can succeed where harassment flags fail.
   - **Blocker:** Requires the visual evidence in Section F. From audio alone it's only a *reference* to chats, which is not enough.

4. **Do NOT use:** a **defamation-only flag** (YouTube won't act on it), and **absolutely not a DMCA/copyright takedown** — the requester does **not** own this video; filing copyright would be **misuse, perjurious, and legally risky** (and ironically is the very thing this video accuses *him* of doing).

**Bottom line:** Without a court order, removal is **unlikely**. The flag-based routes (harassment; privacy-if-applicable) are worth filing because they're free and fast, but set expectations low. The durable path is **legal: RGO → GAC → civil injunction → Legal Removals.**

---

## F. Flags — could NOT be assessed (requester must check manually)

These can each *change the verdict* (especially route #3) and require viewing the video itself:

1. **On-screen chat screenshots** — The video shows "English chat" screenshots of the subject. Check whether they expose: personal phone number, personal email, home/office address, private/personal images, or any **non-public personally identifying info** → if yes, this becomes a **strong Privacy-complaint** (and possibly doxxing/harassment) case. Capture timestamped screenshots.
2. **On-screen text / lower-thirds / captions burned into video** — any additional defamatory statements, slurs, or PII not in the audio.
3. **Faces / images of the subject** — whether his face/photos are shown, and in what context (e.g., morphed, mocking, or with abusive captions).
4. **Whether the displayed messages are authentic/edited** — fabricated screenshots strengthen a defamation/forgery claim.
5. **Pattern across the channel** — search PublicSwar / The PS Show for **other videos targeting the same subject**; a sustained campaign materially strengthens the **harassment** route (single-video harassment is hard; a pattern is not).
6. **The comment section over time** — whether comments contain doxxing/threats (none seen in the 120 retrieved, but the section is active and growing; new comments may cross the line).
7. **Certified translation** — for any legal filing, replace the auto-caption gloss with a certified Hindi/Chhattisgarhi→English transcription.

---

## Evidence files (in `video_evidence/`)
- `transcript_clean.txt` — clean `[mm:ss]` transcript
- `captions.hi-orig.srv1`, `captions.hi.srv1` — raw caption tracks (timestamped XML)
- `meta_fields.json` — structured metadata
- `description.txt` — full video description
- `comments.info.json` — full info JSON incl. 120 comments
- `comments_clean.txt` — comments sorted by likes
- `removal_analysis.md` — this report
