# 361_movie_micro_service: 
Microservice Database Functions: add movie, get all movies, get count 

* File must be downloaded and saved. 

To start server: 
1. npm install - downloads all node modules 
2. npm start - starts server, http://localhost:4000/

How to REQUEST data: 
SAMPLE CALL TO POST HTTP REQUEST : 
POST http://localhost:4000/addFav
Content-Type: application/json

{
"adult": false,
"backdrop_path": "/l6hQWH9eDksNJNiXWYRkWqikOdu.jpg",
"genre_ids": [
14,
18,
80
],
"id": 497,
"original_language": "en",
"original_title": "The Green Mile",
"overview": "A supernatural tale set on death row in a Southern prison, where gentle giant John Coffey possesses the mysterious power to heal people's ailments. When the cell block's head guard, Paul Edgecomb, recognizes Coffey's miraculous gift, he tries desperately to help stave off the condemned man's execution.",
"popularity": 88.961,
"poster_path": "/velWPhVMQeQKcxggNEU8YmIo52R.jpg",
"release_date": "1999-12-10",
"title": "The Green Mile",
"video": false,
"vote_average": 8.5,
"vote_count": 15032
}


How to RECEIVE data: 
To get all saved movies in fav DB
Make GET HTTP request to -->
<!-- http://localhost:4000/getAllFavs  -->

To get count of all saved movies
Make GET HTTP request to
<!-- http://localhost:4000/getFavsCount -->
