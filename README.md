````markdown
# 🔐 Color Code Cryptography & Image Steganography

A web-based cryptography project that provides two different ways to protect secret messages:

1. **Color Code Cryptography** — converts messages into hexadecimal color codes using a secret key.
2. **Image Steganography** — hides encrypted messages inside images and allows them to be revealed later.

## ✨ Features

### 🎨 Color Code Cryptography

- Encrypt text into HEX color codes
- Decrypt HEX color codes back into text
- Secret-key-based color mapping
- Copy encrypted color codes
- Deterministic encryption and decryption

### 🖼️ Image Steganography

- Hide secret messages inside images
- Support PNG and JPEG images
- Use a secret key for encryption
- Generate a stego-image
- Download the generated image
- Generate a separate key file
- Reveal hidden messages from stego-images

## 🧠 How It Works

### Color Encryption

```text
Secret Message
      ↓
Secret Key
      ↓
Generate Color Mapping
      ↓
Convert Characters → HEX Colors
      ↓
Encrypted Color Codes
````

### Image Steganography

```text
Secret Message
      ↓
Encryption + Secret Key
      ↓
Hide Data Inside Image
      ↓
Stego Image + Key File
      ↓
Reveal Using Key
      ↓
Original Message
```

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* Tailwind CSS
* HTML Canvas API

## 🔑 Cryptography Approach

The application generates a deterministic color mapping from a user-provided secret key.

A seeded pseudo-random generator is used to create color values for byte values from `0–255`.

```text
Secret Key
    ↓
Seeded Random Generator
    ↓
256 Color Mapping
    ↓
Character → Color
```

The same secret key is required to reconstruct the mapping and decrypt the message.

## 🖼️ Steganography

The project also demonstrates **image steganography**, where information is hidden inside an image so that the message is not directly visible.

The application uses the browser's **Canvas API** to process image data and create a new image containing the hidden information.

The generated files can include:

* Stego-image
* Key file

These can later be used to recover the hidden message.

## 📁 Project Structure

```text
Color-Cryptography-Steganography/
│
├── index.html
└── README.md
```

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Gautambisht98/color-coding.git
```

### 2. Open the Project

```bash
cd color-coding
```

### 3. Run the Application

Open:

```text
index.html
```

in a modern web browser.

You can also use **Visual Studio Code + Live Server**.

## 🎯 Project Objectives

The main objectives of this project are to:

* Demonstrate basic cryptography concepts
* Explore key-based data transformation
* Convert encrypted information into color representations
* Demonstrate image steganography
* Understand how data can be hidden inside digital images
* Build an interactive browser-based security application

## 📚 Learning Outcomes

This project demonstrates practical understanding of:

* Cryptography
* Steganography
* Secret-key-based encoding
* Data transformation
* Hexadecimal color representation
* JavaScript
* Canvas API
* Image processing
* File handling in the browser
* Front-end web development

## ⚠️ Limitations

* This project is primarily designed for educational purposes.
* The color-based encryption scheme is a custom demonstration and should not be considered a replacement for modern cryptographic standards.
* The security of the system depends on the secrecy and strength of the key.
* Browser-based image processing may have limitations with very large images.
* Do not use this project to protect highly sensitive information in real-world applications.

## 🔒 Security Disclaimer

This project is intended for **educational and cybersecurity learning purposes**.

It demonstrates cryptography and steganography concepts and should not be considered a production-grade secure communication system.

Do not use it to protect passwords, financial information, medical data, or other highly sensitive information.

## 🔮 Future Improvements

Possible future improvements include:

* AES-based encryption
* Stronger key derivation
* Password-based encryption
* Improved steganography techniques
* Better image compression handling
* Drag-and-drop image support
* Multiple image formats
* Encryption strength analysis
* File encryption support
* Improved error detection
* Mobile optimization

## 👨‍💻 Author

**Gautam Bisht**

GitHub: [@Gautambisht98](https://github.com/Gautambisht98)

## ⭐ Support

If you found this project useful for learning **cryptography and steganography**, consider giving the repository a ⭐.

```
```
