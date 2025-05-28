# BabelBot

**BabelBot** is an AI-powered meeting assistant and Scrum bot designed to transform Microsoft Teams meetings and uploaded documents into clear, actionable insights and organized project notes.

> **“BabelBot: Turning Meeting Chaos into Clarity.”**

---

## 🚀 What is BabelBot?

BabelBot is an intelligent assistant that listens to your Microsoft Teams meetings—or analyzes uploaded/copy-pasted transcripts, emails, PDFs, and text files—to automatically extract and organize:

- **Key Decisions**
- **Action Items** (with who, what, and when)
- **User Stories/Work Items** (with context and updates as they’re discussed)
- **Open Questions and Blockers**
- **Other Important Notes**

BabelBot goes beyond simple note-taking: it groups, updates, and (optionally) triggers automation, so nothing slips through the cracks.

---

## 🌟 Key Features

- **Automatic Meeting Summaries:** Converts Teams meeting transcripts and uploaded docs into structured notes.
- **Intelligent Action Detection:** Flags requests to create user stories, tickets, or tasks—complete with context and who requested them.
- **Continuous Updates:** Tracks evolving topics as meetings progress and updates notes accordingly.
- **Multi-Source Support:** Works with Teams transcripts, emails, PDFs, and text files.
- **Actionable Outputs:** Groups items by category and can send them to Teams, email, or project management tools.
- **Automation Ready:** Can trigger task creation in tools like Azure DevOps or Jira (with further integration).

---

## 🛠️ How It Works

1. **Ingests Content:** Takes Teams meeting transcripts or uploaded/pasted documents.
2. **Analyzes & Extracts:** Uses advanced AI (via Copilot Studio) to summarize, categorize, and extract action items.
3. **Groups & Updates:** Organizes by topic, tracks ongoing discussions, and keeps notes current.
4. **Distributes Results:** Shares summaries with meeting participants via Teams, email, or connected systems.

---

## 🏁 Getting Started

1. **Clone this repository:**
    ```bash
    git clone https://github.com/Jerry2d3d/BabelBot.git
    ```
2. **(Optional) Review Documentation:**  
   - See [`/docs`](./docs) for advanced configuration, sample AI prompts, and customization guides.

3. **Integrate with Copilot Studio or your automation tool of choice.**

---

## 🤖 Example Use Case

- **During a meeting:**  
    - “We need to create a user story for updating the login page.”
    - BabelBot detects this, makes a note, and (if enabled) automatically creates the user story in Azure DevOps.
    - Later, more details are discussed—BabelBot updates the same item.

- **After the meeting:**  
    - All key decisions, actions, blockers, and notes are grouped and emailed (or posted to Teams) automatically.

---

## 💡 Customization & Contributions

Want to add new triggers or integrations? Have ideas for smarter note grouping?  
**We welcome contributions!**  
See [`CONTRIBUTING.md`](./CONTRIBUTING.md) for guidelines, and open an issue or pull request.

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).

---

## 🙋‍♂️ Contact

Questions, feedback, or want to demo BabelBot?  
Contact [Gerald Hansen](mailto:gerald.hansen@loves.com) or open an issue on GitHub!

---

> “The ultimate answer to meeting notes, action items, and agile teamwork.”

