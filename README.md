<!-- ═══════════════════════════ HERO ═══════════════════════════ --> <div align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00cc90,100:b060f0&height=200&section=header&text=prabhdeep.exe&fontSize=64&fontColor=ffffff&fontAlignY=38&animation=twinkling&desc=backend%20%E2%80%A2%20security%20%E2%80%A2%20privacy-first%20infra&descAlignY=60&descSize=18" width="100%"/> <a href="https://github.com/Prabhdeep1701"> <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2600&pause=700&color=00CC90&center=true&vCenter=true&width=700&lines=%3E+building+things+that+are+hard+to+break+%F0%9F%94%92;%3E+IT+Intern+%40+Orient+Electric+%E2%9A%A1;%3E+ex-SDE+Intern+%40+Lemma+%F0%9F%A7%A0;%3E+E2E+encryption+enjoyer+%F0%9F%95%B6%EF%B8%8F;%3E+arch+btw+%F0%9F%90%A7" alt="typing intro"/> </a> <br/>

<a href="https://portfolio-pi-ten-1w59qqcw3z.vercel.app/"><img src="https://img.shields.io/badge/✦_portfolio-00cc90?style=for-the-badge&labelColor=0d1117"/></a> <a href="https://www.linkedin.com/in/prabhdeep-singh-313359242/"><img src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117"/></a> <a href="mailto:prabhdeep1701@gmail.com"><img src="https://img.shields.io/badge/say_hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117"/></a> <img src="https://komarev.com/ghpvc/?username=Prabhdeep1701&color=b060f0&style=for-the-badge&label=👀+VIEWS"/>

</div> <br/> <!-- ═══════════════════════════ WHOAMI ═══════════════════════════ -->
console
prabhdeep@arch:~$ whoami
> Prabhdeep Singh — software engineer, security nerd, CSE @ Bennett University ('24–'28)

prabhdeep@arch:~$ cat status.txt
> 📍 Greater Noida, India
> ⚡ IT Intern @ Orient Electric
> 🏛️ Deputy Minister of Digital Infrastructure — Bennett University Student Cabinet
> 🧠 rn learning: blockchain security + zero-knowledge proofs
> 🤖 side quest: agentic AI workflows (Claude Code, n8n, Langflow)

prabhdeep@arch:~$ echo $VIBE
> if it can be broken, i want to break it first.
<!-- ═══════════════════════════ FEATURED ═══════════════════════════ -->
🏆 the main character builds

[!TIP] each project has a how it works dropdown 👇 click to peek under the hood.

<br/>
🔐 WRAITH — dark web messenger

ultra-private, end-to-end encrypted chat for dark web browsers. messages are encrypted on your device and only decrypted by the recipient. the server just relays ciphertext.

<p> <img src="https://img.shields.io/badge/Flask--SocketIO-0d1117?style=flat-square&logo=socketdotio&logoColor=00cc90"/> <img src="https://img.shields.io/badge/PyCryptodome-0d1117?style=flat-square&logo=letsencrypt&logoColor=00cc90"/> <img src="https://img.shields.io/badge/PyQt6-0d1117?style=flat-square&logo=qt&logoColor=00cc90"/> <img src="https://img.shields.io/badge/real--time-0d1117?style=flat-square&logo=lightning&logoColor=00cc90"/> </p> <details> <summary><b>⚙️ how it works</b></summary> <br/>
encrypt locally
Flask-SocketIO
real-time push
decrypt locally
🧑 sender · PyQt6 app
🔒 ciphertext
📡 relay server
🧑 recipient
💬 plaintext
encryption + decryption happen only on the clients (PyCryptodome)
relay never sees plaintext — it just moves encrypted blobs
native desktop client built with PyQt6
</details>

<a href="https://github.com/Prabhdeep1701/WRAITH"><img src="https://img.shields.io/badge/→_view_repo-00cc90?style=for-the-badge&logo=github&logoColor=black"/></a>

🔧 RetroWraith — minimal linux recovery environment

a bootable Arch Linux ISO for when your system is cooked. offline disk access and recovery from a USB stick. terminal-only, ncurses UI, zero graphical dependencies. (there's a research paper too 📄)

<p> <img src="https://img.shields.io/badge/Arch_Linux-0d1117?style=flat-square&logo=archlinux&logoColor=b060f0"/> <img src="https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=b060f0"/> <img src="https://img.shields.io/badge/ncurses-0d1117?style=flat-square&logo=gnubash&logoColor=b060f0"/> <img src="https://img.shields.io/badge/USB_bootable-0d1117?style=flat-square&logo=usb&logoColor=b060f0"/> </p> <details> <summary><b>⚙️ how it works</b></summary> <br/>
boot
💾 USB stick
🐧 minimal Arch ISO
🖥️ ncurses TUI
📂 mount + browse disks
🛠️ recovery tools
✅ files rescued
boots on almost anything, no GUI needed
whole flow is driven from a keyboard-friendly terminal UI
fully offline, no network required
</details>

<a href="https://github.com/Prabhdeep1701/RetroWraith"><img src="https://img.shields.io/badge/→_view_repo-b060f0?style=for-the-badge&logo=github&logoColor=white"/></a> <a href="#"><img src="https://img.shields.io/badge/📄_read_the_paper-0d1117?style=for-the-badge"/></a>

🛡️ Talon — bug bounty automation

recon on autopilot. chains Nmap scanning, BeautifulSoup scraping and Selenium browser automation into one pipeline for full web security assessments.

<p> <img src="https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=f5a623"/> <img src="https://img.shields.io/badge/Nmap-0d1117?style=flat-square&logo=gnubash&logoColor=f5a623"/> <img src="https://img.shields.io/badge/BeautifulSoup-0d1117?style=flat-square&logo=python&logoColor=f5a623"/> <img src="https://img.shields.io/badge/Selenium-0d1117?style=flat-square&logo=selenium&logoColor=f5a623"/> </p> <details> <summary><b>⚙️ how it works</b></summary> <br/>
🎯 target
Nmap · ports + services
BeautifulSoup · crawl +scrape
Selenium · dynamic pages
📋 assessment report
</details>

<a href="https://github.com/Prabhdeep1701/Talon"><img src="https://img.shields.io/badge/→_view_repo-f5a623?style=for-the-badge&logo=github&logoColor=black"/></a>

💾 RetroCloud — distributed encrypted storage

giving old laptops a second life as encrypted cloud nodes. E2E encryption, plausible deniability, and reachable from anywhere through encrypted tunnels.

<p> <img src="https://img.shields.io/badge/Flask-0d1117?style=flat-square&logo=flask&logoColor=e060c0"/> <img src="https://img.shields.io/badge/pyngrok-0d1117?style=flat-square&logo=ngrok&logoColor=e060c0"/> <img src="https://img.shields.io/badge/E2E_encrypted-0d1117?style=flat-square&logo=letsencrypt&logoColor=e060c0"/> <img src="https://img.shields.io/badge/♻️_upcycled_hardware-0d1117?style=flat-square"/> </p> <details> <summary><b>⚙️ how it works</b></summary> <br/>
encrypted tunnel · ngrok
📱 you, anywhere
Flask API
💻 old laptop node
💻 old laptop node
💻 old laptop node
</details>

<a href="https://github.com/Prabhdeep1701/RetroCloud"><img src="https://img.shields.io/badge/→_view_repo-e060c0?style=for-the-badge&logo=github&logoColor=black"/></a>

🧠 Secure Quiz Platform — built @ Lemma

AI-powered quiz platform with anti-cheating built in. shipped during my SDE internship at Lemma.

<a href="https://secure-quiz-platform2.vercel.app"><img src="https://img.shields.io/badge/🟢_try_it_live-00cc90?style=for-the-badge&logo=vercel&logoColor=black"/></a>

<br/> <!-- ═══════════════════════════ STACK ═══════════════════════════ -->
🧰 the toolkit
<div align="center">

languages<br/> <img src="https://skillicons.dev/icons?i=python,java,c,cpp,js,ts,rust,html,css&theme=dark" />

frameworks<br/> <img src="https://skillicons.dev/icons?i=flask,fastapi,django,react,nextjs,qt&theme=dark" />

data + infra<br/> <img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,supabase,mysql,docker,vercel&theme=dark" />

daily drivers<br/> <img src="https://skillicons.dev/icons?i=arch,linux,apple,git,sklearn,selenium&theme=dark" />

security arsenal<br/> <img src="https://img.shields.io/badge/Nmap-0d1117?style=for-the-badge&logo=gnubash&logoColor=f5a623"/> <img src="https://img.shields.io/badge/Burp_Suite-0d1117?style=for-the-badge&logo=portswigger&logoColor=f5a623"/> <img src="https://img.shields.io/badge/Wireshark-0d1117?style=for-the-badge&logo=wireshark&logoColor=f5a623"/> <img src="https://img.shields.io/badge/Metasploit-0d1117?style=for-the-badge&logo=metasploit&logoColor=f5a623"/> <img src="https://img.shields.io/badge/Kali-0d1117?style=for-the-badge&logo=kalilinux&logoColor=f5a623"/> <img src="https://img.shields.io/badge/SOCKS5-0d1117?style=for-the-badge&logo=torproject&logoColor=f5a623"/>

agentic AI<br/> <img src="https://img.shields.io/badge/Claude_Code-0d1117?style=for-the-badge&logo=anthropic&logoColor=b060f0"/> <img src="https://img.shields.io/badge/Ollama-0d1117?style=for-the-badge&logo=ollama&logoColor=b060f0"/> <img src="https://img.shields.io/badge/n8n-0d1117?style=for-the-badge&logo=n8n&logoColor=b060f0"/> <img src="https://img.shields.io/badge/Langflow-0d1117?style=for-the-badge&logo=langchain&logoColor=b060f0"/> <img src="https://img.shields.io/badge/RAG-0d1117?style=for-the-badge&logo=openai&logoColor=b060f0"/>

</div> <!-- ═══════════════════════════ STATS ═══════════════════════════ -->
📊 the receipts
<div align="center"> <img src="https://streak-stats.demolab.com/?user=Prabhdeep1701&theme=tokyonight&hide_border=true&background=0d1117&ring=00cc90&fire=b060f0&currStreakNum=00cc90&sideNums=ffffff&currStreakLabel=00cc90&sideLabels=8b949e&dates=8b949e" width="49%"/> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Prabhdeep1701&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00cc90&text_color=c9d1d9" width="40%"/> <img src="https://github-readme-activity-graph.vercel.app/graph?username=Prabhdeep1701&bg_color=0d1117&color=00cc90&line=b060f0&point=ffffff&area=true&area_color=00cc90&hide_border=true" width="100%"/> <img src="https://raw.githubusercontent.com/Prabhdeep1701/Prabhdeep1701/output/github-snake-dark.svg" width="100%" alt="snake eating my contributions"/> </div> <!-- ═══════════════════════════ FOOTER ═══════════════════════════ --> <div align="center">
diff
+ open to: backend • security • infra problems that keep you up at night
- not open to: insecure-by-default anything

got something hard to break? let's build it. ⚡

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:b060f0,50:00cc90,100:0d1117&height=120&section=footer" width="100%"/> </div>
