# QR Code Generator and Scanner GUI App

This Python application provides a user-friendly GUI for generating and scanning QR codes using the tkinter library. It allows users to:

🔹 Generate a QR code from any text input and save it as a PNG image.

🔹 Scan an existing QR code from an image and decode the embedded data.

## Key Technologies Used:
tkinter – for building the graphical user interface.

pyqrcode – to generate QR codes.

pyzbar – to decode and read QR codes from images.

Pillow – for image handling and display in the GUI.

## Features:
Tabbed Interface using ttk.Notebook:

One tab for generating QR codes from text.

Another tab for scanning and decoding QR codes from images.

Custom Styling for a modern look.

Preview of QR Image in both generate and scan tabs.

Safe file selection using the file dialog.

