# Prizcreen - A GUI for Scrcpy

**Prizcreen** is a graphical interface for [scrcpy](https://github.com/Genymobile/scrcpy), allowing you to control and mirror Android devices to your desktop with ease. With a sleek and intuitive interface, Prizcreen simplifies the process of mirroring and interacting with your Android device, offering the full power of scrcpy without the need for complex terminal commands.

## Features

- **User-Friendly Interface**: Control and mirror your Android device from your desktop using an intuitive GUI.
- **Wireless and Wired Connection**: Connect to Android devices via USB or Wi-Fi.
- **Screen Mirroring**: View your Android screen on your desktop in real-time.
- **Control Your Device**: Interact with your Android device directly from your computer using keyboard and mouse.
- **Customizable Settings**: Adjust performance and quality settings for an optimal mirroring experience.
- **Lightweight**: Built to be fast and low on system resources.

## Prerequisites

To run Prizcreen, you'll need:

- **Android device** with Developer Mode and USB debugging enabled.
- **scrcpy**: Prizcreen is a GUI wrapper for [scrcpy](https://github.com/Genymobile/scrcpy). You’ll need to have scrcpy installed. Please follow the installation instructions on the [scrcpy GitHub page](https://github.com/Genymobile/scrcpy) if you haven't already installed it.

## Installation

### 1. Clone the repository:
```bash
git clone https://github.com/rizqijune/prizcreen.git
cd prizcreen
```

### 2. Install Dependencies:
- **For Linux (Ubuntu)**:
    ```bash
    sudo apt update
    sudo apt install python3-pyqt5
    sudo apt install scrcpy
    ```

- **For Windows**: Download and install [scrcpy](https://github.com/Genymobile/scrcpy/releases), [Python](https://www.python.org/downloads/), and [PyQt5](https://riverbankcomputing.com/software/pyqt/download5).

- **For macOS**: 
    ```bash
    brew install scrcpy
    brew install pyqt
    ```

### 3. Run the App:
Once you’ve cloned the repo and installed the dependencies, you can run the app:

```bash
python3 prizcreen.py
```

### 4. Connect Your Device:
- **Wired Connection**: Connect your Android device via USB.
- **Wireless Connection**: Use the device's IP over Wi-Fi (ensure your device and PC are on the same network).

## Usage

1. Open the **Prizcreen** app.
2. Select your connected Android device from the dropdown.
3. Hit the "Start" button to begin mirroring and controlling your Android device from your desktop.
4. Customize the settings based on your preferences, such as screen resolution, bit rate, etc.

## Contributing

Feel free to fork this project and submit pull requests. If you find any issues or want to request a feature, please open an issue in the [GitHub Issues section](https://github.com/rizqijune/prizcreen/issues).

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.
