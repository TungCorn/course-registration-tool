# 🎓 Course Registration Tool

A browser automation tool demonstrating DOM manipulation and JavaScript injection techniques for educational purposes.

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![License](https://img.shields.io/badge/License-MIT-green)
![Purpose](https://img.shields.io/badge/Purpose-Educational-blue)

---

## ⚠️ DISCLAIMER

> **This tool is created for EDUCATIONAL PURPOSES ONLY** to demonstrate:
> - DOM manipulation techniques
> - JavaScript automation skills
> - Browser scripting concepts
>
> **The author does NOT encourage:**
> - Using this tool to bypass university regulations
> - Disrupting server operations
> - Any form of unauthorized access
>
> **USE AT YOUR OWN RISK.** The author is not responsible for any consequences.

---

## 📖 About This Project

This project was built as a learning exercise to understand:

- 🔍 How browser automation works
- 🎯 DOM element selection and manipulation
- ⏱️ Timing and interval-based scripting
- 🛡️ Rate limiting and responsible automation

**This is NOT a hacking tool.** It's a demonstration of front-end automation concepts that can be applied to legitimate use cases like:
- Automated testing
- Web scraping (with permission)
- Browser extensions development

---

## 🛠️ Technical Concepts Demonstrated

| Concept | Description |
|---------|-------------|
| DOM Manipulation | Selecting and interacting with page elements |
| Event Simulation | Programmatically triggering click events |
| Interval Timing | Using `setInterval` for repeated actions |
| Error Handling | Graceful handling of missing elements |
| Rate Limiting | Preventing server overload with delays |

---

## 📋 Configuration

```javascript
// filepath: src/config.js
module.exports = {
    // Replace with your target URL (for educational testing only)
    targetUrl: "YOUR_UNIVERSITY_PORTAL_URL",
    
    // Course codes to monitor (example format)
    courseCodes: ["COURSE_001", "COURSE_002"],
    
    // Safe delay to simulate human behavior (in milliseconds)
    // DO NOT set below 2000ms to avoid server overload
    delayMs: 3000,
    
    // Maximum retry attempts
    maxRetries: 10
};
```

---

## 🚀 How It Works (Educational Overview)

```
┌─────────────────┐
│  Load Config    │
└────────┬────────┘
         ▼
┌─────────────────┐
│  Find Elements  │ ◄── DOM Query Selectors
└────────┬────────┘
         ▼
┌─────────────────┐
│  Check Status   │ ◄── Read element properties
└────────┬────────┘
         ▼
┌─────────────────┐
│  Simulate Click │ ◄── Trigger events
└────────┬────────┘
         ▼
┌─────────────────┐
│  Wait (Delay)   │ ◄── Rate limiting
└────────┬────────┘
         ▼
      Repeat
```

---

## 📂 Project Structure

```
course-registration-tool/
├── src/
│   ├── main.js        # Main automation logic
│   ├── config.js      # Configuration (user must fill)
│   └── utils.js       # Helper functions
├── assets/            # Screenshots, demos
├── .gitignore
├── LICENSE
├── package.json
└── README.md
```

---

## ⚙️ Setup (For Learning)

```bash
# Clone repository
git clone https://github.com/YOUR_USERNAME/course-registration-tool.git
cd course-registration-tool

# Install dependencies (if any)
npm install

# Edit config with YOUR test environment
# DO NOT use on production systems without permission
nano src/config.js
```

---

## 🔒 Safety Features Built-in

| Feature | Purpose |
|---------|---------|
| **3000ms default delay** | Simulates human clicking speed |
| **Max retry limit** | Prevents infinite loops |
| **No hardcoded credentials** | User must input their own |
| **Generic selectors** | Not targeted at specific systems |

---

## 📝 Lessons Learned

Building this project taught me:

1. **DOM APIs** - `querySelector`, `querySelectorAll`, event dispatching
2. **Async JavaScript** - Promises, intervals, timeouts
3. **Ethical considerations** - Rate limiting, responsible automation
4. **Code organization** - Separating config, utils, and main logic

---

## 🎯 Legitimate Use Cases

This knowledge can be applied to:

- ✅ **Selenium/Puppeteer testing** - Automated QA
- ✅ **Browser extensions** - Productivity tools
- ✅ **Web scraping** - Data collection (with permission)
- ✅ **Accessibility tools** - Helping users navigate sites

---

## ❓ FAQ

**Q: Can I use this on my university's website?**
A: Check your university's terms of service. Many prohibit automated access. This tool is for learning, not production use.

**Q: Will this get me in trouble?**
A: If used irresponsibly, yes. Always get permission before automating any website.

**Q: Why share this publicly?**
A: To demonstrate technical skills for portfolio/CV purposes and help others learn browser automation concepts.

---

## 📄 License

MIT License - Free to use for educational purposes.

---

## 👤 Author

Created as a learning project to explore browser automation.

**Skills demonstrated:**
- JavaScript (ES6+)
- DOM Manipulation
- Async Programming
- Clean Code Architecture

---

> 💡 **For Recruiters:** This project showcases my understanding of browser APIs, automation concepts, and responsible coding practices. I built this to learn, not to exploit.


