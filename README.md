# Chinook_music_case_study-
# Digital Music Store – Data Analysis (Chinook Database)

This project focuses on analyzing the **Chinook Digital Music Store** database to uncover business insights and help optimize business opportunities by answering key data-driven questions.

---

## 📘 Overview
<img width="707" height="571" alt="Data_Model" src="https://github.com/user-attachments/assets/bb6ad064-20a5-4b7c-a764-79ee4013f9f9" />



The Chinook database contains information about:

- Albums
- Artists
- Customers
- Employees
- Genres
- Invoices
- Tracks
- Playlists
- Media Types

Below are the row counts for each table:

```
Album — 347
Artist — 275
Customer — 59
Employee — 8
Genre — 25
Invoice — 412
InvoiceLine — 2240
MediaType — 5
Playlist — 18
PlaylistTrack — 8715
Track — 3503
```

---

## 🎯 SQL Problem Statements

Using SQL, solve the following problems using the **Chinook** database:

### 1) Artist with the maximum number of albums

Display the **artist name** and **number of albums**.

### 2) Listeners who love Jazz, Rock, and Pop

Display **name, email, country** of all such customers.

### 3) Employee supporting the most customers

Display **employee name** and **designation**.

### 4) City with the best customers

Identify the city producing the best customers.

### 5) Country with the highest number of invoices

Find which country has the maximum invoices.

### 6) Best customer

Customer who has **spent the most money**.

### 7) Best city to host a Rock concert

Determine location based on Rock music consumption.

### 8) Albums with less than 5 tracks

Display **album name**, **artist name**, and **number of tracks**.

### 9) Tracks that are not purchased

Display **track, album, artist, genre** for all unpurchased tracks.

### 10) Artists performing in multiple genres

Display **artist name** and **genre list**.

### 11) Most and least popular genre

Determine popularity based on purchases.

### 12) Most expensive tracks

If tracks are more expensive than others, display **track name**, **album title**, **artist name**.

### 13) Top 5 most popular artists for the most popular genre

Popularity defined by **number of songs** performed in that genre.

### 14) Artist with the maximum number of songs/tracks

Display **artist name** and **number of songs**.

### 15) Albums owned by multiple artists

Identify whether any album belongs to more than one artist.

### 16) Invoice issued to a non-existing customer

Check for referential integrity violations.

### 17) Invoice line for a non-existing invoice

Check for orphan invoice line records.

### 18) Albums without a title

Identify incomplete album data.

### 19) Invalid tracks in playlists

Identify tracks present in playlists but invalid or missing.
