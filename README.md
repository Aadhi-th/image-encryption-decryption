
# Image Encryption & Decryption Tool 🔒🖼️

This is a Python-based application with a graphical interface for encrypting and decrypting images using a numeric key. The application ensures secure and user-friendly handling of sensitive images, leveraging a simple XOR-based encryption method.

---

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [How to Use](#how-to-use)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
  

---

## Features

🔒 **Encrypt Images**: Secure your images with a numeric key. Encrypted files are saved with a `.enc` extension.

🖼️ **Decrypt Files**: Recover original images from `.enc` files using the same key used during encryption.

📋 **User-Friendly Interface**: Intuitive GUI to easily select files, set keys, and perform encryption or decryption.

🎨 **Interactive Design**: A visually appealing and responsive interface created with `Tkinter`.

⚡ **Error Handling**: Includes robust error handling to ensure smooth user experience.

---

## Technologies Used

- **Python**: Core language for application logic and GUI development.
- **Tkinter**: Provides the graphical user interface.
- **Pillow (PIL)**: Handles image file operations.

---

## Installation

To run the application locally, follow these steps:

1. **Clone this repository**:
   ```bash
   git clone https://github.com/<your-username>/image-encryption-tool.git
   cd image-encryption-tool
   ```

2. **Install dependencies**:
   ```bash
   pip install pillow
   ```

3. **Run the application**:
   ```bash
   python app.py
   ```

---

## How to Use

1. **Launch the application**:
   Run the `app.py` script to start the GUI.

2. **Encrypt an Image**:
   - Click **Select Image** and choose an image file (`.png`, `.jpg`, or `.jpeg`).
   - Enter a numeric key in the text box.
   - Click **Encrypt Image** to create an encrypted `.enc` file.

3. **Decrypt a File**:
   - Click **Select Encrypted File** and choose a `.enc` file.
   - Enter the numeric key used during encryption.
   - Click **Decrypt File** to recover the original image.

4. **Ensure Key Consistency**:
   Use the same key for encryption and decryption to avoid errors.

---

## Future Enhancements

✨ **Advanced Encryption**: Implement AES or RSA encryption for enhanced security.

🌐 **Cross-Platform Executable**: Package the application for Windows, macOS, and Linux.

📁 **Batch Processing**: Allow users to encrypt/decrypt multiple files simultaneously.

📊 **Encryption Analytics**: Provide visual feedback on file size and processing time.

---

## Contributing

Contributions are welcome! To contribute:

1. Fork this repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push your branch:
   ```bash
   git push origin feature-branch
   ```
5. Submit a pull request.



## Author

- **ADITH A K**
- GitHub: [Aadhi-th](https://github.com/your-username)
- Email: adithak18@gmail.com


## Screenshots

> Add screenshots showcasing the interface, encryption, and decryption results.

- **Main Interface**:
  ![Main Interface](screenshot_ma![Screenshot 2024-11-21 164904](https://github.com/user-attachments/assets/1089e62f-571c-4c49-be9f-0f7a47ea0aa3)
in_interface.png)

- **Encryption Success**:
  ![Encryption Success](screens![Screenshot 2024-11-21 164657](https://github.com/user-attachments/assets/e72114f0-3fbc-4388-9cfc-dff1cbdfd9cd)
hot_encryption_success.pn)

- **Decryption Success**:
  ![Decryption Success](screenshot_d![Screenshot 2024-11-21 164630](https://github.com/user-attachments/assets/1ff005d4-2688-4d2d-bba2-35e6148f6930)
ecryption_success.png)
``` 

Feel free to customize the **Author**, **GitHub**, and **Email** sections with your details and add screenshots for better visualization!
