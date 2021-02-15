*Evilgram*

**Evilgram** is a photo sharing app similar to Instagram but using Parse as its backend.  The only thing evil about it is its color theme.

## User Stories / Functional Requirements
- User can sign up to create a new account using Parse authentication.
- User can log in and log out of his or her account.
- The current signed in user is persisted across app restarts.
- User can take a photo, add a caption, and post it to "Instagram".
- User can view the last 20 posts submitted to "Instagram".
- The user should switch between different tabs - viewing all posts (feed view), compose (capture photos form camera) and profile tabs (posts made) using fragments and a Bottom Navigation View. (2 points)
- User can pull to refresh the last 20 posts submitted to "Instagram".
- User sees app icon in home screen and styled bottom navigation view
- Style the feed to look like the real Instagram feed.
- User can load more posts once he or she reaches the bottom of the feed using infinite scrolling.
- Show the username and creation time for each post.
- User can tap a post to view post details, including timestamp and caption.
- Allow the logged in user to add a profile photo
- Display the profile photo with each post
- User sees app icon in home screen and styled bottom navigation view
- Style the feed to look like the real Instagram feed. (Except for color theme!  This is intentional)
- After the user submits a new post, show an indeterminate progress bar while the post is being uploaded to Parse.
- Instagram theme changed to something decidely more evil :)


TODO:
- Tapping on a post's username or profile photo goes to that user's profile page and shows a grid view of the user's posts 
- User can comment on a post and see all comments for each post in the post details screen.
- User can like a post and see number of likes for each post in the post details screen.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

### Feed, Fragments, Bottom Navigation
<img src="walkthroughs/walkthrough_Evilgram_fragNavProfile.gif" width=250><br>

### Infinite Scroll
<img src="walkthroughs/walkthough_Evilgram_infiniteScroll.gif" width=250><br>

### Uploading/Displaying Profile Photo
<img src="walkthroughs/walkthrough_Evilgram_profilePhoto.gif" width=250><br>

### Pull to Refresh
<img src="walkthroughs/walkthrough_Evilgram_pulltorefresh.gif" width=250><br>

### Detail View
<img src="walkthroughs/walkthough_Evilgram_detailView.gif" width=250><br>

### Signup, Login, Logout, User Persistence
<img src="walkthroughs/Evilgram_walkthrough1.gif" width=250><br>

### Photo Capture, Caption, Post
<img src="walkthroughs/Evilgram_walkthrough2.gif" width=500><br>



## Notes

Right now, only photos taken in landscape mode are supported.  
Will need to build a custom camera activity to get functionality I want.

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android
