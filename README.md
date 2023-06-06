README.md

# Celestial Angles Analysis

This project analyzes celestial angles and identifies photogenic moments in space. It uses Python and requires installation of specific packages. Below are the instructions for setting up and running the project locally on both Windows and Linux operating systems.

## Installation

To run this project, you need to have the following packages installed:

- `spiceypy`
- `numpy`
- `pandas`
- `matplotlib`

You can install these packages using `pip`, the Python package installer. Open a terminal or command prompt and run the following command:

```bash
pip install spiceypy numpy pandas matplotlib
```

## Usage

1. Clone or download this repository to your local machine.
2. Open a terminal or command prompt and navigate to the project directory.
3. Ensure that the required packages are installed by running the installation command mentioned above.
4. Run the project by executing the Python script `celestial_angles_analysis.py`. Use the following command:

   ```bash
   python celestial_angles_analysis.py
   ```

   This will compute the celestial angles and generate a plot showing the miscellaneous phase angles.

5. The resulting plot will be saved as `VENUS_SUN_MOON.png` in the project directory.

## Operating System-Specific Instructions

### Windows

- Install Python: Visit the official Python website at https://www.python.org/downloads/ and download the latest version of Python for Windows. Follow the installation instructions to complete the setup.

- Open a command prompt: Press `Win + R`, type `cmd`, and press Enter to open the command prompt.

- Navigate to the project directory: Use the `cd` command to navigate to the directory where you cloned or downloaded the project.

- Follow the "Usage" instructions mentioned above.

### Linux

- Install Python: Most Linux distributions come with Python pre-installed. If not, open a terminal and run the following command:

  ```bash
  sudo apt-get install python3
  ```

- Open a terminal: Use the terminal emulator available on your Linux distribution.

- Navigate to the project directory: Use the `cd` command to navigate to the directory where you cloned or downloaded the project.

- Follow the "Usage" instructions mentioned above.

## Credits

This project utilizes the `spiceypy` package for celestial computations. For more information about `spiceypy`, visit the official documentation at https://spiceypy.readthedocs.io/.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your own purposes.
