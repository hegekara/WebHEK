

---WebTech Homework Personal Blog Readme File---

Caution: Because of the icons are taken simultaneously from the internet, an internet connection is required while browsing the site for the site to work properly.

1. Purpose
Understand HTML&CSS basics.

2. HTML FILE

	A) Head
	<link rel="stylesheet" href="style.css">	:add CSS file (line 10).
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">	:add font-awesome/4.7.0 library which include some icons (line 11).

	B) Sidebar
	Using with sidebar you can switch between classes. I used font awesome library icons to open and close sidebar with checkbox. And add classes list using unordered list tag <ul>.

	C) Section
		a. Navbar
		This div include only header tag.

		b. Home
		This div include centered main title "Welcome to My First Website".

		c. Content
		This div include some personal stuff using with <p>, <ul>, and image.

		d. Form
		There is  a few form tag in fieldset. This include text, email, tel, radio, date, submit, reset and textarea tags to create form attribute.

		e. Footer
		There are my GitHub and LinkedIn accounts finally.

3.CSS FILE
All images used are in the contents folder.

	A) All File
	I add scroll-behavior: smooth to transition between classes nice.

	B) Sidebar
	Sidebar hiding with margin-left: -250px (because sidebar width: 250px) on the left side. If you click font awesome icon where it is top-left corner the checkbox going to be checked position thus margin-left going to be 0px and show itself (line 140-142 in style.css) and add some transition to look better. I designed the list elements with a odd line number as zebra style for easy reading (line 85-87 in the style.css). You can use sidebar to switch chapters.

	C) Navbar
	Navbar only has header element contains "Home" with black stripe on the back. If tab's width small then 640px nabber goes to top to complexity between the texts and icons (line 185-192 in the style.css). 

	D) Content
	Added black stripe on the back to easy to read and added image left side of the text.

	E) Form
	I used fieldset tag to show the form is not complicated in HTML file. This is a html tag but it appeals to more design so I want to explain it in CSS section.

	F) Footer
	There are GitHub and LinkedIn links in this section. Links are aligned center.

4.Challenges
I struggled two things. First of them while creating sidebar without JS second of them getting the background image to continue to the end of the site properly but I done this by watching some tutorial videos and searching some tutorial based web-sites.

5.References
https://www.w3schools.com/icons/fontawesome_icons_intro.asp -> To add icons
https://pixabay.com/photos/milky-way-stars-night-sky-2695569/?download ->Background image
