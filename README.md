# YouTube Manager App

## Author
Sudham SS

## Description

The *YouTube Manager App* is a Python-based application designed to manage a collection of YouTube videos using MongoDB. The purpose of this project is to demonstrate proficiency in MongoDB, including setup, connection, and CRUD operations. The application uses MongoDB Atlas, a cloud-based service for MongoDB, for managing the database.

## MongoDB Setup

The application connects to MongoDB Atlas using the pymongo library. The MongoDB setup involves the following:

- *Connection:* Establishes a connection to the MongoDB cluster using the provided connection string.
- *Database:* Accesses the ytmanager database.
- *Collection:* Manages video data within the videos collection.

## Features

- *List Videos:* Retrieve and display a list of all videos in the database.
- *Add Video:* Insert new video entries with details such as name and duration.
- *Update Video:* Modify existing video details based on video ID.
- *Delete Video:* Remove video entries from the database based on video ID.

## How It Works

1. *Run the Application:* Start the application to interact with the YouTube video database.
2. *Menu Options:* The user is presented with a menu to list, add, update, or delete videos.
3. *User Input:* Input is received through the console to perform various operations.
