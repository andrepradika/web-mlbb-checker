# Mobile Legends Username & Region Checker

This project is a simple web-based tool that allows users to retrieve Mobile Legends account details (username and region) by entering their ID and Server. The application fetches data from an external API and displays the retrieved information.

## Features
- Fetch Mobile Legends username and account region using ID and server.
- Simple and responsive UI using Tailwind CSS.
- Uses a proxy to bypass CORS restrictions.
- Displays retrieved data in a formatted manner.

## Demo
[Live Demo](#) (Replace with actual hosted link if available)

## Installation
To run this project locally, follow these steps:

1. Clone this repository:
   ```sh
   git clone https://github.com/andrepradika/web-mlbb-checker.git
   ```
2. Navigate to the project directory:
   ```sh
   cd web-mlbb-checker
   ```
3. Open `index.html` in your browser.

## Usage
1. Enter your **ID** and **Server** in the input fields.
2. Click the **Fetch Data** button.
3. The retrieved Mobile Legends account details will be displayed.

## Technologies Used
- **HTML** - Structure of the webpage.
- **CSS (Tailwind CSS)** - Styling and layout.
- **JavaScript (Fetch API)** - Fetching data from the API and displaying results.

## API Used
This project fetches data from:
```
https://yanjiestore.com/submitt.php?ID={id}&server={server}
```
Due to CORS restrictions, it utilizes:
```
https://api.allorigins.win/get?url={encoded_api_url}
```

## Contributing
Feel free to fork this repository and submit a pull request with any improvements!

## License
This project is open-source and available under the MIT License.

## Author
andrepradika

