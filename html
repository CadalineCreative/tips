<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover, user-scalable=no">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="Tips">
<meta name="theme-color" content="#16120E">
<title>Tip Tracker</title>
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='14' fill='%2316120E'/%3E%3Ctext x='32' y='44' font-size='34' text-anchor='middle' fill='%23C89B5A' font-family='Georgia'%3E%24%3C/text%3E%3C/svg%3E">
<style>
:root{
  --ink:#16120E; --panel:#211B15; --panel2:#2A2219; --line:#3A3126;
  --text:#EFE6D8; --dim:#A6957E; --faint:#6E5F4C;
  --brass:#C89B5A; --brass-bright:#E2B978;
  --cc:#5FB3A1; --cash:#93BF6B; --out:#C9705B;
  --mono:ui-monospace,"SF Mono",SFMono-Regular,Menlo,monospace;
  --serif:ui-serif,"New York",Georgia,serif;
  --sans:-apple-system,BlinkMacSystemFont,"SF Pro Text","Segoe UI",sans-serif;
}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent}
html,body{height:100%}
body{background:var(--ink);color:var(--text);font-family:var(--sans);font-size:15px;
  padding-top:env(safe-area-inset-top);overscroll-behavior:none}
button{font:inherit;color:inherit;background:none;border:none;cursor:pointer}
input,select{font:inherit;color:var(--text);background:var(--panel2);border:1px solid var(--line);
  border-radius:8px;padding:9px 10px;width:100%;appearance:none;-webkit-appearance:none}
input:focus,select:focus,button:focus-visible{outline:2px solid var(--brass);outline-offset:1px}
input[type=number]{font-family:var(--mono)}
label{display:block;font-size:12px;color:var(--dim);margin:12px 0 5px;letter-spacing:.03em}
.money{font-family:var(--mono);font-variant-numeric:tabular-nums}
#app{max-width:520px;margin:0 auto;padding:10px 12px calc(96px + env(safe-area-inset-bottom))}

/* header */
header{display:flex;align-items:baseline;gap:10px;padding:6px 2px 10px}
#monthTitle{font-family:var(--serif);font-size:26px;font-weight:600;letter-spacing:.01em}
#yearTitle{font-family:var(--serif);font-size:16px;color:var(--dim)}
header .nav{margin-left:auto;display:flex;gap:4px}
header .nav button{width:38px;height:38px;border-radius:10px;background:var(--panel);
  border:1px solid var(--line);font-size:17px;color:var(--brass)}
header .nav button:disabled{opacity:.3}

/* banners */
.banner{display:flex;align-items:center;gap:10px;width:100%;text-align:left;
  background:var(--panel);border:1px solid var(--line);border-left:3px solid var(--brass);
  border-radius:10px;padding:10px 12px;margin-bottom:10px;font-size:13.5px}
.banner b{color:var(--brass-bright)}
.banner .x{margin-left:auto;color:var(--faint);font-size:16px;padding:2px 6px}

/* goal bar */
#goalCard{background:var(--panel);border:1px solid var(--line);border-radius:12px;padding:12px 14px;margin-bottom:10px}
#goalTop{display:flex;justify-content:space-between;align-items:baseline;margin-bottom:8px}
#goalLabel{font-size:12px;letter-spacing:.08em;color:var(--dim);text-transform:uppercase}
#goalNums{font-size:15px}
#goalNums b{color:var(--brass-bright);font-size:17px}
#goalTrack{height:14px;border-radius:7px;background:var(--ink);border:1px solid var(--line);overflow:hidden}
#goalFill{height:100%;width:0%;border-radius:7px;
  background:linear-gradient(90deg,#8a6a38,var(--brass) 60%,var(--brass-bright));
  transition:width .5s ease}
#goalSub{margin-top:7px;font-size:12px;color:var(--faint)}

/* receipt strip — Friday check */
#receipt{display:block;width:100%;text-align:left;background:#F5EBDB;color:#241C12;border-radius:4px;
  padding:11px 14px 13px;margin-bottom:12px;font-family:var(--mono);font-variant-numeric:tabular-nums;
  position:relative;box-shadow:0 3px 10px rgba(0,0,0,.35)}
#receipt::before,#receipt::after{content:"";position:absolute;left:0;right:0;height:7px;
  background-image:radial-gradient(circle at 5px 0px,var(--ink) 4px,transparent 4.5px);
  background-size:12px 7px;background-repeat:repeat-x}
#receipt::before{top:-1px}
#receipt::after{bottom:-1px;transform:scaleY(-1)}
#receipt .rTitle{font-size:11px;letter-spacing:.14em;color:#6b5b43;margin-bottom:2px}
#receipt .rBig{font-size:26px;font-weight:700;letter-spacing:.01em}
#receipt .rSub{font-size:11.5px;color:#6b5b43;margin-top:3px;line-height:1.5;white-space:pre-line}

/* calendar */
#calWrap{background:var(--panel);border:1px solid var(--line);border-radius:12px;padding:10px 8px 8px}
#dow{display:grid;grid-template-columns:repeat(7,1fr);text-align:center;font-size:10.5px;
  letter-spacing:.08em;color:var(--faint);margin-bottom:6px}
#grid{display:grid;grid-template-columns:repeat(7,1fr);gap:3px}
.day{min-height:52px;border-radius:9px;padding:4px 3px 3px;background:transparent;
  display:flex;flex-direction:column;align-items:center;gap:2px;border:1px solid transparent}
.day.other{opacity:.28}
.day .n{font-size:13.5px;line-height:1.2}
.day.today{border-color:var(--brass)}
.day.today .n{color:var(--brass-bright);font-weight:700}
.day .dots{display:flex;gap:3px;min-height:7px}
.dot{width:6px;height:6px;border-radius:50%}
.dot.sched{border:1.5px solid var(--brass);width:5px;height:5px}
.dot.logged{background:var(--cash)}
.dot.due{background:var(--out)}
.day .amt{font-family:var(--mono);font-size:9.5px;color:var(--cash);min-height:11px}

/* legend */
#legend{display:flex;gap:14px;justify-content:center;margin-top:9px;font-size:11px;color:var(--dim)}
#legend span{display:flex;align-items:center;gap:5px}

/* bottom action bar */
#actions{position:fixed;left:0;right:0;bottom:0;display:flex;gap:10px;justify-content:center;
  padding:10px 14px calc(12px + env(safe-area-inset-bottom));
  background:linear-gradient(transparent,var(--ink) 30%)}
#actions button{flex:1;max-width:246px;padding:14px 10px;border-radius:12px;font-size:15px;font-weight:600}
#btnLog{background:var(--panel);border:1px solid var(--brass);color:var(--brass-bright)}
#btnTips{background:var(--brass);color:#241C12}

/* sheets (modals) */
#overlay{position:fixed;inset:0;background:rgba(0,0,0,.55);opacity:0;pointer-events:none;transition:opacity .2s}
#overlay.show{opacity:1;pointer-events:auto}
.sheet{position:fixed;left:0;right:0;bottom:0;max-height:88vh;overflow-y:auto;-webkit-overflow-scrolling:touch;
  background:var(--panel);border-radius:16px 16px 0 0;border:1px solid var(--line);border-bottom:none;
  padding:8px 16px calc(24px + env(safe-area-inset-bottom));transform:translateY(105%);transition:transform .25s ease;z-index:5}
.sheet.show{transform:translateY(0)}
.sheet .grab{width:38px;height:4px;border-radius:2px;background:var(--line);margin:4px auto 12px}
.sheet h2{font-family:var(--serif);font-size:20px;margin-bottom:2px}
.sheet .sub{font-size:12.5px;color:var(--dim);margin-bottom:8px}
.row2{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.row3{display:grid;grid-template-columns:1fr 1fr 1fr;gap:8px}
.seg{display:flex;gap:6px;margin-top:4px}
.seg button{flex:1;padding:10px 4px;border-radius:9px;border:1px solid var(--line);background:var(--panel2);font-size:14px}
.seg button.on{background:var(--brass);color:#241C12;border-color:var(--brass);font-weight:600}
.primary{display:block;width:100%;margin-top:16px;padding:14px;border-radius:12px;background:var(--brass);
  color:#241C12;font-weight:700;font-size:15px}
.secondary{display:block;width:100%;margin-top:10px;padding:12px;border-radius:12px;background:var(--panel2);
  border:1px solid var(--line);color:var(--text);font-size:14px}
.danger{color:var(--out)}
.hint{font-size:11.5px;color:var(--faint);margin-top:6px;line-height:1.5}

/* shift cards / lists */
.card{background:var(--panel2);border:1px solid var(--line);border-radius:11px;padding:11px 12px;margin-top:10px}
.card .head{display:flex;align-items:baseline;gap:8px}
.card .head b{font-size:15px;text-transform:capitalize}
.card .head .time{color:var(--dim);font-size:12.5px}
.card .head .right{margin-left:auto;display:flex;gap:8px;align-items:center}
.tag{font-size:10.5px;padding:2px 7px;border-radius:20px;letter-spacing:.04em}
.tag.due{background:rgba(201,112,91,.18);color:var(--out)}
.tag.sched{background:rgba(200,155,90,.15);color:var(--brass)}
.tag.done{background:rgba(147,191,107,.15);color:var(--cash)}
.breakdown{margin-top:8px;font-family:var(--mono);font-variant-numeric:tabular-nums;font-size:12.5px;line-height:1.75}
.breakdown .ln{display:flex;justify-content:space-between}
.breakdown .ln.total{border-top:1px dashed var(--line);margin-top:4px;padding-top:4px;font-weight:700;font-size:13.5px}
.k-cc{color:var(--cc)} .k-cash{color:var(--cash)} .k-out{color:var(--out)} .k-brass{color:var(--brass-bright)}
.small{font-size:11px;color:var(--faint)}
.linkish{color:var(--brass);text-decoration:underline;font-size:13px;padding:6px 0}

/* live calc box in tips form */
#calcBox{margin-top:14px;border:1px dashed var(--line);border-radius:11px;padding:10px 12px;
  font-family:var(--mono);font-variant-numeric:tabular-nums;font-size:12.5px;line-height:1.8}
#calcBox .ln{display:flex;justify-content:space-between}

/* checks table */
.chk{border-top:1px solid var(--line);padding:12px 0}
.chk .cHead{display:flex;justify-content:space-between;font-size:13px;margin-bottom:6px}
.chk .grid{display:grid;grid-template-columns:1fr 1fr;gap:8px;font-family:var(--mono);font-size:12.5px}
.chk .cell{background:var(--panel2);border:1px solid var(--line);border-radius:8px;padding:7px 9px}
.chk .cell .lab{font-family:var(--sans);font-size:10px;color:var(--faint);letter-spacing:.05em;margin-bottom:2px}
.settingsGroup{border-top:1px solid var(--line);margin-top:18px;padding-top:12px}
.settingsGroup h3{font-size:13px;letter-spacing:.07em;text-transform:uppercase;color:var(--dim);font-weight:600}
@media (prefers-reduced-motion:reduce){*{transition:none!important}}
</style>
</head>
<body>
<div id="app">
  <header>
    <span id="monthTitle">July</span><span id="yearTitle">2026</span>
    <div class="nav">
      <button id="prevM" aria-label="Previous month">‹</button>
      <button id="nextM" aria-label="Next month">›</button>
      <button id="gear" aria-label="Settings">⚙︎</button>
    </div>
  </header>

  <div id="banners"></div>

  <div id="goalCard">
    <div id="goalTop">
      <span id="goalLabel">July take-home</span>
      <span id="goalNums" class="money"><b>$0</b> / $4,000</span>
    </div>
    <div id="goalTrack"><div id="goalFill"></div></div>
    <div id="goalSub">Counted the night worked · after withholding &amp; tipshare</div>
  </div>

  <button id="receipt" aria-label="Open paycheck log">
    <div class="rTitle">THIS FRIDAY'S CHECK · EST.</div>
    <div class="rBig" id="rAmount">$0.00</div>
    <div class="rSub" id="rDetail"></div>
  </button>

  <div id="calWrap">
    <div id="dow"><span>SUN</span><span>MON</span><span>TUE</span><span>WED</span><span>THU</span><span>FRI</span><span>SAT</span></div>
    <div id="grid"></div>
    <div id="legend">
      <span><i class="dot sched"></i> scheduled</span>
      <span><i class="dot due"></i> tips due</span>
      <span><i class="dot logged"></i> logged</span>
    </div>
  </div>
</div>

<div id="actions">
  <button id="btnLog">＋ Log Shift</button>
  <button id="btnTips">＋ Input Tips</button>
</div>

<div id="overlay"></div>

<div class="sheet" id="shDay">
  <div class="grab"></div>
  <h2 id="dayTitle">Day</h2>
  <div class="sub" id="daySub"></div>
  <div id="dayList"></div>
  <button class="secondary" id="dayAddShift">＋ Log a shift on this day</button>
</div>

<div class="sheet" id="shLog">
  <div class="grab"></div>
  <h2>Log Shift</h2>
  <div class="sub">Schedule ahead — presets fill in, everything overridable.</div>
  <label>Date</label>
  <input type="date" id="logDate" min="2026-01-01" max="2028-12-31">
  <label>Shift type</label>
  <div class="seg" id="logType">
    <button data-t="brunch">Brunch</button>
    <button data-t="lunch">Lunch</button>
    <button data-t="dinner" class="on">Dinner</button>
  </div>
  <div class="row2">
    <div><label>Start</label><input type="time" id="logStart"></div>
    <div><label>End</label><input type="time" id="logEnd"></div>
  </div>
  <div class="hint" id="logPreset"></div>
  <button class="primary" id="logSave">Add shift</button>
  <div id="upcomingWrap">
    <div class="settingsGroup"><h3>Upcoming shifts</h3></div>
    <div id="upcomingList"></div>
    <button class="secondary" id="icsBtn">📅 Download .ics → Add to Apple Calendar</button>
    <div class="hint">The .ics holds all upcoming shifts, each with an alarm at the shift's <b>end time</b> reminding you to input tips. Apple Calendar fires the reminder — this app can't push notifications while closed on iOS.</div>
  </div>
</div>

<div class="sheet" id="shTips">
  <div class="grab"></div>
  <h2>Input Tips</h2>
  <div class="sub" id="tipsSub"></div>
  <div id="tipsPicker"></div>
  <div id="tipsForm" style="display:none">
    <div class="row2">
      <div><label>Actual start</label><input type="time" id="tStart"></div>
      <div><label>Actual end</label><input type="time" id="tEnd"></div>
    </div>
    <div class="row2">
      <div><label>CC tips <span class="k-cc">· employer reports to IRS</span></label><input type="number" id="tCC" inputmode="decimal" step="0.01" min="0" placeholder="0.00"></div>
      <div><label>Cash tips <span class="k-cash">· YOU must report</span></label><input type="number" id="tCash" inputmode="decimal" step="0.01" min="0" placeholder="0.00"></div>
    </div>
    <div class="row2">
      <div><label>Food sales</label><input type="number" id="tFood" inputmode="decimal" step="0.01" min="0" placeholder="0.00"></div>
      <div><label>Alcohol sales</label><input type="number" id="tAlc" inputmode="decimal" step="0.01" min="0" placeholder="0.00"></div>
    </div>
    <label>Bussers</label>
    <div class="seg" id="tBuss">
      <button data-b="1">1 busser (4% food)</button>
      <button data-b="2">2 bussers (5% food)</button>
    </div>
    <div id="calcBox"></div>
    <button class="primary" id="tipsSave">Save shift</button>
    <button class="secondary danger" id="tipsDelete">Delete this shift</button>
  </div>
</div>

<div class="sheet" id="shChecks">
  <div class="grab"></div>
  <h2>Paychecks</h2>
  <div class="sub" id="chkSub"></div>
  <div id="chkList"></div>
</div>

<div class="sheet" id="shSettings">
  <div class="grab"></div>
  <h2>Settings</h2>

  <div class="row2">
    <div><label>Hourly wage ($)</label><input type="number" id="sWage" step="0.01" min="0"></div>
    <div><label>Monthly goal ($)</label><input type="number" id="sGoal" step="50" min="0"></div>
  </div>
  <div class="row2">
    <div><label>Pay period starts on</label>
      <select id="sPayDay">
        <option value="0">Sunday</option><option value="1">Monday</option><option value="2">Tuesday</option>
        <option value="3">Wednesday</option><option value="4">Thursday</option><option value="5">Friday</option>
        <option value="6">Saturday</option>
      </select></div>
    <div><label>Default withholding %</label><input type="number" id="sRate" step="0.1" min="0" max="60"></div>
  </div>
  <div class="hint" id="sRateNote"></div>

  <div class="settingsGroup"><h3>Default shift hours</h3></div>
  <div class="row3">
    <div><label>Brunch start</label><input type="time" id="dBrS"></div>
    <div><label>Lunch start</label><input type="time" id="dLuS"></div>
    <div><label>Dinner start</label><input type="time" id="dDiS"></div>
    <div><label>Brunch end</label><input type="time" id="dBrE"></div>
    <div><label>Lunch end</label><input type="time" id="dLuE"></div>
    <div><label>Dinner end</label><input type="time" id="dDiE"></div>
  </div>
  <div class="hint">Fixed rules: bar tipshare (3% of alcohol) on brunch &amp; dinner only. Bussers default to 2 on Fri/Sat dinner, else 1 — both always overridable per shift.</div>

  <div class="settingsGroup"><h3>Export & backup</h3></div>
  <label>Tax year</label>
  <select id="expYear"><option>2026</option><option>2027</option><option>2028</option></select>
  <button class="secondary" id="expXlsx">⬇︎ Export year as Excel (.xlsx)</button>
  <button class="secondary" id="expJson">⬇︎ Download JSON backup (full restore)</button>
  <button class="secondary" id="impJson">⬆︎ Restore from JSON backup…</button>
  <input type="file" id="impFile" accept=".json,application/json" style="display:none">
  <div class="hint" id="backupNote"></div>
  <div class="hint">iOS can evict a home-screen web app's local data if the app goes unopened for a long stretch. This holds tax records — back up regularly.</div>
</div>

<script>
"use strict";
/* ============================== STATE ============================== */
const KEY="tiptracker.v1";
if(typeof structuredClone!=="function"){window.structuredClone=o=>JSON.parse(JSON.stringify(o))}
const DEFAULTS={
  version:1,
  settings:{
    wage:2.13, goal:4000, payStart:5, defRate:15,
    shifts:{brunch:{s:"09:00",e:"14:00"},lunch:{s:"10:00",e:"14:00"},dinner:{s:"16:30",e:"21:00"}}
  },
  shifts:{},        // id -> shift
  checks:{},        // periodStartISO -> {actGross, actNet}
  lastBackup:null,
  nagSnooze:null
};
let S=load();
function load(){
  try{const raw=localStorage.getItem(KEY); if(!raw) return structuredClone(DEFAULTS);
    const s=JSON.parse(raw);
    // shallow-merge settings against defaults for forward compat
    s.settings=Object.assign(structuredClone(DEFAULTS.settings),s.settings||{});
    s.settings.shifts=Object.assign(structuredClone(DEFAULTS.settings.shifts),s.settings.shifts||{});
    s.shifts=s.shifts||{}; s.checks=s.checks||{};
    return s;
  }catch(e){return structuredClone(DEFAULTS)}
}
function save(){try{localStorage.setItem(KEY,JSON.stringify(S))}catch(e){alert("Couldn't save — storage may be full or blocked.")}}

/* ============================== UTILS ============================== */
const $=id=>document.getElementById(id);
const pad=n=>String(n).padStart(2,"0");
const iso=d=>d.getFullYear()+"-"+pad(d.getMonth()+1)+"-"+pad(d.getDate());
const fromISO=s=>{const[a,b,c]=s.split("-").map(Number);return new Date(a,b-1,c)};
const MONTHS=["January","February","March","April","May","June","July","August","September","October","November","December"];
const DOWS=["Sun","Mon","Tue","Wed","Thu","Fri","Sat"];
function money(n){return "$"+(Math.round(n*100)/100).toLocaleString("en-US",{minimumFractionDigits:2,maximumFractionDigits:2})}
function money0(n){return "$"+Math.round(n).toLocaleString("en-US")}
function t12(t){if(!t)return"";let[h,m]=t.split(":").map(Number);const ap=h>=12?"PM":"AM";h=h%12||12;return h+":"+pad(m)+" "+ap}
function hoursBetween(s,e){ // decimal hours, overnight-safe
  const[sh,sm]=s.split(":").map(Number),[eh,em]=e.split(":").map(Number);
  let mins=(eh*60+em)-(sh*60+sm); if(mins<=0)mins+=1440;
  return Math.round(mins/60*100)/100;
}
function uid(){return Date.now().toString(36)+Math.random().toString(36).slice(2,7)}
function shiftEndDate(sh){ // Date of the shift's end moment
  const d=fromISO(sh.date); const[h,m]=sh.end.split(":").map(Number);
  const[h0,m0]=sh.start.split(":").map(Number);
  d.setHours(h,m,0,0); if(h*60+m<=h0*60+m0)d.setDate(d.getDate()+1);
  return d;
}

/* ============================== MONEY LOGIC ============================== */
function defaultBussers(dateISO,type){
  const dow=fromISO(dateISO).getDay();
  return (type==="dinner"&&(dow===5||dow===6))?2:1;
}
function tipshareOf(sh){
  const bar=(sh.type!=="lunch")?0.03*(sh.alcohol||0):0;
  const buss=((sh.bussers>=2)?0.05:0.04)*(sh.food||0);
  return{bar,buss,total:bar+buss};
}
function effRate(){ // effective withholding rate (fraction)
  const rates=Object.values(S.checks).filter(c=>c.actGross>0&&c.actNet>=0&&c.actNet<=c.actGross)
    .map(c=>(c.actGross-c.actNet)/c.actGross);
  if(rates.length)return rates.reduce((a,b)=>a+b,0)/rates.length;
  return S.settings.defRate/100;
}
function rateSource(){return Object.keys(S.checks).some(k=>S.checks[k].actGross>0)?"calibrated":"default"}
function shiftMath(sh){ // for a logged shift
  const r=effRate(), wagePay=S.settings.wage*(sh.hours||0);
  const ts=tipshareOf(sh);
  const grossTaxed=wagePay+(sh.cc||0);
  const x=grossTaxed*(1-r);            // paycheck-side money after withholding
  const y=(sh.cash||0)-ts.total;       // pocket cash after tipshare paid out
  return{wagePay,ts,x,y,z:x+y,withheld:grossTaxed*r,
    gross:wagePay+(sh.cc||0)+(sh.cash||0)};
}
function loggedShifts(){return Object.values(S.shifts).filter(s=>s.logged)}
function monthTakeHome(y,m){
  return loggedShifts().filter(s=>{const d=fromISO(s.date);return d.getFullYear()===y&&d.getMonth()===m})
    .reduce((a,s)=>a+shiftMath(s).z,0);
}
/* pay periods */
function periodStart(d){ // Date -> Date (start of containing period)
  const x=new Date(d.getFullYear(),d.getMonth(),d.getDate());
  const diff=(x.getDay()-S.settings.payStart+7)%7;
  x.setDate(x.getDate()-diff); return x;
}
function periodOf(dateISO){return iso(periodStart(fromISO(dateISO)))}
function periodShifts(pStartISO){return loggedShifts().filter(s=>periodOf(s.date)===pStartISO)}
function periodEst(pStartISO){ // estimated check for a period
  const r=effRate(); let hrs=0,cc=0;
  for(const s of periodShifts(pStartISO)){hrs+=s.hours||0;cc+=s.cc||0}
  const gross=S.settings.wage*hrs+cc;
  return{hrs,cc,gross,withheld:gross*r,net:gross*(1-r)};
}

/* ============================== RENDER ============================== */
let view=(()=>{const t=new Date();let y=t.getFullYear(),m=t.getMonth();
  if(y<2026){y=2026;m=0} if(y>2028){y=2028;m=11} return{y,m}})();

function render(){renderHeader();renderBanners();renderGoal();renderReceipt();renderCal()}

function renderHeader(){
  $("monthTitle").textContent=MONTHS[view.m];
  $("yearTitle").textContent=view.y;
  $("prevM").disabled=(view.y===2026&&view.m===0);
  $("nextM").disabled=(view.y===2028&&view.m===11);
}
function unloggedPast(){
  const now=new Date();
  return Object.values(S.shifts).filter(s=>!s.logged&&shiftEndDate(s)<now)
    .sort((a,b)=>a.date<b.date?-1:1);
}
function renderBanners(){
  const el=$("banners");el.innerHTML="";
  const due=unloggedPast();
  if(due.length){
    const s=due[0],d=fromISO(s.date);
    const b=document.createElement("button");b.className="banner";
    b.innerHTML="🧾 <span>Unlogged "+s.type+" shift from <b>"+DOWS[d.getDay()]+" "+MONTHS[d.getMonth()].slice(0,3)+" "+d.getDate()+"</b>"+(due.length>1?" (+"+(due.length-1)+" more)":"")+" — tap to input tips.</span>";
    b.onclick=()=>openTips(s.id);el.appendChild(b);
  }
  const days=S.lastBackup?(Date.now()-S.lastBackup)/864e5:Infinity;
  const snoozed=S.nagSnooze&&(Date.now()-S.nagSnooze)<7*864e5;
  if(loggedShifts().length&&days>14&&!snoozed){
    const b=document.createElement("button");b.className="banner";
    b.innerHTML="💾 <span><b>Back up your data.</b> "+(S.lastBackup?"Last backup "+Math.floor(days)+" days ago.":"No backup yet.")+" iOS can evict web-app data — this is tax records.</span><span class='x'>✕</span>";
    b.onclick=e=>{if(e.target.classList.contains("x")){S.nagSnooze=Date.now();save();renderBanners()}else openSettings()};
    el.appendChild(b);
  }
}
function renderGoal(){
  const z=monthTakeHome(view.y,view.m),g=S.settings.goal||4000;
  $("goalLabel").textContent=MONTHS[view.m]+" take-home";
  $("goalNums").innerHTML="<b>"+money0(z)+"</b> / "+money0(g);
  $("goalFill").style.width=Math.max(0,Math.min(100,z/g*100))+"%";
  $("goalSub").textContent="Counted the night worked · after withholding & tipshare · "+
    (rateSource()==="calibrated"?"calibrated rate":"default rate")+" "+(effRate()*100).toFixed(1)+"%";
}
function renderReceipt(){
  const pS=periodStart(new Date()),pE=new Date(pS);pE.setDate(pE.getDate()+6);
  const est=periodEst(iso(pS));
  $("rAmount").textContent=money(est.net);
  const fmt=d=>DOWS[d.getDay()]+" "+MONTHS[d.getMonth()].slice(0,3)+" "+d.getDate();
  $("rDetail").textContent=fmt(pS)+" – "+fmt(pE)+"  ·  "+est.hrs.toFixed(2)+" hrs\n"+
    "wages "+money(S.settings.wage*est.hrs)+"  +  CC tips "+money(est.cc)+"\n"+
    "− withholding "+money(est.withheld)+" ("+(effRate()*100).toFixed(1)+"% "+rateSource()+")\n"+
    "cash & tipshare excluded · tap for past checks";
}
function renderCal(){
  const grid=$("grid");grid.innerHTML="";
  const first=new Date(view.y,view.m,1),start=first.getDay();
  const dim=new Date(view.y,view.m+1,0).getDate();
  const todayISO=iso(new Date()),now=new Date();
  const byDate={};
  for(const s of Object.values(S.shifts)){(byDate[s.date]=byDate[s.date]||[]).push(s)}
  const cells=[];
  const prevDim=new Date(view.y,view.m,0).getDate();
  for(let i=start-1;i>=0;i--)cells.push({d:prevDim-i,other:-1});
  for(let d=1;d<=dim;d++)cells.push({d,other:0});
  while(cells.length%7)cells.push({d:cells.length%7,other:1});
  let trail=1;
  for(const c of cells){
    const b=document.createElement("button");b.className="day"+(c.other?" other":"");
    let dISO=null;
    if(c.other===0)dISO=view.y+"-"+pad(view.m+1)+"-"+pad(c.d);
    if(c.other===1){c.d=trail++;}
    b.innerHTML="<span class='n'>"+c.d+"</span><span class='dots'></span><span class='amt'></span>";
    if(dISO){
      if(dISO===todayISO)b.classList.add("today");
      const list=(byDate[dISO]||[]);
      const dots=b.querySelector(".dots");
      let zSum=0,hasLogged=false;
      for(const s of list.slice(0,3)){
        const dot=document.createElement("i");
        dot.className="dot "+(s.logged?"logged":(shiftEndDate(s)<now?"due":"sched"));
        dots.appendChild(dot);
        if(s.logged){zSum+=shiftMath(s).z;hasLogged=true}
      }
      if(hasLogged)b.querySelector(".amt").textContent=money0(zSum);
      b.onclick=()=>openDay(dISO);
    }else b.disabled=true;
    grid.appendChild(b);
  }
}

/* ============================== SHEETS ============================== */
let openSheet=null;
function show(id){hide();openSheet=id;$("overlay").classList.add("show");$(id).classList.add("show")}
function hide(){if(openSheet){$(openSheet).classList.remove("show");openSheet=null}$("overlay").classList.remove("show")}
$("overlay").onclick=hide;

/* ---- Day sheet ---- */
let dayISO=null;
function openDay(d){
  dayISO=d;const dt=fromISO(d);
  $("dayTitle").textContent=DOWS[dt.getDay()]+", "+MONTHS[dt.getMonth()]+" "+dt.getDate();
  $("daySub").textContent=dt.getFullYear();
  const list=$("dayList");list.innerHTML="";
  const shifts=Object.values(S.shifts).filter(s=>s.date===d).sort((a,b)=>a.start<b.start?-1:1);
  if(!shifts.length){const p=document.createElement("div");p.className="hint";p.textContent="No shifts on this day yet.";list.appendChild(p)}
  const now=new Date();
  for(const s of shifts){
    const c=document.createElement("div");c.className="card";
    const status=s.logged?["done","logged"]:(shiftEndDate(s)<now?["due","tips due"]:["sched","scheduled"]);
    let html="<div class='head'><b>"+s.type+"</b><span class='time'>"+t12(s.start)+"–"+t12(s.end)+"</span>"+
      "<span class='right'><span class='tag "+status[0]+"'>"+status[1]+"</span></span></div>";
    if(s.logged){
      const m=shiftMath(s),r=effRate();
      html+="<div class='breakdown'>"+
        "<div class='ln'><span>"+(s.hours||0).toFixed(2)+" hrs × "+money(S.settings.wage)+"</span><span>"+money(m.wagePay)+"</span></div>"+
        "<div class='ln k-cc'><span>CC tips · already reported to IRS</span><span>"+money(s.cc||0)+"</span></div>"+
        "<div class='ln k-cash'><span>Cash tips · unreported — must report</span><span>"+money(s.cash||0)+"</span></div>"+
        "<div class='ln'><span>Gross earned</span><span>"+money(m.gross)+"</span></div>"+
        "<div class='ln k-out'><span>Tipshare paid out"+(m.ts.bar?" (bar 3%":" (")+(m.ts.bar?" + ":"")+"busser "+((s.bussers>=2)?"5%":"4%")+")</span><span>−"+money(m.ts.total)+"</span></div>"+
        "<div class='ln'><span>Withholding est. ("+(r*100).toFixed(1)+"%)</span><span>−"+money(m.withheld)+"</span></div>"+
        "<div class='ln total k-brass'><span>Take-home z</span><span>"+money(m.z)+"</span></div>"+
        "</div><button class='linkish' data-edit='"+s.id+"'>Edit tips</button>";
    }else{
      html+="<button class='linkish' data-edit='"+s.id+"'>Input tips</button> <button class='linkish danger' data-del='"+s.id+"'>Delete</button>";
    }
    c.innerHTML=html;list.appendChild(c);
  }
  list.onclick=e=>{
    const ed=e.target.getAttribute("data-edit"),del=e.target.getAttribute("data-del");
    if(ed)openTips(ed);
    if(del&&confirm("Delete this scheduled shift?")){delete S.shifts[del];save();render();openDay(d)}
  };
  show("shDay");
}
$("dayAddShift").onclick=()=>openLog(dayISO);

/* ---- Log Shift sheet ---- */
let logType="dinner";
function applyPreset(){
  const p=S.settings.shifts[logType];
  $("logStart").value=p.s;$("logEnd").value=p.e;
  const d=$("logDate").value||iso(new Date());
  const bus=defaultBussers(d,logType);
  $("logPreset").innerHTML="Presets for <b>"+logType+"</b>: "+
    (logType!=="lunch"?"bar tipshare 3% of alcohol · ":"no bar tipshare · ")+
    "bussers default "+bus+" on this date · hours "+t12(p.s)+"–"+t12(p.e)+". All overridable.";
}
function openLog(dateISO){
  $("logDate").value=dateISO||iso(new Date());
  applyPreset();renderUpcoming();show("shLog");
}
$("logType").onclick=e=>{const t=e.target.getAttribute("data-t");if(!t)return;
  logType=t;for(const b of $("logType").children)b.classList.toggle("on",b.getAttribute("data-t")===t);
  applyPreset()};
$("logDate").onchange=applyPreset;
$("logSave").onclick=()=>{
  const date=$("logDate").value;if(!date){alert("Pick a date.");return}
  const y=+date.slice(0,4);if(y<2026||y>2028){alert("Date must be within 2026–2028.");return}
  const s={id:uid(),date,type:logType,start:$("logStart").value,end:$("logEnd").value,logged:false};
  if(!s.start||!s.end){alert("Set start and end times.");return}
  S.shifts[s.id]=s;save();render();renderUpcoming();
};
function upcoming(){const now=new Date();
  return Object.values(S.shifts).filter(s=>!s.logged&&shiftEndDate(s)>=now)
    .sort((a,b)=>(a.date+a.start)<(b.date+b.start)?-1:1)}
function renderUpcoming(){
  const el=$("upcomingList");el.innerHTML="";
  const ups=upcoming();
  if(!ups.length){el.innerHTML="<div class='hint'>Nothing scheduled ahead yet.</div>"}
  for(const s of ups){
    const d=fromISO(s.date);
    const c=document.createElement("div");c.className="card";
    c.innerHTML="<div class='head'><b>"+s.type+"</b><span class='time'>"+DOWS[d.getDay()]+" "+
      MONTHS[d.getMonth()].slice(0,3)+" "+d.getDate()+" · "+t12(s.start)+"–"+t12(s.end)+
      "</span><span class='right'><button class='danger' data-del='"+s.id+"'>✕</button></span></div>";
    el.appendChild(c);
  }
  el.onclick=e=>{const del=e.target.getAttribute("data-del");
    if(del){delete S.shifts[del];save();render();renderUpcoming()}};
  $("icsBtn").style.display=ups.length?"block":"none";
}
$("icsBtn").onclick=()=>downloadICS(upcoming());

/* ---- Input Tips sheet ---- */
let tipsId=null,tBussers=1;
function openTipsPicker(){
  tipsId=null;$("tipsForm").style.display="none";
  $("tipsSub").textContent="Pick the shift you worked.";
  const el=$("tipsPicker");el.innerHTML="";el.style.display="block";
  const now=new Date();
  const cands=Object.values(S.shifts).filter(s=>!s.logged)
    .sort((a,b)=>{const ap=shiftEndDate(a)<now,bp=shiftEndDate(b)<now;
      if(ap!==bp)return ap?-1:1;return (a.date+a.start)<(b.date+b.start)?1:-1});
  if(!cands.length)el.innerHTML="<div class='hint'>No unlogged shifts.</div>";
  for(const s of cands){
    const d=fromISO(s.date);
    const c=document.createElement("button");c.className="card";c.style.width="100%";c.style.textAlign="left";
    const past=shiftEndDate(s)<now;
    c.innerHTML="<div class='head'><b>"+s.type+"</b><span class='time'>"+DOWS[d.getDay()]+" "+MONTHS[d.getMonth()].slice(0,3)+" "+d.getDate()+" · "+t12(s.start)+"–"+t12(s.end)+"</span>"+
      "<span class='right'><span class='tag "+(past?"due'>tips due":"sched'>scheduled")+"</span></span></div>";
    c.onclick=()=>openTips(s.id);el.appendChild(c);
  }
  const add=document.createElement("button");add.className="secondary";
  add.textContent="Worked a shift that isn't listed? Add it";
  add.onclick=()=>{hide();openLog(iso(new Date()))};
  el.appendChild(add);
  show("shTips");
}
function openTips(id){
  const s=S.shifts[id];if(!s)return;
  tipsId=id;$("tipsPicker").style.display="none";$("tipsForm").style.display="block";
  const d=fromISO(s.date);
  $("tipsSub").textContent=s.type[0].toUpperCase()+s.type.slice(1)+" · "+DOWS[d.getDay()]+", "+MONTHS[d.getMonth()]+" "+d.getDate()+" "+d.getFullYear();
  $("tStart").value=s.actualStart||s.start;$("tEnd").value=s.actualEnd||s.end;
  $("tCC").value=s.cc??"";$("tCash").value=s.cash??"";
  $("tFood").value=s.food??"";$("tAlc").value=s.alcohol??"";
  tBussers=s.bussers||defaultBussers(s.date,s.type);
  for(const b of $("tBuss").children)b.classList.toggle("on",+b.getAttribute("data-b")===tBussers);
  liveCalc();show("shTips");
}
$("tBuss").onclick=e=>{const b=e.target.getAttribute("data-b");if(!b)return;
  tBussers=+b;for(const x of $("tBuss").children)x.classList.toggle("on",+x.getAttribute("data-b")===tBussers);liveCalc()};
for(const id of["tStart","tEnd","tCC","tCash","tFood","tAlc"])$(id).addEventListener("input",liveCalc);
function tipsDraft(){
  const s=S.shifts[tipsId];if(!s)return null;
  return{...s,type:s.type,hours:hoursBetween($("tStart").value||s.start,$("tEnd").value||s.end),
    cc:+$("tCC").value||0,cash:+$("tCash").value||0,food:+$("tFood").value||0,alcohol:+$("tAlc").value||0,bussers:tBussers};
}
function liveCalc(){
  const d=tipsDraft();if(!d)return;
  const m=shiftMath(d),ts=m.ts,r=effRate();
  $("calcBox").innerHTML=
    "<div class='ln'><span>Hours</span><span>"+d.hours.toFixed(2)+" × "+money(S.settings.wage)+" = "+money(m.wagePay)+"</span></div>"+
    "<div class='ln k-out'><span>Tipshare owed tonight</span><span>"+money(ts.total)+"</span></div>"+
    "<div class='ln k-out small'><span>· bar "+(d.type!=="lunch"?"3% × "+money(d.alcohol):"— (lunch)")+"</span><span>"+money(ts.bar)+"</span></div>"+
    "<div class='ln k-out small'><span>· busser "+((d.bussers>=2)?"5%":"4%")+" × "+money(d.food)+"</span><span>"+money(ts.buss)+"</span></div>"+
    "<div class='ln'><span>x = (wages + CC) − "+(r*100).toFixed(1)+"%</span><span>"+money(m.x)+"</span></div>"+
    "<div class='ln'><span>y = cash − tipshare</span><span>"+money(m.y)+"</span></div>"+
    "<div class='ln' style='font-weight:700'><span>z = take-home</span><span class='k-brass'>"+money(m.z)+"</span></div>";
}
$("tipsSave").onclick=()=>{
  const s=S.shifts[tipsId];if(!s)return;
  const d=tipsDraft();
  Object.assign(s,{logged:true,actualStart:$("tStart").value,actualEnd:$("tEnd").value,
    hours:d.hours,cc:d.cc,cash:d.cash,food:d.food,alcohol:d.alcohol,bussers:d.bussers});
  save();hide();render();
};
$("tipsDelete").onclick=()=>{if(confirm("Delete this shift and its numbers?")){delete S.shifts[tipsId];save();hide();render()}};

/* ---- Checks sheet ---- */
function openChecks(){
  $("chkSub").textContent="Estimated vs. actual. Enter a real check's gross + deposited amount to calibrate withholding ("+(effRate()*100).toFixed(1)+"% "+rateSource()+" now).";
  const el=$("chkList");el.innerHTML="";
  const curr=iso(periodStart(new Date()));
  const periods=[...new Set(loggedShifts().map(s=>periodOf(s.date)))].sort().reverse();
  const done=periods.filter(p=>p<curr);
  if(!done.length)el.innerHTML="<div class='hint'>No completed pay periods with logged shifts yet. Finished periods appear here every "+["Sun","Mon","Tue","Wed","Thu","Fri","Sat"][S.settings.payStart]+".</div>";
  for(const p of done){
    const est=periodEst(p),ps=fromISO(p),pe=new Date(ps);pe.setDate(pe.getDate()+6);
    const c=S.checks[p]||{};
    const row=document.createElement("div");row.className="chk";
    const fmt=d=>MONTHS[d.getMonth()].slice(0,3)+" "+d.getDate();
    row.innerHTML="<div class='cHead'><b>"+fmt(ps)+" – "+fmt(pe)+" "+pe.getFullYear()+"</b><span class='small'>"+est.hrs.toFixed(2)+" hrs</span></div>"+
      "<div class='grid'>"+
      "<div class='cell'><div class='lab'>EST. GROSS (wages+CC)</div>"+money(est.gross)+"</div>"+
      "<div class='cell'><div class='lab'>EST. NET</div>"+money(est.net)+"</div>"+
      "<div class='cell'><div class='lab'>ACTUAL GROSS</div><input type='number' step='0.01' inputmode='decimal' data-p='"+p+"' data-f='actGross' value='"+(c.actGross??"")+"' placeholder='from stub'></div>"+
      "<div class='cell'><div class='lab'>ACTUAL DEPOSITED</div><input type='number' step='0.01' inputmode='decimal' data-p='"+p+"' data-f='actNet' value='"+(c.actNet??"")+"' placeholder='from bank'></div>"+
      "</div>"+
      (c.actGross>0&&c.actNet>=0?"<div class='small' style='margin-top:6px'>Implied withholding "+(((c.actGross-c.actNet)/c.actGross)*100).toFixed(2)+"% · diff vs est. net "+money((c.actNet)-(est.net))+"</div>":"");
    el.appendChild(row);
  }
  el.oninput=e=>{
    const p=e.target.getAttribute("data-p"),f=e.target.getAttribute("data-f");
    if(!p)return;S.checks[p]=S.checks[p]||{};
    S.checks[p][f]=e.target.value===""?null:+e.target.value;
    save();render(); // refresh rate everywhere; keep sheet open
  };
  show("shChecks");
}
$("receipt").onclick=openChecks;

/* ---- Settings ---- */
function openSettings(){
  const st=S.settings;
  $("sWage").value=st.wage;$("sGoal").value=st.goal;$("sPayDay").value=st.payStart;$("sRate").value=st.defRate;
  $("dBrS").value=st.shifts.brunch.s;$("dBrE").value=st.shifts.brunch.e;
  $("dLuS").value=st.shifts.lunch.s;$("dLuE").value=st.shifts.lunch.e;
  $("dDiS").value=st.shifts.dinner.s;$("dDiE").value=st.shifts.dinner.e;
  $("sRateNote").textContent=rateSource()==="calibrated"
    ?"Calibrated rate in use: "+(effRate()*100).toFixed(2)+"% (averaged from your real checks). The default above is only used before calibration."
    :"No real checks entered yet — using the default rate. FICA alone is 7.65%; federal income tax comes on top per your W-4.";
  $("backupNote").textContent=S.lastBackup?"Last backup: "+new Date(S.lastBackup).toLocaleDateString():"No backup downloaded yet.";
  show("shSettings");
}
$("gear").onclick=openSettings;
$("shSettings").addEventListener("change",e=>{
  const st=S.settings;
  st.wage=+$("sWage").value||2.13;st.goal=+$("sGoal").value||4000;
  st.payStart=+$("sPayDay").value;st.defRate=+$("sRate").value||15;
  st.shifts.brunch={s:$("dBrS").value,e:$("dBrE").value};
  st.shifts.lunch={s:$("dLuS").value,e:$("dLuE").value};
  st.shifts.dinner={s:$("dDiS").value,e:$("dDiE").value};
  save();render();
});

/* ============================== ICS EXPORT ============================== */
function downloadICS(shifts){
  const lines=["BEGIN:VCALENDAR","VERSION:2.0","PRODID:-//TipTracker//Offline//EN","CALSCALE:GREGORIAN"];
  for(const s of shifts){
    const d=s.date.replace(/-/g,""),st=s.start.replace(":","")+"00";
    const endD=shiftEndDate(s);
    const en=endD.getFullYear()+pad(endD.getMonth()+1)+pad(endD.getDate())+"T"+pad(endD.getHours())+pad(endD.getMinutes())+"00";
    lines.push("BEGIN:VEVENT","UID:"+s.id+"@tiptracker",
      "DTSTAMP:"+new Date().toISOString().replace(/[-:]/g,"").slice(0,15)+"Z",
      "DTSTART:"+d+"T"+st,"DTEND:"+en,
      "SUMMARY:"+s.type[0].toUpperCase()+s.type.slice(1)+" shift",
      "DESCRIPTION:After close: open Tip Tracker and input tips (CC\\, cash\\, food & alcohol sales\\, bussers).",
      "BEGIN:VALARM","ACTION:DISPLAY","DESCRIPTION:Shift over — log your tips in Tip Tracker",
      "TRIGGER;RELATED=END:PT0M","END:VALARM","END:VEVENT");
  }
  lines.push("END:VCALENDAR");
  downloadBlob(new Blob([lines.join("\r\n")],{type:"text/calendar"}),"shifts.ics");
}
function downloadBlob(blob,name){
  const a=document.createElement("a");a.href=URL.createObjectURL(blob);a.download=name;
  document.body.appendChild(a);a.click();
  setTimeout(()=>{URL.revokeObjectURL(a.href);a.remove()},4000);
}

/* ============================== JSON BACKUP ============================== */
$("expJson").onclick=()=>{
  S.lastBackup=Date.now();save();
  downloadBlob(new Blob([JSON.stringify(S,null,1)],{type:"application/json"}),
    "tiptracker-backup-"+iso(new Date())+".json");
  openSettings();renderBanners();
};
$("impJson").onclick=()=>$("impFile").click();
$("impFile").onchange=e=>{
  const f=e.target.files[0];if(!f)return;
  const r=new FileReader();
  r.onload=()=>{try{
    const data=JSON.parse(r.result);
    if(!data||typeof data!=="object"||!data.settings||!data.shifts)throw 0;
    if(!confirm("Replace ALL current data with this backup?"))return;
    S=data;S.settings=Object.assign(structuredClone(DEFAULTS.settings),S.settings);
    save();hide();render();alert("Restored.");
  }catch(err){alert("That file isn't a valid Tip Tracker backup.")}};
  r.readAsText(f);e.target.value="";
};

/* ============================== XLSX EXPORT (no libraries) ============================== */
const CRC_T=(()=>{const t=new Uint32Array(256);for(let n=0;n<256;n++){let c=n;
  for(let k=0;k<8;k++)c=(c&1)?(0xEDB88320^(c>>>1)):(c>>>1);t[n]=c}return t})();
function crc32(u8){let c=0xFFFFFFFF;for(let i=0;i<u8.length;i++)c=CRC_T[(c^u8[i])&0xFF]^(c>>>8);return (c^0xFFFFFFFF)>>>0}
function zip(files){ // files: [{name,text}] -> Blob (STORE, no compression)
  const enc=new TextEncoder(),parts=[],central=[];let offset=0;
  const now=new Date();
  const dosT=(now.getHours()<<11)|(now.getMinutes()<<5)|(now.getSeconds()>>1);
  const dosD=((now.getFullYear()-1980)<<9)|((now.getMonth()+1)<<5)|now.getDate();
  const u16=n=>[n&255,(n>>8)&255], u32=n=>[n&255,(n>>8)&255,(n>>16)&255,(n>>24)&255];
  for(const f of files){
    const name=enc.encode(f.name),data=enc.encode(f.text),crc=crc32(data);
    const head=new Uint8Array([80,75,3,4,...u16(20),...u16(0x800),...u16(0),...u16(dosT),...u16(dosD),
      ...u32(crc),...u32(data.length),...u32(data.length),...u16(name.length),...u16(0)]);
    parts.push(head,name,data);
    central.push(new Uint8Array([80,75,1,2,...u16(20),...u16(20),...u16(0x800),...u16(0),...u16(dosT),...u16(dosD),
      ...u32(crc),...u32(data.length),...u32(data.length),...u16(name.length),...u16(0),...u16(0),
      ...u16(0),...u16(0),...u32(0),...u32(offset)]),name);
    offset+=head.length+name.length+data.length;
  }
  let cdSize=0;for(const c of central)cdSize+=c.length;
  const eocd=new Uint8Array([80,75,5,6,...u16(0),...u16(0),...u16(files.length),...u16(files.length),
    ...u32(cdSize),...u32(offset),...u16(0)]);
  return new Blob([...parts,...central,eocd],{type:"application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"});
}
const xesc=s=>String(s).replace(/&/g,"&amp;").replace(/</g,"&lt;").replace(/>/g,"&gt;").replace(/"/g,"&quot;");
function sheetXML(rows){ // rows: array of arrays; numbers stay numbers, strings inline
  let out='<?xml version="1.0" encoding="UTF-8" standalone="yes"?><worksheet xmlns="http://schemas.openxmlformats.org/spreadsheetml/2006/main"><sheetData>';
  rows.forEach((row,ri)=>{
    out+='<row r="'+(ri+1)+'">';
    row.forEach((v,ci)=>{
      const ref=String.fromCharCode(65+ci)+(ri+1);
      if(typeof v==="number"&&isFinite(v))out+='<c r="'+ref+'"><v>'+(Math.round(v*100)/100)+'</v></c>';
      else if(v!==null&&v!==undefined&&v!=="")out+='<c r="'+ref+'" t="inlineStr"><is><t xml:space="preserve">'+xesc(v)+'</t></is></c>';
    });
    out+='</row>';
  });
  return out+'</sheetData></worksheet>';
}
function buildXLSX(year){
  const shifts=loggedShifts().filter(s=>+s.date.slice(0,4)===year).sort((a,b)=>a.date<b.date?-1:1);
  const w=S.settings.wage;
  const sRows=[["Date","Day","Shift","Hours","Hourly wages","CC tips (employer-reported to IRS)","Cash tips (YOU must report)","Food sales","Alcohol sales","Bar tipshare (3%)","Bussers","Busser tipshare","Total tipshare paid (out of pocket)","Gross earned (wages+CC+cash)"]];
  let T={hrs:0,wage:0,cc:0,cash:0,food:0,alc:0,bar:0,buss:0,ts:0,gross:0};
  for(const s of shifts){
    const ts=tipshareOf(s),wp=w*(s.hours||0),gross=wp+(s.cc||0)+(s.cash||0);
    const d=fromISO(s.date);
    sRows.push([s.date,DOWS[d.getDay()],s.type,s.hours||0,wp,s.cc||0,s.cash||0,s.food||0,s.alcohol||0,ts.bar,s.bussers||1,ts.buss,ts.total,gross]);
    T.hrs+=s.hours||0;T.wage+=wp;T.cc+=s.cc||0;T.cash+=s.cash||0;T.food+=s.food||0;T.alc+=s.alcohol||0;
    T.bar+=ts.bar;T.buss+=ts.buss;T.ts+=ts.total;T.gross+=gross;
  }
  sRows.push([]);
  sRows.push(["TOTALS","","",T.hrs,T.wage,T.cc,T.cash,T.food,T.alc,T.bar,"",T.buss,T.ts,T.gross]);
  const sumRows=[
    ["TAX YEAR "+year+" — SUMMARY"],[],
    ["Shifts logged",shifts.length],
    ["Hours worked",T.hrs],
    ["Hourly wages earned ($"+w.toFixed(2)+"/hr)",T.wage],[],
    ["CC tips — ALREADY REPORTED to IRS by employer",T.cc],
    ["Cash tips — NOT auto-reported. YOU MUST REPORT this amount",T.cash],
    ["Total tips",T.cc+T.cash],[],
    ["Tipshare paid out of pocket (bar + bussers) — discuss deductibility with tax preparer",T.ts],
    ["  of which bar tipshare (3% alcohol, brunch/dinner)",T.bar],
    ["  of which busser tipshare (4–5% food)",T.buss],[],
    ["Gross earned (wages + CC + cash, before anything out)",T.gross],
    ["Note","Texas — no state income tax. FICA 7.65% + federal income tax withheld via payroll on wages+CC."]
  ];
  const curr=iso(periodStart(new Date()));
  const periods=[...new Set(shifts.map(s=>periodOf(s.date)))].sort().filter(p=>p<curr);
  const pRows=[["Pay period start","Pay period end","Hours","Est. gross (wages+CC)","Est. net","Actual gross","Actual deposited","Implied withholding %"]];
  for(const p of periods){
    const est=periodEst(p),c=S.checks[p]||{},pe=fromISO(p);pe.setDate(pe.getDate()+6);
    pRows.push([p,iso(pe),est.hrs,est.gross,est.net,c.actGross??"",c.actNet??"",
      (c.actGross>0&&c.actNet>=0)?((c.actGross-c.actNet)/c.actGross*100):""]);
  }
  const CT='<?xml version="1.0" encoding="UTF-8" standalone="yes"?><Types xmlns="http://schemas.openxmlformats.org/package/2006/content-types"><Default Extension="rels" ContentType="application/vnd.openxmlformats-package.relationships+xml"/><Default Extension="xml" ContentType="application/xml"/><Override PartName="/xl/workbook.xml" ContentType="application/vnd.openxmlformats-officedocument.spreadsheetml.sheet.main+xml"/><Override PartName="/xl/worksheets/sheet1.xml" ContentType="application/vnd.openxmlformats-officedocument.spreadsheetml.worksheet+xml"/><Override PartName="/xl/worksheets/sheet2.xml" ContentType="application/vnd.openxmlformats-officedocument.spreadsheetml.worksheet+xml"/><Override PartName="/xl/worksheets/sheet3.xml" ContentType="application/vnd.openxmlformats-officedocument.spreadsheetml.worksheet+xml"/><Override PartName="/xl/styles.xml" ContentType="application/vnd.openxmlformats-officedocument.spreadsheetml.styles+xml"/></Types>';
  const RELS='<?xml version="1.0" encoding="UTF-8" standalone="yes"?><Relationships xmlns="http://schemas.openxmlformats.org/package/2006/relationships"><Relationship Id="rId1" Type="http://schemas.openxmlformats.org/officeDocument/2006/relationships/officeDocument" Target="xl/workbook.xml"/></Relationships>';
  const WB='<?xml version="1.0" encoding="UTF-8" standalone="yes"?><workbook xmlns="http://schemas.openxmlformats.org/spreadsheetml/2006/main" xmlns:r="http://schemas.openxmlformats.org/officeDocument/2006/relationships"><sheets><sheet name="Summary" sheetId="1" r:id="rId1"/><sheet name="Shifts" sheetId="2" r:id="rId2"/><sheet name="Paychecks" sheetId="3" r:id="rId3"/></sheets></workbook>';
  const WBR='<?xml version="1.0" encoding="UTF-8" standalone="yes"?><Relationships xmlns="http://schemas.openxmlformats.org/package/2006/relationships"><Relationship Id="rId1" Type="http://schemas.openxmlformats.org/officeDocument/2006/relationships/worksheet" Target="worksheets/sheet1.xml"/><Relationship Id="rId2" Type="http://schemas.openxmlformats.org/officeDocument/2006/relationships/worksheet" Target="worksheets/sheet2.xml"/><Relationship Id="rId3" Type="http://schemas.openxmlformats.org/officeDocument/2006/relationships/worksheet" Target="worksheets/sheet3.xml"/><Relationship Id="rId4" Type="http://schemas.openxmlformats.org/officeDocument/2006/relationships/styles" Target="styles.xml"/></Relationships>';
  const STY='<?xml version="1.0" encoding="UTF-8" standalone="yes"?><styleSheet xmlns="http://schemas.openxmlformats.org/spreadsheetml/2006/main"><fonts count="1"><font><sz val="11"/><name val="Calibri"/></font></fonts><fills count="2"><fill><patternFill patternType="none"/></fill><fill><patternFill patternType="gray125"/></fill></fills><borders count="1"><border/></borders><cellStyleXfs count="1"><xf numFmtId="0" fontId="0" fillId="0" borderId="0"/></cellStyleXfs><cellXfs count="1"><xf numFmtId="0" fontId="0" fillId="0" borderId="0" xfId="0"/></cellXfs><cellStyles count="1"><cellStyle name="Normal" xfId="0" builtinId="0"/></cellStyles></styleSheet>';
  return zip([
    {name:"[Content_Types].xml",text:CT},
    {name:"_rels/.rels",text:RELS},
    {name:"xl/workbook.xml",text:WB},
    {name:"xl/_rels/workbook.xml.rels",text:WBR},
    {name:"xl/styles.xml",text:STY},
    {name:"xl/worksheets/sheet1.xml",text:sheetXML(sumRows)},
    {name:"xl/worksheets/sheet2.xml",text:sheetXML(sRows)},
    {name:"xl/worksheets/sheet3.xml",text:sheetXML(pRows)}
  ]);
}
$("expXlsx").onclick=()=>{
  const y=+$("expYear").value;
  downloadBlob(buildXLSX(y),"tips-"+y+".xlsx");
};

/* ============================== NAV / INIT ============================== */
$("prevM").onclick=()=>{if(view.m===0){view.y--;view.m=11}else view.m--;render()};
$("nextM").onclick=()=>{if(view.m===11){view.y++;view.m=0}else view.m++;render()};
$("btnLog").onclick=()=>openLog(null);
$("btnTips").onclick=openTipsPicker;
document.addEventListener("visibilitychange",()=>{if(!document.hidden)render()});
render();
</script>
</body>
</html>
