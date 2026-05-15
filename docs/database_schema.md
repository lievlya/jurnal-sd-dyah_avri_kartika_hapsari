\# Database Schema Sederhana

\### 1. Tabel Users

\* `id` (INT, Primary Key)

\* `username` (VARCHAR 50)

\* `email` (VARCHAR 100, Unique)

\* `password\_hash` (VARCHAR 255)

\* `avatar\_url` (VARCHAR 255)



\### 2. Tabel Sessions

\* `id` (INT, Primary Key)

\* `user\_id` (INT, Foreign Key -> Users.id)

\* `login\_time` (TIMESTAMP)

\* `token` (VARCHAR 255)

