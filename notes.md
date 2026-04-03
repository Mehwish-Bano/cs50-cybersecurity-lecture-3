📝 Lecture 3 Notes – Securing Software

🔹 Phishing

Users are tricked into clicking fake links or entering sensitive data.

Example:
Fake link shows trusted site but redirects elsewhere.

---

🔹 Code Injection (XSS)

Injecting malicious scripts into a website.

Example:

<script>alert('attack')</script>---

🔹 Types of XSS

Reflected Attack

- Comes from URL
- Triggered immediately

Stored Attack

- Stored in database
- Affects multiple users

---

🔹 Character Escaping

Special characters are converted into safe format.

Examples:
< becomes <

«becomes >»

---

🔹 HTTP Security Headers

Content-Security-Policy (CSP):

- Restricts scripts & styles
- Prevents XSS

---

🔹 SQL Injection

Example attack:
' OR '1'='1

Effect:

- Bypass login
- Access all data

---

🔹 Prepared Statements

Safe way to handle database queries.

Uses:

- ? instead of direct input
- Prevents SQL injection

---

🔹 Command Injection

User input executes system commands.

Danger:

- Full system compromise

---

🔹 Developer Tools Risk

Users can modify frontend validation.

⚠️ Never rely on client-side validation only

---

🔹 Server-Side Validation

Validates input on backend (secure method)

---

🔹 CSRF (Cross-Site Request Forgery)

Tricks user into performing unwanted actions.

Protection:

- CSRF Tokens

---

🔹 Arbitrary Code Execution (ACE)

Includes:

- Buffer Overflow
- Stack Overflow

---

🔹 Open vs Closed Source

Open Source:
✔ Transparent
❌ Still vulnerable

Closed Source:
✔ Hidden code
❌ Less community review

---

🔹 App Stores Security

- Verified apps
- Digital signatures

---

🔹 Package Managers

- Install trusted libraries
- Use signing mechanisms

---

🔹 Bug Bounty

Companies pay hackers to find bugs legally

---

🔹 Vulnerability Tracking

- CVE → Known vulnerabilities
- CVSS → Severity score
- EPSS → Exploit prediction
- KEV → Known exploited vulnerabilities

---
