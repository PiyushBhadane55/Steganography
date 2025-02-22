**Image Steganography Using Tkinter and OpenCV**<br>

**Overview**<br>
This project implements image steganography using Tkinter for the GUI and OpenCV for image processing. It allows users to hide and retrieve secret messages within an image using a passcode-based encryption system.

**Features**<br>
1)Passcode-Based Encryption – Adds security to hidden messages.<br>
2)Pixel-Based Encoding – Hides text within the BGR channels of an image.<br>
3)User-Friendly GUI – Built with Tkinter for easy interaction.<br>
4)Multi-Channel Steganography – Distributes data across different color channels.<br>
5)Cross-Platform Compatibility – Works on Windows, Linux, and macOS.<br>
6)Error Handling & Validation – Ensures correct encryption/decryption processes.<br>


**Project Preview**<br>
![1](https://github.com/user-attachments/assets/c26ad1d8-f48c-4ccd-9683-4b39981256a4)





**Installation & Requirements**<br>

**Dependencies**<br>
Make sure you have the following installed:<br>
1)Python 3.x<br>
2)OpenCV (cv2)<br>
3)Tkinter (Included with Python)<br>

**Installation Steps**<br>
1)Clone this repository:<br>
  https://github.com/PiyushBhadane55/Steganography.git<br>
2)Install dependencies:<br>
  pip install opencv-python<br>
3)Run the program:<br>
  python main.py<br>

**Usage**<br>

**Encryption (Hiding Text in an Image)**<br>
1)Load a cover image.<br>
2)Enter a secret message.<br>
3)Set a passcode for encryption.<br>
4)Click "Encrypt" to generate an encrypted image.<br>

**Decryption (Extracting Hidden Text)**<br>
1)Load the encrypted image.<br>
2)Enter the correct passcode.<br>
3)Provide the expected message length.<br>
4)Click "Decrypt" to reveal the hidden text.<br>


**Future Enhancements**<br>
1)Stronger Encryption (AES/RSA integration)<br>
2)Support for Other File Types (audio, video, PDFs)<br>
3)AI-Based Optimization (reduce distortion)<br>
4)Mobile Application (Android/iOS version)<br>
  
