# OtakuOrganizer
Anime Episode Tracker 🐾📺

A simple Python CLI tool to track episodes of ongoing anime seasons. Keep track of what you’ve watched, mark new episodes, and stay on top of the current anime season!

Features

Track anime series for the current season.

Record total episodes and watched episodes.

Mark episodes as watched one by one.

Delete anime from your list when finished.

Persistent storage using JSON (data is saved between sessions).

Installation

Clone the repository:

git clone https://github.com/yourusername/anime-episode-tracker.git
cd anime-episode-tracker


(Optional) Create a virtual environment:

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate      # Windows


Install dependencies (if any):

pip install -r requirements.txt


Currently, this project only uses Python’s standard library, so no extra packages are required.

Usage

Run the tracker:

python anime_tracker.py


You will see a menu with options:

List anime – View your tracked anime and progress.

Add anime – Add a new anime with season and total episodes.

Mark episode watched – Increment the watched count for an anime.

Delete anime – Remove an anime from your list.

Exit – Quit the tracker.

Example
--- Anime Episode Tracker ---
1. List anime
2. Add anime
3. Mark episode watched
4. Delete anime
5. Exit
Choose an option: 2
Anime title: Jujutsu Kaisen
Season (e.g., Fall 2025): Fall 2025
Total episodes this season: 24
Added Jujutsu Kaisen!

Future Improvements

GUI version using Tkinter or Streamlit.

API integration to fetch current season anime automatically.

Notifications or reminders for new episodes.

Sorting/filtering options by season, status, or priority.

Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

License

This project is MIT Licensed.
