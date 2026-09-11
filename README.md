# 🎓 PBL-GEU

## GEU Student Mini Projects Repository

<p align="center">
  <strong>Project-Based Learning • Collaboration • Development • Progress Tracking</strong>
</p>

---

## 📌 About

**PBL-GEU** is a centralized GitHub repository created for managing and organizing the **Project-Based Learning (PBL)** projects of students at **Graphic Era University (GEU)**.

Each PBL group is assigned:

- 🌍 A specific country
- 👥 A dedicated GitHub Team
- 🌿 A dedicated GitHub branch
- 📁 A corresponding project folder

The complete project work of each group will be maintained in its assigned branch and project folder.

This repository provides a structured environment for:

- Project development
- Code management
- Team collaboration
- Documentation
- Project progress monitoring

---

# 🔐 Repository Workflow

The PBL repository follows a simple:

**Team → Branch → Folder → Project Work**

structure.

```text
PBL Group
    ↓
GitHub Team
    ↓
Dedicated Branch
    ↓
Assigned Country Folder
    ↓
Project Code & Documentation
```

### Example — Japan Group

```text
Japan Group
    ↓
Japan-Team
    ↓
japan branch
    ↓
Japan folder
    ↓
Project Code & Documentation
```

### Example — India Group

```text
India Group
    ↓
India-Team
    ↓
india branch
    ↓
India folder
    ↓
Project Code & Documentation
```

---

# 🌿 Branch-Based PBL System

Each PBL group has a dedicated GitHub branch.

The **branch is the primary access-control boundary** for each group.

All groups may view the repository and its branches, but each group is authorized to push changes to its own assigned branch.

| 🌎 Country | 👥 GitHub Team | 🌿 Branch | 📁 Folder |
|---|---|---|---|
| 🇮🇳 India | `India-Team` | `india` | `India` |
| 🇯🇵 Japan | `Japan-Team` | `japan` | `Japan` |
| 🇩🇪 Germany | `Germany-Team` | `germany` | `Germany` |
| 🇫🇷 France | `France-Team` | `france` | `France` |
| 🇺🇸 USA | `USA-Team` | `usa` | `USA` |
| 🇬🇧 UK | `UK-Team` | `uk` | `UK` |
| 🇨🇦 Canada | `Canada-Team` | `canada` | `Canada` |
| 🇦🇺 Australia | `Australia-Team` | `australia` | `Australia` |
| 🇮🇹 Italy | `Italy-Team` | `italy` | `Italy` |
| 🇰🇷 South Korea | `South-Korea-Team` | `south-korea` | `South-Korea` |
| 🇧🇷 Brazil | `Brazil-Team` | `brazil` | `Brazil` |
| 🇸🇬 Singapore | `Singapore-Team` | `singapore` | `Singapore` |
| 🇦🇪 UAE | `UAE-Team` | `uae` | `UAE` |
| 🇨🇳 China | `China-Team` | `china` | `China` |
| 🇷🇺 Russia | `Russia-Team` | `russia` | `Russia` |

> 📌 Each group must work on its assigned branch and maintain its project inside its assigned country folder.

---

# 🚀 How to Access Your Group Workspace

Follow these steps whenever you want to work on your PBL project.

## Step 1 — Open the Repository

Open the centralized PBL repository:

```text
https://github.com/PBL-GEU/PBL-GEU
```

---

## Step 2 — Select Your Assigned Branch

At the top of the repository, you will see the branch selector.

For example:

```text
main ▼
```

Click the branch selector and select your group's assigned branch.

### Japan Group

```text
main
  ↓
japan
```

### India Group

```text
main
  ↓
india
```

### Germany Group

```text
main
  ↓
germany
```

> 📌 Always select your assigned branch before working on your project.

---

## Step 3 — Open Your Assigned Country Folder

After selecting your group's branch, open the corresponding country folder.

### Japan Group

```text
japan
└── Japan/
```

### India Group

```text
india
└── India/
```

### Germany Group

```text
germany
└── Germany/
```

---

# 📁 Project Workspace

All project-related files must be maintained inside the group's assigned country folder.

For example, the Japan group may organize its project like this:

```text
Japan/
│
├── frontend/
├── backend/
├── android/
├── database/
├── documentation/
└── README.md
```

The exact project structure may vary according to the requirements of the project.

Project work may include:

- 💻 Frontend
- ⚙️ Backend
- 📱 Android Application
- 🗄️ Database
- 📄 Documentation
- 🧪 Testing
- 📊 Reports
- 📦 Other project-related files

---

# 💻 Working Through GitHub Website

Group Leaders can manage project files directly through GitHub.

### Basic Workflow

```text
Open Repository
      ↓
Select Your Assigned Branch
      ↓
Open Your Country Folder
      ↓
Add / Upload Project Files
      ↓
Commit Changes
```

### Important

Before uploading or creating files, make sure that your assigned branch is selected.

For example, the Japan group must select:

```text
japan
```

and then work inside:

```text
Japan/
```

Similarly, the India group must select:

```text
india
```

and then work inside:

```text
India/
```

---

# 🖥️ Working with Git and VS Code

Groups can also work on the project using Git and VS Code.

## 1. Clone the Repository

```bash
git clone https://github.com/PBL-GEU/PBL-GEU.git
```

Move into the repository:

```bash
cd PBL-GEU
```

---

## 2. Check Available Branches

```bash
git branch -a
```

Example:

```text
main
remotes/origin/main
remotes/origin/japan
remotes/origin/india
remotes/origin/germany
remotes/origin/france
...
```

---

## 3. Switch to Your Assigned Branch

Use your assigned branch name.

### Japan

```bash
git switch japan
```

### India

```bash
git switch india
```

### Germany

```bash
git switch germany
```

> 📌 Replace the branch name with your own assigned branch.

---

## 4. Work Inside Your Assigned Country Folder

After switching to your assigned branch, add or update project files inside your country's folder.

### Japan

```text
Japan/
├── frontend/
├── backend/
├── android/
├── database/
└── documentation/
```

### India

```text
India/
├── frontend/
├── backend/
├── android/
├── database/
└── documentation/
```

---

## 5. Check Your Changes

```bash
git status
```

---

## 6. Stage Your Changes

```bash
git add .
```

---

## 7. Commit Your Changes

Use a meaningful commit message.

Example:

```bash
git commit -m "Add Japan PBL project frontend"
```

Other examples:

```bash
git commit -m "Update backend module"
git commit -m "Add project documentation"
git commit -m "Update database structure"
```

---

## 8. Push Your Changes

Push your changes to your assigned branch.

### Japan

```bash
git push origin japan
```

### India

```bash
git push origin india
```

### Germany

```bash
git push origin germany
```

> 📌 Replace `japan`, `india`, or `germany` with your own assigned branch.

---

# 👥 Group Leader Responsibility

Each PBL Group Leader is responsible for maintaining their group's project workspace.

The Group Leader is responsible for:

- Adding project code
- Updating project files
- Maintaining documentation
- Organizing project folders
- Creating meaningful commits
- Pushing project changes to the assigned branch
- Maintaining the group's project progress in the repository

Group members may provide their project code and files to the Group Leader, who can add and maintain them in the group's assigned workspace.

---

# 🔒 Repository Access & Security

Each PBL group is associated with a dedicated GitHub Team and protected branch.

For example:

```text
Japan-Team
     ↓
Repository Write Access
     ↓
Protected japan Branch
     ↓
Japan/
```

Similarly:

```text
India-Team
     ↓
Repository Write Access
     ↓
Protected india Branch
     ↓
India/
```

The branch protection system restricts direct pushes to the assigned branch to the authorized team.

### Important

The **branch is the primary access-control boundary**.

The country folder is used for **project organization**, while branch permissions control who can push changes.

Therefore:

```text
Japan-Team       → japan branch       → Japan/
India-Team       → india branch       → India/
Germany-Team     → germany branch     → Germany/
France-Team      → france branch      → France/
USA-Team         → usa branch         → USA/
UK-Team          → uk branch          → UK/
Canada-Team      → canada branch      → Canada/
Australia-Team   → australia branch   → Australia/
Italy-Team       → italy branch       → Italy/
South-Korea-Team → south-korea branch → South-Korea/
Brazil-Team      → brazil branch      → Brazil/
Singapore-Team   → singapore branch  → Singapore/
UAE-Team         → uae branch         → UAE/
China-Team       → china branch       → China/
Russia-Team      → russia branch      → Russia/
```

---

# 📌 Important Guidelines

1. Always select your group's assigned branch before working.
2. Maintain your project inside your assigned country folder.
3. Use meaningful commit messages.
4. Keep the project structure organized.
5. Keep project documentation updated.
6. Do not upload unnecessary temporary or generated files.
7. Keep frontend, backend, Android, database, documentation, and other project components properly organized.
8. The Group Leader is responsible for maintaining the group's project workspace.
9. Use the centralized repository for all PBL project work.
10. Sir will monitor the project work through the repository.

---

# ⚠️ Before You Push

Always verify these three things before pushing:

```text
1. Am I on my assigned branch?
        ↓
2. Am I working inside my assigned country folder?
        ↓
3. Am I pushing to my assigned branch?
```

### Example — Japan Group

```bash
git branch
```

Make sure:

```text
* japan
  main
```

Then make sure your files are inside:

```text
Japan/
```

Finally push using:

```bash
git push origin japan
```

---

# 🎯 Complete PBL Workflow

```text
             PBL Group
                 ↓
            Group Leader
                 ↓
            GitHub Team
                 ↓
           Assigned Branch
                 ↓
       Assigned Country Folder
                 ↓
         Project Development
                 ↓
         Add / Update Files
                 ↓
               Commit
                 ↓
               Push
                 ↓
          Sir Monitors Progress
```

---

# 🌟 Example — Japan Group

The Japan group should follow this structure:

```text
PBL-GEU Repository
    │
    └── japan branch
          │
          └── Japan/
                │
                ├── frontend/
                ├── backend/
                ├── android/
                ├── database/
                ├── documentation/
                └── README.md
```

### Japan Git Workflow

Switch to the Japan branch:

```bash
git switch japan
```

Work inside:

```text
Japan/
```

Check changes:

```bash
git status
```

Stage changes:

```bash
git add .
```

Commit changes:

```bash
git commit -m "Update Japan PBL project"
```

Push changes:

```bash
git push origin japan
```

---

# 🌟 Example — India Group

The India group should follow this structure:

```text
PBL-GEU Repository
    │
    └── india branch
          │
          └── India/
                │
                ├── frontend/
                ├── backend/
                ├── android/
                ├── database/
                ├── documentation/
                └── README.md
```

### India Git Workflow

Switch to the India branch:

```bash
git switch india
```

Work inside:

```text
India/
```

Check changes:

```bash
git status
```

Stage changes:

```bash
git add .
```

Commit changes:

```bash
git commit -m "Update India PBL project"
```

Push changes:

```bash
git push origin india
```

---

# 📊 Final Repository Structure

The `main` branch contains the central repository README and general PBL instructions.

Each group branch contains its own project workspace.

```text
PBL-GEU Repository
│
├── main
│   └── README.md
│
├── japan
│   ├── Japan/
│   └── README.md
│
├── india
│   ├── India/
│   └── README.md
│
├── germany
│   ├── Germany/
│   └── README.md
│
├── france
│   ├── France/
│   └── README.md
│
├── usa
│   ├── USA/
│   └── README.md
│
├── uk
│   ├── UK/
│   └── README.md
│
├── canada
│   ├── Canada/
│   └── README.md
│
├── australia
│   ├── Australia/
│   └── README.md
│
├── italy
│   ├── Italy/
│   └── README.md
│
├── south-korea
│   ├── South-Korea/
│   └── README.md
│
├── brazil
│   ├── Brazil/
│   └── README.md
│
├── singapore
│   ├── Singapore/
│   └── README.md
│
├── uae
│   ├── UAE/
│   └── README.md
│
├── china
│   ├── China/
│   └── README.md
│
└── russia
    ├── Russia/
    └── README.md
```

> 📌 The exact project files and README content in each group branch may be updated by the respective Group Leader.

---

# 👥 PBL Group Leaders

This section lists the assigned Group Leader for each PBL group.

| 🌎 Country | 👥 GitHub Team | 🌿 Branch | 👤 Group Leader | 🔗 GitHub Profile |
|---|---|---|---|---|
| 🇮🇳 India | `India-Team` | `india` | Pending | — |
| 🇯🇵 Japan | `Japan-Team` | `japan` | Priyanshi Pal | [GitHub](https://github.com/priyanshipal77) |
| 🇩🇪 Germany | `Germany-Team` | `germany` | Pending | — |
| 🇫🇷 France | `France-Team` | `france` | Pending | — |
| 🇺🇸 USA | `USA-Team` | `usa` | Pending | — |
| 🇬🇧 UK | `UK-Team` | `uk` | Pending | — |
| 🇨🇦 Canada | `Canada-Team` | `canada` | Pending | — |
| 🇦🇺 Australia | `Australia-Team` | `australia` | Divisha Saini |
| 🇮🇹 Italy | `Italy-Team` | `italy` | Pending | — |
| 🇰🇷 South Korea | `South-Korea-Team` | `south-korea` | Pending | — |
| 🇧🇷 Brazil | `Brazil-Team` | `brazil` | Pending | — |
| 🇸🇬 Singapore | `Singapore-Team` | `singapore` | Pending | — |
| 🇦🇪 UAE | `UAE-Team` | `uae` | Pending | — |
| 🇨🇳 China | `China-Team` | `china` | Pending | — |
| 🇷🇺 Russia | `Russia-Team` | `russia` | Pending | — |

> 📌 Group Leader details will be updated as group assignments are confirmed.

> 📌 The Group Leader is responsible for maintaining the group's project work in the assigned branch and country folder.


---

# 👨‍🏫 Project Monitoring

The repository is maintained as a centralized workspace for:

- PBL project development
- Code management
- Documentation
- Progress tracking
- Project monitoring

Each group's work can be reviewed through its respective branch and project workspace.

---

<p align="center">
  🎓 <strong>Graphic Era University</strong><br>
  Project-Based Learning (PBL)<br>
  <strong>PBL-GEU — Under Dr. Amit Kumar</strong>
</p>
