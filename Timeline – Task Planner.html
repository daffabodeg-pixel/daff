<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Timeline – Task Planner</title>
<style>
:root{--bg:#0B0B1A;--card:#13132b;--sh:#1a1a38;--fld:#26264a;--tx:#fff;--mu:#9CA3AF;--ac:#8B5CF6;--g:linear-gradient(135deg,#6366F1,#8B5CF6);color-scheme:dark;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box;-webkit-tap-highlight-color:transparent}
html,body{height:100%;margin:0}
body{background:#05050f;color:var(--tx);font:15px/1.35 -apple-system,BlinkMacSystemFont,"Inter","SF Pro Text","Segoe UI",Roboto,sans-serif}
button{font:inherit;cursor:pointer}
body{perspective:1600px}
#app{animation:in3d 1s cubic-bezier(.2,.8,.2,1) both;position:relative;height:100%;max-width:430px;margin:0 auto;background:var(--bg);display:flex;flex-direction:column;overflow:hidden}
@supports(height:100dvh){html,body{height:100dvh}}
/* Tablet / small laptop: centered card, no phone bezel */
@media(min-width:520px){body{display:grid;place-items:center}#app{max-width:600px;height:min(900px,calc(100% - 32px));border-radius:28px;border:1px solid rgba(255,255,255,.12);box-shadow:0 20px 60px rgba(0,0,0,.55),0 0 80px rgba(99,102,241,.12)}#ov{align-items:center;justify-content:center;padding:16px}.sheet{max-width:520px;border-radius:24px}}
/* Laptop / desktop: two-pane layout (calendar left, timeline right) */
@media(min-width:900px){
#app{max-width:1120px;width:calc(100% - 48px);display:grid;grid-template-columns:380px 1fr;grid-template-rows:1fr auto;height:min(820px,calc(100% - 48px))}
#app:has(#hd:empty){grid-template-columns:1fr}
#hd{grid-column:1;grid-row:1;overflow:auto;padding:18px;border-right:1px solid rgba(255,255,255,.08)}#hd:empty{display:none}
#main{grid-column:2;grid-row:1;border-radius:0;padding:22px 28px 120px}
#app:has(#hd:empty) #main{grid-column:1}
#tabs{grid-column:1/3;grid-row:2}
#fab{bottom:88px;right:24px}
.hdl{display:none}
.mg .dy span{width:38px;height:38px}
.dy:hover span{background:rgba(139,92,246,.25)}.dy.sel:hover span{background:var(--g)}
.tb{flex-direction:row;justify-content:center;gap:8px;font-size:13px}
.row,.gap,.it{border-radius:12px;transition:background .2s}.row:hover,.it:hover{background:rgba(255,255,255,.03)}
}
#hd{padding:8px 16px 0;flex:none}
.top{display:flex;justify-content:space-between;align-items:center}
h1{font-size:28px;margin:4px 0;font-weight:700}h1 b{color:var(--ac);font-weight:700}
h2{margin:6px 0 10px;font-size:24px}
.ib{background:none;border:0;color:var(--mu);font-size:20px;padding:4px 8px}.ib[data-a=today]{font-size:13px;color:var(--ac)}
.wk,.mg{display:grid;grid-template-columns:repeat(7,1fr)}
.dy{background:none;border:0;color:var(--tx);display:flex;flex-direction:column;align-items:center;gap:4px;padding:4px 0}
.dy small{color:var(--mu);font-size:12px}
.dy span{width:34px;height:34px;border-radius:50%;display:grid;place-items:center;font-weight:600;font-size:17px;transition:background .2s}
.dy.td span{color:var(--ac)}.dy.sel span{background:var(--g);color:#fff}
.dy i{display:flex;gap:2px;height:8px}.dy u{width:8px;height:8px;border-radius:50%}
.mg .dy span{width:30px;height:30px;font-size:15px}.mg .o{opacity:.35}.mh{text-align:center;color:var(--mu);font-size:12px}
.hdl{display:block;width:100%;background:none;border:0;padding:8px 0}.hdl::after{content:'';display:block;margin:auto;width:40px;height:5px;border-radius:3px;background:#3b3b63}
#main{flex:1;overflow:auto;background:var(--card);border-radius:24px 24px 0 0;padding:14px 16px 160px}
.pins{display:flex;gap:18px;overflow-x:auto;padding-bottom:14px;margin-bottom:10px;border-bottom:1px solid rgba(255,255,255,.1)}
.pin{background:none;border:0;color:var(--tx);width:68px;flex:none;font-size:12px;text-align:center}
.ci{width:56px;height:56px;border-radius:50%;background:var(--fld);display:grid;place-items:center;font-size:24px;margin:0 auto 6px;position:relative}
.ci span{position:relative;z-index:1}
.ring{background:conic-gradient(#8B5CF6 calc(var(--p)*1%),var(--fld) 0)}.ring::after{content:'';position:absolute;inset:4px;border-radius:50%;background:#13132b}
.pin.dn .ci{outline:2px solid var(--c)}
.row,.gap{display:grid;grid-template-columns:42px 58px 1fr 30px;column-gap:8px;align-items:start}
.row{cursor:pointer}
.tm{color:var(--mu);font-size:12px;padding-top:4px;text-align:right}
.pc{display:flex;flex-direction:column;align-items:center}
.pill{width:58px;border-radius:29px;display:grid;place-items:center;font-size:24px}
.ln{width:2px;height:14px;background:#3b3b63}.gap .ln{height:46px}
.inf{padding-top:6px;min-width:0}.meta{color:var(--mu);font-size:13px}
.ttl{font-size:18px;font-weight:600;margin-top:2px}.sub{color:var(--mu);font-size:13px;margin-top:4px}
.ck{width:26px;height:26px;border-radius:50%;border:2px solid var(--c);background:none;margin-top:12px;color:#fff;font-size:14px;padding:0}
.done .ck{background:var(--c);animation:pop .25s}.done .ttl{text-decoration:line-through;opacity:.5}
@keyframes pop{50%{transform:scale(1.25)}}
@keyframes in3d{from{opacity:0;transform:rotateY(-35deg) rotateX(10deg) translateZ(-300px) scale(.85)}to{opacity:1;transform:none}}
.gap{cursor:pointer;color:var(--mu)}.gap p{margin:0;align-self:center;grid-column:3/5}
.now{display:flex;align-items:center;gap:6px;color:var(--ac);font-size:11px;margin:2px 0}
.now i{width:8px;height:8px;border-radius:50%;background:var(--ac)}.now::after{content:'';flex:1;height:1px;background:var(--ac)}
.empty{color:var(--mu);text-align:center;padding:40px 0}
#fab{position:absolute;right:16px;bottom:84px;width:60px;height:60px;border-radius:50%;background:var(--g);border:0;color:#fff;font-size:34px;line-height:1;box-shadow:0 6px 22px rgba(139,92,246,.45);z-index:5}
#tabs{flex:none;height:64px;display:grid;grid-template-columns:repeat(3,1fr);background:var(--bg);border-top:1px solid var(--sh)}
.tb{background:none;border:0;color:var(--mu);font-size:11px;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:2px}
.tb b{font-size:20px;font-weight:400;filter:grayscale(1);opacity:.7}.tb.on{color:var(--ac)}.tb.on b{filter:none;opacity:1}
#ov{position:absolute;inset:0;background:#0009;display:flex;align-items:flex-end;z-index:10}#ov[hidden]{display:none}
.sheet{width:100%;max-height:92%;overflow:auto;background:var(--sh);border-radius:24px 24px 0 0;padding:16px 16px 24px}
.f{display:block;width:100%;background:var(--fld);border:0;border-radius:12px;color:#fff;padding:12px;font:inherit;margin:6px 0}
.r2{display:grid;grid-template-columns:1fr 1fr;gap:8px}
.sw{display:flex;gap:10px;flex-wrap:wrap;margin:10px 0}.sw button{width:34px;height:34px;border-radius:50%;border:2px solid transparent;color:#fff;padding:0;background:var(--fld)}.sw button.on{border-color:#fff}
.sb{display:flex;align-items:center;gap:8px;padding:6px 0}.sb button{background:none;border:0;color:var(--mu)}
.btn{background:var(--g);border:0;color:#fff;border-radius:12px;padding:12px 16px;font-weight:600}.btn.g{background:var(--fld)}
.acts{display:flex;gap:8px;margin-top:14px;flex-wrap:wrap}.acts .btn:first-child{flex:1}
.mu{color:var(--mu)}
#app{padding-top:44px}
#back{position:absolute;top:8px;left:12px;z-index:6;display:inline-flex;align-items:center;gap:6px;height:30px;padding:0 14px;border-radius:999px;background:var(--g);color:#fff;font-size:13px;font-weight:600;text-decoration:none;box-shadow:0 4px 14px rgba(139,92,246,.4);transition:transform .2s,box-shadow .2s}
#back:hover{transform:translateY(-1px);box-shadow:0 6px 20px rgba(139,92,246,.6)}#back:active{transform:scale(.96)}
.it{display:flex;align-items:center;gap:10px;padding:10px 0;border-bottom:1px solid rgba(255,255,255,.1)}.it .t{flex:1;cursor:pointer}.it.done .t{text-decoration:line-through;opacity:.5}
.it .ck{margin:0}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}}
</style>
</head>
<body>
<div id="app">
  <a id="back" href="https://claude.ai/artifact/3tSyrCqDAWTdBSjyvsiQbR" aria-label="Kembali ke website portofolio">← Return</a>
  <header id="hd"></header>
  <main id="main"></main>
  <button id="fab" aria-label="Tambah task">+</button>
  <nav id="tabs"></nav>
  <div id="ov" hidden></div>
</div>
<script>
// ---------- Util ----------
const $=s=>document.querySelector(s);
const CATS=['#8B5CF6','#6366F1','#38BDF8','#34D399','#F472B6'];
const ICONS=['⏰','☀️','🐾','☕','💼','📞','🎂','🏃','📚','🍽️','🛒','💻'];
const DN=['Min','Sen','Sel','Rab','Kam','Jum','Sab'];
const MN=['Januari','Februari','Maret','April','Mei','Juni','Juli','Agustus','September','Oktober','November','Desember'];
const p2=n=>String(n).padStart(2,'0');
const iso=d=>d.getFullYear()+'-'+p2(d.getMonth()+1)+'-'+p2(d.getDate());
const addD=(d,n)=>{const x=new Date(d);x.setDate(x.getDate()+n);return x};
const mondayOf=d=>addD(d,-((d.getDay()+6)%7));
const fm=m=>p2(Math.floor(m/60))+':'+p2(m%60);
const pm=s=>{const a=(s||'0:0').split(':');return +a[0]*60+ +a[1]};
const dur=m=>m<60?m+' mnt':Math.floor(m/60)+' jam'+(m%60?' '+m%60+' mnt':'');
const esc=s=>String(s).replace(/[&<>"]/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c]));
const dw=k=>new Date(k+'T00:00').getDay();
let nid=1;const uid=()=>'t'+Date.now().toString(36)+(nid++);

// ---------- State & storage ----------
const S={tasks:[],pins:[],sel:iso(new Date()),tab:'tl',month:false};
let loaded=false;
try{const r=JSON.parse(localStorage.getItem('tl1'));if(r&&r.t){S.tasks=r.t;S.pins=r.p||[];loaded=true}}catch(e){}
const save=()=>{try{localStorage.setItem('tl1',JSON.stringify({t:S.tasks,p:S.pins}))}catch(e){}};

// Data contoh dibuat relatif terhadap tanggal hari ini (bukan hardcode)
function seed(){
  const now=new Date();
  const T=(n,s,e,title,cat,ic,o)=>({id:uid(),date:iso(addD(now,n)),start:pm(s),end:pm(e),title,cat,ic,done:false,rec:'',subs:[],...(o||{})});
  S.tasks=[
    T(0,'08:00','08:00','Bangun Tidur',0,'⏰',{rec:'daily'}),
    T(0,'08:00','08:30','Rutinitas Pagi',1,'☀️',{rec:'daily',subs:['Mandi','Sarapan','Minum vitamin'].map(t=>({t,d:false}))}),
    T(0,'08:30','09:00','Jalan Pagi dengan Huge',2,'🐾',{rec:'daily'}),
    T(0,'09:30','10:15','Ngopi dengan George',0,'☕'),
    T(0,'10:15','11:45','Deep Work: Mengerjakan Proyek',1,'💼'),
    T(0,'12:30','13:30','Makan Siang',3,'🍽️'),
    T(-2,'16:00','17:00','Review Mingguan',4,'📚'),
    T(-1,'14:00','14:30','Telepon Klien',1,'📞'),
    T(1,'10:00','11:00','Rapat Tim',3,'💼'),
    T(2,'17:00','18:00','Olahraga Sore',2,'🏃'),
    T(3,'15:00','16:30','Belanja Bulanan',4,'🛒'),
    T(4,'12:00','14:00','Kumpul Keluarga',0,'🍽️')
  ];
  S.pins=[{id:'p0',t:'Siklus',ic:'❄️',ring:42},{id:'p1',t:'Telepon Mama',ic:'📞',c:2},{id:'p2',t:'Ulang Tahun Kevin',ic:'🎂',c:0}];
  save();
}
if(!loaded)seed();

const on=k=>S.tasks.filter(x=>!x.inbox&&(x.date===k||(x.rec&&k>x.date&&(x.rec==='daily'||dw(k)===dw(x.date))))).sort((a,b)=>a.start-b.start||a.end-b.end);
const isDone=x=>x.rec?!!(x.dd&&x.dd[S.sel]):x.done;
const toggle=x=>{if(x.rec){x.dd=x.dd||{};x.dd[S.sel]=!x.dd[S.sel]}else x.done=!x.done;save()};
const dots=k=>[...new Set(on(k).map(x=>x.cat))].slice(0,4).map(c=>`<u style="background:${CATS[c]}"></u>`).join('');

// ---------- Render ----------
function hd(){
  const M=S.month||matchMedia('(min-width:900px)').matches;
  const h=$('#hd');
  if(S.tab!=='tl'){h.innerHTML='';return}
  const sd=new Date(S.sel+'T00:00'),td=iso(new Date());
  let s=`<div class=top><h1>${MN[sd.getMonth()]} <b>${sd.getFullYear()}</b></h1><div><button class=ib data-a=prev aria-label="Sebelumnya">‹</button><button class=ib data-a=today>Hari ini</button><button class=ib data-a=next aria-label="Berikutnya">›</button></div></div>`;
  const cell=(d,o)=>{const k=iso(d);return `<button class="dy${k===S.sel?' sel':''}${k===td?' td':''}${o?' o':''}" data-d="${k}">${M?'':'<small>'+DN[d.getDay()]+'</small>'}<span>${d.getDate()}</span><i>${dots(k)}</i></button>`};
  if(!M){
    s+='<div class=wk id=wk>';const mo=mondayOf(sd);
    for(let i=0;i<7;i++)s+=cell(addD(mo,i));
    s+='</div>';
  }else{
    const f=new Date(sd.getFullYear(),sd.getMonth(),1),st=mondayOf(f);
    s+='<div class=mg>'+['Sen','Sel','Rab','Kam','Jum','Sab','Min'].map(n=>`<small class=mh>${n}</small>`).join('');
    for(let i=0;i<42;i++){const d=addD(st,i);if(i>0&&i%7===0&&d.getMonth()!==f.getMonth())break;s+=cell(d,d.getMonth()!==f.getMonth())}
    s+='</div>';
  }
  s+=`<button class=hdl data-a=mon aria-label="${M?'Ciutkan':'Kembangkan'} kalender"></button>`;
  h.innerHTML=s;
}
const row=x=>{
  const c=CATS[x.cat],d=x.end-x.start,h=Math.max(56,Math.round(d*1.3)),dn=isDone(x);
  const ds=x.subs.filter(s=>s.d).length;
  return `<div class="row${dn?' done':''}" data-id="${x.id}" style="--c:${c}"><div class=tm>${fm(x.start)}</div><div class=pc><div class=pill style="background:${c};height:${h}px">${x.ic}</div><div class=ln></div></div><div class=inf><div class=meta>${fm(x.start)}${d?'–'+fm(x.end)+' ('+dur(d)+')':''}${x.rec?' ↻':''}</div><div class=ttl>${esc(x.title)}</div>${x.subs.length?`<div class=sub>☑ ${ds}/${x.subs.length}</div>`:''}</div><button class=ck data-ck="${x.id}" aria-label="Tandai selesai">${dn?'✓':''}</button></div>`;
};
function tl(){
  let h='<div class=pins>'+S.pins.map(p=>{const dn=p.d===S.sel;return `<button class="pin${dn?' dn':''}" data-pin="${p.id}" style="--c:${CATS[p.c||1]}"><div class="ci${p.ring?' ring':''}" ${p.ring?`style="--p:${p.ring}"`:''}><span>${p.ic}</span></div>${esc(p.t)}</button>`}).join('')+'</div>';
  const L=on(S.sel),now=new Date(),nw=now.getHours()*60+now.getMinutes();
  let nd=S.sel!==iso(now),prev=null;
  const nl=`<div class=now><span>${fm(nw)}</span><i></i></div>`;
  L.forEach(x=>{
    if(prev&&x.start-prev.end>=30)h+=`<div class=gap data-gap="${prev.end}"><div></div><div class=pc><div class=ln></div></div><p>Jeda selesai. Selanjutnya apa?</p></div>`;
    if(!nd&&nw<x.start){h+=nl;nd=true}
    h+=row(x);prev=x;
  });
  if(!nd&&L.length)h+=nl;
  if(!L.length)h+='<p class=empty>Belum ada task di hari ini. Tekan + untuk menambah.</p>';
  return h;
}
function inbox(){
  const L=S.tasks.filter(x=>x.inbox);
  return `<h2>Kotak Masuk</h2><input class=f id=qi placeholder="Tulis task lalu tekan Enter"><p class=mu>Task tanpa jadwal. Tekan judul untuk menjadwalkan.</p>`+
    (L.map(x=>`<div class="it${x.done?' done':''}" style="--c:${CATS[x.cat]}"><button class=ck data-ck="${x.id}" aria-label="Tandai selesai">${x.done?'✓':''}</button><div class=t data-id="${x.id}">${esc(x.title)}</div></div>`).join('')||'<p class=empty>Kotak masuk kosong.</p>');
}
const ai=()=>`<h2>Asisten jadwal</h2><p class=mu>Tulis dengan bahasa sehari-hari, jadwal dibuat otomatis. Contoh: Besok jam 3 sore rapat 1 jam</p><textarea class=f id=ai rows=3 placeholder="Besok jam 3 sore rapat 1 jam"></textarea><button class=btn data-a=ai>Buat jadwal</button><p id=aout class=mu></p>`;
const st=()=>`<h2>Pengaturan</h2><p class=mu>Data tersimpan di browser ini (zona waktu perangkat, awal minggu Senin). Salin teks di bawah untuk cadangan, atau tempel cadangan lalu impor.</p><textarea class=f id=ex rows=6></textarea><div class=acts><button class=btn data-a=exp>Ekspor</button><button class="btn g" data-a=imp>Impor</button><button class="btn g" data-a=reset>Reset data contoh</button></div><p id=sout class=mu></p>`;
function main(){
  const m=$('#main'),y=m.scrollTop;
  m.innerHTML={tl,in:inbox,ai,st}[S.tab]();m.scrollTop=y;
  $('#fab').style.display=S.tab==='tl'||S.tab==='in'?'':'none';
}
function tabs(){
  $('#tabs').innerHTML=[['tl','🗓️','Timeline'],['ai','✨','AI'],['st','⚙️','Pengaturan']].map(t=>`<button class="tb${S.tab===t[0]?' on':''}" data-tab="${t[0]}"><b>${t[1]}</b>${t[2]}</button>`).join('');
}
const render=()=>{hd();main();tabs()};
matchMedia('(min-width:900px)').addEventListener('change',render);

// ---------- Sheet (tambah / edit) ----------
let D=null;
function blank(start,inbox){
  const n=new Date();let s=start;
  if(s==null)s=S.sel===iso(n)?Math.ceil((n.getHours()*60+n.getMinutes()+1)/30)*30:540;
  s=Math.min(s,1380);
  return {id:'',date:S.sel,start:s,end:Math.min(s+60,1439),title:'',cat:1,ic:'💼',done:false,rec:'',subs:[],inbox:!!inbox};
}
function openSheet(x){D=JSON.parse(JSON.stringify(x));sheet()}
function subsHtml(){return D.subs.map((s,i)=>`<div class=sb><input type=checkbox data-sd="${i}" ${s.d?'checked':''} aria-label="Selesai"><span style="flex:1">${esc(s.t)}</span><button data-sx="${i}" aria-label="Hapus subtask">✕</button></div>`).join('')}
function sheet(){
  const o=$('#ov');o.hidden=false;
  o.innerHTML=`<div class=sheet role=dialog aria-label="Task"><h2>${D.id?'Edit task':'Task baru'}</h2>
  <input class=f id=f-t placeholder="Judul task" value="${esc(D.title)}">
  <input class=f id=f-d type=date value="${D.date}">
  <div class=r2><input class=f id=f-s type=time value="${fm(D.start)}" aria-label="Mulai"><input class=f id=f-e type=time value="${fm(D.end)}" aria-label="Selesai"></div>
  <div class=sw id=sw-c>${CATS.map((c,i)=>`<button data-c="${i}" class="${D.cat===i?'on':''}" style="background:${c}" aria-label="Kategori ${i+1}"></button>`).join('')}</div>
  <div class=sw id=sw-i>${ICONS.map(c=>`<button data-i="${c}" class="${D.ic===c?'on':''}">${c}</button>`).join('')}</div>
  <select class=f id=f-r><option value="">Tidak berulang</option><option value=daily ${D.rec==='daily'?'selected':''}>Setiap hari</option><option value=weekly ${D.rec==='weekly'?'selected':''}>Setiap minggu</option></select>
  <div id=subs>${subsHtml()}</div>
  <input class=f id=f-n placeholder="Tambah subtask lalu tekan Enter">
  <div class=acts><button class=btn data-a=sv>Simpan</button>${D.id?'<button class="btn g" data-a=dup>Duplikat</button><button class="btn g" data-a=del>Hapus</button>':''}<button class="btn g" data-a=close>Batal</button></div></div>`;
}
function sync(){
  D.title=$('#f-t').value.trim();D.date=$('#f-d').value||S.sel;
  D.start=pm($('#f-s').value);D.end=Math.max(D.start,pm($('#f-e').value));
  D.rec=$('#f-r').value;D.inbox=false;
}
const closeSheet=()=>{$('#ov').hidden=true;D=null};
function commit(copy){
  sync();
  if(!D.title){$('#f-t').focus();return}
  const i=S.tasks.findIndex(x=>x.id===D.id);
  if(copy){D.id=uid();D.done=false;D.dd={};S.tasks.push(D)}
  else if(i>=0)S.tasks[i]=D;
  else{D.id=uid();S.tasks.push(D)}
  if(!D.inbox)S.sel=D.date;
  save();closeSheet();render();
}

// ---------- Asisten jadwal (parser sederhana, tanpa server) ----------
function parse(s){
  let t=' '+s.toLowerCase()+' ',d=new Date();
  if(/\bbesok\b/.test(t)){d=addD(d,1);t=t.replace('besok','')}
  else if(/\blusa\b/.test(t)){d=addD(d,2);t=t.replace('lusa','')}
  else t=t.replace('hari ini','');
  let st=540,m=t.match(/jam\s*(\d{1,2})(?:[.:](\d{2}))?\s*(pagi|siang|sore|malam)?/);
  if(m){let h=+m[1];if(m[3]&&m[3]!=='pagi'&&h<12)h+=12;st=Math.min(h*60+ +(m[2]||0),1380);t=t.replace(m[0],'')}
  let du=60;m=t.match(/(\d+(?:[.,]\d+)?)\s*(jam|menit)/);
  if(m){const v=parseFloat(m[1].replace(',','.'));du=Math.round(m[2]==='jam'?v*60:v);t=t.replace(m[0],'')}
  t=t.replace(/\b(untuk|selama|pada)\b/g,'').replace(/\s+/g,' ').trim();
  const title=t?t[0].toUpperCase()+t.slice(1):'Task baru';
  return {id:uid(),date:iso(d),start:st,end:Math.min(st+du,1439),title,cat:1,ic:'💼',done:false,rec:'',subs:[]};
}

// ---------- Aksi ----------
function shift(n){
  const sd=new Date(S.sel+'T00:00');
  if(S.month||matchMedia('(min-width:900px)').matches){const y=sd.getFullYear(),m=sd.getMonth()+n,dim=new Date(y,m+1,0).getDate();S.sel=iso(new Date(y,m,Math.min(sd.getDate(),dim)))}
  else S.sel=iso(addD(sd,7*n));
  render();
}
function act(a){
  if(a==='prev')shift(-1);else if(a==='next')shift(1);
  else if(a==='today'){S.sel=iso(new Date());render()}
  else if(a==='mon'){S.month=!S.month;hd()}
  else if(a==='sv')commit(false);else if(a==='dup')commit(true);
  else if(a==='close')closeSheet();
  else if(a==='del'){S.tasks=S.tasks.filter(x=>x.id!==D.id);save();closeSheet();render()}
  else if(a==='ai'){
    const v=$('#ai').value.trim();if(!v)return;
    const x=parse(v);S.tasks.push(x);S.sel=x.date;save();
    $('#aout').textContent='Dibuat: '+x.title+', '+x.date+' pukul '+fm(x.start)+' sampai '+fm(x.end)+'. Lihat di tab Timeline.';$('#ai').value='';
  }
  else if(a==='exp')$('#ex').value=JSON.stringify({t:S.tasks,p:S.pins});
  else if(a==='imp'){
    try{const r=JSON.parse($('#ex').value);if(!r.t)throw 0;S.tasks=r.t;S.pins=r.p||[];save();$('#sout').textContent='Data berhasil diimpor.'}
    catch(e){$('#sout').textContent='Format tidak valid. Tempel hasil ekspor yang utuh.'}
  }
  else if(a==='reset'){seed();$('#sout').textContent='Data contoh dipulihkan.'}
}
// Tombol kembali ke website portofolio
document.addEventListener('click',e=>{
  const b=e.target.closest&&e.target.closest('#back');if(!b)return;
  e.preventDefault();
  window.close();
  setTimeout(()=>{window.open(b.href,'_blank')},250);
});
document.addEventListener('click',e=>{
  const g=s=>e.target.closest(s);let el;
  if(el=g('[data-a]'))return act(el.dataset.a);
  if(g('#ov')&&!g('.sheet'))return closeSheet();
  if(el=g('[data-sd]')){D.subs[+el.dataset.sd].d=el.checked;return}
  if(el=g('[data-sx]')){D.subs.splice(+el.dataset.sx,1);$('#subs').innerHTML=subsHtml();return}
  if(el=g('#sw-c [data-c]')){D.cat=+el.dataset.c;document.querySelectorAll('#sw-c button').forEach(b=>b.classList.toggle('on',b===el));return}
  if(el=g('#sw-i [data-i]')){D.ic=el.dataset.i;document.querySelectorAll('#sw-i button').forEach(b=>b.classList.toggle('on',b===el));return}
  if(el=g('[data-tab]')){S.tab=el.dataset.tab;return render()}
  if(g('#fab'))return openSheet(blank(null,S.tab==='in'));
  if(el=g('[data-d]')){S.sel=el.dataset.d;if(S.month)S.month=false;return render()}
  if(el=g('[data-pin]')){const p=S.pins.find(x=>x.id===el.dataset.pin);p.d=p.d===S.sel?'':S.sel;save();return main()}
  if(el=g('[data-ck]')){const x=S.tasks.find(t=>t.id===el.dataset.ck);toggle(x);return main()}
  if(el=g('[data-gap]'))return openSheet(blank(+el.dataset.gap,false));
  if(el=g('[data-id]')){const x=S.tasks.find(t=>t.id===el.dataset.id);if(x){const c={...x};if(c.inbox){c.inbox=false;c.date=S.sel;c.start=540;c.end=600}openSheet(c)}}
});
document.addEventListener('keydown',e=>{
  if(e.key!=='Enter')return;
  if(e.target.id==='f-n'&&e.target.value.trim()){D.subs.push({t:e.target.value.trim(),d:false});e.target.value='';$('#subs').innerHTML=subsHtml()}
  if(e.target.id==='qi'&&e.target.value.trim()){S.tasks.push({id:uid(),date:S.sel,start:0,end:0,title:e.target.value.trim(),cat:1,ic:'💼',done:false,rec:'',subs:[],inbox:true});save();main()}
});
// Geser kiri/kanan pada header untuk pindah minggu
let tx=null;const H=$('#hd');
H.addEventListener('touchstart',e=>{tx=e.touches[0].clientX},{passive:true});
H.addEventListener('touchend',e=>{if(tx==null)return;const dx=e.changedTouches[0].clientX-tx;tx=null;if(Math.abs(dx)>60)shift(dx<0?1:-1)});
// Garis "sekarang" ikut bergerak tiap menit
setInterval(()=>{if(S.tab==='tl'&&$('#ov').hidden)main()},60000);
render();
</script>
</body>
</html>
