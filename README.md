# CyberGuard — Password Strength & Security Analyzer

CyberGuard is a browser-based password security tool that analyzes password strength, estimates entropy, detects predictable patterns, and generates random passwords and passphrases. It features a cybersecurity-focused dashboard with real-time feedback and privacy-conscious, client-side processing.

## Features

- **Real-Time Password Analysis** — Displays strength scores, character composition, and entropy estimates.
- **Pattern Detection** — Identifies common passwords, repeated characters, sequential patterns, keyboard walks, and year patterns.
- **Crack-Time Estimates** — Compares estimated cracking times across different attack-rate scenarios.
- **Secure Password Generator** — Generates random passwords using the browser's Web Crypto API.
- **Passphrase Generator** — Creates configurable multiword passphrases.
- **Quick Presets** — Test weak, complex, sequential, and passphrase examples.
- **Privacy Controls** — Includes password visibility, blur protection, and clipboard-copy options.
- **Responsive Interface** — Built with a dark cybersecurity-themed dashboard.

## Technologies Used

- HTML5
- Tailwind CSS (CDN)
- JavaScript
- Lucide Icons
- Web Crypto API

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/AhadAbbasi996/ahad-dev-toolkit.git
   ```
2. Open the `password-strength-checker` folder.
 ```bash
cd ahad-dev-toolkit/password-strength-checker
 ```
3. Open `index.html` in a modern web browser.
On Windows:
 ```bash
start index.html
 ```
 On macOS:
 ```bash
open index.html
```

On Linux:
 ```bash
xdg-open index.html
```
No build tools or package installation are required. A modern web browser is all you need.

## Privacy & Security

Password analysis is performed in the browser, and the application does not send entered passwords to a backend server. However, the page loads third-party resources through CDNs. For sensitive use, review the code and consider hosting dependencies locally.

**Important:** Strength scores, entropy values, and cracking-time estimates are heuristic approximations, not guarantees of real-world security. Use a trusted password manager and avoid reusing passwords.

## Author

**Abdul Ahad**  
Software Engineering Undergraduate | Cybersecurity Enthusiast

- GitHub: [@AhadAbbasi996](https://github.com/AhadAbbasi996)
- Project Repository: [ahad-dev-toolkit](https://github.com/AhadAbbasi996/ahad-dev-toolkit)

---

*Built as a practical project exploring password security, browser-based JavaScript, and cybersecurity concepts.*
