# Moodify
Moodify is a program that recommends music based on the user’s current mood. It maps each mood to a specific set of music genres, then retrieves tracks that match those genres. Users input their mood, and the program generates a playlist of songs aligned with that emotional state. It uses a mood analyzer to select genres and connects to Spotify to search for relevant tracks. The recommendations are displayed with song title, artist, and a link to listen.

**Features:**

Mood-Based Genre Selection: Matches user-inputted moods to curated music genres.

Real-Time Track Recommendations: Retrieves actual songs based on selected genres.

Interactive Input: Users enter their current mood to generate a personalized playlist.

**Project Structure:**

moodify.ipynb
Contains the main program interface where users run the notebook, input moods, and receive music recommendations.

• MoodAnalyzer    
  Maps user moods to a predefined list of music genres for playlist generation.

• SpotifyConnect   
  Handles retrieving songs by genre using Spotify’s search functionality.

• PlaylistRecommender   
  Combines the MoodAnalyzer and SpotifyConnect to build playlists based on mood input.

.gitignore   
Excludes environment files, virtual environments, and cache directories from version control.
