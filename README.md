*This repo is no longer being maintained*

# Page Builder Sandwich has been completely rebuilt from the ground up into a Live Front End Page Builder. Please visit [http://pagebuildersandwich.com](http://pagebuildersandwich.com)

Hey folks, 

I wasn't happy at all with how this *old* plugin worked. I just didn't see the point of backend page builders any more. There are a lot of plugins that do that already. The backend isn't exciting and I don't enjoy hitting the preview button multiple times just to see what my edits look like. I want to perform edits on actual content right then and there in the frontend, not on some form of adjusted representation of my content inside a text editor. Page builders should be in the frontend, where you should be able to edit stuff live without any hassle.. just click then type. So I decided to redo the plugin into something that's well suited for frontend editing.

Cheers,

Benjamin Intal


***(All the stuff below this line are from the old plugin)***

---

*We now have [awesome extensions](http://pbsandwi.ch/downloads) to further empower your page building experience.*

# PB Sandwich
*Turn your typical WordPress visual editor into a super charged visual-editor-page-builder hybrid*

One of the most frustrating things when creating content is layouting and writing them inside the visual editor.

Sure you can use **shortcodes columns**, but are not user friendly with all those distracting square brackets. Not to mention that column shortcodes are just displayed as a single column in the visual editor.

Existing **Page builders** are also great, but we didn't want to hijack the content editor and we wanted to find a way to do it using the existing visual editor that everyone knows. Page builders have a ton of code in them for creating brand new interfaces, but more code means more stuff which can go wrong in the future.

# Goal

The goal is to create a page builder that
* Feels and acts *native* and part of WordPress
* Lazy, no settings pages specific for the plugin

# What you can do with it

* Content areas with custom background images & colors
* Create editable, nestable columns
* Edit text and content using the TinyMCE visual editor like how you normally would
* Live working preview of embedded content (e.g. put in a YouTube video and you can play it while still being able to drag it)
* Drag and drop TinyMCE views into other locations
* Clone shortcodes/embeds & columns
* Create different shortcodes
* Working undo

#### Shortcodes

We support the following shortcodes, widgets & elements:

* Archives (Widget)
* Audio (Add Media)
* Audio Playlists (Add Media)
* Button
* Calendar (Widget)
* Categories (Widget)
* Contact Form (Jetpack)
* Custom Menu (Widget)
* Display WordPress Posts (Jetpack)
* Embed
	* Supported URLs include Animoto, Blip, CollegeHumor, DailyMotion, Flickr, FunnyOrDie, Hulu, Imgur, Instagram, iSnare, Issuu, Meetup, EmbedArticles, Mixcloud, Photobucket, PollDaddy, Rdio, Revision3, Scribd, SlideShare, SmugMug, SoundCloud, Spotify, TED, Vimeo, Vine, WordPress.tv and YouTube
	* If you have Jetpack's Shortcode Embeds module enabled, you can also embed Facebook, Github Gist, Google+, and Medium links
* Facebook Like Box (Jetpack)
* Gravatar Profile (Jetpack)
* Google Map (Jetpack)
* HTML5 Video - Self-hosted
* HTML5 Video - Remote-hosted
* Images (Add Media)
* Image Galleries (Add Media)
* Meta (Widget)
* Pages (Widget)
* Portfolio (Jetpack)
* Progress bar
* Recent Comments (Widget)
* Recent Posts (Widget)
* RSS (Widget)
* RSS Links (Jetpack)
* Search (Widget)
* Subscribe (Jetpack)
* Tag Cloud (Widget)
* Toggle / FAQ
* Video (Add Media)
* Video Playlists (Add Media)
* *More being created. Have a suggestion? [Let us know here](https://github.com/gambitph/Page-Builder-Sandwich/issues/new)*

Third-party shortcodes - these show up when the necessary plugin is activated

* bbPress
* Contact Form 7
* Jetpack
* MailChimp for WP
* Ninja Forms
* *Have a plugin suggestion? [Let us know here](https://github.com/gambitph/Page-Builder-Sandwich/issues/new)*

*Shortcode contributions are welcome, we have docs on how to [create them](https://github.com/gambitph/Page-Builder-Sandwich/wiki/Creating-a-Shortcode).

#### WTF, I hate tables! Why are tables used to display columns?

*Be calm!* Tables are **only** used in the backend / visual editor. In the front end, those tables will be **gone** and will be replaced by good ol' clean divs that use Bootstrap's grid to display your content.

Why did we do it this way? Because table editing is handled pretty well by TinyMCE. Instead of re-inventing the wheel, we simply used what TinyMCE already does well and extended that into what we needed.

**So once again, I repeat, no tables are present in the front end.**

# Preview

Shortcodes & widgets
![Shortcodes & Widgets](https://raw.githubusercontent.com/gambitph/Page-Builder-Sandwich/master/preview/shortcodes.jpg)

Creating a registration/login page for bbPress
![Creating a registration/login page for bbPress](https://raw.githubusercontent.com/gambitph/Page-Builder-Sandwich/master/preview/bbpress.jpg)

Drag and drop stuff
![Drag and Drop](https://raw.githubusercontent.com/gambitph/Page-Builder-Sandwich/master/preview/drag-and-drop.jpg)

It lets you do this while editing posts and pages:
![Visual Column Editing](https://raw.githubusercontent.com/gambitph/Page-Builder-Sandwich/master/preview/visual-editor.jpg)

You'll get this as your output:
![Column Results](https://raw.githubusercontent.com/gambitph/Page-Builder-Sandwich/master/preview/frontend.jpg)

# Usage

1. Download the zip from the right side of this page
2. Install & activate the plugin
3. Create/edit a page or post
4. Create shortcodes (via shortcake), add a media or create a column

# Contributing

* [Report bugs](https://github.com/gambitph/Page-Builder-Sandwich/issues) that you may encounter, this is quite new so I'm betting there're some
* We're looking to add common shortcodes via Shortcake to be included in the page builder. You can see our guides on the developer resources.

[View Developer Resources](https://github.com/gambitph/Page-Builder-Sandwich/wiki)
