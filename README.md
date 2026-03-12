# LedgerAI 🧾

> A personal IFRS-compliant accounting suite powered by Claude AI.  
> Upload any invoice or bill — it automatically reads the total, GST, CGST, SGST, IGST and posts a double-entry journal. No manual data entry.

---

## What This Does

| Feature | Details |
|---|---|
| 📄 **AI Document Extraction** | Upload PDF, image, or text invoice — Claude reads the exact total, tax breakdowns, party name, invoice number |
| 🧾 **Double-Entry Bookkeeping** | IFRS-compliant journal entries posted automatically |
| 💰 **GST Breakdown** | Separate CGST · SGST · IGST columns extracted from every document |
| 📊 **Reports** | P&L, Balance Sheet, Trial Balance — all exportable as CSV or HTML |
| 🏢 **Party Ledgers** | Running balance for every debtor and creditor |
| 🔍 **Anomaly Detection** | AI flags duplicate invoices, large amounts, missing fields |
| 🔐 **Secure API Key** | Anthropic key stored as Supabase server secret — never exposed in browser |

---

## Project Info

| | |
|---|---|
| **Supabase Project** | `ledgerai` |
| **Project Ref** | `wvzvtthwzlufbuyqknou` |
| **Region** | `ap-south-1` — Mumbai (data stays in India 🇮🇳) |
| **Edge Function** | `https://wvzvtthwzlufbuyqknou.supabase.co/functions/v1/claude-proxy` |
| **Stack** | Vanilla HTML/CSS/JS · Supabase · Claude AI (claude-sonnet-4) |

---

## Repo Structure

```
ledgerai/
├── ledgerai.html                    ← Entire app in one file, no build step needed
├── sql/
│   └── schema.sql                   ← Full DB schema — run once in Supabase SQL Editor
├── supabase/
│   └── functions/
│       └── claude-proxy/
│           ├── index.ts             ← Secure proxy — injects API key server-side
│           └── deno.json
└── README.md
```

---

## First-Time Setup

### Step 1 — Run the database schema

1. Open → [Supabase SQL Editor](https://supabase.com/dashboard/project/wvzvtthwzlufbuyqknou/sql/new)
2. Open `sql/schema.sql` from this repo in any text editor
3. Select All → Copy → Paste into the SQL Editor → click **Run**
4. You'll see 7 tables created in the Table Editor:
   - `business_info` `parties` `journals` `journal_lines` `documents` `anomalies` `audit_log`

### Step 2 — Get your Anthropic API key

1. Go to → [console.anthropic.com/settings/keys](https://console.anthropic.com/settings/keys)
2. Click **Create Key**
3. Copy the key — it looks like `sk-ant-api03-...`

### Step 3 — Set the key as a Supabase secret

Install the Supabase CLI:

**Windows** — download `supabase_windows_amd64.msi` from [github.com/supabase/cli/releases](https://github.com/supabase/cli/releases)

**Mac:**
```bash
brew install supabase/tap/supabase
```

Then run:
```bash
supabase login
supabase secrets set ANTHROPIC_API_KEY=sk-ant-api03-YOUR_KEY_HERE --project-ref wvzvtthwzlufbuyqknou
```

You should see: `Finished supabase secrets set` ✅

### Step 4 — Open the app

Just double-click `ledgerai.html` — it opens in your browser. No server, no npm, no setup.

---

## How It Works

```
You upload an invoice (PDF / image / CSV)
            │
            ▼
ledgerai.html reads the file
            │
            │  POST — file bytes sent to Supabase Edge Function
            ▼
claude-proxy (Supabase · Mumbai server)
            │  injects ANTHROPIC_API_KEY from server secret
            │
            ▼
Claude AI reads the document
            │  extracts: amount · tax rate · CGST · SGST · IGST
            │            party name · invoice no · date · line items
            ▼
Result sent back to browser
            │
            ▼
You review & confirm → Journal Entry posted automatically
```

**Your API key never touches the browser.** It lives only as an encrypted Supabase secret on the Mumbai server.

---

## Database Tables

| Table | Purpose |
|---|---|
| `business_info` | Your company name, GST registration, accounting period |
| `parties` | Debtors (customers) and creditors (vendors) with running balance |
| `journals` | Journal entry headers (ref, date, narration) |
| `journal_lines` | Individual debit/credit lines per journal |
| `documents` | Uploaded invoice metadata + extracted amounts |
| `anomalies` | AI-flagged issues (duplicates, large amounts, missing fields) |
| `audit_log` | Immutable log of all changes (IFRS compliance) |

---

## Re-deploying the Edge Function

If you make changes to `supabase/functions/claude-proxy/index.ts`:

```bash
supabase functions deploy claude-proxy --project-ref wvzvtthwzlufbuyqknou
```

---

## Troubleshooting

| Problem | Fix |
|---|---|
| Extraction not working | Make sure Step 3 is done — run `supabase secrets list --project-ref wvzvtthwzlufbuyqknou` to verify |
| SQL errors on schema run | Make sure you paste the **entire** `schema.sql` file |
| `supabase: command not found` | Redo the CLI install in Step 3 |
| App opens but shows blank | Open in Chrome or Edge (not Safari on older versions) |

---

## Built With

- [Claude AI](https://anthropic.com) — document extraction & anomaly detection  
- [Supabase](https://supabase.com) — database, edge functions, secrets  
- [IFRS Standards](https://www.ifrs.org) — IAS 1 compliant P&L and Balance Sheet  
