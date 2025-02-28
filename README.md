# QR Code Generator

This is a simple web-based QR code generator that allows you to create QR codes from text input and customize their size.

## Features

* **Text Input:** Enter any text you want to encode into a QR code.
* **Size Selection:** Choose from predefined sizes (small, medium, large, or specific pixel dimensions like 100x100, 200x200, etc.).
* **Easy to Use:** A straightforward interface makes it quick to generate QR codes.
* **Default QR Code:** If no text is entered, a default QR code linking to a OneDrive URL will be generated.
* **Uses external API:** Utilizes the tec-it QR code API.

## Usage

1.  **Enter Text:** Type the text you want to convert into a QR code in the text area.
2.  **Select Size:** Choose the desired size from the dropdown menu.
3.  **Generate:** Click the "submit" button to generate the QR code.
4.  **View QR Code:** The generated QR code will be displayed below the button.

## How it Works

The application uses the `qrcode.tec-it.com` API to generate QR codes. The text input and selected size are passed as parameters to the API, and the resulting QR code image is displayed on the page.

## Code Structure

* **HTML:** Provides the structure of the web page, including input elements, a dropdown for size selection, and an image element to display the QR code.
* **CSS:** Styles the page, including the background color, input elements, and text area.
* **JavaScript:** Handles the QR code generation logic. It retrieves the text and size values, constructs the API URL, and updates the image source.

## API Used

* **tec-it QR Code API:** `https://qrcode.tec-it.com/API/QRCode`

## Customization

* You can modify the CSS to change the appearance of the page.
* You can add more size options to the dropdown menu.
* You can change the default QR code URL in the javascript code.
* You can improve the error handling, to better inform users when they enter invalid data.

## Author

* Vempa Surendra DJ\_H

## Example

Here's a screenshot of the application:

(Add a screenshot of your application here if you have one.)

## How to run locally.

1.  Save the code as an HTML file (e.g., `qrcode.html`).
2.  Open the HTML file in your web browser.

## Future Improvements

* Add options to customize the QR code color.
* Implement client-side QR code generation to avoid external API dependencies.
* Add download functionality to save the generated QR code.
* Add error handling for invalid user input.
