# Captcha Solver Frontend

A simple, responsive web application designed to display captcha images and allow users to input their solutions. This project serves as a frontend interface for interacting with captcha challenges, featuring dynamic image loading and a clean user experience powered by Tailwind CSS.

## Features

-   **Dynamic Image Loading**: Automatically loads captcha images from a `url` query parameter.
-   **Default Image**: If no URL parameter is provided, it defaults to displaying `sample.png` (provided in the same directory).
-   **User Input**: Provides a dedicated input field for users to type their captcha solution.
-   **Responsive Design**: Built with Tailwind CSS, ensuring a consistent and user-friendly experience across various device sizes.
-   **Submission Interface**: A button to submit the entered solution. (Note: Actual captcha verification logic is not implemented in this frontend-only application.)

## Usage

To use this application, simply open the `index.html` file in your web browser.

-   **Default Display**: Upon opening `index.html` without any query parameters, the application will display the `sample.png` image.
-   **Load Custom Captcha**: To display a specific captcha image from a URL, append a `?url=` query parameter to the `index.html` path.
    -   **Example**: `file:///path/to/your/project/index.html?url=https://example.com/path/to/your/captcha.png`
    -   Replace `https://example.com/path/to/your/captcha.png` with the actual URL of the captcha image you wish to display.

## Development

This is a single-file HTML application. No build steps are required. Just open `index.html` in any modern web browser.

## License

This project is open-sourced under the MIT License. See the [LICENSE](LICENSE) file for more details.