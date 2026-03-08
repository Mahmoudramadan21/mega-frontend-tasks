# 🚀 Week 08 – Pattern Matching & Regular Expressions (RegEx)

**MEGA TEAM Frontend Track – Mid Level 2026**

### 🎯 Goal

Build a **Smart Form Validator & Text Parser** relying entirely on Regular Expressions (RegEx). You will validate complex user inputs, search for specific data inside large texts, and format strings without relying on messy `if-else` chains or basic string methods.
Use **only** JavaScript concepts from Lessons #134 to #146.

### 📁 Project Name

`regex-pattern-master`

### 🛠️ What You Need to Build

**1. Secure Registration Form (Form Validation):**

- Build a form with inputs for Username, Email, Egyptian Phone Number, and Password.
- Validate inputs in real-time as the user types (show a green check for valid, red cross for invalid) using RegEx patterns.

**2. Data Extractor (Match & Extract):**

- A text area where the user can paste a large block of text.
- Extract all **URLs** or **Hashtags (#)** from the text and display them in a neat list below the text area.

**3. Text Sanitizer (Replace & Format):**

- Use RegEx to clean up a messy string. For example, replace multiple consecutive spaces with a single space, or censor specific forbidden words (e.g., turning "spam" into "\*\*\*\*").

---

### 🚀 Required JavaScript Concepts – Use each at least once

| Lesson(s)    | Concept                                  | Simple Place to Use It                                                                                                 |
| :----------- | :--------------------------------------- | :--------------------------------------------------------------------------------------------------------------------- |
| **#134–135** | **RegEx Intro & Modifiers**              | Use the global `g` and case-insensitive `i` modifiers to find all instances of a word regardless of its case.          |
| **#136–137** | **Ranges `[]`**                          | Validate that a username only contains lowercase letters and numbers `[a-z0-9]`.                                       |
| **#138–139** | **Character Classes (`\w`, `\d`, `\s`)** | Quickly check if an input contains any digits `\d` or remove all extra whitespaces `\s`.                               |
| **#140–142** | **Quantifiers (`+`, `*`, `?`, `{}`)**    | Ensure a phone number is exactly 11 digits long using `{11}`, or require at least 8 characters for a password.         |
| **#143**     | **Replace With Pattern**                 | **[Mandatory]** Clean up a string by replacing all special characters with a hyphen using `.replace(/pattern/g, '-')`. |
| **#144–146** | **`.test()` & `.match()`**               | Use `.test()` to return true/false for the form inputs, and `.match()` to extract an array of hashtags from a text.    |

---

### ✅ Minimum Requirements Checklist

- [ ] **Username Validation:** Must start with a letter, contain no special characters, and be between 5 to 15 characters long.
- [ ] **Phone Number Validation:** Must match the Egyptian format (starts with 010, 011, 012, or 015 followed by exactly 8 digits).
- [ ] **Email Validation:** Must accept standard email formats (e.g., `user@example.com`).
- [ ] **Real-time UI Feedback:** Use the `.test()` method on the `input` or `keyup` event to toggle validation classes (valid/invalid) on the form fields.
- [ ] **Hashtag Extractor:** Use `.match()` to find any word starting with `#` in a provided text and map them into an HTML `<ul>` list.
- [ ] **String Cleanup:** Create a function that takes a string, removes all extra spaces, and trims it using `.replace()` and character classes.

---

### 📂 Folder Structure

```text
regex-pattern-master/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── validation.js      (All your RegEx patterns and logic go here)
└── README.md
```
