<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Sopaan · Probability</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,700&family=Source+Sans+3:wght@400;600;700&family=IBM+Plex+Mono:wght@500;600&display=swap">
<style>
  html,body{margin:0;} img{max-width:100%;} [hidden]{display:none !important;}
  :root{
    --navy:#16264A; --navy-2:#1F3B6B; --gold:#C79A3E; --gold-soft:#F3E7C9;
    --paper:#FBF9F4; --paper-2:#F1EAD8; --card:#FFFFFF;
    --ink:#211E1A; --ink-soft:#655D4C; --rule:#E4DCC8;
    --success:#2E8B57; --success-soft:#E1F2E7;
    --danger:#BF4B45; --danger-soft:#FAE3E1;
    --locked:#C7BEA9;
    --focus:#1F3B6B;
    --accent-text:#1F3B6B; --retry-text:#8A661F;
    color-scheme:light;
  }
  @media (prefers-color-scheme: dark){
    :root:not([data-theme="light"]){
      --navy:#0E1830; --navy-2:#16264A; --gold:#E0B75B; --gold-soft:#3A2F16;
      --paper:#141210; --paper-2:#1C1914; --card:#1C1914;
      --ink:#EDE7DA; --ink-soft:#B2A996; --rule:#3A342A;
      --success:#7BC79A; --success-soft:#1B2E22;
      --danger:#E38884; --danger-soft:#331D1B;
      --locked:#4A4436;
      --focus:#E0B75B;
      --accent-text:#E0B75B; --retry-text:#E0B75B;
      color-scheme:dark;
    }
  }
  :root[data-theme="dark"]{
    --navy:#0E1830; --navy-2:#16264A; --gold:#E0B75B; --gold-soft:#3A2F16;
    --paper:#141210; --paper-2:#1C1914; --card:#1C1914;
    --ink:#EDE7DA; --ink-soft:#B2A996; --rule:#3A342A;
    --success:#7BC79A; --success-soft:#1B2E22;
    --danger:#E38884; --danger-soft:#331D1B;
    --locked:#4A4436;
    --focus:#E0B75B;
    --accent-text:#E0B75B; --retry-text:#E0B75B;
    color-scheme:dark;
  }

  *{box-sizing:border-box;}
  body{background:var(--paper); color:var(--ink); font-family:'Source Sans 3',-apple-system,'Segoe UI',sans-serif; padding-inline:0; padding-block:0;}
  h1,h2,h3{font-family:'Fraunces',Georgia,serif; text-wrap:balance; margin:0;}
  .num{font-family:'IBM Plex Mono',ui-monospace,monospace; font-variant-numeric:tabular-nums;}

  header.brand{
    background:linear-gradient(155deg,var(--navy) 0%, var(--navy-2) 100%);
    color:#F4EFDF; padding-block:calc(20px + env(safe-area-inset-top,0px)) 18px; padding-inline:20px;
  }
  .brand-row{display:flex; align-items:center; gap:12px; max-width:900px; margin:0 auto;}
  .crest{
    width:42px; height:42px; border-radius:10px; background:var(--gold); color:var(--navy);
    display:flex; align-items:center; justify-content:center; font-family:'Fraunces',serif; font-weight:700; font-size:18px; flex-shrink:0;
  }
  .brand-name{font-size:12px; letter-spacing:.08em; text-transform:uppercase; color:var(--gold); font-weight:700;}
  .series-name{font-size:19px; font-weight:700; font-family:'Fraunces',serif;}
  .chapter-eyebrow{max-width:900px; margin:14px auto 0; font-size:12px; letter-spacing:.06em; text-transform:uppercase; color:#AEB9D6;}
  .chapter-title{font-size:28px; max-width:900px; margin:2px auto 0;}
  .chapter-sub{font-size:14.5px; color:var(--gold); font-weight:700; max-width:900px; margin:3px auto 0;}

  .chapter-progress{max-width:900px; margin:14px auto 0; display:flex; align-items:center; gap:10px;}
  .cp-track{flex:1; height:6px; border-radius:99px; background:rgba(255,255,255,.18); overflow:hidden;}
  .cp-fill{height:100%; background:var(--gold); border-radius:99px; transition:width .3s ease;}
  .cp-label{font-size:11.5px; color:#CFD7EA; white-space:nowrap;}

  .tabbar{position:sticky; top:env(safe-area-inset-top,0px); z-index:15; background:var(--paper); border-bottom:1px solid var(--rule); overflow-x:auto; white-space:nowrap;}
  .tabbar-inner{max-width:900px; margin:0 auto; display:flex; padding-inline:16px;}
  .tab-btn{font-family:inherit; font-size:14px; font-weight:600; color:var(--ink-soft); background:none; border:none; padding:13px 16px; cursor:pointer; position:relative; flex-shrink:0;}
  .tab-btn.active{color:var(--accent-text);}
  .tab-btn.active::after{content:''; position:absolute; left:12px; right:12px; bottom:0; height:3px; background:var(--gold); border-radius:3px 3px 0 0;}
  .tab-count{font-size:11px; color:var(--ink-soft); margin-left:5px;}

  .slide-progress{max-width:900px; margin:0 auto; padding:10px 16px 0; display:flex; align-items:center; gap:10px;}
  .sp-track{flex:1; height:5px; border-radius:99px; background:var(--rule); overflow:hidden;}
  .sp-fill{height:100%; background:var(--accent-text); border-radius:99px; transition:width .3s ease;}
  .sp-label{font-size:12px; color:var(--ink-soft); white-space:nowrap; font-weight:600;}

  .wrap{max-width:900px; margin:0 auto; padding:16px 16px calc(110px + env(safe-area-inset-bottom,0px));}

  .qcard{background:var(--card); border:1px solid var(--rule); border-radius:14px; padding:18px;}
  .qhead{display:flex; align-items:flex-start; gap:10px; margin-bottom:10px;}
  .qnum{width:32px; height:32px; border-radius:8px; background:var(--gold-soft); color:var(--accent-text); display:flex; align-items:center; justify-content:center; font-weight:700; font-family:'Fraunces',serif; flex-shrink:0; font-size:14px;}
  .qtext{font-size:16px; line-height:1.55; flex:1;}
  .qtag{font-size:10.5px; color:var(--gold); background:var(--gold-soft); padding:2px 7px; border-radius:99px; font-weight:700; margin-left:6px; white-space:nowrap;}
  .marks-pill{font-size:11px; font-weight:700; color:var(--ink-soft); border:1px solid var(--rule); padding:3px 9px; border-radius:99px; margin-left:auto; flex-shrink:0; white-space:nowrap;}
  .step-badge{font-size:11px; font-weight:700; color:var(--accent-text); background:var(--paper-2); border:1px solid var(--rule); padding:3px 9px; border-radius:99px; display:inline-block; margin-bottom:12px;}

  .options{display:flex; flex-direction:column; gap:8px; margin-top:10px;}
  .opt{display:flex; align-items:center; gap:10px; padding:11px 12px; border:1.5px solid var(--rule); border-radius:10px; cursor:pointer; font-size:15px; background:var(--paper);}
  .opt input{accent-color:var(--navy-2);}
  .opt.is-correct{border-color:var(--success); background:var(--success-soft);}
  .opt.is-wrong{border-color:var(--danger); background:var(--danger-soft);}
  .opt.locked{cursor:not-allowed;}

  .subpart-label{font-weight:700; font-size:12.5px; color:var(--accent-text); text-transform:uppercase; letter-spacing:.03em; margin:14px 0 6px;}
  .or-divider{text-align:center; font-size:11px; font-weight:700; letter-spacing:.08em; color:var(--ink-soft); margin:8px 0;}

  .steps{display:flex; flex-direction:column; gap:10px;}
  .step-line{font-size:14.5px; line-height:1.9; background:var(--paper); border:1px dashed var(--rule); border-radius:10px; padding:9px 12px;}
  .step-line.resolved{opacity:.9;}
  .blank-input{font-family:'IBM Plex Mono',monospace; font-size:14px; border:1.5px solid var(--rule); border-radius:6px; padding:3px 8px; width:120px; background:var(--card); color:var(--ink); margin:0 2px;}
  .blank-input:focus{outline:none; border-color:var(--focus); box-shadow:0 0 0 3px var(--gold-soft);}
  .blank-input.is-correct{border-color:var(--success); background:var(--success-soft);}
  .blank-input.is-wrong{border-color:var(--danger); background:var(--danger-soft);}
  .blank-input[disabled]{opacity:.85;}
  .reveal-note{font-size:12px; color:var(--danger); padding-left:2px; margin-top:-2px;}

  .feedback{font-size:13.5px; padding:10px 12px; border-radius:9px; margin-top:14px; display:none;}
  .feedback.show{display:block;}
  .feedback.ok{background:var(--success-soft); color:var(--success);}
  .feedback.retry{background:var(--gold-soft); color:var(--retry-text);}
  .feedback.reveal{background:var(--danger-soft); color:var(--danger);}
  .feedback.err{background:var(--danger-soft); color:var(--danger);}
  .attempts-dots{display:inline-flex; gap:4px; margin-left:2px;}
  .attempts-dots span{width:6px; height:6px; border-radius:50%; background:var(--ink-soft); opacity:.3; display:inline-block;}
  .attempts-dots span.used{opacity:1; background:var(--danger);}

  .ar-box{background:var(--paper-2); border-radius:10px; padding:10px 12px; margin-bottom:12px; font-size:13px; color:var(--ink-soft);}

  .navbar{
    position:fixed; left:0; right:0; bottom:0; z-index:30; background:var(--paper);
    border-top:1px solid var(--rule); padding:10px 16px calc(10px + env(safe-area-inset-bottom,0px));
  }
  .navbar-inner{max-width:900px; margin:0 auto; display:flex; gap:8px; flex-wrap:wrap; align-items:center;}
  .btn{font-family:inherit; font-size:13.5px; font-weight:700; padding:10px 14px; border-radius:9px; border:1.5px solid var(--rule); background:var(--card); color:var(--ink); cursor:pointer;}
  .btn:hover{border-color:var(--navy-2);}
  .btn:disabled{opacity:.4; cursor:not-allowed;}
  .btn-primary{background:var(--navy-2); color:#fff; border-color:var(--navy-2);}
  .navbar .spacer{flex:1;}

  .fab{position:fixed; right:16px; bottom:calc(74px + env(safe-area-inset-bottom,0px)); background:var(--gold); color:var(--navy); border:none; border-radius:999px; padding:11px 16px; font-family:inherit; font-weight:700; font-size:13px; display:flex; align-items:center; gap:7px; cursor:pointer; box-shadow:0 6px 16px rgba(0,0,0,.18); z-index:35;}
  .fab-badge{background:rgba(255,255,255,.55); border-radius:99px; padding:1px 7px; font-size:11px;}

  .overlay{position:fixed; inset:0; background:rgba(20,18,14,.45); z-index:50; display:none; align-items:flex-end; justify-content:center;}
  .overlay.show{display:flex;}
  .palette{background:var(--card); width:min(480px,100%); max-height:78vh; overflow-y:auto; border-radius:18px 18px 0 0; padding:18px 18px calc(18px + env(safe-area-inset-bottom,0px)); border:1px solid var(--rule); border-bottom:none;}
  @media (min-width:640px){ .overlay{align-items:center;} .palette{border-radius:18px; border-bottom:1px solid var(--rule); max-height:74vh;} }
  .palette-head{display:flex; align-items:center; justify-content:space-between; margin-bottom:6px;}
  .palette-head h2{font-size:16px;}
  .palette-close{background:none; border:none; font-size:20px; color:var(--ink-soft); cursor:pointer; padding:4px;}
  .palette-legend{display:flex; gap:12px; flex-wrap:wrap; font-size:11px; color:var(--ink-soft); margin:10px 0 14px;}
  .palette-legend span{display:inline-flex; align-items:center; gap:5px;}
  .dot{width:9px; height:9px; border-radius:50%; display:inline-block;}
  .dot.correct{background:var(--success);} .dot.revealed{background:var(--danger);}
  .dot.skipped{background:var(--gold);} .dot.locked{background:var(--locked);}
  .dot.current{background:var(--navy-2);}
  .chip-grid{display:grid; grid-template-columns:repeat(auto-fill,minmax(48px,1fr)); gap:8px;}
  .chip{border:1.5px solid var(--rule); border-radius:9px; padding:8px 4px; text-align:center; font-family:'IBM Plex Mono',monospace; font-size:12.5px; font-weight:600; cursor:pointer; background:var(--paper); color:var(--ink);}
  .chip[data-status="correct"]{border-color:var(--success); background:var(--success-soft); color:var(--success);}
  .chip[data-status="revealed"]{border-color:var(--danger); background:var(--danger-soft); color:var(--danger);}
  .chip[data-status="skipped"]{border-color:var(--gold); background:var(--gold-soft); color:var(--retry-text);}
  .chip[data-status="locked"]{border-color:var(--rule); color:var(--locked); cursor:not-allowed; background:var(--paper-2);}
  .chip[data-status="current"]{outline:2px solid var(--navy-2); outline-offset:1px;}

  .toast{position:fixed; left:50%; bottom:calc(140px + env(safe-area-inset-bottom,0px)); transform:translateX(-50%); background:var(--ink); color:var(--paper); padding:9px 16px; border-radius:99px; font-size:13px; opacity:0; pointer-events:none; transition:opacity .25s ease; z-index:60;}
  .toast.show{opacity:1;}

  .done-card{text-align:center; padding:36px 20px;}
  .done-card .big{font-size:38px; margin-bottom:6px;}
  .score-pills{display:flex; gap:10px; justify-content:center; flex-wrap:wrap; margin:16px 0;}
  .score-pill{padding:8px 16px; border-radius:99px; font-size:13px; font-weight:700;}

  footer.brandfoot{max-width:900px; margin:14px auto 0; padding:0 16px calc(110px + env(safe-area-inset-bottom,0px)); text-align:center; font-size:12px; color:var(--ink-soft);}

  .mode-pill{font-family:inherit; font-size:12.5px; font-weight:700; color:var(--navy); background:var(--gold); border:none; border-radius:99px; padding:6px 14px; cursor:pointer; margin-top:12px; display:inline-flex; align-items:center; gap:6px;}
  .mode-pick{display:flex; flex-direction:column; gap:14px; padding:8px 0 24px;}
  .mode-card{background:var(--card); border:1.5px solid var(--rule); border-radius:16px; padding:22px; cursor:pointer; text-align:left;}
  .mode-card:hover{border-color:var(--navy-2);}
  .mode-card .mode-icon{font-size:26px; margin-bottom:8px;}
  .mode-card h3{font-size:18px; margin-bottom:6px;}
  .mode-card p{font-size:13.5px; color:var(--ink-soft); line-height:1.5; margin:0;}
  .quiz-hint{font-size:12.5px; color:var(--ink-soft); background:var(--paper-2); border-radius:9px; padding:8px 12px; margin-bottom:14px;}
  .review-row{border:1px solid var(--rule); border-radius:10px; padding:11px 13px; margin-bottom:10px;}
  .review-tag{font-size:11.5px; font-weight:700; margin-bottom:4px; display:block;}
  .review-tag.ok{color:var(--success);} .review-tag.bad{color:var(--danger);} .review-tag.na{color:var(--ink-soft);}
  .review-q{font-size:13.5px; margin-bottom:6px; color:var(--ink-soft);}
  .review-ans{font-size:13px; margin-bottom:2px;}

  .who-row{max-width:900px; margin:12px auto 0; display:flex; flex-wrap:wrap; gap:8px; align-items:center;}
  .who-row .mode-pill{margin-top:0;}
  .who{display:inline-flex; flex-wrap:wrap; align-items:center; gap:6px; font-size:12.5px; color:#CFD7EA;}
  .who b{color:#F4EFDF;}
  .who button{font-family:inherit; font-size:12px; font-weight:700; color:#F4EFDF; background:rgba(255,255,255,.12); border:1px solid rgba(255,255,255,.22); border-radius:99px; padding:5px 11px; cursor:pointer;}
  .who button:hover{background:rgba(255,255,255,.2);}
  .login-card{max-width:460px; margin:8px auto 0; background:var(--card); border:1px solid var(--rule); border-radius:16px; padding:22px;}
  .login-card h2{font-size:21px; margin-bottom:4px;}
  .login-card p.lead{font-size:13.5px; color:var(--ink-soft); margin:0 0 16px; line-height:1.5;}
  .fld{display:flex; flex-direction:column; gap:5px; margin-bottom:12px;}
  .fld label{font-size:12px; font-weight:700; letter-spacing:.04em; text-transform:uppercase; color:var(--ink-soft);}
  .fld input{font-family:inherit; font-size:15px; padding:10px 12px; border:1.5px solid var(--rule); border-radius:9px; background:var(--paper); color:var(--ink);}
  .fld input:focus{outline:none; border-color:var(--focus); box-shadow:0 0 0 3px var(--gold-soft);}
  .fld-row{display:grid; grid-template-columns:1fr 1fr; gap:10px;}
  .login-err{font-size:13px; color:var(--danger); background:var(--danger-soft); border-radius:8px; padding:8px 10px; margin-bottom:12px;}
  .login-note{font-size:12px; color:var(--ink-soft); margin-top:12px; line-height:1.5;}
  .known{margin:0 0 16px; display:flex; flex-direction:column; gap:6px;}
  .known-label{font-size:12px; font-weight:700; letter-spacing:.04em; text-transform:uppercase; color:var(--ink-soft);}
  .known-btn{display:flex; justify-content:space-between; align-items:center; gap:10px; text-align:left; font-family:inherit; font-size:14.5px; padding:10px 12px; border:1.5px solid var(--rule); border-radius:10px; background:var(--paper); color:var(--ink); cursor:pointer;}
  .known-btn:hover{border-color:var(--navy-2);}
  .known-btn small{font-size:12px; color:var(--ink-soft);}
  .rec-card{background:var(--card); border:1px solid var(--rule); border-radius:14px; padding:18px; margin-bottom:14px;}
  .rec-card h2{font-size:19px; margin-bottom:10px;}
  .rec-card h3{font-size:15px; margin:4px 0 8px;}
  .rec-table-wrap{overflow-x:auto;}
  .rec-table{width:100%; border-collapse:collapse; font-size:13.5px; font-variant-numeric:tabular-nums;}
  .rec-table th{text-align:left; font-size:11.5px; text-transform:uppercase; letter-spacing:.04em; color:var(--ink-soft); padding:6px 8px; border-bottom:1px solid var(--rule); white-space:nowrap;}
  .rec-table td{padding:8px; border-bottom:1px solid var(--rule); white-space:nowrap;}
  .rec-bar{display:inline-block; width:70px; height:6px; border-radius:99px; background:var(--rule); overflow:hidden; vertical-align:middle; margin-right:6px;}
  .rec-bar i{display:block; height:100%; background:var(--success);}
  .rec-empty{font-size:13.5px; color:var(--ink-soft);}
  .sec-sub{max-width:900px; margin:0 auto; padding:10px 16px 0; font-size:12.5px; font-weight:700; color:var(--accent-text); letter-spacing:.02em;}
  .opt{flex-wrap:wrap;}
  .opt-l{font-family:'IBM Plex Mono',monospace; font-size:13px; font-weight:600; color:var(--ink-soft);}
  .opt-t{flex:1; min-width:0;}
  .opt.is-chosen:not(.is-correct):not(.is-wrong){border-color:var(--navy-2); background:var(--gold-soft);}
  .opt-tag{font-size:11px; font-weight:700; padding:2px 8px; border-radius:99px; background:var(--card); border:1px solid currentColor; white-space:nowrap;}
  .opt.is-correct .opt-tag{color:var(--success);} .opt.is-wrong .opt-tag{color:var(--danger);} .opt.is-chosen:not(.is-correct):not(.is-wrong) .opt-tag{color:var(--accent-text);}
  .chosen{font-size:13.5px; margin-top:10px; padding:8px 12px; border-radius:9px;}
  .chosen.ok{background:var(--success-soft); color:var(--success);} .chosen.bad{background:var(--danger-soft); color:var(--danger);}
  .chosen + .chosen{margin-top:6px;}
  .solution{margin-top:14px; border:1px solid var(--rule); border-left:4px solid var(--gold); background:var(--paper-2); border-radius:10px; padding:12px 14px;}
  .sol-h{font-family:'Fraunces',Georgia,serif; font-weight:700; font-size:14px; color:var(--accent-text); margin-bottom:6px;}
  .sol-line{font-size:14.5px; line-height:1.7;}
  .rev-sol summary{cursor:pointer; font-size:12.5px; font-weight:700; color:var(--accent-text); margin-top:6px;}
  .rev-sol .solution{margin-top:8px;}
  .chapter-credit{max-width:900px; margin:4px auto 0; font-size:12px; color:#CFD7EA;}
  footer.brandfoot a{color:inherit;}
  .blank-input.wide{width:260px; max-width:100%; font-family:'Source Sans 3',sans-serif;}
  .blank-input.expr{width:170px; max-width:100%;}
  /*fix-layout*/ .cp-fill,.sp-fill{width:0;} .fld{min-width:0;} .fld input{width:100%; min-width:0; box-sizing:border-box;}
  .fig{margin:6px 0 10px; display:flex; justify-content:center;}
  .figsvg{width:100%; max-width:340px; height:auto; overflow:visible;}
  .figsvg .ln,.figsvg .arm{stroke:var(--ink); stroke-width:1.6; fill:none;}
  .figsvg .arm{stroke:var(--accent-text); stroke-width:2;}
  .figsvg .pt{fill:var(--ink);}
  .figsvg .lb{fill:var(--ink); font:600 13px 'Source Sans 3',sans-serif;}
  .figsvg .al{fill:var(--accent-text); font:700 12px 'Source Sans 3',sans-serif;}
  .figsvg .wg{fill:var(--gold-soft); stroke:var(--gold); stroke-width:1.2;}
  .figsvg .wg2{fill:rgba(199,154,62,.35); stroke:var(--gold); stroke-width:1.2;}
  .figsvg .ra{fill:none; stroke:var(--ink); stroke-width:1.2;}
  .figsvg .ahd{fill:var(--ink);}
  .figsvg .pr{fill:var(--paper-2); stroke:var(--ink-soft); stroke-width:1.2;}
  .figsvg .tk{stroke:var(--ink-soft); stroke-width:.8;}
  .figsvg .po{fill:var(--ink); font:600 8.5px 'IBM Plex Mono',monospace;}
  .figsvg .pi{fill:var(--danger); font:600 7.5px 'IBM Plex Mono',monospace;}
  .figsvg .sh{fill:var(--gold-soft); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .sh2{fill:rgba(199,154,62,.38); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .sh3{fill:rgba(199,154,62,.22); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .none{fill:none;}
  .figsvg .hid{stroke-dasharray:5 4; fill:none;}
  .figsvg .tick{stroke:var(--ink); stroke-width:1.4; fill:none;}
  .figsvg .shd{fill:var(--accent-text); fill-opacity:.55;}
  .figsvg .cell{fill:var(--card); stroke:var(--ink); stroke-width:1.1;}
  .figsvg .dr{fill:var(--danger);} .figsvg .dw{fill:var(--card); stroke:var(--ink); stroke-width:1.2;}
  .figsvg .dotfill{fill:var(--danger);}
  .tt{border-collapse:collapse; font-size:13.5px; margin:4px auto; font-variant-numeric:tabular-nums;} .tt th,.tt td{border:1px solid var(--rule); padding:4px 9px; text-align:left;} .tt th{background:var(--paper-2); font-weight:700;} .ttw{overflow-x:auto; max-width:100%;}
  .fq{display:inline-flex; flex-direction:column; vertical-align:middle; text-align:center; font-size:.82em; line-height:1.12; margin:0 2px;}
  .fq>span:first-child{border-bottom:1.5px solid currentColor; padding:0 2px;}
  .fq>span:last-child{padding:0 2px;}
  .mx{white-space:nowrap;}
  .blank-input.fr{width:110px;}
  @media (prefers-reduced-motion:reduce){ *{transition:none !important;} }
.datline{display:block;margin-top:8px;padding:8px 10px;border-radius:8px;background:var(--paper-2);font:500 14px/1.7 'IBM Plex Mono',monospace;word-spacing:2px;overflow-wrap:anywhere;}
</style>
</head>
<body>
<header class="brand">
  <div class="brand-row">
    <div class="crest">BM</div>
    <div>
      <div class="brand-name">Brain &amp; Mind Academy</div>
      <div class="series-name">Sopaan <span style="font-weight:400;font-size:14px;color:#CFD7EA;">Practice Series</span></div>
    </div>
  </div>
  <div class="chapter-eyebrow">Grade 6 Mathematics · Chapter 17</div>
  <div class="chapter-title">Probability</div>
  <div class="chapter-sub">Exercises 17A–17D · Review Sets · Step-by-Step Practice</div><div class="chapter-credit">Follows Haese Mathematics 6 (MYP 1), Chapter 17</div>
  <div class="chapter-progress">
    <div class="cp-track"><div class="cp-fill" id="cpFill"></div></div>
    <div class="cp-label" id="cpLabel">0% complete</div>
  </div>
  <div class="who-row"><button class="mode-pill" id="modePill" hidden>Choose a mode</button><span class="who" id="whoBar" hidden></span></div>
</header>

<nav class="tabbar"><div class="tabbar-inner" id="tabbar"></div></nav>
<div class="sec-sub" id="secSub"></div><div class="slide-progress"><div class="sp-track"><div class="sp-fill" id="spFill"></div></div><div class="sp-label" id="spLabel">Question 1 of 49</div></div>
<div class="wrap" id="wrap"></div>
<footer class="brandfoot">Brain &amp; Mind Academy · Sopaan Practice Series · Grade 6 Mathematics<br>Exercises follow the structure of <i>Mathematics 6 (MYP 1), 3rd edition</i>, Haese Mathematics. Questions, steps and solutions written by Brain &amp; Mind Academy.</footer>

<div class="navbar"><div class="navbar-inner" id="navbarInner"></div></div>
<button class="fab" id="paletteFab"><span>Questions</span><span class="fab-badge" id="fabBadge">0/49</span></button>

<div class="overlay" id="overlay">
  <div class="palette" role="dialog" aria-label="Question palette">
    <div class="palette-head"><h2 id="paletteTitle">Question palette</h2><button class="palette-close" id="paletteClose">&times;</button></div>
    <div class="palette-legend">
      <span><i class="dot current"></i>Current</span><span><i class="dot correct"></i>Correct</span>
      <span><i class="dot revealed"></i>Revealed</span><span><i class="dot skipped"></i>Skipped</span>
      <span><i class="dot locked"></i>Locked</span>
    </div>
    <div class="chip-grid" id="paletteBody"></div>
  </div>
</div>
<div class="toast" id="toast"></div>

<script>
(function(){
"use strict";

/* ================= audio ================= */
var audioCtx=null;
function ensureAudio(){ if(!audioCtx){ try{ audioCtx=new (window.AudioContext||window.webkitAudioContext)(); }catch(e){} } return audioCtx; }
function playTone(freqs,dur,type){
  var ctx=ensureAudio(); if(!ctx) return;
  try{
    var t0=ctx.currentTime;
    freqs.forEach(function(f,i){
      var o=ctx.createOscillator(), g=ctx.createGain();
      o.type=type||'sine'; o.frequency.value=f;
      var start=t0+i*dur;
      g.gain.setValueAtTime(0.0001,start);
      g.gain.exponentialRampToValueAtTime(0.16,start+0.02);
      g.gain.exponentialRampToValueAtTime(0.0001,start+dur);
      o.connect(g); g.connect(ctx.destination);
      o.start(start); o.stop(start+dur+0.02);
    });
  }catch(e){}
}
function playSuccess(){ playTone([523.25,659.25,783.99],0.11,'sine'); }
function playWrong(){ playTone([220,185],0.14,'square'); }
function playReveal(){ playTone([300,220],0.16,'triangle'); }

/* ================= helpers ================= */
function norm(s){
  return String(s===undefined||s===null?'':s).trim().toLowerCase().replace(/\s+/g,'')
    .replace(/[×∗*·]/g,'x').replace(/÷/g,'/').replace(/–|—|−/g,'-')
    .replace(/[²]/g,'^2').replace(/[³]/g,'^3').replace(/[⁴]/g,'^4').replace(/[⁵]/g,'^5')
    .replace(/[⁶]/g,'^6').replace(/[⁷]/g,'^7').replace(/[⁸]/g,'^8').replace(/[⁹]/g,'^9')
    .replace(/\^/g,'');
}
function parseNum(s){
  if(s===undefined||s===null) return null;
  var t=String(s).trim().replace(/,/g,'').replace(/[−–—]/g,'-').replace(/\s+/g,''); if(t==='') return null;
  var neg=false; if(t[0]==='-'){neg=true;t=t.slice(1);}
  var m=t.match(/^(\d+)\/(\d+)$/);
  if(m){ var v=parseInt(m[1],10)/parseInt(m[2],10); return neg?-v:v; }
  if(/^\d+(\.\d+)?$/.test(t)){ var v2=parseFloat(t); return neg?-v2:v2; }
  return null;
}
/* ---- expression checker: compares answers like (P-2w)/2 and P/2-w at random values ---- */
function exprPrep(s){
  return String(s).replace(/\s+/g,'').replace(/[×∗·]/g,'*').replace(/÷/g,'/').replace(/[−–—]/g,'-')
    .replace(/²/g,'^2').replace(/³/g,'^3').replace(/π/g,'#').replace(/pi/gi,'#').replace(/½/g,'(1/2)');
}
function exprCompile(src){
  var s=exprPrep(src), i=0, toks=[];
  while(i<s.length){
    var ch=s[i];
    if(/[0-9.]/.test(ch)){ var j=i; while(j<s.length && /[0-9.]/.test(s[j])) j++; toks.push({k:'n',v:parseFloat(s.slice(i,j))}); i=j; continue; }
    if(/[a-zA-Z#]/.test(ch)){ toks.push({k:'v',v:ch}); i++; continue; }
    if('+-*/^()'.indexOf(ch)>=0){ toks.push({k:ch}); i++; continue; }
    return null;
  }
  var out=[];
  for(var t=0;t<toks.length;t++){
    var a=toks[t], b=out[out.length-1];
    if(b && (b.k==='n'||b.k==='v'||b.k===')') && (a.k==='n'||a.k==='v'||a.k==='(')) out.push({k:'&'});
    out.push(a);
  }
  var p=0;
  function peek(){ return out[p]; }
  function parseE(){ var n=parseT(); while(peek() && (peek().k==='+'||peek().k==='-')){ var o=out[p++].k, r=parseT(); n=(function(l,r,o){return function(e){ return o==='+'?l(e)+r(e):l(e)-r(e); };})(n,r,o); } return n; }
  function parseI(){ var n=parseU(); while(peek() && peek().k==='&'){ p++; var r=parseP(); n=(function(l,r){return function(e){ return l(e)*r(e); };})(n,r); } return n; }
  function parseT(){ var n=parseI(); while(peek() && (peek().k==='*'||peek().k==='/')){ var o=out[p++].k, r=parseI(); n=(function(l,r,o){return function(e){ return o==='*'?l(e)*r(e):l(e)/r(e); };})(n,r,o); } return n; }
  function parseU(){ if(peek() && peek().k==='-'){ p++; var u=parseU(); return function(e){ return -u(e); }; } if(peek() && peek().k==='+'){ p++; return parseU(); } return parseP(); }
  function parseP(){ var b=parseA(); if(peek() && peek().k==='^'){ p++; var x=parseU(); return function(e){ return Math.pow(b(e),x(e)); }; } return b; }
  function parseA(){
    var t=out[p++]; if(!t) throw 0;
    if(t.k==='n') return function(){ return t.v; };
    if(t.k==='v') return t.v==='#' ? function(){ return Math.PI; } : function(e){ return e[t.v]; };
    if(t.k==='('){ var n=parseE(); if(!peek()||peek().k!==')') throw 0; p++; return n; }
    throw 0;
  }
  try{ var f=parseE(); if(p!==out.length) return null; return f; }catch(e){ return null; }
}
function exprEqual(input,answer){
  var f=exprCompile(input), g=exprCompile(answer); if(!f||!g) return false;
  var hits=0;
  for(var trial=0;trial<8;trial++){
    var env={}; 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ'.split('').forEach(function(c){ env[c]=1.3+Math.random()*4.1; });
    var x=f(env), y=g(env);
    if(!isFinite(x)||!isFinite(y)) continue;
    if(Math.abs(x-y)>1e-7*Math.max(1,Math.abs(x),Math.abs(y))) return false;
    hits++;
  }
  return hits>=3;
}
function wordsNorm(s){ return String(s||'').toLowerCase().replace(/\band\b/g,' ').replace(/[^a-z]/g,''); }
function listNorm(s){ return (String(s||'').replace(/[−–—]/g,'-').replace(/(\d) (?=\d{3}\b)/g,'$1').match(/-?\d+(\.\d+)?/g)||[]).join(','); }
function powNorm(s){ return String(s||'').toLowerCase().replace(/\s+/g,'').replace(/[×∗*·.]/g,'x').replace(/[⁰¹²³⁴⁵⁶⁷⁸⁹]+/g,function(m){ return '^'+m.split('').map(function(c){ return '⁰¹²³⁴⁵⁶⁷⁸⁹'.indexOf(c); }).join(''); }).replace(/\^1(?!\d)/g,''); }
function fr(s){ return String(s).replace(/\{(\d+) (\d+)\/(\d+)\}/g,'<span class="mx">$1<span class="fq"><span>$2</span><span>$3</span></span></span>').replace(/\{(\d+)\/(\d+)\}/g,'<span class="fq"><span>$1</span><span>$2</span></span>'); }
function gcdI(a,b){ a=Math.abs(a); b=Math.abs(b); while(b){ var t=a%b; a=b; b=t; } return a; }
function fracParse(s){ s=String(s===undefined||s===null?'':s).trim().replace(/[\u2044\u2215\u00f7]/g,'/').replace(/\s+/g,' ').replace(/\s*\/\s*/g,'/'); var m;
  if((m=s.match(/^(-?\d+)$/))) return {v:+m[1],form:'int',n:+m[1],d:1};
  if((m=s.match(/^(-?\d+)\/(\d+)$/))){ if(+m[2]===0) return null; return {v:m[1]/m[2],form:'frac',n:+m[1],d:+m[2]}; }
  if((m=s.match(/^(\d+)(?: |\+|-)(\d+)\/(\d+)$/))){ if(+m[3]===0) return null; return {v:+m[1]+m[2]/m[3],form:'mixed',w:+m[1],n:+m[2],d:+m[3]}; }
  if((m=s.match(/^-?\d*\.\d+$/))) return {v:parseFloat(s),form:'dec'};
  return null; }
function fracOK(mode,input,answer){
  if(mode==='flist'){ var A=String(input).split(/[,;]/).map(function(x){return x.trim();}).filter(Boolean), K=String(answer).split(/[,;]/).map(function(x){return x.trim();});
    if(A.length!==K.length) return false; return A.every(function(x,i){ var a=fracParse(x), k=fracParse(K[i]); return a&&k&&Math.abs(a.v-k.v)<1e-9; }); }
  var a=fracParse(input), k=fracParse(answer); if(!a||!k) return false;
  var same=Math.abs(a.v-k.v)<1e-9; if(!same) return false;
  if(mode==='fv') return true;
  if(mode==='dec') return a.form==='dec'||a.form==='int';
  if(mode==='fe') return (a.form==='frac'&&k.form==='frac'&&a.n===k.n&&a.d===k.d)||(a.form==='int'&&k.form==='int');
  if(mode==='fi') return a.form==='frac'||(a.form==='int'&&k.form==='int');
  if(mode==='fl') return a.form==='int'||(a.form==='frac'&&gcdI(a.n,a.d)===1)||(a.form==='mixed'&&a.n<a.d&&gcdI(a.n,a.d)===1);
  if(mode==='fm') return a.form==='int'||(a.form==='mixed'&&a.n>0&&a.n<a.d&&gcdI(a.n,a.d)===1);
  return false; }
function answerMatches(input,answer,accept,expr){
  if(expr==='dec'||expr==='fv'||expr==='fe'||expr==='fl'||expr==='fm'||expr==='fi'||expr==='flist'){ if(input===undefined||input===null||String(input).trim()==='') return false; return fracOK(expr,input,answer); }
  if(input===undefined||input===null||String(input).trim()==='') return false;
  if(expr==='words'){ return [answer].concat(accept||[]).some(function(a){ return wordsNorm(a)===wordsNorm(input); }); }
  if(expr==='list'){ return [answer].concat(accept||[]).some(function(a){ return listNorm(a)===listNorm(input); }); }
  if(expr==='pow'){ return [answer].concat(accept||[]).some(function(a){ return powNorm(a)===powNorm(input); }); }
  if(expr==='time'){ var tn=function(x){ var t=String(x).toLowerCase().replace(/[\s.]/g,'').replace(/[:h]/g,''); if(/^\d{3}(am|pm)?$/.test(t)) t='0'+t; return t; }; return [answer].concat(accept||[]).some(function(a){ return tn(a)===tn(input); }); }
  if(expr==='glist'){ var gn=function(x){ return String(x).toUpperCase().split(/[\s,;]+/).filter(Boolean).sort().join(','); }; return [answer].concat(accept||[]).some(function(a){ return gn(a)===gn(input); }); }
  if(expr==='coord'){ var cn=function(x){ return String(x).replace(/[\u2212\u2013\u2014]/g,'-').replace(/[\s()\[\]]/g,''); }; return [answer].concat(accept||[]).some(function(a){ return cn(a)===cn(input); }); }
  if(expr==='dlist'){ var dn=function(x){ return (String(x).match(/-?\d*\.?\d+/g)||[]).map(Number).join(','); }; return [answer].concat(accept||[]).some(function(a){ return dn(a)===dn(input); }); }
  if(expr==='set'){ var sn=function(x){ return (String(x).match(/-?\d+/g)||[]).map(Number).sort(function(a,b){return a-b;}).join(','); }; return [answer].concat(accept||[]).some(function(a){ return sn(a)===sn(input); }); }
  if(expr==='primes'){ var pn=function(x){ var t=powNorm(x).replace(/[^0-9x^]/g,''); var out=[]; t.split('x').forEach(function(tok){ if(!tok) return; var m=tok.split('^'); var b=+m[0], e=m[1]?+m[1]:1; for(var i=0;i<e;i++) out.push(b); }); return out.sort(function(a,b){return a-b;}).join(','); }; return [answer].concat(accept||[]).some(function(a){ return pn(a)===pn(input); }); }
  if(expr==='angle'){ var an=function(x){ return String(x).toUpperCase().replace(/[^A-Z]/g,''); }; var k=an(answer), v=an(input); return v===k || v===k.split('').reverse().join(''); }
  if(expr==='trans'){ var tv=function(x){ var s=String(x).toLowerCase().replace(/[−–—]/g,'-').replace(/\b(units?|squares?|and|then|steps?|to|the|a)\b/g,' ').replace(/[,;.]/g,' '); var re=/(\d+)\s*(right|left|up|down|r|l|u|d)\b/g, m, dx=0, dy=0, n=0; while((m=re.exec(s))){ var v=+m[1], d=m[2][0]; if(d==='r')dx+=v; else if(d==='l')dx-=v; else if(d==='u')dy+=v; else dy-=v; n++; } if(!n||s.replace(re,'').replace(/\s+/g,'')!=='') return null; return dx+','+dy; }; var ti=tv(input); return ti!==null && [answer].concat(accept||[]).some(function(a){ return tv(a)===ti; }); }
  if(expr==='rot'){ var rv=function(x){ var s=String(x).toLowerCase().replace(/quarter[\s-]*turn/g,'90').replace(/half[\s-]*turn/g,'180').replace(/three[\s-]*quarter[\s-]*turn/g,'270'); var m=s.match(/\b(90|180|270)\b/); if(!m) return null; var a=+m[1]; if(a===180) return '180'; var dir=/anti|counter|acw|ccw/.test(s)?-1:(/clockwise|\bcw\b/.test(s)?1:0); if(!dir) return null; return String(((a*dir)%360+360)%360); }; var ri=rv(input); return ri!==null && ri===rv(answer); }
  if(expr==='expanded'){ var f=function(x){ return String(x).replace(/\s+/g,'').replace(/,/g,''); }; return [answer].concat(accept||[]).some(function(a){ return f(a)===f(input); }); }
  if(expr===true && input!==undefined && input!==null && String(input).trim()!==''){
    if(exprEqual(input,answer)) return true;
    return (accept||[]).some(function(a){ return exprEqual(input,a); });
  }
  if(input===undefined||input===null||String(input).trim()==='') return false;
  var n1=parseNum(input), n2=parseNum(answer);
  if(n1!==null && n2!==null) return Math.abs(n1-n2)<1e-3;
  var cands=[answer].concat(accept||[]); var ni=norm(input);
  for(var i=0;i<cands.length;i++){ if(norm(cands[i])===ni) return true; }
  return false;
}
function esc(s){ return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;'); }

/* ================= DATA ================= */
var AR_OPTIONS = ["Both A and R are true, and R is the correct explanation of A","Both A and R are true, but R is NOT the correct explanation of A","A is true but R is false","A is false but R is true"];
var SECTIONS = [{"id": "s1", "label": "Ex 17A", "sub": "Describing probability", "slides": [{"kind": "blank", "p": "Describe each event using: impossible, highly unlikely, unlikely, even chance, likely, highly likely or certain.", "tag": "", "marks": "", "flat": [{"t": "a) The sun will set in the west this evening. __B1__", "a": {"B1": "certain"}}, {"t": "b) A tossed ₹5 coin lands heads. __B1__", "a": {"B1": "even chance"}, "accept": ["even chance", "50-50 chance", "50-50", "fifty-fifty", "fifty fifty", "even", "evens", "equal chance", "50/50", "50/50 chance"]}, {"t": "c) You roll a 9 on a normal die. __B1__", "a": {"B1": "impossible"}}, {"t": "d) It snows on Marina Beach, Chennai, this May. __B1__", "a": {"B1": "highly unlikely"}}, {"t": "e) You roll a number less than 5 on a normal die. __B1__", "a": {"B1": "likely"}}, {"t": "f) A baby born today is a girl. __B1__", "a": {"B1": "even chance"}, "accept": ["even chance", "50-50 chance", "50-50", "fifty-fifty", "fifty fifty", "even", "evens", "equal chance", "50/50", "50/50 chance"]}], "sol": "Place each event on the probability scale.\na) this always happens: certain\nb) heads and tails are equally likely: even chance\nc) a die only shows 1 to 6: impossible\nd) almost never happens in Chennai's hot May: highly unlikely\ne) 4 of the 6 numbers work, more than half: likely\nf) boys and girls are born about equally often: even chance", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 340 112\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line class=\"ln\" x1=\"24.0\" y1=\"52.0\" x2=\"316.0\" y2=\"52.0\"/><line class=\"ln\" x1=\"24.0\" y1=\"45.0\" x2=\"24.0\" y2=\"59.0\"/><text class=\"lb\" x=\"24.0\" y=\"71.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">0</text><line class=\"ln\" x1=\"170.0\" y1=\"45.0\" x2=\"170.0\" y2=\"59.0\"/><text class=\"lb\" x=\"170.0\" y=\"71.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">½</text><line class=\"ln\" x1=\"316.0\" y1=\"45.0\" x2=\"316.0\" y2=\"59.0\"/><text class=\"lb\" x=\"316.0\" y=\"71.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><rect x=\"29.84\" y=\"49\" width=\"29.2\" height=\"6\" style=\"fill:var(--gold-soft)\"/><rect x=\"280.96\" y=\"49\" width=\"29.19999999999999\" height=\"6\" style=\"fill:var(--gold-soft)\"/><text class=\"al\" x=\"24.0\" y=\"34.0\" text-anchor=\"start\" dominant-baseline=\"middle\">impossible</text><text class=\"al\" x=\"170.0\" y=\"34.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">even chance</text><text class=\"al\" x=\"316.0\" y=\"34.0\" text-anchor=\"end\" dominant-baseline=\"middle\">certain</text><text class=\"lb\" x=\"105.8\" y=\"71.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">unlikely</text><text class=\"lb\" x=\"234.2\" y=\"71.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">likely</text><text class=\"lb\" x=\"44.4\" y=\"92.0\" text-anchor=\"start\" dominant-baseline=\"middle\">highly unlikely</text><text class=\"lb\" x=\"295.6\" y=\"92.0\" text-anchor=\"end\" dominant-baseline=\"middle\">highly likely</text><line class=\"ln\" x1=\"44.4\" y1=\"82.0\" x2=\"44.4\" y2=\"60.0\"/><line class=\"ln\" x1=\"295.6\" y1=\"82.0\" x2=\"295.6\" y2=\"60.0\"/></svg>"}, {"kind": "blank", "p": "This spinner is spun once. Copy and complete, using a probability word:", "tag": "", "marks": "", "flat": [{"t": "a) Landing on yellow is __B1__.", "a": {"B1": "likely"}}, {"t": "b) Landing on red is __B1__.", "a": {"B1": "unlikely"}}, {"t": "c) Landing on purple is __B1__.", "a": {"B1": "impossible"}}, {"t": "d) Landing on yellow or red is __B1__.", "a": {"B1": "certain"}}], "sol": "3 of the 4 equal parts are yellow and 1 is red.\na) 3 out of 4 is more than half: likely\nb) 1 out of 4 is less than half: unlikely\nc) there is no purple part: impossible\nd) every part is yellow or red: certain", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 300 150\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><path d=\"M150.0,79.0 L150.0,17.0 A62,62 0 0 1 212.0,79.0 Z\" style=\"fill:#f0cf55;stroke:var(--ink);stroke-width:1.3\"/><text x=\"178.9\" y=\"50.1\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">Y</text><path d=\"M150.0,79.0 L212.0,79.0 A62,62 0 0 1 150.0,141.0 Z\" style=\"fill:#f0cf55;stroke:var(--ink);stroke-width:1.3\"/><text x=\"178.9\" y=\"107.9\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">Y</text><path d=\"M150.0,79.0 L150.0,141.0 A62,62 0 0 1 88.0,79.0 Z\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.3\"/><text x=\"121.1\" y=\"107.9\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">R</text><path d=\"M150.0,79.0 L88.0,79.0 A62,62 0 0 1 150.0,17.0 Z\" style=\"fill:#f0cf55;stroke:var(--ink);stroke-width:1.3\"/><text x=\"121.1\" y=\"50.1\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">Y</text><circle cx=\"150.0\" cy=\"79.0\" r=\"4\" style=\"fill:var(--ink)\"/><path d=\"M145.0,5.0 L155.0,5.0 L150.0,20.0 Z\" style=\"fill:var(--danger)\"/></svg>"}, {"kind": "blank", "p": "One marble is taken without looking from each bag. Describe the chance of taking a red marble (R).", "tag": "", "marks": "", "flat": [{"t": "a) Bag 1: __B1__", "a": {"B1": "even chance"}, "accept": ["even chance", "50-50 chance", "50-50", "fifty-fifty", "fifty fifty", "even", "evens", "equal chance", "50/50", "50/50 chance"]}, {"t": "b) Bag 2: __B1__", "a": {"B1": "impossible"}}, {"t": "c) Bag 3: __B1__", "a": {"B1": "highly likely"}, "accept": ["likely"]}, {"t": "d) Bag 4: __B1__", "a": {"B1": "unlikely"}, "accept": ["highly unlikely"]}], "sol": "Compare the red marbles with the total.\na) 4 red of 8: exactly half, even chance\nb) no red marbles: impossible\nc) 9 red of 10: highly likely\nd) 2 red of 8: less than half, unlikely", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 320 164\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><rect x=\"6\" y=\"4\" width=\"148\" height=\"74\" rx=\"10\" style=\"fill:none;stroke:var(--rule);stroke-width:1.2\"/><text class=\"lb\" x=\"80.0\" y=\"17.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Bag 1</text><circle cx=\"28.0\" cy=\"38\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"28.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"54.0\" cy=\"38\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"54.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"80.0\" cy=\"38\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"80.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"106.0\" cy=\"38\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"106.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"132.0\" cy=\"38\" r=\"11\" style=\"fill:#5b8fe0;stroke:var(--ink);stroke-width:1.1\"/><text x=\"132.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">B</text><circle cx=\"28.0\" cy=\"64\" r=\"11\" style=\"fill:#5b8fe0;stroke:var(--ink);stroke-width:1.1\"/><text x=\"28.0\" y=\"64.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">B</text><circle cx=\"54.0\" cy=\"64\" r=\"11\" style=\"fill:#5b8fe0;stroke:var(--ink);stroke-width:1.1\"/><text x=\"54.0\" y=\"64.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">B</text><circle cx=\"80.0\" cy=\"64\" r=\"11\" style=\"fill:#5b8fe0;stroke:var(--ink);stroke-width:1.1\"/><text x=\"80.0\" y=\"64.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">B</text><rect x=\"166\" y=\"4\" width=\"148\" height=\"74\" rx=\"10\" style=\"fill:none;stroke:var(--rule);stroke-width:1.2\"/><text class=\"lb\" x=\"240.0\" y=\"17.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Bag 2</text><circle cx=\"188.0\" cy=\"38\" r=\"11\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"188.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text><circle cx=\"214.0\" cy=\"38\" r=\"11\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"214.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text><circle cx=\"240.0\" cy=\"38\" r=\"11\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"240.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text><circle cx=\"266.0\" cy=\"38\" r=\"11\" style=\"fill:#5b8fe0;stroke:var(--ink);stroke-width:1.1\"/><text x=\"266.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">B</text><circle cx=\"292.0\" cy=\"38\" r=\"11\" style=\"fill:#5b8fe0;stroke:var(--ink);stroke-width:1.1\"/><text x=\"292.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">B</text><circle cx=\"188.0\" cy=\"64\" r=\"11\" style=\"fill:#5b8fe0;stroke:var(--ink);stroke-width:1.1\"/><text x=\"188.0\" y=\"64.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">B</text><rect x=\"6\" y=\"86\" width=\"148\" height=\"74\" rx=\"10\" style=\"fill:none;stroke:var(--rule);stroke-width:1.2\"/><text class=\"lb\" x=\"80.0\" y=\"99.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Bag 3</text><circle cx=\"28.0\" cy=\"120\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"28.0\" y=\"120.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"54.0\" cy=\"120\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"54.0\" y=\"120.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"80.0\" cy=\"120\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"80.0\" y=\"120.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"106.0\" cy=\"120\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"106.0\" y=\"120.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"132.0\" cy=\"120\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"132.0\" y=\"120.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"28.0\" cy=\"146\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"28.0\" y=\"146.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"54.0\" cy=\"146\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"54.0\" y=\"146.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"80.0\" cy=\"146\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"80.0\" y=\"146.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"106.0\" cy=\"146\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"106.0\" y=\"146.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"132.0\" cy=\"146\" r=\"11\" style=\"fill:#f0cf55;stroke:var(--ink);stroke-width:1.1\"/><text x=\"132.0\" y=\"146.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">Y</text><rect x=\"166\" y=\"86\" width=\"148\" height=\"74\" rx=\"10\" style=\"fill:none;stroke:var(--rule);stroke-width:1.2\"/><text class=\"lb\" x=\"240.0\" y=\"99.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Bag 4</text><circle cx=\"188.0\" cy=\"120\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"188.0\" y=\"120.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"214.0\" cy=\"120\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"214.0\" y=\"120.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"240.0\" cy=\"120\" r=\"11\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"240.0\" y=\"120.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text><circle cx=\"266.0\" cy=\"120\" r=\"11\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"266.0\" y=\"120.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text><circle cx=\"292.0\" cy=\"120\" r=\"11\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"292.0\" y=\"120.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text><circle cx=\"188.0\" cy=\"146\" r=\"11\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"188.0\" y=\"146.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text><circle cx=\"214.0\" cy=\"146\" r=\"11\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"214.0\" y=\"146.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text><circle cx=\"240.0\" cy=\"146\" r=\"11\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"240.0\" y=\"146.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text></svg>"}, {"kind": "mcq", "text": "A marble is taken without looking. From which bag is a red marble more likely?", "opts": ["Bag X: 3 red and 5 green", "Bag Y: 3 red and 2 green", "Both are equally likely"], "correct": 1, "tag": "", "sol": "Both bags have 3 red, but Bag Y has fewer other marbles. 3 of 5 is more than half; 3 of 8 is less than half. Bag Y.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 320 82\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><rect x=\"6\" y=\"4\" width=\"148\" height=\"74\" rx=\"10\" style=\"fill:none;stroke:var(--rule);stroke-width:1.2\"/><text class=\"lb\" x=\"80.0\" y=\"17.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Bag X</text><circle cx=\"28.0\" cy=\"38\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"28.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"54.0\" cy=\"38\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"54.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"80.0\" cy=\"38\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"80.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"106.0\" cy=\"38\" r=\"11\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"106.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text><circle cx=\"132.0\" cy=\"38\" r=\"11\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"132.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text><circle cx=\"28.0\" cy=\"64\" r=\"11\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"28.0\" y=\"64.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text><circle cx=\"54.0\" cy=\"64\" r=\"11\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"54.0\" y=\"64.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text><circle cx=\"80.0\" cy=\"64\" r=\"11\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"80.0\" y=\"64.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text><rect x=\"166\" y=\"4\" width=\"148\" height=\"74\" rx=\"10\" style=\"fill:none;stroke:var(--rule);stroke-width:1.2\"/><text class=\"lb\" x=\"240.0\" y=\"17.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Bag Y</text><circle cx=\"188.0\" cy=\"38\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"188.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"214.0\" cy=\"38\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"214.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"240.0\" cy=\"38\" r=\"11\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"240.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"266.0\" cy=\"38\" r=\"11\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"266.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text><circle cx=\"292.0\" cy=\"38\" r=\"11\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"292.0\" y=\"38.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text></svg>"}, {"kind": "mcq", "text": "Which spinner is more likely to land on blue?", "opts": ["Spinner A", "Spinner B", "Both are equally likely"], "correct": 0, "tag": "", "sol": "Spinner A: 4 of 6 parts are blue (more than half). Spinner B: 2 of 6 parts are blue (less than half). Spinner A.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 340 168\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><g><path d=\"M85.0,79.0 L85.0,17.0 A62,62 0 0 1 138.7,48.0 Z\" style=\"fill:#5b8fe0;stroke:var(--ink);stroke-width:1.3\"/><text x=\"105.5\" y=\"43.6\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">B</text><path d=\"M85.0,79.0 L138.7,48.0 A62,62 0 0 1 138.7,110.0 Z\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.3\"/><text x=\"125.9\" y=\"79.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">R</text><path d=\"M85.0,79.0 L138.7,110.0 A62,62 0 0 1 85.0,141.0 Z\" style=\"fill:#5b8fe0;stroke:var(--ink);stroke-width:1.3\"/><text x=\"105.5\" y=\"114.4\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">B</text><path d=\"M85.0,79.0 L85.0,141.0 A62,62 0 0 1 31.3,110.0 Z\" style=\"fill:#5b8fe0;stroke:var(--ink);stroke-width:1.3\"/><text x=\"64.5\" y=\"114.4\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">B</text><path d=\"M85.0,79.0 L31.3,110.0 A62,62 0 0 1 31.3,48.0 Z\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.3\"/><text x=\"44.1\" y=\"79.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">G</text><path d=\"M85.0,79.0 L31.3,48.0 A62,62 0 0 1 85.0,17.0 Z\" style=\"fill:#5b8fe0;stroke:var(--ink);stroke-width:1.3\"/><text x=\"64.5\" y=\"43.6\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">B</text><circle cx=\"85.0\" cy=\"79.0\" r=\"4\" style=\"fill:var(--ink)\"/><path d=\"M80.0,5.0 L90.0,5.0 L85.0,20.0 Z\" style=\"fill:var(--danger)\"/></g><g transform=\"translate(170,0)\"><path d=\"M85.0,79.0 L85.0,17.0 A62,62 0 0 1 138.7,48.0 Z\" style=\"fill:#5b8fe0;stroke:var(--ink);stroke-width:1.3\"/><text x=\"105.5\" y=\"43.6\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">B</text><path d=\"M85.0,79.0 L138.7,48.0 A62,62 0 0 1 138.7,110.0 Z\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.3\"/><text x=\"125.9\" y=\"79.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">R</text><path d=\"M85.0,79.0 L138.7,110.0 A62,62 0 0 1 85.0,141.0 Z\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.3\"/><text x=\"105.5\" y=\"114.4\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">R</text><path d=\"M85.0,79.0 L85.0,141.0 A62,62 0 0 1 31.3,110.0 Z\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.3\"/><text x=\"64.5\" y=\"114.4\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">G</text><path d=\"M85.0,79.0 L31.3,110.0 A62,62 0 0 1 31.3,48.0 Z\" style=\"fill:#5b8fe0;stroke:var(--ink);stroke-width:1.3\"/><text x=\"44.1\" y=\"79.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">B</text><path d=\"M85.0,79.0 L31.3,48.0 A62,62 0 0 1 85.0,17.0 Z\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.3\"/><text x=\"64.5\" y=\"43.6\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">R</text><circle cx=\"85.0\" cy=\"79.0\" r=\"4\" style=\"fill:var(--ink)\"/><path d=\"M80.0,5.0 L90.0,5.0 L85.0,20.0 Z\" style=\"fill:var(--danger)\"/></g><text class=\"lb\" x=\"85.0\" y=\"160.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Spinner A</text><text class=\"lb\" x=\"255.0\" y=\"160.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Spinner B</text></svg>"}, {"kind": "blank", "p": "Pooja puts 10 cards in a box. Some show a star ★ and the rest are blank. How many ★ cards should she use so that taking a ★ card is:", "tag": "", "marks": "", "flat": [{"t": "a) impossible → __B1__ ★ cards", "a": {"B1": "0"}}, {"t": "b) certain → __B1__ ★ cards", "a": {"B1": "10"}}, {"t": "c) an even chance → __B1__ ★ cards", "a": {"B1": "5"}}], "sol": "a) no star cards at all: 0\nb) every card must have a star: 10\nc) half the cards: 10 ÷ 2 = 5"}, {"kind": "blank", "p": "A normal six-sided die is rolled. Describe the chance of rolling:", "tag": "", "marks": "", "flat": [{"t": "a) a 6 → __B1__", "a": {"B1": "unlikely"}, "accept": ["highly unlikely"]}, {"t": "b) an odd number → __B1__", "a": {"B1": "even chance"}, "accept": ["even chance", "50-50 chance", "50-50", "fifty-fifty", "fifty fifty", "even", "evens", "equal chance", "50/50", "50/50 chance"]}, {"t": "c) a number greater than 1 → __B1__", "a": {"B1": "highly likely"}, "accept": ["likely"]}, {"t": "d) a 0 → __B1__", "a": {"B1": "impossible"}}, {"t": "e) a whole number from 1 to 6 → __B1__", "a": {"B1": "certain"}}], "sol": "The die can show 1, 2, 3, 4, 5 or 6.\na) 1 out of 6: unlikely\nb) 1, 3, 5 is 3 out of 6: even chance\nc) 2 to 6 is 5 out of 6: highly likely\nd) there is no 0: impossible\ne) every roll is 1 to 6: certain"}]}, {"id": "s2", "label": "Ex 17B", "sub": "Using numbers to describe probability", "slides": [{"kind": "blank", "p": "Match each probability with a word: impossible, highly unlikely, unlikely, even chance, likely, highly likely, certain.", "tag": "", "marks": "", "flat": [{"t": "a) 1 → __B1__", "a": {"B1": "certain"}}, {"t": "b) 0 → __B1__", "a": {"B1": "impossible"}}, {"t": "c) {1/2} → __B1__", "a": {"B1": "even chance"}, "accept": ["even chance", "50-50 chance", "50-50", "fifty-fifty", "fifty fifty", "even", "evens", "equal chance", "50/50", "50/50 chance"]}, {"t": "d) 0.96 → __B1__", "a": {"B1": "highly likely"}}, {"t": "e) 0.3 → __B1__", "a": {"B1": "unlikely"}}, {"t": "f) 0.7 → __B1__", "a": {"B1": "likely"}}, {"t": "g) 0.03 → __B1__", "a": {"B1": "highly unlikely"}}], "sol": "Probabilities go from 0 (impossible) to 1 (certain), with {1/2} in the middle.\na) certain\nb) impossible\nc) even chance\nd) very close to 1: highly likely\ne) between 0 and {1/2}: unlikely\nf) between {1/2} and 1: likely\ng) very close to 0: highly unlikely", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 340 112\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line class=\"ln\" x1=\"24.0\" y1=\"52.0\" x2=\"316.0\" y2=\"52.0\"/><line class=\"ln\" x1=\"24.0\" y1=\"45.0\" x2=\"24.0\" y2=\"59.0\"/><text class=\"lb\" x=\"24.0\" y=\"71.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">0</text><line class=\"ln\" x1=\"170.0\" y1=\"45.0\" x2=\"170.0\" y2=\"59.0\"/><text class=\"lb\" x=\"170.0\" y=\"71.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">½</text><line class=\"ln\" x1=\"316.0\" y1=\"45.0\" x2=\"316.0\" y2=\"59.0\"/><text class=\"lb\" x=\"316.0\" y=\"71.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><rect x=\"29.84\" y=\"49\" width=\"29.2\" height=\"6\" style=\"fill:var(--gold-soft)\"/><rect x=\"280.96\" y=\"49\" width=\"29.19999999999999\" height=\"6\" style=\"fill:var(--gold-soft)\"/><text class=\"al\" x=\"24.0\" y=\"34.0\" text-anchor=\"start\" dominant-baseline=\"middle\">impossible</text><text class=\"al\" x=\"170.0\" y=\"34.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">even chance</text><text class=\"al\" x=\"316.0\" y=\"34.0\" text-anchor=\"end\" dominant-baseline=\"middle\">certain</text><text class=\"lb\" x=\"105.8\" y=\"71.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">unlikely</text><text class=\"lb\" x=\"234.2\" y=\"71.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">likely</text><text class=\"lb\" x=\"44.4\" y=\"92.0\" text-anchor=\"start\" dominant-baseline=\"middle\">highly unlikely</text><text class=\"lb\" x=\"295.6\" y=\"92.0\" text-anchor=\"end\" dominant-baseline=\"middle\">highly likely</text><line class=\"ln\" x1=\"44.4\" y1=\"82.0\" x2=\"44.4\" y2=\"60.0\"/><line class=\"ln\" x1=\"295.6\" y1=\"82.0\" x2=\"295.6\" y2=\"60.0\"/></svg>"}, {"kind": "blank", "p": "Match each event with its probability. Choose from 0, {1/4}, {1/2}, 1.", "tag": "", "marks": "", "flat": [{"t": "a) A tossed coin lands tails. __B1__", "a": {"B1": "1/2"}, "expr": "fv"}, {"t": "b) Tomorrow has 24 hours. __B1__", "a": {"B1": "1"}, "expr": "fv"}, {"t": "c) A spinner with 4 equal parts, one of them red, lands on red. __B1__", "a": {"B1": "1/4"}, "expr": "fv"}, {"t": "d) A normal die shows 8. __B1__", "a": {"B1": "0"}, "expr": "fv"}], "sol": "a) 1 of 2 outcomes: {1/2}\nb) always true: 1\nc) 1 of 4 equal parts: {1/4}\nd) impossible: 0"}, {"kind": "blank", "p": "Write each probability as a percentage:", "tag": "", "marks": "", "flat": [{"t": "a) {1/2} = __B1__ %", "a": {"B1": "50"}}, {"t": "b) {3/4} = __B1__ %", "a": {"B1": "75"}}, {"t": "c) 0.6 = __B1__ %", "a": {"B1": "60"}}, {"t": "d) {1/5} = __B1__ %", "a": {"B1": "20"}}, {"t": "e) 0.08 = __B1__ %", "a": {"B1": "8"}}, {"t": "f) 1 = __B1__ %", "a": {"B1": "100"}}], "sol": "Multiply by 100 %.\na) 50 %\nb) 75 %\nc) 0.6 × 100 = 60 %\nd) {1/5} = {20/100} = 20 %\ne) 8 %\nf) certain = 100 %"}, {"kind": "blank", "p": "The weather forecast gives the chance of rain tomorrow in six cities.", "tag": "", "marks": "", "flat": [{"t": "a) Which city is most likely to get rain? __B1__", "a": {"B1": "Guwahati"}}, {"t": "b) Which city will not get rain? __B1__", "a": {"B1": "Jaipur"}}, {"t": "c) Which city has an even chance of rain? __B1__", "a": {"B1": "Kolkata"}}, {"t": "d) Describe the chance of rain in Shimla. __B1__", "a": {"B1": "likely"}}, {"t": "e) Apart from Jaipur, which city is least likely to get rain? __B1__", "a": {"B1": "Delhi"}}, {"t": "f) Write the chance of rain in Mumbai as a decimal. __B1__", "a": {"B1": "0.85"}, "expr": "dec"}], "sol": "a) highest %: Guwahati 95 %\nb) 0 % is impossible: Jaipur\nc) 50 %: Kolkata\nd) 60 % is more than half: likely\ne) next lowest: Delhi 10 %\nf) 85 % = 0.85", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 258 176\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><rect x=\"4\" y=\"4\" width=\"110\" height=\"24\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"59.0\" y=\"16.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">City</text><rect x=\"114\" y=\"4\" width=\"140\" height=\"24\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"16.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Chance of rain</text><rect x=\"4\" y=\"28\" width=\"110\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"59.0\" y=\"40.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Delhi</text><rect x=\"114\" y=\"28\" width=\"140\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"40.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">10 %</text><rect x=\"4\" y=\"52\" width=\"110\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"59.0\" y=\"64.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Mumbai</text><rect x=\"114\" y=\"52\" width=\"140\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"64.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">85 %</text><rect x=\"4\" y=\"76\" width=\"110\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"59.0\" y=\"88.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Kolkata</text><rect x=\"114\" y=\"76\" width=\"140\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"88.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">50 %</text><rect x=\"4\" y=\"100\" width=\"110\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"59.0\" y=\"112.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Shimla</text><rect x=\"114\" y=\"100\" width=\"140\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"112.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">60 %</text><rect x=\"4\" y=\"124\" width=\"110\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"59.0\" y=\"136.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Jaipur</text><rect x=\"114\" y=\"124\" width=\"140\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"136.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">0 %</text><rect x=\"4\" y=\"148\" width=\"110\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"59.0\" y=\"160.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Guwahati</text><rect x=\"114\" y=\"148\" width=\"140\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"160.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">95 %</text></svg>"}, {"kind": "blank", "p": "In penalty practice, Isha scores {7/10} of her shots, Kabir scores 0.75 of his and Leela scores 68 %.", "tag": "", "marks": "", "flat": [{"t": "a) Isha's rate as a percentage: __B1__ %", "a": {"B1": "70"}}, {"t": "b) Kabir's rate as a percentage: __B1__ %", "a": {"B1": "75"}}, {"t": "c) Who is most likely to score the next penalty? __B1__", "a": {"B1": "Kabir"}}, {"t": "d) Who is least likely? __B1__", "a": {"B1": "Leela"}}], "sol": "Change all three to percentages.\na) {7/10} = 70 %\nb) 0.75 = 75 %\nc) 75 % is the largest: Kabir\nd) 68 % is the smallest: Leela"}, {"kind": "blank", "p": "A drinks machine gives a random drink. P(tea) = {3/8}, P(coffee) = {1/8}, P(lassi) = {4/8}.", "tag": "", "marks": "", "flat": [{"t": "a) Which drink is most likely? __B1__", "a": {"B1": "lassi"}}, {"t": "b) Which drink has an even chance? __B1__", "a": {"B1": "lassi"}}, {"t": "c) Which drink is least likely? __B1__", "a": {"B1": "coffee"}}, {"t": "d) P(tea) + P(coffee) + P(lassi) = __B1__", "a": {"B1": "1"}, "expr": "fv"}, {"t": "e) P(not coffee) = __B1__", "a": {"B1": "7/8"}, "expr": "fv"}], "sol": "a) {4/8} is the biggest: lassi\nb) {4/8} = {1/2}: lassi\nc) {1/8} is smallest: coffee\nd) {3/8} + {1/8} + {4/8} = {8/8} = 1 (one drink always comes out)\ne) 1 − {1/8} = {7/8}"}, {"kind": "mcq", "text": "Which is more likely: an event with probability 0.4, or one with probability {3/5}?", "opts": ["0.4", "{3/5}", "They are equally likely"], "correct": 1, "tag": "", "sol": "{3/5} = 0.6, and 0.6 > 0.4, so the event with probability {3/5} is more likely."}]}, {"id": "s3", "label": "Ex 17C", "sub": "Outcomes", "slides": [{"kind": "blank", "p": "The spinner is spun once.", "tag": "", "marks": "", "flat": [{"t": "a) List the possible outcomes (separate with commas): __B1__", "a": {"B1": "1, 2, 3, 4, 5"}, "expr": "set"}, {"t": "b) number of possible outcomes: __B1__", "a": {"B1": "5"}}, {"t": "c) outcomes that are odd: __B1__", "a": {"B1": "1, 3, 5"}, "expr": "set"}], "sol": "a) the numbers on the spinner: 1, 2, 3, 4, 5\nb) 5 outcomes\nc) 1, 3 and 5", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 300 150\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><path d=\"M150.0,79.0 L150.0,17.0 A62,62 0 0 1 209.0,59.8 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"174.1\" y=\"45.9\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">1</text><path d=\"M150.0,79.0 L209.0,59.8 A62,62 0 0 1 186.4,129.2 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"188.9\" y=\"91.6\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">2</text><path d=\"M150.0,79.0 L186.4,129.2 A62,62 0 0 1 113.6,129.2 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"150.0\" y=\"119.9\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">3</text><path d=\"M150.0,79.0 L113.6,129.2 A62,62 0 0 1 91.0,59.8 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"111.1\" y=\"91.6\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">4</text><path d=\"M150.0,79.0 L91.0,59.8 A62,62 0 0 1 150.0,17.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"125.9\" y=\"45.9\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">5</text><circle cx=\"150.0\" cy=\"79.0\" r=\"4\" style=\"fill:var(--ink)\"/><path d=\"M145.0,5.0 L155.0,5.0 L150.0,20.0 Z\" style=\"fill:var(--danger)\"/></svg>"}, {"kind": "blank", "p": "A normal six-sided die is rolled.", "tag": "", "marks": "", "flat": [{"t": "a) number of possible outcomes: __B1__", "a": {"B1": "6"}}, {"t": "b) the outcomes that are even: __B1__", "a": {"B1": "2, 4, 6"}, "expr": "set"}, {"t": "c) the outcomes greater than 4: __B1__", "a": {"B1": "5, 6"}, "expr": "set"}, {"t": "d) the outcomes that are multiples of 3: __B1__", "a": {"B1": "3, 6"}, "expr": "set"}], "sol": "Outcomes: 1, 2, 3, 4, 5, 6\na) 6\nb) 2, 4, 6\nc) 5, 6\nd) 3, 6"}, {"kind": "blank", "p": "This spinner shows the letters of the word PLANET.", "tag": "", "marks": "", "flat": [{"t": "a) number of possible outcomes: __B1__", "a": {"B1": "6"}}, {"t": "b) the vowels (letters separated by spaces): __B1__", "a": {"B1": "A E"}, "expr": "glist"}, {"t": "c) number of outcomes that are consonants: __B1__", "a": {"B1": "4"}}], "sol": "a) P, L, A, N, E, T: 6 outcomes\nb) A and E\nc) P, L, N, T: 4", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 300 150\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><path d=\"M150.0,79.0 L150.0,17.0 A62,62 0 0 1 203.7,48.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"170.5\" y=\"43.6\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">P</text><path d=\"M150.0,79.0 L203.7,48.0 A62,62 0 0 1 203.7,110.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"190.9\" y=\"79.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">L</text><path d=\"M150.0,79.0 L203.7,110.0 A62,62 0 0 1 150.0,141.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"170.5\" y=\"114.4\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">A</text><path d=\"M150.0,79.0 L150.0,141.0 A62,62 0 0 1 96.3,110.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"129.5\" y=\"114.4\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">N</text><path d=\"M150.0,79.0 L96.3,110.0 A62,62 0 0 1 96.3,48.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"109.1\" y=\"79.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">E</text><path d=\"M150.0,79.0 L96.3,48.0 A62,62 0 0 1 150.0,17.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"129.5\" y=\"43.6\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">T</text><circle cx=\"150.0\" cy=\"79.0\" r=\"4\" style=\"fill:var(--ink)\"/><path d=\"M145.0,5.0 L155.0,5.0 L150.0,20.0 Z\" style=\"fill:var(--danger)\"/></svg>"}, {"kind": "blank", "p": "Rohan picks a tie without looking from a drawer holding one red, one blue, one green, one striped and one spotted tie.", "tag": "", "marks": "", "flat": [{"t": "a) number of possible outcomes: __B1__", "a": {"B1": "5"}}, {"t": "b) how many of the outcomes are plain-coloured ties? __B1__", "a": {"B1": "3"}}], "sol": "a) 5 different ties\nb) red, blue and green: 3"}, {"kind": "blank", "p": "A date in September 2026 is chosen at random. (1 September 2026 is a Tuesday.)", "tag": "", "marks": "", "flat": [{"t": "a) number of possible outcomes: __B1__", "a": {"B1": "30"}}, {"t": "b) how many of the dates are Sundays? __B1__", "a": {"B1": "4"}}, {"t": "c) the Sunday dates (separate with commas): __B1__", "a": {"B1": "6, 13, 20, 27"}, "expr": "set"}], "sol": "a) September has 30 days\nb) the first Sunday is 6 September, then every 7 days\nc) 6, 13, 20, 27"}, {"kind": "blank", "p": "A pet shop has 3 puppies, 4 kittens and 2 rabbits. One animal is chosen at random to be photographed.", "tag": "", "marks": "", "flat": [{"t": "a) number of possible outcomes (animals): __B1__", "a": {"B1": "9"}}, {"t": "b) how many outcomes are kittens? __B1__", "a": {"B1": "4"}}, {"t": "c) how many outcomes are not puppies? __B1__", "a": {"B1": "6"}}], "sol": "a) 3 + 4 + 2 = 9\nb) 4\nc) 4 + 2 = 6"}, {"kind": "blank", "p": "One country is chosen at random from: India, Nepal, Bhutan, Sri Lanka, Bangladesh, Maldives, Pakistan.", "tag": "", "marks": "", "flat": [{"t": "a) number of possible outcomes: __B1__", "a": {"B1": "7"}}, {"t": "b) how many names begin with B? __B1__", "a": {"B1": "2"}}, {"t": "c) how many names end in the letter a? __B1__", "a": {"B1": "2"}}], "sol": "a) 7 countries\nb) Bhutan, Bangladesh\nc) India, Sri Lanka"}]}, {"id": "s4", "label": "Ex 17D", "sub": "Calculating probabilities", "slides": [{"kind": "blank", "p": "Probability = (number of favourable outcomes) ÷ (total number of outcomes). A ₹10 coin is tossed. Give each answer as a fraction in simplest form.", "tag": "", "marks": "", "flat": [{"t": "a) P(heads) = __B1__", "a": {"B1": "1/2"}, "expr": "fl"}, {"t": "b) P(tails) = __B1__", "a": {"B1": "1/2"}, "expr": "fl"}], "sol": "There are 2 outcomes: heads, tails.\na) 1 out of 2: {1/2}\nb) 1 out of 2: {1/2}"}, {"kind": "blank", "p": "A normal die is rolled once. Find (simplest form):", "tag": "", "marks": "", "flat": [{"t": "a) P(a 4) = __B1__", "a": {"B1": "1/6"}, "expr": "fl"}, {"t": "b) P(an even number) = __B1__", "a": {"B1": "1/2"}, "expr": "fl"}, {"t": "c) P(a number less than 3) = __B1__", "a": {"B1": "1/3"}, "expr": "fl"}, {"t": "d) P(a number greater than 6) = __B1__", "a": {"B1": "0"}, "expr": "fl"}, {"t": "e) P(a number from 1 to 6) = __B1__", "a": {"B1": "1"}, "expr": "fl"}], "sol": "There are 6 equally likely outcomes.\na) 1 out of 6: {1/6}\nb) 3 out of 6: {3/6} = {1/2}\nc) 2 out of 6: {2/6} = {1/3}\nd) no favourable outcomes: 0\ne) every outcome is favourable: 6 out of 6 = 1"}, {"kind": "blank", "p": "Ten cards numbered 1 to 10 are shuffled and one is taken. Find (simplest form):", "tag": "", "marks": "", "flat": [{"t": "a) P(the 7) = __B1__", "a": {"B1": "1/10"}, "expr": "fl"}, {"t": "b) P(an odd number) = __B1__", "a": {"B1": "1/2"}, "expr": "fl"}, {"t": "c) P(a multiple of 3) = __B1__", "a": {"B1": "3/10"}, "expr": "fl"}, {"t": "d) P(a number greater than 8) = __B1__", "a": {"B1": "1/5"}, "expr": "fl"}], "sol": "10 outcomes.\nodd: 1, 3, 5, 7, 9 · multiples of 3: 3, 6, 9 · greater than 8: 9, 10\na) 1 out of 10: {1/10}\nb) 5 out of 10: {5/10} = {1/2}\nc) 3 out of 10: {3/10}\nd) 2 out of 10: {2/10} = {1/5}"}, {"kind": "blank", "p": "A school raffle sells tickets numbered 1 to 50 and every ticket is sold. Meera has 4 tickets. One ticket is drawn. Find (simplest form):", "tag": "", "marks": "", "flat": [{"t": "a) P(Meera wins) = __B1__", "a": {"B1": "2/25"}, "expr": "fl"}, {"t": "b) P(the winning number ends in 7) = __B1__", "a": {"B1": "1/10"}, "expr": "fl"}, {"t": "c) P(the winning number is more than 40) = __B1__", "a": {"B1": "1/5"}, "expr": "fl"}], "sol": "50 outcomes.\nending in 7: 7, 17, 27, 37, 47 · more than 40: 41 to 50\na) 4 out of 50: {4/50} = {2/25}\nb) 5 out of 50: {5/50} = {1/10}\nc) 10 out of 50: {10/50} = {1/5}"}, {"kind": "blank", "p": "On a washing line are 3 blue, 2 white and 5 green shirts. The wind blows one shirt off. Find (simplest form):", "tag": "", "marks": "", "flat": [{"t": "a) P(blue) = __B1__", "a": {"B1": "3/10"}, "expr": "fl"}, {"t": "b) P(white) = __B1__", "a": {"B1": "1/5"}, "expr": "fl"}, {"t": "c) P(not green) = __B1__", "a": {"B1": "1/2"}, "expr": "fl"}], "sol": "3 + 2 + 5 = 10 shirts.\nnot green: 3 + 2 = 5\na) 3 out of 10: {3/10}\nb) 2 out of 10: {2/10} = {1/5}\nc) 5 out of 10: {5/10} = {1/2}"}, {"kind": "blank", "p": "A box has 6 dark, 8 milk and 4 white chocolates. Ananya takes one without looking. Find (simplest form):", "tag": "", "marks": "", "flat": [{"t": "a) P(milk) = __B1__", "a": {"B1": "4/9"}, "expr": "fl"}, {"t": "b) P(dark) = __B1__", "a": {"B1": "1/3"}, "expr": "fl"}, {"t": "c) P(not white) = __B1__", "a": {"B1": "7/9"}, "expr": "fl"}], "sol": "6 + 8 + 4 = 18 chocolates.\nnot white: 6 + 8 = 14\na) 8 out of 18: {8/18} = {4/9}\nb) 6 out of 18: {6/18} = {1/3}\nc) 14 out of 18: {14/18} = {7/9}"}, {"kind": "blank", "p": "A cricket team of 11 has 5 batters, 4 bowlers, 1 wicketkeeper and 1 all-rounder. The captain is chosen at random. Find (simplest form):", "tag": "", "marks": "", "flat": [{"t": "a) P(a bowler) = __B1__", "a": {"B1": "4/11"}, "expr": "fl"}, {"t": "b) P(the wicketkeeper) = __B1__", "a": {"B1": "1/11"}, "expr": "fl"}, {"t": "c) P(not a batter) = __B1__", "a": {"B1": "6/11"}, "expr": "fl"}], "sol": "11 players.\nnot a batter: 11 − 5 = 6\na) 4 out of 11: {4/11}\nb) 1 out of 11: {1/11}\nc) 6 out of 11: {6/11}"}, {"kind": "blank", "p": "This spinner has 8 equal parts. It is spun once. Find (simplest form):", "tag": "", "marks": "", "flat": [{"t": "a) P(red) = __B1__", "a": {"B1": "1/2"}, "expr": "fl"}, {"t": "b) P(blue) = __B1__", "a": {"B1": "1/4"}, "expr": "fl"}, {"t": "c) P(green) = __B1__", "a": {"B1": "1/8"}, "expr": "fl"}, {"t": "d) P(not yellow) = __B1__", "a": {"B1": "7/8"}, "expr": "fl"}], "sol": "8 equal parts: 4 red, 2 blue, 1 green, 1 yellow.\na) 4 out of 8: {4/8} = {1/2}\nb) 2 out of 8: {2/8} = {1/4}\nc) 1 out of 8: {1/8}\nd) 7 out of 8: {7/8}", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 300 150\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><path d=\"M150.0,79.0 L150.0,17.0 A62,62 0 0 1 193.8,35.2 Z\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.3\"/><text x=\"165.7\" y=\"41.2\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">R</text><path d=\"M150.0,79.0 L193.8,35.2 A62,62 0 0 1 212.0,79.0 Z\" style=\"fill:#5b8fe0;stroke:var(--ink);stroke-width:1.3\"/><text x=\"187.8\" y=\"63.3\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">B</text><path d=\"M150.0,79.0 L212.0,79.0 A62,62 0 0 1 193.8,122.8 Z\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.3\"/><text x=\"187.8\" y=\"94.7\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">R</text><path d=\"M150.0,79.0 L193.8,122.8 A62,62 0 0 1 150.0,141.0 Z\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.3\"/><text x=\"165.7\" y=\"116.8\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">G</text><path d=\"M150.0,79.0 L150.0,141.0 A62,62 0 0 1 106.2,122.8 Z\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.3\"/><text x=\"134.3\" y=\"116.8\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">R</text><path d=\"M150.0,79.0 L106.2,122.8 A62,62 0 0 1 88.0,79.0 Z\" style=\"fill:#5b8fe0;stroke:var(--ink);stroke-width:1.3\"/><text x=\"112.2\" y=\"94.7\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">B</text><path d=\"M150.0,79.0 L88.0,79.0 A62,62 0 0 1 106.2,35.2 Z\" style=\"fill:#f0cf55;stroke:var(--ink);stroke-width:1.3\"/><text x=\"112.2\" y=\"63.3\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">Y</text><path d=\"M150.0,79.0 L106.2,35.2 A62,62 0 0 1 150.0,17.0 Z\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.3\"/><text x=\"134.3\" y=\"41.2\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 13px 'Source Sans 3',sans-serif\">R</text><circle cx=\"150.0\" cy=\"79.0\" r=\"4\" style=\"fill:var(--ink)\"/><path d=\"M145.0,5.0 L155.0,5.0 L150.0,20.0 Z\" style=\"fill:var(--danger)\"/></svg>"}, {"kind": "blank", "p": "A drawer holds 4 black, 6 grey and 2 white socks. One sock is taken in the dark. Find (simplest form):", "tag": "", "marks": "", "flat": [{"t": "a) P(grey) = __B1__", "a": {"B1": "1/2"}, "expr": "fl"}, {"t": "b) P(black) = __B1__", "a": {"B1": "1/3"}, "expr": "fl"}, {"t": "c) P(white) = __B1__", "a": {"B1": "1/6"}, "expr": "fl"}], "sol": "4 + 6 + 2 = 12 socks.\na) 6 out of 12: {6/12} = {1/2}\nb) 4 out of 12: {4/12} = {1/3}\nc) 2 out of 12: {2/12} = {1/6}"}, {"kind": "blank", "p": "One word is chosen at random from: apple, banana, cherry, mango, grape, kiwi. Find (simplest form):", "tag": "", "marks": "", "flat": [{"t": "a) P(the word has 5 letters) = __B1__", "a": {"B1": "1/2"}, "expr": "fl"}, {"t": "b) P(the word contains the letter a) = __B1__", "a": {"B1": "2/3"}, "expr": "fl"}, {"t": "c) P(the word starts with a vowel) = __B1__", "a": {"B1": "1/6"}, "expr": "fl"}], "sol": "6 words.\n5 letters: apple, mango, grape · contains a: apple, banana, mango, grape · starts with a vowel: apple\na) 3 out of 6: {3/6} = {1/2}\nb) 4 out of 6: {4/6} = {2/3}\nc) 1 out of 6: {1/6}"}, {"kind": "blank", "p": "A bag holds 20 tokens numbered 1 to 20. One token is drawn. Find (simplest form):", "tag": "", "marks": "", "flat": [{"t": "a) P(a prime number) = __B1__", "a": {"B1": "2/5"}, "expr": "fl"}, {"t": "b) P(a square number) = __B1__", "a": {"B1": "1/5"}, "expr": "fl"}, {"t": "c) P(a multiple of 5) = __B1__", "a": {"B1": "1/5"}, "expr": "fl"}], "sol": "20 outcomes.\nprimes: 2, 3, 5, 7, 11, 13, 17, 19 · squares: 1, 4, 9, 16 · multiples of 5: 5, 10, 15, 20\na) 8 out of 20: {8/20} = {2/5}\nb) 4 out of 20: {4/20} = {1/5}\nc) 4 out of 20: {4/20} = {1/5}"}]}, {"id": "s5", "label": "Review 17A", "sub": "Review set 17A", "slides": [{"kind": "blank", "p": "Describe each event with a probability word.", "tag": "", "marks": "", "flat": [{"t": "a) Rolling a 3 on a normal die. __B1__", "a": {"B1": "unlikely"}, "accept": ["highly unlikely"]}, {"t": "b) Picking a red card from a pack with 26 red and 26 black cards. __B1__", "a": {"B1": "even chance"}, "accept": ["even chance", "50-50 chance", "50-50", "fifty-fifty", "fifty fifty", "even", "evens", "equal chance", "50/50", "50/50 chance"]}, {"t": "c) Next year has 13 months. __B1__", "a": {"B1": "impossible"}}, {"t": "d) Water left in the sun on a hot afternoon gets warmer. __B1__", "a": {"B1": "certain"}, "accept": ["highly likely"]}], "sol": "a) 1 out of 6: unlikely\nb) 26 out of 52 = {1/2}: even chance\nc) impossible\nd) certain"}, {"kind": "blank", "p": "This spinner is spun once.", "tag": "", "marks": "", "flat": [{"t": "a) number of possible outcomes: __B1__", "a": {"B1": "6"}}, {"t": "b) Describe the chance of landing on a number bigger than 2. __B1__", "a": {"B1": "likely"}}, {"t": "c) P(an even number) = __B1__", "a": {"B1": "1/2"}, "expr": "fl"}], "sol": "a) 1, 2, 3, 4, 5, 6\nb) 3, 4, 5, 6 is 4 out of 6: likely\nc) 2, 4, 6: {3/6} = {1/2}", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 300 150\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><path d=\"M150.0,79.0 L150.0,17.0 A62,62 0 0 1 203.7,48.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"170.5\" y=\"43.6\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">1</text><path d=\"M150.0,79.0 L203.7,48.0 A62,62 0 0 1 203.7,110.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"190.9\" y=\"79.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">2</text><path d=\"M150.0,79.0 L203.7,110.0 A62,62 0 0 1 150.0,141.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"170.5\" y=\"114.4\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">3</text><path d=\"M150.0,79.0 L150.0,141.0 A62,62 0 0 1 96.3,110.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"129.5\" y=\"114.4\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">4</text><path d=\"M150.0,79.0 L96.3,110.0 A62,62 0 0 1 96.3,48.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"109.1\" y=\"79.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">5</text><path d=\"M150.0,79.0 L96.3,48.0 A62,62 0 0 1 150.0,17.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"129.5\" y=\"43.6\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">6</text><circle cx=\"150.0\" cy=\"79.0\" r=\"4\" style=\"fill:var(--ink)\"/><path d=\"M145.0,5.0 L155.0,5.0 L150.0,20.0 Z\" style=\"fill:var(--danger)\"/></svg>"}, {"kind": "blank", "p": "A marble is taken without looking. Find (simplest form):", "tag": "", "marks": "", "flat": [{"t": "a) P(green) = __B1__", "a": {"B1": "3/8"}, "expr": "fl"}, {"t": "b) P(red) = __B1__", "a": {"B1": "1/4"}, "expr": "fl"}, {"t": "c) P(not yellow) = __B1__", "a": {"B1": "5/8"}, "expr": "fl"}], "sol": "3 + 2 + 3 = 8 marbles.\na) 3 out of 8: {3/8}\nb) 2 out of 8: {2/8} = {1/4}\nc) 5 out of 8: {5/8}", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 300 44\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><circle cx=\"52.0\" cy=\"20\" r=\"11.5\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"52.0\" y=\"20.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text><circle cx=\"80.0\" cy=\"20\" r=\"11.5\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"80.0\" y=\"20.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text><circle cx=\"108.0\" cy=\"20\" r=\"11.5\" style=\"fill:#4fb47a;stroke:var(--ink);stroke-width:1.1\"/><text x=\"108.0\" y=\"20.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">G</text><circle cx=\"136.0\" cy=\"20\" r=\"11.5\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"136.0\" y=\"20.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"164.0\" cy=\"20\" r=\"11.5\" style=\"fill:#e46b5e;stroke:var(--ink);stroke-width:1.1\"/><text x=\"164.0\" y=\"20.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">R</text><circle cx=\"192.0\" cy=\"20\" r=\"11.5\" style=\"fill:#f0cf55;stroke:var(--ink);stroke-width:1.1\"/><text x=\"192.0\" y=\"20.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">Y</text><circle cx=\"220.0\" cy=\"20\" r=\"11.5\" style=\"fill:#f0cf55;stroke:var(--ink);stroke-width:1.1\"/><text x=\"220.0\" y=\"20.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">Y</text><circle cx=\"248.0\" cy=\"20\" r=\"11.5\" style=\"fill:#f0cf55;stroke:var(--ink);stroke-width:1.1\"/><text x=\"248.0\" y=\"20.5\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:#1b1b1b;font:700 10px 'Source Sans 3',sans-serif\">Y</text></svg>"}, {"kind": "blank", "p": "A letter is chosen at random from the word EQUATOR. Find (simplest form):", "tag": "", "marks": "", "flat": [{"t": "a) P(a vowel) = __B1__", "a": {"B1": "4/7"}, "expr": "fl"}, {"t": "b) P(the letter A) = __B1__", "a": {"B1": "1/7"}, "expr": "fl"}, {"t": "c) P(a consonant) = __B1__", "a": {"B1": "3/7"}, "expr": "fl"}], "sol": "7 letters: E, Q, U, A, T, O, R.\nvowels: E, U, A, O · consonants: Q, T, R\na) 4 out of 7: {4/7}\nb) 1 out of 7: {1/7}\nc) 3 out of 7: {3/7}"}, {"kind": "mcq", "text": "Which probability describes an event that is highly likely?", "opts": ["0.09", "{1/2}", "0.97", "0"], "correct": 2, "tag": "", "sol": "0.97 is very close to 1, so it is highly likely."}]}, {"id": "s6", "label": "Review 17B", "sub": "Review set 17B", "slides": [{"kind": "blank", "p": "Match each probability with a word.", "tag": "", "marks": "", "flat": [{"t": "a) 0.5 → __B1__", "a": {"B1": "even chance"}, "accept": ["even chance", "50-50 chance", "50-50", "fifty-fifty", "fifty fifty", "even", "evens", "equal chance", "50/50", "50/50 chance"]}, {"t": "b) 0.02 → __B1__", "a": {"B1": "highly unlikely"}}, {"t": "c) {5/8} → __B1__", "a": {"B1": "likely"}}, {"t": "d) 1 → __B1__", "a": {"B1": "certain"}}], "sol": "a) half: even chance\nb) very close to 0: highly unlikely\nc) {5/8} is more than {1/2} but not close to 1: likely\nd) certain", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 340 112\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line class=\"ln\" x1=\"24.0\" y1=\"52.0\" x2=\"316.0\" y2=\"52.0\"/><line class=\"ln\" x1=\"24.0\" y1=\"45.0\" x2=\"24.0\" y2=\"59.0\"/><text class=\"lb\" x=\"24.0\" y=\"71.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">0</text><line class=\"ln\" x1=\"170.0\" y1=\"45.0\" x2=\"170.0\" y2=\"59.0\"/><text class=\"lb\" x=\"170.0\" y=\"71.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">½</text><line class=\"ln\" x1=\"316.0\" y1=\"45.0\" x2=\"316.0\" y2=\"59.0\"/><text class=\"lb\" x=\"316.0\" y=\"71.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><rect x=\"29.84\" y=\"49\" width=\"29.2\" height=\"6\" style=\"fill:var(--gold-soft)\"/><rect x=\"280.96\" y=\"49\" width=\"29.19999999999999\" height=\"6\" style=\"fill:var(--gold-soft)\"/><text class=\"al\" x=\"24.0\" y=\"34.0\" text-anchor=\"start\" dominant-baseline=\"middle\">impossible</text><text class=\"al\" x=\"170.0\" y=\"34.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">even chance</text><text class=\"al\" x=\"316.0\" y=\"34.0\" text-anchor=\"end\" dominant-baseline=\"middle\">certain</text><text class=\"lb\" x=\"105.8\" y=\"71.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">unlikely</text><text class=\"lb\" x=\"234.2\" y=\"71.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">likely</text><text class=\"lb\" x=\"44.4\" y=\"92.0\" text-anchor=\"start\" dominant-baseline=\"middle\">highly unlikely</text><text class=\"lb\" x=\"295.6\" y=\"92.0\" text-anchor=\"end\" dominant-baseline=\"middle\">highly likely</text><line class=\"ln\" x1=\"44.4\" y1=\"82.0\" x2=\"44.4\" y2=\"60.0\"/><line class=\"ln\" x1=\"295.6\" y1=\"82.0\" x2=\"295.6\" y2=\"60.0\"/></svg>"}, {"kind": "blank", "p": "Cards numbered 1 to 25 are placed in a hat and one is drawn. Find (simplest form):", "tag": "", "marks": "", "flat": [{"t": "a) P(a multiple of 4) = __B1__", "a": {"B1": "6/25"}, "expr": "fl"}, {"t": "b) P(a number with the digit 2) = __B1__", "a": {"B1": "8/25"}, "expr": "fl"}, {"t": "c) P(an even number) = __B1__", "a": {"B1": "12/25"}, "expr": "fl"}], "sol": "25 outcomes.\nmultiples of 4: 4, 8, 12, 16, 20, 24 · with a digit 2: 2, 12, 20, 21, 22, 23, 24, 25 · even: 2, 4, …, 24\na) 6 out of 25: {6/25}\nb) 8 out of 25: {8/25}\nc) 12 out of 25: {12/25}"}, {"kind": "blank", "p": "A bag of 20 sweets has 5 orange, 6 purple and the rest yellow. One is taken at random.", "tag": "", "marks": "", "flat": [{"t": "a) number of yellow sweets: __B1__", "a": {"B1": "9"}}, {"t": "b) P(orange) = __B1__", "a": {"B1": "1/4"}, "expr": "fl"}, {"t": "c) P(not purple) = __B1__", "a": {"B1": "7/10"}, "expr": "fl"}], "sol": "a) 20 − 5 − 6 = 9\nb) 5 out of 20: {5/20} = {1/4}\nc) not purple: 5 + 9 = 14, so {14/20} = {7/10}"}, {"kind": "blank", "p": "Which spinner gives the better chance of landing on 1? Write each probability first (simplest form).", "tag": "", "marks": "", "flat": [{"t": "a) Spinner A: P(1) = __B1__", "a": {"B1": "1/3"}, "expr": "fl"}, {"t": "b) Spinner B: P(1) = __B1__", "a": {"B1": "3/8"}, "expr": "fl"}, {"t": "c) better spinner (A or B): __B1__", "a": {"B1": "B"}}], "sol": "a) 2 of 6 = {1/3}\nb) 3 of 8\nc) {1/3} = {8/24} and {3/8} = {9/24}, so B is better", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 340 168\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><g><path d=\"M85.0,79.0 L85.0,17.0 A62,62 0 0 1 138.7,48.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"105.5\" y=\"43.6\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">1</text><path d=\"M85.0,79.0 L138.7,48.0 A62,62 0 0 1 138.7,110.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"125.9\" y=\"79.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">2</text><path d=\"M85.0,79.0 L138.7,110.0 A62,62 0 0 1 85.0,141.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"105.5\" y=\"114.4\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">1</text><path d=\"M85.0,79.0 L85.0,141.0 A62,62 0 0 1 31.3,110.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"64.5\" y=\"114.4\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">3</text><path d=\"M85.0,79.0 L31.3,110.0 A62,62 0 0 1 31.3,48.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"44.1\" y=\"79.0\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">2</text><path d=\"M85.0,79.0 L31.3,48.0 A62,62 0 0 1 85.0,17.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"64.5\" y=\"43.6\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">3</text><circle cx=\"85.0\" cy=\"79.0\" r=\"4\" style=\"fill:var(--ink)\"/><path d=\"M80.0,5.0 L90.0,5.0 L85.0,20.0 Z\" style=\"fill:var(--danger)\"/></g><g transform=\"translate(170,0)\"><path d=\"M85.0,79.0 L85.0,17.0 A62,62 0 0 1 128.8,35.2 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"100.7\" y=\"41.2\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">1</text><path d=\"M85.0,79.0 L128.8,35.2 A62,62 0 0 1 147.0,79.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"122.8\" y=\"63.3\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">2</text><path d=\"M85.0,79.0 L147.0,79.0 A62,62 0 0 1 128.8,122.8 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"122.8\" y=\"94.7\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">3</text><path d=\"M85.0,79.0 L128.8,122.8 A62,62 0 0 1 85.0,141.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"100.7\" y=\"116.8\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">1</text><path d=\"M85.0,79.0 L85.0,141.0 A62,62 0 0 1 41.2,122.8 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"69.3\" y=\"116.8\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">2</text><path d=\"M85.0,79.0 L41.2,122.8 A62,62 0 0 1 23.0,79.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"47.2\" y=\"94.7\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">3</text><path d=\"M85.0,79.0 L23.0,79.0 A62,62 0 0 1 41.2,35.2 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"47.2\" y=\"63.3\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">1</text><path d=\"M85.0,79.0 L41.2,35.2 A62,62 0 0 1 85.0,17.0 Z\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1.3\"/><text x=\"69.3\" y=\"41.2\" text-anchor=\"middle\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:700 13px 'Source Sans 3',sans-serif\">2</text><circle cx=\"85.0\" cy=\"79.0\" r=\"4\" style=\"fill:var(--ink)\"/><path d=\"M80.0,5.0 L90.0,5.0 L85.0,20.0 Z\" style=\"fill:var(--danger)\"/></g><text class=\"lb\" x=\"85.0\" y=\"160.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Spinner A</text><text class=\"lb\" x=\"255.0\" y=\"160.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Spinner B</text></svg>"}, {"kind": "blank", "p": "A drinks cooler holds 4 mango, 7 lemon and 1 guava drink. Anil picks one without looking.", "tag": "", "marks": "", "flat": [{"t": "a) Describe the chance of lemon. __B1__", "a": {"B1": "likely"}}, {"t": "b) Describe the chance of cola. __B1__", "a": {"B1": "impossible"}}, {"t": "c) P(mango) = __B1__", "a": {"B1": "1/3"}, "expr": "fl"}, {"t": "d) P(mango) as a percentage, to the nearest whole number: __B1__ %", "a": {"B1": "33"}}], "sol": "12 drinks.\na) 7 of 12 is more than half: likely\nb) there is no cola: impossible\nc) {4/12} = {1/3}\nd) {1/3} × 100 % ≈ 33.3 % ≈ 33 %"}]}];
/* ================= build slide lists ================= */
var SLIDES = {}; SECTIONS.forEach(function(sec){ SLIDES[sec.id]=sec.slides; });
var TAB_DEFS = SECTIONS.map(function(sec){ return {id:sec.id, label:sec.label, sub:sec.sub}; });

/* ================= state ================= */
function blankItem(slide){
  if(slide.kind==='mcq'||slide.kind==='ar'){
    return {status:'unanswered', attempts:0, choice:undefined};
  }
  return {status:'unanswered', curStep:0, stepStates: slide.flat.map(function(){ return {status:'unanswered', attempts:0, inputs:{}}; })};
}
function defaultState(){
  var s={tabs:{}};
  TAB_DEFS.forEach(function(td){
    s.tabs[td.id] = { idx:0, maxReached:0, items: SLIDES[td.id].map(function(sl){ return blankItem(sl); }) };
  });
  return s;
}
var appState = {mode:null, learning:null, quiz:null};
var state = null;      // alias for appState[appState.mode]
var MODE = null;
var activeTab=TAB_DEFS[0].id;

function setMode(m){
  appState.mode = m;
  if(!appState[m]) appState[m] = defaultState();
  state = appState[m];
  MODE = m;
}
/* ================= student accounts (saved on this device) ================= */
var SHEET_KEY='sopaan-g6-ch17';
var ACC_KEY='sopaan-students-v1';
var storageOK=true;
var MEM={};
function lsGet(k){ var r=null; try{ r=localStorage.getItem(k); }catch(e){ storageOK=false; }
  if(r===null||r===undefined) r=MEM[k]||null; try{ return r?JSON.parse(r):null; }catch(e){ return null; } }
function lsSet(k,v){ var j=JSON.stringify(v); MEM[k]=j; try{ localStorage.setItem(k,j); return true; }catch(e){ storageOK=false; return false; } }
try{ localStorage.setItem('sopaan-probe','1'); localStorage.removeItem('sopaan-probe'); }catch(e){ storageOK=false; }
function hashPin(pin,salt){ var h=2166136261, str=salt+'|'+pin; for(var i=0;i<str.length;i++){ h^=str.charCodeAt(i); h=Math.imul(h,16777619)>>>0; } return h.toString(36); }
function accKey(name,roll){ return (name.trim().toLowerCase().replace(/\s+/g,' ')+'#'+roll.trim().toLowerCase()); }
function accounts(){ return lsGet(ACC_KEY)||{students:{}}; }
var student=null; // {key,name,roll}
var records=[];   // finished-tab history for this student on this sheet
function progKey(){ return SHEET_KEY+'::'+student.key; }

function loadState(){
  appState = {mode:null, learning:null, quiz:null}; records=[]; activeTab=TAB_DEFS[0].id;
  var saved=lsGet(progKey());
  if(!saved) return;
  try{
    ['learning','quiz'].forEach(function(m){
      if(saved[m] && saved[m].tabs){
        var fresh = defaultState();
        TAB_DEFS.forEach(function(td){
          if(saved[m].tabs[td.id] && saved[m].tabs[td.id].items && saved[m].tabs[td.id].items.length===SLIDES[td.id].length){
            fresh.tabs[td.id] = saved[m].tabs[td.id];
          }
        });
        appState[m] = fresh;
      }
    });
    if(saved.mode==='learning' || saved.mode==='quiz') appState.mode = saved.mode;
    if(saved.activeTab && TAB_DEFS.some(function(t){ return t.id===saved.activeTab; })) activeTab = saved.activeTab;
    if(Array.isArray(saved.records)) records = saved.records;
  }catch(e){}
}
function saveState(){
  if(!student) return;
  lsSet(progKey(), {mode:appState.mode, learning:appState.learning, quiz:appState.quiz, activeTab:activeTab, records:records, updated:Date.now()});
  var acc=accounts(); if(acc.students[student.key]){ acc.students[student.key].last=Date.now(); lsSet(ACC_KEY,acc); }
}
function addRecord(mode, tabId, correct, revealed, skipped, total){
  records.unshift({at:Date.now(), mode:mode, tab:tabId, correct:correct, revealed:revealed, skipped:skipped, total:total});
  if(records.length>60) records.length=60;
  saveState();
}
function fmtDate(ms){ try{ return new Date(ms).toLocaleString(undefined,{day:'numeric',month:'short',hour:'2-digit',minute:'2-digit'}); }catch(e){ return ''; } }

function renderWho(){
  var el=document.getElementById('whoBar');
  if(!student){ el.hidden=true; el.innerHTML=''; return; }
  el.hidden=false;
  el.innerHTML='Signed in as <b>'+esc(student.name)+'</b> · Roll '+esc(student.roll)+
    ' <button id="btnRecord">My record</button> <button id="btnSignOut">Sign out</button>';
  document.getElementById('btnRecord').addEventListener('click', renderRecord);
  document.getElementById('btnSignOut').addEventListener('click', signOut);
}
function signOut(){
  saveState(); student=null; state=null; MODE=null;
  var acc=accounts(); delete acc.current; lsSet(ACC_KEY,acc);
  document.getElementById('modePill').hidden=true;
  renderWho(); renderLogin();
}
function signIn(key){
  var acc=accounts(); var st=acc.students[key]; if(!st) return;
  student={key:key, name:st.name, roll:st.roll};
  acc.current=key; st.last=Date.now(); lsSet(ACC_KEY,acc);
  loadState(); renderWho();
  if(appState.mode==='learning' || appState.mode==='quiz'){
    setMode(appState.mode); document.getElementById('modePill').hidden=false; updateModePill();
    showChrome(true); buildTabbar(); renderSlide();
    showToast('Welcome back, '+st.name.split(' ')[0]+'. Picking up where you left off.');
  } else {
    renderModePicker();
  }
}
function renderLogin(msg){
  showChrome(false);
  var acc=accounts(); var keys=Object.keys(acc.students).sort(function(a,b){ return (acc.students[b].last||0)-(acc.students[a].last||0); });
  var h='<div class="login-card"><h2>Student sign-in</h2>'+
    '<p class="lead">Sign in to save your answers, see your record and continue where you left off next time.</p>';
  if(!storageOK) h+='<div class="login-err">This browser is blocking saved data (for example, a private window). You can still practise, but progress will not be kept after you close the page.</div>';
  if(msg) h+='<div class="login-err">'+esc(msg)+'</div>';
  if(keys.length){
    h+='<div class="known"><span class="known-label">Continue as</span>';
    keys.slice(0,6).forEach(function(k){ var st=acc.students[k];
      h+='<button class="known-btn" data-k="'+esc(k)+'"><span>'+esc(st.name)+' <small>· Roll '+esc(st.roll)+'</small></span><small>'+(st.last?'Last active '+fmtDate(st.last):'')+'</small></button>'; });
    h+='</div>';
  }
  h+='<form id="loginForm" novalidate>'+
    '<div class="fld"><label for="lgName">Full name</label><input id="lgName" autocomplete="name" required></div>'+
    '<div class="fld-row"><div class="fld"><label for="lgRoll">Roll no.</label><input id="lgRoll" required></div>'+
    '<div class="fld"><label for="lgPin">4-digit PIN</label><input id="lgPin" type="password" inputmode="numeric" maxlength="4" autocomplete="off" required></div></div>'+
    '<button class="btn btn-primary" type="submit" style="width:100%;">Sign in</button>'+
    '<p class="login-note">New here? Enter your name, roll no. and a PIN you will remember, and your profile is created. Progress is saved on this device, so use the same device and browser to continue.</p>'+
    '</form></div>';
  var wrap=document.getElementById('wrap'); wrap.innerHTML=h;
  wrap.querySelectorAll('.known-btn').forEach(function(b){
    b.addEventListener('click', function(){
      var st=accounts().students[b.dataset.k];
      document.getElementById('lgName').value=st.name; document.getElementById('lgRoll').value=st.roll;
      document.getElementById('lgPin').focus();
    });
  });
  document.getElementById('loginForm').addEventListener('submit', function(e){
    e.preventDefault();
    var name=document.getElementById('lgName').value.trim(), roll=document.getElementById('lgRoll').value.trim(), pin=document.getElementById('lgPin').value.trim();
    if(!name||!roll){ renderLoginErr('Enter your name and roll no.'); return; }
    if(!/^\d{4}$/.test(pin)){ renderLoginErr('Your PIN must be exactly 4 digits.'); return; }
    var k=accKey(name,roll); var acc=accounts();
    if(acc.students[k]){
      if(acc.students[k].pin!==hashPin(pin,k)){ renderLoginErr('That PIN does not match this name and roll no. Try again.'); return; }
    } else {
      acc.students[k]={name:name.replace(/\s+/g,' '), roll:roll, pin:hashPin(pin,k), created:Date.now()};
      lsSet(ACC_KEY,acc);
    }
    signIn(k);
  });
}
function renderLoginErr(m){
  var n=document.getElementById('lgName').value, r=document.getElementById('lgRoll').value;
  renderLogin(m); document.getElementById('lgName').value=n; document.getElementById('lgRoll').value=r; document.getElementById('lgPin').focus();
}
function tabSummary(m){
  var st=appState[m]; if(!st) return null;
  return TAB_DEFS.map(function(td){
    var items=st.tabs[td.id].items, n=items.length;
    var c=items.filter(function(i){return i.status==='correct';}).length;
    var done=items.filter(function(i){return i.status!=='unanswered';}).length;
    return {label:td.label, n:n, done:done, correct:c};
  });
}
function renderRecord(){
  showChrome(false);
  var tabLabel=function(id){ var t=TAB_DEFS.find(function(x){return x.id===id;}); return t?t.label:id; };
  var h='<div class="rec-card"><h2>'+esc(student.name)+'’s record</h2><p class="rec-empty" style="margin:0 0 12px;">Roll '+esc(student.roll)+' · Probability</p>';
  ['learning','quiz'].forEach(function(m){
    var sum=tabSummary(m);
    h+='<h3>'+(m==='learning'?'📘 Learning Sheet':'📝 Quiz Mode')+'</h3>';
    if(!sum){ h+='<p class="rec-empty">Not started yet.</p>'; return; }
    h+='<div class="rec-table-wrap"><table class="rec-table"><thead><tr><th>Section</th><th>Progress</th><th>Correct first time</th></tr></thead><tbody>';
    sum.forEach(function(r){ var pct=Math.round(r.done/r.n*100);
      h+='<tr><td>'+r.label+'</td><td><span class="rec-bar"><i style="width:'+pct+'%"></i></span>'+r.done+' / '+r.n+'</td><td>'+(m==='quiz'?'—':r.correct+' / '+r.n)+'</td></tr>'; });
    h+='</tbody></table></div>';
  });
  h+='</div><div class="rec-card"><h3>Finished sections</h3>';
  if(!records.length){ h+='<p class="rec-empty">No sections finished yet. Each time you finish a tab, your score is recorded here.</p>'; }
  else {
    h+='<div class="rec-table-wrap"><table class="rec-table"><thead><tr><th>When</th><th>Mode</th><th>Section</th><th>Score</th></tr></thead><tbody>';
    records.forEach(function(r){ h+='<tr><td>'+fmtDate(r.at)+'</td><td>'+(r.mode==='quiz'?'Quiz':'Learning')+'</td><td>'+tabLabel(r.tab)+'</td><td>'+r.correct+' / '+r.total+(r.mode==='learning'?' <span class="rec-empty">('+r.revealed+' revealed, '+r.skipped+' skipped)</span>':'')+'</td></tr>'; });
    h+='</tbody></table></div>';
  }
  h+='</div><button class="btn btn-primary" id="btnBack">'+(MODE?'Back to practice':'Choose a mode')+'</button>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('btnBack').addEventListener('click', function(){
    if(MODE){ showChrome(true); buildTabbar(); renderSlide(); } else renderModePicker();
  });
  window.scrollTo({top:0});
}

/* ================= tab bar ================= */
function buildTabbar(){
  var el=document.getElementById('tabbar');
  el.innerHTML = TAB_DEFS.map(function(t){
    return '<button class="tab-btn'+(t.id===activeTab?' active':'')+'" data-tab="'+t.id+'">'+t.label+'<span class="tab-count">'+SLIDES[t.id].length+'</span></button>';
  }).join('');
  el.querySelectorAll('.tab-btn').forEach(function(btn){
    btn.addEventListener('click', function(){ activeTab=btn.dataset.tab; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); });
  });
}

/* ================= rendering ================= */
function canProceed(item){ return item.status==='correct'||item.status==='revealed'||item.status==='skipped'; }

function renderSlide(){
  if(!state.tabs[activeTab]){ activeTab=TAB_DEFS[0].id; }
  var ts = state.tabs[activeTab];
  var slides = SLIDES[activeTab];
  if(ts.idx>=slides.length||ts.idx<0) ts.idx=0;
  var idx = ts.idx;
  var slide = slides[idx];
  var item = ts.items[idx];

  var tdef=TAB_DEFS.find(function(t){return t.id===activeTab;});
  document.getElementById('spLabel').textContent = tdef.label+' · Question '+(idx+1)+' of '+slides.length;
  document.getElementById('secSub').textContent = tdef.label+' — '+tdef.sub;
  document.getElementById('spFill').style.width = Math.round(((idx)/(Math.max(slides.length-1,1)))*100)+'%';

  var h='<div class="qcard">';
  if(slide.kind==='mcq' || slide.kind==='ar'){
    h += renderChoiceBody(slide, item, idx);
  } else {
    h += renderBlankBody(slide, item, idx);
  }
  h += '<div class="feedback" id="feedbackBox"></div>';
  if(MODE==='learning' && (item.status==='correct'||item.status==='revealed')) h += solutionHTML(slide);
  h += '</div>';

  document.getElementById('wrap').innerHTML = h;
  wireSlideEvents(slide, item, idx);
  restoreFeedback(item);
  renderNavbar(item);
  updateFab();
  saveState();
}

function solutionHTML(slide){
  if(!slide.sol) return '';
  return '<div class="solution"><div class="sol-h">Solution</div>'+slide.sol.split('\n').map(function(l){ return '<div class="sol-line">'+fr(esc(l))+'</div>'; }).join('')+'</div>';
}
var LETTERS=['a','b','c','d'];
function chosenHTML(slide,item){
  var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
  if(item.choice===undefined) return '';
  var ok=item.choice===slide.correct;
  var h='<div class="chosen '+(ok?'ok':'bad')+'"><b>Your answer:</b> ('+LETTERS[item.choice]+') '+fr(esc(opts[item.choice]))+(ok?' ✓':' ✗')+'</div>';
  if(!ok) h+='<div class="chosen ok"><b>Correct answer:</b> ('+LETTERS[slide.correct]+') '+fr(esc(opts[slide.correct]))+'</div>';
  return h;
}
function renderChoiceBody(slide, item, idx){
  var h='<div class="qhead"><div class="qnum">'+(idx+1)+'</div>';
  if(slide.kind==='mcq'){
    h += '<div class="qtext">'+fr(esc(slide.text))+(slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  } else {
    h += '<div class="qtext"><span class="qtag" style="margin-left:0;margin-right:6px;">A / R</span>Assertion (A): '+fr(esc(slide.a))+'<br>Reason (R): '+fr(esc(slide.r))+(slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  }
  h += '</div>';
  if(slide.fig) h += '<div class="fig">'+slide.fig+'</div>';
  var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
  if(MODE==='quiz') h += '<div class="quiz-hint">Quiz mode — pick an option. The correct answer is revealed once you finish this tab.</div>';
  var locked = MODE==='learning' && (item.status==='correct' || item.status==='revealed');
  h += '<div class="options">';
  opts.forEach(function(opt,i){
    var cls='opt';
    if(locked){
      if(i===slide.correct) cls+=' is-correct';
      else if(item.choice===i) cls+=' is-wrong';
      cls+=' locked';
    }
    if(item.choice===i) cls+=' is-chosen';
    h += '<label class="'+cls+'"><input type="radio" name="choice" value="'+i+'" '+(item.choice===i?'checked':'')+' '+(locked?'disabled':'')+'> <span class="opt-l">('+LETTERS[i]+')</span> <span class="opt-t">'+fr(esc(opt))+'</span>'+(item.choice===i?'<span class="opt-tag">'+(locked?(i===slide.correct?'Your answer ✓':'Your answer ✗'):'Selected')+'</span>':'')+'</label>';
  });
  h += '</div>';
  if(locked) h += chosenHTML(slide,item);
  return h;
}

function renderBlankBody(slide, item, idx){
  var h='<div class="qhead"><div class="qnum">'+(idx+1)+'</div><div class="qtext">';
  if(slide.kind==='case'){ h += '<b>'+esc(slide.title)+'.</b> '+esc(slide.body); }
  else { var pp=fr(esc(slide.p)).split('\n'); h += pp[0]+pp.slice(1).map(function(x){return '<span class="datline">'+x+'</span>';}).join(''); }
  h += (slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  if(slide.marks) h += '<div class="marks-pill">'+slide.marks+'</div>';
  h += '</div>';
  if(slide.fig) h += '<div class="fig">'+slide.fig+'</div>';

  var total = slide.flat.length;
  var hasExpr = slide.flat.some(function(s){ return s.expr===true; });
  var hasFrac = slide.flat.some(function(s){ return ['fv','fe','fl','fm','fi','flist'].indexOf(s.expr)>=0; });
  var blankCount=0; slide.flat.forEach(function(s){ blankCount+=Object.keys(s.a).length; });

  if(MODE==='quiz'){
    h += '<div class="step-badge">'+blankCount+' blank'+(blankCount===1?'':'s')+' in this question</div>';
    h += '<div class="quiz-hint">Quiz mode — fill in what you can. Correct answers are revealed once you finish this tab.</div>';
    if(hasFrac) h += '<div class="quiz-hint">Type fractions like <b>3/4</b> and mixed numbers like <b>2 3/4</b> (whole number, space, fraction).</div>';
    if(hasExpr) h += '<div class="quiz-hint">Type expressions like <b>(P-2w)/2</b>, <b>2A/b</b> or <b>V/(pi*r^2)</b>. Use ^ for powers and pi for π. Any equivalent form is accepted.</div>';
    h += '<div class="steps">';
    for(var qi=0; qi<total; qi++){
      var qstep = slide.flat[qi];
      var qss = item.stepStates[qi];
      if(qstep.partLabel) h += '<div class="subpart-label">'+esc(qstep.partLabel)+'</div>';
      if(qstep.orDivider) h += '<div class="or-divider">OR</div>';
      var qline = fr(qstep.t);
      Object.keys(qstep.a).forEach(function(bkey){
        var val = qss.inputs[bkey]||'';
        var inp='<input class="blank-input'+(['fv','fe','fl','fm','fi','dec'].indexOf(qstep.expr)>=0?' fr':(qstep.expr==='flist'||qstep.expr==='dlist'||qstep.expr==='glist')?' wide':qstep.expr===true?' expr':(qstep.expr==='words'||qstep.expr==='list'||qstep.expr==='expanded'||qstep.expr==='set'||qstep.expr==='primes'||qstep.expr==='trans'||qstep.expr==='rot'?' wide':''))+'" data-step="'+qi+'" data-bkey="'+bkey+'" value="'+esc(val)+'">';
        qline = qline.replace('__'+bkey+'__', inp);
      });
      if(qstep.fig) h += '<div class="fig">'+qstep.fig+'</div>';
      h += '<div class="step-line">'+qline+'</div>';
    }
    h += '</div>';
    return h;
  }

  if(hasFrac) h += '<div class="quiz-hint">Type fractions like <b>3/4</b> and mixed numbers like <b>2 3/4</b> (whole number, space, fraction).</div>';
  if(hasExpr) h += '<div class="quiz-hint">Type expressions like <b>(P-2w)/2</b>, <b>2A/b</b> or <b>V/(pi*r^2)</b>. Use ^ for powers and pi for π. Any equivalent form is accepted.</div>';
  var locked = item.status==='correct' || item.status==='revealed';
  var upto = locked ? total-1 : item.curStep;
  h += '<div class="step-badge">Step '+(Math.min(item.curStep,total-1)+1)+' of '+total+'</div>';
  h += '<div class="steps">';
  for(var i=0;i<=upto;i++){
    var step = slide.flat[i];
    var ss = item.stepStates[i];
    if(step.partLabel) h += '<div class="subpart-label">'+esc(step.partLabel)+'</div>';
    if(step.orDivider) h += '<div class="or-divider">OR</div>';
    var resolved = ss.status==='correct' || ss.status==='revealed';
    var line = fr(step.t);
    Object.keys(step.a).forEach(function(bkey){
      var fs = ss.inputs['fs_'+bkey];
      var cls = fs==='correct'?'is-correct':(fs==='wrong'?'is-wrong':'');
      var val = ss.inputs[bkey]||'';
      var dis = resolved ? 'disabled':'';
      var inp='<input class="blank-input '+cls+(['fv','fe','fl','fm','fi','dec'].indexOf(step.expr)>=0?' fr':(step.expr==='flist'||step.expr==='dlist'||step.expr==='glist')?' wide':step.expr===true?' expr':(step.expr==='words'||step.expr==='list'||step.expr==='expanded'||step.expr==='set'||step.expr==='primes'||step.expr==='trans'||step.expr==='rot'?' wide':''))+'" data-step="'+i+'" data-bkey="'+bkey+'" value="'+esc(val)+'" '+dis+'>';
      line = line.replace('__'+bkey+'__', inp);
    });
    if(step.fig) h += '<div class="fig">'+step.fig+'</div>';
    h += '<div class="step-line'+(resolved?' resolved':'')+'">'+line+'</div>';
    if(ss.status==='revealed'){
      var reveals=[];
      Object.keys(step.a).forEach(function(bkey){ reveals.push(bkey+' = '+esc(step.a[bkey])); });
      h += '<div class="reveal-note">correct: '+reveals.join(', ')+'</div>';
    }
  }
  h += '</div>';
  return h;
}

var __flash=null;
function restoreFeedback(item){
  var fb=document.getElementById('feedbackBox'); if(!fb) return;
  if(__flash){ fb.className='feedback show '+__flash.c; fb.innerHTML=__flash.h; __flash=null; return; }
  if(MODE==='quiz'){ fb.className='feedback'; fb.innerHTML=''; return; }
  if(item.status==='correct'){ fb.className='feedback show ok'; fb.innerHTML='<b>All done — correct!</b>'; }
  else if(item.status==='revealed'){ fb.className='feedback show reveal'; fb.innerHTML='<b>Answer revealed above.</b> Move on whenever you’re ready.'; }
  else if(item.status==='skipped'){ fb.className='feedback show retry'; fb.innerHTML='Skipped — revisit it anytime from the Question Palette.'; }
  else { fb.className='feedback'; fb.innerHTML=''; }
}

function slideIsAnswered(slide,item){
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice!==undefined;
  return item.stepStates.some(function(ss){ return Object.keys(ss.inputs).some(function(k){ return k.indexOf('fs_')!==0 && ss.inputs[k] && String(ss.inputs[k]).trim()!==''; }); });
}
function renderNavbar(item){
  var ts = state.tabs[activeTab];
  var slides = SLIDES[activeTab];
  var slide = slides[ts.idx];
  var isLast = ts.idx === slides.length-1;
  var h='';
  h += '<button class="btn" id="btnPrev" '+(ts.idx===0?'disabled':'')+'>&larr; Previous</button>';

  if(MODE==='quiz'){
    h += '<button class="btn" id="btnSkip">Skip</button>';
    h += '<span class="spacer"></span>';
    h += '<button class="btn btn-primary" id="btnNext">'+(isLast?'Finish':'Next →')+'</button>';
  } else {
    h += '<button class="btn" id="btnSkip" '+(item.status!=='unanswered'?'disabled':'')+'>Skip</button>';
    h += '<span class="spacer"></span>';
    h += '<button class="btn btn-primary" id="btnCheck" '+(item.status!=='unanswered'?'disabled':'')+'>Check</button>';
    h += '<button class="btn btn-primary" id="btnNext" '+(canProceed(item)?'':'disabled')+'>'+(isLast?'Finish':'Next →')+'</button>';
  }
  document.getElementById('navbarInner').innerHTML = h;

  document.getElementById('btnPrev').addEventListener('click', function(){ if(ts.idx>0){ ts.idx--; renderSlide(); } });

  if(MODE==='quiz'){
    document.getElementById('btnSkip').addEventListener('click', function(){
      item.status='skipped';
      advanceQuiz(ts, slides);
    });
    document.getElementById('btnNext').addEventListener('click', function(){
      item.status = slideIsAnswered(slide,item) ? 'answered' : 'unanswered';
      advanceQuiz(ts, slides);
    });
  } else {
    document.getElementById('btnSkip').addEventListener('click', function(){
      if(item.status==='unanswered'){ item.status='skipped'; renderSlide(); }
    });
    document.getElementById('btnNext').addEventListener('click', function(){
      if(!canProceed(item)) return;
      if(ts.idx < slides.length-1){ ts.idx++; ts.maxReached=Math.max(ts.maxReached, ts.idx); renderSlide(); }
      else { renderFinished(); }
    });
    document.getElementById('btnCheck').addEventListener('click', function(){ handleCheck(); });
  }
}
function advanceQuiz(ts, slides){
  if(ts.idx < slides.length-1){ ts.idx++; ts.maxReached=Math.max(ts.maxReached, ts.idx); renderSlide(); }
  else { renderFinished(); }
}

function wireSlideEvents(slide, item, idx){
  document.querySelectorAll('input[type="radio"][name="choice"]').forEach(function(r){
    r.addEventListener('change', function(){ item.choice=parseInt(r.value,10); saveState();
      document.querySelectorAll('.opt').forEach(function(l){ l.classList.remove('is-chosen'); var t=l.querySelector('.opt-tag'); if(t) t.remove(); });
      var lab=r.closest('.opt'); lab.classList.add('is-chosen'); var tg=document.createElement('span'); tg.className='opt-tag'; tg.textContent='Selected'; lab.appendChild(tg); });
  });
  document.querySelectorAll('.blank-input').forEach(function(inp){
    inp.addEventListener('input', function(){
      var si=parseInt(inp.dataset.step,10), bk=inp.dataset.bkey;
      item.stepStates[si].inputs[bk]=inp.value;
      saveState();
    });
  });
}

function handleCheck(){
  var ts = state.tabs[activeTab];
  var slide = SLIDES[activeTab][ts.idx];
  var item = ts.items[ts.idx];
  var fb = document.getElementById('feedbackBox');

  if(slide.kind==='mcq' || slide.kind==='ar'){
    if(item.choice===undefined){ fb.className='feedback show err'; fb.innerHTML='Please choose an option first.'; return; }
    var ok = item.choice===slide.correct;
    if(ok){
      item.status='correct'; playSuccess();
      fb.className='feedback show ok'; fb.innerHTML='<b>Correct!</b>';
    } else {
      item.attempts=(item.attempts||0)+1;
      if(item.attempts>=2){ item.status='revealed'; playReveal(); }
      else { playWrong(); fb.className='feedback show retry'; fb.innerHTML='<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'; __flash={c:'retry',h:'<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'}; }
    }
    renderSlide();
    return;
  }

  // blank / case
  var step = slide.flat[item.curStep];
  var ss = item.stepStates[item.curStep];
  var blanks = Object.keys(step.a);
  var missing = blanks.some(function(k){ return !ss.inputs[k] || String(ss.inputs[k]).trim()===''; });
  if(missing){ fb.className='feedback show err'; fb.innerHTML='Fill in every blank in this step before checking.'; return; }

  var allGood=true;
  blanks.forEach(function(k){
    var good=answerMatches(ss.inputs[k], step.a[k], step.accept, step.expr);
    ss.inputs['fs_'+k]=good?'correct':'wrong';
    if(!good) allGood=false;
  });

  if(allGood){
    ss.status='correct'; playSuccess();
    advanceStepOrFinish(item, slide);
  } else {
    ss.attempts=(ss.attempts||0)+1;
    if(ss.attempts>=2){
      ss.status='revealed'; playReveal();
      advanceStepOrFinish(item, slide);
    } else {
      playWrong();
      fb.className='feedback show retry';
      fb.innerHTML='<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'; __flash={c:'retry',h:'<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'};
      renderSlide();
      return;
    }
  }
  renderSlide();
}

function advanceStepOrFinish(item, slide){
  var total = slide.flat.length;
  var hasExpr = slide.flat.some(function(s){ return s.expr===true; });
  var hasFrac = slide.flat.some(function(s){ return ['fv','fe','fl','fm','fi','flist'].indexOf(s.expr)>=0; });
  if(item.curStep < total-1){
    item.curStep++;
  } else {
    var anyRevealed = item.stepStates.some(function(ss){ return ss.status==='revealed'; });
    item.status = anyRevealed ? 'revealed' : 'correct';
  }
}

/* ================= palette ================= */
var overlay=document.getElementById('overlay');
function statusOf(tabId,i){
  var ts=state.tabs[tabId];
  if(i>ts.maxReached) return 'locked';
  if(i===ts.idx) return 'current';
  return ts.items[i].status==='unanswered' ? 'locked' : ts.items[i].status;
}
function buildPalette(){
  var slides=SLIDES[activeTab];
  document.getElementById('paletteTitle').textContent = TAB_DEFS.find(function(t){return t.id===activeTab;}).label+' · Question palette';
  var body=document.getElementById('paletteBody');
  var html='';
  for(var i=0;i<slides.length;i++){
    html += '<div class="chip" data-status="'+statusOf(activeTab,i)+'" data-idx="'+i+'">'+(i+1)+'</div>';
  }
  body.innerHTML = html;
  body.querySelectorAll('.chip').forEach(function(chip){
    chip.addEventListener('click', function(){
      var i=parseInt(chip.dataset.idx,10);
      var ts=state.tabs[activeTab];
      if(i>ts.maxReached){ showToast('Finish the earlier questions to unlock this one.'); return; }
      ts.idx=i; closePalette(); renderSlide();
    });
  });
}
function openPalette(){ buildPalette(); overlay.classList.add('show'); }
function closePalette(){ overlay.classList.remove('show'); }
var toastTimer;
function showToast(msg){
  var t=document.getElementById('toast'); t.textContent=msg; t.classList.add('show');
  clearTimeout(toastTimer); toastTimer=setTimeout(function(){ t.classList.remove('show'); },2200);
}
document.getElementById('paletteFab').addEventListener('click', openPalette);
document.getElementById('paletteClose').addEventListener('click', closePalette);
overlay.addEventListener('click', function(e){ if(e.target===overlay) closePalette(); });

function updateFab(){
  var slides=SLIDES[activeTab];
  var done=state.tabs[activeTab].items.filter(function(it){ return it.status==='correct'||it.status==='revealed'||it.status==='skipped'; }).length;
  document.getElementById('fabBadge').textContent = done+'/'+slides.length;
}

/* ================= overall progress + finish ================= */
function updateChapterProgress(){
  var total=0, done=0;
  TAB_DEFS.forEach(function(td){
    state.tabs[td.id].items.forEach(function(it){
      total++;
      if(it.status==='correct'||it.status==='revealed'||it.status==='skipped') done++;
    });
  });
  var pct = total>0 ? Math.round((done/total)*100) : 0;
  document.getElementById('cpFill').style.width=pct+'%';
  document.getElementById('cpLabel').textContent=pct+'% complete';
}
function isSlideCorrect(tabId,i){
  var slide=SLIDES[tabId][i], item=state.tabs[tabId].items[i];
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice===slide.correct;
  return slide.flat.every(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).every(function(k){ return answerMatches(ss.inputs[k], step.a[k], step.accept, step.expr); });
  });
}
function isSlideAttempted(tabId,i){
  var slide=SLIDES[tabId][i], item=state.tabs[tabId].items[i];
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice!==undefined;
  return slide.flat.some(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).some(function(k){ return ss.inputs[k] && String(ss.inputs[k]).trim()!==''; });
  });
}
function slideLabel(slide){
  var t = slide.kind==='case' ? slide.title : (slide.kind==='ar' ? slide.a : (slide.p||slide.text||''));
  t = String(t);
  return t.length>90 ? t.slice(0,90)+'…' : t;
}
function slideAnswerText(slide, item, correctSide){
  if(slide.kind==='mcq'||slide.kind==='ar'){
    var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
    if(correctSide) return '('+LETTERS[slide.correct]+') '+opts[slide.correct];
    return item.choice!==undefined ? '('+LETTERS[item.choice]+') '+opts[item.choice] : '— not attempted —';
  }
  return slide.flat.map(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).map(function(k){
      return correctSide ? step.a[k] : (ss.inputs[k] || '—');
    }).join(', ');
  }).join('  |  ');
}

function renderFinished(){
  if(MODE==='quiz'){ renderQuizResults(); return; }
  var ts=state.tabs[activeTab];
  var correct=ts.items.filter(function(i){return i.status==='correct';}).length;
  var revealed=ts.items.filter(function(i){return i.status==='revealed';}).length;
  var skipped=ts.items.filter(function(i){return i.status==='skipped';}).length;
  var h='<div class="qcard done-card"><div class="big">✨</div><h2>Tab complete</h2>';
  h+='<p style="color:var(--ink-soft);font-size:14px;">You worked through all '+ts.items.length+' questions in this tab.</p>';
  if(!ts.recorded){ ts.recorded=true; addRecord('learning', activeTab, correct, revealed, skipped, ts.items.length); }
  h+='<div class="score-pills">'+
     '<span class="score-pill" style="background:var(--success-soft);color:var(--success);">'+correct+' correct</span>'+
     '<span class="score-pill" style="background:var(--danger-soft);color:var(--danger);">'+revealed+' revealed</span>'+
     '<span class="score-pill" style="background:var(--gold-soft);color:var(--retry-text);">'+skipped+' skipped</span></div>'+
     '<button class="btn btn-primary" id="btnReview">Review from question 1</button></div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  document.getElementById('btnReview').addEventListener('click', function(){ ts.idx=0; ts.recorded=false; renderSlide(); });
  updateChapterProgress(); saveState();
}

function renderQuizResults(){
  var ts=state.tabs[activeTab];
  var slides=SLIDES[activeTab];
  var correctCount=0, attemptedCount=0;
  var rowsHtml = slides.map(function(slide,i){
    var item=ts.items[i];
    var ok=isSlideCorrect(activeTab,i);
    var att=isSlideAttempted(activeTab,i);
    if(ok) correctCount++;
    if(att) attemptedCount++;
    var tagCls = ok?'ok':(att?'bad':'na');
    var tagText = ok?'Correct':(att?'Incorrect':'Not attempted');
    var row='<div class="review-row">';
    row+='<span class="review-tag '+tagCls+'">Q'+(i+1)+' · '+tagText+'</span>';
    row+='<div class="review-q">'+fr(esc(slideLabel(slide)))+'</div>';
    row+='<div class="review-ans"><b>Your answer:</b> '+fr(esc(slideAnswerText(slide,item,false)))+'</div>';
    if(!ok) row+='<div class="review-ans" style="color:var(--success);"><b>Correct answer:</b> '+fr(esc(slideAnswerText(slide,item,true)))+'</div>';
    if(slide.sol) row+='<details class="rev-sol"><summary>Show solution</summary>'+solutionHTML(slide)+'</details>';
    row+='</div>';
    return row;
  }).join('');

  addRecord('quiz', activeTab, correctCount, 0, 0, slides.length);
  var h='<div class="qcard done-card" style="text-align:left;">';
  h+='<div style="text-align:center;"><div class="big">🏁</div><h2>Quiz complete</h2>';
  h+='<p style="color:var(--ink-soft);font-size:14px;">'+correctCount+' / '+slides.length+' correct · '+attemptedCount+' attempted</p></div>';
  h+='<div style="margin-top:16px;">'+rowsHtml+'</div>';
  h+='<div style="text-align:center;margin-top:6px;"><button class="btn btn-primary" id="btnReview">Review from question 1</button></div>';
  h+='</div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  document.getElementById('btnReview').addEventListener('click', function(){ ts.idx=0; renderSlide(); });
  playSuccess();
  updateChapterProgress(); saveState();
}

/* ================= mode picker ================= */
function updateModePill(){
  var btn=document.getElementById('modePill');
  if(!btn) return;
  btn.textContent = MODE==='quiz' ? '📝 Quiz Mode · switch' : '📘 Learning Sheet · switch';
}
function showChrome(show){
  document.querySelector('.tabbar').style.display = show?'':'none';
  document.querySelector('.slide-progress').style.display = show?'':'none';
  document.querySelector('.navbar').style.display = show?'':'none';
  document.getElementById('paletteFab').style.display = show?'':'none';
}
function renderModePicker(){
  showChrome(false);
  var wrap=document.getElementById('wrap');
  wrap.innerHTML =
    '<div class="mode-pick">'+
      '<div class="mode-card" data-pick="learning"><div class="mode-icon">📘</div><h3>Learning Sheet</h3>'+
      '<p>Work through each question step by step with instant feedback — two tries, then the correct value is revealed right there so you can keep moving.</p></div>'+
      '<div class="mode-card" data-pick="quiz"><div class="mode-icon">📝</div><h3>Quiz Mode</h3>'+
      '<p>Attempt every question with no hints along the way. Your score and the full answer key are shown together once you finish the tab — just like the real exam.</p></div>'+
    '</div>';
  wrap.querySelectorAll('[data-pick]').forEach(function(card){
    card.addEventListener('click', function(){
      setMode(card.dataset.pick);
      document.getElementById('modePill').hidden=false;
      updateModePill();
      showChrome(true);
      buildTabbar();
      renderSlide();
    });
  });
}
document.getElementById('modePill').addEventListener('click', function(){
  if(!appState.mode){ return; }
  setMode(appState.mode==='quiz' ? 'learning' : 'quiz');
  updateModePill();
  showChrome(true);
  buildTabbar();
  renderSlide();
});

/* ================= boot ================= */
var _origRenderSlide = renderSlide;
renderSlide = function(){ _origRenderSlide(); updateChapterProgress(); updateModePill(); };

renderLogin();
})();
</script>
</body>
</html>
