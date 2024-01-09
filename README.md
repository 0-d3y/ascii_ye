![Logi](https://raw.githubusercontent.com/mr-sami-x/ascii_ye/main/logo.png)

# ASCII YE

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/python-3.6%2B-blue.svg)](https://www.python.org/downloads/release)
[![GitHub issues](https://img.shields.io/github/issues/mr-sami-x/sami_ai)](https://github.com/mr-sami-x/sami_ai/issues)
[![GitHub stars](https://img.shields.io/github/stars/mr-sami-x/sami_ai)](https://github.com/mr-sami-x/sami_ai/stargazers)

## Overview

ASCII_YE ​​is a library that encodes text with the ASCII type, a digital encoding used to encrypt data when making requests over the Internet.

## Features

- Encrypting software scripts
- Encrypt text data
- Plain text encryption
 

## Installation

You can install ascii_ye using pip:

```
pip install ascii-ye 
```

## Example:
```
from ascii_ye import ASCII_YE

original_text = "Hello, ASCII Encryption! By SaMi_ye"
encryptor = ASCII_YE()

encrypted_text = encryptor.encrypt(original_text)
decrypted_text = encryptor.decrypt(encrypted_text)

print("Original Text:", original_text)
print("Encrypted Text:", encrypted_text)
print("Decrypted Text:", decrypted_text)


```
