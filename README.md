<!DOCTYPE html>
<html lang="en"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Billoti Balloon Shop</title>
<link href="https://fonts.googleapis.com/css2?family=Baloo+2:wght@500;700;800&display=swap" rel="stylesheet">
<style>
:root{--bg:#1b1330;--w1:#b06f3f;--w2:#7a4524;--wd:#4b2a14;--tx:#ffe9b8;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0e0a1c}}
:root[data-theme="dark"]{--bg:#0e0a1c}
*{box-sizing:border-box;-webkit-tap-highlight-color:transparent}
html,body{margin:0;height:100%;background:var(--bg);font-family:'Baloo 2',system-ui,sans-serif;user-select:none;-webkit-user-select:none;touch-action:none;overflow:hidden}
#app{position:fixed;inset:0;margin:auto;max-width:480px;overflow:hidden;color:#fff}
.scr{position:absolute;inset:0;display:none;flex-direction:column;align-items:center;padding:12px 14px;padding-top:calc(12px + env(safe-area-inset-top,0px));padding-bottom:calc(12px + env(safe-area-inset-bottom,0px))}
.scr.on{display:flex}
.wood{background:linear-gradient(var(--w1),var(--w2));border:3px solid var(--wd);border-radius:14px;color:var(--tx);box-shadow:0 3px 0 #0005,inset 0 2px 0 #fff3}
.logo{position:relative;text-align:center;padding:8px 22px 4px;margin-top:22px}
.logo b{display:block;font-size:52px;line-height:.9;font-weight:800;color:#ffcf40;-webkit-text-stroke:3px #5a2d12;paint-order:stroke fill;text-shadow:0 4px 0 #5a2d12}
.logo span{font-size:22px;font-weight:800;color:#ffe9b8}
.logo i{position:absolute;top:-32px;left:50%;transform:translateX(-50%);font-style:normal;font-size:46px}
.coin{position:absolute;top:calc(10px + env(safe-area-inset-top,0px));right:12px;padding:2px 12px;border-radius:20px;font-weight:800;z-index:5;font-size:18px}
.back{position:absolute;top:calc(10px + env(safe-area-inset-top,0px));left:12px;width:40px;height:40px;border-radius:50%;font-size:20px;display:grid;place-items:center;z-index:5}
.btn{width:100%;max-width:300px;border:0;border-radius:14px;padding:6px 12px;font:800 22px 'Baloo 2',sans-serif;color:#fff;text-shadow:0 2px 0 #0004;display:flex;gap:10px;justify-content:center;align-items:center;box-shadow:0 4px 0 #0005,inset 0 2px 0 #fff5;touch-action:manipulation}
.btn:active{transform:translateY(3px)}
.g{background:linear-gradient(#5fd35f,#2d9a35)}.o{background:linear-gradient(#ffb93d,#e08a00)}.p{background:linear-gradient(#a56cf0,#6c3ac4)}.b{background:linear-gradient(#3fb6f2,#1c7fc2)}.r{background:linear-gradient(#f4645f,#c22e32)}
.btn.dis{filter:grayscale(1);opacity:.7}
/* splash */
#splash{background:linear-gradient(#2b2f77,#c95b9f 60%,#ffb36b);justify-content:flex-start}
#splash .cat{font-size:130px;margin-top:auto;line-height:1}
.ld{width:80%;height:22px;border-radius:12px;border:3px solid #fff;background:#0004;overflow:hidden;margin-bottom:20px;margin-top:10px}.ld i{display:block;height:100%;width:0;background:linear-gradient(#ffb93d,#e08a00);animation:ld 1.8s forwards}
@keyframes ld{to{width:100%}}
.city{position:absolute;left:0;right:0;bottom:0;height:34%;background:linear-gradient(transparent,#1a1440);clip-path:polygon(0 60%,8% 60%,8% 35%,16% 35%,16% 55%,26% 55%,26% 25%,34% 25%,34% 50%,45% 50%,45% 38%,55% 38%,55% 60%,68% 60%,68% 30%,78% 30%,78% 52%,90% 52%,90% 42%,100% 42%,100% 100%,0 100%);opacity:.9}
/* home */
#home{background:linear-gradient(#57b7f5,#cfeeff 55%,#f5d9a8);gap:8px;justify-content:flex-start}
.banw{position:relative;margin-top:40px;width:94%;text-align:center}.ban{padding:4px 14px;background:linear-gradient(#ffe27a,#f2b72e);color:#7a1b4d;font:800 24px 'Baloo 2';font-size:clamp(17px,5.6vw,24px);border:3px solid #a8691c;border-radius:10px;box-shadow:0 3px 0 #0003;white-space:nowrap}.bl,.br{position:absolute;top:-32px;font-size:30px}.bl{left:0}.br{right:0}
@keyframes fl{50%{transform:translateY(-6px)}}.bl,.br{animation:fl 2s infinite}.br{animation-delay:.7s}
.shopf{position:relative;width:86%;flex:0 0 auto;height:190px;margin-top:10px;background:linear-gradient(#8a5a35,#5a3a20);border:4px solid var(--wd);border-radius:10px} <!DOCTYPE html>
<html lang="en"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Billoti Balloon Shop</title>
<link href="https://fonts.googleapis.com/css2?family=Baloo+2:wght@500;700;800&display=swap" rel="stylesheet">
<style>
:root{--bg:#1b1330;--w1:#b06f3f;--w2:#7a4524;--wd:#4b2a14;--tx:#ffe9b8;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0e0a1c}}
:root[data-theme="dark"]{--bg:#0e0a1c}
*{box-sizing:border-box;-webkit-tap-highlight-color:transparent}
html,body{margin:0;height:100%;background:var(--bg);font-family:'Baloo 2',system-ui,sans-serif;user-select:none;-webkit-user-select:none;touch-action:none;overflow:hidden}
#app{position:fixed;inset:0;margin:auto;max-width:480px;overflow:hidden;color:#fff}
.scr{position:absolute;inset:0;display:none;flex-direction:column;align-items:center;padding:12px 14px;padding-top:calc(12px + env(safe-area-inset-top,0px));padding-bottom:calc(12px + env(safe-area-inset-bottom,0px))}
.scr.on{display:flex}
.wood{background:linear-gradient(var(--w1),var(--w2));border:3px solid var(--wd);border-radius:14px;color:var(--tx);box-shadow:0 3px 0 #0005,inset 0 2px 0 #fff3}
.logo{position:relative;text-align:center;padding:8px 22px 4px;margin-top:22px}
.logo b{display:block;font-size:52px;line-height:.9;font-weight:800;color:#ffcf40;-webkit-text-stroke:3px #5a2d12;paint-order:stroke fill;text-shadow:0 4px 0 #5a2d12}
.logo span{font-size:22px;font-weight:800;color:#ffe9b8}
.logo i{position:absolute;top:-32px;left:50%;transform:translateX(-50%);font-style:normal;font-size:46px}
.coin{position:absolute;top:calc(10px + env(safe-area-inset-top,0px));right:12px;padding:2px 12px;border-radius:20px;font-weight:800;z-index:5;font-size:18px}
.back{position:absolute;top:calc(10px + env(safe-area-inset-top,0px));left:12px;width:40px;height:40px;border-radius:50%;font-size:20px;display:grid;place-items:center;z-index:5}
.btn{width:100%;max-width:300px;border:0;border-radius:14px;padding:6px 12px;font:800 22px 'Baloo 2',sans-serif;color:#fff;text-shadow:0 2px 0 #0004;display:flex;gap:10px;justify-content:center;align-items:center;box-shadow:0 4px 0 #0005,inset 0 2px 0 #fff5;touch-action:manipulation}
.btn:active{transform:translateY(3px)}
.g{background:linear-gradient(#5fd35f,#2d9a35)}.o{background:linear-gradient(#ffb93d,#e08a00)}.p{background:linear-gradient(#a56cf0,#6c3ac4)}.b{background:linear-gradient(#3fb6f2,#1c7fc2)}.r{background:linear-gradient(#f4645f,#c22e32)}
.btn.dis{filter:grayscale(1);opacity:.7}
/* splash */
#splash{background:linear-gradient(#2b2f77,#c95b9f 60%,#ffb36b);justify-content:flex-start}
#splash .cat{font-size:130px;margin-top:auto;line-height:1}
.ld{width:80%;height:22px;border-radius:12px;border:3px solid #fff;background:#0004;overflow:hidden;margin-bottom:20px;margin-top:10px}.ld i{display:block;height:100%;width:0;background:linear-gradient(#ffb93d,#e08a00);animation:ld 1.8s forwards}
@keyframes ld{to{width:100%}}
.city{position:absolute;left:0;right:0;bottom:0;height:34%;background:linear-gradient(transparent,#1a1440);clip-path:polygon(0 60%,8% 60%,8% 35%,16% 35%,16% 55%,26% 55%,26% 25%,34% 25%,34% 50%,45% 50%,45% 38%,55% 38%,55% 60%,68% 60%,68% 30%,78% 30%,78% 52%,90% 52%,90% 42%,100% 42%,100% 100%,0 100%);opacity:.9}
/* home */
#home{background:linear-gradient(#57b7f5,#cfeeff 55%,#f5d9a8);gap:8px;justify-content:flex-start}
.banw{position:relative;margin-top:40px;width:94%;text-align:center}.ban{padding:4px 14px;background:linear-gradient(#ffe27a,#f2b72e);color:#7a1b4d;font:800 24px 'Baloo 2';font-size:clamp(17px,5.6vw,24px);border:3px solid #a8691c;border-radius:10px;box-shadow:0 3px 0 #0003;white-space:nowrap}.bl,.br{position:absolute;top:-32px;font-size:30px}.bl{left:0}.br{right:0}
@keyframes fl{50%{transform:translateY(-6px)}}.bl,.br{animation:fl 2s infinite}.br{animation-delay:.7s}
.shopf{position:relative;width:86%;flex:0 0 auto;height:190px;margin-top:10px;background:linear-gradient(#8a5a35,#5a3a20);border:4px solid var(--wd);border-radius:10px}
