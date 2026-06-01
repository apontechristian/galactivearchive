# Galactic Archive

A retro-inspired command-line archive for exploring the Star Wars universe through an immersive terminal interface. Browse movies, series, documentaries, animated content, specials, and vintage releases in either release order or chronological timeline order.

Designed to feel like a classic DOS-era mainframe, Galactic Archive combines ASCII aesthetics, CRT-inspired visuals, command-prompt loading sequences, and searchable archive records into a single standalone web application.

## Features

* Retro DOS / Command Prompt inspired interface
* Animated boot-up sequence with terminal logs
* ASCII art welcome screen
* Release Order and Chronological Order viewing modes
* Instant search filtering
* Responsive design for desktop and mobile
* CRT-style glow effects and terminal aesthetics
* Complete Star Wars archive database
* Zero dependencies beyond Tailwind CDN
* Single-file deployment

## Archive Categories

The archive includes:

* Movies
* Live-Action Series
* Animated Series
* Documentaries
* Specials
* Mini-Series
* Shorts
* Vintage Collection

## Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla)
* Tailwind CSS (CDN)

## How It Works

### Welcome Screen

Users are greeted with a retro ASCII splash screen and archive introduction.

### System Boot Sequence

Selecting **Initiate Command Sequence** launches an 8-second simulated terminal startup sequence featuring:

* Holonet connections
* Archive mounting
* Imperial database decryption
* Jedi archive synchronization
* Core system initialization

### Archive Interface

Once initialized, users can:

* Search archive entries by title
* Filter by year
* Filter by content type
* Sort by Release Order
* Sort by Chronological Order

Results are displayed in a terminal-style directory listing format.

## Project Structure

```text
index.html
│
├── HTML Layout
├── Custom DOS Styling
├── Star Wars Archive Database
├── Boot Loader System
├── Search & Filter Engine
└── Sorting Functions
```

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/galactic-archive.git
```

Navigate to the project:

```bash
cd galactic-archive
```

Open the file in your browser:

```bash
index.html
```

No build tools or installation steps are required.

## Customization

The archive database is stored inside the JavaScript `data` array.

Example:

```javascript
{
  title: "Star Wars: A New Hope (Episode IV)",
  year: "1977",
  type: "Movie",
  release: 1,
  chrono: 17
}
```

You can:

* Add new entries
* Update chronological positions
* Create additional categories
* Replace the database entirely for another franchise

## Future Enhancements

* Audio effects and startup sounds
* Individual record detail pages
* Timeline visualization
* Expanded filtering options
* Theme selection
* Keyboard command support
* Local storage preferences
* API-powered content updates

## Screenshots

Add screenshots here after deployment.

```text
/assets/screenshot-welcome.png
/assets/screenshot-loader.png
/assets/screenshot-archive.png
```

## Disclaimer

Star Wars and all related properties are trademarks of Lucasfilm Ltd. and The Walt Disney Company.

This project is a fan-made archive created for educational and entertainment purposes only.


