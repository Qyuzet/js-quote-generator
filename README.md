# JS Quote Generator

## Overview

The **JS Quote Generator** is a web application that provides users with randomly generated quotes at the click of a button. This project showcases the use of JavaScript, HTML, and CSS to create an interactive and visually appealing web app. It serves as a practical example for computer science students to learn about API integration, DOM manipulation, and responsive design.
[TRY NOW!](https://qyuzet.github.io/js-quote-generator/)


![image](https://github.com/Qyuzet/js-quote-generator/assets/93258081/b41aa854-8222-41e9-b1db-4642dae015ef)

## Features

- **Random Quote Generation**: Users can generate random quotes by clicking a button.
- **API Integration**: The app fetches quotes from an external API.
- **Responsive Design**: Ensures a seamless experience across various devices.

## Installation

To run the app locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/Qyuzet/js-quote-generator.git
    ```
2. Navigate to the project directory:
    ```bash
    cd js-quote-generator
    ```
3. Open `index.html` in your preferred web browser.

## File Structure

- **index.html**: The main HTML file containing the structure of the app.
- **style.css**: The CSS file providing the styling for the app.
- **scripts.js**: The JavaScript file containing the logic and functionality of the app.

## Usage

1. Open `index.html` in a web browser.
2. Click the "New Quote" button to generate a random quote.

### Code Explanation

#### HTML (`index.html`)

The HTML file sets up the basic structure of the quote generator, including a container for the quote and a button to fetch a new quote.

#### CSS (`style.css`)

The CSS file ensures the app has a clean and modern look. It styles the quote display area, button, and overall layout.

#### JavaScript (`scripts.js`)

The JavaScript file implements the core functionality of the app. Key functions and features include:

- **Event Listeners**: Handling user interactions such as clicking the button.
- **API Fetching**:
  - **getQuote()**: Fetches a random quote from an external API and updates the DOM with the fetched quote.

### Detailed Explanation

#### API Integration
The `getQuote()` function is responsible for fetching quotes from an external API. Here's how it works:

1. **Fetch Request**: Sends a GET request to the API endpoint.
2. **Process Response**: Parses the JSON response to extract the quote.
3. **Update DOM**: Updates the HTML to display the fetched quote.

## Responsive Design

The app is designed to be fully responsive, ensuring it works seamlessly on various devices, including desktops, tablets, and mobile phones. The use of CSS Flexbox and media queries ensures that the layout adjusts appropriately to different screen sizes.

## Academic Insights

This project demonstrates key concepts in web development, including API integration, DOM manipulation, and responsive design. It serves as a practical example for computer science students to understand how front-end technologies can be integrated to create functional web applications. Through this project, students can learn:

- **HTML5**: Structuring web content.
- **CSS3**: Styling web pages.
- **JavaScript**: Adding interactivity and handling data.
- **API Integration**: Fetching and displaying data from external sources.
- **Responsive Design**: Ensuring usability across different devices.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/Qyuzet/js-quote-generator/blob/main/LICENSE) file for details.

## Contact

For any questions or suggestions, please contact Riki Awal Syahputra at [riqyuzet@gmail.com](mailto:riqyuzet@gmail.com).

## Live Demo

You can try the app live at [JS Quote Generator Demo](https://qyuzet.github.io/js-quote-generator/).

For more details and to view the code, visit the [GitHub repository](https://github.com/Qyuzet/js-quote-generator).
