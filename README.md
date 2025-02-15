# spotify_streaming_history

# Overview

This dataset captures user interactions on a music streaming platform, including track plays, skips, shuffle behavior, session details, and listening habits. The dataset is structured to analyze user engagement, music preferences, and behavioral patterns based on various attributes such as time of day, platform usage, and playback actions.

# Dataset Contents

The dataset contains multiple columns representing different aspects of a user's streaming activity. Below is a detailed description of each column:

# Track Information

track_name – The name of the song played.

artist_name – The artist who performed the track.

album_name – The album to which the track belongs.

track_duration (ms_played) – The duration (in milliseconds) the track was played.

track_duration_min – The duration of the track converted to minutes.

# User Behavior & Playback Actions

skipped – Indicates whether the track was skipped (1 = Skipped, 0 = Not Skipped).

shuffle – Indicates whether the track was played in shuffle mode (1 = Shuffled, 0 = Not Shuffled).

reason_start – The reason why the track started playing (e.g., user action, autoplay, playlist).

reason_end – The reason why the track stopped playing (e.g., skipped, track completed).

# Session & Platform Information

session_id – Unique identifier for each listening session.

platform – The device or application used to stream the music (e.g., mobile, desktop, web).

# Temporal Attributes

date – The date when the track was played.

day_of_week – The weekday on which the track was played (e.g., Monday, Tuesday).

month – The month in which the track was played (e.g., January, February).

hour – The hour of the day when the track was played.

# Objectives & Insights Derived

This dataset allows for the exploration of various insights into user listening habits and engagement patterns. Below are some key areas of analysis:

1. User Listening Patterns
   
Analysis of peak listening hours to identify when users are most active.

Understanding weekday vs. weekend listening trends to detect differences in behavior.

Morning vs. evening listening preferences to see how time of day affects music consumption.


2. Skipping Behavior
   
Identifying tracks, artists, and albums with high skip rates.

Analyzing skip rates by track duration to determine if users skip longer songs more often.

Investigating skip rates by time of day to see if skipping behavior changes over time.

3. Shuffle Mode & Playback Patterns
   
Analyzing the frequency of shuffle mode usage across different sessions.

Identifying which tracks are most frequently played in shuffle mode.

Investigating the correlation between shuffle mode and skipping behavior.

4.  Platform Preference
   
Understanding which platforms (mobile, desktop, web) users prefer for streaming.

Analyzing differences in skipping and shuffle behavior across platforms.

5. Artist & Album Popularity
   
Identifying the most played artists and albums.

Analyzing listener loyalty by tracking repeat sessions for specific artists.

Determining which artists have the highest engagement rates.

6. Session Analysis
   
Determining average session duration based on total time played per session.

Identifying how many tracks users listen to per session.

Analyzing session start and end behavior to see how long users engage with the platform.

7. Rarely Played & Never Skipped Songs
   
Identifying tracks that were played only once to analyze less popular songs.

Finding tracks that were never skipped, indicating high engagement.

# Potential Applications

This dataset can be leveraged in various ways, including:

User Engagement Analysis – Understanding user preferences and improving recommendation algorithms.
 
Music Marketing Insights – Helping artists and record labels tailor their marketing strategies.

Product Optimization – Enhancing the music streaming experience by adjusting autoplay, shuffle, and recommendation features.

Personalized Playlists – Identifying listening patterns to create better-curated playlists for users.

