# Video Folder Generator 🎬📁

A simple, fast, and dependency-free web application designed to help video editors, filmmakers, and content creators kickstart their projects with a clean, standardized folder structure. 

Instead of manually creating folders for every new video project, simply type the project name, and this tool will instantly generate a `.zip` file containing a professional post-production directory tree, ready to be extracted and used.

## ✨ Features

* **Zero Server Setup:** Everything runs securely in your browser using JavaScript and the [JSZip](https://stuk.github.io/jszip/) library.
* **Smart Naming Convention:** Automatically formats your project name into a clean, URL-safe `kebab-case` string (e.g., "My Awesome Project!" becomes `my-awesome-project`), stripping out accents and special characters.
* **Automatic Date Prefix:** Prepends the current date (`YYYYMMDD`) to the root folder for easy chronological sorting.
* **Industry-Standard Structure:** Comes pre-configured with a battle-tested folder hierarchy for footage, audio, graphics, VFX, project files (Premiere, DaVinci, After Effects), and exports.

## 📂 The Folder Structure

When you extract the downloaded `.zip` file, you will get the following structure:

```text
YYYYMMDD-your-project-name/
├── 01-project-files/
│   ├── after-effects/
│   ├── davinci-resolve/
│   └── premiere/
├── 02-footage/
│   ├── b-roll/
│   └── day-01/
│       ├── cam-a/
│       └── cam-b/
├── 03-audio/
│   ├── dialogue/
│   ├── gravador-externo/
│   ├── music/
│   ├── sfx/
│   └── voice-over/
├── 04-graphics/
│   ├── assets/
│   │   ├── emojis/
│   │   └── icons/
│   ├── logos/
│   ├── stills/
│   └── typography/
├── 05-vfx/
├── 06-exports/
│   ├── delivery-masters/
│   │   ├── 16x9/
│   │   └── 9x16/
│   └── wip/
└── 07-documents/
    ├── contracts/
    └── scripts-briefing/
