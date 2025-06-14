
# 🔐 Progressive Dispute AI Command Reference

This document outlines all available AI-assisted legal commands integrated into your GitHub-hosted claim archive.

---

## 🧾 Complaint Log Generator

**Command:**
```
/complaint_log
```

Generates a timeline log of:
- Emails, texts, voicemails
- Contradictions, delays
- Supporting exhibits auto-linked

**Output:** Markdown + optional PDF  
**Citations:** `📎 [Exhibit D – Total Loss Letter](...)`

---

## 📬 Attorney Submission Package

**Command:**
```
/generate_attorney_package
```

Generates:
- Timeline
- Formal letter
- Evidence index
- Custom hardship section
- Output: PDF + Markdown

---

## 🗄️ Metadata / EXIF Analysis

**Command:**
```
/analyze_doc filename.pdf
/analyze_exif image002.png
```

Returns:
- EXIF metadata (camera model, timestamp)
- PDF properties (author, creator, edits)

---

## 🔁 Weekly GitHub Sync

Runs automatically or via:
```
/sync_github_now
```

Updates:
- All files
- Rebuilds offline archive
- Refreshes prompt index

---

## 🗂️ Uploading New Files

Upload via GitHub web to:
- `evidence/`
- `communications/`
- `timeline/`
- `docs/`
- `archive/`

Notify system with:
```
/index_new_uploads
```

---

## 🔐 GitHub Integration Notes

Due to sandbox restrictions, AI cannot directly push files.

But it **can**:
- Track repo updates
- Generate push scripts (`/drop push_script`)
- Generate GitHub API calls (`/drop gh_api_commit`)

---

## 🔥 Memory Reset Recovery

If AI memory resets:
```
/reignite INSURANCE_RESTITUTION_TACTICAL
```
Then tell it:
- GitHub Repo: https://github.com/Nfectious/progressive-dispute-charlesherd
- Archive: /mnt/data/valkyrie/progressive_claim_herd.zip

It will re-sync automatically.

---
