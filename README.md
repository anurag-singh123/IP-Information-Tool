# IP-Information-Tool

**A simple Python-based tool with a graphical user interface (GUI) that allows you to retrieve detailed information about a given IP address using the `ipinfo.io` API.**

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This tool is designed to make it easier for users to quickly retrieve and display information about an IP address using a user-friendly graphical interface. It provides information such as the city, region, country, coordinates, organization, and more, all in a clean and responsive GUI built with `tkinter`.

## Features
- **GUI Interface**: Built using `tkinter` for a simple, responsive interface.
- **IP Information**: Retrieves IP address information such as:
  - City, region, and country
  - Geographic coordinates (latitude and longitude)
  - Organization
  - Postal code
  - Hostname
- **Clear Interface**: The tool includes a "Clear" button to reset the input and output.
- **Error Handling**: Displays error messages for invalid input or connection issues.
- **Scrollable Text**: Results are shown in a scrollable text area for easy readability.

## Requirements
- **Python 3.x** installed on your machine.
- Python libraries:
  - `requests`
  - `tkinter` (pre-installed with Python)

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/ip-information-tool.git
    cd ip-information-tool
    ```

2. **Install Dependencies**:
   Install the `requests` library using pip (if not already installed):
   ```bash
   pip install requests
   ```

## Usage

1. **Run the Application**:
   ```bash
   python IPInformationTool.py
   ```

2. **Enter an IP Address**:
   - Input the IP address you want to check in the provided field.
   - Click the **"Get IP Info"** button to fetch and display the information.

3. **Clear the Output**:
   - You can click the **"Clear"** button to reset both the input field and the displayed results.

## Screenshots
**IP Info Tool GUI Screenshot**
![Screenshot 2024-10-19 180319](https://github.com/user-attachments/assets/45aef57b-77ec-48ea-8297-ff09dfda7e1c)


## Customization
- **Change the API**: By default, this tool uses the `ipinfo.io` API. If you want to use a different API, update the `get_ip_info` function in `IPInformationTool.py` with the relevant API URL and data parsing logic.
- **Styling**: The tool’s appearance can be customized by tweaking the `tkinter` styles (colors, fonts, etc.) within the script.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](license) file for details.
