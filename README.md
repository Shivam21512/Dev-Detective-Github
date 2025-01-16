# DevDetective

DevDetective is a simple and elegant web application that allows users to search for GitHub profiles and view key details about users, including their repositories, followers, following count, and more.

## Features

- **Responsive Design:** The app is built to work seamlessly on various devices, offering a great user experience.
- **Search Functionality:** Enter a GitHub username to fetch and display the user's public profile information.
- **Dark Mode Toggle:** A theme switcher allows users to toggle between light and dark modes.
- **Dynamic Content Loading:** Profile details, stats, and other information are dynamically loaded and displayed.
- **External Links:** The app provides links to GitHub profiles, personal websites, and Twitter profiles, where available.

## Technologies Used

- **HTML5**: For the structure of the application.
- **CSS3**: For styling and layout.
- **JavaScript**: For interactivity and fetching GitHub user data via APIs.
- **Google Fonts**: Utilized for better typography with the Space Mono font.
- **Icons**: Custom SVG icons for various sections like location, website, Twitter, and company.

## Project Structure

```plaintext
.
├── index.html       # Main HTML file
├── style.css        # CSS file for styling
├── script.js        # JavaScript file for interactivity
├── Images/          # Folder containing icons and images
│   ├── apple-touch-icon.png
│   ├── favicon-32x32.png
│   ├── favicon-16x16.png
│   ├── moon-icon.svg
│   ├── location-icon.svg
│   ├── website-icon.svg
│   ├── twitter-icon.svg
│   └── company-icon.svg
└── site.webmanifest # Web app manifest for PWA capabilities
