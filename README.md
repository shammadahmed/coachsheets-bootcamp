# CoachSheets Life Coaching Bootcamp Curriculum

[![License](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![CoachSheets](https://img.shields.io/badge/Platform-CoachSheets.app-indigo)](https://coachsheets.app/bootcamp)

Welcome to the open-source curriculum for the **CoachSheets Life Coaching Bootcamp**. This repository houses the canonical curriculum, lesson articles, exercises, and capstone projects that power the interactive learning experience at [coachsheets.app/bootcamp](https://coachsheets.app/bootcamp).

Our goal is to build an open, community-driven, world-class coaching curriculum that continuously improves through the shared knowledge, case studies, and practical insights of professional coaches.

---

## 📚 Curriculum Structure

The curriculum is structured into 6 core modules and 1 capstone project (49 total modules/lessons):

| Module | Title | Description | Lessons |
|:---|:---|:---|:---:|
| **01** | **Coaching Foundations** | Core coaching competencies, active listening, ICF ethical boundaries, and goal-setting theory. | 9 |
| **02** | **Coaching Frameworks & Models** | Practical models: GROW, Motivational Interviewing, Cognitive Behavioral Coaching, and Appreciative Inquiry. | 10 |
| **03** | **Digital Coaching Practice** | Scaling coaching with digital worksheets, automated drip sequences, and AI-assisted workflows. | 8 |
| **04** | **Session Mastery** | Pre-session preparation, note-taking, handling resistance, and tracking client progress over time. | 8 |
| **05** | **Building Your Coaching Practice** | Defining your niche, packaging and pricing, marketing, client onboarding, and group programs. | 7 |
| **06** | **Advanced Topics & Specialization** | Cross-cultural coaching, life transitions, positive psychology, and neuroscience-informed coaching. | 7 |
| **07** | **Capstone: Certified Digital Practitioner** | Comprehensive capstone project demonstrating end-to-end coaching competency. | 1 |

---

## 🗂 Repository Layout

```text
.
├── curriculum.json                  # Canonical hierarchy of modules, lessons, slugs, and types
├── README.md                        # Curriculum overview and contribution guidelines
└── resources/
    └── content/
        └── bootcamp/                # Markdown files for each lesson
            ├── what-is-life-coaching.md
            ├── icf-core-competencies.md
            ├── grow-model-deep-dive.md
            └── ...
```

---

## 🤝 How to Contribute

We invite coaches, mentors, and educators to contribute improvements, new lessons, real-world case studies, and exercises.

### Option 1: In-App via CoachSheets (No GitHub Account Required)
Coaches can submit suggestions and proposed curriculum edits directly from inside the app:
1. Visit [coachsheets.app/bootcamp/proposals](https://coachsheets.app/bootcamp/proposals).
2. Click **Propose a Change** and select one of the 6 actions:
   - Edit an existing lesson
   - Add a new lesson to an existing module
   - Add a new module with an introductory lesson
   - Edit a module title or description
   - Propose a reordered lesson sequence
   - Submit a general curriculum suggestion
3. Discuss and collaborate with fellow coaches directly in the proposal discussion thread. CoachSheets automatically opens a Pull Request or Issue here on GitHub in the background.

### Option 2: Directly via GitHub Pull Requests
If you are comfortable with Git and Markdown:
1. Fork this repository.
2. Create a feature branch: `git checkout -b lesson/add-client-boundaries`.
3. Edit or create the relevant markdown file in `resources/content/bootcamp/{lesson-slug}.md`.
4. If adding a new lesson or module, update `curriculum.json` accordingly.
5. Commit your changes and open a Pull Request against `main`.

---

## 🔍 Review and Approval Process

To maintain high instructional quality:
- All community proposals are reviewed by the maintainer.
- When an admin approves a proposal (either via the CoachSheets admin studio or by merging the Pull Request on GitHub), the changes are automatically applied to the live database and deployed to [coachsheets.app/bootcamp](https://coachsheets.app/bootcamp).
- Student progress records (`bootcamp_progress`, quizzes, completed projects) remain fully intact and non-destructive during all curriculum updates.

---

## 📄 License

The curriculum content in this repository is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/) license.
