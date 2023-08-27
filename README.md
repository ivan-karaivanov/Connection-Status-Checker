# Internet Connection Status Monitor

This repository contains a JavaScript script that allows you to monitor the status of your internet connection and display relevant messages based on whether you are online or offline. The script periodically checks the connection status by fetching an image from a remote server and updating the display accordingly.

## How It Works

The script utilizes the following components:

- `image`: The HTML image element that displays an icon indicating the online/offline status.
- `statusDisplay`: The HTML element that displays the connection status message.
- `bgColor`: The HTML element that represents the background and changes color based on the online status.

The script defines the following functions:

- `setColor()`: Adds a CSS class to change the background color when the connection is online.
- `connectionStatus()`: Makes a fetch request to a remote image and updates the display based on the response status.
- `setInterval()`: Periodically calls the `connectionStatus()` function to monitor the connection status.
- `window.addEventListener("load")`: Checks the connection status when the page loads and updates the status display accordingly.

## Usage

1. Include the provided JavaScript code in your HTML file.
2. Make sure you have online and offline status images (`online.png` and `offline.png`) in the "images" directory relative to your HTML file.
3. Customize the messages or images as needed.

## Note

- This script uses a remote image to determine the connection status. Make sure the image URL is accessible and reliable.
- You can customize the appearance and behavior by modifying the CSS classes and messages in the script.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to contribute or use this script to enhance your website's user experience regarding internet connection status.
