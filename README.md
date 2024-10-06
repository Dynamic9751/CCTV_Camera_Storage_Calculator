# Vohala_CCTV_Camera_Storage_Calculator


This is a simple web-based tool that calculates the required storage space for CCTV camera recordings based on several parameters such as:

    Number of cameras
    Days of recording
    Resolution
    Frames per second (FPS)
    Compression type

Features

    Input Fields: Allows users to input the number of cameras, days of recording, and select various settings such as resolution, FPS, and compression.
    Instant Calculation: Displays the total storage required in GB based on the provided inputs.
    Supports popular video resolutions: 720p, 1080p, and 4K.
    Frame rate options: 15 fps, 30 fps, and 60 fps.
    Compression options: H.264, H.265 (HEVC), and MJPEG.

Usage

To use this calculator:

    Clone the repository or download the project files.
    Open the index.html file in any modern web browser.
    Enter the required values for the number of cameras, days of recording, resolution, FPS, and compression type.
    Click the 'Calculate Storage' button, and the result will be displayed on the page.

Example

For example, with the following inputs:

    4 cameras
    7 days of recording
    Resolution: 1080p
    30 FPS
    Compression: H.264

The calculator will estimate the total storage required based on the input values.
Code Explanation
HTML

The HTML file provides the structure of the page, including the input fields for the user to enter the necessary information. It's styled with basic CSS for a clean, modern interface.
CSS

The CSS file handles the visual styling of the application:

    Responsive layout for all screen sizes.
    Clear and readable typography with a focus on user experience.

JavaScript

The JavaScript handles the logic for calculating the required storage. The calculation depends on several factors such as resolution, FPS, and compression. Once the 'Calculate Storage' button is clicked, it computes and displays the result dynamically.
Storage Calculation Formula

The required storage is calculated using the formula:
Storage (GB)=Bitrate×3600×Hours per Day×Number of Cameras×Number of Days8×1024
Storage (GB)=8×1024Bitrate×3600×Hours per Day×Number of Cameras×Number of Days​

    Bitrate: Derived from the resolution and FPS.
    Compression: Adjusts the bitrate based on the chosen compression type.

Contributing

We welcome contributions! If you'd like to make improvements:

    Fork the repository.
    Make your changes.
    Submit a pull request.

Your contributions will be reviewed and considered for inclusion in the project.
