# DGL114-Process-Portfolio
## By Trevor Jacob
A Process Portfolio for DGL 114, Intro to Mobile App Development

### Week 1
**Activity 0101** <br>
<img src="Images/DGL_114_Task1_Screenshot1.png" alt="Good App PT1" width="200px">
<img src="Images/DGL_114_Task1_Screenshot2.png" alt="Good App PT2" width="200px">

I consider **Reddit's** mobile interface to be good because it keeps it simple but not to the point where it's hard to do anything. The two most commonly used buttons are on the bottom left that show your feeds, and what communities that you're following so you can quickly go to any community you want and view posts made on there.

<img src="Images/DGL_114_Task1PT2_Screenshot1.png" alt="Difficult App PT1" width="200px">
<img src="Images/DGL_114_Task1PT2_Screenshot2.png" alt="Difficult App PT2" width="200px">

I consider **Spotify's** app to be more difficult to use, mostly due to the fact that the home page feels cluttered. It also doesn't help that the library page shows icons for the playlists, meaning less can fit on one page requiring you to scroll down to find playlists that are on the bottom.

**Activity 0102**<br>
- Usable
  - Content on the home page
  - Useful buttons
  - Clear divide between what is the home and what is extra/side content
- Intuitive
  - House/Logo will always take you to the home/main page of the app
  - Useful icons that don't require the user to read the text under it
  - Content is where you'd expect it to be. No settings/extra content on the main page for example

### Week 2
**Activity 0202: Reddit** <br>
<img src="Images/DGL_114_Task1_Screenshot1.png" alt="Model View Controller of Reddit" width="200px">
- Model
  - Subreddit icons/names
  - User's icon at the top left
  - Upvote/Downvote icons clicked yes/no
- View
  - Subreddit icons/names again as you can also click on them
  - The 5 icons at the bottom
  - Profile icon at the top left
  - Coins icon at the top right
- Controller
  - Upvote/Downvote icons
  - Comments, Share and the Award buttons

**Activity 0203** <br>
The Material.io article on [Iconography](https://material.io/design/iconography/product-icons.html) breaks down the "proper" way to design icons for one's brand. It gives a super basic breakdown of how to think about designing an icon, from what the material is made of, to how it interacts with a lighscource. Terminology relevant to the process is also covered and shown with examples, like *Finish, Material background and foreground, Colour and Shadows.* It also covers the do's and don'ts of icon design, though it does make you think about it, or at least brings it to your attention as to why you think something looks good. If you were to follow all of the do's presented on this page though, the icon you'd make would look very similar to everything Google has made and used for their icons.

### Week 3
**Activity 0301: Reddit** <br>
- Posts
  - "My Profile"
  - "Saved" -> comments/posts tabs
  - History
  - Pending
  - Drafts
  - Main page
  - Communities/Custom Feeds page
  - Chats page
- Making Money
  - Reddit Coins
  - Reddit Premium
  - Advertisement posts (click on them and it opens a new screen)
- Settings
  - Inbox
  - Settings menu (it's full screen popup)
  - Avatar Creation

**Activity 0302: Spotify** <br>
- onTouch
  - Selecting Menus
  - Selecting Songs
  - Pause/Song controls
  - Scrolling
  - Navigating Menus
- onDrag
  - Unused
- onLongClick
  - From what I can tell this isn't used, surprisingly
- onFocusChange
  - When inputting searches for songs/artists
  - When clicking on albums/playlists
- Other?
  - I know when spotify knows it's connected to a car's bluetooth it displays a huge version of the song control menu.

### Week 4
**Activity 0401: Spotify** <br>
The app from what I can tell is relatively flat, but not completely so. The main 3 pages for the app are Home, Search, and Your Library. The home page also has a settings button in the top right bringing you to the settings area. The search only has a camera option for scanning codes, and the Your Library page has 3 tabs, Playlists Artists and Albums. Also, this page has a podcasts page with 3 more tabs, Episodes, Downloads, Shows. There's no real central page from where every other page is accessed, instead that function is tied to the bottom bar.

**Activity 0403** <br>
The bottom app bar on a phone is mostly for navigation, but can have other options on it though google suggests no more than 4. When it comes to a Floating Action Button (FAB) they can be either above it layer wise, or inset (taking a chunk out of the bar) but shouldn't be placed physically above the bar as it makes it too hard to comfortably reach. They also suggest avoiding app navigation on the bar, specifically the home button/arrow for example, that should be on the top bar instead. Having a bottom bar doesn't mean you can't also have a top, though they shouldn't share any function (don't place a navigation menu on both top **and** bottom for example).

### Week 5 
**Activity 0502: Spotify** <br>
- Touch events
  - ACTION_DOWN for getting that "feel" of hitting a button. Songs and playlists shrink a little when tapped
  - ACTION_MOVE for scrolling through lists, whether that being song lists or your library of playlists
  - ACTION_UP I believe this is what actually gets used for tapping buttons and other objects, activating them
- Touch gestures
  - Tap. For hitting buttons
  - Scroll. For scrolling through lists
  - Drag. for re-arranging the song queue 
  - Fling. Scrolls through almost the entire playlist without you needing to continue to scroll through

**Activity 0503** <br>
Material.io's article on [Dialogs](https://material.io/components/dialogs) essentially says that dialogs are important, but since they completely stop the flow of the app, they shouldn't be overused. Also mentioned in the article is *how* to make a dialog box that is easy to use and understand. Things such as "choose a good title" and how to place the accept/deny buttons are brought up. The general idea being, don't assume the user knows exactly what each and every button does. So make sure that the deny button for an email for example, says discard instead of "Discard? -> yes." More detailed information on **when** to use them is also brought up, with other notifications that don't *need* user input being better suited to a banner or snackbar popup.
### Week 7