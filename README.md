# URL Replacer

**Version:** 1.0


## Overview

**URL Replacer** is a Chrome extension designed to automatically replace specified URLs when pasting text into input fields and contentEditable elements. This ensures consistent and updated links across various websites, streamlining your workflow and enhancing productivity.

## Features

- **Automatic URL Replacement:** Seamlessly replaces predefined URLs upon pasting.
- **Multiple Replacement Pairs:** Manage multiple URL pairs through an intuitive interface.
- **User-Friendly Interface:** Windows 11-inspired design for a modern and clean look.
- **Works Across All Websites:** Operates on any webpage with input fields or contentEditable elements.
- **Local Storage of Settings:** Keeps your replacement pairs saved between sessions using Chrome's storage API.

## Installation

### Option 1: Install from Chrome Web Store

You can download the extension directly from the Chrome Web Store using the following link:
[URL Replacer on Chrome Web Store](https://chromewebstore.google.com/detail/url-replacer/ammojonfhgipdfopnoollnipdbmkclhi?pli=1)


### Option 2: Install from Source

1. **Download the Extension Files:**

   - Clone the repository or download the ZIP file and extract it.

   ```bash
   git clone git@github.com:nir0k/url-replacer.git
   ```
2. **Load the Extension in Chrome:**
   - Open Google Chrome.
   - Navigate to `chrome://extensions/`.
   - Enable **Developer mode** by toggling the switch in the top right corner.
   - Click on **"Load unpacked"**.
   - Select the directory where you saved the extension files.

## Usage

1. Configure Replacement Pairs:
   - Click on the URL Replacer icon in the Chrome toolbar.
   - The options page will open.
   - Add your desired From URL and To URL pairs.
   - You can add multiple pairs and delete them as needed.

2. Automatic Replacement:
   - When you paste text containing a From URL into any input field or contentEditable element, it will automatically be replaced with the corresponding To URL.
   - This works across all websites without any additional action required.

## Example

If you have the following replacement pair:

   - From URL: `https://oldsite.com`
   - To URL: `https://newsite.com`

When you paste text containing `https://oldsite.com/page`, it will automatically change to `https://newsite.com/page`.

## Development

### Project Structure

   - `manifest.json`: The extension's manifest file.
   - `content.js`: Handles the URL replacement logic.
   - `options.html` and `options.js`: The options page interface and functionality.
   - `icons/`: Contains the extension icons in various sizes.

## Building the Extension

No build process is required since this is a simple Chrome extension. Just ensure all files are in the correct directories as specified.

## Contributing

Contributions are welcome! If you have suggestions for improvements or encounter any issues, please open an issue or submit a pull request.
### Steps to Contribute

    Fork the repository.
    Create a new branch for your feature or bug fix.
    Commit your changes with clear commit messages.
    Push your branch to your forked repository.
    Open a pull request to the main repository.

## License

This project is licensed under the Apache License.
