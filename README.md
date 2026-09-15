# My First Website 🌐

My first website, created while learning HTML and CSS.

## What is this?

This is my personal HTML & CSS playground.
I'm using it to experiment with web design and learn
the fundamentals of building websites.

## What I'm learning

- HTML
- CSS
- Flexbox
- CSS Grid
- Responsive Design

## Pages

- Home
- About
- Favorite Song
- Contact

## Goal

Keep improving this website as I learn more about web development.

## 📁 File Architecture

My-First-Website/
│
├── 📄 index.html
│   └── Main/home page of the website.
│       Contains the primary structure, content, navigation,
│       and links to other pages.
│
├── 📄 form.html
│   └── Form page of the website.
│       Contains the HTML structure for collecting
│       user input through forms.
│
├── 📄 fav_song.html
│   └── Favorite song/music page.
│       Contains the page structure and content
│       related to the favorite song section.
│
├── 📁 css/
│   └── Contains all CSS files used to style the website.
│       Handles layout, colors, fonts, spacing,
│       animations, responsiveness, and overall appearance.
│
├── 📁 fonts/
│   └── Contains custom font files used throughout
│       the website to provide the desired typography.
│
├── 📁 images/
│   └── Contains image assets used by the website,
│       including backgrounds, illustrations,
│       icons, and other visual elements.
│
├── 📁 music/
│   └── Contains audio/music files used by the website.
│       These files are used for the music-related
│       sections and pages.
│
└── 📁 video/
    └── Contains video files used by the website.
        These files provide multimedia/video content
        for the website.

## 🔗 File Relationships

* index.html → Main entry point of the website.
* form.html → Provides the form-related webpage.
* fav_song.html → Provides the favorite-song/music webpage.
* css/ → Provides styling for the HTML pages.
* images/ → Supplies visual assets referenced by the HTML/CSS files.
* fonts/ → Supplies custom fonts referenced by the website.
* music/ → Supplies audio files used by the website.
* video/ → Supplies video files used by the website.

## 🏗️ Architecture Overview

The project follows a simple static website architecture. HTML files are responsible for the structure and content, while the css directory handles presentation and styling. Multimedia and visual resources are separated into dedicated folders, making the project easier to organize and maintain.

                    ┌─────────────────┐
                    │   index.html    │
                    │   Main Page     │
                    └────────┬────────┘
                             │
              ┌──────────────┼──────────────┐
              │              │              │
              ▼              ▼              ▼
       ┌────────────┐ ┌────────────┐ ┌──────────────┐
       │ form.html  │ │fav_song.html │    css/      │
       │   Forms    │ │   Music    │ │   Styling    │
       └────────────┘ └────────────┘ └──────────────┘
                             │
                             ▼
                  ┌─────────────────────┐
                  │   Media Assets      │
                  ├─────────────────────┤
                  │ images/             │
                  │ fonts/              │
                  │ music/              │
                  │ video/              │
                  └─────────────────────┘