Commute · Student Level Demo
============================
Open index.html in a browser (Chrome works best). Keep all files in the same folder.

Files
- index.html          the whole game (HTML/CSS/JS in one file)
- carL.png / car123.png  L train and 1/2/3 train interiors (windows keyed transparent)
- p_hero.png          hero, seated (on the train)
- p_hero_stand.png    hero, standing (on platforms; cropped from the crowd art)
- p_man.png, p_woman.png  other riders
- crowd.png           crowd (busy platforms + "rush" event)
- phone.png           pixel phone frame + home screen

Where to tweak things (search in index.html)
- DELAY_P            chance of a major delay per ride (now 0.30)
- rate()             pacing: how fast time runs in tunnels / at stops / on platforms
- DUR                how long download / read / submit / send take (seconds on screen)
- EV                 per-station MTA service-alert counts used to place delays
- READING, QUIZ      reading text and questions
- popup(... [8,1])   8 = seconds before doors close in a decision pop-up

Data sources
- MTA Subway Schedules 2026 (Wed 2026-08-12) - train times
- MTA Subway Customer Journey-Focused Metrics - real lateness rates (end card)
- MTA Service Alerts, Oct 2025 - Sep 2026 - where/what delays happen
- NYC 311 rat complaints, MTA hourly ridership - rats and crowds
