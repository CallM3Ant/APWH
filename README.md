# 📚 Study Cards - Setup (Ultra Simple)

## ✅ That's it! No setup needed!

Just:
1. **Create folders** - `Resources/Math/Unit1`, `Resources/Science`, etc.
2. **Add `question.json`** to each folder
3. **Edit `folders.json`** - List your folder paths
4. **Open `index.html`** - Done!

---

## 📝 Example: Create Questions

**Folder structure:**
```
STUDY/
├── index.html
├── folders.json
└── Resources/
    ├── Math/
    │   ├── Unit1/question.json
    │   └── Unit2/question.json
    └── Science/question.json
```

**Resources/Math/Unit1/question.json:**
```json
{
  "questions": [
    {
      "text": "What is 2 + 2?",
      "type": "single",
      "correct": ["4"],
      "incorrect": ["3", "5", "6"]
    },
    {
      "text": "Solve: x + 5 = 12",
      "type": "single",
      "correct": ["x = 7"],
      "incorrect": ["x = 5", "x = 17"]
    }
  ]
}
```

**folders.json:**
```json
{
  "folders": [
    "Resources/Math/Unit1",
    "Resources/Math/Unit2",
    "Resources/Science"
  ]
}
```

---

## 🎯 Workflow

### When you add a new folder:
1. Create the folder
2. Create `question.json` inside
3. Add folder path to `folders.json`
4. Refresh `index.html` ✅

### When you add questions:
Just edit `question.json` and refresh! ✅

---

## 📖 Question Format

```json
{
  "questions": [
    {
      "text": "Question text here?",
      "type": "single",
      "correct": ["Answer"],
      "incorrect": ["Wrong1", "Wrong2", "Wrong3"]
    },
    {
      "text": "Pick all correct answers",
      "type": "multiple",
      "correct": ["Right1", "Right2"],
      "incorrect": ["Wrong1", "Wrong2"]
    }
  ]
}
```

- **type**: `"single"` (one answer) or `"multiple"` (many answers)
- **correct**: Array of correct answers
- **incorrect**: Array of wrong answers

---

## 🔥 That's it!

No generators. No scripts. Just:
1. Folders
2. JSON files
3. Edit `folders.json` when you add folders
4. Refresh browser

**Done!** 🚀