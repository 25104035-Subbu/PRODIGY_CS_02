# PRODIGY_CS_02
Image encryption tool using pixel manipulation | Prodigy InfoTech Cyber Security Internship Task 02
Overview
This project is a simple Image Encryption Tool developed using Python. It encrypts and decrypts images by modifying pixel RGB values using a secret key.
Features
Select image from computer
Encrypt image using a secret key
Decrypt image using the same key
Simple GUI using Tkinter
Image preview support
How It Works
Each image contains pixels with RGB (Red, Green, Blue) values ranging from 0 to 255.
Encryption
Adds the secret key to each RGB value.
Decryption
Subtracts the same key from each RGB value to restore the original image.
Example:
Original Pixel:
Plain text
(100, 150, 200)
Key:
Plain text
66
Encrypted Pixel:
Plain text
(166,216,266)
Decrypted Pixel:
Plain text
(100, 150, 200)
Technologies Used
Python 3
Tkinter
Pillow (PIL)
Installation
Install Pillow:
Bash
pip install Pillow
How to Run
Open the project file.
Run the Python script.
Click Browse Image and select an image.
Enter a secret key.
Click Encrypt Image or Decrypt Image.
The processed image will be saved.
Project Functions
browse_file()
Selects an image from the system.
show_preview()
Displays image preview in the GUI.
process_image(mode)
Encrypts or decrypts the image based on the selected mode.
