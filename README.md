# 🔍 ScamLens — Pause. Check. Stay One Step Safer.

<p align="center">
  <strong>Your Digital Safety Companion</strong>
</p>

<p align="center">
  Helping you identify suspicious messages, inspect potentially unsafe URLs, and build smarter digital safety habits.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Project-ScamLens-7C5CFC?style=for-the-badge" alt="ScamLens">
  <img src="https://img.shields.io/badge/Technology-Vanilla%20JavaScript-yellow?style=for-the-badge" alt="Vanilla JavaScript">
  <img src="https://img.shields.io/badge/Platform-Web-blue?style=for-the-badge" alt="Web Platform">
  <img src="https://img.shields.io/badge/Status-Active%20Development-brightgreen?style=for-the-badge" alt="Active Development">
</p>

---

## 🌐 About ScamLens

In today's connected world, digital communication has become part of almost everything we do. From online banking and UPI transactions to social media, shopping, and everyday messaging, we rely on the internet more than ever.

But with this convenience comes an increasing risk of phishing attempts, fraudulent messages, deceptive links, and online scams.

**ScamLens** is a browser-based cybersecurity awareness tool designed to help users recognize common warning signs in suspicious digital communications.

It provides a simple platform to analyze potentially fraudulent messages, inspect suspicious URLs, understand detected warning signs, and learn practical ways to stay safer online.

Rather than overwhelming users with technical security terminology, ScamLens focuses on making digital safety understandable, accessible, and practical.

### Our Mission

To make everyday internet users more aware of digital threats and encourage safer online decisions through accessible cybersecurity tools and education.

> **Pause before you click. Check before you trust. Stay one step safer.**

---

## ✨ Key Features

### 📨 1. Suspicious Message Scanner

Analyze potentially suspicious messages received through SMS, WhatsApp, email, or other digital communication platforms.

- Identifies common phishing and scam-related language patterns.
- Highlights suspicious urgency and pressure tactics.
- Detects potentially fraudulent payment requests.
- Recognizes warning signs involving OTPs, passwords, PINs, and banking details.
- Provides explanations of the patterns detected during analysis.

### 🔗 2. URL Safety Scanner

Inspect potentially unsafe website URLs before deciding whether to visit them.

- Analyzes URL structures without requiring users to open the destination website.
- Identifies unusual or suspicious URL patterns.
- Highlights IP-based hostnames and unusual subdomain structures.
- Checks for certain deceptive-looking domain characteristics.
- Provides an indicative risk score based on detected patterns.

### 📊 3. Explainable Risk Assessment

ScamLens uses a heuristic scoring system to communicate potential warning signs.

- Generates an indicative score between 0 and 100.
- Presents results using three risk-indicator levels.
- Explains which detection patterns contributed to the result.
- Provides relevant safety recommendations.

The goal is not just to display a score, but to help users understand *why* something may deserve attention.

### 🕒 4. Scan History and Reports

Keep track of previously performed scans.

- View previous message and URL analyses.
- Store scan history locally in the browser.
- Export available scan records in CSV format.
- Clear locally stored history whenever required.

### 🎓 5. Cyber Safety Academy

Learn about common online threats through accessible cybersecurity awareness content.

Topics include:

- Phishing attacks
- Fake banking and KYC alerts
- Online job and recruitment scams
- UPI payment fraud
- Fake prize and lottery messages
- OTP theft and social engineering

### 🧠 6. Interactive Cyber Safety Quiz

Test your understanding of common online scams through interactive questions.

- Scenario-based cybersecurity questions.
- Instant feedback on answers.
- Score tracking.
- An engaging way to reinforce safer online habits.

### 📱 7. Responsive User Interface

Designed to provide a consistent experience across different devices.

- Modern cybersecurity-inspired visual design.
- Dark-themed interface.
- Responsive layouts for different screen sizes.
- Simple navigation and user-friendly controls.

---

## 🛠️ Technology Stack

ScamLens is built using lightweight web technologies, keeping the application simple and easy to run.

| Technology | Purpose |
|---|---|
| HTML5 | Application structure and content |
| CSS3 | Styling, layout, and responsive design |
| Vanilla JavaScript | Application logic, detection rules, and interactivity |
| Browser LocalStorage | Local scan-history storage |
| CSV | Exporting scan-history records |
| GitHub | Source-code management |

**No framework or additional package installation is required to run the current application.**

---

## ⚙️ How ScamLens Works

ScamLens currently uses a rule-based detection approach to identify predefined patterns commonly associated with suspicious digital communications.

### Analysis Workflow

**Step 1 — Input**

The user enters a suspicious message or website URL into the relevant scanner.

**Step 2 — Pattern Analysis**

The application processes the input using predefined JavaScript detection rules.

**Step 3 — Warning Identification**

Potentially suspicious patterns are identified and presented with relevant explanations.

**Step 4 — Risk Assessment**

A heuristic score is calculated using the detected patterns.

**Step 5 — Safety Guidance**

The application displays the analysis results and practical recommendations to help users make more informed decisions.

The scoring system is intended as an awareness aid, not as a definitive fraud-verification mechanism.

---

## 🚀 Getting Started

Want to explore ScamLens or run it on your computer? Follow these steps.

### Prerequisites

- A modern web browser.
- Git installed on your system (optional, for cloning the repository).

### 1. Clone the Repository

```bash
git clone https://github.com/iamparrish/scamlens.git
```

### 2. Navigate to the Project Directory

```bash
cd scamlens
```

### 3. Run the Application

You can open `index.html` directly in your browser.

Alternatively, start a local development server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

That's it! No additional dependencies or complex setup are required.

---

## 📂 Project Structure

The current application is organized around the following core files:

```text
ScamLens/
│
├── index.html       # Main application interface
├── style.css        # Styling and responsive layouts
├── app.js           # Application logic and detection functionality
└── favicon.svg      # Application icon
```

Additional documentation files, such as `CONTRIBUTING.md` and `SECURITY.md`, can be added as the project grows.

---

## 🔐 Privacy and Security

Privacy is an important consideration in ScamLens.

The current application is designed to perform its analysis directly in the user's browser.

- No account registration is required.
- Message and URL analysis runs locally.
- Scan history is stored using browser LocalStorage.
- No backend database is required for the current functionality.
- Submitted scan content is not intentionally sent to an external analysis service.

**Important privacy reminder:** Never enter real OTPs, passwords, UPI PINs, CVVs, or other sensitive financial information into any demonstration or analysis tool.

---

## ⚠️ Important Disclaimer

ScamLens is an educational cybersecurity awareness project. It is not a professional security scanner, antivirus solution, or guaranteed fraud-detection service.

Please keep the following limitations in mind:

- Detection is based on predefined rules and patterns, not a trained AI or machine-learning model.
- The application does not currently use live threat-intelligence databases.
- It cannot independently verify the identity of a sender or the ownership of a website.
- Results may include false positives and false negatives.
- A low risk score does not guarantee that a message or website is safe.
- Risk scores are illustrative indicators, not statistically validated probabilities of fraud.

Always exercise caution and verify suspicious communications through official websites, applications, or customer-support channels.

---

## 🇮🇳 Important Cybercrime Resources — India

If you encounter an online scam or financial cyber fraud in India, consider using the following official resources.

| Resource | Purpose |
|---|---|
| [National Cyber Crime Portal](https://cybercrime.gov.in/) | Report cybercrime incidents |
| **1930** | Cyber financial fraud helpline |
| [CERT-In](https://www.cert-in.org.in/) | India's national cybersecurity incident-response agency |
| [Reserve Bank of India](https://www.rbi.org.in/) | Banking and financial awareness resources |

**If you experience financial cyber fraud:** Contact your bank immediately and report the incident through the appropriate official channels as soon as possible.

---

## 🔮 Future Scope

ScamLens is a project that can evolve with additional cybersecurity capabilities.

Potential future improvements include:

- **AI-Assisted Message Analysis:** Explore more advanced message analysis through a secure backend.
- **URL Reputation Integration:** Connect with trusted URL reputation and threat-intelligence services.
- **Multilingual Detection:** Support scam identification across multiple languages.
- **Advanced Phishing Detection:** Improve detection techniques for deceptive websites and communication.
- **Improved Evaluation:** Test detection rules against diverse datasets and measure their effectiveness.
- **Detailed Security Reports:** Provide more comprehensive explanations and downloadable reports.
- **Expanded Learning Resources:** Add more interactive cybersecurity lessons and real-world scenarios.

These are possible future enhancements and are not represented as currently implemented features.

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!

Whether you're interested in frontend development, cybersecurity, usability, or documentation, your contribution can help make ScamLens better.

### How to Contribute

1. Fork this repository.
2. Create a new feature branch.
3. Make your changes.
4. Test your implementation.
5. Commit and push your changes.
6. Open a Pull Request describing your contribution.

For contribution guidelines, see [CONTRIBUTING.md](CONTRIBUTING.md) when available.

---

## 👨‍💻 Developer

**Parrish Tarak**

Developer of ScamLens — a project focused on making cybersecurity awareness more accessible and encouraging safer digital habits.

- **GitHub:** [@iamparrish](https://github.com/iamparrish)
- **Project Repository:** [ScamLens](https://github.com/iamparrish/scamlens)

---

## ⭐ Support the Project

If you find ScamLens useful or appreciate its goal of promoting digital safety:

- Give the repository a ⭐ Star.
- Share it with friends and fellow developers.
- Suggest improvements or report issues.
- Contribute to making the internet a safer place.

Every contribution, suggestion, and bit of support is appreciated.

---

<p align="center">
  <strong>Built with a vision to promote safer digital habits.</strong>
  <br><br>
  🔍 <strong>ScamLens — Pause. Check. Stay One Step Safer.</strong>
</p>
