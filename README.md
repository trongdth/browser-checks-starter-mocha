# Checkly Browser Checks Starter

This repo accompanies the documentation on browser checks at [checklyhq.com/docs](https://checklyhq.com/docs/browser-checks/)
It install mocha and puppeteer and asserts that the Google Puppeteer repo is the first result on Duck Duck Go.

```bash
git clone https://github.com/checkly/browser-checks-starter.git
cd browser-checks-starter
npm install
mocha check_duckduckgo.js
``` 

The result should look as follows:

[![asciicast](https://asciinema.org/a/f3F570OMM20PnEFvSbttfFbTu.png)](https://asciinema.org/a/f3F570OMM20PnEFvSbttfFbTu)