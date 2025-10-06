# 📚 Free Programming Books

[Join WhatsApp channel for any doubts](https://chat.whatsapp.com/BfBWJhy4xj3CJFSGE2qBrL)


<div align="center">

[![Contributors](https://img.shields.io/github/contributors/avinash201199/Free-programming-books)](https://github.com/avinash201199/Free-programming-books/graphs/contributors)
[![Issues](https://img.shields.io/github/issues/avinash201199/Free-programming-books)](https://github.com/avinash201199/Free-programming-books/issues)
[![Stars](https://img.shields.io/github/stars/avinash201199/Free-programming-books)](https://github.com/avinash201199/Free-programming-books/stargazers)
[![Forks](https://img.shields.io/github/forks/avinash201199/Free-programming-books)](https://github.com/avinash201199/Free-programming-books/network/members)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

**A comprehensive collection of free programming and technical e-books for developers, students, and tech enthusiasts**

</div>

## 📖 About

Welcome to the Free Programming Books Repository! This is a community-driven collection of free educational resources designed to help anyone learn programming, advance their technical skills, or explore new technologies. Our mission is to democratize access to quality programming education materials for learners worldwide.

## ✨ Why This Repository?

- 🎯 **Career Development**: Master skills to showcase in your professional journey
- 🌍 **Open Access**: Free resources available to everyone, everywhere
- 🤝 **Community-Driven**: Built by developers, for developers
- 📈 **Continuous Growth**: Regularly updated with new contributions
- 💡 **Diverse Topics**: From basics to advanced programming concepts

## 📂 Repository Structure

Our repository is organized into the following categories:

| Category | Description | Topics Covered |
|----------|-------------|----------------|
| **Android Development** | Mobile app development for Android | Kotlin, Java for Android, Material Design |
| **Artificial Intelligence** | AI concepts and implementations | Neural Networks, Deep Learning, NLP, Computer Vision |
| **C Programming** | System programming with C | Fundamentals, Memory Management, Embedded Systems |
| **C++ Programming** | Object-oriented programming | STL, Modern C++, Game Development |
| **Cloud Computing** | Cloud platforms and services | AWS, Azure, GCP, Serverless, Kubernetes |
| **Computer Networking** | Network fundamentals and protocols | TCP/IP, HTTP/HTTPS, Network Security |
| **Cyber Security** | Information security | Ethical Hacking, Cryptography, Security Auditing |
| **Data Science** | Data analysis and visualization | Python/R for Data Science, Statistics, Big Data |
| **Data Structures & Algorithms** | DSA fundamentals | Sorting, Searching, Dynamic Programming |
| **Interview Preparation** | Technical interview resources | Coding Problems, System Design, Behavioral |
| **Java Programming** | Enterprise Java development | Core Java, Spring Boot, Microservices |
| **Machine Learning** | ML algorithms and applications | Supervised/Unsupervised Learning, Deep Learning |
| **Python Programming** | Python from basics to advanced | Django, Flask, Data Analysis, Automation |
| **Web Development** | Full-stack web development | HTML/CSS/JS, React, Node.js, Databases |
| **Novels & Others** | Non-technical and leisure reading | Tech Biographies, Soft Skills, Fiction |

## 🚀 Quick Start Guide

### For Learners

1. **Browse**: Navigate to your area of interest
2. **Download**: Click on any PDF to view or download
3. **Learn**: Start your learning journey
4. **Practice**: Apply what you learn in projects
5. **Share**: Help others by sharing this resource

### For Contributors

We welcome all contributions! See our [Contributing Guidelines](#-contributing-guidelines) below.

## 🤝 Contributing Guidelines

Contributions are what make the open-source community amazing. Any contributions you make are **greatly valued and appreciated**!



### ✅ Before You Contribute

Ensure your contribution meets these criteria:
- 📚 Add only legally free resources
- ⚠️ No pirated or copyrighted material
- 💻 Must be relevant to programming/tech
- 📑 PDF preferred, under 100MB
- 🌟 Content should add real value

### 📘 How to Add a Book

---

#### 1️⃣ Fork the Repository

# Fork via GitHub UI, then clone
`git clone https://github.com/YOUR_USERNAME/Free-programming-books.git
cd Free-programming-books`

---

#### 2️⃣ Create a Feature Branch

`git checkout -b add-book-category-name`

# Example: git checkout -b add-python-cookbook

---

#### 3️⃣ Add Your Book

- Navigate to the appropriate **category folder**
- Add your **PDF** with a clear, descriptive name  
- Use this naming convention: **`BookTitle_Author_Year.pdf`**
- **Example**: `CleanCode_RobertMartin_2008.pdf`

#### 4️⃣ Update the Code in src/data/books.ts

Inside, it usually looks like this:

`export const books = [
  {
    id: "python-1",
    title: "Learning Python",
    author: "Mark Lutz",
    category: "Python Programming",
    language: "Python",
    year: 2020,
    pages: 1600,
    level: "Advanced",
    description: "Comprehensive guide to Python programming.",
    downloadLink: "https://example.com/learning-python.pdf",
    tags: ["Python", "Reference", "Advanced"]
  }
]

export const categories = [
  "Web Development",
  "Machine Learning",
  "Python Programming",
  "Data Science"
]

export const languages = [
  "Python",
  "Java",
  "JavaScript",
  "C",
  "C++",
  "Kotlin",
  "HTML/CSS",
  "General"
]`

---

## 4️⃣ Add a New Book Entry

Scroll to the `books` array and add your new book following this format:

<CodeBlock language="json">
{`{
  "id": "python-6",
  "title": "Learning Python the Hard Way",
  "author": "Zed A. Shaw",
  "category": "Python Programming",
  "language": "Python",
  "pages": 320,
  "year": 2024,
  "level": "Beginner",
  "description": "Learn Python through practical exercises and examples.",
  "downloadLink": "https://example.com/python-hard-way.pdf",
  "tags": ["Python", "Hands-on", "Beginner"],
  "featured": false
}`}
</CodeBlock>

💡 **Tip:**  
- Use `"language"` to specify the **programming language** (e.g., `"Python"`, `"Java"`, `"JavaScript"`).  
- Keep the description concise (1–2 sentences).

---

## 🏷️ 5️⃣ If Category or Programming Language Doesn’t Exist

If your book belongs to a **new category** or uses a **programming language not yet listed**, add them inside the same file:

**Example:**

<CodeBlock language="ts">
{`export const categories = [
  "Web Development",
  "Machine Learning",
  "Python Programming",
  "AI Ethics" // newly added category
]

export const languages = [
  "Python",
  "Java",
  "JavaScript",
  "C",
  "C++",
  "Kotlin",
  "HTML/CSS",
  "Rust" // newly added programming language
]`}
</CodeBlock>

⚡ Make sure:
- The programming language name matches standard naming (`"Python"`, not `"python"`).
- There are no duplicates.

---

## 6️⃣ Validate Your Syntax

Before committing, ensure your JSON/TS file is valid:

<CodeBlock language="bash">
{`npm run lint
# or use an online JSON/TS validator`}
</CodeBlock>

---

#### 5️⃣ Commit with a Clear Message

<CodeBlock language="bash">
{`git add .
git commit -m "Add [Book Name] by [Author] to [Category] folder"
# Example:
# git commit -m "Add Clean Code by Robert Martin to Java folder"`}
</CodeBlock>

---

#### 6️⃣ Push and Create a Pull Request

<CodeBlock language="bash">
{`git push origin add-book-category-name`}
</CodeBlock>

Then go to **GitHub → Pull Requests → New Pull Request**  
and add a short description of your contribution ✨

---

✅ **Final Checklist**

| Task | Status |
|------|--------|
| Correct file naming (`BookTitle_Author_Year.pdf`) | ✅ |
| Updated `src/data/books.ts` properly | ✅ |
| Commit message is descriptive | ✅ |
| Book is free to distribute | ✅ |
| PR created with details | ✅ |

---


6. **Commit with Clear Message**
   ```bash
   git add .
   git commit -m "Add [Book Name] by [Author] to [Category] folder"
   # Example: git commit -m "Add Clean Code by Robert Martin to Java folder"
   ```

7. **Push and Create Pull Request**
   ```bash
   git push origin add-book-category-name
   ```
   Then create a Pull Request on GitHub with a description of your contribution.

### 🆕 Creating New Categories

Want to add a new category? Please:
1. Open an issue first for discussion
2. Ensure you have at least 3 books for the category
3. Include a README.md explaining the category
4. Follow the existing folder naming convention

### 🐛 Reporting Issues

Help us maintain quality by reporting:
- 📎 Corrupted or broken files
- ⚖️ Copyright violations
- 🔄 Duplicate books
- 📁 Miscategorized content
- 🔗 Dead links or missing files

[Report an Issue →](https://github.com/avinash201199/Free-programming-books/issues/new)

## 📋 Contribution Best Practices

- 🏆 Quality over Quantity: Submit only valuable books
- 🔍 Check Before Adding: Avoid duplicates
- ⚖️ Respect Copyright: Only share legal resources
- 🗂 Stay Organized: Use proper categories
- 📝 Descriptive Naming: BookTitle_Author_Year.pdf

🙌 **Thank you for helping us make programming knowledge free and accessible to all!**


## 🌟 Hall of Fame - Top Contributors

We appreciate everyone who helps build this knowledge base:

- [@avinash201199](https://github.com/avinash201199) - Repository Founder & Maintainer

[View All Contributors →](https://github.com/avinash201199/Free-programming-books/graphs/contributors)

## 📊 Repository Statistics

<div align="center">

| Metric | Count |
|--------|--------|
| 📚 Total Books | 100+ |
| 📁 Categories | 15 |
| 👥 Contributors | Growing Daily |
| ⭐ Stars | Increasing |
| 🍴 Forks | Active |

</div>

## 💬 Community & Support

### Get Help
- 📧 **Issues**: [GitHub Issues](https://github.com/avinash201199/Free-programming-books/issues)
- 💭 **Discussions**: [GitHub Discussions](https://github.com/avinash201199/Free-programming-books/discussions)
- 📱 **Instagram**: [@lets__code](https://www.instagram.com/lets__code/) - Follow for coding tips and updates

### Stay Updated
- ⭐ Star this repository to stay notified
- 👁️ Watch for new book additions
- 🔔 Follow [@avinash201199](https://github.com/avinash201199) for updates

## 📜 Legal Information

### License
This repository structure and organization is available under the MIT License. Individual books maintain their original licenses and copyrights.

### ⚖️ Copyright Disclaimer
- All books are believed to be freely distributable
- We respect intellectual property rights
- Books are either:
  - In public domain
  - Shared with explicit permission
  - Licensed for free distribution (Creative Commons, etc.)
  - Open-source educational materials

### DMCA Notice
If you believe any content violates your copyright, please immediately:
1. Open an issue with details
2. Contact the repository maintainer
3. We will remove the content within 24 hours of verification

## 🗺️ Roadmap & Future Plans

- [ ] Add search functionality via GitHub Pages
- [ ] Create learning paths for different technologies
- [ ] Add book ratings and reviews system
- [ ] Implement automated quality checks
- [ ] Create mobile-friendly web interface
- [ ] Add multi-language book support
- [ ] Build recommendation engine based on skill level
- [ ] Add video tutorial links for books

## 🎯 Learning Paths (Coming Soon)

### 🚀 Beginner Developer Path
1. Programming Fundamentals (C/Python)
2. Data Structures & Algorithms
3. Web Development Basics
4. Version Control with Git
5. First Project Ideas

### 💼 Full-Stack Developer Path
1. Frontend (HTML, CSS, JavaScript)
2. Backend (Node.js/Python/Java)
3. Databases (SQL & NoSQL)
4. DevOps Basics
5. Cloud Deployment

## 🙏 Acknowledgments

Special thanks to:
- 📖 All authors who make their knowledge freely available
- 👥 Every contributor who has shared resources
- ⭐ Everyone who has starred and shared this repository
- 🌍 The global programming community

## 📣 Spread the Word

Help others discover these free resources:
- ⭐ **Star** this repository
- 🔄 **Share** with your network
- 📝 **Write** about it in your blog
- 🐦 **Tweet** about it
- 💬 **Tell** your fellow developers

---

<div align="center">

### 🌟 Star this repository to help others find these free resources! 🌟

**Happy Learning & Happy Coding! 💻📚**

*Building a world where quality programming education is free for everyone*

<div align="center" markdown="1">

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)&#160;
[![License: CC BY 4.0](https://img.shields.io/github/license/EbookFoundation/free-programming-books)](https://creativecommons.org/licenses/by/4.0/)&#160;
[![Hacktoberfest 2025 stats](https://img.shields.io/github/hacktoberfest/2025/EbookFoundation/free-programming-books?label=Hacktoberfest+2025)](https://github.com/EbookFoundation/free-programming-books/pulls?q=is%3Apr+is%3Amerged+created%3A2025-10-01..2025-10-31)

</div>

Search the list at [https://ebookfoundation.github.io/free-programming-books-search/](https://ebookfoundation.github.io/free-programming-books-search/).

This page is available as an easy-to-read website. Access it by clicking [here](https://ebookfoundation.github.io/free-programming-books/).

<div align="center">
  <form action="https://ebookfoundation.github.io/free-programming-books-search">
    <input type="text" id="fpbSearch" name="search" required placeholder="Search Book or Author"/>
    <label for="submit"> </label>
    <input type="submit" id="submit" name="submit" value="Search" />
  </form>
</div>

## Intro

This list was originally a clone of [StackOverflow - List of Freely Available Programming Books](https://web.archive.org/web/20140606191453/http://stackoverflow.com/questions/194812/list-of-freely-available-programming-books/392926) with contributions from Karan Bhangui and George Stocker.

The list was moved to GitHub by Victor Felder for collaborative updating and maintenance. It has grown to become one of [GitHub's most popular repositories](https://octoverse.github.com/).

<div align="center" markdown="1">

[![GitHub repo forks](https://img.shields.io/github/forks/EbookFoundation/free-programming-books?style=flat&logo=github&logoColor=whitesmoke&label=Forks)](https://github.com/EbookFoundation/free-programming-books/network)&#160;
[![GitHub repo stars](https://img.shields.io/github/stars/EbookFoundation/free-programming-books?style=flat&logo=github&logoColor=whitesmoke&label=Stars)](https://github.com/EbookFoundation/free-programming-books/stargazers)&#160;
[![GitHub repo contributors](https://img.shields.io/github/contributors-anon/EbookFoundation/free-programming-books?style=flat&logo=github&logoColor=whitesmoke&label=Contributors)](https://github.com/EbookFoundation/free-programming-books/graphs/contributors)    
[![GitHub org sponsors](https://img.shields.io/github/sponsors/EbookFoundation?style=flat&logo=github&logoColor=whitesmoke&label=Sponsors)](https://github.com/sponsors/EbookFoundation)&#160;
[![GitHub repo watchers](https://img.shields.io/github/watchers/EbookFoundation/free-programming-books?style=flat&logo=github&logoColor=whitesmoke&label=Watchers)](https://github.com/EbookFoundation/free-programming-books/watchers)&#160;
[![GitHub repo size](https://img.shields.io/github/repo-size/EbookFoundation/free-programming-books?style=flat&logo=github&logoColor=whitesmoke&label=Repo%20Size)](https://github.com/EbookFoundation/free-programming-books/archive/refs/heads/main.zip)

</div>

The [Free Ebook Foundation](https://ebookfoundation.org) now administers the repo, a not-for-profit organization devoted to promoting the creation, distribution, archiving, and sustainability of free ebooks. [Donations](https://ebookfoundation.org/contributions.html) to the Free Ebook Foundation are tax-deductible in the US.

## How To Contribute

Please read [CONTRIBUTING](docs/CONTRIBUTING.md). If you're new to GitHub, [welcome](docs/HOWTO.md)! Remember to abide by our adapted from ![Contributor Covenant 1.3](https://img.shields.io/badge/Contributor%20Covenant-1.3-4baaaa.svg) [Code of Conduct](docs/CODE_OF_CONDUCT.md) too ([translations](#translations) also available).

Click on these badges to see how you might be able to help:

<div align="center" markdown="1">

[![GitHub repo Issues](https://img.shields.io/github/issues/EbookFoundation/free-programming-books?style=flat&logo=github&logoColor=red&label=Issues)](https://github.com/EbookFoundation/free-programming-books/issues)&#160;
[![GitHub repo Good Issues for newbies](https://img.shields.io/github/issues/EbookFoundation/free-programming-books/good%20first%20issue?style=flat&logo=github&logoColor=green&label=Good%20First%20issues)](https://github.com/EbookFoundation/free-programming-books/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22)&#160;
[![GitHub Help Wanted issues](https://img.shields.io/github/issues/EbookFoundation/free-programming-books/help%20wanted?style=flat&logo=github&logoColor=b545d1&label=%22Help%20Wanted%22%20issues)](https://github.com/EbookFoundation/free-programming-books/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22)    
[![GitHub repo PRs](https://img.shields.io/github/issues-pr/EbookFoundation/free-programming-books?style=flat&logo=github&logoColor=orange&label=PRs)](https://github.com/EbookFoundation/free-programming-books/pulls)&#160;
[![GitHub repo Merged PRs](https://img.shields.io/github/issues-search/EbookFoundation/free-programming-books?style=flat&logo=github&logoColor=green&label=Merged%20PRs&query=is%3Amerged)](https://github.com/EbookFoundation/free-programming-books/pulls?q=is%3Apr+is%3Amerged)&#160;
[![GitHub Help Wanted PRs](https://img.shields.io/github/issues-pr/EbookFoundation/free-programming-books/help%20wanted?style=flat&logo=github&logoColor=b545d1&label=%22Help%20Wanted%22%20PRs)](https://github.com/EbookFoundation/free-programming-books/pulls?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22)

</div>

## Resources

This project lists books and other resources grouped by genres:

### Books

[English, By Programming Language](books/free-programming-books-langs.md)  
[English, By Subject](books/free-programming-books-subjects.md)  

#### Other Languages

+ [Arabic / العربية](books/free-programming-books-ar.md)
+ [Bengali / বাংলা](books/free-programming-books-bn.md)
+ [Chinese / 中文](books/free-programming-books-zh.md)
+ [French / français](books/free-programming-books-fr.md)
+ [German / Deutsch](books/free-programming-books-de.md)
+ [Hindi / हिन्दी](books/free-programming-books-hi.md)
+ [Italian / italiano](books/free-programming-books-it.md)
+ [Japanese / 日本語](books/free-programming-books-ja.md)
+ [Korean / 한국어](books/free-programming-books-ko.md)
+ [Portuguese (Brazil)](books/free-programming-books-pt_BR.md)
+ [Russian / Русский язык](books/free-programming-books-ru.md)
+ [Spanish / español](books/free-programming-books-es.md)
+ [Urdu / اردو](books/free-programming-books-ur.md)
+ ... *[Many more languages](books/README.md#other-languages)* ...

### License

Each file included in this repository is licensed under the [CC BY License](LICENSE).
<br>

Made with ❤️ by [Avinash](https://github.com/avinash201199) and [Contributors](https://github.com/avinash201199/Free-programming-books/graphs/contributors)

</div>
