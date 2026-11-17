# 📝 JEE (Main) 2027 Mock Test: CBT Mode

A full-length **JEE (Main) 2027 Paper 1 (B.E./B.Tech.)** practice mock test that recreates the look and feel of the real NTA computer-based test (CBT), right in your browser.

🔗 **Take the test:** https://jeemainscbtmodemocktest.aarushoberoi.workers.dev

---

## 🎯 Exam Pattern

| Detail | Value |
| ------ | ----- |
| Duration | 180 minutes (3 hours) |
| Total questions | 75 |
| Subjects | Physics (Q1–25), Chemistry (Q26–50), Mathematics (Q51–75) |
| Per subject | **Section A:** 20 MCQs (one correct option) · **Section B:** 5 numerical-value questions |
| Marking | **+4** correct · **−1** incorrect · **0** unanswered (MCQs and numericals) |
| Language | English |

All questions are compulsory.

## ✨ Features

- **Authentic CBT interface** modelled on the real exam screen
- **Login screen** with candidate name and optional roll number
- **Instructions page** that must be accepted before starting, as in the real exam
- **Countdown timer**, with the test ending automatically at zero
- **Question palette** showing each question's status: not visited, not answered, answered, marked for review, and answered and marked for review
- **Section tabs** to switch between Physics, Chemistry and Mathematics at any time
- **Answer controls:** Save & Next, Clear, Mark for Review & Next, Save & Mark for Review, Back and Next
- **On-screen keypad** for numerical-value questions
- **Collapsible palette** for a larger question area
- **Progress saved in your browser**, so refreshing the page won't lose your answers
- **Static site** with no sign-up, no backend and nothing to install

## 🧭 How to Use

1. Open the [live site](https://jeemainscbtmodemocktest.aarushoberoi.workers.dev).
2. Enter your name (roll number is optional) and click **Login**.
3. Read the instructions, tick the declaration and click **Proceed**.
4. Attempt the paper within 3 hours. Use **Save & Next** to record each answer.
5. Click **Submit** when you're done (or let the timer end the test).

> 💡 **Tip:** Treat it like the real exam. Sit down for the full 3 hours, avoid external help, and review your marked questions before time runs out.

## 🗂️ Project Structure

```
JEE-Mains-CBT-Mode-Mock-Test/
├── index.html    # Test interface (login, instructions, exam screen)
├── ...           # Scripts, styles and question data
└── README.md
```

## 🚀 Run Locally

```bash
git clone https://github.com/AarushOberoi/JEE-Mains-CBT-Mode-Mock-Test.git
cd JEE-Mains-CBT-Mode-Mock-Test

# Option 1: Python
python -m http.server 8000

# Option 2: Node
npx serve .
```

Then open `http://localhost:8000`.

## ☁️ Deployment

Deployed as static assets on **Cloudflare Workers**:

```bash
npx wrangler deploy
```

## 🤝 Contributing

Found a wrong answer, a typo or a bug? Contributions are welcome:

1. Fork the repository
2. Create a branch: `git checkout -b fix/question-number`
3. Commit your changes and open a pull request

## ⚠️ Disclaimer

This is an **unofficial practice mock test**. It is not affiliated with, endorsed by, or connected to the National Testing Agency (NTA) or the official JEE (Main) examination. The pattern follows the publicly announced exam format, but the questions are for practice only and may differ from the real paper in difficulty and style.

## 👤 Author

Made by [Aarush Oberoi](https://github.com/AarushOberoi)
