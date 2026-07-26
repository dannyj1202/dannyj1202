<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1120,100:0E7490&height=220&section=header&text=Daniel%20John%20Varghese&fontSize=42&fontColor=FFFFFF&animation=fadeIn&fontAlignY=35&desc=AI%2FML%20%7C%20Systems%20%7C%20Network%20Security&descAlignY=55&descSize=18" width="100%"/>

<a href="https://github.com/dannyj1202">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=14B8A6&center=true&vCenter=true&repeat=true&width=1000&height=80&lines=Building+Dental+AI+%7C+Diagnostic+ML+for+X-rays;Final-Year+BSc+Computer+Science+with+AI+%40+UoB+Dubai;Software+Engineer+Intern+%7C+Network+Security+%40+Paramount;ML+Systems+%7C+Performance+Engineering+%7C+Secure+Backends" alt="Typing SVG" />
</a>

<br/>

[![Email](https://img.shields.io/badge/Email-djvarghese12%40gmail.com-0E7490?style=for-the-badge&logo=gmail&logoColor=white)](mailto:djvarghese12@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-dannyj1202-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dannyj1202)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/daniel-varghese-269756201)
![Profile Views](https://komarev.com/ghpvc/?username=dannyj1202&style=for-the-badge&color=0E7490&label=PROFILE+VIEWS)

</div>

---

### 👋 About Me

I'm a final-year **Computer Science with Artificial Intelligence** undergraduate at the **University of Birmingham Dubai**, building applied ML systems and performance-conscious software — grounded in hands-on **enterprise network security** experience. I care about *how* things run, not just whether they run: code that's efficient, measurable, and hard to break.

- 🦷 Building **medical imaging AI** — deep learning on dental radiographs for clinical decision support, served through a FastAPI backend
- ⚡ Drawn to **performance engineering** — profiling, optimisation, and getting close to the metal with **C** (C++ / Rust next)
- 🛡️ Interned in **network security** at Paramount Computer Systems — **Fortinet, Check Point, Cisco, Wireshark** in a production environment
- 🐍 Writing **security tooling** in Python (Scapy, layer-2 attack & defence study)
- 🌍 Based between the **UAE and Kuwait** · open to internships and early-stage teams

---

### 🎯 Current Focus

`Medical AI` &nbsp;·&nbsp; `ML Systems` &nbsp;·&nbsp; `Performance & Low-Level Engineering` &nbsp;·&nbsp; `Secure Backend Development` &nbsp;·&nbsp; `Cloud (AWS)`

---

### 🌟 Main Project

<table>
<tr>
<td width="100%" valign="top">

**🦷 Dental Diagnostic AI** — Deep Learning for Radiographic Decision Support

An object-detection pipeline that reads panoramic dental X-rays and surfaces findings a clinician can verify — caries, periapical lesions, bone loss, and impacted teeth — built as a decision-support layer, not a replacement for diagnosis.

- Trained **PyTorch** detection models on the **DENTEX** panoramic radiograph dataset, with quadrant/enumeration/diagnosis label hierarchy
- Built a reproducible training stack — **CUDA**-accelerated PyTorch, pinned dependencies via `pyproject.toml`, deterministic seeds and versioned experiment configs
- Engineered the inference layer as a **FastAPI** service returning bounding boxes with per-finding confidence, designed for clinic-side integration
- Applied medical-imaging-aware preprocessing and augmentation (CLAHE, geometric transforms) tuned for greyscale radiographs
- Treating **explainability and calibration as first-class** requirements — findings are surfaced for review, never asserted as diagnoses

`Python` `PyTorch` `CUDA` `FastAPI` `OpenCV` `NumPy` `Docker`

[![View Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dannyj1202)

</td>
</tr>
</table>

---

### 📦 Other Projects

<table>
<tr>
<td width="50%" valign="top">

**🛡️ ARP Spoofer**
*Ethical Hacking / Layer-2 Networking*

A command-line ARP spoofing tool that positions the host as a man-in-the-middle between a target and its gateway — built to study layer-2 attacks and the controls that stop them.

- Crafted and injected forged ARP replies with **Scapy** to poison target and gateway caches
- Implemented IP forwarding and clean **cache restoration on exit** so the network is left as found
- Documented the defensive side: **DAI (Dynamic ARP Inspection)**, port security, and static bindings
- Written as a lab exercise on an isolated, owned network

`Python` `Scapy` `Networking` `Security`

[![View Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dannyj1202/ARP-Spoofer---Ethical-Hacking-Project)

</td>
<td width="50%" valign="top">

**🏨 Hotel Booking Cancellation Predictor**
*Supervised Machine Learning*

A model that predicts whether a hotel booking will be cancelled, wrapped in an interactive app so anyone can test it without touching code.

- Trained and tuned a **decision-tree classifier** with **scikit-learn**, evaluated on precision/recall trade-offs rather than raw accuracy
- Handled categorical encoding, missing values, and class imbalance across the booking dataset
- Analysed **feature importance** to explain *why* a booking is flagged at risk
- Shipped an interactive **Gradio** interface for live inference

`Python` `scikit-learn` `pandas` `Gradio`

[![View Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dannyj1202/Hotel-Booking-Cancellation-ML-Predictor-Model)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**📊 Customer Segmentation with K-Means**
*Unsupervised Machine Learning*

Clustering on retail transaction data to surface distinct buyer personas that marketing can actually act on.

- Applied **K-Means** clustering with **elbow method and silhouette scoring** to select cluster count defensibly
- Built RFM-style feature engineering and scaling before clustering
- Reduced dimensionality with **PCA** for interpretable 2D cluster visualisation
- Translated clusters into retention and targeting recommendations

`Python` `scikit-learn` `pandas` `Matplotlib` `Jupyter`

[![View Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dannyj1202/Customer-Segmentation-Unsupervised-Learning-ML-model-)

</td>
<td width="50%" valign="top">

**🤖 AI Study Assistant**
*GDG Bounty Hackathon 2026 — Team Build*

A full-stack academic assistant that turns uploaded course material into summaries, flashcards, and study resources.

- Built the **document ingestion and generation flow** on top of cloud AI APIs
- Generated **flashcards and structured summaries** from raw lecture material
- Delivered a working full-stack build and **demoed it live** at the university hackathon
- Collaborated in a time-boxed team environment with Git-based workflow

`JavaScript` `Cloud AI` `Full-Stack`

[![View Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dannyj1202/AI-study-assistant)

</td>
</tr>
</table>

---

### 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logoColor=white)

**Backend & Databases**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)

**Infra & Deployment**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

**Security & Networking**

![Fortinet](https://img.shields.io/badge/Fortinet-EE3124?style=for-the-badge&logo=fortinet&logoColor=white)
![Check Point](https://img.shields.io/badge/Check_Point-E10600?style=for-the-badge&logoColor=white)
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Scapy](https://img.shields.io/badge/Scapy-0F4C81?style=for-the-badge&logoColor=white)

**Tools & Platforms**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?style=for-the-badge&logo=obsidian&logoColor=white)

---

### 💼 Experience

<div align="center">

| Role | Organisation | Period |
|:---|:---|:---:|
| **Software Engineer Intern — Network Security** | Paramount Computer Systems WLL, Kuwait | 2026 |
| **IT Apprentice** | NREC — National Real Estate Company, Kuwait | 2024 – 2025 |

</div>

**Software Engineer Intern — Network Security** · *Paramount Computer Systems WLL, Kuwait*
> Selected for a 45-day engineering internship at a regional cybersecurity provider. Worked in a production environment across **Fortinet, Check Point, and Cisco** technologies — firewall policy and NAT configuration (VIPs, IP pools), traffic analysis in **Wireshark**, XDR platform evaluation, ethical-hacking lab builds to study attack vectors and defences, and topology design/troubleshooting in Cisco Packet Tracer (EIGRP, IOS config).

**IT Apprentice** · *NREC — National Real Estate Company, Kuwait*
> Hands-on **Linux system administration**, server monitoring, and enterprise IT operations. Ran SQL queries against **Oracle** systems, worked with **Microsoft Azure**, and built **Java** and **Python** internal tools that automated reporting workflows for the IT and finance teams.

---

### 🎓 Education

**BSc Computer Science with Artificial Intelligence** · University of Birmingham Dubai · *Sep 2024 – Jun 2027 (expected)*
> First-class standing, with strongest results in **Security & Networks, Artificial Intelligence, Functional Programming, Operating Systems, and Databases**.

---

### 📜 Certifications

<div align="center">

| Certification | Issuer | Year |
|:---|:---|:---:|
| **AWS Cloud Practitioner Essentials** | Amazon Web Services | 2025 |
| **Data Science & Machine Learning: Making Data-Driven Decisions** | MIT IDSS | 2025 |
| **CCNA 200-301 (course completion)** | Udemy | 2026 |
| **Responsive Web Design** | freeCodeCamp | 2025 |
| **Fortinet FCF / FCP — Secure Networking** | Fortinet | *in progress* |
| **AWS Solutions Architect – Associate** | Amazon Web Services | *targeting 2026* |

</div>

---

### 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=dannyj1202&show_icons=true&count_private=true&hide_border=true&bg_color=0B1120&title_color=14B8A6&text_color=CBD5E1&icon_color=0E7490&border_color=1E293B" width="48%"/>
<img src="https://github-readme-streak-stats.demolab.com?user=dannyj1202&hide_border=true&background=0B1120&stroke=1E293B&ring=14B8A6&fire=0E7490&currStreakLabel=14B8A6&sideLabels=CBD5E1&currStreakNum=14B8A6&sideNums=CBD5E1&dates=64748B" width="48%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dannyj1202&layout=compact&hide_border=true&bg_color=0B1120&title_color=14B8A6&text_color=CBD5E1&border_color=1E293B" width="48%"/>
<img src="https://github-profile-trophy.vercel.app/?username=dannyj1202&theme=darkhub&no-frame=true&row=2&column=4&margin-w=8&margin-h=8" width="48%"/>

</div>

---

<div align="center">

### 📫 Let's Connect

Open to **internships and graduate roles in AI/ML, software engineering, and cybersecurity** — and to early-stage teams building something real.

[![Email](https://img.shields.io/badge/Email_Me-0E7490?style=for-the-badge&logo=gmail&logoColor=white)](mailto:djvarghese12@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/daniel-varghese-269756201)
[![GitHub](https://img.shields.io/badge/Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dannyj1202)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0E7490,100:0B1120&height=120&section=footer" width="100%"/>

</div>
