# CE341 Repository Structure

This repository contains materials for CE341 - Transportation Engineering at KFUPM.

## 📁 Folder Structure

```
ce341/
├── 📄 index.html                    # Main landing page
├── 📄 syllabus.html                 # Course syllabus (HTML version)
├── 📁 chapters/                     # Chapter HTML files (website)
│   ├── chapter1.html
│   ├── chapter2.html
│   ├── chapter3.html
│   ├── chapter4.html
│   ├── chapter5.html
│   └── chapter6.html
├── 📁 content/                      # Offline-readable content (Markdown)
│   ├── syllabus.md
│   ├── chapter1.md
│   ├── chapter2.md
│   ├── chapter3.md
│   ├── chapter4.md
│   ├── chapter5.md
│   └── chapter6.md
├── 📁 quizzes/                      # All quiz-related files
│   ├── index.html                   # Quiz landing page (was quizzes.html)
│   └── quiz1-ch1-ch2.html          # Quiz 1 (was quiz1_ch1_ch2.html)
├── 📁 quizzes-content/              # Quiz questions in readable format
│   └── quiz1-ch1-ch2.md
└── 📁 assets/                       # CSS, images, etc.
    └── css/
        └── styles.css
```

## 🗑️ Removed Files

- `syllabus.txt` - Duplicated content (kept HTML version, added Markdown)

## 📝 Notes

- All HTML files use consistent external CSS (no inline styles)
- Markdown versions in `/content/` are for offline reading
- Quiz content extracted to `/quizzes-content/` for easy reference
