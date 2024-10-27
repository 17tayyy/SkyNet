# Skynet

![Captura de pantalla 2024-10-27 195536](https://github.com/user-attachments/assets/ebcf10d6-743e-4b66-ba9b-f0196d95becd)


**Skynet** is a powerful Command and Control (C2) framework designed for interacting with and managing multiple devices remotely through a backdoor. This software allows for command execution, file transfer, and capturing screenshots and webcam images from the victim's machine. Its functionality includes persistence, ensuring that the backdoor remains active even after reboots.

## Features

- **Persistence**: The backdoor is configured to automatically start upon system boot, ensuring its presence on every startup.
- **Remote Interaction**: Provides a command-line interface that allows operators to effectively interact with the victim's system.

## Requirements

To run Skynet, make sure you have the following Python libraries installed:

```bash
pip install mss opencv-python
```

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your_username/skynet.git
   cd skynet
   ```

2. **Run the C2 server**:

   ```bash
   python server.py
   ```

3. **Compile the backdoor (optional)**:

   To compile the backdoor into a `.exe` executable, use `PyInstaller`:

   ```bash
   pyinstaller --onefile --noconsole backdoor.py
   ```

## Disclaimer 

I will be doing updates adding more cool **features**

## Warning

**Skynet** is a powerful tool and should be used ethically and legally. Unauthorized use on systems you do not own is illegal and could lead to legal consequences. Use this tool only on systems you own or in controlled testing environments.
