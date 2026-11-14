[There_Is_No_Team_It_Is_A_YOLO_Slideshow_7s_Rules_and_Tactics_Controls_Fixed.html](https://github.com/user-attachments/files/34839032/There_Is_No_Team_It_Is_A_YOLO_Slideshow_7s_Rules_and_Tactics_Controls_Fixed.html)
# dwbot2
dwbot 2.0
<!doctype html>
<html lang="en"><head><meta charset="utf-8"/><meta content="width=device-width, initial-scale=1" name="viewport"/><title>There Is No Team, It Is a YOLO! — Seven-Second Rules and Tactics Slideshow</title>
<style>
:root{--navy:#112a45;--gold:#e5bd82;--cream:#f4f0e8;--line:rgba(255,255,255,.22)}*{box-sizing:border-box}html,body{height:100%;margin:0}body{background:#071626;color:var(--cream);font-family:Georgia,'Times New Roman',serif;overflow:hidden}
#deck{height:100%;display:flex;align-items:center;justify-content:center;flex-direction:column;gap:12px;padding:12px 12px 78px}
#stage{position:relative;width:min(92vw, calc(77vh * 1.2));height:min(77vh, calc(92vw / 1.2));aspect-ratio:1.2;max-width:1120px;max-height:860px;border-radius:20px;overflow:hidden;box-shadow:0 24px 70px rgba(0,0,0,.5);border:1px solid rgba(229,189,130,.55);background:radial-gradient(circle at 75% 15%,#294d6d,#091b2e 65%)}
.slide{position:absolute;inset:0;overflow:hidden;isolation:isolate}.slide[hidden]{display:none}.slide-bg{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;opacity:.50;filter:saturate(.78) brightness(.66);z-index:-3}.slide-shade{position:absolute;inset:0;background:linear-gradient(115deg,rgba(5,18,33,.88),rgba(7,24,43,.59) 58%,rgba(6,18,31,.77));z-index:-2}
.slide-frame{position:relative;z-index:1;height:100%;padding:clamp(24px,4vw,54px);display:flex;flex-direction:column;justify-content:center;max-width:100%}
.slide-top{display:flex;align-items:center;justify-content:space-between;margin-bottom:14px;gap:18px}.kicker{color:var(--gold);font:700 clamp(10px,1.2vw,14px)/1.3 Arial,sans-serif;letter-spacing:.19em;text-transform:uppercase}.hero-icon{width:clamp(58px,8vw,96px);height:clamp(48px,6vw,72px);color:var(--gold);fill:none;stroke:currentColor;stroke-width:3;stroke-linecap:round;stroke-linejoin:round;filter:drop-shadow(0 3px 8px #000)}
h1{font-size:clamp(30px,4.2vw,52px);line-height:1.05;letter-spacing:.015em;margin:0 0 22px;color:#fff;text-shadow:0 3px 12px #000}.slide p{font-size:clamp(15px,1.65vw,20px);line-height:1.55;text-align:left;margin:0 0 15px;max-width:900px;text-shadow:0 2px 8px rgba(0,0,0,.9)}.slide-footer{margin-top:auto;padding-top:18px;display:flex;justify-content:space-between;gap:10px;color:rgba(255,255,255,.67);font:700 10px Arial,sans-serif;letter-spacing:.16em}
.icon-cluster{display:flex;gap:8px;align-items:center;margin-top:12px}.icon-cluster svg{width:48px;height:32px;fill:none;stroke:var(--gold);stroke-width:2.7;stroke-linecap:round;stroke-linejoin:round;opacity:.95}
.image-credit{position:absolute;right:16px;bottom:48px;z-index:3;font:10px Arial,sans-serif;color:rgba(255,255,255,.55);opacity:.0;transition:opacity .2s}#stage:hover .image-credit{opacity:1}.image-credit a{color:inherit}
#transition{position:absolute;inset:0;display:none;align-items:center;justify-content:center;background:linear-gradient(135deg,rgba(4,17,31,.96),rgba(14,41,65,.93));z-index:10;overflow:hidden}#transition.active{display:flex}.trans-content{position:relative;display:flex;flex-direction:column;align-items:center;gap:18px;text-align:center;padding:30px}.trans-title{font:700 12px Arial,sans-serif;letter-spacing:.22em;text-transform:uppercase;color:var(--gold)}.trans-icons{display:flex;align-items:center;gap:24px;position:relative}.trans-icon{width:clamp(100px,17vw,180px);height:105px;fill:none;stroke:#f4e4ca;stroke-width:3;stroke-linecap:round;stroke-linejoin:round}.trans-icon.old{animation:depart 7s ease-in forwards}.trans-icon.next{stroke:var(--gold);opacity:0;animation:arrive 7s ease-out forwards}.travel-line{position:absolute;left:12%;right:12%;top:50%;height:2px;background:repeating-linear-gradient(90deg,rgba(255,255,255,.0) 0 12px,rgba(229,189,130,.7) 12px 20px);animation:dash 7s linear infinite}.action-lines{position:absolute;left:0;right:0;top:43%;height:30px;background:repeating-linear-gradient(90deg,transparent 0 25px,rgba(255,255,255,.4) 25px 42px,transparent 42px 65px);opacity:0;animation:action 7s ease-in-out 1}.muzzle-flash{position:absolute;width:28px;height:28px;border-radius:50%;background:#fff3bd;box-shadow:0 0 25px 18px #f5a53c;opacity:0;animation:flash .7s ease-out 1.3s 1}
@keyframes depart{0%{transform:translateX(0) rotate(0);opacity:1}65%{transform:translateX(-65px) rotate(-12deg);opacity:.7}100%{transform:translateX(-120px) rotate(-18deg) scale(.6);opacity:0}}@keyframes arrive{0%{transform:translateX(90px) scale(.6) rotate(13deg);opacity:0}60%{opacity:1}100%{transform:translateX(0) scale(1) rotate(0);opacity:1}}@keyframes dash{to{background-position:130px 0}}@keyframes action{0%,100%{opacity:0;transform:translateX(0)}30%,70%{opacity:.75;transform:translateX(-18px)}}@keyframes flash{0%,100%{opacity:0;transform:scale(.25)}25%{opacity:1;transform:scale(1.4)}65%{opacity:.5;transform:scale(2)}}
#transText{font-size:clamp(19px,2.3vw,28px);color:#fff;text-align:center;text-wrap:balance;text-shadow:0 2px 12px rgba(0,0,0,.55)}
#transSub{font:12px Arial,sans-serif;color:rgba(255,255,255,.65);letter-spacing:.08em}
.transition-cards{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:18px;width:min(940px,88vw);margin-top:8px;text-align:left;align-items:stretch}
.transition-card{position:relative;isolation:isolate;min-width:0;min-height:158px;padding:19px 22px 21px;border-radius:15px;display:flex;flex-direction:column;justify-content:flex-start;overflow:hidden;box-shadow:0 16px 34px rgba(0,0,0,.32)}
.transition-card::after{content:"";position:absolute;inset:0;z-index:-1;pointer-events:none;opacity:.45;background:linear-gradient(115deg,transparent 0 44%,rgba(255,255,255,.055) 50%,transparent 57%)}
.transition-card-head{display:flex;align-items:center;gap:12px;min-width:0;padding-bottom:13px;margin-bottom:13px;border-bottom:1px solid currentColor;border-color:rgba(255,255,255,.16)}
.transition-card-mark{width:38px;height:38px;flex:0 0 38px;display:grid;place-items:center;border-radius:11px;font:700 21px/1 Georgia,serif}
.transition-card-heading{min-width:0;display:flex;flex-direction:column;gap:4px}
.transition-card-label{font:800 11px/1.25 Arial,sans-serif;letter-spacing:.17em;text-transform:uppercase}
.transition-card-subtitle{font:700 9px/1.3 Arial,sans-serif;letter-spacing:.13em;text-transform:uppercase;opacity:.68}
.transition-card-number{margin-left:auto;align-self:flex-start;white-space:nowrap;border-radius:999px;padding:5px 8px;font:800 9px/1 Arial,sans-serif;letter-spacing:.1em}
.transition-card p{margin:0;font-size:clamp(14px,1.5vw,17px);line-height:1.48;max-width:58ch;text-wrap:pretty}
.transition-rule{border:1px solid rgba(229,189,130,.78);border-left:5px solid #e5bd82;background:linear-gradient(135deg,rgba(48,42,34,.98),rgba(18,35,52,.98));color:#f7eddd;font-family:Georgia,'Times New Roman',serif}
.transition-rule::before{content:"";position:absolute;left:0;right:0;top:0;height:2px;background:linear-gradient(90deg,#f0cd91,rgba(229,189,130,.08) 72%)}
.transition-rule .transition-card-mark{background:rgba(229,189,130,.15);border:1px solid rgba(229,189,130,.58);color:#f0cd91}
.transition-rule .transition-card-label{color:#f0cd91}
.transition-rule .transition-card-number{color:#f3d9ad;background:rgba(229,189,130,.13);border:1px solid rgba(229,189,130,.32)}
.transition-rule p{font-family:Georgia,'Times New Roman',serif;font-size:clamp(15px,1.55vw,18px);font-weight:600;line-height:1.5}
.transition-tactic{border:1px solid rgba(79,225,219,.82);border-left:5px solid #48d9d2;background:linear-gradient(135deg,rgba(3,62,78,.99),rgba(7,29,50,.99));color:#e7fcff;font-family:Arial,sans-serif}
.transition-tactic::before{content:"";position:absolute;left:0;right:0;top:0;height:2px;background:linear-gradient(90deg,#73f3e9,rgba(72,217,210,.08) 72%)}
.transition-tactic .transition-card-mark{background:rgba(72,217,210,.13);border:1px solid rgba(105,242,230,.58);color:#82f5e9;font-family:Arial,sans-serif}
.transition-tactic .transition-card-label{color:#8ef5ea}
.transition-tactic .transition-card-number{color:#9cf7ef;background:rgba(72,217,210,.11);border:1px solid rgba(105,242,230,.3)}
.transition-tactic p{font:700 clamp(14px,1.45vw,17px)/1.5 Arial,sans-serif;letter-spacing:.005em}

.controls{position:fixed;left:50%;bottom:14px;transform:translateX(-50%);z-index:100;display:flex;align-items:center;justify-content:center;gap:8px;flex-wrap:wrap;width:max-content;max-width:calc(100vw - 24px);padding:9px 12px;border:1px solid rgba(229,189,130,.46);border-radius:18px;background:rgba(5,17,30,.94);box-shadow:0 12px 34px rgba(0,0,0,.48);backdrop-filter:blur(10px)}#skip{visibility:hidden;opacity:0;pointer-events:none;transition:opacity .15s ease}button{border:1px solid rgba(229,189,130,.6);background:#112a45;color:#f7f1e8;padding:10px 14px;border-radius:999px;cursor:pointer;font:700 12px Arial,sans-serif;letter-spacing:.04em}button:hover{background:#204769}button:focus-visible{outline:3px solid #fff;outline-offset:2px}button.primary{background:#9b6d39;border-color:#e4bd82;color:#101e2e}#progress{font:12px Arial,sans-serif;color:rgba(255,255,255,.75);min-width:70px;text-align:center}#bar{width:min(240px,22vw);height:4px;background:rgba(255,255,255,.18);border-radius:99px;overflow:hidden}#barFill{height:100%;width:0;background:var(--gold);transition:width .35s ease}
details.credits{position:absolute;bottom:8px;right:14px;color:#d9dfe5;font:11px Arial,sans-serif;z-index:20}details.credits summary{cursor:pointer}details.credits ul{max-height:35vh;overflow:auto;background:rgba(5,14,25,.94);padding:12px 28px;border-radius:10px;max-width:340px}details.credits a{color:#e6c18c}
@media(max-width:760px){.transition-cards{grid-template-columns:1fr;gap:10px;width:min(92%,640px)}.transition-card{min-height:0;padding:13px 16px 14px;border-radius:12px}.transition-card-head{gap:9px;padding-bottom:8px;margin-bottom:8px}.transition-card-mark{width:31px;height:31px;flex-basis:31px;border-radius:9px;font-size:18px}.transition-card-label{font-size:9px}.transition-card-subtitle{font-size:8px}.transition-card-number{font-size:8px;padding:4px 7px}.transition-card p{font-size:14px;line-height:1.38}}
@media(max-width:680px){#deck{padding:8px;gap:8px}#stage{width:94vw;height:76vh;aspect-ratio:auto}.slide-frame{padding:22px}.slide p{font-size:15px;line-height:1.43;margin-bottom:11px}h1{font-size:30px;margin-bottom:16px}.hero-icon{width:60px}.image-credit{display:none}button{padding:9px 11px;font-size:11px}#bar{width:90px}.trans-content{gap:9px;padding:12px;width:100%}.trans-icons{gap:10px}.trans-icon{width:92px;height:62px}.transition-cards{width:min(94%,620px);gap:8px}.transition-card{padding:10px 12px}.transition-card-head{padding-bottom:7px;margin-bottom:7px}.transition-card p{font-size:13px;line-height:1.32}}
@media(max-height:620px) and (min-width:761px){.trans-content{gap:8px;padding:10px}.trans-icon{height:64px;width:110px}.transition-cards{gap:10px}.transition-card{min-height:118px;padding:12px 15px}.transition-card-head{padding-bottom:8px;margin-bottom:8px}.transition-card p{font-size:13px;line-height:1.35}}
@media(prefers-reduced-motion:reduce){*,*::before,*::after{animation-duration:.01ms!important;animation-iteration-count:1!important;transition-duration:.01ms!important}/* Preserve the full seven-second transformation even when reduced motion is enabled. */#transition.active .trans-icon.old,#transition.active .trans-icon.next,#transition.active .travel-line,#transition.active .action-lines{animation-duration:7s!important;animation-iteration-count:1!important}#transition.active .muzzle-flash{animation-duration:.7s!important;animation-delay:1.3s!important;animation-iteration-count:1!important}}


</style></head><body>
<svg aria-hidden="true" style="position:absolute;width:0;height:0;overflow:hidden" xmlns="http://www.w3.org/2000/svg">
<defs>
<symbol id="i-battleship" viewbox="0 0 220 100"><path d="M15 66 L198 66 L178 84 L48 84 Z"></path><path d="M54 65 L66 48 L87 48 L93 37 L125 37 L133 50 L166 50 L175 65"></path><path d="M76 48 L76 34 L91 34 L91 48 M104 37 L104 24 L126 24 L126 37 M145 50 L145 39 L160 39 L160 50"></path><path d="M32 91 Q53 83 74 91 T116 91 T158 91 T199 91"></path><path d="M42 48 L42 40 L62 40 L62 48 M116 25 L116 15 M110 21 L122 21"></path><path d="M76 34 L63 30 M133 50 L149 50"></path></symbol>
<symbol id="i-anchor" viewbox="0 0 100 100"><circle cx="50" cy="15" r="9"></circle><path d="M50 24 V78 M30 42 H70 M18 60 C20 80 34 89 50 89 C66 89 80 80 82 60 M18 60 L8 69 M82 60 L92 69 M50 78 L40 70 M50 78 L60 70"></path></symbol>
<symbol id="i-plane" viewbox="0 0 140 90"><path d="M10 48 L59 39 L84 8 L97 8 L91 39 L126 44 L132 51 L90 56 L100 76 L90 79 L68 58 L26 61 L10 56 Z"></path><path d="M50 41 L73 42 M59 57 L75 57"></path></symbol>
<symbol id="i-submarine" viewbox="0 0 220 90"><path d="M15 51 Q42 35 84 36 L185 36 Q205 42 210 53 Q201 66 182 67 L84 67 Q42 69 15 51Z"></path><path d="M94 36 L101 20 L130 20 L140 36 M115 20 L115 10 M127 20 L127 8"></path><path d="M15 51 L4 43 L4 59 Z M210 53 L218 43 L218 63 Z"></path><path d="M60 71 Q79 79 98 71 T136 71 T174 71"></path></symbol>
<symbol id="i-captain" viewbox="0 0 100 110"><path d="M19 42 Q50 10 81 42 L76 52 L24 52 Z M14 52 H86 L80 60 H20 Z"></path><path d="M50 61 C27 61 19 74 18 96 L82 96 C81 74 73 61 50 61Z"></path><path d="M36 77 H64 M42 87 H58"></path><path d="M42 37 H58 M50 28 V42"></path></symbol>
<symbol id="i-crosshair" viewbox="0 0 100 100"><circle cx="50" cy="50" r="29"></circle><circle cx="50" cy="50" r="8"></circle><path d="M50 4 V29 M50 71 V96 M4 50 H29 M71 50 H96"></path></symbol>
<symbol id="i-turret" viewbox="0 0 140 100"><path d="M20 75 H120 L111 90 H29 Z M37 75 L44 51 H97 L108 75"></path><path d="M61 51 L56 35 H95 L101 51 M90 38 L132 28 M88 44 L130 37"></path><path d="M33 91 H111"></path><path d="M132 28 L139 25 M132 37 L139 37"></path></symbol>
<symbol id="i-compass" viewbox="0 0 100 100"><circle cx="50" cy="50" r="42"></circle><path d="M50 13 L61 49 L50 87 L39 51 Z M13 50 H87 M50 13 V87"></path><circle cx="50" cy="50" r="5"></circle></symbol>
<symbol id="i-medal" viewbox="0 0 100 110"><path d="M30 8 H45 L50 38 L55 8 H70 L61 47 H39 Z"></path><circle cx="50" cy="69" r="25"></circle><path d="M50 52 L55 64 L69 65 L58 74 L61 87 L50 80 L39 87 L42 74 L31 65 L45 64 Z"></path></symbol>
<symbol id="i-radar" viewbox="0 0 120 100"><path d="M60 84 V16 M60 84 H103 M60 84 H17"></path><path d="M60 84 A26 26 0 0 1 86 58 M60 84 A46 46 0 0 1 106 38"></path><path d="M60 84 L93 39"></path><circle cx="60" cy="84" r="5"></circle><circle cx="93" cy="39" r="5"></circle></symbol>
<symbol id="i-fleet" viewbox="0 0 240 100"><path d="M10 70 L95 70 L82 87 L24 87 Z M94 70 L180 70 L166 87 L109 87 Z M174 70 L231 70 L219 87 L186 87 Z"></path><path d="M38 70 L50 50 L75 50 L82 70 M125 70 L135 42 L160 42 L172 70 M195 70 L202 55 L216 55 L222 70"></path><path d="M50 49 V37 M139 42 V30 M204 55 V44"></path><path d="M18 94 Q41 88 64 94 T110 94 T156 94 T202 94"></path></symbol>
</defs></svg>
<div id="deck">
<div aria-live="polite" id="stage"><section aria-label="Slide 1: THERE IS NO TEAM, IT IS A YOLO!" class="slide" data-icon="battleship" data-index="0" hidden="">
<img alt="Official World of Warships wallpaper collection" class="slide-bg" loading="eager" src="https://wowsp-wows-eu.wgcdn.co/dcont/fb/image/58f5591c-4362-11ef-9a4b-b49691e6ead0.jpg"/>
<div class="slide-shade"></div>
<div class="slide-frame">
<div class="slide-top"><span class="kicker">THE ADMIRALTY CHRONICLES</span><svg aria-hidden="true" class="hero-icon"><use href="#i-battleship"></use></svg></div>
<h1>THERE IS NO TEAM, IT IS A YOLO!</h1><p>The Admiralty brings World of Warships PC players together for a competition built around individual performance. Damage is the usual starting measure, but each event can test a different skill through its announced scoring settings.</p><p>Players still fight in teams because the battle requires cooperation: spotting, creating crossfires, protecting positions, and securing objectives all matter. But a battle victory does not automatically decide the tournament standings. Teams fight the battles; individuals compete in the YOLO.</p><p>From a simple Pilot YOLO to the Road to the Grand YOLO, the format can grow without losing that central idea: there is no team, it is a YOLO!</p>

<div aria-hidden="true" class="icon-cluster"><svg><use href="#i-battleship"></use></svg><svg><use href="#i-plane"></use></svg><svg><use href="#i-submarine"></use></svg><svg><use href="#i-anchor"></use></svg></div>
<div class="slide-footer"><span>THE ADMIRALTY CHRONICLES</span><span>01 / 11</span></div>
</div>
<div class="image-credit">Image: <a href="https://wowsp-wows-eu.wgcdn.co/dcont/fb/image/58f5591c-4362-11ef-9a4b-b49691e6ead0.jpg" rel="noopener" target="_blank">Official World of Warships wallpaper collection</a></div>
</section><section aria-label="Slide 2: The idea behind YOLO" class="slide" data-icon="crosshair" data-index="1" hidden="">
<img alt="Official World of Warships Airship Escort gameplay" class="slide-bg" loading="eager" src="https://wows-wowsp-global.gcdn.co/media/ceph-image/7df29d78-54a3-11ee-ad47-ac162d70f4e4.jpg"/>
<div class="slide-shade"></div>
<div class="slide-frame">
<div class="slide-top"><span class="kicker">INDIVIDUAL PERFORMANCE, SHARED BATTLES</span><svg aria-hidden="true" class="hero-icon"><use href="#i-crosshair"></use></svg></div>
<h1>The idea behind YOLO</h1><p>YOLO is intended for the wider World of Warships PC community, especially clan players. Participants may be drafted into different lineups from one game or evening to the next, so a player is not permanently defined by a fixed roster or a clan's result.</p><p>By default, team wins and losses have little or no influence on individual bracket movement, seeding, or final standings. Damage is the central starting point, while the Admiralty can select kills, potential damage, torpedo hits, experience, survival, objectives, or a combination when a particular event calls for it.</p>

<div class="slide-footer"><span>THE ADMIRALTY CHRONICLES</span><span>02 / 11</span></div>
</div>
<div class="image-credit">Image: <a href="https://wows-wowsp-global.gcdn.co/media/ceph-image/7df29d78-54a3-11ee-ad47-ac162d70f4e4.jpg" rel="noopener" target="_blank">Official World of Warships Airship Escort gameplay</a></div>
</section><section aria-label="Slide 3: The Admiralty" class="slide" data-icon="captain" data-index="2" hidden="">
<img alt="Official World of Warships battle screenshot" class="slide-bg" loading="eager" src="https://wows-web-static.wgcdn.co/wowsp-cms-bundles/update-14-2/flagships_screen_2-48d1706c.jpg"/>
<div class="slide-shade"></div>
<div class="slide-frame">
<div class="slide-top"><span class="kicker">AUTHORITY WITH A HUMAN FACE</span><svg aria-hidden="true" class="hero-icon"><use href="#i-captain"></use></svg></div>
<h1>The Admiralty</h1><p>The Admiralty personifies the people who host and administer YOLO before, during, and after competition. Rowan “Anchor” Pierce represents command; Elias “Wake” Mercer defends standards; Ava “Chartroom” Keene and Mira “Valkyrie” Solano bring leadership and judgment.</p><p>Jonah “Tide” Bell brings mentorship, Victor “Spear” Moreno competitive instinct, Rafael “Quarterdeck” Ortiz practical organization, and Darius “Keel” Holt evidence integrity. Nia “Tideglass” Byrne, Rhea “Crosswind” Patel, and Selene Ward bring participant, support, and impartial-review perspectives. Their conversations can be warm, argumentative, or teasing, but their decisions must leave competitors knowing what has been chosen.</p>

<div class="slide-footer"><span>THE ADMIRALTY CHRONICLES</span><span>03 / 11</span></div>
</div>
<div class="image-credit">Image: <a href="https://wows-web-static.wgcdn.co/wowsp-cms-bundles/update-14-2/flagships_screen_2-48d1706c.jpg" rel="noopener" target="_blank">Official World of Warships battle screenshot</a></div>
</section><section aria-label="Slide 4: Pilot YOLO" class="slide" data-icon="battleship" data-index="3" hidden="">
<img alt="World of Warships Steam Store gameplay screenshot" class="slide-bg" loading="eager" src="https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/552990/9f38903d525fdce3bdb15691f0b8183eefd05b28/ss_9f38903d525fdce3bdb15691f0b8183eefd05b28.jpg"/>
<div class="slide-shade"></div>
<div class="slide-frame">
<div class="slide-top"><span class="kicker">A STANDALONE BEGINNER EVENT</span><svg aria-hidden="true" class="hero-icon"><use href="#i-battleship"></use></svg></div>
<h1>Pilot YOLO</h1><p>Pilot YOLO is a standalone introduction to the competition, not a permanent casual format. Its imagined evening lasts roughly two to three hours, begins with a ten-minute battle timer, and uses about seven games per participant as a planning estimate rather than a fixed limit.</p><p>Attendance is normally settled about an hour before play, with lineups arranged closer to the start. A six-human/six-bot room is one example; two humans against six bots, three against nine, six-versus-six, and nine-versus-nine are other possibilities. Bots generally fill vacancies unless the Admiralty says otherwise, and their movement or firing behavior can be configured to suit the activity.</p>

<div class="slide-footer"><span>THE ADMIRALTY CHRONICLES</span><span>04 / 11</span></div>
</div>
<div class="image-credit">Image: <a href="https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/552990/9f38903d525fdce3bdb15691f0b8183eefd05b28/ss_9f38903d525fdce3bdb15691f0b8183eefd05b28.jpg" rel="noopener" target="_blank">World of Warships Steam Store gameplay screenshot</a></div>
</section><section aria-label="Slide 5: The Road to the Grand YOLO" class="slide" data-icon="compass" data-index="4" hidden="">
<img alt="Official World of Warships carrier gameplay" class="slide-bg" loading="eager" src="https://wowsp-wows-eu.wgcdn.co/dcont/fb/image/99bc1152-f97a-11e4-a8d3-000c299b2956.jpg"/>
<div class="slide-shade"></div>
<div class="slide-frame">
<div class="slide-top"><span class="kicker">A SEASON OF INDIVIDUAL STANDINGS</span><svg aria-hidden="true" class="hero-icon"><use href="#i-compass"></use></svg></div>
<h1>The Road to the Grand YOLO</h1><p>The Road to the Grand YOLO is the larger season journey, connecting regular events, possible postseason play, and the season-ending championship. A twelve-stage season is one possible structure, not a required calendar; the Admiralty selects the length, dates, evenings, rounds, and games per participant for the actual season.</p><p>Random drafting is the normal preference because it gives players changing teammates and opponents. Registration, eligibility, mercenaries or stand-ins, map rotation, lineup visibility, and qualification are all governed by the announced season configuration. Special events such as the Race can contribute to season standings or remain separate, but that choice must be clear before they begin.</p>

<div class="slide-footer"><span>THE ADMIRALTY CHRONICLES</span><span>05 / 11</span></div>
</div>
<div class="image-credit">Image: <a href="https://wowsp-wows-eu.wgcdn.co/dcont/fb/image/99bc1152-f97a-11e4-a8d3-000c299b2956.jpg" rel="noopener" target="_blank">Official World of Warships carrier gameplay</a></div>
</section><section aria-label="Slide 6: Scoring and advancement" class="slide" data-icon="turret" data-index="5" hidden="">
<img alt="Official World of Warships submarine gameplay" class="slide-bg" loading="eager" src="https://wows-wowsp-global.gcdn.co/media/ceph-image/7e6d7444-409f-11ed-a035-8cdcd4b147d4.jpg"/>
<div class="slide-shade"></div>
<div class="slide-frame">
<div class="slide-top"><span class="kicker">DAMAGE FIRST — OTHER METRICS BY DESIGN</span><svg aria-hidden="true" class="hero-icon"><use href="#i-turret"></use></svg></div>
<h1>Scoring and advancement</h1><p>Damage is the usual competitive starting point, but an event may score kills, potential damage, torpedo hits, XP, credits, survival, objective performance, or a combination. Different rounds can use different measures, and the required evidence must match the metrics selected for that round.</p><p>Individual performance normally drives advancement and standings; team victories matter only when the chosen configuration explicitly includes them. Where Doubloons are used, the announced pool and formula determine each participant's award. The Excel workbook is a participant-facing way to explore scoring examples—not the authority that approves the event's final calculation—and real prize pools are distributed under their announced award rules.</p>

<div class="slide-footer"><span>THE ADMIRALTY CHRONICLES</span><span>06 / 11</span></div>
</div>
<div class="image-credit">Image: <a href="https://wows-wowsp-global.gcdn.co/media/ceph-image/7e6d7444-409f-11ed-a035-8cdcd4b147d4.jpg" rel="noopener" target="_blank">Official World of Warships submarine gameplay</a></div>
</section><section aria-label="Slide 7: The Race" class="slide" data-icon="submarine" data-index="6" hidden="">
<img alt="World of Warships naval battle wallpaper" class="slide-bg" loading="eager" src="https://www.4gamer.net/games/138/G013889/20210617034/SS/002.jpg"/>
<div class="slide-shade"></div>
<div class="slide-frame">
<div class="slide-top"><span class="kicker">A DIFFERENT ROUTE TO THE GRAND YOLO</span><svg aria-hidden="true" class="hero-icon"><use href="#i-submarine"></use></svg></div>
<h1>The Race</h1><p>The Race is optional and may be a standalone activity or part of the season. One suggested version uses Ocean and a southwest-to-northeast route, with eligibility, duration, and starting positions selected for that event. Stationary bots are a familiar setup, but the Admiralty determines whether they fire and what obstacles or restrictions apply.</p><p>The intended time measure is inverse time, 1/t, so a faster valid finish earns a stronger time result. First-finisher bonuses and death penalties are optional modifiers, not automatic rules. Race damage can also count wherever the scoring configuration recognizes it, allowing the Race to affect individual standings or postseason seeding when announced.</p>

<div class="slide-footer"><span>THE ADMIRALTY CHRONICLES</span><span>07 / 11</span></div>
</div>
<div class="image-credit">Image: <a href="https://www.4gamer.net/games/138/G013889/20210617034/SS/002.jpg" rel="noopener" target="_blank">World of Warships naval battle wallpaper</a></div>
</section><section aria-label="Slide 8: Grand YOLO" class="slide" data-icon="medal" data-index="7" hidden="">
<img alt="World of Warships naval battle screenshot" class="slide-bg" loading="eager" src="https://wows-wowsp-global.gcdn.co/media/ceph-image/7df29d78-54a3-11ee-ad47-ac162d70f4e4.jpg"/>
<div class="slide-shade"></div>
<div class="slide-frame">
<div class="slide-top"><span class="kicker">THE SUPER BOWL OF THE TOURNAMENT</span><svg aria-hidden="true" class="hero-icon"><use href="#i-medal"></use></svg></div>
<h1>Grand YOLO</h1><p>Grand YOLO is the season-ending championship—the Super Bowl of the tournament. Round robin is the preferred starting format, while best-of-three, best-of-five, and other structures can be selected to suit the number of qualifiers and the kind of final challenge the Admiralty wants to create.</p><p>The championship is intended to recognize several forms of individual achievement rather than treating one team result as the entire story. Multiple award categories can reward different strengths, and regular-season events, special activities, and Race results may contribute when the published qualification and scoring arrangements say they do.</p>

<div class="slide-footer"><span>THE ADMIRALTY CHRONICLES</span><span>08 / 11</span></div>
</div>
<div class="image-credit">Image: <a href="https://wows-wowsp-global.gcdn.co/media/ceph-image/7df29d78-54a3-11ee-ad47-ac162d70f4e4.jpg" rel="noopener" target="_blank">World of Warships naval battle screenshot</a></div>
</section><section aria-label="Slide 9: Evidence, trust, and DWBOT" class="slide" data-icon="radar" data-index="8" hidden="">
<img alt="Official World of Warships wallpaper collection" class="slide-bg" loading="eager" src="https://wowsp-wows-eu.wgcdn.co/dcont/fb/image/58f5591c-4362-11ef-9a4b-b49691e6ead0.jpg"/>
<div class="slide-shade"></div>
<div class="slide-frame">
<div class="slide-top"><span class="kicker">THE RESULT MUST BE UNDERSTANDABLE</span><svg aria-hidden="true" class="hero-icon"><use href="#i-radar"></use></svg></div>
<h1>Evidence, trust, and DWBOT</h1><p>Screenshots remain required evidence. Replays, OCR extraction, and a Python-generated report may add useful detail, but automated processing does not replace human verification. Participants review and authenticate their own values before final submission, and the event's chosen fields determine what evidence must be checked.</p><p>Evidence is retained for at least forty-eight hours, with disputed material preserved until the issue is resolved. The event owner operates DWBOT and must have Discord administrator access. Its participant browser reader presents official settings, announcements, scores, corrections, and results so that competitors can see the information used to administer the event.</p>

<div class="slide-footer"><span>THE ADMIRALTY CHRONICLES</span><span>09 / 11</span></div>
</div>
<div class="image-credit">Image: <a href="https://wowsp-wows-eu.wgcdn.co/dcont/fb/image/58f5591c-4362-11ef-9a4b-b49691e6ead0.jpg" rel="noopener" target="_blank">Official World of Warships wallpaper collection</a></div>
</section><section aria-label="Slide 10: Many configurations, one YOLO" class="slide" data-icon="anchor" data-index="9" hidden="">
<img alt="Official World of Warships battle screenshot" class="slide-bg" loading="eager" src="https://wows-web-static.wgcdn.co/wowsp-cms-bundles/update-14-2/flagships_screen_2-48d1706c.jpg"/>
<div class="slide-shade"></div>
<div class="slide-frame">
<div class="slide-top"><span class="kicker">STANDING RULES, EVENT SETTINGS, ONE-TIME EXCEPTIONS</span><svg aria-hidden="true" class="hero-icon"><use href="#i-anchor"></use></svg></div>
<h1>Many configurations, one YOLO</h1><p>The Admiralty can configure maps, bots, metrics, formulas, schedules, brackets, streaming permissions, rosters, and special activities to suit each event. Standing rules remain in force until changed; a one-time exception applies only to the occasion it names and does not silently rewrite the wider tournament settings.</p><p>Material changes must be announced at least one hour before the affected matches, including who issued the decision, what it changes, and when it takes effect. Completed matches and finalized results are not altered retroactively. The v3.22 package is a tentative general reference, while the Pilot YOLO story, sample brackets, and ten-week Admiralty heritage arc remain illustrative rather than mandatory history.</p>

<div class="slide-footer"><span>THE ADMIRALTY CHRONICLES</span><span>10 / 11</span></div>
</div>
<div class="image-credit">Image: <a href="https://wows-web-static.wgcdn.co/wowsp-cms-bundles/update-14-2/flagships_screen_2-48d1706c.jpg" rel="noopener" target="_blank">Official World of Warships battle screenshot</a></div>
</section><section aria-label="Slide 11: The future is open" class="slide" data-icon="fleet" data-index="10" hidden="">
<img alt="Official World of Warships wallpaper collection" class="slide-bg" loading="eager" src="https://wowsp-wows-eu.wgcdn.co/dcont/fb/image/58f5591c-4362-11ef-9a4b-b49691e6ead0.jpg"/>
<div class="slide-shade"></div>
<div class="slide-frame">
<div class="slide-top"><span class="kicker">THERE IS NO TEAM, IT IS A YOLO!</span><svg aria-hidden="true" class="hero-icon"><use href="#i-fleet"></use></svg></div>
<h1>The future is open</h1><p>One YOLO may reward damage; another may test potential damage, torpedo hits, survival, or objective control. A Race can add route choice and time management, while a special battle can change the pace through a shorter timer or a different ruleset. Each activity remains part of the same competition because its conditions are selected and explained before players take part.</p><p>The Admiralty chooses the challenge, participants bring their ambition and skill, and verified results establish the outcome. The format can become more demanding without losing its individual focus or its place in the wider community. Teams fight the battles. Individuals compete in the tournament. There is no team, it is a YOLO!</p>

<div aria-hidden="true" class="icon-cluster"><svg><use href="#i-battleship"></use></svg><svg><use href="#i-plane"></use></svg><svg><use href="#i-submarine"></use></svg><svg><use href="#i-anchor"></use></svg></div>
<div class="slide-footer"><span>THE ADMIRALTY CHRONICLES</span><span>11 / 11</span></div>
</div>
<div class="image-credit">Image: <a href="https://wowsp-wows-eu.wgcdn.co/dcont/fb/image/58f5591c-4362-11ef-9a4b-b49691e6ead0.jpg" rel="noopener" target="_blank">Official World of Warships wallpaper collection</a></div>
</section>
<div aria-hidden="true" id="transition"><div class="trans-content"><div class="trans-title">Changing course</div><div class="trans-icons"><div class="travel-line"></div><div class="action-lines"></div><svg class="trans-icon old"><use href="#i-battleship" id="oldUse"></use></svg><svg class="trans-icon next"><use href="#i-anchor" id="newUse"></use></svg><div class="muzzle-flash"></div></div><div id="transText">One configuration gives way to another</div><div class="transition-cards" aria-label="Tournament rule and tactical briefing"><section aria-label="Tournament-wide rule" class="transition-card transition-rule"><div class="transition-card-head"><span class="transition-card-mark" aria-hidden="true">§</span><div class="transition-card-heading"><div class="transition-card-label">Tournament-wide rule</div><div class="transition-card-subtitle">Applies across the YOLO event</div></div><span class="transition-card-number" id="transRuleNum">RULE 01</span></div><p aria-live="polite" id="transRule">The announced configuration governs the event.</p></section><section aria-label="Tactical point" class="transition-card transition-tactic"><div class="transition-card-head"><span class="transition-card-mark" aria-hidden="true">⌖</span><div class="transition-card-heading"><div class="transition-card-label">Tactical point</div><div class="transition-card-subtitle">Battlefield guidance</div></div><span class="transition-card-number" id="transTacticNum">TACTIC 01</span></div><p aria-live="polite" id="transTactic">Build the lineup around vision, overlapping radar, crossfires, and objective control.</p></section></div></div></div>
</div>
<div class="controls">
<button aria-label="Previous slide" id="prev">← Previous</button>
<button class="primary" id="play">▶ Play</button>
<button aria-label="Next slide" id="next">Next →</button>
<button id="slower">Slower −</button><button id="faster">Faster +</button>
<button id="skip">Skip transition</button>
<span id="progress">01 / 11</span><div id="bar"><div id="barFill"></div></div>
</div>
<details class="credits"><summary>Image credits</summary><ul><li><a href="https://wowsp-wows-eu.wgcdn.co/dcont/fb/image/58f5591c-4362-11ef-9a4b-b49691e6ead0.jpg" rel="noopener" target="_blank">Official World of Warships wallpaper collection</a></li>
<li><a href="https://wows-wowsp-global.gcdn.co/media/ceph-image/7df29d78-54a3-11ee-ad47-ac162d70f4e4.jpg" rel="noopener" target="_blank">Official World of Warships Airship Escort gameplay</a></li>
<li><a href="https://wows-web-static.wgcdn.co/wowsp-cms-bundles/update-14-2/flagships_screen_2-48d1706c.jpg" rel="noopener" target="_blank">Official World of Warships battle screenshot</a></li>
<li><a href="https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/552990/9f38903d525fdce3bdb15691f0b8183eefd05b28/ss_9f38903d525fdce3bdb15691f0b8183eefd05b28.jpg" rel="noopener" target="_blank">World of Warships Steam Store gameplay screenshot</a></li>
<li><a href="https://wowsp-wows-eu.wgcdn.co/dcont/fb/image/99bc1152-f97a-11e4-a8d3-000c299b2956.jpg" rel="noopener" target="_blank">Official World of Warships carrier gameplay</a></li>
<li><a href="https://wows-wowsp-global.gcdn.co/media/ceph-image/7e6d7444-409f-11ed-a035-8cdcd4b147d4.jpg" rel="noopener" target="_blank">Official World of Warships submarine gameplay</a></li>
<li><a href="https://www.4gamer.net/games/138/G013889/20210617034/SS/002.jpg" rel="noopener" target="_blank">World of Warships naval battle wallpaper</a></li>
<li><a href="https://wows-wowsp-global.gcdn.co/media/ceph-image/7df29d78-54a3-11ee-ad47-ac162d70f4e4.jpg" rel="noopener" target="_blank">World of Warships naval battle screenshot</a></li>
<li><a href="https://wowsp-wows-eu.wgcdn.co/dcont/fb/image/58f5591c-4362-11ef-9a4b-b49691e6ead0.jpg" rel="noopener" target="_blank">Official World of Warships wallpaper collection</a></li>
<li><a href="https://wows-web-static.wgcdn.co/wowsp-cms-bundles/update-14-2/flagships_screen_2-48d1706c.jpg" rel="noopener" target="_blank">Official World of Warships battle screenshot</a></li>
<li><a href="https://wowsp-wows-eu.wgcdn.co/dcont/fb/image/58f5591c-4362-11ef-9a4b-b49691e6ead0.jpg" rel="noopener" target="_blank">Official World of Warships wallpaper collection</a></li></ul></details>
</div>
<script>
(() => {
 const slides = [...document.querySelectorAll('.slide')];
 const transition = document.getElementById('transition');
 const playBtn = document.getElementById('play');
 const skipBtn = document.getElementById('skip');
 const prevBtn = document.getElementById('prev');
 const nextBtn = document.getElementById('next');
 const progress = document.getElementById('progress');
 const fill = document.getElementById('barFill');
 const oldUse = document.getElementById('oldUse');
 const newUse = document.getElementById('newUse');
 const transText = document.getElementById('transText');
 const transRule = document.getElementById('transRule');
 const transTactic = document.getElementById('transTactic');
 const transRuleNum = document.getElementById('transRuleNum');
 const transTacticNum = document.getElementById('transTacticNum');
 const strategicTips = [
  'Build the lineup around vision, overlapping radar, crossfires, and objective control—not damage output alone.',
  'Call the radar target before activation, and make sure allied guns are loaded, aimed, and ready to punish the reveal.',
  'Keep the two destroyers on separate routes so the lineup can scout more than one approach without risking both in the same opening fight.',
  'Use different cruiser firing angles to force enemy ships to turn; avoid letting them angle against one predictable line of fire.',
  'Before exposing a cruiser, identify the likely return fire and the island, smoke screen, or retreat route that will let it disengage.',
  'Push only when allied support is ready, the local fight is favorable, and the enemy crossfire can be contained.',
  'Focus fire on the enemy whose removal creates the greatest immediate advantage, especially a destroyer or radar cruiser threatening the objective.',
  'When ahead on ships or points, preserve health, keep a ship spotting, and make the opponent cross dangerous firing lanes to contest you.',
  'When behind, rally around one achievable objective and isolate one opponent to create a temporary local numbers advantage.',
  'Defend the caps that matter rather than every lane; use protected positions and coordinated pressure to reset capture attempts.',
  'Treat smoke as concealment, not immunity: account for radar, hydro, torpedoes, blind fire, and the fact that smoke can hide the enemy too.'
 ];
 const tournamentRules = [
  'Individual advancement follows each participant’s configured performance; team wins and losses matter only when team scoring is explicitly enabled.',
  'The announced event configuration governs its ships, maps, scoring, roster, match procedures, and eligibility.',
  'A material rule or configuration change must be announced at least one hour before the affected matches.',
  'A one-time exception applies only to the match or circumstance it names; it does not change the standing tournament rules.',
  'Completed matches and finalized results are never changed retroactively.',
  'Each participant must review and authenticate their score data before making a final submission.',
  'Screenshots are required evidence; replays may provide additional support when the event enables them.',
  'OCR and automated reports can assist review, but human verification remains part of official score acceptance.',
  'An appeal must be reviewed by an official independent of the participant’s team and clan connections.',
  'Participants may inspect their scores, status, corrections, and appeals under the event’s published procedures.',
  'Every real prize pool committed to an event is distributed in full under its announced award rules.',
  'The event owner operates DWBOT and must have Discord administrator access; participants use its reader interface for official settings and results.'
 ];
 let index = 0, playing = false, holdMs = 9000, transitionMs = 7000, timer = null, pending = null, holdTimer=null, interludeIndex=0;
 function show(i) { index = (i + slides.length) % slides.length; slides.forEach((s,n)=>s.hidden=n!==index); transition.classList.remove('active'); skipBtn.style.visibility='hidden'; skipBtn.style.opacity='0'; skipBtn.style.pointerEvents='none'; update(); }
 function update() { progress.textContent=String(index+1).padStart(2,'0')+' / '+String(slides.length).padStart(2,'0'); fill.style.width=((index+1)/slides.length*100)+'%'; }
 function stopTimers() { clearTimeout(timer); clearTimeout(holdTimer); timer=holdTimer=null; }
 function beginTransition(to) {
   stopTimers(); pending=(to+slides.length)%slides.length;
   const oldIcon=slides[index].dataset.icon, newIcon=slides[pending].dataset.icon;
   oldUse.setAttribute('href','#i-'+oldIcon); newUse.setAttribute('href','#i-'+newIcon);
   transText.textContent=slides[pending].querySelector('h1').textContent;
   const ruleNumber = interludeIndex % tournamentRules.length;
   const tacticNumber = interludeIndex % strategicTips.length;
   transRule.textContent=tournamentRules[ruleNumber];
   transTactic.textContent=strategicTips[tacticNumber];
   transRuleNum.textContent='RULE ' + String(ruleNumber+1).padStart(2,'0');
   transTacticNum.textContent='TACTIC ' + String(tacticNumber+1).padStart(2,'0');
   interludeIndex++;
   transition.classList.remove('active'); void transition.offsetWidth; transition.classList.add('active'); skipBtn.style.visibility='visible'; skipBtn.style.opacity='1'; skipBtn.style.pointerEvents='auto';
   // Restart each transformation animation, then start the matching timer on that frame.
   // The next slide appears at the end of the seven-second animation, with no extra pause.
   requestAnimationFrame(()=>{
     transition.querySelectorAll('.trans-icon.old,.trans-icon.next,.travel-line,.action-lines,.muzzle-flash').forEach(el=>{
       el.style.animation='none'; void el.offsetWidth; el.style.animation='';
     });
     timer=setTimeout(()=>{ show(pending); if(playing) scheduleHold(); },transitionMs);
   });
 }
 function advance(delta) { if(transition.classList.contains('active')) { stopTimers(); show(index+delta); if(playing) scheduleHold(); return; } beginTransition(index+delta); }
 function scheduleHold() { stopTimers(); if(!playing) return; holdTimer=setTimeout(()=>beginTransition(index+1),holdMs); }
 function play() { playing=true; playBtn.textContent='Ⅱ Pause'; playBtn.classList.add('primary'); scheduleHold(); }
 function pause() { playing=false; stopTimers(); playBtn.textContent='▶ Play'; }
 prevBtn.addEventListener('click',()=>{ const was=playing; pause(); advance(-1); if(was) { /* manual navigation pauses automation intentionally */ } });
 nextBtn.addEventListener('click',()=>{ const was=playing; pause(); advance(1); });
 skipBtn.addEventListener('click',()=>{ if(pending!==null) { stopTimers(); show(pending); if(playing) scheduleHold(); } });
 playBtn.addEventListener('click',()=>playing?pause():play());
 document.getElementById('slower').addEventListener('click',()=>{ holdMs=Math.min(18000,holdMs+2000); document.getElementById('slower').textContent='Slower ('+(holdMs/1000).toFixed(0)+'s)'; });
 document.getElementById('faster').addEventListener('click',()=>{ holdMs=Math.max(4000,holdMs-2000); document.getElementById('faster').textContent='Faster ('+(holdMs/1000).toFixed(0)+'s)'; });
 document.addEventListener('keydown',e=>{ if(e.key==='ArrowRight') { pause(); advance(1); } else if(e.key==='ArrowLeft') { pause(); advance(-1); } else if(e.code==='Space') { e.preventDefault(); playing?pause():play(); } });
 show(0);
})();
</script></body></html>
