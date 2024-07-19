# SimpleAdBlocker
Overview
Simple Ad Blocker is a Chrome extension designed to block ads and improve your browsing experience. This extension utilizes the declarativeNetRequest API in Manifest V3 to filter out unwanted advertisements from known ad servers.

Features
Blocks ads from specific domains (e.g., doubleclick.net and googleadsservices.com).
Simple and lightweight.
Easy to configure and extend with additional rules.

Installation
Clone the repository:
git clone https://github.com/yourusername/Simple_Ad_Blocker.git
Open Chrome and navigate to chrome://extensions/.

Enable "Developer mode" in the top right corner.

Click on "Load unpacked" and select the directory where you cloned the repository.

The Simple Ad Blocker extension should now be installed and active.

Usage
The extension will automatically block ads from the specified domains.
To modify the list of blocked domains, edit the rules.json file and reload the extension.
File Structure
manifest.json: The extension manifest file that defines permissions and resources.
rules.json: Contains the rules for blocking ad URLs.

Contributing
Feel free to fork this repository and submit pull requests. If you encounter any issues or have suggestions for improvements, please open an issue.

