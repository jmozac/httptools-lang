# 🌍 HTTP Tools Translations

Welcome to the official translation repository for **HTTP Tools**.

This repository contains language files used by the **HTTP Tools** application.  
We welcome contributors from around the world who would like to help translate HTTP Tools into their native languages.

Thank you for helping make HTTP Tools accessible to more users worldwide.

---

## 📖 About HTTP Tools

**HTTP Tools** is a utility application designed to help developers and users work with HTTP requests, APIs, and web services more easily.

This repository is dedicated only to application translations.

The application source code is maintained separately.

---

## 🚀 How to Contribute

Anyone can help improve HTTP Tools translations.

### Contribution steps:

1. Fork this repository.
2. Select or create your language file.
3. Translate the text while keeping the original meaning.
4. Commit your changes.
5. Submit a Pull Request.
6. Wait for review and approval.

---

## 📂 Repository Structure

Translation files are stored in JSON format.

Example:

```text
lang/
├── en.json        # English (source language)
├── id.json        # Indonesian
├── fr.json        # French
├── de.json        # German
├── es.json        # Spanish
├── ja.json        # Japanese
└── ...
```

---

## 📝 Translation Rules

Please follow these guidelines when translating:

- Keep the original meaning of the text.
- Use natural expressions in your language.
- Do not translate technical terms unless commonly translated.
- Keep placeholders unchanged.

Examples:

```text
%s
%d
{name}
{count}
```

- Do not modify:
  - URLs
  - File paths
  - HTML tags
  - Code snippets
  - JSON keys

Example:

```json
{
    "button_save": "Save"
}
```

Only translate the value:

```json
{
    "button_save": "Simpan"
}
```

Do not change:

```json
{
    "tombol_simpan": "Simpan"
}
```

---

## 🌐 Supported Languages

| Code | Language | Status |
|------|----------|--------|
| en | English | ✅ Complete |
| id | Indonesian | ✅ Complete |
| fr | French | 🚧 In Progress |
| de | German | 🚧 In Progress |
| es | Spanish | 🚧 In Progress |
| ja | Japanese | 🚧 In Progress |
| zh | Chinese | 🚧 In Progress |

---

## ➕ Adding a New Language

To add a new language:

1. Copy the English language file:

```bash
cp lang/en.json lang/your-language-code.json
```

2. Translate all text values.
3. Submit a Pull Request.

Language codes should follow standard ISO language codes.

Examples:

| Language | Code |
|----------|------|
| English | en |
| Indonesian | id |
| French | fr |
| German | de |
| Spanish | es |
| Japanese | ja |

---

## 🐞 Reporting Problems

If you find:

- Incorrect translations
- Missing translations
- Typographical errors
- Language formatting issues

Please open an Issue or submit a Pull Request.

---

## 🤝 Contributors

Thank you to everyone who contributes translations and helps improve HTTP Tools.

Every contribution makes the application better for users around the world.

---

## 📄 License

Translation files in this repository are provided for use with HTTP Tools.

See the repository license for more information.
