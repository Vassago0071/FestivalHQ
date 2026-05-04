<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Festival HQ</title>
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --bg: #ffffff;
    --bg2: #f5f5f3;
    --bg3: #eeede9;
    --text: #1a1a18;
    --text2: #6b6b66;
    --text3: #a0a09b;
    --border: rgba(0,0,0,0.10);
    --border2: rgba(0,0,0,0.18);
    --border3: rgba(0,0,0,0.25);
    --radius: 8px;
    --radius-lg: 12px;
    --font: 'Segoe UI', system-ui, -apple-system, sans-serif;
    --danger: #E24B4A;
    --danger-bg: #FCEBEB;
    --danger-text: #A32D2D;
    --success-bg: #EAF3DE;
    --success-text: #27500A;
  }

  @media (prefers-color-scheme: dark) {
    :root {
      --bg: #1c1c1a;
      --bg2: #252523;
      --bg3: #2e2e2b;
      --text: #f0efe8;
      --text2: #a0a09b;
      --text3: #66665f;
      --border: rgba(255,255,255,0.08);
      --border2: rgba(255,255,255,0.14);
      --border3: rgba(255,255,255,0.22);
      --danger-bg: #3a1515;
      --danger-text: #f09595;
      --success-bg: #1a2e0a;
      --success-text: #97c459;
    }
  }

  html, body { height: 100%; background: var(--bg3); font-family: var(--font); color: var(--text); }

  /* ── screens ── */
  .screen { display: none; }
  .screen.active { display: flex; flex-direction: column; }

  /* ── login ── */
  #screen-login { min-height: 100vh; align-items: center; justify-content: center; padding: 2rem; background: var(--bg3); }
  .login-box { background: var(--bg); border: 1px solid var(--border2); border-radius: var(--radius-lg); padding: 2rem; width: 100%; max-width: 360px; display: flex; flex-direction: column; gap: 14px; }
  .login-logo { font-size: 20px; font-weight: 600; color: var(--text); text-align: center; letter-spacing: -0.3px; }
  .login-sub { font-size: 13px; color: var(--text2); text-align: center; margin-top: -8px; }
  .field-label { font-size: 12px; color: var(--text2); margin-bottom: 4px; }
  input, select, textarea {
    width: 100%; padding: 9px 12px; font-size: 14px; font-family: var(--font);
    border: 1px solid var(--border2); border-radius: var(--radius);
    background: var(--bg); color: var(--text); outline: none;
    transition: border-color 0.15s;
  }
  input:focus, select:focus { border-color: var(--border3); }
  .btn { padding: 9px 16px; font-size: 14px; font-family: var(--font); font-weight: 500; border-radius: var(--radius); cursor: pointer; border: 1px solid var(--border2); background: var(--bg); color: var(--text); transition: background 0.15s; }
  .btn:hover { background: var(--bg2); }
  .btn-primary { background: var(--text); color: var(--bg); border-color: var(--text); }
  .btn-primary:hover { opacity: 0.88; }
  .btn-sm { padding: 6px 12px; font-size: 12px; }
  .btn-danger { border-color: var(--danger); color: var(--danger-text); }
  .btn-danger:hover { background: var(--danger-bg); }
  .err { font-size: 12px; color: var(--danger); display: none; }

  /* ── app shell ── */
  #screen-app { height: 100vh; background: var(--bg3); }
  .app-inner { height: 100vh; display: flex; flex-direction: column; max-width: 1100px; margin: 0 auto; background: var(--bg); border-left: 1px solid var(--border); border-right: 1px solid var(--border); }

  /* ── topbar ── */
  .topbar { display: flex; align-items: center; justify-content: space-between; padding: 10px 18px; border-bottom: 1px solid var(--border); background: var(--bg2); flex-shrink: 0; }
  .topbar-l { display: flex; align-items: center; gap: 8px; }
  .topbar-title { font-size: 15px; font-weight: 600; color: var(--text); letter-spacing: -0.2px; }
  .odot { width: 8px; height: 8px; border-radius: 50%; background: #22c55e; flex-shrink: 0; }
  .topbar-r { display: flex; align-items: center; gap: 8px; }
  .user-pill { display: flex; align-items: center; gap: 6px; padding: 4px 10px 4px 4px; border: 1px solid var(--border); border-radius: 20px; background: var(--bg); }
  .avatar { width: 24px; height: 24px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 10px; font-weight: 600; flex-shrink: 0; }
  .uname { font-size: 13px; color: var(--text); }
  .nbtn { position: relative; width: 32px; height: 32px; border: 1px solid var(--border); border-radius: var(--radius); background: var(--bg); cursor: pointer; display: flex; align-items: center; justify-content: center; }
  .nbtn:hover { background: var(--bg2); }
  .nbadge { position: absolute; top: -5px; right: -5px; min-width: 17px; height: 17px; border-radius: 9px; background: #E24B4A; color: #fff; font-size: 9px; font-weight: 700; display: none; align-items: center; justify-content: center; padding: 0 3px; }

  /* ── tabs ── */
  .tabs-wrap { display: flex; align-items: stretch; border-bottom: 1px solid var(--border); background: var(--bg2); flex-shrink: 0; }
  .tabs { display: flex; padding: 0 12px; overflow-x: auto; flex: 1; scrollbar-width: none; }
  .tabs::-webkit-scrollbar { display: none; }
  .tab { display: flex; align-items: center; gap: 5px; padding: 10px 14px; font-size: 13px; color: var(--text2); cursor: pointer; border-bottom: 2px solid transparent; white-space: nowrap; user-select: none; transition: color 0.15s; }
  .tab:hover { color: var(--text); }
  .tab.active { color: var(--text); font-weight: 500; border-bottom-color: var(--text); }
  .tab-x { font-size: 15px; color: var(--text3); line-height: 1; padding: 0 2px; cursor: pointer; opacity: 0; transition: opacity 0.15s; }
  .tab:hover .tab-x { opacity: 1; }
  .tab-x:hover { color: var(--danger); }
  .add-tab-btn { display: flex; align-items: center; gap: 5px; padding: 0 16px; font-size: 12px; color: var(--text2); cursor: pointer; border-left: 1px solid var(--border); background: transparent; border-top: none; border-right: none; border-bottom: none; white-space: nowrap; font-family: var(--font); transition: color 0.15s, background 0.15s; }
  .add-tab-btn:hover:not(:disabled) { color: var(--text); background: var(--bg); }
  .add-tab-btn:disabled { opacity: 0.38; cursor: not-allowed; }

  /* ── new team form ── */
  .new-team-bar { display: none; align-items: center; gap: 10px; padding: 10px 18px; border-bottom: 1px solid var(--border); background: var(--bg2); flex-shrink: 0; flex-wrap: wrap; }
  .new-team-bar.open { display: flex; }
  .new-team-bar input, .new-team-bar select { width: auto; flex: 1; min-width: 140px; padding: 7px 10px; font-size: 13px; }
  .new-team-bar label { font-size: 12px; color: var(--text2); white-space: nowrap; }

  /* ── main layout ── */
  .main { display: flex; flex: 1; overflow: hidden; }

  /* ── tasks ── */
  .tasks-col { flex: 1; display: flex; flex-direction: column; overflow: hidden; min-width: 0; }
  .tasks-top { display: flex; align-items: center; justify-content: space-between; padding: 14px 18px 10px; flex-shrink: 0; }
  .section-title { font-size: 14px; font-weight: 500; color: var(--text); }
  .prog-wrap { display: flex; align-items: center; gap: 8px; }
  .prog-bar { width: 90px; height: 5px; background: var(--border); border-radius: 3px; overflow: hidden; }
  .prog-fill { height: 100%; border-radius: 3px; transition: width 0.3s; }
  .prog-txt { font-size: 12px; color: var(--text3); min-width: 32px; }
  .add-row { display: flex; gap: 8px; padding: 0 18px 12px; flex-shrink: 0; }
  .add-row input { flex: 1; padding: 8px 11px; font-size: 13px; }
  .add-row select { width: 100px; padding: 8px 10px; font-size: 13px; }
  .add-row button { padding: 8px 16px; font-size: 13px; font-weight: 500; white-space: nowrap; background: var(--text); color: var(--bg); border: none; border-radius: var(--radius); cursor: pointer; font-family: var(--font); }
  .add-row button:hover { opacity: 0.88; }
  .task-list { flex: 1; overflow-y: auto; padding: 0 18px 14px; }
  .task-item { display: flex; align-items: flex-start; gap: 10px; padding: 10px 0; border-bottom: 1px solid var(--border); }
  .task-item:last-child { border-bottom: none; }
  .cb { width: 17px; height: 17px; border: 1.5px solid var(--border2); border-radius: 4px; cursor: pointer; flex-shrink: 0; margin-top: 2px; display: flex; align-items: center; justify-content: center; transition: all 0.15s; background: var(--bg); }
  .cb.chk { background: var(--text); border-color: var(--text); }
  .cb svg { display: none; }
  .cb.chk svg { display: block; }
  .task-body { flex: 1; display: flex; flex-direction: column; gap: 4px; min-width: 0; }
  .task-txt { font-size: 13px; color: var(--text); line-height: 1.5; }
  .task-txt.done { text-decoration: line-through; color: var(--text3); }
  .task-meta { display: flex; align-items: center; gap: 7px; flex-wrap: wrap; }
  .prio { font-size: 11px; font-weight: 500; padding: 2px 7px; border-radius: 5px; }
  .p-urgent { background: #FCEBEB; color: #A32D2D; }
  .p-medium { background: #FAEEDA; color: #633806; }
  .p-low { background: #EAF3DE; color: #27500A; }
  .task-who { font-size: 11px; color: var(--text3); }
  .task-del { font-size: 16px; color: var(--text3); cursor: pointer; opacity: 0; padding: 0 3px; line-height: 1; transition: opacity 0.15s; flex-shrink: 0; }
  .task-item:hover .task-del { opacity: 1; }
  .task-del:hover { color: var(--danger); }

  /* ── chat ── */
  .chat-col { width: 290px; border-left: 1px solid var(--border); display: flex; flex-direction: column; flex-shrink: 0; }
  .chat-hdr { padding: 14px 16px 10px; border-bottom: 1px solid var(--border); flex-shrink: 0; }
  .chat-title { font-size: 14px; font-weight: 500; color: var(--text); }
  .chat-msgs { flex: 1; overflow-y: auto; padding: 12px 14px; display: flex; flex-direction: column; gap: 10px; }
  .msg { display: flex; flex-direction: column; gap: 3px; }
  .msg.own { align-items: flex-end; }
  .msg-meta { display: flex; align-items: center; gap: 5px; font-size: 11px; color: var(--text3); }
  .mav { width: 18px; height: 18px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 8px; font-weight: 600; flex-shrink: 0; }
  .bubble { font-size: 13px; padding: 7px 11px; border-radius: 10px; max-width: 92%; line-height: 1.5; background: var(--bg2); color: var(--text); border-top-left-radius: 3px; word-break: break-word; }
  .msg.own .bubble { background: var(--text); color: var(--bg); border-top-left-radius: 10px; border-top-right-radius: 3px; }
  .chat-inp { padding: 10px 12px; border-top: 1px solid var(--border); display: flex; gap: 7px; align-items: center; flex-shrink: 0; }
  .chat-inp input { flex: 1; padding: 8px 12px; font-size: 13px; border-radius: 16px; }
  .send-btn { width: 30px; height: 30px; border-radius: 50%; background: var(--text); border: none; cursor: pointer; display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
  .send-btn:hover { opacity: 0.8; }

  /* ── notifications ── */
  .notif-panel { display: none; border-top: 1px solid var(--border); background: var(--bg2); padding: 10px 18px; max-height: 160px; overflow-y: auto; flex-shrink: 0; }
  .notif-panel.open { display: block; }
  .notif-hdr { display: flex; align-items: center; justify-content: space-between; margin-bottom: 8px; }
  .notif-label { font-size: 13px; font-weight: 500; color: var(--text); }
  .notif-clear { font-size: 12px; color: var(--text3); cursor: pointer; }
  .notif-clear:hover { color: var(--text2); }
  .notif-item { font-size: 12px; color: var(--text2); padding: 4px 0; border-bottom: 1px solid var(--border); line-height: 1.5; }
  .notif-item:last-child { border-bottom: none; }
  .nt { color: var(--text3); margin-left: 5px; }

  .empty { padding: 24px; text-align: center; font-size: 13px; color: var(--text3); }

  /* ── responsive ── */
  @media (max-width: 600px) {
    .chat-col { display: none; }
    .topbar-title { font-size: 14px; }
    .add-row select { width: 80px; }
  }
</style>
</head>
<body>

<!-- LOGIN -->
<div id="screen-login" class="screen active">
  <div class="login-box">
    <div class="login-logo">🎪 Festival HQ</div>
    <div class="login-sub">Sign in to your team workspace</div>
    <div>
      <div class="field-label">Your name</div>
      <input type="text" id="login-name" placeholder="e.g. Sarah" maxlength="30" autocomplete="name" />
    </div>
    <div>
      <div class="field-label">Your team</div>
      <select id="login-team"><option value="">Select a team...</option></select>
    </div>
    <button class="btn btn-primary" style="width:100%;margin-top:4px" onclick="doLogin()">Enter Festival HQ</button>
    <div class="err" id="login-err">Please enter your name and select a team.</div>
    <div style="font-size:11px;color:var(--text3);text-align:center;margin-top:4px">Your data is saved in this browser's local storage.<br>Share this page with your team so everyone can sign in.</div>
  </div>
</div>

<!-- APP -->
<div id="screen-app" class="screen">
  <div class="app-inner">

    <div class="topbar">
      <div class="topbar-l">
        <span class="odot"></span>
        <span class="topbar-title">Festival HQ</span>
      </div>
      <div class="topbar-r">
        <div class="nbtn" id="notif-btn" onclick="toggleNotif()" title="Notifications">
          <svg width="15" height="15" viewBox="0 0 15 15" fill="none">
            <path d="M7.5 1.5C7.5 1.5 3.5 3.5 3.5 7.5V9.5L2.5 10.5V11.5H12.5V10.5L11.5 9.5V7.5C11.5 3.5 7.5 1.5 7.5 1.5Z" stroke="currentColor" stroke-width="1.1" fill="none"/>
            <path d="M6 11.5C6 12.3 6.7 13 7.5 13C8.3 13 9 12.3 9 11.5" stroke="currentColor" stroke-width="1.1" fill="none"/>
          </svg>
          <div class="nbadge" id="nbadge">0</div>
        </div>
        <div class="user-pill">
          <div class="avatar" id="topbar-av"></div>
          <span class="uname" id="topbar-name"></span>
        </div>
        <button class="btn btn-sm" onclick="doLogout()">Sign out</button>
      </div>
    </div>

    <div class="tabs-wrap">
      <div class="tabs" id="tabs"></div>
      <button class="add-tab-btn" id="add-tab-btn" onclick="toggleNewTeamBar()">
        <svg width="11" height="11" viewBox="0 0 11 11" fill="none"><path d="M5.5 1V10M1 5.5H10" stroke="currentColor" stroke-width="1.5" stroke-linecap="round"/></svg>
        Add team
      </button>
    </div>

    <div class="new-team-bar" id="new-team-bar">
      <label>Team name:</label>
      <input type="text" id="new-team-name" placeholder="e.g. Ticketing" maxlength="20" style="max-width:180px" onkeydown="if(event.key==='Enter')createTeam()" />
      <label>Colour:</label>
      <select id="new-team-color" style="max-width:120px">
        <option value="coral">Coral</option>
        <option value="teal">Teal</option>
        <option value="purple">Purple</option>
        <option value="amber">Amber</option>
        <option value="blue">Blue</option>
        <option value="green">Green</option>
        <option value="pink">Pink</option>
      </select>
      <button class="btn btn-sm" onclick="createTeam()">Create</button>
      <button class="btn btn-sm" onclick="closeNewTeamBar()">Cancel</button>
    </div>

    <div class="main">
      <div class="tasks-col">
        <div class="tasks-top">
          <div class="section-title" id="team-label"></div>
          <div class="prog-wrap">
            <div class="prog-bar"><div class="prog-fill" id="prog-fill"></div></div>
            <div class="prog-txt" id="prog-txt"></div>
          </div>
        </div>
        <div class="add-row">
          <input type="text" id="task-in" placeholder="Add a task..." onkeydown="if(event.key==='Enter')addTask()" />
          <select id="prio-in">
            <option value="low">Low</option>
            <option value="medium" selected>Medium</option>
            <option value="urgent">Urgent</option>
          </select>
          <button onclick="addTask()">+ Add</button>
        </div>
        <div class="task-list" id="task-list"></div>
      </div>

      <div class="chat-col">
        <div class="chat-hdr"><div class="chat-title" id="chat-title"></div></div>
        <div class="chat-msgs" id="chat-msgs"></div>
        <div class="chat-inp">
          <input type="text" id="chat-in" placeholder="Message your team..." onkeydown="if(event.key==='Enter')sendMsg()" />
          <button class="send-btn" onclick="sendMsg()">
            <svg width="12" height="12" viewBox="0 0 12 12" fill="none"><path d="M1.5 10.5L10.5 6L1.5 1.5V5L7.5 6L1.5 7V10.5Z" fill="white"/></svg>
          </button>
        </div>
      </div>
    </div>

    <div class="notif-panel" id="notif-panel">
      <div class="notif-hdr">
        <span class="notif-label">Notifications</span>
        <span class="notif-clear" onclick="clearNotifs()">Clear all</span>
      </div>
      <div id="notif-list"></div>
    </div>

  </div>
</div>

<script>
const COLOR_MAP = {
  coral:  { color:'#D85A30', bg:'#FAECE7', tc:'#712B13' },
  teal:   { color:'#1D9E75', bg:'#E1F5EE', tc:'#085041' },
  purple: { color:'#7F77DD', bg:'#EEEDFE', tc:'#3C3489' },
  amber:  { color:'#BA7517', bg:'#FAEEDA', tc:'#633806' },
  blue:   { color:'#378ADD', bg:'#E6F1FB', tc:'#0C447C' },
  green:  { color:'#639922', bg:'#EAF3DE', tc:'#27500A' },
  pink:   { color:'#D4537E', bg:'#FBEAF0', tc:'#72243E' },
};

const DEFAULT_TEAMS = [
  { id:'marketing',     label:'Marketing',     colorKey:'purple' },
  { id:'entertainment', label:'Entertainment', colorKey:'teal'   },
  { id:'decor',         label:'Decor',         colorKey:'pink'   },
  { id:'management',    label:'Management',    colorKey:'blue'   },
  { id:'fnb',           label:'Food & Bev',    colorKey:'amber'  },
  { id:'logistics',     label:'Logistics',     colorKey:'green'  },
];

const SEED_TASKS = {
  marketing:     ['Design festival poster|urgent','Set up social media pages|medium','Send press releases|medium','Create event hashtag|low','Email newsletter blast|low'],
  entertainment: ['Book headline act|urgent','Confirm support bands|medium','Schedule sound check|medium','Arrange MC|low','Order stage lighting|medium'],
  decor:         ['Order fairy lights|medium','Design entrance arch|medium','Source floral arrangements|medium','Plan colour scheme|low','Hire decor crew|medium'],
  management:    ['Finalise event timeline|urgent','Brief all team leads|urgent','Obtain venue permits|urgent','Set up volunteer rota|medium','Arrange security team|medium'],
  fnb:           ['Source food vendors|urgent','Plan beverage stations|medium','Arrange water stations|medium','Order disposable cups|low','Confirm health & safety|urgent'],
  logistics:     ['Arrange parking plan|medium','Hire shuttle buses|urgent','Set up signage|medium','Plan load-in schedule|medium','Coordinate waste disposal|low'],
};

const SEED_MSGS = {
  marketing:     [{u:'Zara',t:'09:14',txt:'Poster draft is ready for review!'},{u:'Liam',t:'09:35',txt:'Instagram page is live!'}],
  entertainment: [{u:'Priya',t:'10:02',txt:'DJ confirmed for Friday night'},{u:'Priya',t:'10:18',txt:'They arrive at 3pm, setup by 5pm'}],
  decor:         [{u:'Mei',t:'11:00',txt:'Fairy lights order placed ✓'},{u:'James',t:'11:22',txt:'Arch design looks great!'}],
  management:    [{u:'Director',t:'08:30',txt:'Morning standup at 9am everyone'},{u:'Sam',t:'09:00',txt:'Permits approved by the council!'}],
  fnb:           [{u:'Chef',t:'12:00',txt:'8 food stalls confirmed'},{u:'Chef',t:'12:15',txt:'3 stalls are fully vegetarian'}],
  logistics:     [{u:'Tom',t:'13:00',txt:'Shuttle route confirmed'},{u:'Tom',t:'13:08',txt:'6 buses running every 20 mins'}],
};

const STORAGE_KEY = 'festival_hq_v1';
const MAX_CUSTOM  = 2;

let S             = {};
let currentUser   = null;
let currentTeam   = null;
let activeTeam    = null;
let notifOpen     = false;

/* ── persistence ── */
function loadState() {
  try {
    const raw = localStorage.getItem(STORAGE_KEY);
    if (raw) S = JSON.parse(raw);
  } catch(e) {}

  if (!S.teams)       S.teams       = DEFAULT_TEAMS.map(t => ({ ...t }));
  if (!S.data)        S.data        = {};
  if (!S.customCount) S.customCount = 0;
  if (!S._notifs)     S._notifs     = [];

  S.teams.forEach(t => {
    if (!S.data[t.id]) S.data[t.id] = { tasks: [], msgs: [] };

    if (!S.data[t.id].tasks.length && SEED_TASKS[t.id]) {
      let id = 0;
      S.data[t.id].tasks = SEED_TASKS[t.id].map(x => {
        const [text, prio] = x.split('|');
        return { id: id++, text, prio: prio || 'medium', done: false, by: 'system' };
      });
    }
    if (!S.data[t.id].msgs.length && SEED_MSGS[t.id]) {
      S.data[t.id].msgs = SEED_MSGS[t.id].map(m => ({ u: m.u, t: m.t, txt: m.txt }));
    }
  });
}

function saveState() {
  try { localStorage.setItem(STORAGE_KEY, JSON.stringify(S)); } catch(e) {}
}

/* ── helpers ── */
function initials(name) {
  return name.trim().split(' ').map(w => w[0]).join('').slice(0, 2).toUpperCase();
}
function getTeam(id)   { return S.teams.find(t => t.id === id) || S.teams[0]; }
function teamColors(id){ return COLOR_MAP[getTeam(id).colorKey] || COLOR_MAP.purple; }
function nowTime()     { const d = new Date(); return d.getHours().toString().padStart(2,'0') + ':' + d.getMinutes().toString().padStart(2,'0'); }

/* ── login ── */
function populateLoginTeams() {
  const sel = document.getElementById('login-team');
  sel.innerHTML = '<option value="">Select a team...</option>';
  S.teams.forEach(t => {
    const o = document.createElement('option');
    o.value = t.id; o.textContent = t.label;
    sel.appendChild(o);
  });
}

function doLogin() {
  const name = document.getElementById('login-name').value.trim();
  const team = document.getElementById('login-team').value;
  if (!name || !team) { document.getElementById('login-err').style.display = 'block'; return; }
  document.getElementById('login-err').style.display = 'none';
  currentUser = name; currentTeam = team; activeTeam = team;
  saveState();
  showApp();
}

function doLogout() {
  currentUser = currentTeam = activeTeam = null;
  closeNewTeamBar();
  document.getElementById('screen-app').classList.remove('active');
  document.getElementById('screen-login').classList.add('active');
  document.getElementById('login-name').value = '';
  document.getElementById('login-team').value = '';
  populateLoginTeams();
}

/* ── app ── */
function showApp() {
  document.getElementById('screen-login').classList.remove('active');
  document.getElementById('screen-app').classList.add('active');
  const tc = teamColors(currentTeam);
  const av = document.getElementById('topbar-av');
  av.textContent = initials(currentUser);
  av.style.background = tc.bg; av.style.color = tc.tc;
  document.getElementById('topbar-name').textContent = currentUser;
  updateAddTabBtn();
  renderTabs();
  switchTeam(activeTeam);
  renderNotifBadge();
}

function updateAddTabBtn() {
  const btn = document.getElementById('add-tab-btn');
  btn.disabled = S.customCount >= MAX_CUSTOM;
  btn.title    = S.customCount >= MAX_CUSTOM ? 'Maximum 2 custom teams reached' : 'Add a custom team';
}

/* ── tabs ── */
function renderTabs() {
  document.getElementById('tabs').innerHTML = S.teams.map(t => {
    const isCustom = !DEFAULT_TEAMS.find(d => d.id === t.id);
    return `<div class="tab ${t.id === activeTeam ? 'active' : ''}" onclick="switchTeam('${t.id}')">
      ${t.label}
      ${isCustom ? `<span class="tab-x" onclick="event.stopPropagation();removeTeam('${t.id}')" title="Remove team">×</span>` : ''}
    </div>`;
  }).join('');
}

function switchTeam(tid) {
  activeTeam = tid;
  renderTabs();
  document.getElementById('team-label').textContent  = getTeam(tid).label + ' tasks';
  document.getElementById('chat-title').textContent  = getTeam(tid).label + ' chat';
  renderTasks(); renderChat();
}

/* ── new team ── */
function toggleNewTeamBar() {
  if (S.customCount >= MAX_CUSTOM) return;
  const bar = document.getElementById('new-team-bar');
  const open = bar.classList.toggle('open');
  if (open) setTimeout(() => document.getElementById('new-team-name').focus(), 50);
}

function closeNewTeamBar() {
  document.getElementById('new-team-bar').classList.remove('open');
  document.getElementById('new-team-name').value = '';
}

function createTeam() {
  if (S.customCount >= MAX_CUSTOM) return;
  const name     = document.getElementById('new-team-name').value.trim();
  const colorKey = document.getElementById('new-team-color').value;
  if (!name) { document.getElementById('new-team-name').focus(); return; }
  const id = 'custom_' + Date.now();
  S.teams.push({ id, label: name, colorKey });
  S.data[id]   = { tasks: [], msgs: [] };
  S.customCount++;
  closeNewTeamBar();
  updateAddTabBtn();
  saveState();
  renderTabs();
  switchTeam(id);
  pushNotif(`New team "${name}" was created`);
}

function removeTeam(id) {
  const t = getTeam(id);
  if (!confirm(`Remove the "${t.label}" team and all its data?`)) return;
  S.teams       = S.teams.filter(x => x.id !== id);
  delete S.data[id];
  S.customCount = Math.max(0, S.customCount - 1);
  if (activeTeam === id) activeTeam = S.teams[0].id;
  updateAddTabBtn();
  saveState(); renderTabs(); switchTeam(activeTeam);
}

/* ── tasks ── */
function renderTasks() {
  const tasks = S.data[activeTeam].tasks;
  const done  = tasks.filter(t => t.done).length;
  const pct   = tasks.length ? Math.round(done / tasks.length * 100) : 0;
  const tc    = teamColors(activeTeam);
  document.getElementById('prog-fill').style.width      = pct + '%';
  document.getElementById('prog-fill').style.background = tc.color;
  document.getElementById('prog-txt').textContent        = done + '/' + tasks.length;
  const el = document.getElementById('task-list');
  if (!tasks.length) { el.innerHTML = '<div class="empty">No tasks yet — add one above</div>'; return; }
  const sorted = [...tasks].sort((a, b) => {
    const w = { urgent: 0, medium: 1, low: 2 };
    if (a.done !== b.done) return a.done ? 1 : -1;
    return (w[a.prio] || 1) - (w[b.prio] || 1);
  });
  el.innerHTML = sorted.map(t => `
    <div class="task-item">
      <div class="cb ${t.done ? 'chk' : ''}" onclick="toggleTask(${t.id})">
        <svg width="10" height="10" viewBox="0 0 10 10" fill="none">
          <path d="M1.5 5L4 7.5L8.5 2.5" stroke="white" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
      </div>
      <div class="task-body">
        <div class="task-txt ${t.done ? 'done' : ''}">${escHtml(t.text)}</div>
        <div class="task-meta">
          <span class="prio p-${t.prio}">${t.prio}</span>
          ${t.by && t.by !== 'system' ? `<span class="task-who">added by ${escHtml(t.by)}</span>` : ''}
        </div>
      </div>
      <span class="task-del" onclick="deleteTask(${t.id})" title="Delete">×</span>
    </div>`).join('');
}

function addTask() {
  const inp  = document.getElementById('task-in');
  const prio = document.getElementById('prio-in').value;
  const val  = inp.value.trim();
  if (!val) return;
  const tasks = S.data[activeTeam].tasks;
  const newId = tasks.length ? Math.max(...tasks.map(t => t.id)) + 1 : 0;
  tasks.push({ id: newId, text: val, prio, done: false, by: currentUser });
  inp.value = '';
  pushNotif(`${currentUser} added "${val}" to ${getTeam(activeTeam).label}`);
  saveState(); renderTasks();
}

function toggleTask(id) {
  const t = S.data[activeTeam].tasks.find(x => x.id === id);
  if (t) {
    t.done = !t.done;
    if (t.done) pushNotif(`${currentUser} completed "${t.text}" in ${getTeam(activeTeam).label}`);
  }
  saveState(); renderTasks();
}

function deleteTask(id) {
  S.data[activeTeam].tasks = S.data[activeTeam].tasks.filter(x => x.id !== id);
  saveState(); renderTasks();
}

/* ── chat ── */
function renderChat() {
  const msgs = S.data[activeTeam].msgs;
  const tc   = teamColors(activeTeam);
  const el   = document.getElementById('chat-msgs');
  if (!msgs.length) { el.innerHTML = '<div class="empty">No messages yet</div>'; return; }
  el.innerHTML = msgs.map(m => {
    const own = m.u === currentUser;
    return `<div class="msg ${own ? 'own' : ''}">
      <div class="msg-meta">
        ${!own ? `<div class="mav" style="background:${tc.bg};color:${tc.tc}">${initials(m.u)}</div>` : ''}
        <span>${own ? 'You' : escHtml(m.u)}</span>
        <span class="nt">${m.t}</span>
      </div>
      <div class="bubble">${escHtml(m.txt)}</div>
    </div>`;
  }).join('');
  el.scrollTop = el.scrollHeight;
}

function sendMsg() {
  const inp = document.getElementById('chat-in');
  const val = inp.value.trim();
  if (!val) return;
  S.data[activeTeam].msgs.push({ u: currentUser, t: nowTime(), txt: val });
  inp.value = '';
  pushNotif(`${currentUser} in ${getTeam(activeTeam).label}: "${val.slice(0, 50)}${val.length > 50 ? '...' : ''}"`);
  saveState(); renderChat();
}

/* ── notifications ── */
function pushNotif(msg) {
  S._notifs.unshift({ msg, t: nowTime() });
  if (S._notifs.length > 40) S._notifs.pop();
  renderNotifBadge(); renderNotifList();
}

function renderNotifBadge() {
  const n = S._notifs.length;
  const b = document.getElementById('nbadge');
  if (n > 0) { b.style.display = 'flex'; b.textContent = n > 9 ? '9+' : n; }
  else        { b.style.display = 'none'; }
}

function toggleNotif() {
  notifOpen = !notifOpen;
  document.getElementById('notif-panel').classList.toggle('open', notifOpen);
  renderNotifList();
}

function renderNotifList() {
  const el = document.getElementById('notif-list');
  if (!S._notifs.length) { el.innerHTML = '<div class="empty">No notifications yet</div>'; return; }
  el.innerHTML = S._notifs.slice(0, 20).map(n =>
    `<div class="notif-item">${escHtml(n.msg)}<span class="nt">${n.t}</span></div>`
  ).join('');
}

function clearNotifs() {
  S._notifs = [];
  saveState(); renderNotifBadge(); renderNotifList();
}

/* ── security ── */
function escHtml(s) {
  return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;');
}

/* ── boot ── */
loadState();
populateLoginTeams();

document.getElementById('login-name').addEventListener('keydown', e => {
  if (e.key === 'Enter') document.getElementById('login-team').focus();
});
document.getElementById('login-team').addEventListener('keydown', e => {
  if (e.key === 'Enter') doLogin();
});
</script>
</body>
</html>
