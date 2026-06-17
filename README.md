Galactic Archive System

A retro-inspired terminal-style Star Wars archive built with HTML, CSS, and JavaScript. Browse the complete Star Wars timeline in either chronological order or release order through an immersive command prompt interface.

Features
Retro Terminal Interface
Classic DOS/Command Prompt aesthetic
CRT-inspired glow effects
Animated boot sequence
Custom terminal styling and keyboard shortcuts
Star Wars Timeline Database
Movies
TV Series
Animated Series
Documentaries
Specials
Vintage Collection
Mini-Series
Shorts
Advanced Search

Search using free text or advanced operators:

mandalorian

type:movie

type:series year:2022

chrono:1-10

type:doc
Sorting Modes
Chronological Order – View content according to Star Wars timeline events.
Release Order – View content by original release date.
Watchlist System
Save favorite entries
Persistent storage using LocalStorage
Quick visual indicators for saved content
Keyboard Shortcuts
Key	Action
/	Focus search
Ctrl + F	Focus search
?	Show help
Esc	Clear search
W	Add hovered item to watchlist
Technologies Used
HTML5
CSS3
JavaScript (Vanilla)
Tailwind CSS
LocalStorage API
Project Structure
project/
│
├── index.html
└── README.md

All functionality is contained in a single HTML file including:

UI rendering
Search engine
Timeline database
Watchlist management
Keyboard navigation
Search Operators
Filter by Type
type:movie
type:series
type:doc
type:anim
type:spec
type:short
Filter by Year
year:2024
year:2019
Filter by Timeline Position
chrono:1
chrono:1-5
chrono:10-20
Combined Filters
type:series year:2022

type:movie chrono:15-25
Watchlist

Hover over any archive entry and press:

W

The selected item will be saved to your personal watchlist.

Watchlist data is stored locally in your browser:

localStorage["galactic_watchlist"]
Installation
Option 1: Open Directly

Download the project and open:

index.html

in any modern browser.

Option 2: Local Server
git clone https://github.com/yourusername/galactic-archive.git

cd galactic-archive

Then run:

python -m http.server

Visit:

http://localhost:8000
Screenshots
Boot Sequence
[████████████████████] 100%
ACCESS GRANTED
Archive Database
YEAR  TYPE   CHRONO FILE_NAME
──────────────────────────────────────────────
1977  MOVIE  17     STAR WARS: A NEW HOPE
1980  MOVIE  18     THE EMPIRE STRIKES BACK
1983  MOVIE  19     RETURN OF THE JEDI
Future Improvements
Export watchlists
Dark/Green terminal themes
Expanded Star Wars metadata
Episode-level filtering
Search suggestions
Mobile TUI enhancements
Cloud synchronization
Disclaimer

Star Wars and all related properties are trademarks of Lucasfilm Ltd. and The Walt Disney Company.

This project is a fan-made archive and is intended for educational and entertainment purposes only.

License

MIT License

Feel free to use, modify, and distribute this project. 🚀

May the Force be with you. ⭐
