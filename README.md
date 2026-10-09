<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,100:7aa2f7&height=180&section=header&text=Pratham%20Panchal&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20@%20Barclays&descAlignY=58&descSize=18" width="100%"/>

  <a href="https://prathampanchal.dev">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1200&color=7AA2F7&center=true&vCenter=true&width=820&lines=Most+of+my+code+exists+because+a+tool+almost+did+what+I+needed;Built+OmniCompiler%2C+one+debugger+for+5+languages;Built+Scrub%2C+a+local+ffmpeg+GUI+that+lands+under+a+size+limit;Benchmarked+local+LLMs+over+4%2C101+runs+on+one+GPU" alt="Typing SVG" />
  </a>
</div>

<br>

## About

- 🏦 Software Engineer at **Barclays**, mainly Python and TypeScript/JavaScript (React, Node, Express), with C++ when performance is the actual constraint
- 🤖 Running local models and agent harnesses, and measuring what breaks
- 🏏⚽🏎️🏸🎾🎮 Off the keyboard: sports, all of it, cricket, football, F1, badminton, tennis, pickleball, squash, and gaming
- 🌐 Everything I have built, with a demo on each: **[prathampanchal.dev](https://prathampanchal.dev)**

<br>

## Tech Stack

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white">
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white">
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white">
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white">
</div>

<br>

## Projects

<table>
<tr>
<td width="50%" valign="top">

**[OmniCompiler](https://github.com/Pratham2994/OmniCompiler)**

Run, step-debug and translate code across Python, JavaScript, Java, C++ and Go from one interface. Debugging is driven by the real per-language debuggers (gdb, jdb, pdb, Delve) behind a single event protocol, not a simulated stepper. Every run gets its own Docker container. Research paper under review.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">

</td>
<td width="50%" valign="top">

**[Scrub](https://github.com/Pratham2994/Scrub)**

Local-only ffmpeg GUI, no server, no account, nothing leaves your machine. Give it a Discord, WhatsApp or email size limit and it two-pass encodes to land under it, instead of leaving you to guess a bitrate. The command it builds is shown on screen before it runs, and it's editable, so what you see is exactly what executes.

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB">
<img src="https://img.shields.io/badge/ffmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white">

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[LocaLLM](https://github.com/Pratham2994/LocaLLM)**

Which local model is worth running on one 12 GB card? A test harness around llama.cpp: 34 tasks of my own, 41 configurations, 4,101 runs, each answer checked by running tests or comparing SQL rows. It ranks models by correct answers per hour, not tokens per second, and the two rankings do not agree.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/llama.cpp-000000?style=flat-square">
<img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white">

</td>
<td width="50%" valign="top">

**[Prats-Deck](https://github.com/Pratham2994/Prats-Deck)**

Fifteen touch apps on a Raspberry Pi Pico 2 W: PC stats, macros, and a pet cat. C++ firmware taken from 5 to 40 frames a second with faster drawing code and the second core, and no torn frames. A simulator runs the same code on a PC, and a script taps the real deck over USB to test every app.

<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Raspberry%20Pi%20Pico-A22846?style=flat-square&logo=raspberrypi&logoColor=white">

</td>
</tr>
</table>

<div align="center">

**All ten projects, with a demo on each: [prathampanchal.dev](https://prathampanchal.dev)**

</div>

<br>

## Connect

<div align="center">
  <a href="https://prathampanchal.dev">
    <img src="https://img.shields.io/badge/Portfolio-1a1b27?style=for-the-badge&logo=googlechrome&logoColor=white">
  </a>
  <a href="https://prathampanchal.dev/Pratham-Panchal-Resume.pdf">
    <img src="https://img.shields.io/badge/Resume-7aa2f7?style=for-the-badge&logo=readdotcv&logoColor=white">
  </a>
  <a href="https://www.linkedin.com/in/pratham-panchal-abcd2994/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
  <a href="https://discord.com/users/478527719416791054">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
  </a>
  <a href="mailto:prathampanchal02994@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white">
  </a>
</div>

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,100:1a1b27&height=100&section=footer" width="100%"/>
