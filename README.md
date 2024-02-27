# dv-v1

# Text Recognition Project

This project aims to develop a simple text recognition program that takes a JPG photo containing text, displays the image with highlighted text on the screen, and allows the user to copy the recognized text to the clipboard for further use.

## Prerequisites

Before you begin, make sure you have the following dependencies installed on your system:

- OpenCV
- Tesseract
- C++ compiler (e.g., g++)

## Building the Project

1. Clone the project repository:

   ```bash
   git clone https://github.com/alex-anokhin/dv-v1.git
   cd dv-v1

2. Create a libs directory and place the compiled libraries (OpenCV and Tesseract) inside it.

3. Build the project using CMake:
   
   ```bash
   cmake .
   make

## Running the Program

4. Run the compiled executable:
  ```bash
./text_recognition
    
```
## Usage

- Modify the path to your JPG photo in the main.c file.
- Customize the project according to your specific requirements.
  
## Contributing

If you'd like to contribute to this project, please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.
