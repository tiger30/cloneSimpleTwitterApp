# MySimpleTweets

Week3 Codepath Android Assignment:  write a simple twitter application that allows user to view and
post tweets to their twitter timeline.

Required features:

[x] User can sign in to Twitter using OAuth login.
[x] User can view the tweets from their home timeline.
    [x] User should be displayed the username, name, and body for each tweet. 
    [x] User should be displayed the relative timestamp for each tweet "8m", "7h". 
    [x] User can view more tweets as they scroll with infinite pagination.
[x] User can compose a new tweet.
    [x] User can click a “Compose” icon in the Action Bar on the top right. 
    [x] User can then enter a new tweet and post this to twitter .
    [x] User is taken back to home timeline with new tweet visible in timeline. 

Optional features:

[x] Advanced: While composing a tweet, user can see a character counter with characters remaining for tweet out of 140.
[x] Advanced: Links in tweets are clickable and will launch the web browser.
[x] User can refresh tweets timeline by pulling down to refresh (i.e pull-to-refresh).
[] Advanced: User can open the twitter app offline and see last loaded tweets.
  [] Tweets are persisted into sqlite and can be displayed from the local DB.
[] Advanced: User can tap a tweet to display a "detailed" view of that tweet.
[x] Advanced: User can select "reply" from detail view to respond to a tweet .
[x] Advanced: Improve the user interface and theme the app to feel "twitter branded".
[] Bonus: User can see embedded image media within the tweet detail view.
[] Bonus: User can watch embedded video within the tweet. 
[x] Bonus: Compose activity is replaced with a modal overlay.
[] Bonus: Use Parcelable instead of Serializable using the popular Parceler library.
[] Bonus: Apply the popular Butterknife annotation library to reduce view boilerplate. 
[x] Bonus: Leverage RecyclerView as a replacement for the ListView and ArrayAdapter for all lists of tweets. 
[] Bonus: Move the "Compose" action to a FloatingActionButton instead of on the AppBar. 
[x] Bonus: Replace Picasso with Glide for more efficient image rendering.


## Video Walkthrough

Here's a walkthrough of implemented user stories:


<img src='http://imgur.com/f2naoFf' title='Login Walkthrough' width='' alt='Login Walkthrough' />

<img src='http://imgur.com/9YaYLbP' title='Compose Walkthrough' width='' alt='Compose Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).
