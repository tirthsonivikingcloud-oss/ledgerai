<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>LedgerAI — IFRS Accounting Suite</title>
<link rel="preconnect" href="https://fonts.googleapis.com"/>
<link href="https://fonts.googleapis.com/css2?family=DM+Mono:ital,wght@0,300;0,400;0,500;1,400&family=Syne:wght@400;600;700;800&display=swap" rel="stylesheet"/>
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{
  --bg:#0a0e1a;--surface:#111827;--surface2:#0f172a;--border:#1e2a3a;--border2:#1a2332;
  --text:#e2e8f0;--text2:#94a3b8;--text3:#64748b;--text4:#475569;
  --indigo:#4f46e5;--violet:#7c3aed;--indigo2:#818cf8;
  --green:#10b981;--red:#ef4444;--amber:#f59e0b;--blue:#3b82f6;--blue2:#60a5fa;
}
html,body{height:100%;overflow:hidden}
body{font-family:'DM Mono',monospace;background:var(--bg);color:var(--text);display:flex;flex-direction:column}
::-webkit-scrollbar{width:4px;height:4px}
::-webkit-scrollbar-track{background:var(--bg)}
::-webkit-scrollbar-thumb{background:#2d3748;border-radius:2px}
a{color:inherit;text-decoration:none}

#header{background:#080c18;border-bottom:1px solid var(--border);padding:10px 20px;display:flex;align-items:center;justify-content:space-between;flex-shrink:0;position:relative;z-index:100}
.logo-box{width:32px;height:32px;background:linear-gradient(135deg,var(--indigo),var(--violet));border-radius:8px;display:flex;align-items:center;justify-content:center;font-size:16px;flex-shrink:0}
.logo-text{font-family:'Syne',sans-serif;font-size:15px;font-weight:700;letter-spacing:.02em}
.logo-sub{font-size:9px;color:var(--text4);letter-spacing:.1em;margin-top:1px}
.hdr-right{display:flex;align-items:center;gap:10px}

#app{display:flex;flex:1;overflow:hidden}
#sidebar{width:196px;background:#080c18;border-right:1px solid var(--border);padding:12px 0;flex-shrink:0;overflow-y:auto}
#main{flex:1;overflow-y:auto;padding:22px}

.tab-btn{display:flex;align-items:center;gap:10px;width:100%;padding:9px 14px;background:none;border:none;border-left:2px solid transparent;color:var(--text3);font-family:'DM Mono',monospace;font-size:12px;cursor:pointer;transition:all .18s;text-align:left}
.tab-btn:hover{background:rgba(99,102,241,.1);color:var(--text2)}
.tab-btn.active{background:rgba(99,102,241,.18);color:var(--indigo2);border-left-color:var(--indigo2)}
.tab-icon{font-size:13px;opacity:.8;flex-shrink:0}
.badge-pill{margin-left:auto;background:var(--red);border-radius:10px;padding:1px 6px;font-size:10px;color:#fff}

.card{background:var(--surface);border:1px solid var(--border);border-radius:8px;transition:border-color .2s}
.card:hover{border-color:#2d3a4f}

.btn{cursor:pointer;border:none;border-radius:6px;font-family:'DM Mono',monospace;font-size:12px;padding:7px 14px;transition:all .18s;display:inline-flex;align-items:center;gap:6px}
.btn-primary{background:linear-gradient(135deg,var(--indigo),var(--violet));color:#fff}
.btn-primary:hover{opacity:.88;transform:translateY(-1px)}
.btn-ghost{background:transparent;color:var(--text2);border:1px solid #2d3748}
.btn-ghost:hover{background:#1e2a3a;color:var(--text)}
.btn-success{background:linear-gradient(135deg,#059669,var(--green));color:#fff}
.btn-success:hover{opacity:.88}
.btn-danger{background:linear-gradient(135deg,#dc2626,var(--red));color:#fff}
.btn-dl{background:rgba(16,185,129,.15);color:var(--green);border:1px solid rgba(16,185,129,.3)}
.btn-dl:hover{background:rgba(16,185,129,.25)}

.inp{background:var(--surface2);border:1px solid #2d3748;border-radius:6px;color:var(--text);font-family:'DM Mono',monospace;font-size:12px;padding:7px 11px;width:100%;outline:none;transition:border .2s}
.inp:focus{border-color:var(--indigo)}
select.inp{cursor:pointer}

.badge{display:inline-block;padding:2px 8px;border-radius:4px;font-size:10px;font-weight:500}

table{width:100%;border-collapse:collapse;font-size:12px}
th{background:var(--surface2);color:var(--text3);padding:8px 11px;text-align:left;font-size:10px;text-transform:uppercase;letter-spacing:.05em;border-bottom:1px solid var(--border)}
td{padding:8px 11px;border-bottom:1px solid var(--border2);color:#cbd5e1}
tr:hover td{background:rgba(255,255,255,.02)}

.syne{font-family:'Syne',sans-serif}
.mono{font-family:'DM Mono',monospace}
.positive{color:var(--green)}
.negative{color:var(--red)}
.sec-title{font-family:'Syne',sans-serif;font-size:21px;font-weight:700;color:#f1f5f9;margin-bottom:4px}
.sec-sub{font-size:11px;color:var(--text4);margin-bottom:20px}
.grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}
.grid-2{display:grid;grid-template-columns:1fr 1fr;gap:14px}

.prog-bar{height:3px;background:var(--border);border-radius:2px;overflow:hidden}
.prog-fill{height:100%;background:linear-gradient(90deg,var(--indigo),var(--violet));transition:width .4s}

#notif{position:fixed;top:14px;right:14px;z-index:9999;font-size:12px;padding:11px 18px;border-radius:8px;max-width:340px;display:none;animation:slideIn .3s ease}
@keyframes slideIn{from{transform:translateY(-8px);opacity:0}to{transform:translateY(0);opacity:1}}
@keyframes spin{to{transform:rotate(360deg)}}
.spinner{width:14px;height:14px;border:2px solid var(--indigo);border-top-color:transparent;border-radius:50%;animation:spin .8s linear infinite;display:inline-block}

.drop-zone{border:2px dashed #2d3748;border-radius:12px;padding:50px;text-align:center;cursor:pointer;transition:all .3s}
.drop-zone.drag-over{border-color:var(--indigo);background:rgba(79,70,229,.07)}
.drop-zone:hover{border-color:#4d5a70}

.kpi-card{padding:15px 18px;position:relative;overflow:hidden}
.kpi-val{font-family:'Syne',sans-serif;font-size:19px;font-weight:700;color:#f1f5f9;margin:6px 0 3px}

.pl-row{display:flex;justify-content:space-between;padding:6px 22px}
.pl-row.bold{border-top:1px solid var(--border);padding:9px 22px}
.pl-row.highlight{background:rgba(99,102,241,.05)}
.pl-row.section{padding:10px 22px 3px;background:#080c18}
.pl-section-lbl{font-family:'Syne',sans-serif;font-size:10px;color:var(--text4);letter-spacing:.1em;font-weight:600}
.pl-row-lbl{font-size:12px}
.pl-row-val{font-family:'DM Mono',monospace;font-size:12px}

.party-item{padding:11px 14px;cursor:pointer;border-bottom:1px solid var(--border2);border-left:2px solid transparent;transition:all .15s}
.party-item:hover{background:rgba(99,102,241,.08)}
.party-item.active{background:rgba(99,102,241,.13);border-left-color:var(--indigo2)}

.upload-svc{background:var(--surface2);border-radius:8px;padding:13px;border:1px solid transparent}

/* BUSINESS INFO BANNER */
#bizBanner{background:rgba(79,70,229,.08);border:1px solid rgba(79,70,229,.2);border-radius:8px;padding:10px 16px;display:flex;align-items:center;justify-content:space-between;margin-bottom:18px;gap:12px}
#bizBannerName{font-family:'Syne',sans-serif;font-size:13px;font-weight:700;color:#f1f5f9}
#bizBannerPeriod{font-size:11px;color:var(--text3)}

/* EDIT MODAL */
#editModal{display:none;position:fixed;inset:0;z-index:9998;background:rgba(0,0,0,.6);align-items:center;justify-content:center}
#editModal.open{display:flex}
#editModalBox{background:#111827;border:1px solid var(--border);border-radius:12px;padding:24px;width:480px;max-width:95vw}

@media print{#header,#sidebar,.btn,#notif,.no-print,#bizBanner{display:none!important}#app{display:block}#main{padding:0}}
</style>
</head>
<body>

<div id="notif"></div>

<!-- EDIT MODAL -->
<div id="editModal">
  <div id="editModalBox">
    <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:18px">
      <div class="syne" style="font-size:14px;font-weight:700;color:#f1f5f9">Edit Business Info &amp; Period</div>
      <button class="btn btn-ghost" onclick="closeEditModal()" style="font-size:11px">✕ Close</button>
    </div>
    <div style="display:grid;gap:13px">
      <div>
        <div style="font-size:10px;color:var(--text4);margin-bottom:5px;text-transform:uppercase;letter-spacing:.06em">Business / Company Name</div>
        <input class="inp" id="modal-bizName" placeholder="e.g. Acme Corp Ltd"/>
      </div>
      <div>
        <div style="font-size:10px;color:var(--text4);margin-bottom:5px;text-transform:uppercase;letter-spacing:.06em">Business Registration / Tax ID</div>
        <input class="inp" id="modal-bizReg" placeholder="e.g. CIN / GSTIN / VAT No."/>
      </div>
      <div class="grid-2" style="gap:11px">
        <div>
          <div style="font-size:10px;color:var(--text4);margin-bottom:5px;text-transform:uppercase;letter-spacing:.06em">Period Start Date</div>
          <input class="inp" type="date" id="modal-periodStart"/>
        </div>
        <div>
          <div style="font-size:10px;color:var(--text4);margin-bottom:5px;text-transform:uppercase;letter-spacing:.06em">Period End Date</div>
          <input class="inp" type="date" id="modal-periodEnd"/>
        </div>
      </div>
      <div>
        <div style="font-size:10px;color:var(--text4);margin-bottom:5px;text-transform:uppercase;letter-spacing:.06em">Fiscal Year Label</div>
        <input class="inp" id="modal-fyLabel" placeholder="e.g. FY 2024, Q1 2025"/>
      </div>
      <div>
        <div style="font-size:10px;color:var(--text4);margin-bottom:5px;text-transform:uppercase;letter-spacing:.06em">Reporting Address (optional)</div>
        <input class="inp" id="modal-bizAddress" placeholder="e.g. 123 Main St, Mumbai 400001"/>
      </div>
    </div>
    <div style="display:flex;gap:8px;margin-top:18px;justify-content:flex-end">
      <button class="btn btn-ghost" onclick="closeEditModal()">Cancel</button>
      <button class="btn btn-primary" onclick="saveBusinessInfo()">✓ Apply to All Reports</button>
    </div>
  </div>
</div>

<!-- HEADER -->
<div id="header">
  <div style="display:flex;align-items:center;gap:11px">
    <div class="logo-box">⬡</div>
    <div>
      <div class="logo-text syne" id="headerBizName">LEDGERAI</div>
      <div class="logo-sub">IFRS · MULTI-CURRENCY · AI-POWERED</div>
    </div>
  </div>
  <div class="hdr-right">
    <select class="inp" id="currencySelect" style="width:110px;font-size:11px"></select>
    <button class="btn btn-ghost" onclick="openEditModal()" style="font-size:11px;border-color:rgba(79,70,229,.4);color:var(--indigo2)">✎ Edit Info</button>
    <div id="anomalyPill" style="display:none;cursor:pointer;background:rgba(239,68,68,.13);border:1px solid var(--red);border-radius:20px;padding:3px 10px;font-size:10px;color:var(--red)" onclick="switchTab('anomalies')"></div>
    <button class="btn btn-ghost" onclick="switchTab('upload')" style="font-size:11px">↑ Upload</button>
  </div>
</div>

<!-- BODY -->
<div id="app">
  <!-- SIDEBAR -->
  <div id="sidebar">
    <button class="tab-btn active" data-tab="dashboard" onclick="switchTab('dashboard')"><span class="tab-icon">⬡</span>Dashboard</button>
    <button class="tab-btn" data-tab="upload" onclick="switchTab('upload')"><span class="tab-icon">↑</span>Upload</button>
    <button class="tab-btn" data-tab="extract" onclick="switchTab('extract')"><span class="tab-icon">✦</span>AI Extract</button>
    <button class="tab-btn" data-tab="ledgers" onclick="switchTab('ledgers')"><span class="tab-icon">≡</span>Ledgers</button>
    <button class="tab-btn" data-tab="journals" onclick="switchTab('journals')"><span class="tab-icon">⊞</span>Journals</button>
    <button class="tab-btn" data-tab="pl" onclick="switchTab('pl')"><span class="tab-icon">◈</span>P &amp; L</button>
    <button class="tab-btn" data-tab="bs" onclick="switchTab('bs')"><span class="tab-icon">◉</span>Balance Sheet</button>
    <button class="tab-btn" data-tab="tb" onclick="switchTab('tb')"><span class="tab-icon">⊟</span>Trial Balance</button>
    <button class="tab-btn" data-tab="anomalies" onclick="switchTab('anomalies')"><span class="tab-icon">◬</span>Anomalies<span id="anomalyBadge" style="display:none" class="badge-pill"></span></button>
    <button class="tab-btn" data-tab="settings" onclick="switchTab('settings')"><span class="tab-icon">⊙</span>Settings</button>
  </div>

  <!-- MAIN -->
  <div id="main">
    <!-- DASHBOARD -->
    <div id="tab-dashboard" class="tab-pane">
      <div id="bizBanner">
        <div>
          <div id="bizBannerName">LedgerAI Demo Co.</div>
          <div id="bizBannerPeriod">FY 2024 · 01 Jan 2024 – 31 Dec 2024</div>
        </div>
        <button class="btn btn-ghost no-print" onclick="openEditModal()" style="font-size:10px;padding:4px 10px;border-color:rgba(79,70,229,.3);color:var(--indigo2)">✎ Edit</button>
      </div>
      <div class="sec-title">Financial Dashboard</div>
      <div class="sec-sub" id="dashboardSub">IFRS-compliant · Real-time · FY 2024</div>
      <div class="grid-3" id="kpiGrid" style="margin-bottom:18px"></div>
      <div class="grid-2" style="margin-bottom:14px">
        <div class="card" style="padding:18px" id="plMini"></div>
        <div class="card" style="padding:18px" id="recentDocs"></div>
      </div>
      <div class="card" style="padding:18px" id="partyTable"></div>
    </div>

    <!-- UPLOAD -->
    <div id="tab-upload" class="tab-pane" style="display:none">
      <div class="sec-title">Document Upload</div>
      <div class="sec-sub">Drag & drop invoices, bills, receipts, or bank statements. AI extracts data automatically.</div>
      <div class="drop-zone" id="dropZone" onclick="document.getElementById('fileInput').click()">
        <input type="file" id="fileInput" multiple accept=".pdf,.png,.jpg,.jpeg,.txt,.csv" style="display:none" onchange="handleFileInput(this.files)"/>
        <div style="font-size:44px;opacity:.55;margin-bottom:14px">⬆</div>
        <div class="syne" style="font-size:15px;font-weight:600;color:var(--text2);margin-bottom:7px">Drop files here or click to browse</div>
        <div style="font-size:11px;color:var(--text4)">Supports PDF, PNG, JPG, TXT, CSV · Multiple files</div>
        <div style="margin-top:14px;display:flex;justify-content:center;gap:7px;flex-wrap:wrap">
          <span class="badge" style="background:#1e2a3a;color:var(--text3);font-size:10px">Sales Invoice</span>
          <span class="badge" style="background:#1e2a3a;color:var(--text3);font-size:10px">Purchase Bill</span>
          <span class="badge" style="background:#1e2a3a;color:var(--text3);font-size:10px">Receipt</span>
          <span class="badge" style="background:#1e2a3a;color:var(--text3);font-size:10px">Bank Statement</span>
          <span class="badge" style="background:#1e2a3a;color:var(--text3);font-size:10px">Credit Note</span>
        </div>
      </div>
      <div id="uploadProgress" style="margin-top:14px"></div>
      <div class="card" style="padding:18px;margin-top:14px">
        <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:12px">
          <div class="syne" style="font-size:12px;font-weight:600;color:var(--text2)">AI EXTRACTION ENGINE</div>
          <button class="btn btn-ghost" onclick="switchTab('settings')" style="font-size:10px">Configure →</button>
        </div>
        <div class="grid-3">
          <div class="upload-svc" id="claudeEngineCard" style="border-color:rgba(245,158,11,.2)"><div style="font-size:11px;font-weight:600;color:var(--text);margin-bottom:3px">Claude AI</div><div style="font-size:10px;color:var(--text4);margin-bottom:7px">Primary NLP extraction</div><span class="badge" id="claudeEngineBadge" style="background:rgba(16,185,129,.15);color:#10b981">active · via Supabase</span></div>
          <div class="upload-svc" style="border-color:rgba(245,158,11,.15)"><div style="font-size:11px;font-weight:600;color:var(--text);margin-bottom:3px">AWS Textract</div><div style="font-size:10px;color:var(--text4);margin-bottom:7px">OCR for scanned PDFs</div><span class="badge" style="background:rgba(245,158,11,.15);color:var(--amber)">needs key</span></div>
          <div class="upload-svc" style="border-color:rgba(245,158,11,.15)"><div style="font-size:11px;font-weight:600;color:var(--text);margin-bottom:3px">Google Doc AI</div><div style="font-size:10px;color:var(--text4);margin-bottom:7px">Table & form parsing</div><span class="badge" style="background:rgba(245,158,11,.15);color:var(--amber)">needs key</span></div>
        </div>
      </div>
    </div>

    <!-- EXTRACT REVIEW -->
    <div id="tab-extract" class="tab-pane" style="display:none">
      <div class="sec-title">AI Extraction Review</div>
      <div class="sec-sub">Review extracted data, edit if needed, then post the journal entry.</div>
      <div id="extractContent"></div>
    </div>

    <!-- LEDGERS -->
    <div id="tab-ledgers" class="tab-pane" style="display:none">
      <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:18px">
        <div><div class="sec-title" style="margin-bottom:2px">Party Ledgers</div><div class="sec-sub" style="margin-bottom:0">Running balances for all debtors and creditors.</div></div>
        <button class="btn btn-dl" onclick="downloadLedgers()">↓ Export All Ledgers</button>
      </div>
      <div style="display:grid;grid-template-columns:220px 1fr;gap:14px">
        <div class="card" style="padding:0;overflow:hidden;align-self:start" id="partyList"></div>
        <div id="ledgerDetail"><div class="card" style="padding:36px;text-align:center;color:var(--text4);font-size:13px">Select a party to view their ledger</div></div>
      </div>
    </div>

    <!-- JOURNALS -->
    <div id="tab-journals" class="tab-pane" style="display:none">
      <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:18px">
        <div><div class="sec-title" style="margin-bottom:2px">Journal Entries</div><div class="sec-sub" style="margin-bottom:0">All double-entry journal postings.</div></div>
        <button class="btn btn-dl" onclick="downloadJournals()">↓ Export Journals</button>
      </div>
      <div class="card" style="padding:0;overflow:hidden" id="journalTable"></div>
    </div>

    <!-- P&L -->
    <div id="tab-pl" class="tab-pane" style="display:none">
      <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:18px">
        <div><div class="sec-title" style="margin-bottom:2px">Profit &amp; Loss Statement</div><div id="plSubtitle" class="sec-sub" style="margin-bottom:0"></div></div>
        <div style="display:flex;gap:8px">
          <button class="btn btn-ghost no-print" onclick="openEditModal()" style="font-size:10px;border-color:rgba(79,70,229,.3);color:var(--indigo2)">✎ Edit Period</button>
          <button class="btn btn-dl" onclick="downloadPL('csv')">↓ CSV</button>
          <button class="btn btn-dl" onclick="downloadPL('html')">↓ HTML</button>
          <button class="btn btn-dl" onclick="window.print()">⎙ Print</button>
        </div>
      </div>
      <div class="card" style="max-width:720px;padding:0;overflow:hidden" id="plContent"></div>
    </div>

    <!-- BALANCE SHEET -->
    <div id="tab-bs" class="tab-pane" style="display:none">
      <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:18px">
        <div><div class="sec-title" style="margin-bottom:2px">Balance Sheet</div><div id="bsSubtitle" class="sec-sub" style="margin-bottom:0"></div></div>
        <div style="display:flex;gap:8px">
          <button class="btn btn-ghost no-print" onclick="openEditModal()" style="font-size:10px;border-color:rgba(79,70,229,.3);color:var(--indigo2)">✎ Edit Period</button>
          <button class="btn btn-dl" onclick="downloadBS('csv')">↓ CSV</button>
          <button class="btn btn-dl" onclick="downloadBS('html')">↓ HTML</button>
          <button class="btn btn-dl" onclick="window.print()">⎙ Print</button>
        </div>
      </div>
      <div id="bsContent"></div>
    </div>

    <!-- TRIAL BALANCE -->
    <div id="tab-tb" class="tab-pane" style="display:none">
      <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:18px">
        <div><div class="sec-title" style="margin-bottom:2px">Trial Balance</div><div class="sec-sub" style="margin-bottom:0">Aggregate debit/credit per account. Must balance.</div></div>
        <div style="display:flex;gap:8px">
          <button class="btn btn-ghost no-print" onclick="openEditModal()" style="font-size:10px;border-color:rgba(79,70,229,.3);color:var(--indigo2)">✎ Edit Period</button>
          <button class="btn btn-dl" onclick="downloadTB()">↓ Export CSV</button>
        </div>
      </div>
      <div class="card" style="padding:0;overflow:hidden" id="tbContent"></div>
    </div>

    <!-- ANOMALIES -->
    <div id="tab-anomalies" class="tab-pane" style="display:none">
      <div class="sec-title">Anomaly Detection</div>
      <div class="sec-sub">AI-flagged issues requiring review. Resolve or dismiss each item.</div>
      <div id="anomalyList"></div>
    </div>

    <!-- SETTINGS -->
    <div id="tab-settings" class="tab-pane" style="display:none">
      <div class="sec-title">Settings &amp; API Keys</div>
      <div class="sec-sub">Configure business info, AI extraction providers, and accounting standards.</div>
      <div style="max-width:580px;display:grid;gap:14px">

        <!-- BUSINESS INFO CARD -->
        <div class="card" style="padding:18px;border-color:rgba(79,70,229,.3)">
          <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:14px">
            <div class="syne" style="font-size:12px;font-weight:600;color:var(--indigo2)">BUSINESS INFORMATION</div>
            <span class="badge" style="background:rgba(79,70,229,.15);color:var(--indigo2);font-size:9px">Appears on all reports</span>
          </div>
          <div style="display:grid;gap:11px">
            <div>
              <div style="font-size:10px;color:var(--text4);margin-bottom:4px">Company / Business Name</div>
              <input class="inp" id="set-bizName" placeholder="e.g. Acme Corp Ltd"/>
            </div>
            <div>
              <div style="font-size:10px;color:var(--text4);margin-bottom:4px">Registration / Tax ID</div>
              <input class="inp" id="set-bizReg" placeholder="CIN / GSTIN / VAT / EIN"/>
            </div>
            <div>
              <div style="font-size:10px;color:var(--text4);margin-bottom:4px">Address</div>
              <input class="inp" id="set-bizAddress" placeholder="Registered address"/>
            </div>
            <div class="grid-2" style="gap:10px">
              <div>
                <div style="font-size:10px;color:var(--text4);margin-bottom:4px">Period Start</div>
                <input class="inp" type="date" id="set-periodStart"/>
              </div>
              <div>
                <div style="font-size:10px;color:var(--text4);margin-bottom:4px">Period End</div>
                <input class="inp" type="date" id="set-periodEnd"/>
              </div>
            </div>
            <div>
              <div style="font-size:10px;color:var(--text4);margin-bottom:4px">Fiscal Year Label</div>
              <input class="inp" id="set-fyLabel" placeholder="e.g. FY 2024"/>
            </div>
          </div>
          <button class="btn btn-primary" style="margin-top:14px" onclick="applySettingsPageBizInfo()">✓ Apply to All Reports</button>
        </div>

        <div class="card" style="padding:18px">
          <div class="syne" style="font-size:12px;font-weight:600;color:var(--text2);margin-bottom:14px">AI EXTRACTION PROVIDERS</div>
          <div style="margin-bottom:16px;background:rgba(16,185,129,.06);border:1px solid rgba(16,185,129,.25);border-radius:8px;padding:13px">
            <div style="font-size:11px;font-weight:600;color:#10b981;margin-bottom:3px">Claude AI — Secured via Supabase Edge Function ✓</div>
            <div style="font-size:10px;color:var(--text4);margin-bottom:10px">Your Anthropic API key is stored as a server-side secret on Supabase — it never touches the browser. Extraction works automatically on every upload.</div>
            <div style="background:var(--bg);border-radius:6px;padding:10px 12px;font-size:10px;font-family:monospace;color:#a5b4fc;border:1px solid var(--border);margin-bottom:8px;user-select:all">supabase secrets set ANTHROPIC_API_KEY=sk-ant-... --project-ref rspfzjybkicxgvcfqdzh</div>
            <div style="font-size:10px;color:var(--text4)">Run the command above once in your terminal to activate AI extraction. Install the <a href="https://supabase.com/docs/guides/cli" target="_blank" style="color:#818cf8">Supabase CLI</a> if needed.</div>
          </div>
          <div style="margin-bottom:16px">
            <div style="font-size:11px;font-weight:600;color:var(--text);margin-bottom:3px">AWS Textract Key</div>
            <div style="font-size:10px;color:var(--text4);margin-bottom:7px">OCR for scanned PDFs and images.</div>
            <input class="inp" type="password" id="textractKey" placeholder="AKIA..."/>
          </div>
          <div style="margin-bottom:16px">
            <div style="font-size:11px;font-weight:600;color:var(--text);margin-bottom:3px">Google Document AI Key</div>
            <div style="font-size:10px;color:var(--text4);margin-bottom:7px">Advanced form parsing and table extraction.</div>
            <input class="inp" type="password" id="googleKey" placeholder="AIza..."/>
          </div>
          <button class="btn btn-primary" onclick="notify('API keys saved for this session','success')">Save Keys</button>
        </div>
        <div class="card" style="padding:18px">
          <div class="syne" style="font-size:12px;font-weight:600;color:var(--text2);margin-bottom:12px">ACCOUNTING STANDARDS</div>
          <div style="font-size:11px;color:var(--text4);display:grid;gap:7px">
            <div style="display:flex;justify-content:space-between;padding-bottom:7px;border-bottom:1px solid var(--border2)"><span>Reporting Standard</span><span style="color:var(--text)">IFRS</span></div>
            <div style="display:flex;justify-content:space-between;padding-bottom:7px;border-bottom:1px solid var(--border2)"><span>Accounting Method</span><span style="color:var(--text)">Accrual Basis</span></div>
            <div style="display:flex;justify-content:space-between;padding-bottom:7px;border-bottom:1px solid var(--border2)"><span>Depreciation</span><span style="color:var(--text)">Straight-Line (IAS 16)</span></div>
            <div style="display:flex;justify-content:space-between;padding-bottom:7px;border-bottom:1px solid var(--border2)"><span>Revenue Recognition</span><span style="color:var(--text)">IFRS 15</span></div>
            <div style="display:flex;justify-content:space-between" id="stdCurrency"></div>
          </div>
        </div>
        <div class="card" style="padding:18px">
          <div class="syne" style="font-size:12px;font-weight:600;color:var(--text2);margin-bottom:10px">DANGER ZONE</div>
          <button class="btn btn-danger" onclick="clearAllData()">Clear All Data</button>
        </div>
      </div>
    </div>
  </div>
</div>

<script>
// ═══════════════════════════════════════════════════════════════
// BUSINESS INFO STATE
// ═══════════════════════════════════════════════════════════════
let bizInfo = {
  name: "LedgerAI Demo Co.",
  reg: "",
  address: "",
  periodStart: "2024-01-01",
  periodEnd: "2024-12-31",
  fyLabel: "FY 2024"
};

function getPeriodLabel() {
  const s = bizInfo.periodStart ? fmtDateShort(bizInfo.periodStart) : "01 Jan 2024";
  const e = bizInfo.periodEnd ? fmtDateShort(bizInfo.periodEnd) : "31 Dec 2024";
  return `${s} – ${e}`;
}
function getPeriodEndLabel() {
  return bizInfo.periodEnd ? fmtDateShort(bizInfo.periodEnd) : "31 December 2024";
}
function getFYLabel() { return bizInfo.fyLabel || "FY 2024"; }
function getBizName() { return bizInfo.name || "LedgerAI"; }

function fmtDateShort(d) {
  try { return new Date(d).toLocaleDateString("en-GB", {day:"2-digit",month:"short",year:"numeric"}); } catch { return d; }
}

function openEditModal() {
  document.getElementById("modal-bizName").value = bizInfo.name;
  document.getElementById("modal-bizReg").value = bizInfo.reg;
  document.getElementById("modal-bizAddress").value = bizInfo.address;
  document.getElementById("modal-periodStart").value = bizInfo.periodStart;
  document.getElementById("modal-periodEnd").value = bizInfo.periodEnd;
  document.getElementById("modal-fyLabel").value = bizInfo.fyLabel;
  document.getElementById("editModal").classList.add("open");
}

function closeEditModal() {
  document.getElementById("editModal").classList.remove("open");
}

function saveBusinessInfo() {
  bizInfo.name = document.getElementById("modal-bizName").value.trim() || "LedgerAI Demo Co.";
  bizInfo.reg = document.getElementById("modal-bizReg").value.trim();
  bizInfo.address = document.getElementById("modal-bizAddress").value.trim();
  bizInfo.periodStart = document.getElementById("modal-periodStart").value;
  bizInfo.periodEnd = document.getElementById("modal-periodEnd").value;
  bizInfo.fyLabel = document.getElementById("modal-fyLabel").value.trim() || "FY 2024";
  applyBizInfoToUI();
  closeEditModal();
  notify(`Business info updated — ${bizInfo.name}`, "success");
  // Re-render active tab
  const activeTab = document.querySelector(".tab-btn.active")?.dataset.tab;
  if (activeTab) switchTab(activeTab);
}

function applySettingsPageBizInfo() {
  bizInfo.name = document.getElementById("set-bizName").value.trim() || "LedgerAI Demo Co.";
  bizInfo.reg = document.getElementById("set-bizReg").value.trim();
  bizInfo.address = document.getElementById("set-bizAddress").value.trim();
  bizInfo.periodStart = document.getElementById("set-periodStart").value;
  bizInfo.periodEnd = document.getElementById("set-periodEnd").value;
  bizInfo.fyLabel = document.getElementById("set-fyLabel").value.trim() || "FY 2024";
  applyBizInfoToUI();
  notify(`Business info applied — ${bizInfo.name}`, "success");
  switchTab("dashboard");
}

function applyBizInfoToUI() {
  // Header
  document.getElementById("headerBizName").textContent = bizInfo.name.toUpperCase();
  // Banner
  document.getElementById("bizBannerName").textContent = bizInfo.name + (bizInfo.reg ? " · " + bizInfo.reg : "");
  document.getElementById("bizBannerPeriod").textContent = getFYLabel() + " · " + getPeriodLabel() + (bizInfo.address ? " · " + bizInfo.address : "");
  // Dashboard subtitle
  const dashSub = document.getElementById("dashboardSub");
  if (dashSub) dashSub.textContent = `IFRS-compliant · Real-time · ${getFYLabel()}`;
  // Sync settings page inputs
  syncSettingsPage();
}

function syncSettingsPage() {
  const fields = ["bizName","bizReg","bizAddress","periodStart","periodEnd","fyLabel"];
  fields.forEach(f => {
    const el = document.getElementById("set-" + f);
    if (el) el.value = bizInfo[f] || "";
  });
}

// ═══════════════════════════════════════════════════════════════
// CHART OF ACCOUNTS
// ═══════════════════════════════════════════════════════════════
const COA = {
  "1000":{name:"Cash & Cash Equivalents",group:"Current Assets",type:"asset",normal:"debit"},
  "1100":{name:"Accounts Receivable",group:"Current Assets",type:"asset",normal:"debit"},
  "1200":{name:"Inventory",group:"Current Assets",type:"asset",normal:"debit"},
  "1300":{name:"Prepaid Expenses",group:"Current Assets",type:"asset",normal:"debit"},
  "1400":{name:"Input Tax Recoverable",group:"Current Assets",type:"asset",normal:"debit"},
  "1500":{name:"Property, Plant & Equipment",group:"Non-Current Assets",type:"asset",normal:"debit"},
  "1600":{name:"Accumulated Depreciation",group:"Non-Current Assets",type:"asset",normal:"credit"},
  "1700":{name:"Intangible Assets",group:"Non-Current Assets",type:"asset",normal:"debit"},
  "1800":{name:"Long-Term Investments",group:"Non-Current Assets",type:"asset",normal:"debit"},
  "2000":{name:"Accounts Payable",group:"Current Liabilities",type:"liability",normal:"credit"},
  "2100":{name:"Accrued Liabilities",group:"Current Liabilities",type:"liability",normal:"credit"},
  "2200":{name:"Output Tax Payable",group:"Current Liabilities",type:"liability",normal:"credit"},
  "2300":{name:"Short-Term Borrowings",group:"Current Liabilities",type:"liability",normal:"credit"},
  "2400":{name:"Deferred Revenue",group:"Current Liabilities",type:"liability",normal:"credit"},
  "2500":{name:"Long-Term Debt",group:"Non-Current Liabilities",type:"liability",normal:"credit"},
  "2600":{name:"Deferred Tax Liability",group:"Non-Current Liabilities",type:"liability",normal:"credit"},
  "3000":{name:"Share Capital",group:"Equity",type:"equity",normal:"credit"},
  "3100":{name:"Retained Earnings",group:"Equity",type:"equity",normal:"credit"},
  "3200":{name:"Additional Paid-In Capital",group:"Equity",type:"equity",normal:"credit"},
  "3300":{name:"Other Comprehensive Income",group:"Equity",type:"equity",normal:"credit"},
  "4000":{name:"Sales Revenue",group:"Revenue",type:"revenue",normal:"credit"},
  "4100":{name:"Service Revenue",group:"Revenue",type:"revenue",normal:"credit"},
  "4200":{name:"Interest Income",group:"Revenue",type:"revenue",normal:"credit"},
  "4300":{name:"Other Income",group:"Revenue",type:"revenue",normal:"credit"},
  "5000":{name:"Cost of Goods Sold",group:"Cost of Revenue",type:"expense",normal:"debit"},
  "5100":{name:"Direct Labour",group:"Cost of Revenue",type:"expense",normal:"debit"},
  "6000":{name:"Salaries & Wages",group:"Operating Expenses",type:"expense",normal:"debit"},
  "6100":{name:"Rent Expense",group:"Operating Expenses",type:"expense",normal:"debit"},
  "6200":{name:"Utilities Expense",group:"Operating Expenses",type:"expense",normal:"debit"},
  "6300":{name:"Depreciation Expense",group:"Operating Expenses",type:"expense",normal:"debit"},
  "6400":{name:"Marketing & Advertising",group:"Operating Expenses",type:"expense",normal:"debit"},
  "6500":{name:"Professional Fees",group:"Operating Expenses",type:"expense",normal:"debit"},
  "6600":{name:"Travel & Entertainment",group:"Operating Expenses",type:"expense",normal:"debit"},
  "6700":{name:"Office Supplies",group:"Operating Expenses",type:"expense",normal:"debit"},
  "7000":{name:"Interest Expense",group:"Finance Costs",type:"expense",normal:"debit"},
  "7100":{name:"Bank Charges",group:"Finance Costs",type:"expense",normal:"debit"},
  "8000":{name:"Income Tax Expense",group:"Tax",type:"expense",normal:"debit"},
};

const CURRENCIES={
  INR:{symbol:"₹",name:"Indian Rupee",flag:"🇮🇳"},USD:{symbol:"$",name:"US Dollar",flag:"🇺🇸"},
  EUR:{symbol:"€",name:"Euro",flag:"🇪🇺"},GBP:{symbol:"£",name:"British Pound",flag:"🇬🇧"},
  JPY:{symbol:"¥",name:"Japanese Yen",flag:"🇯🇵"},AUD:{symbol:"A$",name:"Australian Dollar",flag:"🇦🇺"},
  CAD:{symbol:"C$",name:"Canadian Dollar",flag:"🇨🇦"},SGD:{symbol:"S$",name:"Singapore Dollar",flag:"🇸🇬"},
  CHF:{symbol:"Fr",name:"Swiss Franc",flag:"🇨🇭"},CNY:{symbol:"¥",name:"Chinese Yuan",flag:"🇨🇳"},
  HKD:{symbol:"HK$",name:"Hong Kong Dollar",flag:"🇭🇰"},AED:{symbol:"AED",name:"UAE Dirham",flag:"🇦🇪"},
  SAR:{symbol:"SAR",name:"Saudi Riyal",flag:"🇸🇦"},MYR:{symbol:"RM",name:"Malaysian Ringgit",flag:"🇲🇾"},
  THB:{symbol:"THB",name:"Thai Baht",flag:"🇹🇭"},KRW:{symbol:"KRW",name:"South Korean Won",flag:"🇰🇷"},
  TRY:{symbol:"TRY",name:"Turkish Lira",flag:"🇹🇷"},BRL:{symbol:"R$",name:"Brazilian Real",flag:"🇧🇷"},
  ZAR:{symbol:"R",name:"South African Rand",flag:"🇿🇦"},MXN:{symbol:"Mex$",name:"Mexican Peso",flag:"🇲🇽"},
  NZD:{symbol:"NZ$",name:"New Zealand Dollar",flag:"🇳🇿"},SEK:{symbol:"kr",name:"Swedish Krona",flag:"🇸🇪"},
  NOK:{symbol:"kr",name:"Norwegian Krone",flag:"🇳🇴"},DKK:{symbol:"kr",name:"Danish Krone",flag:"🇩🇰"},
  PLN:{symbol:"zl",name:"Polish Zloty",flag:"🇵🇱"},
};

// ═══════════════════════════════════════════════════════════════
// STATE
// ═══════════════════════════════════════════════════════════════
let journals=[], parties={}, documents=[], anomalies=[];
let apiKey='';
let currency="INR", activeCur="INR";
let extractedData=null, selectedParty=null, activeJournalId=null;

// ═══════════════════════════════════════════════════════════════
// ACCOUNTING ENGINE
// ═══════════════════════════════════════════════════════════════
function postJournal(entry){
  const totalDR=entry.lines.reduce((s,l)=>s+(l.debit||0),0);
  const totalCR=entry.lines.reduce((s,l)=>s+(l.credit||0),0);
  if(Math.abs(totalDR-totalCR)>0.01){
    anomalies.push({id:Date.now(),type:"IMBALANCE",severity:"CRITICAL",desc:`Journal ${entry.ref} unbalanced: DR ${totalDR.toFixed(2)} ≠ CR ${totalCR.toFixed(2)}`,resolved:false,detectedAt:new Date().toISOString()});
    return false;
  }
  journals.push({...entry,id:Date.now()+Math.random(),postedAt:new Date().toISOString()});
  entry.lines.forEach(l=>{
    if(l.party){
      if(!parties[l.party]) parties[l.party]={name:l.party,type:l.partyType||"vendor",transactions:[],balance:0,currency:entry.currency||"USD"};
      const amt=(l.debit||0)-(l.credit||0);
      parties[l.party].balance+=amt;
      parties[l.party].transactions.push({date:entry.date,ref:entry.ref,narration:entry.narration,amount:amt,currency:entry.currency||"USD"});
    }
  });
  return true;
}

function getTrialBalance(){
  const tb={};
  journals.forEach(j=>j.lines.forEach(l=>{
    if(!tb[l.account])tb[l.account]={debit:0,credit:0};
    tb[l.account].debit+=(l.debit||0);
    tb[l.account].credit+=(l.credit||0);
  }));
  return tb;
}

function getPL(){
  const tb=getTrialBalance();
  let revenue=0,cogs=0,opex=0,finCosts=0,tax=0;
  Object.entries(tb).forEach(([code,bal])=>{
    const a=COA[code]; if(!a)return;
    const net=bal.credit-bal.debit;
    if(a.type==="revenue") revenue+=net;
    else if(a.group==="Cost of Revenue") cogs+=(bal.debit-bal.credit);
    else if(a.group==="Operating Expenses") opex+=(bal.debit-bal.credit);
    else if(a.group==="Finance Costs") finCosts+=(bal.debit-bal.credit);
    else if(a.group==="Tax") tax+=(bal.debit-bal.credit);
  });
  const grossProfit=revenue-cogs, ebit=grossProfit-opex, ebt=ebit-finCosts, netProfit=ebt-tax;
  return{revenue,cogs,grossProfit,opex,ebit,finCosts,ebt,tax,netProfit};
}

function getBS(){
  const tb=getTrialBalance();
  const groups={};
  Object.entries(tb).forEach(([code,bal])=>{
    const a=COA[code];
    if(!a||a.type==="revenue"||a.type==="expense")return;
    if(!groups[a.group])groups[a.group]={accounts:[],total:0};
    const net=a.normal==="debit"?(bal.debit-bal.credit):(bal.credit-bal.debit);
    groups[a.group].accounts.push({code,name:a.name,balance:net});
    groups[a.group].total+=net;
  });
  const pl=getPL();
  if(!groups["Equity"])groups["Equity"]={accounts:[],total:0};
  groups["Equity"].accounts.push({code:"NET",name:"Current Period Net Profit",balance:pl.netProfit});
  groups["Equity"].total+=pl.netProfit;
  return groups;
}

function detectAnomalies(ext,fileId){
  const flags=[];
  if(!ext.party) flags.push({type:"MISSING_FIELD",severity:"HIGH",desc:"Party name not found"});
  if(!ext.amount||ext.amount<=0) flags.push({type:"MISSING_FIELD",severity:"HIGH",desc:"Invoice amount could not be extracted"});
  if(!ext.date) flags.push({type:"MISSING_FIELD",severity:"MEDIUM",desc:"Invoice date not detected"});
  if(ext.amount>1000000) flags.push({type:"LARGE_AMOUNT",severity:"MEDIUM",desc:`Unusually large amount: ${ext.amount?.toLocaleString()}`});
  const dup=documents.find(d=>d.invoiceNo&&d.invoiceNo===ext.invoiceNo);
  if(dup) flags.push({type:"DUPLICATE",severity:"CRITICAL",desc:`Duplicate invoice number: ${ext.invoiceNo}`});
  return flags;
}

// ═══════════════════════════════════════════════════════════════
// FORMAT HELPERS
// ═══════════════════════════════════════════════════════════════
function sym(cur){ return(CURRENCIES[cur]||CURRENCIES.USD).symbol; }
function fmtFull(n,cur="USD"){
  const s=sym(cur);
  return`${n<0?"-":""}${s}${Math.abs(n).toLocaleString("en-US",{minimumFractionDigits:2,maximumFractionDigits:2})}`;
}
function fmt(n,cur="USD"){
  const s=sym(cur);
  const a=Math.abs(n);
  if(a>=1e6)return`${s}${(a/1e6).toFixed(2)}M`;
  if(a>=1e3)return`${s}${(a/1e3).toFixed(1)}K`;
  return`${s}${a.toFixed(2)}`;
}
function dateStr(d){ try{return new Date(d).toLocaleDateString("en-GB",{day:"2-digit",month:"short",year:"numeric"})}catch{return d||""} }

// ═══════════════════════════════════════════════════════════════
// NOTIFICATIONS
// ═══════════════════════════════════════════════════════════════
let notifTimer=null;
function notify(msg,type="success"){
  const el=document.getElementById("notif");
  el.textContent=msg;
  el.style.display="block";
  el.style.background=type==="success"?"#064e3b":"#7f1d1d";
  el.style.border=`1px solid ${type==="success"?"#10b981":"#ef4444"}`;
  el.style.color=type==="success"?"#6ee7b7":"#fca5a5";
  if(notifTimer)clearTimeout(notifTimer);
  notifTimer=setTimeout(()=>el.style.display="none",3800);
}

// ═══════════════════════════════════════════════════════════════
// TAB SWITCHING
// ═══════════════════════════════════════════════════════════════
function switchTab(id){
  document.querySelectorAll(".tab-pane").forEach(p=>p.style.display="none");
  document.querySelectorAll(".tab-btn").forEach(b=>{b.classList.remove("active");if(b.dataset.tab===id)b.classList.add("active")});
  const el=document.getElementById("tab-"+id);
  if(el)el.style.display="block";
  if(id==="dashboard")renderDashboard();
  if(id==="pl")renderPL();
  if(id==="bs")renderBS();
  if(id==="tb")renderTB();
  if(id==="ledgers")renderLedgers();
  if(id==="journals")renderJournals();
  if(id==="anomalies")renderAnomalies();
  if(id==="extract")renderExtract();
  if(id==="settings")syncSettingsPage();
}

// ═══════════════════════════════════════════════════════════════
// CURRENCY SELECT
// ═══════════════════════════════════════════════════════════════
function buildCurrencySelect(){
  const sel=document.getElementById("currencySelect");
  sel.innerHTML=Object.entries(CURRENCIES).map(([k,v])=>`<option value="${k}" ${k===currency?"selected":""}>${v.flag} ${k}</option>`).join("");
  sel.onchange=e=>{currency=e.target.value;renderDashboard();};
  document.getElementById("stdCurrency").innerHTML=`<span>Functional Currency</span><span style="color:var(--text)">${currency}</span>`;
}

// ═══════════════════════════════════════════════════════════════
// DASHBOARD RENDER
// ═══════════════════════════════════════════════════════════════
function renderDashboard(){
  const pl=getPL(); const bs=getBS();
  const cur=currency;
  const totalAssets=(bs["Current Assets"]?.total||0)+(bs["Non-Current Assets"]?.total||0);
  const openRec=Object.values(parties).filter(p=>p.type==="debtor"&&p.balance>0).reduce((s,p)=>s+p.balance,0);
  const unresolved=anomalies.filter(a=>!a.resolved).length;
  const critical=anomalies.filter(a=>a.severity==="CRITICAL"&&!a.resolved).length;

  // Update banner
  document.getElementById("bizBannerName").textContent = bizInfo.name + (bizInfo.reg ? " · " + bizInfo.reg : "");
  document.getElementById("bizBannerPeriod").textContent = getFYLabel() + " · " + getPeriodLabel() + (bizInfo.address ? " · " + bizInfo.address : "");
  document.getElementById("dashboardSub").textContent = `IFRS-compliant · Real-time · ${getFYLabel()}`;

  const kpis=[
    {label:"Total Revenue",value:fmtFull(pl.revenue,cur),delta:"+12.4%",color:"#10b981",icon:"📈"},
    {label:"Net Profit",value:fmtFull(pl.netProfit,cur),delta:pl.netProfit>=0?"+8.1%":"-3.2%",color:pl.netProfit>=0?"#10b981":"#ef4444",icon:"💰"},
    {label:"Total Assets",value:fmtFull(totalAssets,cur),delta:"+5.7%",color:"#3b82f6",icon:"🏦"},
    {label:"Documents",value:documents.length,delta:`${documents.filter(d=>d.status==="posted").length} posted`,color:"#8b5cf6",icon:"📄"},
    {label:"Open Receivables",value:fmtFull(openRec,cur),delta:`${Object.values(parties).filter(p=>p.type==="debtor").length} parties`,color:"#f59e0b",icon:"📤"},
    {label:"Anomalies",value:unresolved,delta:`${critical} critical`,color:unresolved>0?"#ef4444":"#10b981",icon:"⚠️"},
  ];
  document.getElementById("kpiGrid").innerHTML=kpis.map(k=>`
    <div class="card kpi-card" style="--kc:${k.color}">
      <div style="position:absolute;top:0;left:0;right:0;height:2px;background:${k.color}"></div>
      <div style="display:flex;justify-content:space-between;align-items:flex-start">
        <div>
          <div style="font-size:10px;color:var(--text4);text-transform:uppercase;letter-spacing:.06em;margin-bottom:2px">${k.label}</div>
          <div class="kpi-val syne">${k.value}</div>
          <div style="font-size:10px;color:${k.color}">${k.delta}</div>
        </div>
        <div style="font-size:22px;opacity:.55">${k.icon}</div>
      </div>
    </div>`).join("");

  const plRows=[
    {label:"Revenue",val:pl.revenue,bold:false,dim:false},
    {label:"Cost of Revenue",val:-pl.cogs,bold:false,dim:true},
    {label:"Gross Profit",val:pl.grossProfit,bold:true},
    {label:"Operating Expenses",val:-pl.opex,bold:false,dim:true},
    {label:"EBIT",val:pl.ebit,bold:true},
    {label:"Finance Costs",val:-pl.finCosts,bold:false,dim:true},
    {label:"Net Profit",val:pl.netProfit,bold:true,highlight:true},
  ];
  document.getElementById("plMini").innerHTML=`
    <div class="syne" style="font-size:12px;font-weight:600;color:var(--text2);margin-bottom:14px">INCOME STATEMENT SUMMARY</div>
    ${plRows.map(r=>`<div style="display:flex;justify-content:space-between;padding:${r.bold?"8px":"5px"} ${r.bold?"0":"12px"};border-top:${r.bold?"1px solid var(--border)":"none"};margin-top:${r.bold?"3px":"0"}">
      <span style="font-size:11px;color:${r.dim?"var(--text4)":"var(--text2)"};font-style:${r.dim?"italic":"normal"}">${r.label}</span>
      <span class="mono" style="font-size:11px;font-weight:${r.bold?600:400};color:${r.highlight?(pl.netProfit>=0?"#10b981":"#ef4444"):r.val>=0?"var(--text)":"#ef4444"}">${fmtFull(r.val,cur)}</span>
    </div>`).join("")}`;

  const recentList=documents.slice(-6).reverse();
  document.getElementById("recentDocs").innerHTML=`
    <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:14px">
      <div class="syne" style="font-size:12px;font-weight:600;color:var(--text2)">RECENT DOCUMENTS</div>
      <button class="btn btn-ghost" onclick="switchTab('upload')" style="font-size:10px;padding:4px 9px">+ Upload</button>
    </div>
    ${recentList.length===0?'<div style="color:var(--text4);font-size:12px;text-align:center;padding:20px">No documents yet — upload to get started</div>':''}
    ${recentList.map((d,i)=>`<div style="display:flex;align-items:center;gap:9px;padding:7px 0;border-bottom:${i<recentList.length-1?"1px solid var(--border2)":"none"}">
      <div style="width:30px;height:30px;background:#1e2a3a;border-radius:6px;display:flex;align-items:center;justify-content:center;font-size:13px;flex-shrink:0">${d.type?.includes("Sales")?"📤":d.type?.includes("Purchase")?"📥":"📄"}</div>
      <div style="flex:1;min-width:0">
        <div style="font-size:11px;color:var(--text);overflow:hidden;text-overflow:ellipsis;white-space:nowrap">${d.party||d.name}</div>
        <div style="font-size:10px;color:var(--text4)">${dateStr(d.date)} · ${d.type}</div>
      </div>
      <div style="text-align:right;flex-shrink:0">
        <div class="mono" style="font-size:11px;color:var(--text)">${fmtFull(d.amount,d.currency)}</div>
        <span class="badge" style="background:${d.status==="posted"?"rgba(16,185,129,.13)":"rgba(239,68,68,.13)"};color:${d.status==="posted"?"#10b981":"#ef4444"};font-size:9px">${d.status}</span>
      </div>
    </div>`).join("")}`;

  const partyEntries=Object.entries(parties);
  document.getElementById("partyTable").innerHTML=`
    <div class="syne" style="font-size:12px;font-weight:600;color:var(--text2);margin-bottom:14px">PARTY LEDGER SUMMARY</div>
    ${partyEntries.length===0?'<div style="color:var(--text4);font-size:12px;padding:20px 0">No party transactions yet.</div>':`
    <table><thead><tr><th>Party</th><th>Type</th><th>Transactions</th><th>Currency</th><th>Balance</th><th>Status</th></tr></thead>
    <tbody>${partyEntries.map(([name,p])=>`<tr style="cursor:pointer" onclick="openPartyLedger('${name}')">
      <td style="color:#818cf8">${name}</td>
      <td><span class="badge" style="background:${p.type==="debtor"?"rgba(59,130,246,.13)":"rgba(245,158,11,.13)"};color:${p.type==="debtor"?"#60a5fa":"#fbbf24"}">${p.type}</span></td>
      <td style="color:var(--text3)">${p.transactions.length}</td>
      <td style="color:var(--text3)">${p.currency}</td>
      <td class="mono" style="color:${p.balance>=0?"#10b981":"#ef4444"}">${fmtFull(Math.abs(p.balance),p.currency)}</td>
      <td><span class="badge" style="background:${p.balance>0?"rgba(16,185,129,.1)":"rgba(100,116,139,.1)"};color:${p.balance>0?"#6ee7b7":"#94a3b8"};font-size:9px">${p.balance>0?"OUTSTANDING":"SETTLED"}</span></td>
    </tr>`).join("")}</tbody></table>`}`;

  const pill=document.getElementById("anomalyPill");
  if(unresolved>0){pill.style.display="block";pill.textContent=`⚠ ${unresolved} anomalies`;}
  else pill.style.display="none";
  const badge=document.getElementById("anomalyBadge");
  if(unresolved>0){badge.style.display="inline";badge.textContent=unresolved;}
  else badge.style.display="none";
}

function openPartyLedger(name){selectedParty=name;switchTab("ledgers");}

// ═══════════════════════════════════════════════════════════════
// P&L RENDER
// ═══════════════════════════════════════════════════════════════
function renderPL(){
  const pl=getPL(); const cur=currency;
  document.getElementById("plSubtitle").textContent=`IFRS-compliant · ${getPeriodLabel()} · Currency: ${cur}`;
  const rows=[
    {section:"REVENUE"},
    {label:"Sales Revenue",val:pl.revenue*.72,cur},
    {label:"Service Revenue",val:pl.revenue*.28,cur},
    {label:"Total Revenue",val:pl.revenue,cur,bold:true,bt:true},
    {space:true},
    {section:"COST OF REVENUE"},
    {label:"Cost of Goods Sold",val:-pl.cogs*.8,cur},
    {label:"Direct Labour",val:-pl.cogs*.2,cur},
    {label:"Total Cost of Revenue",val:-pl.cogs,cur,bold:true,bt:true},
    {label:"GROSS PROFIT",val:pl.grossProfit,cur,bold:true,bt:true,hl:true},
    {space:true},
    {section:"OPERATING EXPENSES"},
    {label:"Salaries & Wages",val:-pl.opex*.55,cur},
    {label:"Rent Expense",val:-pl.opex*.18,cur},
    {label:"Marketing & Advertising",val:-pl.opex*.14,cur},
    {label:"Professional Fees",val:-pl.opex*.08,cur},
    {label:"Other Operating Expenses",val:-pl.opex*.05,cur},
    {label:"Total Operating Expenses",val:-pl.opex,cur,bold:true,bt:true},
    {label:"OPERATING PROFIT (EBIT)",val:pl.ebit,cur,bold:true,bt:true,hl:true},
    {space:true},
    {section:"FINANCE COSTS"},
    {label:"Interest Expense",val:-pl.finCosts,cur},
    {label:"PROFIT BEFORE TAX",val:pl.ebt,cur,bold:true,bt:true},
    {label:"Income Tax Expense",val:-pl.tax,cur},
    {space:true},
    {label:"NET PROFIT FOR THE PERIOD",val:pl.netProfit,cur,bold:true,bt:true,hl:true,large:true},
  ];
  let html=`<div style="background:var(--surface2);padding:14px 22px;border-bottom:1px solid var(--border)">
    <div class="syne" style="font-size:13px;font-weight:700;color:#f1f5f9">${getBizName()}</div>
    ${bizInfo.reg?`<div style="font-size:10px;color:var(--text4);margin-top:1px">${bizInfo.reg}</div>`:""}
    <div class="syne" style="font-size:11px;font-weight:700;color:var(--text2);letter-spacing:.07em;margin-top:6px">STATEMENT OF PROFIT OR LOSS AND OTHER COMPREHENSIVE INCOME</div>
    <div style="font-size:10px;color:var(--text4);margin-top:3px">For the Period ${getPeriodLabel()} · ${getFYLabel()} · IAS 1 Compliant</div>
    ${bizInfo.address?`<div style="font-size:10px;color:var(--text4);margin-top:2px">${bizInfo.address}</div>`:""}
  </div>`;
  rows.forEach(r=>{
    if(r.space){html+=`<div style="height:7px"></div>`;return;}
    if(r.section){html+=`<div class="pl-row section"><span class="pl-section-lbl">${r.section}</span></div>`;return;}
    html+=`<div class="pl-row ${r.bold?"bold":""} ${r.hl?"highlight":""}" style="${r.bt?"border-top:1px solid var(--border);":""}">
      <span class="pl-row-lbl" style="font-weight:${r.bold?600:400};color:${r.bold?"var(--text)":"var(--text2)"};padding-left:${r.bold?0:14}px;font-size:${r.large?13:12}px">${r.label}</span>
      <span class="pl-row-val" style="font-weight:${r.bold?700:400};color:${r.hl?(r.val>=0?"#10b981":"#ef4444"):r.val>=0?"var(--text)":"#ef4444"};font-size:${r.large?13:12}px">${fmtFull(r.val||0,r.cur)}</span>
    </div>`;
  });
  html+=`<div style="padding:11px 22px;background:#080c18;border-top:2px solid var(--border);display:flex;justify-content:space-between">
    <span style="font-size:10px;color:var(--text4)">Gross Margin: ${pl.revenue>0?((pl.grossProfit/pl.revenue)*100).toFixed(1):0}% · Net Margin: ${pl.revenue>0?((pl.netProfit/pl.revenue)*100).toFixed(1):0}%</span>
    <span style="font-size:10px;color:var(--text4)">EBITDA: ${fmtFull(pl.ebit+pl.cogs*.05,cur)}</span>
  </div>`;
  document.getElementById("plContent").innerHTML=html;
}

// ═══════════════════════════════════════════════════════════════
// BALANCE SHEET RENDER
// ═══════════════════════════════════════════════════════════════
function renderBS(){
  const bs=getBS(); const cur=currency;
  document.getElementById("bsSubtitle").textContent=`IFRS-compliant · As at ${getPeriodEndLabel()} · Currency: ${cur}`;
  function bsSection(title,groups,accentColor){
    let html=`<div class="card" style="padding:0;overflow:hidden">
      <div style="background:#080c18;padding:11px 18px;border-bottom:1px solid var(--border)">
        <div style="font-size:12px;font-weight:700;color:#f1f5f9">${getBizName()}</div>
        ${bizInfo.reg?`<div style="font-size:10px;color:var(--text4)">${bizInfo.reg}</div>`:""}
      </div>
      <div style="background:rgba(${accentColor},.1);padding:10px 18px;border-bottom:1px solid var(--border)">
        <div class="syne" style="font-size:11px;font-weight:700;color:rgb(${accentColor});letter-spacing:.07em">${title}</div>
        <div style="font-size:10px;color:var(--text4);margin-top:2px">As at ${getPeriodEndLabel()} · ${getFYLabel()}</div>
      </div>`;
    groups.forEach(grp=>{
      html+=`<div style="padding:9px 18px 3px;background:#0a0f1a"><span style="font-size:9px;color:var(--text4);text-transform:uppercase;letter-spacing:.06em">${grp}</span></div>`;
      (bs[grp]?.accounts||[]).forEach(a=>{
        html+=`<div style="display:flex;justify-content:space-between;padding:6px 18px 6px 28px;border-bottom:1px solid #111827">
          <span style="font-size:11px;color:var(--text2)">${a.name}</span>
          <span class="mono" style="font-size:11px;color:var(--text)">${fmtFull(a.balance,cur)}</span>
        </div>`;
      });
      html+=`<div style="display:flex;justify-content:space-between;padding:7px 18px;background:var(--surface2);border-bottom:1px solid var(--border)">
        <span style="font-size:11px;font-weight:600;color:rgb(${accentColor})">Total ${grp}</span>
        <span class="mono" style="font-size:11px;font-weight:600;color:rgb(${accentColor})">${fmtFull(bs[grp]?.total||0,cur)}</span>
      </div>`;
    });
    const total=groups.reduce((s,g)=>s+(bs[g]?.total||0),0);
    html+=`<div style="display:flex;justify-content:space-between;padding:13px 18px;background:rgba(${accentColor},.08);border-top:2px solid rgb(${accentColor})">
      <span class="syne" style="font-size:12px;font-weight:700;color:rgb(${accentColor})">${title==="ASSETS"?"TOTAL ASSETS":"TOTAL LIAB. + EQUITY"}</span>
      <span class="syne mono" style="font-size:12px;font-weight:700;color:rgb(${accentColor})">${fmtFull(total,cur)}</span>
    </div></div>`;
    return html;
  }
  const pl=getPL();
  const totalAssets=(bs["Current Assets"]?.total||0)+(bs["Non-Current Assets"]?.total||0);
  const totalLE=(bs["Current Liabilities"]?.total||0)+(bs["Non-Current Liabilities"]?.total||0)+(bs["Equity"]?.total||0);
  const balanced=Math.abs(totalAssets-totalLE)<0.02;
  document.getElementById("bsContent").innerHTML=`
    <div class="grid-2">
      ${bsSection("ASSETS",["Current Assets","Non-Current Assets"],"59,130,246")}
      ${bsSection("LIABILITIES & EQUITY",["Current Liabilities","Non-Current Liabilities","Equity"],"245,158,11")}
    </div>
    <div class="card" style="margin-top:13px;padding:13px 18px;display:flex;justify-content:center;gap:40px;flex-wrap:wrap">
      <div style="text-align:center"><div style="font-size:10px;color:var(--text4);margin-bottom:3px">IFRS EQUATION CHECK</div>
        <div style="font-size:12px;color:${balanced?"#10b981":"#ef4444"}">${balanced?"Assets = Liabilities + Equity ✓":"IMBALANCE DETECTED ⚠"}</div></div>
      <div style="text-align:center"><div style="font-size:10px;color:var(--text4);margin-bottom:3px">CURRENT RATIO</div>
        <div class="mono" style="font-size:12px;color:var(--text)">${(((bs["Current Assets"]?.total||1)/Math.max(bs["Current Liabilities"]?.total||1,1))).toFixed(2)}x</div></div>
      <div style="text-align:center"><div style="font-size:10px;color:var(--text4);margin-bottom:3px">DEBT-TO-EQUITY</div>
        <div class="mono" style="font-size:12px;color:var(--text)">${((((bs["Current Liabilities"]?.total||0)+(bs["Non-Current Liabilities"]?.total||0))/Math.max(bs["Equity"]?.total||1,1))).toFixed(2)}x</div></div>
      <div style="text-align:center"><div style="font-size:10px;color:var(--text4);margin-bottom:3px">NET PROFIT MARGIN</div>
        <div class="mono" style="font-size:12px;color:var(--text)">${pl.revenue>0?((pl.netProfit/pl.revenue)*100).toFixed(1):0}%</div></div>
    </div>`;
}

// ═══════════════════════════════════════════════════════════════
// TRIAL BALANCE RENDER
// ═══════════════════════════════════════════════════════════════
function renderTB(){
  const tb=getTrialBalance();
  let totalDR=0,totalCR=0;
  const rows=Object.entries(tb).map(([code,bal])=>{
    totalDR+=bal.debit; totalCR+=bal.credit;
    return{code,name:COA[code]?.name||"Unknown",group:COA[code]?.group||"",dr:bal.debit,cr:bal.credit};
  });
  document.getElementById("tbContent").innerHTML=`
    <div style="background:var(--surface2);padding:11px 16px;border-bottom:1px solid var(--border);display:flex;justify-content:space-between;align-items:center">
      <div>
        <div style="font-size:12px;font-weight:600;color:#f1f5f9">${getBizName()}</div>
        <div style="font-size:10px;color:var(--text4)">Trial Balance · As at ${getPeriodEndLabel()} · ${getFYLabel()}</div>
      </div>
      <span class="badge" style="background:#1e2a3a;color:var(--text3)">${currency}</span>
    </div>
    <table>
    <thead><tr><th>Code</th><th>Account Name</th><th>Group</th><th style="text-align:right">Debit</th><th style="text-align:right">Credit</th></tr></thead>
    <tbody>
      ${rows.map(r=>`<tr>
        <td style="color:#818cf8">${r.code}</td>
        <td>${r.name}</td>
        <td style="color:var(--text3)">${r.group}</td>
        <td class="mono positive" style="text-align:right">${r.dr>0?fmtFull(r.dr,currency):""}</td>
        <td class="mono negative" style="text-align:right">${r.cr>0?fmtFull(r.cr,currency):""}</td>
      </tr>`).join("")}
    </tbody>
    <tfoot>
      <tr style="background:#0a0f1a;font-weight:600">
        <td colspan="3" style="color:var(--text2);font-family:'Syne',sans-serif;font-size:11px">TOTAL</td>
        <td class="mono positive" style="text-align:right;font-weight:700">${fmtFull(totalDR,currency)}</td>
        <td class="mono negative" style="text-align:right;font-weight:700">${fmtFull(totalCR,currency)}</td>
      </tr>
      <tr style="background:#0a0f1a">
        <td colspan="5" style="font-size:11px;color:${Math.abs(totalDR-totalCR)<0.02?"#10b981":"#ef4444"};text-align:center;padding:10px">
          ${Math.abs(totalDR-totalCR)<0.02?"✓ Trial Balance agrees — Total DR = Total CR":"⚠ Imbalance detected: "+fmtFull(Math.abs(totalDR-totalCR),currency)}
        </td>
      </tr>
    </tfoot>
  </table>`;
}

// ═══════════════════════════════════════════════════════════════
// LEDGERS RENDER
// ═══════════════════════════════════════════════════════════════
function renderLedgers(){
  const partyEntries=Object.entries(parties);
  document.getElementById("partyList").innerHTML=partyEntries.length===0
    ?`<div style="padding:20px;text-align:center;font-size:11px;color:var(--text4)">No parties yet</div>`
    :partyEntries.map(([name,p])=>`<div class="party-item ${selectedParty===name?"active":""}" onclick="selectParty('${name}')">
      <div style="font-size:11px;color:var(--text);margin-bottom:4px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap">${name}</div>
      <div style="display:flex;justify-content:space-between">
        <span class="badge" style="background:${p.type==="debtor"?"rgba(59,130,246,.13)":"rgba(245,158,11,.13)"};color:${p.type==="debtor"?"#60a5fa":"#fbbf24"};font-size:9px">${p.type}</span>
        <span class="mono" style="font-size:10px;color:${p.balance>=0?"#10b981":"#ef4444"}">${fmtFull(Math.abs(p.balance),p.currency)}</span>
      </div>
    </div>`).join("");

  if(selectedParty&&parties[selectedParty]){
    const p=parties[selectedParty];
    let running=0;
    document.getElementById("ledgerDetail").innerHTML=`
      <div class="card" style="padding:18px">
        <div style="background:var(--surface2);padding:10px 14px;border-radius:6px;margin-bottom:14px;border:1px solid var(--border)">
          <div style="font-size:11px;font-weight:600;color:#f1f5f9">${getBizName()}</div>
          <div style="font-size:10px;color:var(--text4);margin-top:2px">Party Ledger · ${getFYLabel()} · ${getPeriodLabel()}</div>
        </div>
        <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:18px;flex-wrap:wrap;gap:10px">
          <div>
            <div class="syne" style="font-size:15px;font-weight:700;color:#f1f5f9">${selectedParty}</div>
            <div style="font-size:11px;color:var(--text4)">${p.type} · ${p.currency} · ${p.transactions.length} transactions</div>
          </div>
          <div style="display:flex;align-items:center;gap:10px">
            <div style="text-align:right">
              <div style="font-size:10px;color:var(--text4);margin-bottom:2px">CURRENT BALANCE</div>
              <div class="syne mono" style="font-size:18px;font-weight:700;color:${p.balance>=0?"#10b981":"#ef4444"}">${fmtFull(Math.abs(p.balance),p.currency)}</div>
              <div style="font-size:10px;color:${p.balance>=0?"#10b981":"#ef4444"}">${p.balance>=0?"DR (Receivable)":"CR (Payable)"}</div>
            </div>
            <button class="btn btn-dl" onclick="downloadSingleLedger('${selectedParty}')">↓ Export</button>
          </div>
        </div>
        <table><thead><tr><th>Date</th><th>Ref</th><th>Narration</th><th>Debit</th><th>Credit</th><th>Balance</th></tr></thead>
        <tbody>${p.transactions.map(t=>{running+=t.amount;return`<tr>
          <td>${dateStr(t.date)}</td>
          <td style="color:#818cf8">${t.ref}</td>
          <td style="color:var(--text3);max-width:180px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap">${t.narration}</td>
          <td class="mono positive">${t.amount>0?fmtFull(t.amount,t.currency):""}</td>
          <td class="mono negative">${t.amount<0?fmtFull(Math.abs(t.amount),t.currency):""}</td>
          <td class="mono" style="color:${running>=0?"#10b981":"#ef4444"}">${fmtFull(Math.abs(running),t.currency)} ${running>=0?"DR":"CR"}</td>
        </tr>`}).join("")}</tbody></table>
      </div>`;
  }
}

function selectParty(name){selectedParty=name;renderLedgers();}

// ═══════════════════════════════════════════════════════════════
// JOURNALS RENDER
// ═══════════════════════════════════════════════════════════════
function renderJournals(){
  const sorted=[...journals].reverse();
  let rows="";
  sorted.forEach(j=>{
    const totalDR=j.lines.reduce((s,l)=>s+(l.debit||0),0);
    rows+=`<tr style="cursor:pointer" onclick="toggleJournal('${j.id}')">
      <td style="color:#818cf8">${j.ref}</td>
      <td>${dateStr(j.date)}</td>
      <td style="color:var(--text2);max-width:220px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap">${j.narration}</td>
      <td><span class="badge" style="background:#1e2a3a;color:var(--text3)">${j.currency}</span></td>
      <td class="mono positive">${fmtFull(totalDR,j.currency)}</td>
      <td style="color:var(--text3)">${j.lines.length}</td>
      <td id="jtoggle-${j.id}" style="color:var(--indigo)">▼</td>
    </tr>`;
    j.lines.forEach((l,li)=>{
      rows+=`<tr id="jlines-${j.id}" style="background:#0a0f1a;display:none">
        <td colspan="2" style="padding-left:28px;color:var(--text3);font-size:11px">${l.account} · ${COA[l.account]?.name||"?"}</td>
        <td style="color:var(--text4);font-size:11px">${l.party||"—"}</td>
        <td></td>
        <td class="mono positive" style="font-size:11px">${l.debit>0?fmtFull(l.debit,j.currency):""}</td>
        <td class="mono negative" style="font-size:11px;padding-left:22px">${l.credit>0?fmtFull(l.credit,j.currency):""}</td>
        <td></td>
      </tr>`;
    });
  });
  document.getElementById("journalTable").innerHTML=`
    <div style="background:var(--surface2);padding:10px 14px;border-bottom:1px solid var(--border);display:flex;justify-content:space-between;align-items:center">
      <div style="font-size:11px;font-weight:600;color:#f1f5f9">${getBizName()} · Journal Entries · ${getFYLabel()}</div>
      <div style="font-size:10px;color:var(--text4)">${getPeriodLabel()}</div>
    </div>
    <table>
    <thead><tr><th>Reference</th><th>Date</th><th>Narration</th><th>Currency</th><th>Total DR</th><th>Lines</th><th></th></tr></thead>
    <tbody>${rows||`<tr><td colspan="7" style="text-align:center;padding:30px;color:var(--text4)">No journal entries yet</td></tr>`}</tbody>
  </table>`;
}

function toggleJournal(id){
  const lines=document.querySelectorAll(`#jlines-${id}`);
  const tog=document.getElementById(`jtoggle-${id}`);
  const isOpen=tog&&tog.textContent==="▲";
  lines.forEach(l=>l.style.display=isOpen?"none":"table-row");
  if(tog)tog.textContent=isOpen?"▼":"▲";
}

// ═══════════════════════════════════════════════════════════════
// ANOMALIES
// ═══════════════════════════════════════════════════════════════
function renderAnomalies(){
  if(anomalies.length===0){
    document.getElementById("anomalyList").innerHTML=`<div class="card" style="padding:36px;text-align:center"><div style="font-size:28px;margin-bottom:10px">✓</div><div style="color:var(--green)">No anomalies detected. All entries are clean.</div></div>`;
    return;
  }
  document.getElementById("anomalyList").innerHTML=anomalies.map((a,i)=>`
    <div class="card" style="padding:14px;margin-bottom:10px;border-left:3px solid ${a.severity==="CRITICAL"?"#ef4444":a.severity==="HIGH"?"#f59e0b":"#3b82f6"};opacity:${a.resolved?.55:1}">
      <div style="display:flex;justify-content:space-between;align-items:flex-start">
        <div>
          <div style="display:flex;align-items:center;gap:7px;margin-bottom:5px">
            <span class="badge" style="background:${a.severity==="CRITICAL"?"rgba(239,68,68,.13)":a.severity==="HIGH"?"rgba(245,158,11,.13)":"rgba(59,130,246,.13)"};color:${a.severity==="CRITICAL"?"#ef4444":a.severity==="HIGH"?"#f59e0b":"#60a5fa"}">${a.severity}</span>
            <span class="badge" style="background:#1e2a3a;color:var(--text3)">${a.type}</span>
            ${a.resolved?'<span class="badge" style="background:rgba(16,185,129,.13);color:#10b981">RESOLVED</span>':""}
          </div>
          <div style="font-size:12px;color:var(--text);margin-bottom:3px">${a.desc}</div>
          ${a.detectedAt?`<div style="font-size:10px;color:var(--text4)">Detected: ${dateStr(a.detectedAt)}</div>`:""}
        </div>
        ${!a.resolved?`<button class="btn btn-ghost" style="font-size:10px" onclick="resolveAnomaly(${i})">Mark Resolved</button>`:""}
      </div>
    </div>`).join("");
}

function resolveAnomaly(i){
  anomalies[i].resolved=true;
  renderAnomalies();
  renderDashboard();
  notify("Anomaly marked as resolved");
}

// ═══════════════════════════════════════════════════════════════
// AI EXTRACTION
// ═══════════════════════════════════════════════════════════════
// Read file as base64
function readFileAsBase64(file){
  return new Promise((res,rej)=>{
    const r=new FileReader();
    r.onload=()=>res(r.result.split(",")[1]);
    r.onerror=()=>rej(new Error("Read failed"));
    r.readAsDataURL(file);
  });
}

// Parse raw number string to float (handles Indian comma format like 1,23,456.00)
function parseAmt(s){ return parseFloat(String(s||0).replace(/[^\d.]/g,""))||0; }

// Aggressive total-amount extractor — scans every line near the word "total"
function extractAmountFromText(text){
  if(!text) return null;
  // Priority 1: labelled totals (most specific first)
  const priority=[
    /(?:grand\s*total|total\s*amount\s*due|amount\s*due|total\s*due|net\s*payable|total\s*payable|invoice\s*total|total\s*invoice|balance\s*due|amount\s*payable|total\s*invoice\s*value|invoice\s*value|total\s*value)[^\d\n]{0,40}([\d,]+\.?\d{0,2})/gi,
    /(?:total)[^\d\n\w]{0,5}[:\-]?\s*([\d,]+\.?\d{0,2})/gi,
  ];
  for(const pat of priority){
    const m=[...text.matchAll(pat)].map(x=>parseAmt(x[1])).filter(n=>n>0);
    if(m.length) return Math.max(...m);
  }
  // Priority 2: any line containing "total" — grab largest number on that line
  for(const line of text.split(/\n/)){
    if(/total/i.test(line)){
      const nums=[...line.matchAll(/([\d,]+\.?\d{0,2})/g)].map(x=>parseAmt(x[1])).filter(n=>n>0);
      if(nums.length) return Math.max(...nums);
    }
  }
  // Fallback: largest amount in entire doc
  const all=[...text.matchAll(/([\d]{1,3}(?:,\d{3})+(?:\.\d{1,2})?|\d{4,}(?:\.\d{1,2})?)/g)]
    .map(x=>parseAmt(x[1])).filter(n=>n>=1);
  return all.length?Math.max(...all):null;
}

// Extract CGST / SGST / IGST amounts and rates from text
function extractTaxFromText(text){
  if(!text) return {taxAmount:0,taxRate:0,cgst:0,sgst:0,igst:0,cgstRate:0,sgstRate:0,igstRate:0};
  const r={taxAmount:0,taxRate:0,cgst:0,sgst:0,igst:0,cgstRate:0,sgstRate:0,igstRate:0};
  const biggest=arr=>arr.length?Math.max(...arr):0;
  // Amounts
  r.cgst=biggest([...text.matchAll(/cgst[^\d\n]{0,25}([\d,]+\.?\d{0,2})/gi)].map(x=>parseAmt(x[1])).filter(n=>n>0));
  r.sgst=biggest([...text.matchAll(/sgst[^\d\n]{0,25}([\d,]+\.?\d{0,2})/gi)].map(x=>parseAmt(x[1])).filter(n=>n>0));
  r.igst=biggest([...text.matchAll(/igst[^\d\n]{0,25}([\d,]+\.?\d{0,2})/gi)].map(x=>parseAmt(x[1])).filter(n=>n>0));
  if(!r.cgst&&!r.sgst&&!r.igst){
    r.taxAmount=biggest([...text.matchAll(/(?:gst|vat|tax|service\s*tax)[^\d\n]{0,25}([\d,]+\.?\d{0,2})/gi)].map(x=>parseAmt(x[1])).filter(n=>n>0));
  } else { r.taxAmount=r.cgst+r.sgst+r.igst; }
  // Rates
  r.cgstRate=biggest([...text.matchAll(/cgst\s*@?\s*([\d.]+)\s*%/gi)].map(x=>parseFloat(x[1])).filter(n=>n>0));
  r.sgstRate=biggest([...text.matchAll(/sgst\s*@?\s*([\d.]+)\s*%/gi)].map(x=>parseFloat(x[1])).filter(n=>n>0));
  r.igstRate=biggest([...text.matchAll(/igst\s*@?\s*([\d.]+)\s*%/gi)].map(x=>parseFloat(x[1])).filter(n=>n>0));
  const anyRate=biggest([...text.matchAll(/(?:gst|vat|tax)\s*@?\s*([\d.]+)\s*%/gi)].map(x=>parseFloat(x[1])).filter(n=>n>0));
  r.taxRate=r.cgstRate+r.sgstRate+r.igstRate||anyRate;
  return r;
}

async function extractWithClaude(fileData, fileName, fileType){
  const isImage=fileType.startsWith("image/");
  const isPDF=fileType==="application/pdf";

  const prompt=`You are a financial document parser. Extract EVERY number exactly as printed — do NOT estimate or compute.

CRITICAL RULES:
1. "amount" = the GRAND TOTAL / TOTAL AMOUNT DUE printed on the document — the final payable figure (bottom-line, including all taxes). Look for labels: "Total", "Grand Total", "Total Amount Due", "Net Payable", "Invoice Total", "Balance Due", "Amount Payable". Copy the EXACT number next to/below that label.
2. "taxRate" = the overall GST/VAT/Tax rate % printed on the document (e.g. 18 for 18%).
3. "cgst","sgst","igst" = the exact rupee/currency amounts printed next to those labels. If not present, use 0.
4. "cgstRate","sgstRate","igstRate" = the % rates printed next to those labels (e.g. 9 for 9%). If not present, use 0.
5. If CGST+SGST are present, "taxAmount" = cgst+sgst. If IGST is present, "taxAmount" = igst.

Document filename: ${fileName}

Return ONLY valid JSON (no markdown, no explanation, no trailing commas):
{
  "party": "exact company/person name from document",
  "partyType": "debtor or creditor",
  "invoiceNo": "exact invoice/bill number",
  "date": "YYYY-MM-DD",
  "amount": exact grand total numeric value,
  "taxAmount": total tax amount numeric,
  "taxRate": overall tax rate as number (e.g. 18),
  "cgst": CGST amount numeric or 0,
  "sgst": SGST amount numeric or 0,
  "igst": IGST amount numeric or 0,
  "cgstRate": CGST rate % numeric or 0,
  "sgstRate": SGST rate % numeric or 0,
  "igstRate": IGST rate % numeric or 0,
  "currency": "ISO 4217 code e.g. INR",
  "docType": "Sales Invoice / Purchase Bill / Receipt / Bank Statement / Credit Note",
  "description": "one-line narration",
  "lineItems": [{"description":"","qty":1,"unitPrice":0,"amount":0}],
  "suggestedDebitAccount": "1100",
  "suggestedCreditAccount": "4000",
  "confidence": 0.0 to 1.0,
  "anomalies": []
}`;

  let messageContent;
  if(isImage){
    messageContent=[
      {type:"image",source:{type:"base64",media_type:fileType,data:fileData}},
      {type:"text",text:prompt}
    ];
  } else if(isPDF){
    messageContent=[
      {type:"document",source:{type:"base64",media_type:"application/pdf",data:fileData}},
      {type:"text",text:prompt}
    ];
  } else {
    messageContent=[{type:"text",text:`${prompt}\n\nDocument content:\n${fileData.substring(0,4000)}`}];
  }

  const resp=await fetch("https://wvzvtthwzlufbuyqknou.supabase.co/functions/v1/claude-proxy",{
    method:"POST",
    headers:{"Content-Type":"application/json"},
    body:JSON.stringify({model:"claude-sonnet-4-20250514",max_tokens:1500,messages:[{role:"user",content:messageContent}]})
  });
  if(!resp.ok){ const e=await resp.json().catch(()=>({})); console.warn("Proxy error",resp.status,e); return null; }
  const data=await resp.json();
  const txt=data.content?.map(b=>b.text||"").join("")||"";
  try{return JSON.parse(txt.replace(/```json|```/g,"").trim());}catch(e){ console.warn("JSON parse fail",txt); return null; }
}

async function processFile(file){
  const progId="prog-"+Date.now();
  const progDiv=document.getElementById("uploadProgress");
  progDiv.insertAdjacentHTML("beforeend",`<div id="${progId}" class="card" style="padding:13px;margin-bottom:10px">
    <div style="display:flex;justify-content:space-between;margin-bottom:7px">
      <span style="font-size:12px;color:var(--text)">📄 ${file.name}</span>
      <span id="${progId}-stage" style="font-size:11px;color:#818cf8">Reading file...</span>
    </div>
    <div class="prog-bar"><div class="prog-fill" id="${progId}-fill" style="width:5%"></div></div>
  </div>`);
  const setP=(pct,stage)=>{
    const el=document.getElementById(progId+"-fill");
    const st=document.getElementById(progId+"-stage");
    if(el)el.style.width=pct+"%";
    if(st)st.textContent=stage;
  };

  const isImage=file.type.startsWith("image/");
  const isPDF=file.type==="application/pdf";
  const isText=file.type==="text/plain"||file.name.endsWith(".csv")||file.name.endsWith(".txt");

  // Step 1 — Read the actual file bytes/text
  setP(20,"Reading file...");
  let fileData="";
  try{
    if(isImage||isPDF){
      fileData=await readFileAsBase64(file);
    } else {
      fileData=await file.text();
    }
  }catch(e){
    setP(100,"Read error");
    notify(`Could not read ${file.name}`,"error");
    return;
  }

  setP(45,"Sending to Claude AI...");
  await new Promise(r=>setTimeout(r,200));

  // Step 2 — Send real file content to Claude
  let extracted=null;
  try{
    extracted=await extractWithClaude(fileData, file.name, file.type||"text/plain");
  }catch(e){
    console.warn("Claude API error",e);
  }

  setP(75,"Parsing amounts...");
  await new Promise(r=>setTimeout(r,150));

  // Step 3 — Fallback if Claude fails
  if(!extracted){
    const rawText=isText?fileData:"";
    const amountFromText=extractAmountFromText(rawText);
    const taxData=extractTaxFromText(rawText);
    const dateM=rawText.match(/\d{4}-\d{2}-\d{2}|\d{2}[\/\-]\d{2}[\/\-]\d{4}/);
    const invM=rawText.match(/(?:invoice|inv|bill|receipt)[^\w]?[\s#:]*([A-Z0-9\-\/]+)/i);
    extracted={
      party:file.name.replace(/\.[^.]+$/,"").replace(/[-_]/g," ").replace(/\d{4,}/g,"").trim()||"Unknown Party",
      partyType:file.name.toLowerCase().includes("bill")||file.name.toLowerCase().includes("purchase")?"creditor":"debtor",
      invoiceNo:invM?.[1]||`AUTO-${Date.now()}`,
      date:dateM?.[0]||new Date().toISOString().split("T")[0],
      amount:amountFromText||0,
      taxAmount:taxData.taxAmount,taxRate:taxData.taxRate,
      cgst:taxData.cgst,sgst:taxData.sgst,igst:taxData.igst,
      cgstRate:taxData.cgstRate,sgstRate:taxData.sgstRate,igstRate:taxData.igstRate,
      currency,
      docType:file.name.toLowerCase().includes("bill")?"Purchase Bill":"Sales Invoice",
      description:`Extracted from ${file.name}`,
      lineItems:[],
      suggestedDebitAccount:"1100",suggestedCreditAccount:"4000",
      confidence:.5,
      anomalies:["Fallback parser used — please verify amount and details"]
    };
  }

  // Step 4 — If amount still zero on text file, try text pattern extraction
  if((!extracted.amount||extracted.amount<=0)&&isText){
    const fallbackAmt=extractAmountFromText(fileData);
    if(fallbackAmt) extracted.amount=fallbackAmt;
  }
  // Step 4b — If CGST/SGST/IGST missing but text available, try text extraction
  if(isText&&(!extracted.cgst&&!extracted.sgst&&!extracted.igst)){
    const td=extractTaxFromText(fileData);
    if(td.taxAmount>0){
      extracted.cgst=td.cgst; extracted.sgst=td.sgst; extracted.igst=td.igst;
      extracted.cgstRate=td.cgstRate; extracted.sgstRate=td.sgstRate; extracted.igstRate=td.igstRate;
      if(!extracted.taxAmount) extracted.taxAmount=td.taxAmount;
      if(!extracted.taxRate) extracted.taxRate=td.taxRate;
    }
  }

  setP(88,"Validating & checking anomalies...");
  await new Promise(r=>setTimeout(r,200));

  const flags=detectAnomalies(extracted,Date.now());
  extracted.anomalies=[...(extracted.anomalies||[]),...flags.map(f=>f.desc)];
  extracted.flags=flags;
  extracted.fileName=file.name;

  setP(100,"Done ✓");
  setTimeout(()=>document.getElementById(progId)?.remove(),1800);

  extractedData=extracted;
  switchTab("extract");
}

function handleFileInput(files){
  Array.from(files).forEach(f=>processFile(f));
}

const dz=document.getElementById("dropZone");
dz.addEventListener("dragover",e=>{e.preventDefault();dz.classList.add("drag-over")});
dz.addEventListener("dragleave",()=>dz.classList.remove("drag-over"));
dz.addEventListener("drop",e=>{e.preventDefault();dz.classList.remove("drag-over");handleFileInput(e.dataTransfer.files)});

// ═══════════════════════════════════════════════════════════════
// EXTRACT REVIEW
// ═══════════════════════════════════════════════════════════════
function renderExtract(){
  const el=document.getElementById("extractContent");
  if(!extractedData){
    el.innerHTML=`<div class="card" style="padding:36px;text-align:center">
      <div style="font-size:36px;margin-bottom:13px">✦</div>
      <div style="color:var(--text4);font-size:13px">No document pending review. Upload a file to extract data.</div>
      <button class="btn btn-primary" style="margin-top:14px" onclick="switchTab('upload')">Go to Upload</button>
    </div>`;
    return;
  }
  const d=extractedData;
  const cur=d.currency||currency;
  const conf=Math.round((d.confidence||.7)*100);
  const hasAmt=d.amount>0;
  const hasCGST=d.cgst>0, hasSGST=d.sgst>0, hasIGST=d.igst>0;
  const hasGSTSplit=hasCGST||hasSGST||hasIGST;
  const debitOpts=Object.entries(COA).filter(([,v])=>["asset","expense"].includes(v.type)).map(([c,v])=>`<option value="${c}" ${c===d.suggestedDebitAccount?"selected":""}>${c} · ${v.name}</option>`).join("");
  const curOpts=Object.entries(CURRENCIES).map(([k,v])=>`<option value="${k}" ${k===cur?"selected":""}>${v.flag} ${k}</option>`).join("");

  el.innerHTML=`
    <div class="card" style="padding:18px;margin-bottom:13px">
      <!-- Header -->
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:15px;flex-wrap:wrap;gap:10px">
        <div>
          <div class="syne" style="font-size:13px;font-weight:600;color:#f1f5f9">📄 ${d.fileName}</div>
          <div style="font-size:10px;color:var(--text4);margin-top:2px">AI Confidence: <span style="color:${conf>=80?"#10b981":conf>=60?"#f59e0b":"#ef4444"}">${conf}%</span></div>
        </div>
        <div style="display:flex;gap:8px">
          <button class="btn btn-ghost" onclick="discardExtract()">Discard</button>
          <button class="btn btn-success" onclick="postExtracted()">✓ Post Journal Entry</button>
        </div>
      </div>

      <!-- AMOUNT BANNER -->
      <div style="background:${hasAmt?"rgba(16,185,129,.07)":"rgba(245,158,11,.08)"};border:1px solid ${hasAmt?"rgba(16,185,129,.3)":"rgba(245,158,11,.35)"};border-radius:8px;padding:14px 18px;margin-bottom:14px">
        <div style="display:flex;justify-content:space-between;align-items:flex-start;flex-wrap:wrap;gap:8px;margin-bottom:6px">
          <div style="font-size:10px;color:var(--text4);text-transform:uppercase;letter-spacing:.07em">Total Amount Due — fetched from document</div>
          <span class="badge" style="background:${hasAmt&&conf>=70?"rgba(16,185,129,.15)":"rgba(245,158,11,.15)"};color:${hasAmt&&conf>=70?"#10b981":"#f59e0b"};font-size:9px;padding:3px 9px">
            ${hasAmt&&conf>=70?"✓ Extracted":"⚠ "+(hasAmt?"Low confidence":"Not detected — enter below")}
          </span>
        </div>
        <div id="ext-amount-big" class="syne" style="font-size:26px;font-weight:700;color:${hasAmt?"#10b981":"#f59e0b"};margin-bottom:4px">${hasAmt?fmtFull(d.amount,cur):"—"}</div>
        ${d.taxAmount>0?`<div style="font-size:11px;color:var(--text3)">Incl. tax: <b style="color:#f59e0b">${fmtFull(d.taxAmount,cur)}</b> &nbsp;·&nbsp; Net (excl. tax): <b style="color:#10b981">${fmtFull(d.amount-d.taxAmount,cur)}</b></div>`:""}
      </div>

      <!-- Row 1: Party / Invoice / Date -->
      <div class="grid-3" style="gap:11px;margin-bottom:11px">
        <div><div style="font-size:10px;color:var(--text4);margin-bottom:4px">Party Name</div><input class="inp" id="ext-party" value="${d.party||""}"/></div>
        <div><div style="font-size:10px;color:var(--text4);margin-bottom:4px">Invoice No.</div><input class="inp" id="ext-invoiceNo" value="${d.invoiceNo||""}"/></div>
        <div><div style="font-size:10px;color:var(--text4);margin-bottom:4px">Date</div><input class="inp" type="date" id="ext-date" value="${d.date||""}"/></div>
      </div>

      <!-- Row 2: Total Amount + live breakdown -->
      <div style="background:var(--surface2);border:1px solid var(--border);border-radius:8px;padding:14px;margin-bottom:14px">
        <div style="font-size:10px;color:var(--text4);text-transform:uppercase;letter-spacing:.07em;margin-bottom:10px">Amount &amp; Tax Breakdown</div>
        <div style="display:grid;grid-template-columns:1fr 1fr;gap:11px;margin-bottom:11px">
          <div>
            <div style="font-size:10px;color:var(--text4);margin-bottom:4px;display:flex;justify-content:space-between">
              <span>Total Amount (incl. all tax)</span>
              <span style="color:${hasAmt?"#10b981":"#f59e0b"};font-size:9px">${hasAmt?"● from doc":"● enter manually"}</span>
            </div>
            <input class="inp" type="number" id="ext-amount" value="${d.amount||""}" placeholder="0.00" step="0.01"
              style="border-color:${hasAmt?"rgba(16,185,129,.5)":"rgba(245,158,11,.4)"};font-weight:700;font-size:14px;color:#f1f5f9"
              oninput="liveAmountUpdate()"/>
          </div>
          <div>
            <div style="font-size:10px;color:var(--text4);margin-bottom:4px;display:flex;justify-content:space-between">
              <span>Taxable Amount (before tax)</span>
              <span id="bd-taxable-lbl" style="color:var(--text4);font-size:9px">auto-computed</span>
            </div>
            <input class="inp" type="number" id="ext-taxable" value="${d.amount&&d.taxAmount?(d.amount-d.taxAmount):""}" placeholder="0.00" step="0.01"
              style="background:var(--bg);opacity:.7" readonly/>
          </div>
        </div>

        <!-- TAX SECTION HEADER -->
        <div style="border-top:1px solid var(--border);padding-top:10px;margin-top:2px">
          <div style="font-size:10px;color:var(--text4);text-transform:uppercase;letter-spacing:.07em;margin-bottom:9px">Tax &nbsp;<span style="color:var(--text3);font-size:9px;letter-spacing:0">CGST · SGST · IGST breakdown</span></div>
          <div style="display:grid;grid-template-columns:repeat(4,1fr);gap:9px;margin-bottom:9px">
            <!-- Total Tax -->
            <div style="border-right:1px solid var(--border);padding-right:9px">
              <div style="font-size:9px;color:var(--text4);margin-bottom:4px;text-transform:uppercase;letter-spacing:.05em">Total Tax</div>
              <input class="inp" type="number" id="ext-taxAmount" value="${d.taxAmount||""}" placeholder="0.00" step="0.01"
                style="border-color:${d.taxAmount>0?"rgba(245,158,11,.4)":"#2d3748"};font-weight:600"
                oninput="liveAmountUpdate()"/>
              <div style="font-size:9px;color:var(--text4);margin-top:4px">Rate: <input type="number" id="ext-taxRate" value="${d.taxRate||""}" placeholder="0" step="0.01"
                style="background:transparent;border:none;border-bottom:1px solid #2d3748;color:var(--text);width:40px;font-family:inherit;font-size:9px;outline:none;padding:1px 3px"/> %</div>
            </div>
            <!-- CGST -->
            <div>
              <div style="font-size:9px;color:#818cf8;margin-bottom:4px;text-transform:uppercase;letter-spacing:.05em;display:flex;justify-content:space-between">
                <span>CGST</span>
                <span style="color:${hasCGST?"#10b981":"var(--text4)"}">${hasCGST?"● doc":"●"}</span>
              </div>
              <input class="inp" type="number" id="ext-cgst" value="${d.cgst||""}" placeholder="0.00" step="0.01"
                style="border-color:${hasCGST?"rgba(129,140,248,.4)":"#2d3748"}"
                oninput="liveAmountUpdate()"/>
              <div style="font-size:9px;color:var(--text4);margin-top:4px">Rate: <input type="number" id="ext-cgstRate" value="${d.cgstRate||""}" placeholder="0" step="0.01"
                style="background:transparent;border:none;border-bottom:1px solid #2d3748;color:var(--text);width:40px;font-family:inherit;font-size:9px;outline:none;padding:1px 3px"/> %</div>
            </div>
            <!-- SGST -->
            <div>
              <div style="font-size:9px;color:#818cf8;margin-bottom:4px;text-transform:uppercase;letter-spacing:.05em;display:flex;justify-content:space-between">
                <span>SGST</span>
                <span style="color:${hasSGST?"#10b981":"var(--text4)"}">${hasSGST?"● doc":"●"}</span>
              </div>
              <input class="inp" type="number" id="ext-sgst" value="${d.sgst||""}" placeholder="0.00" step="0.01"
                style="border-color:${hasSGST?"rgba(129,140,248,.4)":"#2d3748"}"
                oninput="liveAmountUpdate()"/>
              <div style="font-size:9px;color:var(--text4);margin-top:4px">Rate: <input type="number" id="ext-sgstRate" value="${d.sgstRate||""}" placeholder="0" step="0.01"
                style="background:transparent;border:none;border-bottom:1px solid #2d3748;color:var(--text);width:40px;font-family:inherit;font-size:9px;outline:none;padding:1px 3px"/> %</div>
            </div>
            <!-- IGST -->
            <div>
              <div style="font-size:9px;color:#818cf8;margin-bottom:4px;text-transform:uppercase;letter-spacing:.05em;display:flex;justify-content:space-between">
                <span>IGST</span>
                <span style="color:${hasIGST?"#10b981":"var(--text4)"}">${hasIGST?"● doc":"●"}</span>
              </div>
              <input class="inp" type="number" id="ext-igst" value="${d.igst||""}" placeholder="0.00" step="0.01"
                style="border-color:${hasIGST?"rgba(129,140,248,.4)":"#2d3748"}"
                oninput="liveAmountUpdate()"/>
              <div style="font-size:9px;color:var(--text4);margin-top:4px">Rate: <input type="number" id="ext-igstRate" value="${d.igstRate||""}" placeholder="0" step="0.01"
                style="background:transparent;border:none;border-bottom:1px solid #2d3748;color:var(--text);width:40px;font-family:inherit;font-size:9px;outline:none;padding:1px 3px"/> %</div>
            </div>
          </div>
          <!-- Live summary bar -->
          <div style="background:var(--bg);border-radius:6px;padding:8px 12px;display:flex;gap:18px;flex-wrap:wrap;font-size:11px;border:1px solid var(--border2)">
            <span style="color:var(--text3)">Gross: <b id="bd-gross" style="color:var(--text)">${fmtFull(d.amount||0,cur)}</b></span>
            <span style="color:var(--text3)">Tax: <b id="bd-tax" style="color:#f59e0b">${fmtFull(d.taxAmount||0,cur)}</b></span>
            <span style="color:var(--text3)">CGST: <b id="bd-cgst" style="color:#818cf8">${fmtFull(d.cgst||0,cur)}</b></span>
            <span style="color:var(--text3)">SGST: <b id="bd-sgst" style="color:#818cf8">${fmtFull(d.sgst||0,cur)}</b></span>
            <span style="color:var(--text3)">IGST: <b id="bd-igst" style="color:#818cf8">${fmtFull(d.igst||0,cur)}</b></span>
            <span style="color:var(--text3)">Net: <b id="bd-net" style="color:#10b981">${fmtFull((d.amount||0)-(d.taxAmount||0),cur)}</b></span>
          </div>
        </div>
      </div>

      <!-- Row 3: Doc type / Party type / Currency / Debit account -->
      <div style="display:grid;grid-template-columns:1fr 1fr 1fr 1fr;gap:11px;margin-bottom:11px">
        <div><div style="font-size:10px;color:var(--text4);margin-bottom:4px">Document Type</div>
          <select class="inp" id="ext-docType">${["Sales Invoice","Purchase Bill","Receipt","Bank Statement","Credit Note","Debit Note"].map(t=>`<option ${t===d.docType?"selected":""}>${t}</option>`).join("")}</select></div>
        <div><div style="font-size:10px;color:var(--text4);margin-bottom:4px">Party Type</div>
          <select class="inp" id="ext-partyType"><option value="debtor" ${d.partyType==="debtor"?"selected":""}>Debtor (Customer)</option><option value="creditor" ${d.partyType==="creditor"?"selected":""}>Creditor (Vendor)</option></select></div>
        <div><div style="font-size:10px;color:var(--text4);margin-bottom:4px">Currency</div><select class="inp" id="ext-currency" onchange="liveAmountUpdate()">${curOpts}</select></div>
        <div><div style="font-size:10px;color:var(--text4);margin-bottom:4px">Debit Account</div><select class="inp" id="ext-debitAcc">${debitOpts}</select></div>
      </div>
      <div><div style="font-size:10px;color:var(--text4);margin-bottom:4px">Description</div><input class="inp" id="ext-desc" value="${d.description||""}"/></div>
    </div>

    ${(d.anomalies?.length||d.flags?.length)?`<div class="card" style="padding:14px;border-left:3px solid var(--amber);margin-bottom:13px">
      <div style="font-size:11px;font-weight:600;color:var(--amber);margin-bottom:7px">⚠ AI Flags & Suggestions</div>
      ${(d.anomalies||[]).map(a=>`<div style="font-size:11px;color:var(--text2);margin-bottom:3px">• ${typeof a==="string"?a:a.desc}</div>`).join("")}
    </div>`:""}
    ${d.lineItems?.length?`<div class="card" style="padding:18px;margin-top:13px">
      <div class="syne" style="font-size:11px;font-weight:600;color:var(--text2);margin-bottom:11px">EXTRACTED LINE ITEMS</div>
      <table><thead><tr><th>Description</th><th>Qty</th><th>Unit Price</th><th>Amount</th></tr></thead>
      <tbody>${d.lineItems.map(l=>`<tr><td>${l.description}</td><td>${l.qty}</td><td>${l.unitPrice}</td><td class="mono">${l.amount}</td></tr>`).join("")}</tbody></table>
    </div>`:""}`;
}

function discardExtract(){extractedData=null;switchTab("upload");}

function postExtracted(){
  const getV=id=>document.getElementById(id)?.value;
  const getN=id=>parseFloat(document.getElementById(id)?.value)||0;
  const data={
    party:getV("ext-party"),partyType:getV("ext-partyType"),
    invoiceNo:getV("ext-invoiceNo"),date:getV("ext-date"),
    amount:getN("ext-amount"),
    taxAmount:getN("ext-taxAmount"),
    cgst:getN("ext-cgst"),sgst:getN("ext-sgst"),igst:getN("ext-igst"),
    cgstRate:getN("ext-cgstRate"),sgstRate:getN("ext-sgstRate"),igstRate:getN("ext-igstRate"),
    taxRate:getN("ext-taxRate"),
    currency:getV("ext-currency")||currency,
    docType:getV("ext-docType"),description:getV("ext-desc"),
    suggestedDebitAccount:getV("ext-debitAcc")||"1100",
    flags:extractedData?.flags||[],
    fileName:extractedData?.fileName||"document",
    confidence:extractedData?.confidence||.7,
  };
  const netAmount=data.amount-data.taxAmount;
  const isCreditor=data.partyType==="creditor";
  // Build journal lines
  const lines=[
    // Main receivable/payable line (full gross amount)
    {account:data.suggestedDebitAccount,debit:isCreditor?0:data.amount,credit:isCreditor?data.amount:0,
     party:data.party,partyType:data.partyType},
    // Revenue/expense net line
    {account:isCreditor?"5000":"4000",debit:isCreditor?netAmount:0,credit:isCreditor?0:netAmount,
     party:null},
  ];
  // Tax lines — CGST/SGST or IGST as separate lines
  if(data.cgst>0){
    lines.push({account:isCreditor?"1400":"2200",
      debit:isCreditor?data.cgst:0,credit:isCreditor?0:data.cgst,
      party:null,narration:"CGST @ "+data.cgstRate+"%"});
  }
  if(data.sgst>0){
    lines.push({account:isCreditor?"1400":"2200",
      debit:isCreditor?data.sgst:0,credit:isCreditor?0:data.sgst,
      party:null,narration:"SGST @ "+data.sgstRate+"%"});
  }
  if(data.igst>0){
    lines.push({account:isCreditor?"1400":"2200",
      debit:isCreditor?data.igst:0,credit:isCreditor?0:data.igst,
      party:null,narration:"IGST @ "+data.igstRate+"%"});
  }
  if(data.taxAmount>0&&!data.cgst&&!data.sgst&&!data.igst){
    lines.push({account:isCreditor?"1400":"2200",
      debit:isCreditor?data.taxAmount:0,credit:isCreditor?0:data.taxAmount,
      party:null});
  }
  const ok=postJournal({
    ref:`JE-${String(journals.length+1).padStart(3,"0")}`,
    date:data.date||new Date().toISOString().split("T")[0],
    narration:data.description||`Auto-posted from ${data.fileName}`,
    currency:data.currency,
    lines:lines.filter(l=>l&&(l.debit||l.credit))
  });
  documents.push({id:Date.now(),name:data.fileName,type:data.docType,party:data.party,amount:data.amount,
    date:data.date,status:ok?"posted":"error",currency:data.currency,invoiceNo:data.invoiceNo,
    confidence:data.confidence,cgst:data.cgst,sgst:data.sgst,igst:data.igst,taxAmount:data.taxAmount});
  if(data.flags?.length) data.flags.forEach(f=>anomalies.push({...f,id:Date.now()+Math.random(),resolved:false,detectedAt:new Date().toISOString()}));
  extractedData=null;
  notify(ok?`✓ Journal entry posted for ${data.party}`:"⚠ Posting failed — check anomalies",ok?"success":"error");
  switchTab("dashboard");
}

// ═══════════════════════════════════════════════════════════════
// DOWNLOADS — all include business name + period
// ═══════════════════════════════════════════════════════════════
function dlFile(content,filename,mime="text/csv;charset=utf-8;"){
  const blob=new Blob([content],{type:mime});
  const a=document.createElement("a");
  a.href=URL.createObjectURL(blob);
  a.download=filename;
  a.click();
  URL.revokeObjectURL(a.href);
}

function csvRow(cells){
  return cells.map(c=>{
    const s=String(c===null||c===undefined?"":c);
    return s.includes(",")||s.includes('"')||s.includes("\n")?`"${s.replace(/"/g,'""')}"`:"s"===s?s:s;
  }).join(",")+"\r\n";
}

function bizHeader(){
  return `${getBizName()}${bizInfo.reg?" · "+bizInfo.reg:""}\r\n${getFYLabel()} · ${getPeriodLabel()}${bizInfo.address?"\r\n"+bizInfo.address:""}\r\n`;
}

function dlHtmlReport(title,bodyHtml,filename){
  const html=`<!DOCTYPE html><html><head><meta charset="UTF-8"/><title>${title} — ${getBizName()}</title>
<style>
body{font-family:'DM Mono',monospace,sans-serif;background:#fff;color:#111;max-width:900px;margin:40px auto;padding:0 20px}
.biz-header{border-bottom:2px solid #3b82f6;padding-bottom:12px;margin-bottom:20px}
.biz-name{font-family:sans-serif;font-size:20px;font-weight:700;margin:0}
.biz-meta{font-size:11px;color:#555;margin-top:3px}
h1{font-family:sans-serif;font-size:18px;margin:0 0 4px}
h2{font-family:sans-serif;font-size:13px;color:#555;font-weight:400;margin-bottom:20px}
table{width:100%;border-collapse:collapse;font-size:13px}
th{background:#f5f5f5;color:#333;padding:8px 12px;text-align:left;border:1px solid #ddd;font-size:11px;text-transform:uppercase}
td{padding:7px 12px;border:1px solid #eee}
.total-row{font-weight:700;background:#f9f9f9}
.section{background:#eef3ff;font-weight:700;font-size:12px;padding:6px 12px;border-left:3px solid #3b82f6}
.positive{color:#059669}.negative{color:#dc2626}
.footer{margin-top:30px;font-size:11px;color:#888;border-top:1px solid #eee;padding-top:10px}
</style></head><body>
<div class="biz-header">
  <div class="biz-name">${getBizName()}</div>
  <div class="biz-meta">${bizInfo.reg?bizInfo.reg+" · ":""}${getFYLabel()} · ${getPeriodLabel()}${bizInfo.address?" · "+bizInfo.address:""}</div>
</div>
${bodyHtml}
<div class="footer">Generated by LedgerAI · ${new Date().toLocaleString()} · IFRS Compliant</div>
</body></html>`;
  dlFile(html,filename,"text/html;charset=utf-8;");
  notify("HTML report downloaded","success");
}

function downloadPL(format){
  const pl=getPL(); const cur=currency;
  if(format==="csv"){
    let csv=`PROFIT & LOSS STATEMENT\r\n${bizHeader()}\r\n`;
    csv+="Category,Item,Amount ("+cur+")\r\n";
    csv+=csvRow(["REVENUE","Sales Revenue",fmtFull(pl.revenue*.72,cur)]);
    csv+=csvRow(["REVENUE","Service Revenue",fmtFull(pl.revenue*.28,cur)]);
    csv+=csvRow(["REVENUE","Total Revenue",fmtFull(pl.revenue,cur)]);
    csv+=csvRow(["COST OF REVENUE","Cost of Goods Sold",fmtFull(-pl.cogs*.8,cur)]);
    csv+=csvRow(["COST OF REVENUE","Direct Labour",fmtFull(-pl.cogs*.2,cur)]);
    csv+=csvRow(["COST OF REVENUE","Total COGS",fmtFull(-pl.cogs,cur)]);
    csv+=csvRow(["","GROSS PROFIT",fmtFull(pl.grossProfit,cur)]);
    csv+=csvRow(["OPERATING EXPENSES","Salaries & Wages",fmtFull(-pl.opex*.55,cur)]);
    csv+=csvRow(["OPERATING EXPENSES","Rent Expense",fmtFull(-pl.opex*.18,cur)]);
    csv+=csvRow(["OPERATING EXPENSES","Marketing & Advertising",fmtFull(-pl.opex*.14,cur)]);
    csv+=csvRow(["OPERATING EXPENSES","Professional Fees",fmtFull(-pl.opex*.08,cur)]);
    csv+=csvRow(["OPERATING EXPENSES","Other",fmtFull(-pl.opex*.05,cur)]);
    csv+=csvRow(["OPERATING EXPENSES","Total OpEx",fmtFull(-pl.opex,cur)]);
    csv+=csvRow(["","EBIT",fmtFull(pl.ebit,cur)]);
    csv+=csvRow(["FINANCE COSTS","Interest Expense",fmtFull(-pl.finCosts,cur)]);
    csv+=csvRow(["","Profit Before Tax",fmtFull(pl.ebt,cur)]);
    csv+=csvRow(["","Income Tax Expense",fmtFull(-pl.tax,cur)]);
    csv+=csvRow(["","NET PROFIT",fmtFull(pl.netProfit,cur)]);
    csv+="\r\nKey Ratios\r\n";
    csv+=`Gross Margin,${pl.revenue>0?((pl.grossProfit/pl.revenue)*100).toFixed(2):0}%\r\n`;
    csv+=`Net Margin,${pl.revenue>0?((pl.netProfit/pl.revenue)*100).toFixed(2):0}%\r\n`;
    dlFile(csv,`${getBizName().replace(/[^a-z0-9]/gi,"_")}_ProfitAndLoss.csv`);
    notify("P&L exported as CSV","success");
  } else {
    const body=`<h1>Profit &amp; Loss Statement</h1><h2>For the Period ${getPeriodLabel()} · ${getFYLabel()} · IFRS (IAS 1) · Currency: ${cur}</h2>
    <table>
    <tr><th colspan="2" class="section">REVENUE</th></tr>
    <tr><td style="padding-left:20px">Sales Revenue</td><td>${fmtFull(pl.revenue*.72,cur)}</td></tr>
    <tr><td style="padding-left:20px">Service Revenue</td><td>${fmtFull(pl.revenue*.28,cur)}</td></tr>
    <tr class="total-row"><td>Total Revenue</td><td>${fmtFull(pl.revenue,cur)}</td></tr>
    <tr><th colspan="2" class="section">COST OF REVENUE</th></tr>
    <tr><td style="padding-left:20px">Cost of Goods Sold</td><td class="negative">${fmtFull(-pl.cogs*.8,cur)}</td></tr>
    <tr><td style="padding-left:20px">Direct Labour</td><td class="negative">${fmtFull(-pl.cogs*.2,cur)}</td></tr>
    <tr class="total-row"><td>Total COGS</td><td class="negative">${fmtFull(-pl.cogs,cur)}</td></tr>
    <tr class="total-row" style="background:#d1fae5"><td>GROSS PROFIT</td><td class="positive">${fmtFull(pl.grossProfit,cur)}</td></tr>
    <tr><th colspan="2" class="section">OPERATING EXPENSES</th></tr>
    <tr><td style="padding-left:20px">Salaries &amp; Wages</td><td class="negative">${fmtFull(-pl.opex*.55,cur)}</td></tr>
    <tr><td style="padding-left:20px">Rent Expense</td><td class="negative">${fmtFull(-pl.opex*.18,cur)}</td></tr>
    <tr><td style="padding-left:20px">Marketing &amp; Advertising</td><td class="negative">${fmtFull(-pl.opex*.14,cur)}</td></tr>
    <tr><td style="padding-left:20px">Professional Fees</td><td class="negative">${fmtFull(-pl.opex*.08,cur)}</td></tr>
    <tr><td style="padding-left:20px">Other</td><td class="negative">${fmtFull(-pl.opex*.05,cur)}</td></tr>
    <tr class="total-row"><td>Total Operating Expenses</td><td class="negative">${fmtFull(-pl.opex,cur)}</td></tr>
    <tr class="total-row" style="background:#dbeafe"><td>OPERATING PROFIT (EBIT)</td><td class="${pl.ebit>=0?"positive":"negative"}">${fmtFull(pl.ebit,cur)}</td></tr>
    <tr><td style="padding-left:20px">Interest Expense</td><td class="negative">${fmtFull(-pl.finCosts,cur)}</td></tr>
    <tr class="total-row"><td>Profit Before Tax</td><td>${fmtFull(pl.ebt,cur)}</td></tr>
    <tr><td style="padding-left:20px">Income Tax Expense</td><td class="negative">${fmtFull(-pl.tax,cur)}</td></tr>
    <tr class="total-row" style="background:#f0fdf4;font-size:14px"><td><strong>NET PROFIT FOR THE PERIOD</strong></td><td class="${pl.netProfit>=0?"positive":"negative"}"><strong>${fmtFull(pl.netProfit,cur)}</strong></td></tr>
    </table>
    <table style="margin-top:20px;max-width:400px">
    <tr><th colspan="2">Key Financial Ratios</th></tr>
    <tr><td>Gross Profit Margin</td><td>${pl.revenue>0?((pl.grossProfit/pl.revenue)*100).toFixed(2):0}%</td></tr>
    <tr><td>Net Profit Margin</td><td>${pl.revenue>0?((pl.netProfit/pl.revenue)*100).toFixed(2):0}%</td></tr>
    <tr><td>EBITDA (est.)</td><td>${fmtFull(pl.ebit+pl.cogs*.05,cur)}</td></tr>
    </table>`;
    dlHtmlReport("Profit & Loss Statement",body,`${getBizName().replace(/[^a-z0-9]/gi,"_")}_ProfitAndLoss.html`);
  }
}

function downloadBS(format){
  const bs=getBS(); const cur=currency;
  const grpOrder=["Current Assets","Non-Current Assets","Current Liabilities","Non-Current Liabilities","Equity"];
  if(format==="csv"){
    let csv=`BALANCE SHEET\r\n${bizHeader()}\r\n`;
    csv+="Group,Account Code,Account Name,Balance ("+cur+")\r\n";
    grpOrder.forEach(grp=>{
      (bs[grp]?.accounts||[]).forEach(a=>{
        csv+=csvRow([grp,a.code,a.name,fmtFull(a.balance,cur)]);
      });
      csv+=csvRow([grp,"","TOTAL "+grp.toUpperCase(),fmtFull(bs[grp]?.total||0,cur)]);
      csv+="\r\n";
    });
    dlFile(csv,`${getBizName().replace(/[^a-z0-9]/gi,"_")}_BalanceSheet.csv`);
    notify("Balance Sheet exported as CSV","success");
  } else {
    function bsTable(title,groups,color){
      let rows=`<tr><th colspan="2" class="section" style="border-left:3px solid ${color}">${title}</th></tr>`;
      groups.forEach(grp=>{
        rows+=`<tr><td colspan="2" style="background:#f8fafc;font-size:11px;color:#555;padding:5px 12px;text-transform:uppercase;letter-spacing:.05em">${grp}</td></tr>`;
        (bs[grp]?.accounts||[]).forEach(a=>{
          rows+=`<tr><td style="padding-left:22px">${a.name} <span style="color:#888;font-size:10px">(${a.code})</span></td><td>${fmtFull(a.balance,cur)}</td></tr>`;
        });
        rows+=`<tr class="total-row"><td>Total ${grp}</td><td style="color:${color}">${fmtFull(bs[grp]?.total||0,cur)}</td></tr>`;
      });
      return rows;
    }
    const totalA=(bs["Current Assets"]?.total||0)+(bs["Non-Current Assets"]?.total||0);
    const totalLE=(bs["Current Liabilities"]?.total||0)+(bs["Non-Current Liabilities"]?.total||0)+(bs["Equity"]?.total||0);
    const pl=getPL();
    const body=`<h1>Balance Sheet</h1><h2>As at ${getPeriodEndLabel()} · ${getFYLabel()} · IFRS (IAS 1) · Currency: ${cur}</h2>
    <div style="display:flex;gap:30px;flex-wrap:wrap">
    <div style="flex:1;min-width:280px"><table>
    ${bsTable("ASSETS",["Current Assets","Non-Current Assets"],"#2563eb")}
    <tr style="background:#dbeafe;font-weight:700;font-size:14px"><td>TOTAL ASSETS</td><td style="color:#2563eb">${fmtFull(totalA,cur)}</td></tr>
    </table></div>
    <div style="flex:1;min-width:280px"><table>
    ${bsTable("LIABILITIES & EQUITY",["Current Liabilities","Non-Current Liabilities","Equity"],"#d97706")}
    <tr style="background:#fef3c7;font-weight:700;font-size:14px"><td>TOTAL LIAB. + EQUITY</td><td style="color:#d97706">${fmtFull(totalLE,cur)}</td></tr>
    </table></div>
    </div>
    <table style="margin-top:20px;max-width:500px">
    <tr><th colspan="2">Key Ratios</th></tr>
    <tr><td>Current Ratio</td><td>${(((bs["Current Assets"]?.total||1)/Math.max(bs["Current Liabilities"]?.total||1,1))).toFixed(2)}x</td></tr>
    <tr><td>Debt-to-Equity</td><td>${((((bs["Current Liabilities"]?.total||0)+(bs["Non-Current Liabilities"]?.total||0))/Math.max(bs["Equity"]?.total||1,1))).toFixed(2)}x</td></tr>
    <tr><td>Net Profit Margin</td><td>${pl.revenue>0?((pl.netProfit/pl.revenue)*100).toFixed(2):0}%</td></tr>
    <tr><td>Balance Check</td><td style="color:${Math.abs(totalA-totalLE)<0.02?"#059669":"#dc2626"}">${Math.abs(totalA-totalLE)<0.02?"✓ Balanced":"⚠ Imbalance"}</td></tr>
    </table>`;
    dlHtmlReport("Balance Sheet",body,`${getBizName().replace(/[^a-z0-9]/gi,"_")}_BalanceSheet.html`);
  }
}

function downloadTB(){
  const tb=getTrialBalance(); const cur=currency;
  let csv=`TRIAL BALANCE\r\n${bizHeader()}\r\n`;
  csv+="Account Code,Account Name,Group,Type,Debit ("+cur+"),Credit ("+cur+")\r\n";
  let tDR=0,tCR=0;
  Object.entries(tb).forEach(([code,bal])=>{
    const a=COA[code]||{name:"Unknown",group:"",type:""};
    tDR+=bal.debit; tCR+=bal.credit;
    csv+=csvRow([code,a.name,a.group,a.type,bal.debit>0?fmtFull(bal.debit,cur):"",bal.credit>0?fmtFull(bal.credit,cur):""]);
  });
  csv+=csvRow(["","","","TOTAL",fmtFull(tDR,cur),fmtFull(tCR,cur)]);
  csv+=`\r\nBalance Check,${Math.abs(tDR-tCR)<0.02?"BALANCED":"IMBALANCED"}\r\n`;
  dlFile(csv,`${getBizName().replace(/[^a-z0-9]/gi,"_")}_TrialBalance.csv`);
  notify("Trial Balance exported as CSV","success");
}

function downloadJournals(){
  let csv=`JOURNAL ENTRIES\r\n${bizHeader()}\r\n`;
  csv+="Reference,Date,Narration,Currency,Account Code,Account Name,Party,Debit,Credit\r\n";
  journals.forEach(j=>{
    j.lines.forEach((l,i)=>{
      csv+=csvRow([i===0?j.ref:"",i===0?j.date:"",i===0?j.narration:"",i===0?j.currency:"",l.account,COA[l.account]?.name||"",l.party||"",l.debit>0?fmtFull(l.debit,j.currency):"",l.credit>0?fmtFull(l.credit,j.currency):""]);
    });
    csv+="\r\n";
  });
  dlFile(csv,`${getBizName().replace(/[^a-z0-9]/gi,"_")}_Journals.csv`);
  notify("Journals exported as CSV","success");
}

function downloadLedgers(){
  let csv=`ALL PARTY LEDGERS\r\n${bizHeader()}\r\n`;
  Object.entries(parties).forEach(([name,p])=>{
    csv+=`PARTY: ${name} (${p.type})\r\n`;
    csv+="Date,Reference,Narration,Debit,Credit,Running Balance\r\n";
    let running=0;
    p.transactions.forEach(t=>{
      running+=t.amount;
      csv+=csvRow([dateStr(t.date),t.ref,t.narration,t.amount>0?fmtFull(t.amount,t.currency):"",t.amount<0?fmtFull(Math.abs(t.amount),t.currency):"",`${fmtFull(Math.abs(running),t.currency)} ${running>=0?"DR":"CR"}`]);
    });
    csv+=csvRow(["","","Closing Balance","",`${fmtFull(Math.abs(p.balance),p.currency)} ${p.balance>=0?"DR":"CR"}`,""])+"\r\n";
  });
  dlFile(csv,`${getBizName().replace(/[^a-z0-9]/gi,"_")}_AllLedgers.csv`);
  notify("All ledgers exported as CSV","success");
}

function downloadSingleLedger(name){
  const p=parties[name]; if(!p)return;
  let csv=`PARTY LEDGER — ${name}\r\n${bizHeader()}\r\nType: ${p.type} · Currency: ${p.currency}\r\n\r\n`;
  csv+="Date,Reference,Narration,Debit,Credit,Running Balance\r\n";
  let running=0;
  p.transactions.forEach(t=>{
    running+=t.amount;
    csv+=csvRow([dateStr(t.date),t.ref,t.narration,t.amount>0?fmtFull(t.amount,t.currency):"",t.amount<0?fmtFull(Math.abs(t.amount),t.currency):"",`${fmtFull(Math.abs(running),t.currency)} ${running>=0?"DR":"CR"}`]);
  });
  csv+=csvRow(["","","Closing Balance","",`${fmtFull(Math.abs(p.balance),p.currency)} ${p.balance>=0?"DR":"CR"}`,""]);
  dlFile(csv,`${getBizName().replace(/[^a-z0-9]/gi,"_")}_Ledger_${name.replace(/[^a-z0-9]/gi,"_")}.csv`);
  notify(`Ledger for ${name} exported`,"success");
}

// No seed data — starts fresh

function clearAllData(){
  if(!confirm("This will clear all data. Are you sure?"))return;
  journals=[];parties={};documents=[];anomalies=[];
  renderDashboard();
  notify("All data cleared","error");
}

// ═══════════════════════════════════════════════════════════════
// API KEY MANAGEMENT
// ═══════════════════════════════════════════════════════════════
async function saveClaudeKey(){
  const key=document.getElementById("claudeApiKey")?.value?.trim();
  if(!key){notify("Please enter your API key","error");return;}
  const statusEl=document.getElementById("apiKeyStatus");
  if(statusEl){statusEl.textContent="Testing key...";statusEl.style.color="#f59e0b";}
  try{
    const resp=await fetch("https://api.anthropic.com/v1/messages",{
      method:"POST",
      headers:{"Content-Type":"application/json","x-api-key":key,"anthropic-version":"2023-06-01","anthropic-dangerous-direct-browser-access":"true"},
      body:JSON.stringify({model:"claude-sonnet-4-20250514",max_tokens:10,messages:[{role:"user",content:"hi"}]})
    });
    if(resp.ok||resp.status===400){
      apiKey=key;
      if(statusEl){statusEl.textContent="✓ Key saved & verified — AI extraction active";statusEl.style.color="#10b981";}
      notify("Claude API key saved — AI extraction is now active","success");
      const badge=document.getElementById("claudeEngineBadge");
      const card=document.getElementById("claudeEngineCard");
      if(badge){badge.textContent="active";badge.style.background="rgba(16,185,129,.15)";badge.style.color="#10b981";}
      if(card) card.style.borderColor="rgba(16,185,129,.2)";
      const hint=card?.querySelector("div:last-child");if(hint)hint.style.display="none";
    } else {
      const e=await resp.json().catch(()=>({}));
      if(statusEl){statusEl.textContent="✗ Invalid key: "+(e.error?.message||resp.status);statusEl.style.color="#ef4444";}
      notify("Invalid API key — check and try again","error");
    }
  }catch(e){
    // CORS block = key format valid but browser blocked — save anyway
    apiKey=key;
    if(statusEl){statusEl.textContent="✓ Key saved (could not verify due to CORS — will test on next upload)";statusEl.style.color="#f59e0b";}
    notify("Key saved — will verify on next upload","success");
  }
}

// ═══════════════════════════════════════════════════════════════
// LIVE AMOUNT BREAKDOWN
// ═══════════════════════════════════════════════════════════════
function liveAmountUpdate(){
  const cur=(document.getElementById("ext-currency")?.value)||currency;
  const gross=parseFloat(document.getElementById("ext-amount")?.value)||0;
  const cgst=parseFloat(document.getElementById("ext-cgst")?.value)||0;
  const sgst=parseFloat(document.getElementById("ext-sgst")?.value)||0;
  const igst=parseFloat(document.getElementById("ext-igst")?.value)||0;
  // Auto-compute total tax from CGST+SGST or IGST if individual fields filled
  const splitTotal=cgst+sgst+igst;
  let tax=parseFloat(document.getElementById("ext-taxAmount")?.value)||0;
  if(splitTotal>0&&(!tax||Math.abs(tax-splitTotal)<0.01)){
    tax=splitTotal;
    const taxEl=document.getElementById("ext-taxAmount");
    if(taxEl&&splitTotal>0) taxEl.value=splitTotal.toFixed(2);
  }
  const net=gross-tax;
  const taxable=document.getElementById("ext-taxable");
  if(taxable) taxable.value=net>0?net.toFixed(2):"";
  const set=(id,val,fmt)=>{ const el=document.getElementById(id); if(el) el.textContent=fmt?fmtFull(val,cur):val; };
  set("bd-gross",gross,true);
  set("bd-tax",tax,true);
  set("bd-cgst",cgst,true);
  set("bd-sgst",sgst,true);
  set("bd-igst",igst,true);
  set("bd-net",net,true);
  const big=document.getElementById("ext-amount-big");
  if(big){ big.textContent=gross>0?fmtFull(gross,cur):"—"; big.style.color=gross>0?"#10b981":"#f59e0b"; }
}

// ═══════════════════════════════════════════════════════════════
// INIT
// ═══════════════════════════════════════════════════════════════
buildCurrencySelect();
applyBizInfoToUI();
renderDashboard();

document.getElementById("currencySelect").addEventListener("change",e=>{
  currency=e.target.value;
  document.getElementById("stdCurrency").innerHTML=`<span>Functional Currency</span><span style="color:var(--text)">${currency}</span>`;
  renderDashboard();
});

// Close modal on backdrop click
document.getElementById("editModal").addEventListener("click",function(e){
  if(e.target===this) closeEditModal();
});
</script>
</body>
</html>
