<h1 align="center">Sergi Martí</h1>

<p align="center">
  <b>Software developer</b> · macOS apps, back end and AI tools · Barcelona, Spain 🇪🇸<br>
  Enterprise Oracle apps by day; native macOS tools, Python services and AI agents by night.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/martisergi/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://ko-fi.com/seergiii"><img src="https://img.shields.io/badge/Ko--fi-ff5e5b?style=for-the-badge&logo=kofi&logoColor=white" alt="Ko-fi"></a>
  <a href="https://github.com/sponsors/BySergiMM"><img src="https://img.shields.io/badge/Sponsor-ea4aaa?style=for-the-badge&logo=githubsponsors&logoColor=white" alt="GitHub Sponsors"></a>
</p>

<br>

<p align="center">
  <a href="https://github.com/BySergiMM/OmniMac"><img src="https://raw.githubusercontent.com/BySergiMM/OmniMac/main/docs/site/img/icon.png" width="110" alt="OmniMac"></a>
</p>

<h2 align="center">OmniMac — everything your Mac is missing</h2>

<p align="center">
  <b>Eleven</b> Mac utilities in <b>one</b> lightweight, free, open-source menu-bar app:<br>
  a Dynamic Island for <b>any</b> Mac, notch or not · keep-awake · ⌘Tab by windows · window shortcuts &amp; saved layouts<br>
  clipboard history that strips tracking from links · command bar · volume mixer with a 10-band EQ<br>
  a real performance monitor — per-core CPU, GPU, memory, disk, network, temperature — with alerts<br>
  menu-bar hider · app cleaner · OCR, colour picker, mic mute. <b>Every shortcut is yours to change.</b>
</p>

<p align="center">
  <b>0.017–0.033 % CPU and 33–37 MB of real memory at idle</b> · universal binary · macOS 14.2+ · no accounts, no telemetry.<br>
  It does the job of the seven utilities it replaces in your menu bar with <b>86 MB instead of 851 MB</b> (RSS, same Mac, same method).
</p>

<p align="center">
  <a href="https://github.com/BySergiMM/OmniMac/releases/latest/download/OmniMac.pkg"><img src="https://img.shields.io/badge/Download%20OmniMac.pkg-5b5bd6?style=for-the-badge&logo=apple&logoColor=white" alt="Download"></a>
  &nbsp;
  <a href="https://bysergimm.github.io/OmniMac/"><img src="https://img.shields.io/badge/Website-1d1d1f?style=for-the-badge" alt="Website"></a>
  &nbsp;
  <a href="https://github.com/BySergiMM/OmniMac"><img src="https://img.shields.io/badge/Source%20code-000?style=for-the-badge&logo=github&logoColor=white" alt="Source"></a>
</p>

<p align="center">
  <a href="https://github.com/BySergiMM/OmniMac"><img src="https://raw.githubusercontent.com/BySergiMM/OmniMac/main/docs/site/img/en/notch-media.png" width="681" alt="OmniMac's notch expanded with the music tab"></a>
</p>


<p align="center">
  <a href="https://github.com/BySergiMM/OmniMac/releases/latest"><img src="https://img.shields.io/github/v/release/BySergiMM/OmniMac?label=release&color=5b5bd6" alt="Release"></a>
  <a href="https://github.com/BySergiMM/OmniMac/releases"><img src="https://img.shields.io/github/downloads/BySergiMM/OmniMac/total?label=downloads&color=5b5bd6" alt="Downloads"></a>
  <a href="https://github.com/BySergiMM/OmniMac/stargazers"><img src="https://img.shields.io/github/stars/BySergiMM/OmniMac?style=flat&color=ffd60a" alt="Stars"></a>
  <a href="https://github.com/BySergiMM/OmniMac/actions/workflows/build.yml"><img src="https://github.com/BySergiMM/OmniMac/actions/workflows/build.yml/badge.svg" alt="Build"></a>
</p>


<br>

<h3 align="center">What I'm building now</h3>

<table align="center">
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/BySergiMM/holdcall">holdcall</a></b> · Go<br>
      <sub>A local guard for AI agents. It sits between Claude Code, Cursor or Claude Desktop and their MCP tools, holds risky calls until you approve them, keeps API keys in the system keychain instead of plain text configs, and writes every decision to a tamper evident log you can verify offline.</sub><br>
      <sub><a href="https://holdcall.vercel.app">holdcall.vercel.app</a></sub>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/BySergiMM/metac-bot-template">Metaculus forecasting bot</a></b> · Python<br>
      <sub>An LLM agent that forecasts real world questions on its own in Metaculus' AI tournaments. Five forecasts per question spread across Claude, Gemini and open models, with fallbacks when a provider fails. Finished 88th of 192 bots in its first season and is now competing in the Fall 2026 season.</sub>
    </td>
  </tr>
</table>

---

```python
from dataclasses import dataclass

@dataclass
class SergiMarti:
    role: str         = "Oracle Technical Consultant @ Timestamp España"
    location: str     = "Barcelona, Spain"
    by_day: tuple     = ("PL/SQL", "Oracle Forms", "Oracle ERP", "Oracle Data Integrator")
    by_night: tuple   = ("Swift / SwiftUI", "Python + FastAPI", "Go", "LLM agents & MCP")
    building: tuple   = ("OmniMac", "holdcall", "metac-bot-template")
    principles: tuple = ("Clean Architecture", "SOLID", "typed + tested", "ship to prod")

    def say_hi(self) -> str:
        return "Databases by day, production software by night."
```

### 🧰 Tech

`macOS` Swift · SwiftUI · AppKit · CoreAudio · IOKit · Accessibility APIs · Sparkle  
`Oracle` PL/SQL · Oracle Forms · Oracle ERP · Oracle Data Integrator · Oracle Database  
`Backend` Python · FastAPI · Go · ASP.NET / C# · Java  
`AI/LLM` Claude · Gemini · OpenRouter · Groq · MCP · evals  
`Frontend` Next.js · React · Tailwind CSS  
`Mobile` Kotlin · Android SDK  
`Data` Oracle SQL · PostgreSQL · SQLAlchemy · Entity Framework · Prisma · Supabase  
`DevOps` Docker · GitHub Actions · Render · Vercel · Alembic · Linux
