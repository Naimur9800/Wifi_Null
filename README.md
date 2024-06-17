**Wifi_Null** is a sophisticated tool designed for Wi-Fi security testing. This script enables users to perform various actions related to wireless networks, including monitoring and exploiting vulnerabilities.

## Features

- Automated Wi-Fi network scanning
- WPS vulnerability testing using Pixie Dust attacks
- Integration with `wpa_supplicant` for robust Wi-Fi management
- User-friendly command-line interface

## Prerequisites

Ensure the following dependencies are installed before proceeding:

- Git
- Tsu
- Python
- Wpa-supplicant
- Pixiewps
- Iw

## Installation

To install Wifi_Null, please follow the steps outlined below:

1. **Update package lists and upgrade installed packages:**
    ```sh
    apt update && apt upgrade
    ```

2. **Install the `root-repo` package:**
    ```sh
    pkg install -y root-repo
    ```

3. **Install the required dependencies:**
    ```sh
    pkg install -y git tsu python wpa-supplicant pixiewps iw
    ```

4. **Clone the Wifi_Null repository:**
    ```sh
    git clone https://github.com/Naimur9800/Wifi_Null
    ```

5. **Navigate to the Wifi_Null directory:**
    ```sh
    cd Wifi_Null
    ```

6. **Make the script executable:**
    ```sh
    chmod +x Naimur.py
    ```

## Usage

To execute the Wifi_Null script, please follow these steps:

1. **Navigate to your home directory:**
    ```sh
    cd ~
    ```

2. **Run the script with `sudo` privileges:**
    ```sh
    sudo python Wifi_Null/Naimur.py -i wlan0 -K
    ```

## Contribution Guidelines

We welcome contributions from the community. To contribute to Wifi_Null, please adhere to the following steps:

1. Fork the repository.
2. Create a new branch.
3. Implement your changes and commit them.
4. Push your changes to the branch.
5. Submit a pull request for review.

## License

This project is licensed under the MIT License. For more information, please refer to the [LICENSE](LICENSE) file.

## Acknowledgements

We extend our gratitude to the developers and the open-source community for their invaluable tools and resources that made this project possible.

---
