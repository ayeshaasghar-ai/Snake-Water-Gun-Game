# 🔒 Security Policy

## 📦 Supported Versions

The following versions of Snake Water Gun Game are currently supported with security updates:

| Version | Supported          |
|---------|--------------------|
| 1.0.x   | ✅ Yes             |
| < 1.0   | ❌ No              |

---

## 🐛 Reporting a Vulnerability

I take security seriously — even for small projects. If you discover a security vulnerability in this project, please follow the steps below:

### 📬 How to Report

**Please do NOT open a public GitHub Issue for security vulnerabilities.**

Instead, report it privately by:

- 📧 **Email:** your-email@gmail.com
- 🔒 **GitHub Private Advisory:** Go to `Security` tab → `Report a vulnerability`

### 📝 What to Include in Your Report

Please provide as much detail as possible:

- **Description** of the vulnerability
- **Steps to reproduce** the issue
- **Potential impact** — what could an attacker do?
- **Suggested fix** (if you have one)

---

## ⏱️ Response Timeline

| Action | Timeframe |
|--------|-----------|
| Initial response to your report | Within **48 hours** |
| Confirmation of the vulnerability | Within **5 days** |
| Fix released (if valid) | Within **14 days** |

---

## ✅ What Happens After You Report?

1. You will receive an acknowledgement within **48 hours**
2. The issue will be investigated and verified
3. If confirmed, a fix will be developed and tested
4. A new version will be released with the fix
5. You will be **credited** in the release notes (if you wish)

---

## 🔐 Security Best Practices for Contributors

If you are contributing to this project, please follow these guidelines:

- **Never** hardcode sensitive data (passwords, API keys, tokens)
- **Validate** all user inputs properly
- **Avoid** using `eval()` or `exec()` functions
- Keep all **dependencies updated**
- Follow **PEP 8** and write clean, readable code

---

## ⚠️ Known Security Considerations

Since this is a **CLI-based Python game**, the main security consideration is:

- **Input Validation** — The current version accepts only `s`, `w`, or `g` as valid inputs. Invalid inputs may cause a `KeyError`. This is a known issue and will be handled in a future update.

---

## 🙏 Responsible Disclosure

I kindly request that you practice **responsible disclosure**:

- Give me reasonable time to fix the issue before making it public
- Do not exploit the vulnerability maliciously
- Do not share vulnerability details with others before the fix is released

I truly appreciate the security community's efforts in keeping open source projects safe! 🛡️

---

## 👩‍💻 Author

**Ayesha**
- Email: ayeshaasghar.1310@gmail.com

---

Thank you for helping keep this project secure! 🔒
