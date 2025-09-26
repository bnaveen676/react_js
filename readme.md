సరే Naveen 🚀
ఇప్పుడే నీకు **Git** & **GitHub** గురించి తెలుగు లో step by step గా, ముఖ్యమైన concepts అన్నీ చెబుతాను.

# Password 
Naveen@github123

---

## 1️⃣ Git అంటే ఏమిటి?

👉 Git ఒక **Version Control System (VCS)**.

- అంటే మనం project లో files, code change చేసినప్పుడల్లా history ని save చేసుకుంటుంది.
- ఎవరు ఏమి change చేసారు, ఎప్పుడు చేసారు అన్నది track చేస్తుంది.
- అవసరమైతే పాత version కి కూడా తిరిగి వెళ్ళొచ్చు.

📝 Example: నువ్వు ఒక project develop చేస్తుంటే ఒక feature add చేసావు → తర్వాత problem వచ్చిందనుకో → Git లో previous stable version కి తిరిగి వెళ్లవచ్చు.

---

## 2️⃣ GitHub అంటే ఏమిటి?

👉 GitHub అనేది **Git repositories** ని host చేసే **cloud platform**.

- Git అంటే local లో వాడే tool.
- GitHub అనేది మన Git repos ను **online లో store, share & collaborate** చేసుకునే website.
- ఇక్కడ మనం ఇతర developers తో కలిసి పని చేయవచ్చు.

---

## 3️⃣ Git లో ముఖ్యమైన Concepts

### 🔹 Repository (Repo)

- మన project ను Git తో track చేయడం మొదలు పెడితే అది **repository** అని పిలుస్తారు.

### 🔹 Commit

- Files లో change చేసినప్పుడు వాటిని save చేయడం.
- ప్రతి commit కి unique **commit id (hash)** ఉంటుంది.

### 🔹 Branch

- Repo లోని ఒక parallel version.
- Default గా `main` (లేదా `master`) branch ఉంటుంది.
- కొత్త features కోసం separate branch create చేస్తారు → తర్వాత merge చేస్తారు.

### 🔹 Merge

- ఒక branch లో చేసిన changes ని మరో branch లోకి కలపడం.

### 🔹 Clone

- GitHub లో ఉన్న repo ని మన local machine లోకి copy చేయడం.

### 🔹 Push

- Local లో చేసిన changes (commits) ని GitHub కి పంపడం.

### 🔹 Pull

- GitHub (remote repo) లో ఉన్న latest changes ని మన local లోకి తీసుకోవడం.

### 🔹 Staging Area

- Changes చేసిన files ని commit చేయడానికి ముందు prepare చేసే place.
- Command: `git add filename`

---

## 4️⃣ Git లో ముఖ్యమైన Commands

```bash
# Git Repo initialize చేయడానికి
git init

# Repo ని GitHub నుండి copy చేయడానికి
git clone <repo-url>

# File changes ని staging కి add చేయడానికి
git add filename
git add .   # అన్ని files add అవుతాయి

# Commit చేయడానికి
git commit -m "message"

# Remote Repo ని link చేయడానికి
git remote add origin <repo-url>

# Local commits ని GitHub కి పంపడానికి
git push origin main

# GitHub లోని latest code ని తీసుకోవడానికి
git pull origin main

# Branch create చేయడానికి
git branch feature-1

# Branch change అవ్వడానికి
git checkout feature-1

# Merge చేయడానికి
git merge feature-1
```

---

## 5️⃣ GitHub లో ముఖ్యమైన Concepts

### 🔹 Fork

- ఇతరుల repo ని మన GitHub account లోకి copy చేయడం.

### 🔹 Pull Request (PR)

- Fork లేదా branch లో చేసిన changes ని original repo లోకి merge చేయమని request పెట్టడం.

### 🔹 Issues

- Bugs లేదా కొత్త features గురించి discussion చేయడానికి.

### 🔹 Actions

- Automation కోసం (CI/CD pipelines).

---

## 6️⃣ Real-Time Workflow (Team లో పని చేసే విధానం)

1. GitHub లో repo create చేస్తారు.
2. Local కి clone చేస్తారు.
3. New branch create చేసి పని చేస్తారు.
4. Changes → `git add` → `git commit`.
5. Branch ని push చేస్తారు.
6. GitHub లో Pull Request పెడతారు.
7. Team members review చేస్తారు.
8. Merge అవుతుంది → main branch కి.

---

👉 మొత్తానికి:

- **Git** → Local tool for version control.
- **GitHub** → Online platform for collaboration.
- Important terms: Repo, Commit, Branch, Merge, Push, Pull, PR, Fork.

---

Naveen, నీకు కావాలంటే నేను **Git & GitHub cheat sheet (commands + workflow diagram)** కూడా create చేసి ఇస్తా. నీకు అవసరమా?
