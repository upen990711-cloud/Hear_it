# HearIt – Music Streaming Analytics 🎧📊
<img width="1280" height="1024" alt="Hear-It_Transparent" src="https://github.com/user-attachments/assets/8e6228af-bb73-42f3-9734-c9e6af04b39c" />


HearIt is a data analytics project that simulates the backend data environment of a modern music streaming platform. The project focuses on designing a structured relational database, generating realistic streaming activity data, and performing analytical queries to understand user engagement, music popularity, and overall platform performance.

The objective of this project is to demonstrate practical data analyst skills including database design, SQL-based analytics, and data-driven insight generation.

---

## Technologies Used

* **SQL** – data modeling and analytical queries
* **PostgreSQL** – relational database management system
* **Python** – synthetic dataset generation
* **Pandas** – data processing and transformation
* **Power BI** – dashboard visualization and analytics insights

---

## Database Design

The project uses a normalized relational schema consisting of the following tables:

1. **users** – stores user profile information and subscription type
2. **artists** – artist details including genre and country
3. **albums** – album metadata linked to artists
4. **songs** – song details and duration
5. **playlists** – playlists created by users
6. **playlist_songs** – mapping between playlists and songs
7. **listening_history** – records of user streaming activity

The database includes primary keys, foreign key relationships, validation constraints, and indexes to improve query performance and maintain data integrity.

---

## Schema Relationships

artists
│
▼
albums
│
▼
songs ─────────► listening_history
│
▼
playlist_songs
│
▼
playlists
│
▼
users

---

## Project Purpose

This project demonstrates an end-to-end analytics workflow including database schema design, dataset generation, SQL analytics, and dashboard-based insight generation.
