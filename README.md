# QR-Code-Generator

## 1. HTML (index.html):
DOCTYPE and HTML tag: Specifies the HTML5 document type and opens the HTML document.
Head section: Contains metadata, including character set, viewport settings, title, and a link to the CSS file.
Body section:
Container div: This div holds the entire content of the page.
Heading (h1): Provides a title for the page, such as "QR Code Generator."
Label and Input: A label instructs the user to enter text, and an input field allows them to input the text.
Button: A button triggers the QR code generation when clicked.
Div for QR code (qrcode): This empty div will display the generated QR code.
## 2. CSS (style.css):
Body styling: Applies a background color and styles to the body for a clean layout.
Container styling: Adds styling to the container div, such as background color, padding, border-radius, and box shadow.
Label and Input styling: Provides spacing and styling for the input label and field.
Button styling: Defines the appearance of the button, including background color, text color, padding, border, border-radius, and a hover effect.
QR Code div styling: Adds margin to the top of the div where the QR code will be displayed.
## 3. JavaScript (script.js):
generateQRCode function: This function is triggered when the button is clicked.
Retrieves the input text from the input field.
Checks if the input is not empty.
If not empty, uses the QRCode library to generate a QR code inside the designated div (qrcode).
If empty, displays an alert asking the user to enter text.
 ## API which i used in this project "https://api.qrserver.com/v1/create-qr-code/?size=150x150&data="
