# 🛡️ Phishing Awareness Training

An interactive, browser-based **Phishing Awareness Training** application designed to teach users how to identify, prevent, and respond to phishing and social-engineering attacks.

The project is built as a single-page HTML application using HTML, CSS, and JavaScript, with no backend or external dependencies.

## 🚀 Features

- 📚 11 interactive training slides
- 🎣 Introduction to phishing and common attack types
- 📧 Phishing email identification
- 🚩 Red-flag detection checklist
- 🔍 Fake website and URL analysis
- 🧠 Social engineering awareness
- 🧪 Interactive phishing email examples
- 📖 Real-world phishing case studies
- 🛡️ Security best-practice checklist
- 🚨 Incident-response guidance
- 🎯 Interactive knowledge-check quiz
- 🔀 Randomized quiz questions
- 📊 Automatic quiz scoring
- 💡 Answer explanations
- 🏆 Certificate generation after passing
- 💾 Checklist progress saved using `localStorage`
- ⌨️ Keyboard navigation
- 📱 Responsive design

## 🎯 Objectives

1. Educate users about phishing attacks.
2. Help users recognize suspicious emails and websites.
3. Explain common social-engineering techniques.
4. Promote safe online security practices.
5. Provide an interactive learning experience.
6. Test the user's knowledge through quizzes.
7. Teach users what to do after a suspected phishing incident.

## 🧰 Technologies Used

| Technology | Purpose |
|---|---|
| **HTML5** | Application structure and training content |
| **CSS3** | UI design, responsive layout and animations |
| **JavaScript** | Navigation, quiz logic, scoring and interactions |
| **LocalStorage** | Saving checklist progress |
| **Browser APIs** | Certificate generation and keyboard controls |

No framework, database, backend server, or package installation is required.

## 📂 Project Structure

```text
Phishing Awareness Training/
│
├── index.html
└── README.md
```

The current implementation contains the HTML, CSS, and JavaScript directly inside `index.html`.

## ▶️ How to Run

### Method 1 — Open Directly

Double-click:

```text
index.html
```

The application will open in your default browser.

### Method 2 — VS Code + Live Server

1. Open the project folder in Visual Studio Code.
2. Open `index.html`.
3. Install the **Live Server** extension if needed.
4. Right-click `index.html`.
5. Select **Open with Live Server**.

## 🧑‍🏫 Training Modules

### 1. Introduction
Introduces phishing and explains the purpose of the training.

### 2. What is Phishing?
Covers:
- Email phishing
- Spear phishing
- Whaling
- Smishing
- Vishing
- Clone phishing

### 3. Recognizing Phishing Emails

Users learn to identify:
- Urgent language
- Generic greetings
- Grammar mistakes
- Suspicious sender addresses
- Unexpected attachments
- Mismatched URLs
- Requests for sensitive information
- Fake prizes or offers

### 4. Interactive Email Analysis

The project provides phishing and legitimate email examples where users can reveal the analysis and identify suspicious indicators.

### 5. Fake Website Detection

Users learn to inspect:
- URLs
- HTTPS/certificates
- Domain names
- Website quality
- Contact information
- Suspicious pop-ups
- URL manipulation techniques

### 6. Social Engineering

The training explains:
- Urgency
- Authority
- Social proof
- Reciprocity
- Curiosity
- Fear
- Trust/familiarity
- Pretexting
- Baiting
- Quid pro quo
- Tailgating

### 7. Case Studies

The project includes examples of real-world phishing/social-engineering incidents, including the Google/Facebook scam, Twitter incident, and Colonial Pipeline incident.

### 8. Security Best Practices

Users are encouraged to practice:
- MFA
- Password-manager usage
- Independent verification
- Software updates
- Careful link checking
- Suspicious-email reporting
- Limiting personal information online
- Email filtering

### 9. Incident Response

The application provides steps to follow if a user believes they have been phished, including changing passwords, enabling MFA, scanning the device, reporting the incident, and monitoring accounts.

### 10. Knowledge Quiz

The quiz randomly shuffles its questions and calculates the user's score automatically.

A score of **80% or higher** is treated as passing, and the certificate option becomes available after passing.

### 11. Certificate

After successfully completing the training, users can generate a text-based certificate containing:
- Completion date
- Quiz score
- Demonstrated competencies

## 🎨 UI Features

- Responsive layout
- Gradient header
- Progress bar
- Slide-based navigation
- Interactive cards
- Warning/success/information boxes
- Animated slide transitions
- Interactive checklists
- Quiz result visualization

## 🔐 Cybersecurity Purpose

This project is intended for **education and security awareness**.

It demonstrates how users can be trained to recognize phishing indicators and develop safer cybersecurity habits. It does **not** collect credentials, send phishing emails, or perform real-world attacks.

## 📸 Demo Flow

```text
Start Training
      │
      ▼
Phishing Fundamentals
      │
      ▼
Identify Email Red Flags
      │
      ▼
Analyze Example Emails
      │
      ▼
Identify Fake Websites
      │
      ▼
Learn Social Engineering
      │
      ▼
Study Case Examples
      │
      ▼
Learn Security Practices
      │
      ▼
Incident Response
      │
      ▼
Interactive Quiz
      │
      ▼
Score
      │
      ├── < 80% ──► Retake Training
      │
      └── ≥ 80% ──► Certificate
```

## 🔮 Future Improvements

Possible future enhancements:
- User login and progress tracking
- Backend database
- Admin dashboard
- User-specific certificates
- More quiz questions
- Difficulty levels
- Phishing email simulation environment
- Email-header analysis
- URL reputation checking
- AI-powered phishing detection
- Training analytics
- Organization-wide employee dashboards
- PDF certificate generation
- Multi-language support

## ⚠️ Disclaimer

This project is created for **cybersecurity education and awareness training**. The phishing examples are simulated educational scenarios. Users should not use the project to deceive, impersonate, or target real individuals or organizations.

## 👨‍💻 Author

**Hacker Return**

GitHub: https://github.com/badshah3429

## 📄 License

This project can be used for educational and academic purposes. Add a formal open-source license such as MIT if you want to publish the project for broader reuse.
