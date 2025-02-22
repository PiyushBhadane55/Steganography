**Image Steganography Using Tkinter and OpenCV**

**Overview**
This project implements image steganography using Tkinter for the GUI and OpenCV for image processing. It allows users to hide and retrieve secret messages within an image using a passcode-based encryption system.

**Features**
1)Passcode-Based Encryption – Adds security to hidden messages.
2)Pixel-Based Encoding – Hides text within the BGR channels of an image.
3)User-Friendly GUI – Built with Tkinter for easy interaction.
4)Multi-Channel Steganography – Distributes data across different color channels.
5)Cross-Platform Compatibility – Works on Windows, Linux, and macOS.
6)Error Handling & Validation – Ensures correct encryption/decryption processes.


**Project Preview**



**Installation & Requirements**

**Dependencies**
Make sure you have the following installed:
1)Python 3.x
2)OpenCV (cv2)
3)Tkinter (Included with Python)

**Installation Steps**
1)Clone this repository:
2)Install dependencies:
  pip install opencv-python
3)Run the program:
  python main.py

**Usage**

**Encryption (Hiding Text in an Image)**
1)Load a cover image.
2)Enter a secret message.
3)Set a passcode for encryption.
4)Click "Encrypt" to generate an encrypted image.

**Decryption (Extracting Hidden Text)**
1)Load the encrypted image.
2)Enter the correct passcode.
3)Provide the expected message length.
4)Click "Decrypt" to reveal the hidden text.


**Future Enhancements**
1)Stronger Encryption (AES/RSA integration)
2)Support for Other File Types (audio, video, PDFs)
3)AI-Based Optimization (reduce distortion)
4)Mobile Application (Android/iOS version)
  
