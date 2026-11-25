# 🔍 ScamLens — Pause. Check. Stay One Step Safer.

<p align="center">
  <strong>Your Digital Safety Companion</strong>
</p>

<p align="center">
  Identify suspicious messages, inspect potentially unsafe URLs, and develop smarter digital safety habits.
</p>

<p align="center">
  <a href="https://github.com/iamparrish/scamlens">
    <img src="https://img.shields.io/badge/Project-ScamLens-7C5CFC?style=for-the-badge" alt="ScamLens">
  </a>
  <img src="https://img.shields.io/badge/Technology-Vanilla%20JavaScript-yellow?style=for-the-badge" alt="JavaScript">
  <img src="https://img.shields.io/badge/Platform-Web-blue?style=for-the-badge" alt="Web">
  <img src="https://img.shields.io/badge/Hosting-GitHub%20Pages-black?style=for-the-badge" alt="GitHub Pages">
</p>

---

## 🌐 About ScamLens

ScamLens is a lightweight cybersecurity awareness project designed to help users recognize common warning signs in suspicious digital communications.

With the increasing use of online banking, UPI payments, digital services, and social media, fraudulent messages and deceptive links have become a growing concern.

ScamLens provides a simple platform where users can analyze suspicious messages, inspect URLs, understand potential warning signs, and learn practical ways to protect themselves online.

The project focuses on making cybersecurity awareness more accessible through an easy-to-use interface and explainable results.

**Our philosophy is simple: Pause before you click. Check before you trust.**

## ✨ Key Features

### 📨 1. Message Scanner
- Analyze suspicious SMS, WhatsApp messages, and emails.
- Identify common phishing and fraud-related patterns.
- Detect suspicious payment requests and urgent messages.
- Highlight requests involving OTPs, passwords, PINs, and banking information.
- Display explanations for detected warning signs.

### 🔗 2. URL Scanner
- Inspect website URLs without opening them.
- Identify potentially suspicious URL structures.
- Detect unusual subdomains and IP-based hostnames.
- Highlight certain deceptive-looking domain characteristics.
- Display an illustrative warning score.

### 📊 3. Risk Indicator System
- Provides a heuristic score from 0 to 100.
- Displays three warning levels: Lower Indicator Score, Caution, and High Risk.
- Explains which detection patterns contributed to the score.
- Provides practical safety recommendations.

### 🕒 4. Scan History
- View previously analyzed messages and URLs.
- Store scan history locally in the browser.
- Export scan history in CSV format.
- Clear saved history whenever required.

### 🎓 5. Cyber Safety Academy
Learn about common online fraud techniques, including:
- Phishing attacks
- Fake banking and KYC alerts
- Online job scams
- UPI payment fraud
- Fake prize and lottery messages
- OTP theft and social engineering

### 🧠 6. Interactive Safety Quiz
- Test your cybersecurity awareness.
- Answer practical scenario-based questions.
- Receive instant feedback.
- Track your quiz score and improve your knowledge.

### 📱 7. Responsive Interface
- Modern cybersecurity-inspired design.
- Dark-themed user interface.
- Responsive layout for different screen sizes.
- Simple navigation and accessible controls.

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling and responsive design |
| JavaScript | Detection logic and interactivity |
| LocalStorage | Browser-based scan history |
| GitHub Pages | Static website hosting |

## ⚙️ How It Works

ScamLens currently uses a lightweight, rule-based detection mechanism.

**Step 1 — Input:** The user enters a suspicious message or URL.

**Step 2 — Analysis:** JavaScript checks the input against predefined detection patterns.

**Step 3 — Identification:** Matching patterns are displayed with explanations.

**Step 4 — Risk Indicator:** A heuristic score is calculated using the matched rules.

**Step 5 — Awareness:** The user receives safety recommendations and guidance.

The results are designed to help users make more informed decisions rather than automatically determine whether something is fraudulent.

## 🚀 Getting Started

### Run the project locally

Clone the repository:

\`\`\`bash
git clone https://github.com/iamparrish/scamlens.git
\`\`\`

Navigate to the project directory:

\`\`\`bash
cd scamlens
\`\`\`

Open the application by launching:

\`\`\`text
index.html
\`\`\`

Alternatively, start a local development server:

\`\`\`bash
python -m http.server 8000
\`\`\`

Open the following address:

\`\`\`text
http://localhost:8000
\`\`\`

No additional dependencies or installation steps are required.

## 📂 Project Structure

\`\`\`text
ScamLens/
│
├── index.html          # Main application interface
├── style.css           # Styling and responsive design
├── app.js              # Detection logic and application functionality
├── favicon.svg         # Application icon
├── README.md           # Project documentation
├── CONTRIBUTING.md     # Contribution guidelines
└── SECURITY.md         # Security policy
\`\`\`

## 🔐 Privacy and Security

ScamLens is designed to perform its current analysis directly in the user's browser.

- No account registration is required.
- Message and URL analysis runs locally.
- Scan history is stored using browser LocalStorage.
- No backend database is currently required.
- The application does not intentionally transmit submitted scan content to an external analysis service.

**Privacy reminder:** Avoid entering real OTPs, passwords, PINs, CVVs, or sensitive banking information.

## ⚠️ Important Disclaimer

ScamLens is an educational cybersecurity prototype and should not be considered a professional security scanner.

- Detection is based on predefined patterns, not a trained AI model.
- It does not use live threat-intelligence databases.
- It cannot verify website ownership or sender identity.
- It may produce false positives and false negatives.
- A low score does not guarantee that a message or website is safe.
- Risk scores are illustrative indicators, not probabilities of fraud.

Always verify suspicious communications through official channels.

## 🇮🇳 Important Cybercrime Resources

If you encounter online fraud in India, use official reporting channels.

| Resource | Details |
|---|---|
| National Cyber Crime Portal | https://cybercrime.gov.in/ |
| Cyber Financial Fraud Helpline | 1930 |
| CERT-In | https://www.cert-in.org.in/ |
| Reserve Bank of India | https://www.rbi.org.in/ |

If you experience financial cyber fraud, contact your bank immediately and report it promptly through the appropriate official channels.

## 🔮 Future Scope

Potential future improvements include:

- AI-assisted message analysis through a secure backend.
- Integration with trusted URL reputation services.
- Multilingual scam detection.
- Advanced phishing detection techniques.
- Improved detection accuracy through testing and evaluation.
- More detailed security reports.
- Expanded cybersecurity learning resources.

These are planned possibilities, not currently implemented features.

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

If you would like to contribute:

1. Fork this repository.
2. Create a new branch.
3. Make your changes.
4. Test your implementation.
5. Submit a Pull Request.

Please refer to [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 👨‍💻 Developer

**Parrish Tarak**

GitHub: [@iamparrish](https://github.com/iamparrish)

Project: [ScamLens](https://github.com/iamparrish/scamlens)

---

<p align="center">
  <strong>Built with a vision to promote safer digital habits.</strong>
  <br><br>
  🔍 Pause. Check. Stay One Step Safer.
</p>
