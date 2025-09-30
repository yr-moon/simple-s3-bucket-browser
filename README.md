# simple-s3-bucket-browser

A simple, client-side S3 bucket browser built with HTML + jQuery.  
This project allows you to navigate folders, view files, and see the latest modified date of nested contents.

## Features
- Browse folders (`CommonPrefixes`) and files (`Contents`)
- Shows file/folder counts at 1-depth
- Folder **Date Modified** reflects the newest file inside (recursive)
- Works directly with S3 REST endpoint (not static website hosting)

## Usage
1. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/s3-bucket-browser.git
   cd s3-bucket-browser
   ```
2. Edit `index.html` and set:
   ```js
   var BUCKET  = "<your-bucket-name>";
   var REGION  = "<your-region>";
   ```
3. Open `index.html` in your browser.

## License
[MIT](LICENSE)

---

© 2025 https://github.com/yr-moon
