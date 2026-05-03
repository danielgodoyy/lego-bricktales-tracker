# LEGO Bricktales - 100% Completion Tracker 

A lightweight, web-based progress tracker designed for achievement hunters looking to reach 100% completion in **LEGO Bricktales**. 

Instead of guessing which collectibles you missed or manually checking every biome, this tool reads your local save file and instantly shows you exactly what you are missing (chests, animals, ghost shop items, etc.) in a clean, visual dashboard.

## How to Use

You **do not** need to download this repository or install any software. The tracker runs entirely in your browser!

1. **Access the Tracker:** Go to the live website here: `[link]`
2. **Locate your Save File:** On your Windows PC, press `Win + R`, paste the following path, and hit Enter:
   `path`
3. **Drag and Drop:** Find your save file (usually a `.dat` or `savegame` file) and drag it directly into the designated area on the website.
4. **Track your Progress:** The dashboard will instantly update, highlighting the biomes and specific collectibles you still need to find.

> **Privacy Note:** Your save file is processed entirely locally on your device using your browser's File API. No data is uploaded to any server or stored in any database.

## How it was Made

This project was built from scratch as a purely front-end solution:
* **Tech Stack:** HTML, CSS, and Vanilla JavaScript.
* **Architecture:** The logic revolves around a custom Save Parser that reads the binary/text structure of the `.dat` file directly in the browser.
* **Development Workflow:** This tool was architected and developed with the assistance of AI tools (Gemini for project architecture and Claude Code / local LLMs for code generation and file parsing).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
