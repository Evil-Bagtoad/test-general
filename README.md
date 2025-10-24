# My Notes Repository

This repository is used to store my personal notes, ideas, and documentation.

## 📁 Structure

- `notes/` - Main notes directory
  - `daily/` - Daily notes and journal entries
  - `projects/` - Project-specific notes
  - `ideas/` - Ideas and brainstorming
  - `learning/` - Learning notes and resources
  - `meeting-notes/` - Meeting notes and action items
  - `reference/` - Reference materials and documentation

## 📝 Creating Notes

You can use the `note-template.md` file as a starting point for new notes.

Each note should include:
- Clear title
- Date created
- Tags for easy searching
- Content organized with headers

## 🏷️ Tagging Convention

Use tags to help organize and find notes:
- `#todo` - Action items
- `#idea` - Ideas and brainstorming
- `#important` - Important information
- `#review` - Items to review later
- `#project-name` - Project-specific tags

## 🔍 Searching Notes

Use GitHub's search functionality or `grep` to search across all notes:

```bash
# Search for a specific term
grep -r "search term" notes/

# Search for a tag
grep -r "#tag" notes/
```

## 📅 Daily Notes

Daily notes follow the format: `YYYY-MM-DD.md` in the `notes/daily/` directory.