# Movie-Insight-Assistant-Using-Python

## Project Description
Movie Insight Assistant is a Python-based interactive application designed to help users explore movies effortlessly. It combines API-based data retrieval and web scraping techniques to deliver detailed movie information and intelligent genre-based recommendations through a clean, chat-style interface.

The project focuses on enhancing user experience by simplifying how movie data is accessed, displayed, and navigated. Instead of browsing multiple websites, users can obtain comprehensive movie insights from a single application window.

---

## Key Objectives
- Provide instant access to detailed movie information
- Enable personalized movie discovery through genre selection
- Demonstrate API integration and web scraping in Python
- Build an interactive and responsive GUI using Tkinter
- Manage dynamic content and user interaction efficiently

---

## Features
- Search movies by title
- View movie details such as:
  - Release year
  - Genres
  - Director
  - Cast
  - Plot summary
  - IMDb rating
  - Language
- Get movie recommendations based on selected genres
- Chat-style interface with auto scrolling
- Clear chat history option
- Full-screen and windowed mode toggle
- Keyboard support (Enter key to send)

### Genre-Based Recommendations
- Genre buttons allow users to explore curated movie lists
- Uses TMDb API to fetch real-time recommendations
- Displays multiple suggestions in a readable format

### Interactive Chat Interface
- Messages appear in a conversational format
- Automatically scrolls as new results are added
- Maintains a clean and organized chat history

### Utility Controls
- Clear History button to reset the interface
- Full-Screen mode toggle for enhanced viewing
- Keyboard support (Enter key submission)

---

## Technical Stack
- **Programming Language:** Python
- **GUI Framework:** Tkinter
- **APIs Used:**
  - IMDb API (movie details)
  - TMDb API (genre-based recommendations)
- **Libraries:**
  - requests
  - imdbpy
- **Concepts Implemented:**
  - API handling
  - Web scraping
  - Event-driven programming
  - GUI layout management
  - Dynamic content rendering

---

## System Architecture
### Input
- Genre selection via buttons
- Movie title entered by user
- Button clicks and keyboard events

### Processing
- API request generation based on user input
- JSON response parsing
- Data formatting and filtering
- Chat history management
- Window state control for full-screen mode

### Output
- Movie lists based on selected genres
- Detailed movie information display
- Updated UI states and messages

---

## Project File
```text
Python web scraping project 24BEC1419 V.G.MANASA (1).py
