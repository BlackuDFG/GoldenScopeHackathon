# GoldenScopeHackathon
# 🏙️ FixMyCity AI
### Smart City Hackathon | Pforzheim 2026

**AI-Powered Urban Issue Reporting, Prioritization & Administration**

## 💡 About the Project

FixMyCity AI is an AI-powered platform designed to improve communication between citizens and local government.

Citizens can report problems in public spaces by uploading a photo, providing a short description, and specifying the location.

Our system analyzes the submitted information, automatically categorizes the issue, assesses its urgency, and recommends the responsible municipal department.

City administrators can review incoming reports and forward them to the appropriate department with just one click.

**Our mission:** Make urban issue reporting faster, smarter, and more efficient.

## 🎯 The Problem

Cities receive reports about damaged roads, illegal waste disposal, broken streetlights, and other infrastructure problems.

Processing these reports manually can be time-consuming because each issue must be reviewed, categorized, prioritized, and assigned to the appropriate department.

FixMyCity AI aims to simplify this process through AI-assisted decision-making.

## 🚀 Key Features

### 1. Citizen Reporting Portal
- Upload a photo of an urban issue
- Add a short description
- Specify the location
- Submit the report

### 2. AI-Powered Image & Text Analysis
- Analyze uploaded images
- Interpret citizen descriptions
- Identify the reported problem
- Automatically assign an issue category

### 3. Intelligent Categorization

Issues are classified into categories such as:

- Road Damage
- Waste & Cleanliness
- Street Lighting
- Sidewalks & Accessibility
- Parks & Green Spaces
- Traffic Infrastructure

### 4. Smart Prioritization

The system suggests a priority level based on factors such as:

- Potential safety risks
- Severity of the issue
- Impact on citizens
- Urgency

| Priority | Description |
|---|---|
| 🔴 P1 – Critical | Potential immediate safety hazard requiring urgent review |
| 🟠 P2 – High | Significant issue requiring timely attention |
| 🟢 P3 – Normal | Non-urgent issue for regular processing |

Priority recommendations are generated using transparent decision rules and can be reviewed by city administrators.

### 5. Municipal Administration Dashboard

City administrators can:

- View incoming reports
- Filter issues by category and priority
- Review AI-generated assessments
- Confirm or change the recommended department
- Assign reports to departments with one click
- Track the processing status

### 6. Department Assignment

The system recommends the responsible department based on the issue category.

A city administrator reviews the recommendation and confirms the assignment.

For the hackathon prototype, this workflow is demonstrated within the application rather than through a live integration with municipal systems.

## 🔄 How It Works

**Citizen submits report**

↓

**AI analyzes image and description**

↓

**Automatic categorization**

↓

**Risk assessment and prioritization**

↓

**Report appears in the administration dashboard**

↓

**Administrator reviews and assigns department**

↓

**Department receives the assigned report**

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Programming Language | Python |
| Frontend | Streamlit |
| AI Analysis | Multimodal AI API |
| Prioritization | Python-based decision rules |
| Database | SQLite |
| Version Control | Git & GitHub |
| Development Environment | VS Code |

*The technology stack is planned and may be adjusted during development.*

## 📂 Project Structure

```text
fixmycity-ai/
├── app.py
├── admin.py
├── ai_analysis.py
├── prioritization.py
├── database.py
├── requirements.txt
├── .gitignore
└── README.md
```

## 🧪 Development Roadmap

- [ ] Set up GitHub repository and project structure
- [ ] Develop citizen reporting interface
- [ ] Implement image and text analysis
- [ ] Develop automatic issue categorization
- [ ] Implement risk-based prioritization
- [ ] Set up database
- [ ] Build administration dashboard
- [ ] Implement one-click department assignment
- [ ] Test functionality with example reports
- [ ] Prepare final hackathon demonstration

## 🔐 Responsible AI

FixMyCity AI is designed as a decision-support system.

- AI recommendations remain reviewable by humans.
- Uncertain classifications can be flagged for manual review.
- Priority decisions should be explainable.
- Potential emergencies should not rely solely on automated classification.
- Personal data and uploaded images must be handled securely.

## 🌍 Our Vision

**From citizen reports to smarter city decisions.**

FixMyCity AI aims to help cities respond more efficiently to urban problems, reduce administrative workload, and improve the quality of public spaces.

By combining artificial intelligence with human oversight, we want to make cities more responsive, accessible, and citizen-friendly.

---

**Developed for Smart City Days Pforzheim 2026.**

*FixMyCity AI – Report it. Detect it. Prioritize it. Fix it.*
