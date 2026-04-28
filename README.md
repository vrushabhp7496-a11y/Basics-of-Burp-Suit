# 🕸️ Burp Suite Basics

This repository documents my hands-on learning of **Burp Suite** — the industry-standard tool for web application security testing.

---

## 📌 What's inside this project?

In the PDF below, I have covered the core concepts and features of Burp Suite with explanations and screenshots.

[📄 **Burp Suite Basics - Full PDF**](./burp-suit-basics.docx.pdf)

### 📂 Topics covered in the PDF:

| # | Topic | Description |
| :--- | :--- | :--- |
| 1 | What is Burp Suite? | Java-based, API-based manual pentesting tool |
| 2 | Features of Burp Suite | Proxy, Repeater, Intruder, Decoder, Comparer, Sequencer |
| 3 | The Dashboard | Tasks, Event Log, Issue Activity, Advisory |
| 4 | Navigation | Navigation bar, keyboard shortcuts |
| 5 | Options | Global settings vs Project settings |
| 6 | Burp Proxy | Intercepting HTTP/HTTPS traffic, Request manipulation |
| 7 | Burp Suite Browser | Built-in Chromium browser (no FoxyProxy needed) |
| 8 | Scoping & Targeting | Adding targets to scope, filtering traffic |
| 9 | Example Attack | XSS attack demonstration through request manipulation |

---

## 🛠️ Key Features I Learned

| Feature | What it does |
| :--- | :--- |
| **Proxy** | Intercepts and manipulates requests/responses between browser and server |
| **Repeater** | Capture, modify, and resend the same request multiple times |
| **Intruder** | Spray endpoints with requests (brute force, fuzzing) |
| **Decoder** | Encode/decode data in various formats |
| **Comparer** | Compare two pieces of data (binary or ASCII) |
| **Sequencer** | Analyze randomness of tokens/session IDs |

---

## ⌨️ Essential Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| `Ctrl + Shift + D` | Dashboard |
| `Ctrl + Shift + T` | Target tab |
| `Ctrl + Shift + P` | Proxy tab |
| `Ctrl + Shift + I` | Intruder tab |
| `Ctrl + Shift + R` | Repeater tab |

---

## 🔧 Burp Suite Settings

| Setting Type | Scope |
| :--- | :--- |
| **Global Settings (User Settings)** | Affect entire Burp Suite installation |
| **Project Settings** | Apply only to current project |

---

## 🎯 Why Scoping is Important

When capturing all traffic, it can be overwhelming to find the right requests. **Scoping** allows you to:
- Add your target to scope
- Capture ONLY traffic related to your target
- Filter out noise from other websites

---

## 💥 Example Attack (XSS)

In this lab, I demonstrated a basic **Cross-Site Scripting (XSS)** attack:

1. Entered a legitimate email and query
2. Intercepted the request in Burp Proxy
3. Modified the email field with: `<script>alert("Successful XSS")</script>`
4. Forwarded the request — the script executed successfully ✅

---

## 💡 What I Learned

> "Burp Suite is not just a tool — it's a complete ecosystem for web application security testing."

- ✅ Burp Proxy gives **complete control** over HTTP/HTTPS traffic
- ✅ Repeater turns manual testing into **controlled experimentation**
- ✅ Intruder automates **brute force and fuzzing attacks**
- ✅ Scoping filters out **unnecessary traffic**
- ✅ Even the **Community Edition** is extremely powerful for learning

---

## 📚 How I Learned

| Resource | What I Used |
| :--- | :--- |
| **TryHackMe** | Burp Suite rooms (Basics, Repeater, Intruder) |

---

## 🔗 My Other Projects

- 🔐 [Cybersecurity Basics]
- 🐧 [Linux Fundamentals]
- 🪟 [Windows Fundamentals]
- 🏢 [Active Directory Lab]
- 📡 [Nmap Scanning]
- 🛡️ [Metasploit Exploitation]
- 🔑 [Hydra Brute Force]

> *"Burp Suite is the Swiss Army knife of web security. Master it, and you master the web."*

⭐ **Star this repository** if you found it helpful!
