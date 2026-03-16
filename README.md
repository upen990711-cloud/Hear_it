# Hear_it <img width="1280" height="1024" alt="Hear-It_Transparent" src="https://github.com/user-attachments/assets/cf6e8dc7-55ef-47ce-847e-28323cbd2cc5" />

Hear It is a data analytics project that simulates the backend data environment of a modern music streaming platform. The project focuses on building a structured relational database, generating realistic streaming activity data, and performing analytical queries to understand user engagement, music popularity, and platform performance.

The goal of this project is to demonstrate practical data analyst skills such as database design, SQL analytics, and data-driven insight generation.

Technologies Used:-
->SQL for data modeling and analytical queries
->PostgreSQL for relational database management
->Python for synthetic dataset generation
->Pandas for data processing and transformation
->Power BI for dashboard visualization and insights

Database Design:-
1--users – stores user profile information and subscription type
2--artists – artist details including genre and country
3--albums – album metadata linked to artists
4--songs – song details and duration
5--playlists – playlists created by users
6--playlist_songs – mapping between playlists and songs
7--listening_history – records of user streaming activity

The database structure includes primary keys, foreign key relationships, data validation constraints, and indexes to improve query performance and ensure data integrity.





artists
   │
   ▼
albums
   │
   ▼
songs
   │
   ├ ─────────────► listening_history
   │                   │
   │                   ▼
   │                 users
   │
   ▼
playlist_songs
   │
   ▼
playlists
   
   ▼
users
