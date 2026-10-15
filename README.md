# Lab 4: XML and JSON

This repository contains the two required Fetch API pages:

- `index.html`: lab entry page
- `xml.html`: parses `book.xml` with `DOMParser` and displays title, author, and price
- `json.html`: parses `userProfiles.json` and displays all required profile fields

## Run locally

Because browsers block some local fetch calls from `file://`, serve the folder:

```powershell
python -m http.server 8000
```

Then open <http://localhost:8000>.

## Publish with GitHub Pages

1. Create a GitHub repository and upload all files in this folder.
2. Go to **Settings > Pages**.
3. Under **Source**, choose **Deploy from a branch**.
4. Choose the default branch (often `main`) and `/ (root)`, then save.
5. Wait until GitHub shows the Pages URL, then submit that URL in your lab report.
