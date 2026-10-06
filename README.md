# 4605 HUB

GitHub Pages dashboard + public GitHub file storage for the 4605 HUB ESP32 project.

## Structure

- `index.html` - dashboard
- `files.json` - local file index
- `personalization.txt` - AI personalization
- `Exam/` - local study files

## Dashboard

GitHub Pages:
https://gowthamc-0712.github.io/4605-HUB-GITHUB/

The dashboard uses a fine-grained GitHub token entered by the user. The token is kept in browser session storage and is not hard-coded into this repository.

## ESP32

The ESP32 will later read public raw GitHub files directly and call Gemini directly. The Gemini API key belongs only in the ESP32 firmware and must never be committed here.
