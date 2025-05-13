A lightweight browser extension built using JavaScript that blocks intrusive ads and pop-ups for a smoother, faster, and distraction-free browsing experience.

📌 Table of Contents
Features

Technologies Used

Installation

Usage

How It Works

Screenshots

Contributing

License

✅ Features
Blocks banner ads, pop-ups, and video ads.

Improves page load speed by preventing unwanted scripts.

Easy toggle ON/OFF via a browser action button.

Custom blacklist for user-defined blocked URLs.

Simple and clean UI built with HTML, CSS, and JS.

🛠 Technologies Used
Core Languages:

JavaScript (Vanilla)

HTML5

CSS3

Browser Platform:

Chrome (compatible with Chromium-based browsers)

Tools:

Chrome Extensions API

Manifest v3

Regex for URL matching

🚀 Installation
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/yourusername/ad-blocker-js.git
Load Extension in Chrome:

Open Chrome and go to chrome://extensions/

Enable Developer Mode (top right)

Click Load Unpacked

Select the project directory (ad-blocker-js)

Verify Installation:

You’ll see the Ad Blocker icon in the extension bar.

💻 Usage
Click on the Ad Blocker icon to:

Enable or disable ad blocking on the current site.

Add the current site to the custom blocklist.

Ads will be automatically removed from supported pages.

To customize blocked elements, update the blacklist in background.js.

⚙️ How It Works
Uses Chrome’s webRequest API to intercept and block requests to known ad URLs.

Injects content scripts that hide DOM elements matching ad-related CSS selectors.

Custom blacklist allows users to add their own rules.

Lightweight and non-intrusive, with no performance penalty.
