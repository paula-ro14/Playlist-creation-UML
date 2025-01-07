# Playlist-creation-UML
A project to create new playlists through unsupervised machine learning!🌀 🎵 🔥

# Project Description 
Having a data set with 19 columns and 5235 rows to describe songs and their "vibes"✨, from Spotify, the goal is to find a way to organize them, 
set some parameters and create the clusters or in this case "playlists".

For that, using Python 🐍 is necessary along with libraries to plot graphs and of course the use of sklearn is of the utmost importance❗

# How is it looking?
It's giving vibes!✨🌀

What you will find in the coding area is:
🛁 Cleaning the "features" or "characteristics" from 19 down to 9! how you ask? CRITICAL THINKING and also correlations :bowtie:
Once the cleaning is done, 💥let's drop the beat!!! let's drop the duplicates before we scale (MinMaxScale) our clean dataset.
With MinMaxScale we are not changing the distribution of our dataset and so we move on with a more homogeneous df! 

How many cluster for Kmeans cluster are there? IDK 🙇 so let's see!
📈 📉 Using Inertia and Silhouette score, check the code :), the conclusion is to use 53 clusters!

NEXT!----> Kmeans cluster time! 💫 UML MAGIC! 💫
We run our algorithm, which btw is a repetitive algorithm that separates a dataset where each data point belongs to only one sub-group. 
And we end up with our 53 playlists, each with a different number of songs to play! 🎵 🔥

Furthering our analysis or "creation", we take playlist 3 with 244 songs (max) and playlist 30 with 17 songs (min)

Now what!!? we don't have time to listen all the playlist to check if they are correct or homogeneous! but we do have time to vibe✨ with one. Playlist 30! 🙌 
So... we chill with playlist 30 with the liveness and the acoustics of the songs picked for us... by a "machine" 🤖 that doesn't get to "vibe"✨  the way we do ☀️

