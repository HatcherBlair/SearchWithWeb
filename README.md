# Search With Web - A Chrome extension that makes Google searches default to the web tab

## Motivation
I was recently informed of the web tab when doing a Google search, a tab meaning all, images, videos, shopping, etc.  Web search removes most of the sponsored content and other junk that tends to clog up a Google search.  I wanted to make this the default option on my browser but there is not a native way to do it in Chrome. This extension solves that problem by adding a search engine to Chrome and making it default to the web tab.

## Installation
This extension is not available on the web store because I would need to own the domain google.com to post it.  The only way to install it is to clone the repo and load the extension in developer mode.

1.  Clone the repo `git clone https://github.com/HatcherBlair/SearchWithWeb.git`
2. Go to the extensions menu in Chrome `chrome://extensions`
3. Enable developer mode by clicking the toggle button in the top right
4. Click on the Load unpacked button in the top left
5. Select the directory cloned from GitHub and Chrome will load the extension

## Usage
Once the extension is installed any search from the address bar will have ‘&udm=14’ appended to it, which makes the search default to the web tab.  The first search after the extension is installed will ask you to confirm that an extension is changing your search engine.  Searches from google.com directly will not default to the web tab.  There is no UI to selectively enable or disable the extension, it must be done from `chrome://extensions`.

### At the moment English is the only supported language

## Contribution
Feel free to fork and submit PRs.  Also, feel free to fork and make your own repo. Do whatever you want.
