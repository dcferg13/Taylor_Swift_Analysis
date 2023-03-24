# Taylor_Swift_Analysis
Using Tableau as a visualization of Taylor Swift data from Spotify's API
## Overview
Using data on Taylor Swifts albums from Spotify's API, this dataset was gathered from [Kaggle](https://www.kaggle.com/datasets/jarredpriester/taylor-swift-spotify-dataset?select=taylor_swift_spotify.csv)
## Results
In order to better understand this data was to convert the duration column. The data was presented as milliseconds, but converting it into minutes and seconds would give better knowledge to the viewer on the duration of a track. To convert the duration in tableau, I had to create a calculated field.
![duration_conversion](https://user-images.githubusercontent.com/107289345/224881219-35178822-659e-42a7-8d04-7f3f2fff40f9.png)

Two things that I wanted to know about this data was popularity. 
1) Which song was the most popular? 
2) The comparison on popularity between Red & Red (Taylor's Version), and Fearless & Fearless (Taylor's Version). 
![popularity_dashboard](https://user-images.githubusercontent.com/107289345/227386876-7f0c8f5e-fcb6-4486-b5b3-175db3906750.png)
According to the two charts, the most popular song (as of 03/07/2023) was "Don't Blame Me" and most popular Album was Reputation. 
It was interesting to also see that the Taylor Version's of albums Red and Fearless were more popular than the original albums. My educated guess would be that Taylor Fans listen to the Taylor Version as a sign of support toward her. 

Another, visualization that I looked at was the danceability. The dataset describes danceability as a rating between 0.0 and 1.0, with 1.0 being the most danceable and danceability described as a track that best suits dancing based on the combination of musical elements within that track.

In this image below, I wanted to look at the danceability between that latest album released "Midnights" (10/21/2022) and her debut album "Taylor Swift" (10/24/2006). 
We can see that "Midnights" has the majority of danceable songs compared to "Taylor Swift", with the song "Vigilante Sh*t" being the most danceable song and "Sweet Nothing" be ranked last. The next step in this category would be to compare her first and last country albums and her first and latest pop genre album.

![danceability](https://user-images.githubusercontent.com/107289345/227391521-2d129651-8456-4a57-af16-7e94765cf9d9.png)

The next step in this category would be to compare her first and last country albums and her first and latest pop genre album.
