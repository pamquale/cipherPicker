# Encryption and Decryption Application

This project is an interactive application for encrypting and decrypting text using various algorithms. It uses an object-oriented approach in Python and provides a user-friendly interface with `ipywidgets`.

## Features

- **Encryption and Decryption**: Supports multiple encryption and decryption algorithms.
- **Interactive Interface**: Uses `ipywidgets` for a dynamic user interface.
- **Algorithm Selection**: Choose from different encryption algorithms.
- **Key Selection**: Specify encryption/decryption keys.
- **Save Results**: Save encrypted and decrypted text to a file.

## Algorithms Implemented

- **Caesar Cipher**
- **Base64 Encoding**

## Prerequisites

- Python 3.x
- `ipywidgets` library

You can install `ipywidgets` using pip:
```bash
pip install ipywidgets
```

## Usage

### Step 1: Define Encryption Classes

The base class `Cipher` and subclasses for specific algorithms like `CaesarCipher` and `Base64Cipher` are defined. These classes include methods for encryption and decryption.

### Step 2: Create the Interactive Interface

The `EncryptionApp` class sets up the user interface using `ipywidgets`. The interface includes text boxes for input, dropdowns for algorithm selection, and buttons for encrypting, decrypting, and saving results.

### Step 3: Run the Application



### Running the Code

1. **Set up your environment**: Make sure you have Python and `ipywidgets` installed.
2. **Run the code**: Execute the code in a Jupyter Notebook.
3. **Use the interface**: Enter text, select an algorithm, input a key, and click the buttons to encrypt, decrypt, and save results.
