# jenkins-blue-scroll-no-more
An unpackaged chrome extension that stops Jenkins Blue from scrolling to the bottom of the page while a job is building.

## Usage
1. The extension can be added to chrome by:
  a. Pulling this repository
  b. Visiting the `chrome://extensions/` page 
  c. Selecting 'Load Unpacked' and selecting the repository directory 
2. The `jenkins-js-extension.js` file must be hosted on a file server, the URL to which must be updated in the `redirect_file.js`.
