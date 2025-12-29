
# Lost and Found Managment System

A desktop-based application built with JavaFX designed to streamline the process of reporting lost items and matching them with found entries. The system acts as a bridge to help users recover their belongings through an automated matching engine.

# 🚀 Features
### Report Lost Items: 
Users can submit detailed descriptions of lost items, including category, color, location, and date.

### Report Found Items: 
Finders can log items they've discovered with specific attributes.

### Automated Matching Engine: 
The core logic compares new "Lost" queries against the existing "Found" database and notifies the user if a potential match is found.

### Search & Filter: 
Browse through the list of reported items based on various categories.

### User-Friendly Interface: 
Built with JavaFX for a clean, responsive desktop experience

## 🛠️ Tech Stack
Language: Java

Framework: JavaFX (for GUI)

Build Tool: Maven

Database: MySQL

## 🧩 How It Works
#### Submission: 
The user inputs details about an object (e.g., "iPhone 13, Blue, Library, 2024-10-12").
Processing: The system stores these specifications in the database.

#### Matching Logic:

When a "Lost" entry is created, the system triggers a search function.

It iterates through the "Found" table, comparing key attributes like Category, Primary Color, and Location.

If the similarity threshold is met, the system displays the match to the user.
