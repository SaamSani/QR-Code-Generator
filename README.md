
# QR Code Generator 📱

A simple Node.js application that generates QR codes from user-provided URLs. The app also saves the URL to a text file for reference.

## How It Works

- Users are prompted to enter a URL.
- The app generates a QR code for the URL and saves it as `qr_img.png`.
- The entered URL is stored in `URL.txt`.

## Project Files

- **`index.js`**: The main application logic.
- **`package.json`**: Project metadata and dependencies.
- **`package-lock.json`**: Locks the dependency tree.
- **`qr_img.png`**: The generated QR code image.
- **`URL.txt`**: Stores the entered URL.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/SaamSani/QR-Code-Generator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd QR-Code-Generator
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Run the application:
   ```bash
   node index.js
   ```
5. Enter the URL when prompted. The QR code and URL will be saved in the project directory.

---

Feel free to improve or expand the project to meet your needs!
