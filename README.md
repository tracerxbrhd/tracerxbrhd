# TRACER / ENGINEERED SYSTEMS

Software architecture, game systems and product experiments.

---

## 🎮 01 / GAME SYSTEMS

### 🧩 UNDERWORLD STUDIO

A modular Minecraft ecosystem built around a shared technical foundation.

```mermaid
flowchart TB
    API["U-API<br/>Shared Foundation"]
    SA["Soul Ascension<br/>Character Progression"]
    DD["Dedicated Dungeons<br/>Dungeon Framework"]
    IN["Innutrient<br/>Nutrition System"]
    TC["The Coinage<br/>Currency System"]

    API --> SA
    API --> DD
    API --> IN
    API --> TC
```

[**U-API**](https://github.com/tracerxbrhd/u-api) · [Soul Ascension](https://github.com/tracerxbrhd/soul-ascension) · [Dedicated Dungeons](https://github.com/tracerxbrhd/dedicated-dungeons) · [Innutrient](https://github.com/tracerxbrhd/innutrient) · [The Coinage](https://github.com/tracerxbrhd/the-coinage)

---

## 🌐 02 / WEB & PRODUCT SYSTEMS

### 💻 PRFIO

Product-focused web projects spanning full-stack systems, data visualization and interaction design.

<table>
<tr>
<td width="33%" valign="top">
<strong><a href="https://github.com/tracerxbrhd/prfio-tableflow">TableFlow</a></strong><br>
Restaurant operations & reservation system<br>
<code>React</code> · <code>Flask</code> · <code>PostgreSQL</code>
</td>
<td width="33%" valign="top">
<strong><a href="https://github.com/tracerxbrhd/prfio-atlas-lab">Atlas Lab</a></strong><br>
Interactive urban data explorer<br>
<code>React</code> · <code>SVG</code> · <code>Vite</code>
</td>
<td width="33%" valign="top">
<strong><a href="https://github.com/tracerxbrhd/prfio-verde-escape">Verde Escape</a></strong><br>
Hospitality frontend & stay planner<br>
<code>JavaScript</code> · <code>Vite</code>
</td>
</tr>
<tr>
<td width="33%" valign="top">
<a href="https://github.com/tracerxbrhd/prfio-opsboard">OpsBoard</a><br>
Team delivery workspace<br>
<code>React</code> · <code>Django</code> · <code>PostgreSQL</code>
</td>
<td width="33%" valign="top">
<a href="https://github.com/tracerxbrhd/prfio-glassdesk">GlassDesk</a><br>
Customer-support workspace<br>
<code>React</code> · <code>Django REST</code> · <code>PostgreSQL</code>
</td>
<td width="33%" valign="top">
<a href="https://github.com/tracerxbrhd/prfio-nova-studio">NOVA Studio</a><br>
Editorial studio frontend<br>
<code>JavaScript</code> · <code>Vite</code>
</td>
</tr>
</table>

---

## 🛠️ 03 / INDEPENDENT SYSTEMS

### 🎟️ [Tickets! Please](https://github.com/tracerxbrhd/tickets-please-discord)

Discord support and ticket management system with persistent server configuration, role-based workflows and PostgreSQL-backed state. Built, deployed and operated as a live bot.

`Python` · `Discord` · `PostgreSQL` · `Docker`
