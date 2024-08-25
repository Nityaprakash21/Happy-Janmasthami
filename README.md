# Happy-Janmasthami
Creating a Janmashtami-themed animation using HTML and CSS is a wonderful way to combine web development skills with cultural celebration. In this article, we will break down each line of the provided code, explaining its purpose and functionality. We will also discuss the significance of Janmashtami, exploring why it is celebrated and its importance in Hindu culture.

# Understanding the HTML Structure
•	!DOCTYPE html: This declaration defines the document type and version of HTML being used. It ensures that the document is rendered correctly across different browsers.

•	html lang="en": This tag wraps the entire HTML document. The lang attribute specifies the primary language of the document, which is English in this case.

•	head: The head section contains meta-information about the document, such as character set, viewport settings, and links to external resources like stylesheets.

•	meta charset="UTF-8": This meta tag specifies the character encoding for the document, ensuring that it can display characters from multiple languages.

•	meta name="viewport" content="width=device-width, initial-scale=1.0": This meta tag ensures that the page is responsive, meaning it adjusts its layout based on the device’s screen size.

•	titleHappy Janmashtami Animated Landing Page/title: The title tag defines the title of the webpage, which appears in the browser’s title bar or tab.

•	link rel="stylesheet" href="styles.css": This link tag connects the HTML file to an external CSS stylesheet (styles.css), which will be used to style the page.

•	link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css": This link tag includes the Bootstrap Icons library, providing access to a wide range of icons for use on the page.

# Body Content
•	video autoplay loop muted: The video element is used to embed a video on the page. The attributes autoplay, loop, and muted ensure that the video plays automatically, loops indefinitely, and does so without sound.
•	source src="Happy Janmashtami.mp4": This tag specifies the video file to be used. Here, the video is named “Happy Janmashtami.mp4.”
•	nav class="navbar": The nav element represents the navigation bar of the website. It contains links to different sections of the website.
•	div class="container": This div serves as a wrapper to center and contain the navigation elements.
•	a href="#" class="logo"MatteX/a: This a tag is used to create a clickable logo that links to the homepage. The class="logo" is for styling the logo text.
•	ul: The ul element defines an unordered list, used here for the navigation links.
•	li: Each li element contains a single list item, representing a navigation link.
•	main class="container": The main element is the central content area of the webpage, holding the page’s primary content.
•	div class="page-content": This div contains all the content displayed on the page, including the heading, paragraph, buttons, and social links.
•	h1 class="heading"Happy Janmashtami/h1: The h1 element is used for the main heading of the page, styled with the heading class.
•	p: The p element defines a paragraph, used here to display a celebratory message.
•	div class="buttons": This div contains buttons that link to other sections or pages. The active class is used to highlight the primary button.
•	div class="social-links": This div contains social media icons, allowing users to connect via different platforms.
•	a href="#" class="bi bi-facebook"/a: The a tag with Bootstrap Icon classes (bi bi-facebook) creates a clickable Facebook icon

# Breaking Down the CSS
•	@font-face: This CSS rule allows you to define custom fonts. The font-family attribute assigns a name to the font, and the src attribute specifies the location of the font file.
•	*, ::before, ::after: This universal selector targets all elements and their ::before and ::after pseudo-elements, resetting their margin and padding to zero, setting a transition for smoother animations, and ensuring the box-sizing is set to border-box to include padding and borders in the element’s total width and height.

Styling the Video Background
•	position: absolute;: This positions the video relative to the nearest positioned ancestor, which in this case is the body.
•	left: 0; top: 0;: These properties ensure that the video starts from the top-left corner of the page.
•	height: 100%; width: 100%;: These properties make the video cover the entire viewport.
•	object-fit: cover;: This property ensures that the video covers the entire area without distorting its aspect ratio.
•	pointer-events: none;: This makes the video unclickable, ensuring that the user interacts with other elements on the page.
•	z-index: -1;: This places the video behind other content on the page.

Container and Navbar Styling
•	max-width: 950px;: The container’s width is limited to 950px, ensuring the content doesn’t stretch too wide on larger screens.
•	margin: auto;: This centers the container horizontally.
•	padding: 12px 10px;: The navbar is given padding to create space inside the element.
•	display: flex;: Flexbox is used to arrange items within the navbar.
•	justify-content: space-between;: The navbar items are spaced out evenly, with space between them.
•	align-items: center;: This vertically centers the navbar content.
•	font-family: 'sd-asian';: The logo text uses the ‘sd-asian’ font.
Navbar Links and Hover Effects
•	list-style-type: none;: Removes default bullet points from the list.
•	display: flex;: This arranges the list items in a horizontal row.
•	text-decoration: none;: Removes the default underline from the links.
•	margin: 0 10px;: Adds horizontal space between the links.
•	position: relative;: Prepares the link for further styling with pseudo-elements or additional effects.
•	filter: blur(10px);: This CSS rule blurs non-hovered links when one of them is hovered, creating a focus effect.

Page Content and Typography
•	text-align: center;: Centers the text content horizontally.
•	margin-top: 12rem;: Creates vertical space above the page content.
•	font-size: 8rem;: Sets a large font size for the main heading.
•	font-family: 'Poppins', sans-serif;: Uses the ‘Poppins’ font for the paragraph text, ensuring readability and a clean appearance.

Button Styling
•	display: flex;: The buttons are arranged in a row using Flexbox.
•	justify-content: center;: Centers the buttons horizontally within the container.
•	margin: 0 16px;: Adds space between the buttons.
•	padding: 10px 12px;: Provides internal spacing for the buttons.
•	border-radius: 6px;: Rounds the corners of the buttons.
•	backdrop-filter: blur(60px);: Applies a blur effect to the background behind the buttons.
•	overflow: hidden;: Ensures that any content overflowing the button’s boundaries is hidden.
•	z-index: 1;: Ensures the button appears above other elements if there is overlap.
•	border: 1px solid #ffffff1e;: Adds a subtle border to the buttons.

Social Links Styling
•	height: 40px; width: 40px;: Sets the size of the social media icons.
•	border-radius: 99px;: Makes the icons circular.
•	backdrop-filter: blur(160px);: Applies a strong blur effect to the background behind the icons.
•	background: #c624f71e;: Sets a semi-transparent background color for the icons.
•	position: absolute;: Positions the ::after pseudo-element absolutely within its parent element.
•	height: 0%;: Initially, the background color in the ::after pseudo-element is set to cover none of the icon.
•	height: 100%;: On hover, the background color expands to cover the entire icon.

# Janmashtami: A Celebration of Divine Birth
Janmashtami, also known as Gokulashtami, is the celebration of the birth of Lord Krishna, one of the most revered deities in Hinduism. This festival falls on the eighth day (Ashtami) of the Krishna Paksha (dark fortnight) in the month of Shravana according to the Hindu lunar calendar, which usually corresponds to August or September in the Gregorian calendar.

The Significance of Janmashtami
Lord Krishna is considered the eighth incarnation (avatar) of Lord Vishnu, the preserver of the universe in Hindu belief. His birth is celebrated as Janmashtami because it marks the arrival of the Supreme Being in human form, whose life and teachings have deeply influenced Indian culture and spirituality.
Krishna’s life story, particularly his childhood and youth, is a source of great inspiration and joy for millions. His teachings in the Bhagavad Gita, his playful antics as a child, his love for Radha, and his role in the epic Mahabharata are celebrated with great enthusiasm across India and beyond.

How Janmashtami is Celebrated
The celebration of Janmashtami varies across different regions of India. However, the central theme remains the same: celebrating the birth of Lord Krishna with devotion, joy, and enthusiasm.
•	Fasting and Feasting: Devotees observe a fast on Janmashtami, which they break at midnight, the time of Krishna’s birth. The fast is often followed by a feast of special dishes made with devotion.
•	Midnight Celebrations: Since Krishna is believed to have been born at midnight, temples and homes host midnight celebrations. Devotees sing bhajans (devotional songs), perform aarti (ritual of worship with light), and re-enact scenes from Krishna’s life.
•	Dahi Handi: This is a popular event in Maharashtra and parts of North India, where teams form human pyramids to break a pot filled with curd (dahi), symbolizing Krishna’s love for butter and curd.
•	Decorations and Celebrations in Temples: Temples dedicated to Krishna are beautifully decorated. The idol of Krishna is bathed, adorned with new clothes, and placed in a cradle, symbolizing his birth. Devotees visit these temples to offer prayers and seek blessings.
•	Cultural Programs: Many communities organize cultural programs featuring dance, drama, and music that depict various episodes from Krishna’s life, particularly his childhood.

The Spiritual Message of Janmashtami
Janmashtami is not just a celebration of Krishna’s birth but also an occasion to reflect on his teachings. Lord Krishna’s life is a symbol of the triumph of good over evil, love over hatred, and dharma (righteousness) over adharma (unrighteousness). His teachings, particularly in the Bhagavad Gita, continue to inspire millions across the world.
•	Bhakti (Devotion): Krishna emphasizes the importance of bhakti or devotion. Through his life, he showed that the love between the divine and the devotee is the highest form of love.
•	Karma (Action): Krishna’s discourse on karma in the Bhagavad Gita highlights the importance of performing one’s duties without attachment to the results. This teaching encourages people to live a life of selfless service and dedication.
•	Dharma (Righteousness): Krishna’s life is a reminder of the importance of following the path of dharma, even in the face of adversity. He stood up against injustice and evil, encouraging others to do the same.

Conclusion
The Janmashtami animation created with HTML and CSS not only captures the festive spirit of the occasion but also serves as a digital homage to Lord Krishna. By combining modern web technologies with the traditional celebration of Janmashtami, this project offers a unique way to honor the divine. The animation, with its vibrant visuals and interactive elements, provides a meaningful and engaging way to celebrate Krishna’s birth online. Whether you’re a developer or a devotee, this project is a testament to how technology can be used to celebrate and share our cultural heritage.
