# Top.Earning.Zone
ঘরে বসে কোনো প্রকার ইনভেস্টমেন্ট না করে দৈনিক ১০০-৫০০ টাকা ইনকাম করুন একদম‌ ফ্রি।
<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>top-earning-point - 100% Trusted</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Hind Siliguri,sans-serif}
body{background:#000;color:#fff}
.auth{max-width:430px;margin:0 auto;padding:18px;min-height:100vh;display:flex;flex-direction:column;justify-content:center}
.logo{text-align:center;margin-bottom:18px}
.logo h1{color:#00ff88;font-size:28px;font-weight:900;text-transform:uppercase;letter-spacing:1px}
.logo p{color:#888;font-size:12px;margin-top:6px;line-height:1.5}
.card{background:#111;border:1px solid #222;border-radius:18px;padding:15px;margin:10px 12px}
.input{width:100%;padding:13px;background:#000;border:1px solid #333;border-radius:10px;color:#fff;margin-top:10px;outline:none}
.btn{width:100%;padding:13px;border:none;border-radius:12px;font-weight:900;margin-top:12px;cursor:pointer;font-size:14px}
.btn-g{background:#00ff88;color:#000}
.btn-y{background:#f1c40f;color:#000}
.btn-o{background:transparent;border:1px solid #333;color:#888}
.top{background:linear-gradient(90deg,#00ff88,#00cc77);padding:16px;border-radius:0 0 22px 22px;color:#000;text-align:center}
.wallet{display:flex;justify-content:space-between;align-items:center}
.badge{background:rgba(0,0,0,.2);padding:4px 12px;border-radius:20px;font-size:11px;font-weight:700}
.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:10px;margin-top:12px}
.task{background:#1a1a1a;border:1px solid #252525;border-radius:16px;padding:16px;text-align:center;cursor:pointer;transition:.2s}
.task:active{transform:scale(.96)}
.task i{font-size:28px;display:block;margin-bottom:8px}
.task b{display:block;font-size:13px}
.task span{font-size:12px;color:#00ff88;font-weight:700}
#dashboard,#admin{display:none}
.note{background:#00ff8811;border:1px solid #00ff8833;color:#00ff88;padding:10px;border-radius:10px;font-size:12px;margin-top:10px}
</style>
</head>
<body>

<!-- LOGIN / REGISTER -->
<div id="auth" class="auth">
<div class="logo">
<h1>top-earning-point</h1>
<p>💳 একাউন্ট ভেরিফাই: মাত্র 5 টাকা<br>💰 দৈনিক ইনকাম: ১০-১০০০ টাকা</p>
</div>
<div class="card">
<h3 id="fTitle">📝 নতুন একাউন্ট খুলুন</h3>
<input id="ph" class="input" placeholder="মোবাইল নাম্বার 01XXXXXXXXX">
<input id="ps" type="password" class="input" placeholder="পাসওয়ার্ড (4 সংখ্যা)">
<input id="ref" class="input" placeholder="রেফার কোড (যদি থাকে)" style="display:block">
<div class="note">✅ 5 টাকা ভেরিফাই করলেই একাউন্ট একটিভ হবে</div>
<button class="btn btn-g" onclick="doAuth()" id="aBtn">একাউন্ট খুলুন - 5৳ ভেরিফাই</button>
<p style="text-align:center;margin-top:12px;font-size:13px;color:#888"><span onclick="tog()" id="tTxt" style="color:#00ff88">লগইন করুন</span></p>
<p style="text-align:center;color:#444;font-size:11px;margin-top:8px">Admin: 01700000000 / admin123</p>
</div>
<div class="card">
<p style="font-size:13px;line-height:1.6">⏳ তাই দেরি না করে এখনই একাউন্ট খুলে কাজ শুরু করুন এবং নিজের ইনকাম বাড়ান।</p>
</div>
</div>

<!-- USER DASHBOARD -->
<div id="dashboard">
<div class="top"><h2 style="text-transform:uppercase">top-earning-point</h2><p id="uId" style="font-size:11px;font-weight:700"></p></div>
<div class="card wallet"><div><span class="badge">● Verified</span><h3 id="uName" style="margin-top:6px"></h3><small id="uRef" style="color:#00ff88;font-size:12px"></small></div><div style="text-align:right"><small style="color:#aaa">ব্যালেন্স</small><h2 style="color:#f1c40f">৳ <span id="bal">0</span></h2></div></div>

<div class="card">
<h3>📌 এখানে যে কাজগুলো করতে পারবেন:</h3>
<div class="grid" id="tGrid"></div>
<div class="note">💰 দৈনিক ইনকাম: প্রায় ১০-১০০০ টাকা পর্যন্ত</div>
</div>

<div class="card">
<h3>📤 উইথড্র সুবিধা:</h3>
<p style="font-size:13px;color:#aaa;margin-top:6px">✔ কোন রেফার ছাড়াই উইথড্র করা যাবে<br>✔ মাত্র ৫০ টাকা হলেই উইথড্র</p>
<input id="bk" class="input" placeholder="বিকাশ/নগদ নাম্বার দিন">
<button class="btn btn-y" onclick="wd()">৫০ টাকা উইথড্র করুন</button>
</div>

<div class="card">
<h3>✅ রেফার বোনাস এবং মাসিক স্যালারি</h3>
<div id="rlink" style="background:#000;border:1px dashed #333;padding:10px;border-radius:10px;font-size:12px;word-break:break-all"></div>
<p style="font-size:12px;color:#888;margin-top:6px">প্রতি রেফারে ২০% + ১০ রেফারে ৩০০০৳ স্যালারি</p>
<button class="btn btn-o" onclick="logout()">লগআউট</button>
</div>
</div>

<!-- ADMIN -->
<div id="admin">
<div style="background:#ff4757;padding:16px;text-align:center"><h2>ADMIN PANEL</h2><p>সব কন্ট্রোল</p></div>
<div class="card" id="aUsers"></div>
<div class="card"><button class="btn btn-g" onclick="location.reload()">ইউজার সাইটে যান</button></div>
</div>

<script>
const TASKS=[
{id:'typing',n:'Typing কাজ',i:'fa-keyboard',p:10,c:'#0a84ff',d:'টাইপ করে ইনকাম'},
{id:'gmail',n:'Gmail কাজ',i:'fa-envelope',p:15,c:'#ea4335',d:'জিমেইল দিয়ে'},
{id:'fb',n:'Facebook কাজ',i:'fa-brands fa-facebook',p:12,c:'#1877f2',d:'ফলো/লাইক'},
{id:'math',n:'Math solve কাজ',i:'fa-calculator',p:8,c:'#f1c40f',d:'অংক সমাধান'},
{id:'video',n:'Video Watching',i:'fa-play',p:10,c:'#ff4757',d:'ভিডিও দেখা'},
{id:'insta',n:'Instagram sell',i:'fa-brands fa-instagram',p:20,c:'#e4405f',d:'ইন্সটা সেল'},
{id:'refer',n:'রেফার বোনাস',i:'fa-users',p:30,c:'#00ff88',d:'মাসিক স্যালারি'}
];
let isLogin=false, cur=null;
function tog(){isLogin=!isLogin; document.getElementById('fTitle').innerText=isLogin?'🔐 লগইন করুন':'📝 নতুন একাউন্ট খুলুন'; document.getElementById('aBtn').innerText=isLogin?'লগইন করুন':'একাউন্ট খুলুন - 5৳ ভেরিফাই'; document.getElementById('tTxt').innerText=isLogin?'নতুন একাউন্ট খুলুন':'লগইন করুন'; document.getElementById('ref').style.display=isLogin?'none':'block';}
tog(); tog();
function doAuth(){
let ph=document.getElementById('ph').value, ps=document.getElementById('ps').value, rc=document.getElementById('ref').value;
if(ph.length<11||ps.length<3){alert('সঠিক নাম্বার ও পাস দিন');return;}
let users=JSON.parse(localStorage.getItem('tep_u')||'[]');
if(!isLogin){
if(users.find(u=>u.phone==ph)){alert('একাউন্ট আছে, লগইন করুন'); isLogin=true; tog(); return;}
if(!confirm('5 টাকা ভেরিফাই ফি কাটা হবে, রাজি?'))return;
let b=10; if(rc){ let ru=users.find(u=>u.myRef==rc||u.phone==rc); if(ru){ru.balance+=20; b+=5;} }
let nu={phone:ph,pass:ps,balance:b,myRef:ph.slice(-4)+Math.floor(Math.random()*90+10)}; users.push(nu); localStorage.setItem('tep_u',JSON.stringify(users)); alert('একাউন্ট সফল! বোনাস '+b+'৳ পেয়েছেন'); isLogin=true; tog();
}else{
if(ph=='01700000000'&&ps=='admin123'){document.getElementById('auth').style.display='none';document.getElementById('admin').style.display='block';let h=''; users.forEach(u=>{h+=`<div style="display:flex;justify-content:space-between;padding:8px;background:#1a1a1a;border-radius:8px;margin-top:6px"><span>${u.phone} - ${u.balance}৳</span><span>${u.myRef}</span></div>`});document.getElementById('aUsers').innerHTML='<h3>মোট ইউজার: '+users.length+'</h3>'+h;return;}
let u=users.find(u=>u.phone==ph&&u.pass==ps); if(!u){alert('ভুল তথ্য');return;} cur=u; show();
}}
function show(){
document.getElementById('auth').style.display='none'; document.getElementById('dashboard').style.display='block';
document.getElementById('uName').innerText=cur.phone; document.getElementById('uId').innerText='ID: TEP-'+cur.myRef; document.getElementById('uRef').innerText='Ref: '+cur.myRef; document.getElementById('bal').innerText=cur.balance; document.getElementById('rlink').innerText='https://'+location.host+'/?ref='+cur.myRef;
let g=''; TASKS.forEach(t=>{ g+=`<div class="task" onclick="task('${t.id}',${t.p})"><i class="fa-solid ${t.i}" style="color:${t.c}"></i><b>${t.n}</b><span>+${t.p}৳</span></div>`;}); document.getElementById('tGrid').innerHTML=g;
}
function task(id,p){ if(id=='refer'){alert('রেফার লিংক কপি করে বন্ধুদের দিন, প্রতি রেফারে 20৳ পাবেন + মাসিক 3000৳');return;} cur.balance+=p; up(); alert('✅ '+p+' টাকা যোগ হয়েছে!');}
function wd(){ if(cur.balance<50){alert('৫০৳ লাগবে, আছে '+cur.balance+'৳ - কোন রেফার লাগবে না, শুধু কাজ করুন');return;} if(document.getElementById('bk').value.length<11){alert('বিকাশ নাম্বার দিন');return;} cur.balance-=50; up(); alert('উইথড্র সফল! ২৪ ঘন্টায় পেমেন্ট পাবেন');}
function up(){ document.getElementById('bal').innerText=cur.balance; let users=JSON.parse(localStorage.getItem('tep_u')||'[]'); let i=users.findIndex(u=>u.phone==cur.phone); users[i]=cur; localStorage.setItem('tep_u',JSON.stringify(users));}
function logout(){location.reload();}
</script>
</body>
</html>
