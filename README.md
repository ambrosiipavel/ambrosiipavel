Ambrosii Pavel

Frontend developer from Chișinău, Moldova. I build websites and Telegram bots.

Most of my work is small, self-contained things that have to actually run: a landing page that loads fast and collects real enquiries, a bot that keeps working when someone types the wrong thing into it.

Stack: HTML5 · CSS3 · JavaScript · Python · aiogram · SQLAlchemy · SQLite · Git · Figma

Projects
vultur-club — bilingual landing page

Live demo →

Website for a martial arts club in Chișinău. Romanian and English, switched without a page reload. Schedule filtered by discipline, today's row highlighted automatically, working contact form. Responsive down to small phones; the schedule table turns into cards on mobile. Motion is disabled when the visitor asks the system to reduce it.

HTML CSS JavaScript Netlify

hr-track-bot — recruitment CRM inside Telegram

Internal bot with three roles. A recruiter adds a candidate and assigns a coordinator; the coordinator sees only their own candidates and moves them through a status pipeline; the admin gets statistics, search and an Excel export. Every status change is written to history with who changed it and when. A candidate can only be closed with a final status, and a rejection requires a reason. Daily reminders for stalled candidates and scheduled callbacks.

Access is enforced server-side, not by hiding buttons — a coordinator cannot open someone else's candidate even by crafting a request.

Python aiogram 3 SQLAlchemy APScheduler openpyxl

lead-radar — job listener for Telegram channels

Listens to chosen channels through Telethon and scores every post: keywords, region, a budget figure in the text, minus points for noise like courses and crypto. Anything above the threshold arrives as a DM with an explanation of why it matched.

The same job gets reposted across five channels, so posts are deduplicated by a hash of the normalised text — links, mentions, punctuation and emoji stripped. Per-channel statistics show which sources are worth keeping.

Python Telethon aiogram 3 SQLAlchemy

Contact
Freelancehunt — kingmemacik
Telegram — @kingmemacik
Email — ambrosii.pavel@ceiti.md

Working remotely, UTC+2. I speak Russian, English (B2) and Romanian (B2).
