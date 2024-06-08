# RSA Encryption Program for CSPB 2824 (Discrete Structures)

## Overview

This project was the finished product for my CSPB 2824 class project at CU Boulder. This is an RSA encryption project written in Python. The code will select prime numbers for you, generate keys, and encrypt/decrypt messages. Additionally, there is a code-breaking function that allows you to attempt to decrypt an RSA encrypted message using only the public key.

## Features

- **Prime Number Selection:** Automatically selects prime numbers.
- **Key Generation:** Generates public and private keys for encryption and decryption.
- **Message Encryption/Decryption:** Encrypts and decrypts messages using RSA.
- **Code Breaking Function:** Attempts to decrypt an RSA encrypted message using only the public key.

## Requirements

Before you begin, ensure you have met the following requirements:
- You have installed the latest version of Python.
- You have installed JupyterLab for running the notebook.
- You have installed the `pyfiglet` module.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repo.git
   ```
2. Navigate to the project directory:
   ```sh
   cd your-repo
   ```
3. Install the required module:
   ```sh
   pip install pyfiglet
   ```

## Usage

To run this program, follow these steps:

1. **Open JupyterLab:**

   Start JupyterLab from your terminal:
   ```sh
   jupyter lab
   ```

2. **Open the Notebook:**

   Navigate to the project directory in JupyterLab and open `2824-RSA-Project.ipynb`.

3. **Run the Notebook:**

   Run all the cells in the notebook to execute the program.

## Example

Here's a brief example of how to use the program within the notebook:

1. **Convert Text to Integer List:**
   ```python
   def Convert_Text(_string):
       integer_list = []
       for c in _string:
           integer_list.append(ord(c))
       return integer_list
   ```

2. **Generate Keys and Encrypt Message:**
   ```python
   # Code to generate keys and encrypt message
   ```

3. **Decrypt Message:**
   ```python
   # Code to decrypt message
   ```
