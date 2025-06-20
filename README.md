🕵️‍♀️ LSB Image Steganography Using Python

This project demonstrates how to hide and extract secret messages inside grayscale images using the **Least Significant Bit (LSB)** steganography technique with Python.

---

📌 Features

- 🔒 Hide any text message in an image using LSB technique
- 🖼️ Supports grayscale `.png` or `.bmp` images
- 🧪 Extracts hidden messages accurately from stego-images
- 🐍 Implemented in Python using OpenCV, NumPy, and Pillow
- 💡 Includes a clean and tested Jupyter Notebook

---

🚀 How to Use

🔧 1. Install Required Libraries

Run this in your terminal or Colab:

//bash
pip install opencv-python numpy pillow matplotlib

2️⃣ Run the Code
Open stego.ipynb in Jupyter Notebook or Google Colab and follow the instructions inside:

Upload a grayscale image

Enter the secret message

Run the LSB encoding cell

Extract the message using the decoder cell

🧠 How LSB Steganography Works
Each pixel in a grayscale image is made up of 8 bits.
This technique replaces the least significant bit (LSB) of each pixel with bits from the secret message.
The visual change is imperceptible to the human eye, making the message hidden in plain sight.

🧪 Sample Output
Original message: Hello, LSB!

Input image: sample_input.png

Stego-image: output_image.png

Extracted message: Hello, LSB!

📚 References
Johnson, N. F., & Jajodia, S. (1998). Exploring steganography: Seeing the unseen. IEEE Computer, 31(2), 26–34. https://doi.org/10.1109/2.658917

Krenn, R. (2004). Steganography and steganalysis. Retrieved from: http://www.krenn.nl/univ/cry/steg/article.pdf

Provos, N., & Honeyman, P. (2003). Hide and seek: An introduction to steganography. IEEE Security & Privacy, 1(3), 32–44.

Python Software Foundation. (n.d.). *Python Documentation*. https://www.python.org/doc/

OpenCV.org. (n.d.). *Open Source Computer Vision Library*. https://opencv.org/

NumPy Developers. (n.d.). *NumPy Documentation*. https://numpy.org/


🙋‍♀️ Author
Divyadharshini D

B.E. Computer Science and Engineering – Cyber Security

Sri Sairam Institute of Technology


