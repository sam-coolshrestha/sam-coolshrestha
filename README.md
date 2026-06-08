<!--
███████╗ █████╗ ███╗   ███╗██████╗ ██╗██████╗ ██╗  ██╗██╗
██╔════╝██╔══██╗████╗ ████║██╔══██╗██║██╔══██╗██║  ██║██║
███████╗███████║██╔████╔██║██████╔╝██║██║  ██║███████║██║
╚════██║██╔══██║██║╚██╔╝██║██╔══██╗██║██║  ██║██╔══██║██║
███████║██║  ██║██║ ╚═╝ ██║██║  ██║██║██████╔╝██║  ██║██║
╚══════╝╚═╝  ╚═╝╚═╝     ╚═╝╚═╝  ╚═╝╚═╝╚═════╝ ╚═╝  ╚═╝╚═╝
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:f9a8d4,25:e879f9,50:a78bfa,75:60a5fa,100:67e8f9&height=220&section=header&text=Samridhi%20Kulshrestha&fontSize=42&fontColor=ffffff&fontAlignY=40&desc=C%2B%2B%20%7C%20Python%20%7C%20Cybersecurity%20%7C%20AI%2FML&descAlignY=58&descSize=18&descColor=fce7f3" width="100%"/>

</div>

---

<div align="center">

```bash
┌─[samridhi@github]─[~]
└──╼ whoami
```

</div>

```
> Computer Science student at JIIT Noida
> Building at the intersection of security, systems, and AI
> Passionate about understanding how things break — and how to fix them
> Currently learning: Binary Exploitation · Network Security · ML with Python
> Portfolio: [samridhi-kulshrestha-portfolio.vercel.app](https://samridhi-kulshrestha-portfolio.vercel.app)
> Open to: Internships · Collaborations · Open Source
```

---

## `~/about`

I'm a CS undergrad who started with competitive programming, got pulled into cybersecurity,
and never looked back. I like systems-level thinking — which is why C++ and Python feel
like home. DSA isn't just exam prep for me; it's how I think about designing efficient
solutions (ask DRAS).

When I'm not coding, I'm breaking things ethically in CTFs or reading about how the
next zero-day got discovered.

---

## `~/stats`

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=sam-coolshrestha&theme=tokyonight&hide_border=true&border_radius=8&date_format=j%20M%5B%20Y%5D)](https://git.io/streak-stats)

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=sam-coolshrestha&theme=tokyo-night&hide_border=true&radius=8)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## `~/projects`

<details open>
<summary><b>🚨 DRAS 2.0 — Emergency Management & Response Gateway</b></summary>

<br/>

> A live, deployed system that computes optimal rescue routes across 7 UP cities during multi-incident emergencies — built as a full DSA showcase.

**The problem:** When disaster strikes, emergency responders need the fastest route — not just the shortest. They also need to know which hospitals might become isolated (articulation points), where hazards are highest, and how to visit every relief centre efficiently.

**What it does:**
- Plots hospitals, relief centres, and live disaster risk zones (earthquake, storm, nuclear, rail accident, and more) on an interactive map
- Computes rescue routes via **Dijkstra** (shortest distance), **A\*** (fastest with heuristic), and **Min-Max Hazard** (safest path) — side-by-side
- Identifies **critical infrastructure nodes** using Tarjan's algorithm and **MST** via Kruskal + Union-Find
- Approximates the optimal hospital tour using a **nearest-neighbour + 2-opt TSP** solver
- Shows execution time, nodes visited, and complexity class for every route — because it's also a DSA explainer
- Supports **live GPS location**, IP fallback, email alerts, and shows all incidents within 20km of you

**Stack:** `Python 3.10` · `Flask` · `C++ (engine)` · `Leaflet.js` · `OpenStreetMap` · `Render`

[![Live Demo](https://img.shields.io/badge/Live_Demo-▶_Try_it_now-22c55e?style=for-the-badge&logoColor=white)](https://dras-gw0j.onrender.com)
[![Repo](https://img.shields.io/badge/GitHub-View_Repo-181717?style=for-the-badge&logo=github)](https://github.com/sam-coolshrestha/DRAS_2.0)

</details>

---

<details open>
<summary><b>📋 Attendify 2.0 — Cloud-Based Attendance Management System</b></summary>

<br/>

> Eliminates proxy attendance and saves 10–15 minutes of lecture time per class by replacing paper registers with a live digital system.

**The problem:** Traditional roll-calls waste instructional time, and paper registers are trivially exploited — students mark absent friends present ("proxy"), creating fraudulent records with no accountability.

**What it does:**
- Role-based dashboards for **Admins**, **Teachers**, and **Students** — each sees exactly what they need
- Teachers mark an entire class in seconds via digital checklist; every entry is timestamped instantly
- Students view their **live attendance percentage** and total-vs-attended stats in real time
- **MongoDB Atlas** NoSQL backend maps Student IDs to Subject IDs as flexible JSON documents
- Deployed on **Render** with CI/CD — every GitHub push goes live automatically
- Sessions prevent students from accessing teacher or admin routes; env vars keep credentials safe

**Stack:** `Python` · `Flask` · `MongoDB Atlas` · `Gunicorn` · `Vanilla JS` · `Render`

[![Live Demo](https://img.shields.io/badge/Live_Demo-▶_Try_it_now-22c55e?style=for-the-badge&logoColor=white)](https://attendify-2-0-p2kj.onrender.com)
[![Repo](https://img.shields.io/badge/GitHub-View_Repo-181717?style=for-the-badge&logo=github)](https://github.com/sam-coolshrestha/_ATTENDIFY-2.0_)

</details>

---

<details open>
<summary><b>🩺 Health Lens — Medical Image Analysis Tool</b></summary>

<br/>

> An AI-powered health analysis tool that processes medical data and images to surface actionable insights.

[![Repo](https://img.shields.io/badge/GitHub-View_Repo-181717?style=for-the-badge&logo=github)](https://github.com/sam-coolshrestha/Health_Lens_)

</details>

---

## `~/stack`

<div align="center">

**Languages**

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Web & Frameworks**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

**Data & DevOps**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)

</div>

---

## `~/currently`

```python
class Samridhi:
    def __init__(self):
        self.education    = "BTech CSE · JIIT Noida"
        self.location     = "Greater Noida, India"
        self.interests    = ["Cybersecurity", "AI/ML", "Systems Programming", "DSA"]

    def currently_doing(self):
        return {
            "learning"  : ["Binary Exploitation", "Network Security", "ML with Python"],
            "building"  : "Next project (ask me what's in the pipeline)",
            "open_to"   : ["Internships", "Collaborations", "CTF teams"],
        }

    def say_hi(self):
        print("Let's build something that matters. Reach out anytime 👋")

me = Samridhi()
me.say_hi()
```

---

## `~/connect`

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://samridhi-kulshrestha-portfolio.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/samridhikulshrestha)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your@email.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sam-coolshrestha)

</div>

---

<div align="center">

```
╔══════════════════════════════════════════════════════════╗
║  "Security is not a product, but a process." — Schneier  ║
║                                                          ║
║         Currently running on: chai + curiosity ☕        ║
╚══════════════════════════════════════════════════════════╝
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:67e8f9,25:60a5fa,50:a78bfa,75:e879f9,100:f9a8d4&height=120&section=footer" width="100%"/>

</div>
