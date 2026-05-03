# 💭 Reflections — Google Cybersecurity Certificate

> *A personal reflection on what I learned across all 9 courses, how it connects to my transition from QA & Test Automation Engineering into Cybersecurity, and where I want to go next.*

---

## 🎯 Why I Did This Certificate

As a QA & Test Automation Engineer, I'd spent years thinking critically about software — finding edge cases, breaking systems, and documenting failures. I knew that mindset had a place in cybersecurity, but I needed a structured, recognized path to make the transition credible. The Google Cybersecurity Certificate gave me exactly that: a solid foundation covering the full security landscape, with hands-on exposure to the tools and workflows that SOC analysts use every day.

It wasn't just about adding a certificate to my resume. It was about building a new professional vocabulary, connecting concepts I already understood to a new domain, and confirming that this transition was the right one.

---

## 📚 Course-by-Course Reflections

### Course 1 — Foundations of Cybersecurity
**Overall feeling:** A mix of familiar and new.

Coming from QA, some foundational concepts felt like home — structured thinking, risk awareness, understanding how systems are supposed to behave versus how they actually behave. But the security-specific framing was new: the CIA triad, the CISSP 8 domains, the history and evolution of cybersecurity as a discipline.

What I took away from this course was a proper mental model — a way of organizing everything that came after it. Before this, I had security *intuitions* from years in QA. After this, I had a *framework*.

---

### Course 2 — Play It Safe: Manage Security Risks
**What stood out:** Everything — this felt entirely new and challenging.

This was the course where I realized how much I didn't know. Risk management frameworks like NIST RMF, the structure of security audits, the way organizations formally assess and treat risk — none of this had direct equivalents in my QA experience. It was humbling in the best way.

What challenged me most was thinking at an organizational level rather than a technical one. QA is often focused on a specific system or feature. Risk management requires zooming out to see the entire organization, its assets, its exposure, and its appetite for risk. That shift in perspective was genuinely hard — and genuinely valuable.

---

### Course 3 — Connect and Protect: Networks & Network Security
**What clicked:** Network hardening techniques.

I understood networks at a surface level from working with APIs and CI/CD pipelines — HTTP, requests, responses, status codes. But this course pushed me much deeper: how TCP/IP actually works, what happens at each layer, how traffic flows, and critically, how it can be intercepted or disrupted.

Network hardening was where things clicked most powerfully. Understanding *why* certain configurations exist — why you segment networks, why you close unused ports, why you enforce strict firewall rules — made everything feel purposeful rather than procedural. I stopped seeing security configurations as bureaucratic checklists and started seeing them as deliberate defensive decisions.

---

### Course 4 — Tools of the Trade: Linux & SQL
**What was most useful:** Both equally — and for different reasons.

Linux was already part of my daily work from running automated test suites and working in CI/CD pipelines. But this course forced me to understand it at a deeper level — file permissions, user management, process monitoring, log navigation. I went from *using* Linux to *understanding* it, and that difference matters enormously in security work.

SQL was more unexpected. I knew it existed but had never needed it seriously in QA. Using it for security investigations — querying logs, filtering by user activity, identifying anomalous patterns in database records — opened up a completely new way of thinking about data analysis. Both skills felt immediately practical and directly applicable to SOC work.

---

### Course 5 — Assets, Threats & Vulnerabilities
**What hit hardest:** Threat modeling — thinking like an attacker.

This was the course that most fundamentally changed how I think. In QA, I design test cases to find where software fails *accidentally*. Threat modeling asks a different question entirely: where would software fail if someone *intentionally* tried to break it, and what would they gain from doing so?

That shift — from finding bugs to anticipating adversaries — was the biggest mental leap of the entire certificate. I found myself looking back at systems I had tested in my QA career and seeing entirely new categories of risk I had never considered. Uncomfortable and fascinating at the same time.

---

### Course 6 — Sound the Alarm: Detection & Response
**The highlight:** This was the most exciting course of the entire certificate.

Everything clicked here. IDS/IPS, Suricata, SIEM alerts, log correlation, the incident response lifecycle — it all came together into a coherent picture of what a SOC analyst actually does. For the first time, I could clearly see myself doing this job.

What made it exciting wasn't just the tools — it was the *pace* of it. Detection and response is fast, structured, and consequential. Every alert matters. Every decision has an impact. That energy reminded me of the best moments in QA, when a critical bug surfaces right before a release and the whole team mobilizes. Except in a SOC, the stakes are real and the adversary is active.

This course is the reason I'm committed to pursuing a SOC Analyst role.

---

### Course 7 — Automate Cybersecurity Tasks with Python
**How it felt:** Automating log parsing felt deeply connected to my QA background.

Python automation wasn't new territory for me — I've written test automation scripts throughout my QA career. What was new was the *purpose*. Writing a script to parse security logs, extract IOCs, or flag anomalous patterns felt like a natural extension of what I already knew how to do — just pointed at a different problem.

This course confirmed something important: my automation skills are directly transferable to security. The logic of "read input, filter by condition, flag anomalies, output a report" is the same whether you're parsing test results or security logs. The domain changes. The engineering thinking doesn't.

---

### Course 8 — Put It to Work: Prepare for Cybersecurity Jobs
**What resonated most:** It made my transition feel real and achievable.

Up to this point, the certificate had been building skills. This course made it personal. Working on my professional portfolio, understanding the roles and career paths available, learning how to frame my QA background as a strength rather than a detour — it all came together here.

The moment that stuck with me was realizing that my years in QA aren't something I need to explain away. They're part of what makes me a different kind of security professional — someone who has spent years thinking systematically about failure, documentation, and quality. This course helped me own that narrative with confidence.

---

### Course 9 — Accelerate Your Job Search with AI
**What was most useful:** Using AI for resume and interview prep was eye-opening.

I expected this to be the lightest course of the certificate. It turned out to be one of the most immediately practical. Learning how to use AI tools to tailor my resume for specific job descriptions, prepare for technical interview questions, and identify gaps in my profile was something I could apply the same day.

What surprised me most was how much more strategic my job search became after this course. Instead of sending generic applications, I learned to analyze job postings, identify the keywords and competencies that matter, and position my QA background in ways that security hiring managers actually respond to.

---

## 🌟 Biggest Takeaway from the Full Certificate

If I had to pick one thing the Google Cybersecurity Certificate gave me, it's this: **a complete mental model of how security works as a system.**

Each course added a layer — foundations, risk, networks, tools, threats, detection, automation, careers. By the end, those layers connected into something coherent. I don't just know security concepts in isolation anymore. I understand how they relate to each other, how they can fail together, and how defenders use them together.

---

## 😤 What Was Hard

The hardest part wasn't technical — it was the mindset shift in Course 2. Thinking at an organizational, risk-management level — rather than at the level of a specific system or feature — required a new way of framing problems that didn't come naturally at first. It took real effort before risk assessment started to feel intuitive rather than abstract.

---

## 🔍 What I Want to Go Deeper On

| Topic | Why it interests me | How I plan to explore it |
|-------|-------------------|------------------------|
| SIEM query writing (Splunk SPL) | Course 6 showed me the surface — I want to go much deeper | TryHackMe SOC Level 1, Splunk free training |
| Threat hunting | Moving from reactive alerts to proactive hunting | MITRE ATT&CK Navigator practice |
| Python for security automation | Course 7 opened the door — I want to build real tools | Personal scripts, open source security tools |
| Incident response in depth | The IR lifecycle deserves more hands-on practice | VA Cybersecurity Mentorship SOC track |

---

## 🚀 What's Next

| Next Step | How it builds on this certificate |
|-----------|----------------------------------|
| VA Cybersecurity Mentorship — SOC Track | Real mentorship to apply IR and SIEM skills with guidance from a working professional |
| TryHackMe SOC Level 1 | Hands-on lab practice for detection, log analysis, and alert triage |
| Hackers do Bem — DevSecOps Specialization | Apply Python automation and security thinking inside CI/CD pipelines |
| CompTIA Security+ | Formal certification to validate and deepen the foundations covered here |

---

## 💡 How This Changed How I Think

I now look at every system I've ever tested through a different lens. Every form field is a potential injection point. Every API endpoint is an attack surface. Every authentication flow is a target. Every log file is a story waiting to be read.

The certificate didn't replace my QA knowledge — it recontextualized it. I'm not starting over. I'm seeing everything I already knew from a new angle, and that angle is security.

---

*Written by Sigrid | [LinkedIn](https://linkedin.com/in/sigrid-rodrigues) | [GitHub](https://github.com/sigrid-fr)* 
