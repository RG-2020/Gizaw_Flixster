# Gizaw_Flixster

# Flixster Part 1

### User Stories
- [x] User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.

#### BONUS
- [x] (2pts) Views should be responsive for both landscape/portrait mode.
   - [x] (1pt) In portrait mode, the poster image, title, and movie overview is shown.
   - [x] (1pt) In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.

- [x] (2pts) Display a nice default [placeholder graphic](https://guides.codepath.org/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading
- [x] (2pts) Improved the user interface by experimenting with styling and coloring.
- [x] (2pts) For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones.

### App Walkthough GIF

<img src="Flixster.gif" width=250><br>

### Notes
App crashed and reinstalled for three times with the help of GURU I was able to compelete the Assignment. 

## Flixster Part 2

### User Stories

#### REQUIRED (10pts)

- [x] Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [x]  Allow video posts to be played in full-screen using the YouTubePlayerView.

### App Walkthough GIF

<img src="FlixsterP_2.gif" width=250><br>

---

### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids
