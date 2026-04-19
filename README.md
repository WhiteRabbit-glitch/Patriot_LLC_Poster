# Patriot Enterprises LLC — AI Proposal Generation Capstone Poster

**CIS576 AI in Business · Arizona State University · Spring 2026**  
Team: Chandra Carr · Chris Applewhite · Aryanna Golabi · Nalin Lee  
Faculty Advisor: Dr. Lu Xiao · SME: Marc (Technical Architecture)

---

## What This Is

A 36" × 24" academic research poster designed for the ASU CIS576 capstone presentation.

The poster presents a prototype **AI-assisted proposal generation system** for Patriot Enterprises LLC, a mid-tier federal government contractor (GovCon). The system uses a **Retrieval-Augmented Generation (RAG)** architecture — combining FAISS vector search, local embeddings via llama.cpp, and Claude (hosted on Amazon Bedrock via Amazon GovCloud) — to automate the most time-intensive stages of federal proposal writing while keeping humans in the loop at every step.

**Key findings:**
- 30–40% projected reduction in proposal drafting time
- Win rate target: 25%+ (up from 20% baseline)
- Zero autonomous AI outputs — every stage requires human review and sign-off
- Patriot's proprietary institutional knowledge (past performance, CO relationships, incumbent intel) is the core competitive differentiator

The poster file is a single self-contained HTML file (`patriot_capstone_poster1.html`) with all content and styling inline — no build tools or dependencies required.

---

## How to Export to PDF and Send to Print

### Step 1 — Open in Chrome

Open `patriot_capstone_poster1.html` in **Google Chrome** (recommended). Other browsers may not render fonts or background colors correctly.

### Step 2 — Print to PDF

1. Press `Ctrl + P` (Windows) or `Cmd + P` (Mac)
2. Set **Destination** → **Save as PDF**
3. Set **Paper size** → **Custom**
   - Width: **91.44 cm** (36 inches)
   - Height: **60.96 cm** (24 inches)
4. Set **Margins** → **None**
5. Set **Scale** → **100%**
6. Enable **Background graphics** (checkbox at the bottom of More settings)
7. Click **Save**

> **Note:** Chrome's custom paper size dialog accepts centimeters. Enter exactly `91.44 cm` wide × `60.96 cm` tall to match the 36" × 24" print size.

### Step 3 — Send to Print

When ordering from a large-format print shop (e.g., FedEx Office, Staples, campus print center, or an online poster printer):

| Setting | Value |
|---|---|
| File format | PDF |
| Finished size | **36" wide × 24" tall** (landscape) |
| Orientation | Landscape |
| Paper | Gloss or matte poster stock (60–80 lb recommended) |
| Color | Full color |
| Margins | None / borderless |
| Scale | Do **not** scale to fit — print at **100% / actual size** |

Upload the saved PDF directly to the print shop's portal or bring it on a USB drive.

---

## Files

| File | Description |
|---|---|
| `patriot_capstone_poster1.html` | Main poster — open in Chrome to view or export |
| `WPCarey.png` | W. P. Carey School of Business logo |
| `Screenshot 2026-04-19 153503.png` | Patriot Enterprises screenshot / logo |
| `LICENSE` | Repository license |
