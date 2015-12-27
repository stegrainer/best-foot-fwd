# Best Foot Forward

Best Foot Forward is a starter template for a web-based résumé. With this template, your résumé will look great on any device, and even printed. It's responsive, which means the content adapts to fit the device you're viewing it from. It uses the hResume microformat which means that it's easier for search engines and job services to correctly parse and categorize your résumé.

## Contents

The ZIP file you received contains several files:
- This very helpful README file
- index.html - the résumé file itself
- styles.css - the primary stylesheet
- print.css - the printed stylesheet
- respond.min.js - javascript file to make the responsive stylesheet work in Internet Explorer
- photo.png - generic "photo" image as a placeholder for the photo in the template
- /images
	- marker.gif - the map marker image that appears next to locations
	- marker-sm.gif - a smaller map marker image for IE variants
	- calendar.gif - the calendar image that appears next to dates
	- calendar-sm.gif - a smaller calendar image for IE variants
	- paper-bg.png - the paper background on the 'light' theme
	- dark-bg.png - the dark background on the 'dark' theme
	- wood-bg.png - the wood background on the 'medium' theme
	- dribbble.png - image for Dribbble links
	- facebook.png - image for Facebook links
	- twitter.png - image for Twitter links
	- gplus.png - image for Google+ links
	- linkedin.png - image for LinkedIn links

The images will only appear on the web. (They are placed as background images, and most browsers by default do not print background images.)


## Features:
- Fully responsive
	- quick navigation points for smaller screens
	- fluid design up to 1000 pixels wide (to maintain maximum readable line lengths)
	- icons for location/date in experience and education look crisp even on high DPI displays
- hResume microformat for better semantic parsing by search engines
- Great print stylesheet; leave the Word or PDF résumé on your old ZIP disk
- Highlight the depth of your skills - visually convey which skills are strengths and which skills are average
- Simple to update and extend


## Setup

1. Obviously, since you are reading this README file, you have already unzipped the contents of the file. Feel free to proceed to step 2.

2. Customize the résumé to your heart's content.
		a. If you're comfortable with HTML, feel free to dive right in and add your own personal details. Make sure to leave the classes intact to maintain the styles and hResume microformat.
		b. If you're new to HTML, you have a few options.
				i. Find a good "WYSIWYG" (What You See Is What You Get) web editor - a quick search on Google points me toward several reasonable sounding options, the most popular of which seems to be KompoZer.
				ii. If you have a friend or family member who knows HTML, have them edit the page with your changes.
				iii. Tough it out and add novice HTML to your skills

3. There are a couple things to note on customizing your résumé:
		- For the photo, I recommend an image roughly 400 pixels wide by 500 pixels tall at 72 dpi. (The higher resolution looks better on high-DPI/retina displays.)
				- If you would prefer to remove the photo, you will need to:
						- remove 'hasphoto' from the class attribute on the <body> tag
						- remove the entire section from START PHOTO BLOCK to END PHOTO BLOCK
		- To customize the background, set the body tag's class to either:
				- light: defaults to a light paper texture
				- dark: defaults to a dark linen texture
				- medium: defaults to a bamboo wood texture. Use medium for any background image with significant complexity (such as images or medium-range textures).
		- You can also append the following optional classes on the body tag:
				- tiled: to tile your background image repeatedly (great for seamless, repeating textures)
				- full: to fill the page with your background image instead of tiling it (recommended for larger images or photos)
				- fixed: to have your background image remain in place as the page is scrolled
				- you can add both "full" and "fixed" to have a large image that stays fixed in place as you scroll
		- There are several tiers to skills to help you visually show depth of experience. Those tiers are in order of experience:
				- novice
				- journeyman
				- adept
				- master
				- guru
			Be honest when assessing your skill level, and your interviews will go much more smoothly.
		- Some sections may not be relevant depending on your career path. If you don't have or need to list a portfolio or publications, by all means, remove those sections. Be sure to remove the corresponding link from the navigation as well. (The navigation only displays at lower resolutions.)
		- Social icons and links are available for Facebook, Twitter, LinkedIn, Google+, and Dribbble. If you need or want to include others, the full, matching set of icons is available for purchase from: http://lifetreecreative.com/icons/

4. Once you have updated your résumé, you will need to find a place to host it on the web. There are plenty of free or inexpensive hosting services available. Here are some recommendations:
		- [The Simplest and Cheapest Free Web-Hosting Services](http://lifehacker.com/5530961/the-simplest-and-cheapest-free-web-hosting-services)
		- [Use Dropbox to Share and Host Your Web Site](http://lifehacker.com/5528104/use-dropbox-to-share-and-host-your-web-site)
		- [Five Best Web Hosting Companies](http://lifehacker.com/5911651/five-best-web-hosting-companies)
	The main thing to look for is hosts that allow you to upload your own files. (Some free hosts require you to build the site through their templates.)


## Writing a great résumé
- Be honest, but don't be afraid to brag about your accomplishments.
- Experience lacking somewhere? Find ways to augment that with volunteer work or personal projects.
- Keep it short and sweet. Don't go over two pages. Make your descriptions sing with strong action verbs.
- Keep it relevant. If you're applying for a design job and have good relevant design experience, don't spend much (if any) time talking about that fast food job from high school.
- Don't lie. Sooner or later, it will come back to bite you.


## Thanks!

Thanks for purchasing the Best Foot Forward résumé template. If you have any further questions about customizing it, I would be happy to assist you at support@saunterstudios.com.


## Version History

1.1 - Latest Version
		- Added a photo to the template
		- Added a social networking section, including links and icons for Facebook, Twitter, Google+, LinkedIn, and Dribbbble

1.0
		- Responsive resume template
		- Printer-friendly stylesheet
		- Themes (light, dark, medium)
		- Ranked skills list
		- hResume format