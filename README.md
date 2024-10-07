# Screenshots to PDF Converter

This Python project, designed to be used in Google Colab, converts multiple screenshot images into a single PDF document. It is intended to work with screenshots captured with the Chrome extension "Instant Screenshot". Users can upload multiple PNG files, which the program then sorts based on the timestamps in their filenames. These sorted images are combined into a single PDF, which is automatically generated and downloaded.

## Features

- **File Upload**: Upload PNG screenshots directly from your computer.
- **Automatic Sorting**: The files are sorted by their timestamp (`screenshot_${timestamp}.png`) to maintain the correct order.
- **PDF Generation**: Combines all uploaded screenshots into a single PDF document.
- **Automatic Download**: The generated PDF is automatically downloaded to your local machine.


## Requirements

- [Google Colab](https://colab.research.google.com/)
- Pillow - Python Imaging Library (PIL)
- Python Standard Libraries:
  - `os`
  - `datetime`


## How to Use

1. Use the **Instant Screenshot** Chrome extension to take your screenshots.
2. Open the Google Colab notebook.
3. Run the notebook
4. Upload your PNG screenshots.
5. The PDF will be generated and downloaded.


## License

This project is licensed under the MIT License.
