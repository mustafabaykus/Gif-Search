# Gif Search App

This project is a Gif Search App that allows users to search for GIFs related to a specific keyword. The app uses the GIPHY API to fetch and display GIFs on the screen. Users can also copy the link to the GIF to share it with others.

## How to Use

1. Clone or download the project repository to your local machine.

2. Open the `index.html` file in your web browser.

3. Enter a keyword in the search box and click the "Submit" button. By default, the app will display GIFs related to the keyword "laugh."

4. The app will fetch 10 GIFs from the GIPHY API and display them on the screen in a grid layout.

5. If the GIFs are still loading, a loader will be displayed until all GIFs are ready.

6. Once the GIFs are loaded, you can click the "Copy Link" button on any GIF to copy the direct link to the GIF to your clipboard.

7. If your browser supports clipboard access, the link will be directly copied to your clipboard. Otherwise, you will be prompted to copy the link manually.

8. The app is responsive and will adjust its layout for different screen sizes, ensuring a smooth user experience on both desktop and mobile devices.

## Configuration

Before running the app, make sure to set your GIPHY API key in the `script.js` file. Replace the placeholder `apiKey` with your actual GIPHY API key.

```javascript
//Paste the generated API Key here
let apiKey = "YOUR_GIPHY_API_KEY";
```

You can obtain a GIPHY API key by signing up for a GIPHY account and creating a new app in the GIPHY Developer Dashboard.

## Dependencies

The app uses the following dependencies:

- **Google Fonts:** The app uses the "Poppins" font from Google Fonts for a clean and modern look.

## Styling

The app's styles are defined in the `style.css` file. It provides a simple and responsive layout for an optimal user experience.

## Support

The Gif Search App has been tested and verified on modern web browsers. For the best experience, it is recommended to use the latest version of your preferred web browser.

Please note that the app might not work correctly on outdated or unsupported browsers.

## Contributing

If you encounter any issues, have suggestions for improvement, or want to contribute to the project, feel free to create a pull request or submit an issue on the project's GitHub repository.

Happy Gif Searching! 🎉
