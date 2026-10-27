# Google-Dorks Guide 🕵️‍♂️

Welcome to the **Google-Dorks** repository! This repository contains a comprehensive guide on Google Dorking, including foundational search operators, practical applications, and useful information for security researchers, bug bounty hunters, and OSINT enthusiasts.

## ⚠️ Disclaimer

**Please read all the instructions carefully before proceeding.**

This repository is intended for **educational and ethical purposes only**. The techniques and information provided here should only be used on systems and domains for which you have explicit, authorized permission. Unauthorized scanning or exploiting of systems is illegal and strictly prohibited. The author is not responsible for any misuse of the information contained in this repository.

## 📖 What are Google Dorks?

Google Dorks are advanced search queries that leverage Google's search operators to uncover hidden, exposed, or sensitive information indexed by the search engine. By combining specific operators, you can refine search results in ways that go far beyond standard search capabilities.

## 🛠️ Core Search Operators

This repository breaks down the most essential operators you need to know. Here are the top 10 operators covered in the files:

| Operator | Description | Example |
| :--- | :--- | :--- |
| `site:` | Limits results to a specific domain or website. | `site:example.com` |
| `intitle:` | Restricts results to pages containing specific words in the title. | `intitle:"index of /admin"` |
| `inurl:` | Narrows results to URLs containing specific words. | `inurl:login.php` |
| `filetype:` | Finds specific file types (PDFs, spreadsheets, databases). | `filetype:pdf site:example.com` |
| `ext:` | Similar to `filetype:`, searches for specific file extensions. | `ext:php intitle:"index of"` |
| `cache:` | Views the cached version of a webpage. | `cache:example.com` |
| `related:` | Provides results related to a specific website. | `related:nytimes.com` |
| `info:` | Provides information about a specific webpage. | `info:example.com` |
| `intext:` | Searches for pages containing specific words in their body text. | `intext:"privacy policy"` |
| `allintitle:` | Requires all specified words to appear in the page title. | `allintitle:OpenAI GPT-3` |

## 🎯 Practical Applications

Google Dorks are invaluable for various security and research tasks:

- **Ethical Hacking & Penetration Testing:** Identifying potential vulnerabilities and exposed admin panels.
- **OSINT (Open-Source Intelligence):** Gathering publicly available information about a target.
- **Bug Bounty Hunting:** Discovering sensitive files, directories, and misconfigurations.
- **Security Auditing:** Checking if your own organization is leaking sensitive data.

## 📂 Repository Contents

- **`Google Dorks .file`** - Foundational operators and explanations.
- **`Google Dorks 1.file` to `5.file`** - Various collections and categorized dork lists.
- **`Google Dorks Attack .txt`** - Specific attack vectors using dorks.
- **`SQL.file`** - Dorks related to SQL injections and database exposures.

## 🤝 Contributing

If you have new dorks, better explanations, or want to organize the repository structure better, feel free to contribute!
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/NewDorks`).
3. Commit your changes (`git commit -m 'Added new SQL dorks'`).
4. Push to the branch (`git push origin feature/NewDorks`).
5. Open a Pull Request.

## 👤 Author

**Tawfique Elahey**
- GitHub: [@tawfique02](https://github.com/tawfique02)

---
⭐ *If you find this repository helpful, please consider giving it a star!*
