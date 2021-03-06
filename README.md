# QR Code Encryption in Python

This python script was developed as a part to the project for the IGEM (international Genetic Enegineered Machines) competition by team Groningen 2019.

<p align="center">
  <img src="https://raw.githubusercontent.com/M-P-P-C/QR-Code-Encryption/master/Example_QRcode_encrypted.png" width="100">
</p>

The goal of the script is to develop QR codes with AES encrypted messages and be able to decrypt them.

Encryption of a message will output a 3D version of the QR code to be 3D printed, or in PNG format.

The extruded version (3D file) is achieved by extruding the png version using the numpy2stl script

<b>HOW TO RUN:</b>
- in the downloaded folder run the command "pip install -r requirements.txt" to install all requirements
- run python script "main.py" and follow instructions in command line
- The final QR code files are outputted in the same folder as the python script

An Example of the prompts given by the main script:
<p align="center">
  <img src="https://raw.githubusercontent.com/M-P-P-C/QR-Code-Encryption/master/Example_outputs/tempsnip.png" width="600">
</p>
