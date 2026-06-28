<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover"/>
<title>🏰 حصون الإيمان — اللعبة</title>
<link rel="manifest" href="manifest.json"/>
<meta name="theme-color" content="#1B3A4B"/>
<meta name="apple-mobile-web-app-capable" content="yes"/>
<meta name="apple-mobile-web-app-title" content="حصون الإيمان"/>
<link rel="apple-touch-icon" href="icons/icon-192.png"/>
<link rel="preconnect" href="https://fonts.googleapis.com"/>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;900&display=swap" rel="stylesheet"/>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"/>
<style>
/* ================================================================
   GAME VARIABLES & RESET
================================================================ */
:root {
  --navy:       #0D1F2D;
  --navy2:      #1B3A4B;
  --gold:       #D4AF37;
  --gold2:      #F0D060;
  --gold3:      #fff0a0;
  --green:      #27AE60;
  --red:        #E74C3C;
  --purple:     #8E44AD;
  --blue:       #2980B9;
  --orange:     #E67E22;
  --white:      #FFFFFF;
  --bg:         #0a1520;
  --card:       rgba(255,255,255,0.06);
  --card2:      rgba(255,255,255,0.10);
  --border:     rgba(212,175,55,0.20);
  --font:       'Cairo', sans-serif;
  --radius:     18px;
  --radius-sm:  10px;
  --glow-gold:  0 0 20px rgba(212,175,55,0.4);
  --glow-green: 0 0 20px rgba(39,174,96,0.5);
  --trans:      all 0.3s ease;
}
*{margin:0;padding:0;box-sizing:border-box;-webkit-tap-highlight-color:transparent;}
html,body{height:100%;overflow:hidden;}
body{
  font-family:var(--font);
  background:var(--bg);
  color:var(--white);
  line-height:1.7;
  position:relative;
}

/* ================================================================
   STAR BACKGROUND ANIMATION
================================================================ */
#starfield{
  position:fixed;inset:0;pointer-events:none;z-index:0;overflow:hidden;
}
.star{
  position:absolute;border-radius:50%;
  background:rgba(212,175,55,0.6);
  animation:twinkle var(--dur,3s) ease-in-out infinite var(--delay,0s);
}
@keyframes twinkle{
  0%,100%{opacity:0.2;transform:scale(1);}
  50%{opacity:0.9;transform:scale(1.4);}
}

/* ================================================================
   SCREENS SYSTEM
================================================================ */
.screen{
  position:fixed;inset:0;z-index:10;
  display:none;flex-direction:column;align-items:center;
  overflow-y:auto;padding-bottom:30px;
  background:linear-gradient(160deg,#0a1520 0%,#0d2035 50%,#0a1520 100%);
}
.screen.active{display:flex;}

/* ================================================================
   HUD — TOP BAR
================================================================ */
#hud{
  position:fixed;top:0;left:0;right:0;z-index:100;
  display:none;
  background:rgba(13,31,45,0.95);
  backdrop-filter:blur(12px);
  padding:10px 16px;
  border-bottom:1px solid var(--border);
  align-items:center;gap:10px;
  flex-wrap:wrap;
}
#hud.visible{display:flex;}
.hud-stat{
  display:flex;align-items:center;gap:5px;
  background:rgba(255,255,255,0.06);
  padding:5px 12px;border-radius:30px;
  font-size:0.88rem;font-weight:700;
  border:1px solid rgba(255,255,255,0.08);
  white-space:nowrap;
}
.hud-stat .icon{font-size:1rem;}
#hud-xp .icon{color:#D4AF37;}
#hud-gems .icon{color:#3498DB;}
#hud-streak .icon{color:#E74C3C;}
#hud-level{
  background:linear-gradient(135deg,#D4AF37,#F0D060);
  color:#000;font-weight:900;
  padding:5px 14px;border-radius:30px;font-size:0.88rem;
}
.hud-xp-bar{
  flex:1;min-width:80px;
  height:6px;background:rgba(255,255,255,0.1);
  border-radius:4px;overflow:hidden;
}
.hud-xp-bar-fill{
  height:100%;background:linear-gradient(90deg,#D4AF37,#F0D060);
  border-radius:4px;transition:width 0.6s ease;
}
.hud-right{margin-right:auto;}

/* ================================================================
   PARTICLES & EFFECTS
================================================================ */
#particles-container{
  position:fixed;inset:0;pointer-events:none;z-index:200;overflow:hidden;
}
.particle{
  position:absolute;border-radius:50%;pointer-events:none;
  animation:particle-rise 1.2s ease-out forwards;
}
@keyframes particle-rise{
  0%{opacity:1;transform:translateY(0) scale(1);}
  100%{opacity:0;transform:translateY(-120px) scale(0.3);}
}
#floating-text{
  position:fixed;top:50%;left:50%;transform:translate(-50%,-50%);
  z-index:300;pointer-events:none;
  font-size:2.5rem;font-weight:900;
  color:var(--gold2);
  text-shadow:0 0 30px rgba(212,175,55,0.8);
  animation:float-up 1.4s ease-out forwards;
  display:none;
  text-align:center;
}
@keyframes float-up{
  0%{opacity:1;transform:translate(-50%,-50%) scale(0.5);}
  40%{opacity:1;transform:translate(-50%,-70%) scale(1.1);}
  100%{opacity:0;transform:translate(-50%,-100%) scale(0.9);}
}

/* ================================================================
   SCREEN 1: WELCOME / ONBOARDING
================================================================ */
#screen-welcome{
  justify-content:center;
  background:linear-gradient(160deg,#050d14 0%,#0d2035 60%,#050d14 100%);
}
.welcome-castle{
  font-size:5rem;margin-bottom:8px;
  animation:castle-glow 2s ease-in-out infinite alternate;
  filter:drop-shadow(0 0 20px rgba(212,175,55,0.6));
}
@keyframes castle-glow{
  from{filter:drop-shadow(0 0 15px rgba(212,175,55,0.4));}
  to{filter:drop-shadow(0 0 35px rgba(212,175,55,0.9));}
}
.welcome-title{
  font-size:2.4rem;font-weight:900;
  background:linear-gradient(135deg,#D4AF37,#F0D060,#D4AF37);
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;
  background-clip:text;
  text-align:center;margin-bottom:4px;
}
.welcome-sub{
  font-size:1rem;color:rgba(255,255,255,0.65);
  text-align:center;margin-bottom:30px;
}
.welcome-form{
  width:100%;max-width:340px;padding:0 20px;
  display:flex;flex-direction:column;gap:14px;
}
.input-group{position:relative;}
.input-group i{
  position:absolute;right:14px;top:50%;transform:translateY(-50%);
  color:var(--gold);font-size:1.1rem;
}
.game-input{
  width:100%;padding:14px 44px 14px 16px;
  background:rgba(255,255,255,0.07);
  border:1.5px solid var(--border);
  border-radius:var(--radius-sm);
  color:var(--white);font-family:var(--font);font-size:1rem;
  outline:none;transition:var(--trans);
}
.game-input:focus{border-color:var(--gold);box-shadow:0 0 0 3px rgba(212,175,55,0.15);}
.game-input::placeholder{color:rgba(255,255,255,0.35);}
.avatar-grid{
  display:grid;grid-template-columns:repeat(5,1fr);gap:8px;
}
.avatar-opt{
  font-size:1.8rem;text-align:center;
  padding:10px 4px;border-radius:var(--radius-sm);
  cursor:pointer;
  background:rgba(255,255,255,0.05);
  border:2px solid transparent;
  transition:var(--trans);
}
.avatar-opt:hover,.avatar-opt.chosen{
  border-color:var(--gold);
  background:rgba(212,175,55,0.15);
  transform:scale(1.12);
}
.age-grid{
  display:grid;grid-template-columns:repeat(4,1fr);gap:8px;
}
.age-opt{
  padding:10px 4px;text-align:center;
  border-radius:var(--radius-sm);cursor:pointer;
  background:rgba(255,255,255,0.05);
  border:2px solid transparent;
  font-size:0.95rem;font-weight:700;
  transition:var(--trans);
}
.age-opt:hover,.age-opt.chosen{
  border-color:var(--gold);
  background:rgba(212,175,55,0.15);
}
.label-small{
  font-size:0.82rem;color:rgba(212,175,55,0.8);
  margin-bottom:6px;font-weight:600;
}

/* ================================================================
   SCREEN 2: MAP (World Map)
================================================================ */
#screen-map{padding-top:80px;}
.map-header{
  text-align:center;padding:20px 16px 10px;width:100%;
}
.map-header h1{
  font-size:1.6rem;font-weight:900;color:var(--gold);
}
.player-greeting{
  font-size:0.95rem;color:rgba(255,255,255,0.7);margin-top:4px;
}
.map-grid{
  width:100%;max-width:480px;padding:10px 16px 20px;
  display:flex;flex-direction:column;gap:14px;
}
.fortress-card{
  background:var(--card);
  border:1.5px solid var(--border);
  border-radius:var(--radius);
  padding:18px 16px;
  cursor:pointer;
  transition:var(--trans);
  position:relative;overflow:hidden;
  display:flex;align-items:center;gap:16px;
}
.fortress-card::before{
  content:'';position:absolute;inset:0;
  background:linear-gradient(135deg,transparent,rgba(212,175,55,0.04));
  pointer-events:none;
}
.fortress-card:hover,.fortress-card:active{
  transform:translateY(-3px);
  border-color:var(--gold);
  box-shadow:0 8px 30px rgba(0,0,0,0.3),var(--glow-gold);
}
.fortress-card.locked{
  opacity:0.5;cursor:not-allowed;
  filter:grayscale(0.6);
}
.fortress-card.locked:hover{transform:none;box-shadow:none;border-color:var(--border);}
.fortress-card.completed{
  border-color:var(--green);
  box-shadow:var(--glow-green);
}
.fortress-icon-wrap{
  width:60px;height:60px;flex-shrink:0;
  background:rgba(255,255,255,0.07);
  border-radius:14px;
  display:flex;align-items:center;justify-content:center;
  font-size:1.8rem;
  border:1.5px solid rgba(255,255,255,0.1);
  position:relative;
}
.fortress-icon-wrap .lock-badge{
  position:absolute;top:-6px;right:-6px;
  background:#555;border-radius:50%;
  width:20px;height:20px;
  display:flex;align-items:center;justify-content:center;
  font-size:0.6rem;
}
.fortress-info{flex:1;min-width:0;}
.fortress-name{
  font-size:1.05rem;font-weight:900;
  color:var(--white);margin-bottom:3px;
}
.fortress-meta{
  font-size:0.8rem;color:rgba(255,255,255,0.55);
  margin-bottom:8px;
}
.fortress-prog-wrap{
  height:5px;background:rgba(255,255,255,0.1);
  border-radius:4px;overflow:hidden;margin-bottom:4px;
}
.fortress-prog-fill{
  height:100%;border-radius:4px;
  transition:width 0.7s ease;
}
.fortress-pct{
  font-size:0.75rem;color:rgba(255,255,255,0.5);
}
.fortress-badge{
  width:32px;flex-shrink:0;
  display:flex;align-items:center;justify-content:center;
  font-size:1.4rem;
}
.chapter-number{
  position:absolute;top:10px;left:14px;
  font-size:0.7rem;font-weight:700;
  color:rgba(212,175,55,0.6);
  letter-spacing:1px;
}

/* ================================================================
   SCREEN 3: LESSONS LIST
================================================================ */
#screen-lessons{padding-top:80px;}
.back-bar{
  width:100%;padding:14px 16px;
  display:flex;align-items:center;gap:12px;
}
.btn-back-game{
  background:rgba(255,255,255,0.08);
  border:1px solid var(--border);
  color:var(--white);padding:8px 16px;
  border-radius:30px;font-family:var(--font);
  font-size:0.9rem;font-weight:700;cursor:pointer;
  display:flex;align-items:center;gap:6px;
  transition:var(--trans);
}
.btn-back-game:hover{background:rgba(255,255,255,0.14);}
.lesson-fortress-title{
  font-size:1.1rem;font-weight:900;color:var(--gold);
}
.lessons-list{
  width:100%;max-width:480px;padding:4px 16px 20px;
  display:flex;flex-direction:column;gap:10px;
}
.lesson-row{
  background:var(--card);
  border:1.5px solid var(--border);
  border-radius:var(--radius-sm);
  padding:14px 16px;
  display:flex;align-items:center;gap:14px;
  cursor:pointer;transition:var(--trans);
  position:relative;overflow:hidden;
}
.lesson-row.done{border-color:rgba(39,174,96,0.5);}
.lesson-row.locked{opacity:0.45;cursor:not-allowed;}
.lesson-row:not(.locked):hover{
  border-color:var(--gold);
  transform:translateX(-4px);
  box-shadow:4px 0 20px rgba(0,0,0,0.3);
}
.lesson-num{
  width:38px;height:38px;flex-shrink:0;
  border-radius:50%;
  display:flex;align-items:center;justify-content:center;
  font-weight:900;font-size:0.9rem;
  background:rgba(255,255,255,0.08);
  border:1.5px solid rgba(255,255,255,0.15);
}
.lesson-row.done .lesson-num{
  background:var(--green);border-color:var(--green);
}
.lesson-row.current .lesson-num{
  background:var(--gold);color:#000;border-color:var(--gold);
  animation:pulse-num 1.5s ease infinite;
}
@keyframes pulse-num{
  0%,100%{box-shadow:0 0 0 0 rgba(212,175,55,0.5);}
  50%{box-shadow:0 0 0 8px rgba(212,175,55,0);}
}
.lesson-info{flex:1;}
.lesson-title-row{
  font-size:0.95rem;font-weight:700;
  color:var(--white);margin-bottom:3px;
}
.lesson-xp-tag{
  display:inline-flex;align-items:center;gap:4px;
  font-size:0.75rem;color:var(--gold);
  background:rgba(212,175,55,0.1);
  padding:2px 10px;border-radius:20px;
}
.lesson-status-icon{font-size:1.3rem;}

/* ================================================================
   SCREEN 4: LESSON CONTENT READER
================================================================ */
#screen-lesson{padding-top:80px;}
.lesson-content-wrap{
  width:100%;max-width:600px;padding:10px 16px 20px;
}
.lesson-card-game{
  background:var(--card);
  border:1px solid var(--border);
  border-radius:var(--radius);
  margin-bottom:14px;overflow:hidden;
}
.section-header-game{
  padding:12px 16px;
  display:flex;align-items:center;gap:10px;
  border-bottom:1px solid rgba(255,255,255,0.06);
}
.section-icon-circle{
  width:36px;height:36px;flex-shrink:0;
  border-radius:50%;
  display:flex;align-items:center;justify-content:center;
  font-size:1rem;font-weight:900;
}
.section-type-label{
  font-size:0.85rem;font-weight:700;color:var(--gold);
}
.section-body{
  padding:14px 16px;
  font-size:0.95rem;line-height:1.85;
  color:rgba(255,255,255,0.88);
}
.section-body p{margin-bottom:10px;}
/* Quran style */
.quran-text{
  font-size:1.05rem;
  color:var(--gold2);
  background:rgba(212,175,55,0.07);
  border-right:3px solid var(--gold);
  padding:10px 14px;
  border-radius:0 8px 8px 0;
  margin:8px 0;line-height:2;
}
/* Hadith style */
.hadith-text{
  font-size:0.95rem;
  color:#a8d8ea;
  background:rgba(41,128,185,0.08);
  border-right:3px solid #2980B9;
  padding:10px 14px;
  border-radius:0 8px 8px 0;
  margin:8px 0;
}
.source-tag{
  font-size:0.78rem;
  color:rgba(255,255,255,0.45);
  font-style:italic;margin-top:4px;
  display:block;
}
/* Read Complete Button */
.btn-read-done{
  display:flex;align-items:center;justify-content:center;gap:10px;
  width:100%;padding:16px;margin-top:10px;
  background:linear-gradient(135deg,#1B3A4B,#0D2035);
  border:2px solid var(--gold);
  border-radius:var(--radius);
  color:var(--gold);font-family:var(--font);font-size:1.1rem;font-weight:900;
  cursor:pointer;transition:var(--trans);
}
.btn-read-done:hover{
  background:linear-gradient(135deg,var(--gold),var(--gold2));
  color:#000;box-shadow:var(--glow-gold);
}

/* ================================================================
   SCREEN 5: QUIZ
================================================================ */
#screen-quiz{justify-content:flex-start;padding-top:80px;}
.quiz-wrap{
  width:100%;max-width:480px;
  padding:10px 16px 30px;
}
.quiz-progress-bar{
  height:6px;background:rgba(255,255,255,0.1);
  border-radius:4px;overflow:hidden;margin-bottom:20px;
}
.quiz-progress-fill{
  height:100%;background:linear-gradient(90deg,var(--gold),var(--gold2));
  border-radius:4px;transition:width 0.4s ease;
}
.quiz-q-num{
  font-size:0.8rem;color:rgba(212,175,55,0.7);
  margin-bottom:6px;font-weight:600;letter-spacing:1px;
}
.quiz-question{
  font-size:1.15rem;font-weight:700;
  color:var(--white);margin-bottom:20px;
  line-height:1.7;
  background:var(--card);
  border:1px solid var(--border);
  border-radius:var(--radius);
  padding:18px 16px;
}
.quiz-options{
  display:flex;flex-direction:column;gap:10px;
  margin-bottom:16px;
}
.quiz-opt{
  padding:14px 16px;
  background:var(--card);
  border:1.5px solid var(--border);
  border-radius:var(--radius-sm);
  color:var(--white);font-family:var(--font);font-size:0.97rem;font-weight:600;
  cursor:pointer;transition:var(--trans);
  text-align:right;
  display:flex;align-items:center;gap:10px;
}
.quiz-opt:hover:not(:disabled){
  border-color:var(--gold);
  background:rgba(212,175,55,0.08);
  transform:translateX(-4px);
}
.quiz-opt.correct{
  border-color:var(--green);
  background:rgba(39,174,96,0.15);
  animation:correct-pulse 0.4s ease;
}
.quiz-opt.wrong{
  border-color:var(--red);
  background:rgba(231,76,60,0.12);
  animation:shake 0.4s ease;
}
@keyframes correct-pulse{
  0%{transform:scale(1);}50%{transform:scale(1.03);}100%{transform:scale(1);}
}
@keyframes shake{
  0%,100%{transform:translateX(0);}
  25%{transform:translateX(-8px);}75%{transform:translateX(8px);}
}
.opt-circle{
  width:30px;height:30px;flex-shrink:0;
  border-radius:50%;
  border:1.5px solid rgba(255,255,255,0.2);
  display:flex;align-items:center;justify-content:center;
  font-weight:900;font-size:0.85rem;
  background:rgba(255,255,255,0.05);
}
.quiz-feedback{
  padding:14px 16px;
  border-radius:var(--radius-sm);
  font-size:0.95rem;font-weight:600;
  margin-bottom:14px;
  display:none;
  line-height:1.6;
}
.quiz-feedback.correct-fb{
  background:rgba(39,174,96,0.12);
  border:1px solid rgba(39,174,96,0.3);
  color:#7defa5;
}
.quiz-feedback.wrong-fb{
  background:rgba(231,76,60,0.1);
  border:1px solid rgba(231,76,60,0.3);
  color:#f1a0a0;
}
.btn-next-q{
  display:flex;align-items:center;justify-content:center;gap:8px;
  width:100%;padding:15px;
  background:linear-gradient(135deg,var(--gold),var(--gold2));
  color:#000;border:none;border-radius:var(--radius);
  font-family:var(--font);font-size:1.05rem;font-weight:900;
  cursor:pointer;transition:var(--trans);
  display:none;
}
.btn-next-q:hover{transform:translateY(-2px);box-shadow:var(--glow-gold);}
.quiz-timer{
  text-align:center;font-size:2rem;font-weight:900;
  color:var(--gold);margin-bottom:10px;
  font-variant-numeric:tabular-nums;
}
.quiz-timer.urgent{color:var(--red);animation:blink 0.5s ease infinite alternate;}
@keyframes blink{from{opacity:1;}to{opacity:0.4;};}

/* ================================================================
   SCREEN 6: LESSON RESULT
================================================================ */
#screen-result{justify-content:center;}
.result-wrap{
  text-align:center;padding:30px 20px;
  max-width:360px;width:100%;
}
.result-emoji{
  font-size:4.5rem;margin-bottom:10px;
  animation:bounce-in 0.6s cubic-bezier(0.175,0.885,0.32,1.275);
}
@keyframes bounce-in{
  0%{transform:scale(0);}60%{transform:scale(1.2);}100%{transform:scale(1);}
}
.result-title{
  font-size:1.8rem;font-weight:900;
  background:linear-gradient(135deg,var(--gold),var(--gold2));
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;
  background-clip:text;
  margin-bottom:6px;
}
.result-subtitle{
  font-size:0.95rem;color:rgba(255,255,255,0.6);
  margin-bottom:22px;
}
.result-stats{
  display:grid;grid-template-columns:repeat(3,1fr);gap:10px;
  margin-bottom:22px;
}
.result-stat-box{
  background:var(--card);
  border:1px solid var(--border);
  border-radius:var(--radius-sm);
  padding:14px 8px;text-align:center;
}
.result-stat-box .stat-val{
  font-size:1.6rem;font-weight:900;color:var(--gold);
}
.result-stat-box .stat-lbl{
  font-size:0.75rem;color:rgba(255,255,255,0.5);margin-top:3px;
}
.stars-row{
  display:flex;justify-content:center;gap:6px;
  font-size:2.2rem;margin-bottom:20px;
}
.star-item{
  animation:star-pop 0.3s ease forwards;
  opacity:0;
}
.star-item:nth-child(1){animation-delay:0.2s;}
.star-item:nth-child(2){animation-delay:0.5s;}
.star-item:nth-child(3){animation-delay:0.8s;}
@keyframes star-pop{
  0%{opacity:0;transform:scale(0) rotate(-30deg);}
  100%{opacity:1;transform:scale(1) rotate(0);}
}
.result-badge{
  display:inline-flex;align-items:center;gap:8px;
  background:rgba(212,175,55,0.1);
  border:1px solid rgba(212,175,55,0.3);
  padding:8px 20px;border-radius:30px;
  font-size:0.9rem;color:var(--gold);font-weight:700;
  margin-bottom:20px;
}
.result-btns{display:flex;flex-direction:column;gap:10px;}
.btn-primary-game{
  padding:15px;border-radius:var(--radius);border:none;
  background:linear-gradient(135deg,var(--gold),var(--gold2));
  color:#000;font-family:var(--font);font-size:1rem;font-weight:900;
  cursor:pointer;transition:var(--trans);
  display:flex;align-items:center;justify-content:center;gap:8px;
}
.btn-primary-game:hover{transform:translateY(-2px);box-shadow:var(--glow-gold);}
.btn-secondary-game{
  padding:13px;border-radius:var(--radius);
  border:1.5px solid var(--border);
  background:transparent;
  color:var(--white);font-family:var(--font);font-size:0.95rem;font-weight:700;
  cursor:pointer;transition:var(--trans);
  display:flex;align-items:center;justify-content:center;gap:8px;
}
.btn-secondary-game:hover{border-color:var(--gold);color:var(--gold);}

/* ================================================================
   SCREEN 7: FORTRESS COMPLETE
================================================================ */
#screen-fortress-win{justify-content:center;}
.fortress-win-wrap{
  text-align:center;padding:30px 20px;max-width:360px;width:100%;
}
.win-castle{
  font-size:5rem;margin-bottom:10px;
  animation:castle-float 2s ease-in-out infinite;
  filter:drop-shadow(0 0 30px rgba(212,175,55,0.8));
}
@keyframes castle-float{
  0%,100%{transform:translateY(0);}
  50%{transform:translateY(-12px);}
}
.win-title{
  font-size:1.9rem;font-weight:900;color:var(--gold);
  margin-bottom:6px;
}
.win-sub{font-size:1rem;color:rgba(255,255,255,0.65);margin-bottom:24px;}
.badge-earned{
  background:linear-gradient(135deg,rgba(212,175,55,0.15),rgba(212,175,55,0.05));
  border:2px solid var(--gold);
  border-radius:var(--radius);
  padding:20px 16px;margin-bottom:22px;
  position:relative;overflow:hidden;
}
.badge-earned::before{
  content:'✦';position:absolute;top:8px;right:12px;
  color:rgba(212,175,55,0.3);font-size:1.5rem;
}
.badge-icon{font-size:3rem;margin-bottom:8px;}
.badge-name{font-size:1.1rem;font-weight:900;color:var(--gold);}
.badge-desc{font-size:0.82rem;color:rgba(255,255,255,0.55);margin-top:4px;}

/* ================================================================
   SCREEN 8: PROFILE / TROPHY ROOM
================================================================ */
#screen-profile{padding-top:80px;}
.profile-wrap{width:100%;max-width:480px;padding:10px 16px 30px;}
.profile-hero{
  background:linear-gradient(135deg,rgba(212,175,55,0.1),rgba(212,175,55,0.03));
  border:1px solid var(--border);
  border-radius:var(--radius);
  padding:24px 16px;text-align:center;margin-bottom:16px;
}
.profile-avatar{font-size:3.5rem;margin-bottom:6px;}
.profile-name{font-size:1.4rem;font-weight:900;color:var(--gold);}
.profile-level-tag{
  display:inline-block;
  background:linear-gradient(135deg,var(--gold),var(--gold2));
  color:#000;font-weight:900;font-size:0.85rem;
  padding:4px 16px;border-radius:20px;margin:6px 0;
}
.profile-xp-bar-wrap{
  height:8px;background:rgba(255,255,255,0.1);
  border-radius:4px;overflow:hidden;margin:10px 0 4px;
}
.profile-xp-bar-fill{
  height:100%;border-radius:4px;
  background:linear-gradient(90deg,var(--gold),var(--gold2));
  transition:width 0.8s ease;
}
.profile-xp-label{font-size:0.8rem;color:rgba(255,255,255,0.45);}
.stats-grid{
  display:grid;grid-template-columns:repeat(2,1fr);gap:10px;
  margin-bottom:16px;
}
.stat-card{
  background:var(--card);border:1px solid var(--border);
  border-radius:var(--radius-sm);
  padding:16px;text-align:center;
}
.stat-card .s-icon{font-size:1.6rem;margin-bottom:4px;}
.stat-card .s-val{font-size:1.4rem;font-weight:900;color:var(--gold);}
.stat-card .s-lbl{font-size:0.75rem;color:rgba(255,255,255,0.45);margin-top:2px;}
.badges-section h3{
  font-size:1rem;font-weight:700;color:var(--gold);
  margin-bottom:12px;
}
.badges-grid{
  display:grid;grid-template-columns:repeat(4,1fr);gap:8px;
}
.badge-cell{
  background:var(--card);border:1px solid var(--border);
  border-radius:var(--radius-sm);
  padding:12px 4px;text-align:center;
  position:relative;
}
.badge-cell .b-icon{font-size:1.8rem;}
.badge-cell .b-name{font-size:0.65rem;color:rgba(255,255,255,0.5);margin-top:4px;}
.badge-cell.locked-badge{filter:grayscale(1);opacity:0.35;}
.badge-cell.locked-badge .b-icon::after{
  content:'🔒';position:absolute;
  bottom:28px;right:50%;transform:translateX(50%);
  font-size:0.8rem;
}

/* ================================================================
   MODAL OVERLAY
================================================================ */
.modal-overlay{
  position:fixed;inset:0;z-index:500;
  background:rgba(0,0,0,0.8);backdrop-filter:blur(6px);
  display:none;align-items:center;justify-content:center;padding:20px;
}
.modal-overlay.open{display:flex;}
.modal-box{
  background:linear-gradient(160deg,#0d2035,#0a1520);
  border:1.5px solid var(--border);
  border-radius:var(--radius);
  padding:30px 22px;text-align:center;
  max-width:340px;width:100%;
  animation:modal-in 0.35s cubic-bezier(0.175,0.885,0.32,1.275);
}
@keyframes modal-in{
  from{transform:scale(0.7);opacity:0;}
  to{transform:scale(1);opacity:1;}
}
.modal-box h2{font-size:1.4rem;font-weight:900;color:var(--gold);margin-bottom:8px;}
.modal-box p{font-size:0.92rem;color:rgba(255,255,255,0.65);margin-bottom:20px;}

/* ================================================================
   BOTTOM NAV
================================================================ */
#bottom-nav{
  position:fixed;bottom:0;left:0;right:0;z-index:100;
  display:none;
  background:rgba(10,21,32,0.97);
  backdrop-filter:blur(12px);
  border-top:1px solid var(--border);
  padding:8px 0;padding-bottom:calc(8px + env(safe-area-inset-bottom));
}
#bottom-nav.visible{display:flex;justify-content:space-around;align-items:center;}
.nav-item{
  display:flex;flex-direction:column;align-items:center;gap:3px;
  padding:6px 16px;cursor:pointer;
  color:rgba(255,255,255,0.4);font-size:0.7rem;font-weight:600;
  transition:var(--trans);border-radius:8px;
}
.nav-item i{font-size:1.3rem;}
.nav-item.active,.nav-item:hover{color:var(--gold);}
.nav-item.active i{
  filter:drop-shadow(0 0 6px rgba(212,175,55,0.7));
}

/* ================================================================
   UTILITY
================================================================ */
.gold-text{color:var(--gold);}
.center{text-align:center;}
.mt-10{margin-top:10px;}
.w100{width:100%;}
.btn-icon-text{display:flex;align-items:center;gap:8px;justify-content:center;}
.divider{height:1px;background:var(--border);margin:14px 0;}

/* Section type colors */
.st-paragraph .section-icon-circle{background:rgba(212,175,55,0.15);color:var(--gold);}
.st-quote .section-icon-circle{background:rgba(41,128,185,0.15);color:#60b8e8;}
.st-explanation .section-icon-circle{background:rgba(142,68,173,0.15);color:#c39bd3;}
.st-application .section-icon-circle{background:rgba(39,174,96,0.15);color:#82e0aa;}
.st-benefit .section-icon-circle{background:rgba(230,126,34,0.15);color:#f0b27a;}

/* Smooth scrolling for content screen */
#screen-lesson{overflow-y:auto;}
.screen{-webkit-overflow-scrolling:touch;}

/* XP popup */
.xp-popup{
  position:fixed;z-index:400;
  pointer-events:none;
  font-size:1.2rem;font-weight:900;
  color:var(--gold2);
  text-shadow:0 2px 8px rgba(0,0,0,0.5);
  animation:xp-float 1.5s ease-out forwards;
}
@keyframes xp-float{
  0%{opacity:1;transform:translateY(0) scale(1);}
  100%{opacity:0;transform:translateY(-60px) scale(0.8);}
}

/* Streak flame */
.streak-flame{
  animation:flame-flicker 0.8s ease-in-out infinite alternate;
}
@keyframes flame-flicker{
  from{filter:hue-rotate(-10deg) brightness(1);}
  to{filter:hue-rotate(10deg) brightness(1.3);}
}

/* Confetti */
.confetti-piece{
  position:fixed;pointer-events:none;z-index:600;
  width:8px;height:8px;border-radius:2px;
  animation:confetti-fall var(--dur,2s) ease-in var(--delay,0s) forwards;
}
@keyframes confetti-fall{
  0%{transform:translateY(-20px) rotate(0deg);opacity:1;}
  100%{transform:translateY(100vh) rotate(720deg);opacity:0;}
}

/* Responsive tweaks */
@media(max-width:380px){
  .welcome-title{font-size:1.9rem;}
  .avatar-opt{font-size:1.4rem;}
  .fortress-icon-wrap{width:50px;height:50px;font-size:1.5rem;}
}


/* ===== ADMIN COURSE BUILDER ===== */
.admin-wrap{
  width:100%;max-width:980px;margin:0 auto;padding:82px 16px 110px;color:var(--text);
}
.admin-hero{
  background:linear-gradient(135deg,rgba(212,175,55,.16),rgba(46,139,87,.12));
  border:1px solid rgba(212,175,55,.25);border-radius:18px;padding:18px;margin-bottom:14px;
}
.admin-hero h2{margin:0 0 6px;font-size:1.35rem;color:var(--gold);}
.admin-hero p{margin:0;color:rgba(255,255,255,.72);font-size:.9rem;line-height:1.7;}
.admin-grid{display:grid;grid-template-columns:1fr 1fr;gap:14px;align-items:start;}
.admin-panel{
  background:rgba(13,31,45,.82);border:1px solid rgba(255,255,255,.1);border-radius:16px;padding:16px;
  box-shadow:0 12px 30px rgba(0,0,0,.18);
}
.admin-panel.full{grid-column:1/-1;}
.admin-panel h3{margin:0 0 12px;color:#fff;font-size:1rem;display:flex;gap:8px;align-items:center;}
.admin-field{margin-bottom:10px;}
.admin-field label{display:block;font-size:.78rem;color:rgba(255,255,255,.68);margin-bottom:5px;font-weight:800;}
.admin-field input,.admin-field select,.admin-field textarea{
  width:100%;border:1px solid rgba(255,255,255,.14);background:rgba(255,255,255,.08);color:#fff;
  border-radius:10px;padding:10px 12px;font-family:var(--font);font-size:.9rem;outline:none;
}
.admin-field select option{color:#111;}
.admin-field textarea{min-height:120px;resize:vertical;line-height:1.7;}
.admin-field .hint{font-size:.7rem;color:rgba(255,255,255,.46);margin-top:4px;line-height:1.5;}
.admin-actions{display:flex;gap:8px;flex-wrap:wrap;margin-top:8px;}
.admin-btn{
  border:0;border-radius:999px;padding:10px 14px;font-family:var(--font);font-weight:900;cursor:pointer;
  display:inline-flex;align-items:center;gap:7px;transition:transform .2s ease,filter .2s ease;
}
.admin-btn:hover{transform:translateY(-1px);filter:brightness(1.08);}
.admin-btn.primary{background:var(--gold);color:#111;}
.admin-btn.secondary{background:rgba(255,255,255,.12);color:#fff;border:1px solid rgba(255,255,255,.1);}
.admin-btn.danger{background:#c0392b;color:#fff;}
.admin-list{display:grid;gap:10px;}
.admin-course-item{border:1px solid rgba(255,255,255,.1);border-radius:14px;padding:12px;background:rgba(255,255,255,.055);}
.admin-course-head{display:flex;align-items:center;justify-content:space-between;gap:10px;margin-bottom:8px;}
.admin-course-title{display:flex;align-items:center;gap:8px;color:#fff;font-weight:900;}
.admin-course-title .admin-emoji{font-size:1.45rem;}
.admin-course-meta{font-size:.75rem;color:rgba(255,255,255,.55);}
.admin-lesson-row{display:flex;align-items:center;justify-content:space-between;gap:10px;padding:8px 10px;border-radius:10px;background:rgba(0,0,0,.16);margin-top:6px;}
.admin-lesson-row span{font-size:.82rem;color:rgba(255,255,255,.82);}
.admin-small-btn{border:0;border-radius:999px;padding:6px 9px;font-family:var(--font);font-weight:800;cursor:pointer;background:rgba(255,255,255,.12);color:#fff;}
.admin-small-btn.danger{background:rgba(192,57,43,.9);}
.admin-message{display:none;margin-top:10px;border-radius:10px;padding:9px 12px;font-weight:800;font-size:.82rem;}
.admin-message.ok{display:block;background:rgba(39,174,96,.16);color:#7bed9f;border:1px solid rgba(39,174,96,.35);}
.admin-message.err{display:block;background:rgba(231,76,60,.16);color:#ff9b91;border:1px solid rgba(231,76,60,.35);}
@media(max-width:760px){.admin-grid{grid-template-columns:1fr}.admin-wrap{padding-left:12px;padding-right:12px}.admin-course-head{align-items:flex-start;flex-direction:column}.admin-actions{flex-direction:column}.admin-btn{justify-content:center;width:100%;}}

</style>
</head>
<body>

<!-- ============================================================
     BACKGROUND STARS
============================================================ -->
<div id="starfield"></div>
<div id="particles-container"></div>
<div id="floating-text"></div>

<!-- ============================================================
     HUD
============================================================ -->
<div id="hud">
  <div id="hud-level">⭐ مستوى 1</div>
  <div class="hud-stat" id="hud-xp">
    <span class="icon">✨</span><span id="hud-xp-val">0</span> XP
  </div>
  <div class="hud-xp-bar">
    <div class="hud-xp-bar-fill" id="hud-xp-bar" style="width:0%"></div>
  </div>
  <div class="hud-stat" id="hud-gems">
    <span class="icon">💎</span><span id="hud-gems-val">0</span>
  </div>
  <div class="hud-stat" id="hud-streak">
    <span class="icon streak-flame">🔥</span><span id="hud-streak-val">0</span>
  </div>
</div>

<!-- ============================================================
     BOTTOM NAV
============================================================ -->
<div id="bottom-nav">
  <div class="nav-item active" onclick="showMap()" id="nav-map">
    <i class="fas fa-map"></i><span>الخريطة</span>
  </div>
  <div class="nav-item" onclick="showProfile()" id="nav-profile">
    <i class="fas fa-trophy"></i><span>بطلي</span>
  </div>
  <div class="nav-item" onclick="showAdmin()" id="nav-admin">
    <i class="fas fa-pen-to-square"></i><span>إدارة</span>
  </div>
</div>

<!-- ============================================================
     SCREENS
============================================================ -->

<!-- SCREEN 1: WELCOME -->
<div class="screen active" id="screen-welcome">
  <div style="padding:40px 0 0;display:flex;flex-direction:column;align-items:center;width:100%;max-width:380px;padding:40px 20px;">
    <div class="welcome-castle">🏰</div>
    <h1 class="welcome-title">حصون الإيمان</h1>
    <p class="welcome-sub">رحلة الفارس المؤمن — ابن حصنك الآن!</p>
    
    <div class="welcome-form" id="welcome-form">
      <div>
        <div class="label-small">🦸 اختر اسم فارسك</div>
        <div class="input-group">
          <i class="fas fa-user-shield"></i>
          <input class="game-input" id="player-name" type="text" placeholder="اسمك هنا..." maxlength="20"/>
        </div>
      </div>

      <div>
        <div class="label-small">🎭 اختر شخصيتك</div>
        <div class="avatar-grid" id="avatar-grid">
          <div class="avatar-opt" data-av="🦁" onclick="chooseAvatar(this)">🦁</div>
          <div class="avatar-opt" data-av="🦅" onclick="chooseAvatar(this)">🦅</div>
          <div class="avatar-opt" data-av="⚔️" onclick="chooseAvatar(this)">⚔️</div>
          <div class="avatar-opt" data-av="🌟" onclick="chooseAvatar(this)">🌟</div>
          <div class="avatar-opt" data-av="🛡️" onclick="chooseAvatar(this)">🛡️</div>
          <div class="avatar-opt" data-av="🌙" onclick="chooseAvatar(this)">🌙</div>
          <div class="avatar-opt" data-av="🏹" onclick="chooseAvatar(this)">🏹</div>
          <div class="avatar-opt" data-av="🌺" onclick="chooseAvatar(this)">🌺</div>
          <div class="avatar-opt" data-av="🦋" onclick="chooseAvatar(this)">🦋</div>
          <div class="avatar-opt" data-av="🌹" onclick="chooseAvatar(this)">🌹</div>
        </div>
      </div>

      <div>
        <div class="label-small">🎂 عمرك</div>
        <div class="age-grid" id="age-grid">
          <div class="age-opt" data-age="9" onclick="chooseAge(this)">9</div>
          <div class="age-opt" data-age="10" onclick="chooseAge(this)">10</div>
          <div class="age-opt" data-age="11" onclick="chooseAge(this)">11</div>
          <div class="age-opt" data-age="12" onclick="chooseAge(this)">12</div>
          <div class="age-opt" data-age="13" onclick="chooseAge(this)">13</div>
          <div class="age-opt" data-age="14" onclick="chooseAge(this)">14</div>
          <div class="age-opt" data-age="15" onclick="chooseAge(this)">15</div>
          <div class="age-opt" data-age="16+" onclick="chooseAge(this)">16+</div>
        </div>
      </div>

      <button class="btn-primary-game w100" onclick="startGame()" style="margin-top:6px;">
        <span>🚀 ابدأ المغامرة!</span>
      </button>
    </div>
  </div>
</div>

<!-- SCREEN 2: MAP -->
<div class="screen" id="screen-map">
  <div class="map-header">
    <h1>🗺️ خريطة الحصون</h1>
    <p class="player-greeting" id="map-greeting">أهلاً بك يا فارس!</p>
  </div>
  <div class="map-grid" id="map-grid"></div>
</div>

<!-- SCREEN 3: LESSONS LIST -->
<div class="screen" id="screen-lessons">
  <div class="back-bar">
    <button class="btn-back-game" onclick="showMap()">
      <i class="fas fa-arrow-right"></i> الخريطة
    </button>
    <span class="lesson-fortress-title" id="lesson-fortress-title">الحصن الأول</span>
  </div>
  <div class="lessons-list" id="lessons-list"></div>
</div>

<!-- SCREEN 4: LESSON READER -->
<div class="screen" id="screen-lesson">
  <div class="back-bar">
    <button class="btn-back-game" id="lesson-back-btn">
      <i class="fas fa-arrow-right"></i> عودة
    </button>
    <span class="lesson-fortress-title" id="lesson-reading-title">الدرس</span>
  </div>
  <div class="lesson-content-wrap" id="lesson-content-wrap">
    <!-- dynamic -->
  </div>
</div>

<!-- SCREEN 5: QUIZ -->
<div class="screen" id="screen-quiz">
  <div class="quiz-wrap">
    <div class="quiz-timer" id="quiz-timer">⏱ 20</div>
    <div class="quiz-progress-bar">
      <div class="quiz-progress-fill" id="quiz-prog-fill" style="width:0%"></div>
    </div>
    <div class="quiz-q-num" id="quiz-q-num">السؤال 1 من 3</div>
    <div class="quiz-question" id="quiz-question"></div>
    <div class="quiz-options" id="quiz-options"></div>
    <div class="quiz-feedback" id="quiz-feedback"></div>
    <button class="btn-next-q" id="btn-next-q" onclick="nextQuestion()">
      <span id="next-q-label">التالي</span> <i class="fas fa-arrow-left"></i>
    </button>
  </div>
</div>

<!-- SCREEN 6: LESSON RESULT -->
<div class="screen" id="screen-result">
  <div class="result-wrap">
    <div class="result-emoji" id="result-emoji">🌟</div>
    <h2 class="result-title" id="result-title">أحسنت!</h2>
    <p class="result-subtitle" id="result-subtitle">أكملت الدرس بنجاح</p>
    <div class="stars-row" id="result-stars"></div>
    <div class="result-stats">
      <div class="result-stat-box">
        <div class="stat-val" id="res-xp">+50</div>
        <div class="stat-lbl">نقاط XP</div>
      </div>
      <div class="result-stat-box">
        <div class="stat-val" id="res-correct">3/3</div>
        <div class="stat-lbl">إجابات صحيحة</div>
      </div>
      <div class="result-stat-box">
        <div class="stat-val" id="res-gems">+2</div>
        <div class="stat-lbl">جواهر</div>
      </div>
    </div>
    <div class="result-badge" id="result-badge" style="display:none"></div>
    <div class="result-btns">
      <button class="btn-primary-game" id="btn-result-next" onclick="goNextLesson()">
        <i class="fas fa-arrow-left"></i> الدرس التالي
      </button>
      <button class="btn-secondary-game" onclick="showLessons()">
        <i class="fas fa-list"></i> قائمة الدروس
      </button>
    </div>
  </div>
</div>

<!-- SCREEN 7: FORTRESS COMPLETE -->
<div class="screen" id="screen-fortress-win">
  <div class="fortress-win-wrap">
    <div class="win-castle" id="fw-icon">🏰</div>
    <h2 class="win-title" id="fw-title">أكملت الحصن!</h2>
    <p class="win-sub" id="fw-sub">أنت فارس حقيقي</p>
    <div class="badge-earned">
      <div class="badge-icon" id="fw-badge-icon">🥇</div>
      <div class="badge-name" id="fw-badge-name">شارة الحصن الأول</div>
      <div class="badge-desc" id="fw-badge-desc">أكملت كل دروس الحصن بنجاح</div>
    </div>
    <div class="result-stats">
      <div class="result-stat-box">
        <div class="stat-val" id="fw-xp">+500</div>
        <div class="stat-lbl">مكافأة XP</div>
      </div>
      <div class="result-stat-box">
        <div class="stat-val" id="fw-gems">+20</div>
        <div class="stat-lbl">جواهر</div>
      </div>
      <div class="result-stat-box">
        <div class="stat-val" id="fw-level">↑</div>
        <div class="stat-lbl">مستوى جديد</div>
      </div>
    </div>
    <div class="result-btns" style="margin-top:20px;">
      <button class="btn-primary-game" onclick="showMap()">
        <i class="fas fa-map"></i> الحصن التالي!
      </button>
    </div>
  </div>
</div>

<!-- SCREEN 8: PROFILE -->
<div class="screen" id="screen-profile">
  <div class="back-bar">
    <button class="btn-back-game" onclick="showMap()">
      <i class="fas fa-arrow-right"></i> الخريطة
    </button>
    <span class="lesson-fortress-title">بطاقة الفارس</span>
  </div>
  <div class="profile-wrap" id="profile-wrap"></div>
</div>

<!-- SCREEN 9: ADMIN -->
<div class="screen" id="screen-admin">
  <div class="admin-wrap">
    <div class="back-bar">
      <button class="btn-back-game" onclick="showMap()">
        <i class="fas fa-arrow-right"></i> الخريطة
      </button>
      <span class="lesson-fortress-title">لوحة إدارة الدورات</span>
    </div>
    <div class="admin-hero">
      <h2>بناء الدورات</h2>
      <p>أضف دوراتك الخاصة وأضف إليها الدروس. بإمكانك إضافة كل من درس دورة وتعديل محتوى الدرس في المحرر ثم الاختبارات اليدوية في الإعدادات المتاحة.</p>
    </div>
    <div class="admin-grid">
      <div class="admin-panel">
        <h3><i class="fas fa-book"></i> إضافة دورة</h3>
        <div class="admin-field"><label>عنوان الدورة</label><input id="admin-course-title" placeholder="مثال: أذكار الصباح" /></div>
        <div class="admin-field"><label>رمز الدورة</label><input id="admin-course-emoji" maxlength="4" placeholder="📖" /></div>
        <div class="admin-field"><label>لون الدورة</label><input id="admin-course-color" type="color" value="#2E8B57" /></div>
        <div class="admin-actions"><button class="admin-btn primary" onclick="adminAddCourse()"><i class="fas fa-plus"></i> إضافة الدورة</button></div>
        <div class="admin-message" id="admin-course-msg"></div>
      </div>
      <div class="admin-panel">
        <h3><i class="fas fa-scroll"></i> إضافة درس</h3>
        <div class="admin-field"><label>اختر الدورة</label><select id="admin-lesson-course"></select></div>
        <div class="admin-field"><label>عنوان الدرس</label><input id="admin-lesson-title" placeholder="مثال: أذكار المساء" /></div>
        <div class="admin-field"><label>محتوى الدرس HTML</label><textarea id="admin-lesson-content" placeholder="<p><strong>الفقرة الأساسية:</strong> ...</p>"></textarea></div>
        <div class="admin-field"><label>أسئلة الاختبار</label><textarea id="admin-lesson-quiz" placeholder="السؤال | خيار 1 | خيار 2 | خيار 3 | خيار 4 | رقم الإجابة الصحيحة 1-4"></textarea><div class="hint">سطر لكل سؤال. كل سؤال يحتوي على السؤال والخيارات ورقم الإجابة مفصولة بـ |</div></div>
        <div class="admin-actions"><button class="admin-btn primary" onclick="adminAddLesson()"><i class="fas fa-plus"></i> إضافة الدرس</button></div>
        <div class="admin-message" id="admin-lesson-msg"></div>
      </div>
      <div class="admin-panel full">
        <h3><i class="fas fa-layer-group"></i> الدورات المضافة</h3>
        <div class="admin-actions" style="margin-bottom:12px;">
          <button class="admin-btn secondary" onclick="adminExportData()"><i class="fas fa-file-export"></i> تصدير JSON</button>
          <button class="admin-btn secondary" onclick="adminImportData()"><i class="fas fa-file-import"></i> استيراد JSON</button>
          <button class="admin-btn danger" onclick="adminClearCustomData()"><i class="fas fa-trash"></i> حذف كل الدورات</button>
        </div>
        <div id="admin-list" class="admin-list"></div>
        <div class="admin-message" id="admin-main-msg"></div>
      </div>
    </div>
  </div>
</div>

<!-- MODAL: FIRST TIME -->
<div class="modal-overlay" id="modal-start">
  <div class="modal-box">
    <div style="font-size:3rem;margin-bottom:8px;">🏰</div>
    <h2>مرحباً يا فارس!</h2>
    <p>ستبني قلعة الإيمان حصناً حصناً. كل درس = لبنة جديدة. اجمع النجوم والجواهر وتسلّق المستويات!</p>
    <button class="btn-primary-game w100" id="btn-start-adventure" onclick="closeModal('modal-start'); showMap();">
      🚀 لنبدأ المغامرة!
    </button>
  </div>
</div>

<!-- MODAL: XP LEVEL UP -->
<div class="modal-overlay" id="modal-levelup">
  <div class="modal-box">
    <div style="font-size:3rem;margin-bottom:8px;">🎉</div>
    <h2 id="levelup-title">ارتقيت مستوى!</h2>
    <p id="levelup-desc">أنت الآن في مستوى جديد. واصل التقدم!</p>
    <button class="btn-primary-game w100" onclick="closeModal('modal-levelup')">
      💪 رائع!
    </button>
  </div>
</div>

<script src="game-data.js"></script>
<script>
// ================================================================
// VERSION & CONSTANTS
// ================================================================
const GAME_VERSION = "2.1";

// ================================================================
// RAW COURSES CONTENT (only "أركان الإيمان")
// ================================================================
// ================================================================
// rawCourses — مُحمَّلة من ملف game-data.js الخارجي
// ================================================================

// ================================================================
// FORTRESSES DATA (only "أركان الإيمان")
// ================================================================
// ================================================================
// FORTRESSES — مُحمَّلة من ملف game-data.js الخارجي
// ================================================================

// ================================================================
// LOCAL ADMIN: ADD COURSES & LESSONS (only custom)
// ================================================================
const ADMIN_CUSTOM_KEY = "husun_custom_courses_v1";
const BASE_FORTRESS_COUNT = FORTRESSES.length;
const BASE_RAW_COURSES_COUNT = rawCourses.length;

function adminGetCustomCourses() {
  try {
    const data = JSON.parse(localStorage.getItem(ADMIN_CUSTOM_KEY) || "[]");
    return Array.isArray(data) ? data : [];
  } catch(e) { return []; }
}
function adminSaveCustomCourses(courses) {
  localStorage.setItem(ADMIN_CUSTOM_KEY, JSON.stringify(courses));
}
function adminDefaultQuiz(title) {
  return [
    { q:`ما موضوع هذا الدرس؟`, opts:[title,"موضوع آخر","لا أعرف","سؤال عشوائي"], a:0, hint:`موضوع الدرس هو: ${title}` },
    { q:"ماذا يجب على طالب العلم أولاً؟", opts:["حفظ المعلومات","فهم المعلومات وتطبيقها في الحياة","السماع فقط","قراءة الكتب"], a:1, hint:"طالب العلم يفهم ويطبق المعلومات." },
    { q:"ما أهمية الاستمرار في طلب العلم؟", opts:["غير مهم للعلم","بناء شخصية متكاملة","غير ضروري","يعيق النجاح"], a:0, hint:"الاستمرار ضروري في طلب العلم." }
  ];
}
function adminNormalizeCourse(course) {
  const lessons = Array.isArray(course.lessons) ? course.lessons : [];
  return {
    id: course.id || ("custom-" + Date.now()),
    title: String(course.title || "دورة جديدة").trim(),
    emoji: String(course.emoji || "📖").trim() || "📖",
    color: course.color || "#2E8B57",
    badge: course.badge || { icon: String(course.emoji || "📖"), name: "شارة " + String(course.title || "دورة جديدة"), desc: "أكملت هذه الدورة" },
    lessons: lessons.map(l => ({
      id: l.id || ("lesson-" + Date.now() + Math.floor(Math.random()*999)),
      title: String(l.title || "درس جديد").trim(),
      content: l.content || `<p><strong>الفقرة الأساسية:</strong> ${String(l.title || "درس جديد")}</p>`,
      quiz: Array.isArray(l.quiz) && l.quiz.length ? l.quiz : adminDefaultQuiz(String(l.title || "درس جديد"))
    }))
  };
}
function escapeHtml(str) {
  if (!str) return "";
  return String(str)
    .replace(/&/g, "&amp;")
    .replace(/</g, "&lt;")
    .replace(/>/g, "&gt;")
    .replace(/"/g, "&quot;")
    .replace(/'/g, "&#039;");
}
function adminReloadCustomCourses() {
  FORTRESSES.splice(BASE_FORTRESS_COUNT);
  rawCourses.splice(BASE_RAW_COURSES_COUNT);
  adminGetCustomCourses().map(adminNormalizeCourse).forEach(c => {
    FORTRESSES.push({ id:c.id, title:c.title, emoji:c.emoji, color:c.color, badge:c.badge, lessons:c.lessons.map(l => ({ title:l.title, quiz:l.quiz })) });
    rawCourses.push({ id:c.id, title:c.title, icon:"fa-book", color:c.color, lessons:c.lessons.map(l => ({ title:l.title, content:l.content })) });
  });
}
function adminParseQuiz(text, title) {
  const lines = String(text || "").split(/\n+/).map(x => x.trim()).filter(Boolean);
  const quiz = lines.map(line => {
    const p = line.split("|").map(x => x.trim());
    if (p.length < 6) return null;
    const answer = Math.max(0, Math.min(3, (parseInt(p[5], 10) || 1) - 1));
    return { q:p[0], opts:p.slice(1,5), a:answer, hint:"راجع الدرس للتعرف على الإجابة الصحيحة." };
  }).filter(Boolean);
  return quiz.length ? quiz : adminDefaultQuiz(title);
}
function adminShowMessage(id, text, ok=true) {
  const el = document.getElementById(id);
  if (!el) return;
  el.textContent = text;
  el.className = "admin-message " + (ok ? "ok" : "err");
  clearTimeout(el._timer);
  el._timer = setTimeout(() => { el.className = "admin-message"; }, 3500);
}
function showAdmin() {
  updateNavActive("nav-admin");
  adminReloadCustomCourses();
  adminRender();
  showScreen("admin");
}
function adminRender() {
  const select = document.getElementById("admin-lesson-course");
  if (select) {
    select.innerHTML = FORTRESSES.map((c, i) => `<option value="${i}">${c.emoji || "📖"} ${escapeHtml(c.title)}</option>`).join("");
  }
  const custom = adminGetCustomCourses().map(adminNormalizeCourse);
  const list = document.getElementById("admin-list");
  if (!list) return;
  if (!custom.length) {
    list.innerHTML = `<div class="empty-hint" style="text-align:center;padding:20px;color:rgba(255,255,255,0.4);">لم تُضف أي دورات خاصة بعد.</div>`;
    return;
  }
  list.innerHTML = custom.map((c, ci) => `
    <div class="admin-course-item">
      <div class="admin-course-head">
        <div>
          <div class="admin-course-title"><span class="admin-emoji">${escapeHtml(c.emoji)}</span><span>${escapeHtml(c.title)}</span></div>
          <div class="admin-course-meta">${c.lessons.length} درس فيها</div>
        </div>
        <button class="admin-small-btn danger" onclick="adminDeleteCourse(${ci})">حذف الدورة</button>
      </div>
      ${c.lessons.length ? c.lessons.map((l, li) => `
        <div class="admin-lesson-row"><span>${li+1}. ${escapeHtml(l.title)}</span><button class="admin-small-btn danger" onclick="adminDeleteLesson(${ci},${li})">حذف</button></div>
      `).join("") : `<div class="empty-hint" style="font-size:0.8rem;color:rgba(255,255,255,0.4);padding:8px;">لا توجد دروس في هذه الدورة.</div>`}
    </div>`).join("");
}
function adminAddCourse() {
  const title = document.getElementById("admin-course-title").value.trim();
  const emoji = document.getElementById("admin-course-emoji").value.trim() || "📖";
  const color = document.getElementById("admin-course-color").value || "#2E8B57";
  if (!title) return adminShowMessage("admin-course-msg", "يرجى كتابة عنوان الدورة أولاً.", false);
  const courses = adminGetCustomCourses();
  courses.push(adminNormalizeCourse({ id:"custom-" + Date.now(), title, emoji, color, lessons:[] }));
  adminSaveCustomCourses(courses);
  adminReloadCustomCourses();
  adminRender();
  document.getElementById("admin-course-title").value = "";
  document.getElementById("admin-course-emoji").value = "";
  adminShowMessage("admin-course-msg", "✅ تمت إضافة الدورة إلى قائمة الحصون.");
}
function adminAddLesson() {
  const globalIndex = parseInt(document.getElementById("admin-lesson-course").value, 10);
  const title = document.getElementById("admin-lesson-title").value.trim();
  const content = document.getElementById("admin-lesson-content").value.trim();
  const quizText = document.getElementById("admin-lesson-quiz").value;
  if (!title) return adminShowMessage("admin-lesson-msg", "يرجى كتابة عنوان الدرس أولاً.", false);
  const baseCount = BASE_FORTRESS_COUNT;
  if (globalIndex < baseCount) return adminShowMessage("admin-lesson-msg", "يمكنك فقط إضافة دروس للدورات المخصصة، وليس الدورات الأصلية.", false);
  const customIndex = globalIndex - baseCount;
  const courses = adminGetCustomCourses().map(adminNormalizeCourse);
  if (!courses[customIndex]) return adminShowMessage("admin-lesson-msg", "الدورة المختارة غير موجودة.", false);
  courses[customIndex].lessons.push({
    id:"lesson-" + Date.now(),
    title,
    content: content || `<p><strong>الفقرة الأساسية:</strong> ${escapeHtml(title)}</p><p><strong>الفائدة التربوية:</strong> أضف هنا محتوى الدرس وفوائده التربوية.</p>`,
    quiz: adminParseQuiz(quizText, title)
  });
  adminSaveCustomCourses(courses);
  adminReloadCustomCourses();
  adminRender();
  document.getElementById("admin-lesson-title").value = "";
  document.getElementById("admin-lesson-content").value = "";
  document.getElementById("admin-lesson-quiz").value = "";
  adminShowMessage("admin-lesson-msg", "✅ تمت إضافة الدرس بنجاح إلى الدورة.");
}
function adminDeleteCourse(index) {
  if (!confirm("هل أنت متأكد من حذف هذه الدورة؟")) return;
  const courses = adminGetCustomCourses();
  courses.splice(index, 1);
  adminSaveCustomCourses(courses);
  adminReloadCustomCourses();
  adminRender();
  adminShowMessage("admin-main-msg", "✅ تم حذف الدورة.");
}
function adminDeleteLesson(courseIndex, lessonIndex) {
  if (!confirm("هل أنت متأكد من حذف هذا الدرس؟")) return;
  const courses = adminGetCustomCourses().map(adminNormalizeCourse);
  if (!courses[courseIndex]) return;
  courses[courseIndex].lessons.splice(lessonIndex, 1);
  adminSaveCustomCourses(courses);
  adminReloadCustomCourses();
  adminRender();
  adminShowMessage("admin-main-msg", "✅ تم حذف الدرس.");
}
function adminExportData() {
  const data = JSON.stringify(adminGetCustomCourses(), null, 2);
  navigator.clipboard?.writeText(data).then(() => adminShowMessage("admin-main-msg", "✅ تم نسخ JSON إلى الحافظة."))
    .catch(() => prompt("انسخ بيانات JSON:", data));
}
function adminImportData() {
  const data = prompt("الصق بيانات JSON الخاصة بالدورات المخصصة:");
  if (!data) return;
  try {
    const parsed = JSON.parse(data);
    if (!Array.isArray(parsed)) throw new Error("not array");
    adminSaveCustomCourses(parsed.map(adminNormalizeCourse));
    adminReloadCustomCourses();
    adminRender();
    adminShowMessage("admin-main-msg", "✅ تم استيراد البيانات بنجاح.");
  } catch(e) {
    adminShowMessage("admin-main-msg", "❌ بيانات JSON غير صحيحة.", false);
  }
}
function adminClearCustomData() {
  if (!confirm("هل أنت متأكد؟ سيتم حذف كل الدورات المخصصة نهائياً.")) return;
  adminSaveCustomCourses([]);
  adminReloadCustomCourses();
  adminRender();
  adminShowMessage("admin-main-msg", "✅ تم حذف كل الدورات المخصصة.");
}
adminReloadCustomCourses();

// ================================================================
// GAME ENGINE
// ================================================================
const XP_PER_LEVEL = 200;
const XP_PER_CORRECT = 30;
const XP_PER_LESSON_COMPLETE = 50;
const XP_FORTRESS_BONUS = 300;
const GEMS_PER_LESSON = 2;
const GEMS_PERFECT_BONUS = 3;

let STATE = {
  version: GAME_VERSION,
  playerName: "",
  avatar: "🦁",
  age: "12",
  xp: 0,
  gems: 0,
  streak: 0,
  lastPlayDate: "",
  level: 1,
  badgesEarned: [],
  lessonsCompleted: {},
  currentFortress: null,
  currentLessonIndex: null,
};
let quizState = { questions:[], current:0, correct:0, timer:null };

// ============================================================
// STORAGE
// ============================================================
function saveState() {
  try { localStorage.setItem("husun_game_v2", JSON.stringify(STATE)); } catch(e){}
}
function loadState() {
  try {
    const raw = localStorage.getItem("husun_game_v2");
    if (!raw) return false;
    const parsed = JSON.parse(raw);
    if (typeof parsed !== "object" || parsed === null) throw new Error("invalid state");
    if (typeof parsed.playerName !== "string") throw new Error("missing playerName");
    if (typeof parsed.xp !== "number") parsed.xp = 0;
    if (typeof parsed.gems !== "number") parsed.gems = 0;
    if (typeof parsed.level !== "number" || parsed.level < 1) parsed.level = 1;
    if (typeof parsed.streak !== "number") parsed.streak = 0;
    if (!Array.isArray(parsed.badgesEarned)) parsed.badgesEarned = [];
    if (typeof parsed.lessonsCompleted !== "object" || parsed.lessonsCompleted === null) parsed.lessonsCompleted = {};
    STATE = { ...STATE, ...parsed };
    return true;
  } catch(e) {
    console.warn("State load failed, resetting:", e);
    localStorage.removeItem("husun_game_v2");
    return false;
  }
}

// ============================================================
// SCREEN MANAGER
// ============================================================
function showScreen(id) {
  document.querySelectorAll(".screen").forEach(s => s.classList.remove("active"));
  const el = document.getElementById("screen-" + id);
  if (el) el.classList.add("active");
  if (el) el.scrollTop = 0;
  const needsHud = ["map","lessons","lesson","quiz","profile","admin"].includes(id);
  document.getElementById("hud").classList.toggle("visible", needsHud);
  document.getElementById("bottom-nav").classList.toggle("visible", needsHud);
  updateHUD();
}

// ============================================================
// HUD
// ============================================================
function updateHUD() {
  const xpForLevel = STATE.level * XP_PER_LEVEL;
  const xpInLevel = STATE.xp - (STATE.level - 1) * XP_PER_LEVEL;
  const pct = Math.min(100, Math.round((xpInLevel / XP_PER_LEVEL) * 100));
  document.getElementById("hud-level").textContent = "⭐ مستوى " + STATE.level;
  document.getElementById("hud-xp-val").textContent = STATE.xp;
  document.getElementById("hud-xp-bar").style.width = pct + "%";
  document.getElementById("hud-gems-val").textContent = STATE.gems;
  document.getElementById("hud-streak-val").textContent = STATE.streak;
}

// ============================================================
// STARS & CONFETTI
// ============================================================
function makeStars(canvas, total=10) {
  for (let i=0; i<total; i++) {
    const s = document.createElement("div");
    s.className = "star";
    s.style.cssText = `
      width:${2+Math.random()*3}px;height:${2+Math.random()*3}px;
      left:${Math.random()*100}%;top:${Math.random()*100}%;
      --dur:${2+Math.random()*4}s;--delay:${Math.random()*3}s;
    `;
    canvas.appendChild(s);
  }
}
function launchConfetti() {
  const colors = ["#D4AF37","#F0D060","#27AE60","#3498DB","#E74C3C","#9B59B6","#E67E22"];
  for (let i=0; i<50; i++) {
    const c = document.createElement("div");
    c.className = "confetti-piece";
    c.style.cssText = `
      left:${Math.random()*100}vw;
      background:${colors[Math.floor(Math.random()*colors.length)]};
      --dur:${1.5+Math.random()*1.5}s;--delay:${Math.random()*0.8}s;
      width:${6+Math.random()*8}px;height:${6+Math.random()*8}px;
      border-radius:${Math.random()>0.5?"50%":"2px"};
    `;
    document.body.appendChild(c);
    setTimeout(() => c.remove(), 3000);
  }
}
function showFloatText(txt) {
  const el = document.getElementById("floating-text");
  el.textContent = txt;
  el.style.display = "block";
  setTimeout(() => el.style.display = "none", 1500);
}
function showXpPopup(xp, el) {
  const pop = document.createElement("div");
  pop.className = "xp-popup";
  pop.textContent = "+" + xp + " XP";
  const rect = el ? el.getBoundingClientRect() : { left: window.innerWidth/2, top: window.innerHeight/2 };
  pop.style.cssText = `left:${rect.left + 20}px;top:${rect.top}px;`;
  document.body.appendChild(pop);
  setTimeout(() => pop.remove(), 1600);
}

// ============================================================
// STREAK
// ============================================================
function updateStreak() {
  const today = new Date().toDateString();
  if (STATE.lastPlayDate !== today) {
    const yesterday = new Date(Date.now()-86400000).toDateString();
    STATE.streak = STATE.lastPlayDate === yesterday ? STATE.streak + 1 : 1;
    STATE.lastPlayDate = today;
  }
}

// ============================================================
// WELCOME SCREEN
// ============================================================
function chooseAvatar(el) {
  document.querySelectorAll(".avatar-opt").forEach(a => a.classList.remove("chosen"));
  el.classList.add("chosen");
  STATE.avatar = el.dataset.av;
}
function chooseAge(el) {
  document.querySelectorAll(".age-opt").forEach(a => a.classList.remove("chosen"));
  el.classList.add("chosen");
  STATE.age = el.dataset.age;
}
function startGame() {
  const name = document.getElementById("player-name").value.trim();
  if (!name) { 
    document.getElementById("player-name").style.borderColor = "#E74C3C";
    setTimeout(() => document.getElementById("player-name").style.borderColor = "", 1500);
    return;
  }
  STATE.playerName = name;
  saveState();
  updateStreak();
  openModal("modal-start");
}

// ============================================================
// MAP
// ============================================================
function showMap() {
  updateNavActive("nav-map");
  renderMap();
  showScreen("map");
}
function renderMap() {
  document.getElementById("map-greeting").textContent =
    `أهلاً بك ${STATE.avatar} ${STATE.playerName}! وصلت إلى ${countCompletedLessons()} درس 🎯`;
  const grid = document.getElementById("map-grid");
  grid.innerHTML = "";
  FORTRESSES.forEach((f, fi) => {
    const prev = fi === 0 ? true : isFortressUnlocked(fi - 1);
    const unlocked = fi === 0 ? true : prev;
    const { done, total, pct } = getFortressProgress(fi);
    const completed = done === total && total > 0;
    const card = document.createElement("div");
    card.className = "fortress-card" + (completed ? " completed" : "") + (unlocked ? "" : " locked");
    if (unlocked) card.onclick = () => showLessons(fi);
    card.innerHTML = `
      <span class="chapter-number">الحصن ${fi+1}</span>
      <div class="fortress-icon-wrap">
        <span>${f.emoji}</span>
        ${!unlocked ? '<span class="lock-badge">🔒</span>' : ""}
      </div>
      <div class="fortress-info">
        <div class="fortress-name">${f.title}</div>
        <div class="fortress-meta">${f.lessons.length} درس ${completed ? "✅" : ""}</div>
        <div class="fortress-prog-wrap">
          <div class="fortress-prog-fill" style="width:${pct}%;background:${f.color}"></div>
        </div>
        <div class="fortress-pct">${pct}% مكتمل</div>
      </div>
      <div class="fortress-badge">${completed ? "🏆" : (unlocked ? "▶️" : "🔒")}</div>
    `;
    grid.appendChild(card);
  });
}
function getFortressProgress(fi) {
  const f = FORTRESSES[fi];
  let done = 0;
  f.lessons.forEach((_, li) => {
    if (STATE.lessonsCompleted[`f${fi}-l${li}`]) done++;
  });
  const total = f.lessons.length;
  return { done, total, pct: total ? Math.round((done/total)*100) : 0 };
}
function isFortressUnlocked(fi) {
  if (fi === 0) return true;
  const { done, total } = getFortressProgress(fi - 1);
  return done === total && total > 0;
}
function countCompletedLessons() {
  return Object.keys(STATE.lessonsCompleted).length;
}

// ============================================================
// LESSONS LIST
// ============================================================
function showLessons(fi) {
  STATE.currentFortress = fi;
  const f = FORTRESSES[fi];
  document.getElementById("lesson-fortress-title").textContent = f.emoji + " " + f.title;
  const list = document.getElementById("lessons-list");
  list.innerHTML = "";
  f.lessons.forEach((lesson, li) => {
    const key = `f${fi}-l${li}`;
    const prev = li === 0 ? true : !!STATE.lessonsCompleted[`f${fi}-l${li-1}`];
    const isDone = !!STATE.lessonsCompleted[key];
    const isCurrent = !isDone && prev;
    const isLocked = !isDone && !prev;
    const row = document.createElement("div");
    row.className = "lesson-row" + (isDone?" done":"") + (isCurrent?" current":"") + (isLocked?" locked":"");
    if (!isLocked) row.onclick = () => startLesson(fi, li);
    const stars = isDone ? (STATE.lessonsCompleted[key].stars || 1) : 0;
    row.innerHTML = `
      <div class="lesson-num">${isDone?"✔":(isLocked?"🔒":(li+1))}</div>
      <div class="lesson-info">
        <div class="lesson-title-row">${lesson.title}</div>
        <span class="lesson-xp-tag">✨ ${isDone ? (STATE.lessonsCompleted[key].xp||XP_PER_LESSON_COMPLETE) : XP_PER_LESSON_COMPLETE+"+"} XP
        ${isDone ? " · " + "⭐".repeat(stars) : ""}</span>
      </div>
      <div class="lesson-status-icon">${isDone?"✅":(isCurrent?"▶️":"🔒")}</div>
    `;
    list.appendChild(row);
  });
  showScreen("lessons");
}

// ============================================================
// LESSON READER
// ============================================================
function startLesson(fi, li) {
  STATE.currentFortress = fi;
  STATE.currentLessonIndex = li;
  const f = FORTRESSES[fi];
  const lesson = f.lessons[li];
  document.getElementById("lesson-reading-title").textContent = lesson.title;
  document.getElementById("lesson-back-btn").onclick = () => showLessons(fi);

  const rawContent = getRawLessonContent(fi, li);
  const wrap = document.getElementById("lesson-content-wrap");
  wrap.innerHTML = renderLessonSections(rawContent, lesson.title) +
    `<button class="btn-read-done" onclick="startQuiz(${fi},${li})">
      <i class="fas fa-check-circle"></i> قرأت وفهمت — ابدأ الاختبار!
    </button>`;
  showScreen("lesson");
}

function getRawLessonContent(fi, li) {
  try {
    const fortressTitle = FORTRESSES[fi].title;
    if (rawCourses[fi] && rawCourses[fi].lessons && rawCourses[fi].lessons[li]) {
      return rawCourses[fi].lessons[li].content || "";
    }
    let rc = rawCourses.find(c => c.title === fortressTitle);
    if (!rc) rc = rawCourses.find(c => c.title && c.title.startsWith(fortressTitle));
    if (!rc) rc = rawCourses.find(c => fortressTitle && fortressTitle.startsWith(c.title));
    if (!rc || !rc.lessons[li]) return "";
    return rc.lessons[li].content || "";
  } catch(e) {
    console.warn("getRawLessonContent error:", e);
    return "";
  }
}

function renderLessonSections(html, title) {
  const sections = [
    { type:"paragraph", icon:"📌", label:"الفقرة الأساسية", match:"الفقرة الأساسية" },
    { type:"quote", icon:"📖", label:"الدليل", match:"الدليل" },
    { type:"explanation", icon:"💡", label:"الشرح المختصر", match:"الشرح المختصر" },
    { type:"application", icon:"✅", label:"النموذج التطبيقي", match:"النموذج التطبيقي" },
    { type:"benefit", icon:"🌟", label:"الفائدة التربوية", match:"الفائدة التربوية" },
    { type:"paragraph", icon:"⚠️", label:"الشبهة", match:"الشبهة" },
    { type:"quote", icon:"🔍", label:"الرد بالدليل", match:"الرد بالدليل" },
    { type:"explanation", icon:"💬", label:"الشرح", match:"الشرح المختصر" },
    { type:"application", icon:"🗣️", label:"كيف ترد؟", match:"النموذج التطبيقي" },
  ];

  const tmp = document.createElement("div");
  tmp.innerHTML = html;
  const rawText = tmp.innerHTML;

  const parts = rawText.split(/<p>|<\/p>/g).filter(p => p.trim());
  let cards = "";
  let currentType = "paragraph";
  let currentLabel = "المحتوى";
  let currentIcon = "📌";
  let buffer = [];

  function flushBuffer() {
    if (!buffer.length) return;
    const colorMap = {
      paragraph:"st-paragraph", quote:"st-quote",
      explanation:"st-explanation", application:"st-application", benefit:"st-benefit"
    };
    cards += `
      <div class="lesson-card-game ${colorMap[currentType]||"st-paragraph"}">
        <div class="section-header-game">
          <div class="section-icon-circle">${currentIcon}</div>
          <span class="section-type-label">${currentLabel}</span>
        </div>
        <div class="section-body">${buffer.join("")}</div>
      </div>`;
    buffer = [];
  }

  parts.forEach(part => {
    const textOnly = part.replace(/<[^>]+>/g,"").trim();
    let matched = false;
    for (const sec of sections) {
      if (textOnly.startsWith(sec.match) || textOnly.includes("<strong>" + sec.match)) {
        flushBuffer();
        currentType = sec.type;
        currentLabel = sec.label;
        currentIcon = sec.icon;
        let content = part.replace(/<strong>([^<]+)<\/strong>/g, '<strong style="color:var(--gold)">$1</strong>');
        content = content.replace(/﴿([^﴾]+)﴾/g, '<div class="quran-text">﴿$1﴾</div>');
        content = content.replace(/«([^»]+)»/g, '<div class="hadith-text">«$1»<span class="source-tag"></span></div>');
        buffer.push("<p>" + content + "</p>");
        matched = true;
        break;
      }
    }
    if (!matched && part.trim()) {
      let content = part.replace(/<strong>([^<]+)<\/strong>/g, '<strong style="color:var(--gold)">$1</strong>');
      content = content.replace(/﴿([^﴾]+)﴾/g, '<div class="quran-text">﴿$1﴾</div>');
      content = content.replace(/«([^»]+)»/g, '<div class="hadith-text">«$1»</div>');
      buffer.push("<p>" + content + "</p>");
    }
  });
  flushBuffer();
  return cards || `<div class="lesson-card-game st-paragraph"><div class="section-body"><p>${html}</p></div></div>`;
}

// ============================================================
// QUIZ ENGINE
// ============================================================
function startQuiz(fi, li) {
  const lesson = FORTRESSES[fi].lessons[li];
  quizState = {
    questions: [...lesson.quiz],
    current: 0,
    correct: 0,
    fi, li,
    timer: null
  };
  renderQuestion();
  showScreen("quiz");
}
function renderQuestion() {
  const q = quizState.questions[quizState.current];
  const total = quizState.questions.length;
  const pct = ((quizState.current) / total) * 100;
  document.getElementById("quiz-prog-fill").style.width = pct + "%";
  document.getElementById("quiz-q-num").textContent = `السؤال ${quizState.current+1} من ${total}`;
  document.getElementById("quiz-question").textContent = q.q;
  document.getElementById("quiz-feedback").style.display = "none";
  document.getElementById("btn-next-q").style.display = "none";
  const letters = ["أ","ب","ج","د"];
  const opts = document.getElementById("quiz-options");
  opts.innerHTML = q.opts.map((opt,i) => `
    <button class="quiz-opt" onclick="answerQ(${i})" id="opt-${i}">
      <div class="opt-circle">${letters[i]}</div>
      ${opt}
    </button>
  `).join("");
  clearInterval(quizState.timer);
  let t = 20;
  const timerEl = document.getElementById("quiz-timer");
  timerEl.classList.remove("urgent");
  timerEl.textContent = "⏱ " + t;
  quizState.timer = setInterval(() => {
    t--;
    timerEl.textContent = "⏱ " + t;
    if (t <= 5) timerEl.classList.add("urgent");
    if (t <= 0) {
      clearInterval(quizState.timer);
      answerQ(-1);
    }
  }, 1000);
}
function answerQ(chosen) {
  clearInterval(quizState.timer);
  const q = quizState.questions[quizState.current];
  const correct = q.a;
  const isCorrect = chosen === correct;
  document.querySelectorAll(".quiz-opt").forEach(b => b.disabled = true);
  const btns = document.querySelectorAll(".quiz-opt");
  if (btns[correct]) btns[correct].classList.add("correct");
  if (chosen >= 0 && chosen !== correct && btns[chosen]) btns[chosen].classList.add("wrong");
  const fb = document.getElementById("quiz-feedback");
  if (isCorrect) {
    quizState.correct++;
    fb.className = "quiz-feedback correct-fb";
    fb.innerHTML = "✅ " + ["ممتاز! أجبت بشكل صحيح 🌟","رائع جداً! إجابة صحيحة 🎉","أحسنت! هذا هو الجواب الصحيح 🏆","بطل! إجابتك صحيحة 💪","نجحت! أنت تعرف هذا جيداً ⭐"][Math.floor(Math.random()*5)];
    STATE.xp += XP_PER_CORRECT;
    showXpPopup(XP_PER_CORRECT, btns[correct]);
    checkLevelUp();
  } else {
    fb.className = "quiz-feedback wrong-fb";
    const hintText = q.hint ? `<br><span style="color:rgba(255,255,255,0.7);font-size:0.88rem;">💡 ${q.hint}</span>` : "";
    if (chosen === -1) {
      fb.innerHTML = "⏱ انتهى الوقت!" + hintText;
    } else {
      fb.innerHTML = "❌ إجابة خاطئة — حاول أن تتذكر في المرة القادمة!" + hintText;
    }
  }
  fb.style.display = "block";
  const nextBtn = document.getElementById("btn-next-q");
  const isLast = quizState.current === quizState.questions.length - 1;
  document.getElementById("next-q-label").textContent = isLast ? "انظر نتيجتك!" : "السؤال التالي";
  nextBtn.style.display = "flex";
}
function nextQuestion() {
  quizState.current++;
  if (quizState.current < quizState.questions.length) {
    renderQuestion();
  } else {
    finishQuiz();
  }
}
function finishQuiz() {
  clearInterval(quizState.timer);
  const { fi, li, correct, questions } = quizState;
  const total = questions.length;
  const stars = correct === total ? 3 : correct >= Math.ceil(total*0.6) ? 2 : 1;
  const xpEarned = XP_PER_LESSON_COMPLETE + (correct * XP_PER_CORRECT);
  const gemsEarned = GEMS_PER_LESSON + (correct === total ? GEMS_PERFECT_BONUS : 0);
  STATE.xp += xpEarned;
  STATE.gems += gemsEarned;
  checkLevelUp();
  const key = `f${fi}-l${li}`;
  const isFirstTime = !STATE.lessonsCompleted[key];
  if (isFirstTime || (STATE.lessonsCompleted[key].stars < stars)) {
    STATE.lessonsCompleted[key] = { stars, correct, total, xp: xpEarned };
  }
  updateStreak();
  saveState();
  showResult(fi, li, stars, correct, total, xpEarned, gemsEarned, isFirstTime);
}
function showResult(fi, li, stars, correct, total, xp, gems, isFirst) {
  const msgs = [
    ["واصل التقدم! 💪", "أكملت الدرس، راجع الإجابات واستمر"],
    ["جيد جداً! 🌟", "أداء ممتاز، واصل مسيرتك"],
    ["مثالي! 🏆🎉", "درجة كاملة — أنت نجم حصون الإيمان!"]
  ];
  document.getElementById("result-emoji").textContent = ["😊","🌟","🏆"][stars-1];
  document.getElementById("result-title").textContent = msgs[stars-1][0];
  document.getElementById("result-subtitle").textContent = msgs[stars-1][1];
  document.getElementById("res-xp").textContent = "+" + xp;
  document.getElementById("res-correct").textContent = correct + "/" + total;
  document.getElementById("res-gems").textContent = "+" + gems;
  const starsRow = document.getElementById("result-stars");
  starsRow.innerHTML = [1,2,3].map(s => `<span class="star-item">${s<=stars?"⭐":"☆"}</span>`).join("");
  const { done, total: ftotal } = getFortressProgress(fi);
  const badge = document.getElementById("result-badge");
  if (done === ftotal) {
    badge.style.display = "flex";
    badge.innerHTML = `🏆 أكملت حصن "${FORTRESSES[fi].title}"!`;
  } else {
    badge.style.display = "none";
  }
  const nextBtn = document.getElementById("btn-result-next");
  const nextLi = li + 1;
  if (nextLi < FORTRESSES[fi].lessons.length) {
    nextBtn.style.display = "flex";
    nextBtn.textContent = "▶ الدرس التالي";
    nextBtn.onclick = () => startLesson(fi, nextLi);
  } else {
    nextBtn.style.display = "flex";
    nextBtn.innerHTML = "🏆 احتفالية الحصن!";
    nextBtn.onclick = () => showFortressWin(fi);
  }
  if (stars === 3) launchConfetti();
  showScreen("result");
}
function goNextLesson() {
  const fi = quizState.fi;
  const li = quizState.li;
  if (fi === undefined || li === undefined) { showMap(); return; }
  const nextLi = li + 1;
  if (nextLi < FORTRESSES[fi].lessons.length) {
    startLesson(fi, nextLi);
  } else {
    showFortressWin(fi);
  }
}
function showFortressWin(fi) {
  const f = FORTRESSES[fi];
  document.getElementById("fw-icon").textContent = f.emoji;
  document.getElementById("fw-title").textContent = "🎉 أكملت " + f.title + "!";
  document.getElementById("fw-sub").textContent = "أنت فارس حقيقي — حصن جديد بُني!";
  document.getElementById("fw-badge-icon").textContent = f.badge.icon;
  document.getElementById("fw-badge-name").textContent = f.badge.name;
  document.getElementById("fw-badge-desc").textContent = f.badge.desc;
  STATE.xp += XP_FORTRESS_BONUS;
  STATE.gems += 20;
  document.getElementById("fw-xp").textContent = "+" + XP_FORTRESS_BONUS;
  document.getElementById("fw-gems").textContent = "+20";
  if (!STATE.badgesEarned.includes(f.badge.name)) {
    STATE.badgesEarned.push(f.badge.name);
  }
  checkLevelUp();
  saveState();
  launchConfetti();
  showFloatText("🏆 مبروك!");
  showScreen("fortress-win");
}

// ============================================================
// LEVEL UP
// ============================================================
function checkLevelUp() {
  const newLevel = Math.floor(STATE.xp / XP_PER_LEVEL) + 1;
  if (newLevel > STATE.level) {
    STATE.level = newLevel;
    openModal("modal-levelup");
    document.getElementById("levelup-title").textContent = "🎉 مستوى " + STATE.level + "!";
    document.getElementById("levelup-desc").textContent = "أنت الآن في المستوى " + STATE.level + "! تابع، الأبطال لا يتوقفون!";
    launchConfetti();
    saveState();
  }
  updateHUD();
}

// ============================================================
// PROFILE
// ============================================================
function showProfile() {
  updateNavActive("nav-profile");
  const wrap = document.getElementById("profile-wrap");
  const xpForLevel = STATE.level * XP_PER_LEVEL;
  const xpInLevel = STATE.xp - (STATE.level - 1) * XP_PER_LEVEL;
  const pct = Math.min(100, Math.round((xpInLevel / XP_PER_LEVEL) * 100));
  const allBadges = FORTRESSES.map(f => f.badge);
  wrap.innerHTML = `
    <div class="profile-hero">
      <div class="profile-avatar">${STATE.avatar}</div>
      <div class="profile-name">${STATE.playerName}</div>
      <div class="profile-level-tag">⭐ المستوى ${STATE.level}</div>
      <div class="profile-xp-bar-wrap">
        <div class="profile-xp-bar-fill" style="width:${pct}%"></div>
      </div>
      <div class="profile-xp-label">${xpInLevel} / ${XP_PER_LEVEL} XP للمستوى التالي</div>
    </div>
    <div class="stats-grid">
      <div class="stat-card"><div class="s-icon">✨</div><div class="s-val">${STATE.xp}</div><div class="s-lbl">إجمالي XP</div></div>
      <div class="stat-card"><div class="s-icon">💎</div><div class="s-val">${STATE.gems}</div><div class="s-lbl">جواهر</div></div>
      <div class="stat-card"><div class="s-icon">🔥</div><div class="s-val">${STATE.streak}</div><div class="s-lbl">أيام متتالية</div></div>
      <div class="stat-card"><div class="s-icon">📚</div><div class="s-val">${countCompletedLessons()}</div><div class="s-lbl">دروس مكتملة</div></div>
    </div>
    <div class="badges-section">
      <h3>🏅 شاراتي</h3>
      <div class="badges-grid">
        ${allBadges.map(b => {
          const earned = STATE.badgesEarned.includes(b.name);
          return `<div class="badge-cell ${earned?"":"locked-badge"}">
            <div class="b-icon">${b.icon}</div>
            <div class="b-name">${b.name}</div>
          </div>`;
        }).join("")}
      </div>
    </div>
    <div style="margin-top:20px;text-align:center;">
      <div style="font-size:0.75rem;color:rgba(212,175,55,0.6);margin-bottom:8px;">تأليف المادة العلمية</div>
      <div style="font-size:0.95rem;color:var(--gold);font-weight:700;">محمد أبو عبد الرحمن — عفا الله عنه</div>
    </div>
  `;
  showScreen("profile");
}

// ============================================================
// NAV & MODAL
// ============================================================
function updateNavActive(active) {
  document.querySelectorAll(".nav-item").forEach(n => n.classList.remove("active"));
  const el = document.getElementById(active);
  if (el) el.classList.add("active");
}
function openModal(id) {
  document.getElementById(id).classList.add("open");
}
function closeModal(id) {
  document.getElementById(id).classList.remove("open");
}

// ============================================================
// INIT
// ============================================================
window.onload = function() {
  makeStars(document.getElementById("starfield"), 60);
  const loaded = loadState();
  if (loaded && STATE.playerName) {
    updateStreak();
    showMap();
  } else {
    showScreen("welcome");
    const firstAv = document.querySelector(".avatar-opt");
    if (firstAv) firstAv.classList.add("chosen");
    const firstAge = document.querySelector('[data-age="12"]');
    if (firstAge) firstAge.classList.add("chosen");
  }
};

// ================================================================
// PWA Service Worker
// ================================================================
if ("serviceWorker" in navigator) {
  navigator.serviceWorker.register("./sw.js").catch(()=>{});
}

// ================================================================
// 🔊 HUSUN SOUND ENGINE — Web Audio API
// ================================================================
const HusunSound = (() => {
  let ctx = null;
  let unlocked = false;
  let masterGain = null;

  function init() {
    if (ctx) return;
    try {
      ctx = new (window.AudioContext || window.webkitAudioContext)();
      masterGain = ctx.createGain();
      masterGain.gain.setValueAtTime(0.7, ctx.currentTime);
      masterGain.connect(ctx.destination);
      unlocked = true;
    } catch(e) {
      console.warn("Web Audio API not supported:", e);
      unlocked = false;
    }
  }

  function osc(type, freq, start, dur, gainVal, gainEnd, dest) {
    const o = ctx.createOscillator();
    const g = ctx.createGain();
    o.type = type;
    o.frequency.setValueAtTime(freq, start);
    g.gain.setValueAtTime(gainVal, start);
    g.gain.exponentialRampToValueAtTime(gainEnd || 0.001, start + dur);
    o.connect(g);
    g.connect(dest || masterGain);
    o.start(start);
    o.stop(start + dur + 0.05);
    return { osc: o, gain: g };
  }

  function slide(o, fromFreq, toFreq, start, dur) {
    o.frequency.setValueAtTime(fromFreq, start);
    o.frequency.exponentialRampToValueAtTime(toFreq, start + dur);
  }

  let _noiseBuffer = null;
  function getNoiseBuffer() {
    if (_noiseBuffer && _noiseBuffer.sampleRate === ctx.sampleRate) return _noiseBuffer;
    const size = ctx.sampleRate * 2;
    _noiseBuffer = ctx.createBuffer(1, size, ctx.sampleRate);
    const data = _noiseBuffer.getChannelData(0);
    for (let i = 0; i < size; i++) data[i] = Math.random() * 2 - 1;
    return _noiseBuffer;
  }
  function whiteNoise(start, dur, gainVal, gainEnd, filterFreq) {
    const buffer = getNoiseBuffer();
    const src = ctx.createBufferSource();
    src.buffer = buffer;
    const filter = ctx.createBiquadFilter();
    filter.type = "bandpass";
    filter.frequency.setValueAtTime(filterFreq || 1200, start);
    filter.Q.setValueAtTime(0.8, start);
    const g = ctx.createGain();
    g.gain.setValueAtTime(gainVal, start);
    g.gain.exponentialRampToValueAtTime(gainEnd || 0.001, start + dur);
    src.connect(filter);
    filter.connect(g);
    g.connect(masterGain);
    src.start(start);
    src.stop(start + dur + 0.1);
    return src;
  }

  let correctCount = 0;
  let wrongCount = 0;
  let welcomeVariant = 0;

  function playCorrect() {
    if (!unlocked) return;
    correctCount++;
    const variant = correctCount % 4;
    const t = ctx.currentTime + 0.02;

    if (variant === 0) {
      for (let i = 0; i < 6; i++) {
        whiteNoise(t + i * 0.08, 0.06, 0.3 + Math.random() * 0.2, 0.001, 800 + Math.random() * 400);
      }
      setTimeout(() => {
        const t2 = ctx.currentTime;
        const n1 = osc("sine", 523, t2, 0.15, 0.3, 0.001);
        const n2 = osc("sine", 659, t2 + 0.12, 0.18, 0.3, 0.001);
        const n3 = osc("sine", 784, t2 + 0.26, 0.25, 0.35, 0.001);
      }, 400);
    } else if (variant === 1) {
      for (let i = 0; i < 8; i++) {
        const delay = i * 0.065 + Math.random() * 0.02;
        whiteNoise(t + delay, 0.055, 0.4, 0.001, 700 + Math.random() * 600);
      }
      setTimeout(() => {
        const t2 = ctx.currentTime;
        const up = osc("sine", 400, t2, 0.4, 0.25, 0.001);
        slide(up.osc, 400, 880, t2, 0.35);
      }, 500);
    } else if (variant === 2) {
      for (let i = 0; i < 5; i++) {
        const n = osc("square", 180 + Math.random() * 40, t + i * 0.07, 0.04, 0.25, 0.001);
      }
      setTimeout(() => {
        const t2 = ctx.currentTime;
        osc("sine", 660, t2, 0.12, 0.28, 0.001);
        osc("sine", 880, t2 + 0.14, 0.18, 0.3, 0.001);
        osc("sine", 1047, t2 + 0.3, 0.22, 0.28, 0.001);
      }, 380);
    } else {
      for (let i = 0; i < 10; i++) {
        const delay = i * 0.07 + Math.random() * 0.025;
        const freq = 600 + Math.random() * 800;
        whiteNoise(t + delay, 0.065, 0.25 + Math.random() * 0.2, 0.001, freq);
      }
      setTimeout(() => {
        const t2 = ctx.currentTime;
        osc("sine", 523, t2, 0.1, 0.2, 0.001);
        osc("sine", 659, t2 + 0.08, 0.1, 0.22, 0.001);
        osc("sine", 784, t2 + 0.17, 0.1, 0.25, 0.001);
        osc("sine", 1047, t2 + 0.28, 0.3, 0.3, 0.001);
      }, 650);
    }
  }

  function playWrong() {
    if (!unlocked) return;
    wrongCount++;
    const variant = wrongCount % 3;
    const t = ctx.currentTime + 0.02;

    if (variant === 0) {
      const o1 = osc("sine", 320, t, 0.35, 0.28, 0.001);
      slide(o1.osc, 320, 160, t, 0.32);
      setTimeout(() => {
        const t2 = ctx.currentTime;
        const o2 = osc("sine", 200, t2, 0.25, 0.22, 0.001);
        slide(o2.osc, 200, 100, t2, 0.28);
      }, 280);
    } else if (variant === 1) {
      const o = osc("triangle", 280, t, 0.5, 0.32, 0.001);
      slide(o.osc, 280, 130, t, 0.45);
      whiteNoise(t, 0.15, 0.08, 0.001, 300);
    } else {
      const o1 = osc("sine", 350, t, 0.2, 0.3, 0.001);
      slide(o1.osc, 350, 200, t, 0.18);
      const o2 = osc("sine", 250, t + 0.22, 0.3, 0.28, 0.001);
      slide(o2.osc, 250, 120, t + 0.22, 0.27);
    }
  }

  function playTimeout() {
    if (!unlocked) return;
    const t = ctx.currentTime + 0.02;
    for (let i = 0; i < 3; i++) {
      const o = osc("square", 440, t + i * 0.18, 0.12, 0.18, 0.001);
      o.gain.gain.setValueAtTime(0.18, t + i * 0.18);
      o.gain.gain.exponentialRampToValueAtTime(0.001, t + i * 0.18 + 0.12);
    }
    setTimeout(() => {
      const t2 = ctx.currentTime;
      const o = osc("sine", 220, t2, 0.35, 0.25, 0.001);
      slide(o.osc, 220, 100, t2, 0.32);
    }, 580);
  }

  function playWelcome() {
    if (!unlocked) return;
    welcomeVariant = (welcomeVariant + 1) % 3;
    const t = ctx.currentTime + 0.05;

    if (welcomeVariant === 0) {
      const notes = [523, 659, 784, 1047];
      notes.forEach((freq, i) => {
        osc("sine", freq, t + i * 0.13, 0.35, 0.22, 0.001);
      });
    } else if (welcomeVariant === 1) {
      whiteNoise(t, 0.25, 0.12, 0.001, 2000);
      const o = osc("sine", 440, t + 0.1, 0.55, 0.28, 0.001);
      slide(o.osc, 440, 880, t + 0.1, 0.4);
    } else {
      for (let i = 0; i < 3; i++) {
        osc("triangle", 300 + i * 80, t + i * 0.1, 0.08, 0.2, 0.001);
      }
      osc("sine", 784, t + 0.32, 0.35, 0.3, 0.001);
    }
  }

  function playFortressWin() {
    if (!unlocked) return;
    const t = ctx.currentTime + 0.05;
    for (let i = 0; i < 16; i++) {
      const delay = i * 0.06 + Math.random() * 0.03;
      whiteNoise(t + delay, 0.07, 0.3 + Math.random() * 0.25, 0.001, 600 + Math.random() * 1000);
    }
    const fanfare = [523, 659, 784, 659, 784, 1047];
    fanfare.forEach((freq, i) => {
      osc("sine", freq, t + 0.8 + i * 0.12, 0.2, 0.3, 0.001);
    });
    setTimeout(() => {
      const t2 = ctx.currentTime;
      for (let i = 0; i < 4; i++) {
        const drum = osc("sine", 80, t2 + i * 0.22, 0.18, 0.35, 0.001);
        slide(drum.osc, 80, 40, t2 + i * 0.22, 0.15);
        whiteNoise(t2 + i * 0.22, 0.05, 0.2, 0.001, 2000);
      }
    }, 700);
  }

  function playLevelUp() {
    if (!unlocked) return;
    const t = ctx.currentTime + 0.05;
    const notes = [392, 494, 587, 740, 880, 1175];
    notes.forEach((freq, i) => {
      const o = osc("sine", freq, t + i * 0.1, 0.22, 0.28, 0.001);
      osc("sine", freq * 2, t + i * 0.1, 0.12, 0.08, 0.001);
    });
    setTimeout(() => {
      for (let i = 0; i < 5; i++) {
        whiteNoise(ctx.currentTime + i * 0.07, 0.055, 0.2, 0.001, 900 + Math.random() * 400);
      }
    }, 700);
  }

  function playPerfect() {
    if (!unlocked) return;
    playFortressWin();
    setTimeout(() => {
      const t = ctx.currentTime;
      for (let i = 0; i < 3; i++) {
        osc("sine", [784, 1047, 1318][i], t + i * 0.15, 0.4, 0.32, 0.001);
      }
    }, 1200);
  }

  function playStartLesson() {
    if (!unlocked) return;
    const t = ctx.currentTime + 0.05;
    osc("sine", 392, t, 0.15, 0.18, 0.001);
    osc("sine", 494, t + 0.12, 0.15, 0.2, 0.001);
    osc("sine", 587, t + 0.25, 0.2, 0.22, 0.001);
    whiteNoise(t, 0.08, 0.05, 0.001, 3000);
  }

  function playNewQuestion() {
    if (!unlocked) return;
    const t = ctx.currentTime + 0.02;
    osc("sine", 660, t, 0.08, 0.12, 0.001);
    osc("sine", 880, t + 0.06, 0.07, 0.1, 0.001);
  }

  function playTimerUrgent() {
    if (!unlocked) return;
    const t = ctx.currentTime + 0.02;
    const o = osc("square", 880, t, 0.06, 0.12, 0.001);
    o.gain.gain.setValueAtTime(0.12, t);
    o.gain.gain.exponentialRampToValueAtTime(0.001, t + 0.06);
  }

  function playUnlock() {
    if (!unlocked) return;
    const t = ctx.currentTime + 0.05;
    const o = osc("triangle", 1200, t, 0.12, 0.2, 0.001);
    slide(o.osc, 1200, 600, t, 0.1);
    setTimeout(() => {
      const t2 = ctx.currentTime;
      osc("sine", 523, t2, 0.12, 0.18, 0.001);
      osc("sine", 659, t2 + 0.1, 0.12, 0.2, 0.001);
      osc("sine", 784, t2 + 0.2, 0.18, 0.22, 0.001);
    }, 250);
  }

  function playQuizStart() {
    if (!unlocked) return;
    const t = ctx.currentTime + 0.05;
    whiteNoise(t, 0.15, 0.1, 0.001, 1500);
    osc("sine", 440, t + 0.1, 0.2, 0.22, 0.001);
    osc("sine", 587, t + 0.24, 0.18, 0.22, 0.001);
    osc("sine", 440, t + 0.4, 0.25, 0.28, 0.001);
  }

  function playTap() {
    if (!unlocked) return;
    const t = ctx.currentTime + 0.01;
    osc("sine", 800, t, 0.04, 0.1, 0.001);
  }

  function playBack() {
    if (!unlocked) return;
    const t = ctx.currentTime + 0.02;
    osc("sine", 523, t, 0.06, 0.12, 0.001);
    osc("sine", 440, t + 0.08, 0.05, 0.1, 0.001);
  }

  return {
    init,
    correct: playCorrect,
    wrong: playWrong,
    timeout: playTimeout,
    welcome: playWelcome,
    fortressWin: playFortressWin,
    levelUp: playLevelUp,
    perfect: playPerfect,
    startLesson: playStartLesson,
    newQuestion: playNewQuestion,
    timerUrgent: playTimerUrgent,
    unlock: playUnlock,
    quizStart: playQuizStart,
    tap: playTap,
    back: playBack
  };
})();

document.addEventListener("click", () => HusunSound.init(), { once: true });
document.addEventListener("touchstart", () => HusunSound.init(), { once: true });

const _origShowScreen    = showScreen;
const _origAnswerQ       = answerQ;
const _origStartLesson   = startLesson;
const _origStartQuiz     = startQuiz;
const _origRenderQuestion= renderQuestion;
const _origCheckLevelUp  = checkLevelUp;
const _origShowResult    = showResult;
const _origShowFortWin   = showFortressWin;
const _origStartGame     = startGame;
const _origShowLessons   = showLessons;

showScreen = function(id) {
  _origShowScreen(id);
  if (id === "welcome") {
    setTimeout(() => HusunSound.welcome(), 400);
  } else if (id === "quiz") {
    setTimeout(() => HusunSound.quizStart(), 200);
  } else if (id === "lesson") {
    setTimeout(() => HusunSound.startLesson(), 200);
  }
};

answerQ = function(chosen) {
  _origAnswerQ(chosen);
  const q = quizState.questions[quizState.current];
  if (q) {
    const correct = q.a;
    if (chosen === -1) {
      HusunSound.timeout();
    } else if (chosen === correct) {
      HusunSound.correct();
    } else {
      HusunSound.wrong();
    }
  }
};

startLesson = function(fi, li) {
  _origStartLesson(fi, li);
  HusunSound.startLesson();
};

renderQuestion = function() {
  _origRenderQuestion();
  setTimeout(() => HusunSound.newQuestion(), 300);
};

checkLevelUp = function() {
  const prevLevel = STATE.level;
  _origCheckLevelUp();
  if (STATE.level > prevLevel) {
    setTimeout(() => HusunSound.levelUp(), 400);
  }
};

showResult = function(fi, li, stars, correct, total, xp, gems, isFirst) {
  _origShowResult(fi, li, stars, correct, total, xp, gems, isFirst);
  setTimeout(() => {
    if (stars === 3) {
      HusunSound.perfect();
    } else if (stars === 2) {
      HusunSound.correct();
    } else {
      HusunSound.wrong();
    }
  }, 500);
};

showFortressWin = function(fi) {
  _origShowFortWin(fi);
  setTimeout(() => HusunSound.fortressWin(), 300);
};

startGame = function() {
  HusunSound.init();
  _origStartGame();
  setTimeout(() => HusunSound.welcome(), 600);
};

showLessons = function(fi) {
  _origShowLessons(fi);
  HusunSound.tap();
};

(function patchQuizTimer() {
  const observer = new MutationObserver(() => {
    const timerEl = document.getElementById("quiz-timer");
    if (timerEl && timerEl.classList.contains("urgent")) {
      if (!timerEl._soundPlaying) {
        timerEl._soundPlaying = true;
        HusunSound.timerUrgent();
        setTimeout(() => { if(timerEl) timerEl._soundPlaying = false; }, 950);
      }
    }
  });
  const startObserving = () => {
    const timerEl = document.getElementById("quiz-timer");
    if (timerEl) {
      observer.observe(timerEl, { childList: true, subtree: true, characterData: true });
    }
  };
  document.addEventListener("DOMContentLoaded", startObserving);
  setTimeout(startObserving, 1000);
})();

document.addEventListener("DOMContentLoaded", () => {
  document.querySelectorAll(".btn-back-game").forEach(btn => {
    btn.addEventListener("click", () => HusunSound.back());
  });
});

(function watchModalStart() {
  const btn = document.getElementById("btn-start-adventure");
  if (btn) {
    btn.addEventListener("click", () => {
      HusunSound.init();
      setTimeout(() => HusunSound.welcome(), 200);
    });
  } else {
    setTimeout(watchModalStart, 500);
  }
})();
</script>
</body>
</html>
