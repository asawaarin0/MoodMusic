# MoodMusic

-Built as a hackathon project with a group of other Purdue University Students

MoodMusic is a Python program that recommends songs to a user based on their previous listening history and their current mood. To detect the user's mood, 
a facial recognition Python framework called deepface is used. This framework classifies a user's current emotion into 7 different categories: angry, happy, sad, 
disgust, fear, suprise, and neutral. To get song recommendations based on the the current mood and listening history, the Spotify API is used. The Spotipy python library
is used to interface with the Spotify API using python. 
