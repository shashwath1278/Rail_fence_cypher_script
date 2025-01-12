# Rail Fence Cipher Decryption Script

This repository contains a Python script for decrypting messages encoded using the Rail Fence Cipher. The Rail Fence Cipher is a classical transposition cipher that arranges characters in a zigzag pattern based on a specified number of rails. This script takes the ciphertext and the number of rails as input and efficiently reconstructs the original plaintext.

## Features
- Decrypts Rail Fence Cipher texts based on a user-specified number of rails.
- Simulates the zigzag pattern to decode the ciphertext accurately.
- User-friendly interface with simple input prompts.

## Requirements
- **Python 3.x**: Ensure you have Python 3.x installed on your system.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/shashwath1278/Rail_fence_cypher_script.git
   cd Rail_fence_cypher_script
   ```

2. Verify that Python 3.x is installed:
   ```bash
   python3 --version
   ```

3. (Optional) Create a virtual environment to isolate dependencies:
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Linux/macOS
   venv\Scripts\activate    # On Windows
   ```

## Usage
1. Run the script:
   ```bash
   python3 Rail_fence_cypher_script.py
   ```
2. Provide the required inputs when prompted:
   ```plaintext
   Enter the ciphertext: <ciphertext>
   Enter the number of rails: <number_of_rails>
   ```

### Example
For a ciphertext `WECRLTEERDSOEEFEAOCAIVDEN` encrypted with 3 rails:
```plaintext
Enter the ciphertext: WECRLTEERDSOEEFEAOCAIVDEN
Enter the number of rails: 3
Decrypted text: WEAREDISCOVEREDFLEEATONCE
```

## Notes
- The decryption assumes that the Rail Fence Cipher is applied without any additional modifications (e.g., no offset or key shifts).
- Ensure the ciphertext and the number of rails match the encryption parameters.

## Troubleshooting

1. **Incorrect Decryption:**
   Ensure the number of rails provided during decryption matches the number used during encryption.

2. **Python Compatibility:**
   Use Python 3.x to avoid syntax issues.

## Contributing
Feel free to fork this repository and submit pull requests for improvements or additional features. Suggestions and feedback are welcome!
