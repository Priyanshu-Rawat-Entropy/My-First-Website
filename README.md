## Architecture Overview

The project follows a simple static website architecture. HTML files are responsible for the structure and content, while the css directory handles presentation and styling. Multimedia and visual resources are separated into dedicated folders, making the project easier to organize and maintain.

                           ┌──────────────────────┐
                           │      index.html      │
                           │       Home Page      │
                           └──────────┬───────────┘
                                      │
                    ┌─────────────────┼─────────────────┐
                    │                 │                 │
                    │                 │                 │
                    ▼                 ▼                 ▼
          ┌────────────────┐  ┌────────────────┐  ┌─────────────────┐
          │ fav_song.html  │  │   form.html    │  │ External Links  │
          │ Favorite Song  │  │     Form       │  │ YouTube / Mail  │
          └───────┬────────┘  └────────────────┘  └─────────────────┘
                  │
                  │
                  │ Home link
                  │
                  ▼
          ┌────────────────┐
          │   index.html   │
          │    Home Page   │
          └────────────────┘


          fav_song.html
               │
       ┌───────┼───────────┐
       │       │           │
       ▼       ▼           ▼
    index    Joji       YouTube
     .html   Website      Videos


## File Architecture

```text
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
```
## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Priyanshu-Rawat-Entropy/My-First-Website.git
```

### 2. Open the Project

```bash
cd My-First-Website
```

### 3. Run the Website

Since this is a static **HTML & CSS** website, no additional packages are required.

Open `index.html` directly in your browser.

You can also use **VS Code with Live Server** to run the website locally.
